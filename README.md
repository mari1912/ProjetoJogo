# Projeto `DinosaurMaze`

## Equipe
* David Afonso Borges dos Santos- 261032
* Mariana Sartorato Jorge - 241334

## Descrição Resumida do Projeto
Os dinossauros estão correndo risco de extinção. Nesse jogo, o jogador irá ajudar um dinossauro a fugir de meteoros que estão o perseguindo. O jogo será formado por um tabuleiro e peças que se movimentam nele. As peças que serão encontradas ao longo do tabuleiro são: árvores (serão obstáculos no caminho do dinossauro, que terão que contorná-las), meteoros (estarão tentando ir atrás do dinossauro), o dinossauro (vai tentar fugir dos meteoros e ganhar pontos), arbustos escondendo utensílios (esses utensílios poderão ajudar ou atrapalhar o dinossauro na sua fuga) e comida (cada peça comida aumentará em 500 pontos a pontuação do jogador). Os objetivos do jogo são: fugir dos meteoros e ganhar o maior número de pontos possível. O jogo acaba quando a comida disponível acaba ou quando o dinossauro é atingido por algum meteoro.

## Vídeo do Projeto
[Link do vídeo](https://www.youtube.com/watch?v=qXy4wn0Sr80)

## Diagrama geral das Componentes

### Exemplo 1

Este é o diagrama compondo componentes para análise:

![Diagrama Analise](diagrama-componentes-analise.png)

### xemplo 2

Este é um diagrama inicial do projeto de jogos:

![Diagrama Jogos](diagrama-componentes-jogos.png)

### Ex 3

Este é outro diagrama de um projeto de vendas:

![Diagrama Vendas](diagrama-componentes-vendas.png)

Para cada componente será apresentado um documento conforme o modelo a seguir:

## Componente<Nome do Componente>`

![Componente](diagrama-componente.png)

### Interfaces

Interfaces associadas a esse componente:

![Diagrama Interfaces](diagrama-interfaces.png)

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

## Exemplo:

### Interface `ITableProducer`

Interface provida por qualquer fonte de dados que os forneça na forma de uma tabela.

Método | Objetivo
-------| --------
`requestAttributes` | Retorna um vetor com o nome de todos os atributos (colunas) da tabela.
`requestInstances` | Retorna uma matriz em que cada linha representa uma instância e cada coluna o valor do respectivo atributo (a ordem dos atributos é a mesma daquela fornecida por `requestAttributes`.

### Interface `IDataSetProperties`

Define o recurso (usualmente o caminho para um arquivo em disco) que é a fonte de dados.

Método | Objetivo
-------| --------
`getDataSource` | Retorna o caminho da fonte de dados.
`setDataSource` | Define o caminho da fonte de dados, informado através do parâmetro `dataSource`.
