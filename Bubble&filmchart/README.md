# 📊Gráfico de bolhas e filmes🎬

Todo o projeto foi desenvolvido com muito carinho e dedicação. A fim de ilustrar o potencial do gráfico de bolhas em análises práticas. Explicarei para que serve e com cheguei à essa 👇 conclusão.

<img src="https://raw.githubusercontent.com/PedroHSS01/PyDataViz/refs/heads/main/Bubble%26filmchart/graficos/Filmes%26S%C3%A9riesNetflixplot.png">

## Descrição 📝

Este gráfico de bolhas oferece uma visão dos filmes e séries da <img src="https://emojis.slackmojis.com/emojis/images/1643514492/4757/netflix.png?1643514492" width="20">, permitindo analisar diversos aspectos como gênero, classificação IMDb e ano de lançamento. Cada bolha representa uma produção, com seu tamanho proporcional a um fator relevante como número de votos por exemplo.

Embora a quantidade de dados possa inicialmente parecer complexa e visualmente poluída, é possível filtrar por gênero para uma análise mais focada. Ao passar o cursor sobre uma bolha, são exibidas informações detalhadas sobre a produção, incluindo título, gênero, ano de lançamento, classificação IMDb e número de votos.

Há também uma versão similar desse gráfico, focada especificamente em 🎄filmes de Natal🎅, permitindo identificar os títulos mais populares, os gêneros mais comuns ao longo dos anos nesse período festivo.

<img src="https://raw.githubusercontent.com/PedroHSS01/PyDataViz/refs/heads/main/Bubble%26filmchart/graficos/FilmesNatalinosplot.png">

O desenvolvimento desse projeto foi executado usando o serviço do Jupyter Notebook o que não implica em ser usado em outros serviços. 

Os DataFrame coletados são públicos e encontrados no kaggle [aqui](https://www.kaggle.com/code/josluizfjunior/an-lise-de-filmes-netflix/input) e [aqui](https://www.kaggle.com/datasets/jonbown/christmas-movies/data). Também estão disponíveis na pasta `dadoscsv` para sua comodidade.

## Gráfico de bolhas

Um gráfico de bolhas é um gráfico de dispersão, mas com um toque extra. Em vez de apenas pontos, ele usa círculos (bolhas). A posição de cada bolha nos eixos horizontal (X) e vertical (Y) representa dois valores, assim como no gráfico de dispersão. A diferença é que o tamanho de cada bolha representa um terceiro valor. Isso permite visualizar três dimensões de dados em um único gráfico, facilitando a comparação e a identificação de padrões entre os dados.

### Quando usar gráficos de bolhas

Quando você precisar da relação entre três variáveis ao mesmo tempo. Imagine que você tem dados sobre filmes e séries:

- Variável 1 (Eixo X): Ano de lançamento.
- Variável 2 (Eixo Y): Classificação IMBb.
- Variável 3 (Tamanho da bolha): Votos.

### Quando não usar gráficos de bolhas

Gráficos de bolhas não são ideais para apenas duas variáveis (use um gráfico de dispersão comum). Muitos dados podem tornar o gráfico confuso; considere dividi-los ou uma visualização mais adquada. 

## Exemplo 💡

No projeto `Bubble&filmchart` foi elaborado um exemplo de como foram utilizados os dados para a construção dos gráfico interativo. Os módulos e bibliotecas utilizados foram:

``` 
import plotly.express as px
import pandas as pd
import re
```
Devido a:
 - plotly.express: Criar os gráficos interativos.
 - pandas: Manipular e analisa dados.
 - re: Trabalhar com expressões regulares.
 
## Referência

Esse projeto tem como inspiração as ideias de:

 - [The Python Graph Gallery](https://python-graph-gallery.com/)
 - [Andre Kuniyoshi](https://www.linkedin.com/in/andrekuniyoshi/)
 - ...

## Feedback 🗨️

Se você tiver algum feedback, por favor, envie uma mensagem por meio do e-mail: 2pedrohss@gmail.com ou entre em contado no [LinkedIn.](https://www.linkedin.com/in/pedro-h-s-sousa/)
