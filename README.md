# Projeto-01-SB
integrantes da equipe:
Fernanda Cordeiro Panzera
Igor Rafael Carvalho Gonçalves
Marco Antônio Oliveira Machado
Rafael Ponciano Vasconcelos Da Silva

 O projeto envolve o desenvolvimento de um jogo em C++. O jogo utiliza o console para o desenvolvimento gráfico e interação com o usuário. O objetivo do jogo é desafiar o jogador a passar de três fases, onde cada um deles terão seu próprio mapa.
 
 JOGO:
     O jogo é do estilo aventura/puzzle onde o objetivo é o jogador conseguir passar de três fases. Em cada fase o jogador deve se movimentar para pegar uma chave para abrir a porta fechada.
     O jogador possui os seguintes comando:
W: O jogador movimenta uma unidade para cima;
A: O jogador movimenta uma unidade para esquerda;
S: O jogador movimenta uma unidade para baixo;
D: O jogador movimenta uma unidade para direita;
I: O jogador interage com o objeto que ele estar em cima.
     O jogo possui os seguintes elementos nas fases:
&: Simbolo que representa o jogador.
*: Simbolo que representa uma parede, o jogador ao se movimentar não pode passar pela parede.
@: Simbolo que representa a chave para abrir a porta para finalizar a fase, a porta abre no momento que o jogador interage com a chave.
D: Simbolo que representa a porta fechada.
=: Simbolo que representa a porta aberta quando o jogador interagiu com a chave.
O: Simbolo que representa um botão que o usuário pode interagir, o botão fica no chão e o jogador deve ficar em cima dele para poder interagir.
#: Simbolo que representa um espinho. A fase é reiniciada quando o jogador toca no espinho, caso a fase seja reiniciada três vezes, o jogo volta para o menu principal.
>: Simbolo que representa um teletransporte. O teletransporte sempre deve vir em par, quando o jogador toca em um ele é transportado para o outro e vice-versa.
