# Arquitetura 

* As fun��es relacionadas ao gerenciamento das casas do 
jogo da velha ficar�o no m�dulo **jogovelha.py**

* O estado de cada casa do jogo ser� representada por uma
string: "." para casa vazia; "X" para casa ocupada pelo 1o 
jogador; "O" para casa ocupada pelo 2o jogador

* A fun��o inicializar() retornar� uma lista 3x3, onde cada 
posi��o conter� uma string para indicar o estado de uma
casa do jogo. A fun��o retornar� todas as casas
inicialmente vazias.