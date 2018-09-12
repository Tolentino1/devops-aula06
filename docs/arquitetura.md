# Requisitos
* Gerar uma estrutura de dados para manter o estado de cada uma das casas de um jogo da velha.
* Cada casa do jogo da velha poderá estar vazia, ocupada pelo 1º jogador ou ocupada pelo 2º jogador

# Arquitetura

* As funções relacionadas ao ferenciamento das casas do jogo da velha ficarão no módulo **jogovelha.py**.


* O estado de cada casa do jogo será representada por uma string: "." para casa vazia; "X" para casa ocupada pelo 1º jogador; "O" para casa ocupada pelo 2º jogador

* A função inicializar () retornará uma lista 3x3, onde cada posição conterá uma string para indicar o estad de uma casa do jogo. A função retornará todas as casas inicialmente vazias
