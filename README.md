
**Versões/Versions:** [Português](#portugues) , [English](#ingles) 

<div id="portugues">
  
# XADREZ DE TERMINAL &#9812; &#9813; &#9814; &#9815; &#9816; &#9817;

O projeto do Xadrez de terminal, foi feito para me ajudar no desenvolvimento de habilidades com Programação Orientada a Objetos utilizando a linguagem Java. 
No projeto estão contidos todos os pilares da programação (Abstração, Polimorfismo, Encapsulamento e Herança) . 

<br>

### Tecnologias utilizadas

- JAVA 21
- Eclipse IDE

<br>

### Requisitos

- Java JDK

<br>

### Como rodar na sua máquina?

- No terminal do seu computador clone o repositório usando o comando abaixo na pasta desejada:  

        git clone https://github.com/christianfernandesprofissional/terminal_chess_java.git

- Após a clonagem entre vá em:

          .\terminal_chess_java\src\application  

- Copie o arquivo Program.java para

          .\terminal_chess_java\src

- Abra o terminal nesta pasta e digite o comando:
  
          javac Program.java
  

- Logo após, o jogo estará pronto para ser iniciado, para iniciar o jogo digite:

          java Program.java

  ***

<br>

### Como o jogo funciona?

No jogo é possível jogar com dois jogadores, seguindo todas as regras contidas no xadrez, inclusive regras adicionais que são menos conhecidas como o Roque e o En Passant.   
As peças do jogo estão representadas pela letra do seu nome em inglês, sendo **Peão (P), Cavalo (N), Bispo (B), Torre (R), Rainha (Q), Rei (K)**.  


![Game Start](/assets/game-start.png "Tela inicial do jogo")

As peças pretas são representadas na cor verde para um melhor contraste.
<br>

Para jogar, o jogador deve primeiro selecionar a coordenada da peça que deseja mover, que é a letra que representa a linha onde a peça está, e um número correspondente a coluna.  

![Game Start](/assets/moving-pieces.png "Movendo as peças") ![Game Start](/assets/possible-capture.png "Possível captura")
<br>

Após a seleção da peça o jogo irá mostrar os movimentos possíveis com aquela peça, na cor azul.  
Caso o jogador selecione um movimento inválido a jogada voltará ao início.
As peças capturadas durante a partida serão mostradas em baixo dentro dos colchetes.  

![Game Start](/assets/captured-pieces.png "Peças capturadas")
<br>

Caso ocorra um ***CHEQUE*** na partida, o jogo anunciará em vermelho, e enquanto o jogador não fizer movimentos que o livrem do ***CHEQUE***, todos os outros movimentos serão inválidos.  

![Game Start](/assets/king-in-check.png "Rei em cheque") 
<br>

O jogo também impede que o jogador se coloque em CHEQUE, e caso o rei esteja nessa situação ele é obrigado a se defender.

![Game Start](/assets/king-defense.png "Defenda o rei")

<br>

Caso a defesa não seja possível, ocorre um CHEQUE-MATE, e o jogo acaba.

![Game Start](/assets/checkmate.png "CHEQUE-MATE")

<br>

**Espero que você se divirta!** :smiley:

Caso você tenha alguma sugestão de melhoria ou algum comentário sobre o jogo,  
sinta-se livre para entrar em contato através do email: ``christianfernandesprofissional@gmail.com``.

</div>

<br><br>

***

<div id="ingles">
  
# TERMINAL CHESS &#9812; &#9813; &#9814; &#9815; &#9816; &#9817;

The Terminal Chess project was designed to help me develop skills with Object Oriented Programming using the Java language. 
The project contains all the pillars of programming (Abstraction, Polymorphism, Encapsulation and Inheritance).

<br>

### Technologies used

- JAVA 21
- Eclipse IDE

<br>

### Requirements

- Java JDK

<br>

### Como rodar na sua máquina?

- In your computer's terminal, clone the repository using the command below in the desired folder:  

        git clone https://github.com/christianfernandesprofissional/terminal_chess_java.git

- After cloning, go to:

          .\terminal_chess_java\src\application  

- Copy the Program.java file to:

          .\terminal_chess_java\src

- Open the terminal in this folder and type the command:
  
          javac Program.java
  

- Soon after, the game will be ready to start, to start the game type:

          java Program.java

  ***

### How does the game work?

In the game it is possible to play with two players, following all the rules contained in chess, including additional rules that are less known such as Castling and En Passant.   
The game pieces are represented by the letter of their name in English, being **Pawn (P), Knight (N), Bishop (B), Rook (R), Queen (Q), King (K)**.


![Game Start](/assets/game-start.png "Game home screen")

The black pieces are represented in green for better contrast.
<br>

To play, the player must first select the coordinate of the piece they want to move, which is the letter that represents the line where the piece is, and a number corresponding to the column. 

![Game Start](/assets/moving-pieces.png "Moving the pieces") ![Game Start](/assets/possible-capture.png "Possible capture")
<br>

After selecting the piece, the game will show the possible movements with that piece, in blue.  
If the player selects an invalid move, the move will return to the beginning.
The pieces captured during the game will be shown below within the brackets.

![Game Start](/assets/captured-pieces.png "Captured pieces")
<br>

If a ***CHECK*** occurs in the match, the game will announce it in red, and as long as the player does not make moves that free him from the ***CHECK***, all other moves will be invalid.

![Game Start](/assets/king-in-check.png "King in Check") 
<br>

The game also prevents the player from putting himself in CHECK, and if the King is in this situation he is forced to defend himself.

![Game Start](/assets/king-defense.png "Defend the King")

<br>

If the defense is not possible, a CHECKMATE occurs, and the game ends.

![Game Start](/assets/checkmate.png "CHECKMATE")

<br>

**Hope you have fun!** :smiley:

If you have any suggestions for improvements or comments about the game,
feel free to get in touch via email: ``christianfernandesprofissional@gmail.com``.

</div>

<br><br>

</div>



