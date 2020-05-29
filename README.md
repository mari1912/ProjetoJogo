# Projeto `DinosaurMaze`

## Equipe
* David Afonso Borges dos Santos- 261032
* Mariana Sartorato Jorge - 241334

## Descrição Resumida do Projeto
Os dinossauros estão correndo risco de extinção. Nesse jogo, o jogador irá ajudar um dinossauro a fugir de meteoros que estão o perseguindo. O jogo será formado por um tabuleiro e peças que se movimentam nele. As peças que serão encontradas ao longo do tabuleiro são: árvores (serão obstáculos no caminho do dinossauro, que terá que contorná-las), meteoros (estarão tentando ir atrás do dinossauro), o dinossauro (vai tentar fugir dos meteoros e ganhar pontos), arbustos escondendo utensílios (esses utensílios poderão ajudar ou atrapalhar o dinossauro na sua fuga) e comida (cada peça comida aumentará em 500 pontos a pontuação do jogador). Os objetivos do jogo são: fugir dos meteoros e ganhar o maior número de pontos possível. O jogo acaba quando a comida disponível acaba ou quando o dinossauro é atingido por algum meteoro.

## Vídeo do Projeto
[Link do vídeo](https://www.youtube.com/watch?v=qXy4wn0Sr80)

## Diagrama geral das Componentes

## Componentes

## Tabuleiro

### Interfaces

Interfaces associadas a esse componente:
![Imagem tabuleiro](tabuleiro.png)

Campo | Valor
----- | -----
Classe | Tabuleiro
Autores | David e Mariana
Objetivo | Representar o espaço do jogo
Interface | ITabuleiro
~~~
public interface ITabuleiro {
  void endGame();
  void startGame();
  void doOneLoop();
}
~~~

## Detalhamento das Interfaces

### Interface `ITabuleiro`
Iniciar e relizar movimentos do jogo no tabuleiro até que ele acabe.

Método | Objetivo
-------| --------
startGame() | iniciar o jogo posicionando as peças
endGame()| ver se o dinossauro ainda está vivo, se não estiver, acabar com o jogo
doOneLoop() | 

## PeçasMovimento

### Interfaces

Interfaces associadas a esse componente:
![Imagem tabuleiro](movable(3).png)

Campo | Valor
----- | -----
Classe | Tabuleiro
Autores | David e Mariana
Objetivo | Representar o espaço do jogo
Interface | ITabuleiro
~~~
public interface ITabuleiro {
  void endGame();
  void startGame();
  void doOneLoop();
}
~~~

## Detalhamento das Interfaces

### Interface `ITabuleiro`
Iniciar e relizar movimentos do jogo no tabuleiro até que ele acabe.

Método | Objetivo
-------| --------
startGame() | iniciar o jogo posicionando as peças
endGame()| ver se o dinossauro ainda está vivo, se não estiver, acabar com o jogo
doOneLoop() | 
