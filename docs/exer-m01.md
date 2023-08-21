# Aula sobre Conceitos básicos

1. Escreva um script python que define duas variáveis do tipo inteiro (__int__)
e atribui um valor positivo para elas. Imprima as duas variáveis.

def main():
    x = 2
    y = 3

    print(x,y)

if __name__ == "__main__":
  main()


3. Seja x = 2 + 4j, descubra qual é tipo associado a essa variável pelo interpretador.
tipo "complex"

   
5. Experimente a inicialização de variáveis como segue:
   1. urnas = {}
   2. sessao = {"escola municipal", 103}

   descubra qual é o tipo da variável __urnas__ e da variável __sessao__. Explique se necessário
a razão dos tipos serem distintos.
   __urnas__ tipo <class 'dict'> porque está sendo associado um dicionario
   __sessao__ tipo <class 'set'> porque está sendo associado um conjunto de elementos unicos e nâo ordenados
   
7. Nas definições de nomes de variáveis abaixo quais têm nomes válidos e quais são invalidos
    1. ola = "mundo"  - válido
    2. _ola = "mundo" - válido 
    3. _1_ola = "mundo" - válido
    4. 1_ola = "mundo" - inválido - começa com número
    5. ola_1 = "mundo"  - válido
    6. meu mundo = "ola" - inválido  - espaço em branco

aponte as razões para os nomes inválidos, indicando o item e a razão da violação
das regras de nomeação de variável.

5. No seguinte comando de atribuição 
   1. casa, senha = "minha", "ola" - válido   
   2. casa, senha = "minha" - inválido - tenta atribuir 2 valores a uma variável 
   3. casa = "minha"  - válido

Quais foram as atribuições que funcionaram e quais não funcionaram? Explique a razão dos problemas.
   
6. Considere as seguintes operações matemáticas, e indique o resultado de cada uma:
   1. (10 - 6)**2  - (16)
   2. 10 - 6**2  - (-26)
   3. 10 - 3 // 2 - (9)
   4. 10 - 3 / 2 - (8.5)

7. Qual a importância de se criar ambiente virtuais para o desenvolvimentos de projetos usando Python?
    Isolamento de Dependências
    Gerenciamento de Versões
    Ambiente Limpo
    Facilidade de Colaboração
    Experimentação Segura
    Resolução de Conflitos
    Eficiência e Limpeza

9. Descubra e responda qual versão do python está instalado no seu ambiente de desenvolvimento. Que comando você usou 
para obter essa informação?
Python 3.10.12
python3 --version

11. Uma tupla é um tipo imutável, portanto qualquer variável desse tipo pode ser alterada desde que os seus elementos 
sejam individualizados, como no código abaixo:

   __comprado = ("carro", "GM", "20K")__

   __comprado[1] = "Ford"__

   você concorda com essa afirmação? justifique sua resposta.
   O fato das tuplas serem imutáveis está correta, no entanto o codigo apresenta erro, justamente por serem uma tupla e os valores serem imutáveis não é possivél alterar o valor de um elemento individualmente.  

11. Considere o código abaixo:

      __numero = input()__
      
      print(numero*3)
   
      se o valor 3(três) for informado como entrada e armazenado na variável número.
retornará 333 -  irá repetir o valor "3" 3 vezes, pois a entreda será interpretada como string. 

13. Revise o código disponibilizado em src/primeiro.py. Em seguida altere o programa
para que ele se torne generalista, i.e., aceite qualquer quantidade de notas que cada
aluno pode ter. 
