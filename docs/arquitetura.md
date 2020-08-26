# Arquitetura

* As funções relacionadas ao gerenciamento das casa do jogo da velha ficaram no módulo **jogovelha.py**.

* O estado de cada casa do jogo será representada or uma string: "." para casa vazia; "X" para casa ocupada pelo 1o jogador; "O" para casa ocupada pelo 2o jogador.

* A função inicializar () retornará uma lista 3x3, onde cada podição conterá uma string para indicar o estado de uma casa do jogo. A função retornará todas as casas inicialmente vazias.