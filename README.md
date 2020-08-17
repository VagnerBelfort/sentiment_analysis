# Estudos de Análise de Sentimentos.

## Aplicando NRC EMOTIONAL LEXICON em um dataset.
Utilizando dados do conjunto de dados Economic News Article Tone 2016 (https://data.world/crowdflower/economic-news-article-tone), disponível por CrowdFlower. As notícias sobre a economia americana são coletadas de vários sites de notícias publicadas entre 1951 e 2014. Há para cada notícia, um sentimento dado por um jhumano em uma escala de 1 a 9, onde 1 é o mais negativo e 9 o mais positivo. Também existe o nível de confidência sobre a classificação dada em uma escala de 0 a.

Há 8000 artigos de notícias e quinze colunas:

- articleid: id do artigo
- text: conteúdo textual 
- date: data de publicação
- positivity: sentimento dado por humano (ground truth)human-rated sentiment - 1(most negative)-9(most positive)
- positivity.confidence: confidence of human rating

### Pré-requisitos

 - requirements.txt;
 - O dataset se encontra na pasta data.

### Recursos utilizados no desenvolvimento:

- Jupyter Notebook.
