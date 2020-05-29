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

### Interfaces

Interfaces associadas a esse componente:

Campo | Valor
----- | -----
Classe | `<caminho completo da classe com pacotes>` <br> Exemplo: `pt.c08componentes.s20catalog.s10ds.DataSetComponent`
Autores | `<nome dos membros que criaram o componente>`
Objetivo | `<objetivo do componente>`
Interface | `<interface em Java do componente>`
~~~
public interface ITableProducer {
  String[] requestAttributes();
  String[][] requestInstances();
}
public interface IDataSource {
  public String getDataSource();
  public void setDataSource(String dataSource);
}
public interface IDataSet extends ITableProducer, IDataSource {
}
~~~

## Detalhamento das Interfaces

### Interface `<nome da interface>`
`<papel da interface>`.

Método | Objetivo
-------| --------
`<id do método em Java>` | `<objetivo do método e descrição dos parâmetros>`
