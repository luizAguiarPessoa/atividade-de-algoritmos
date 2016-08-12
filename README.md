# atividade-de-algoritmos
[filtro] - Atividade p4.26 até p4.34 - aluno

 26:Permite em que uma sequencia de comandos que seja repetida até a condição determinada for satisfeita.
 
 
   
 27:O controle por contador consiste em controlar o número de repetições do laço.
 
   
 
 28:O controle por entrada flag consiste é usado quando não sabemos o número das repetições de um determinado valor.
 
 
 29:Faça o acompanhamento da execução do algoritmo abaixo e preencha a Tabela de Variáveis:
  
 |    TRECHO DE ALGORITMO     |    TABELA DE VARIÁVEIS |
  | | | N | L | N # 6 | Saida | |
  | N fl 0 | |
 | L fl 1 | |
 |      enquanto N # 6 faça   |                        |
  | O fl * G (-1) | |
  | N fl N + 1 | |
 |        se L > 0            |                        |
 |         então escreva N    |                        |
 |    fim-se                  |                        |
 |    fim-enquanto            |                        |
 
 30:
 

 T = eval(input("Digite um valor para N :"))
  Tempo (T <= 50):
  Impressão (N)
  T= T + 1 
 
 31:
   

 T = int(input("Digite o numero 2 :"))
  Tempo (N% 2 == 0) e N <= 100:
  Impressão (T)
  T = T + 2 
 
 32:
 

 T = int(input("Digite o numero 10: ")) 
 Enquanto (T <= 1000):
  Impressão (T)
 	T = T + 10
 
33:
   
 
 T = int(input("Digite um numero inteiro:"))
  Enquanto T> = 1 e T <= 100:
  Impressão (T)
  T = T - 1
 
34:
   
 N = int(input("Digite o valor de N:"))
 TOIS = int(input("Digite um numero :"))
 soma = 1
  Enquanto TOIS <N:
 	soma = TOIS + soma
 	TOIS = TOIS + 1
  Impressão (soma)
