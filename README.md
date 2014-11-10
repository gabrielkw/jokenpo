#Jogo Pedra, Papel, Tesoura
Por Gabriel Kwiecinski Antunes

Exercício da disciplina de Circuitos Digitais

Universidade Federal da Fronteira Sul

2014/2

Professor Luciano Lores Caimi

##Regras
O número de participantes é de 2 jogadores.

O vencedor é definido segundo a seguinte regra:

● Pedra vence tesoura, pois amassa a tesoura.

● Tesoura vence papel, pois corta o papel.

● Papel vence pedra, pois embrulha a pedra.

● Toda vez que os dois jogadores optarem pelo mesmo objeto, ocorre um empate.

A jogada de cada jogador é informada através de 2 bits:

● 00 Aguardando entrada

● 01 Pedra

● 10 Papel

● 11 Tesoura

##Interface

A indicação do vencedor (saída do circuito) é composta por 2 sinais assim definidos:

● 11 Empate

● 10 Jogador 1 vence

● 01 Jogador 2 vence

● 00 Entrada Inválida
