# Classificador de Imagens por Satélite 🛰️

Bem-vindo ao Classificador de Imagens por Satélite! Este projeto utiliza uma rede neural convolucional (CNN) para categorizar imagens obtidas por satélite em quatro classes: 'cloudy', 'desert', 'forest' e 'sea/lake'.

## Conteúdo do Repositório 📁

- `classificacao_satelite.ipynb`: Jupyter Notebook com o código do classificador.
- `classificação_satélite.py`: Código fonte do classificador em arquivo python.
- `satelite.zip`: Arquivo zip que contém a pasta que está o conjunto de dados de treinamento e teste utilizados para a classificação.

## Como Usar

1. Faça o download do conjunto de dados de imagens por satélite e extraia-o na pasta `data`.
2. Abra o arquivo `classificacao_satelite.ipynb` em um ambiente de desenvolvimento Python (de preferência o Google Colab).
3. Siga as instruções no notebook para executar o código.

## Como Usar no Google Colab 🚀

1. Abra o [Google Colab](https://colab.research.google.com/).
2. Crie um novo notebook ou abra um existente.
3. No ambiente do Colab, clique em "Arquivo" > "Upload" e faça o upload do arquivo `classificacao_satelite.ipynb`.
4. Abra o arquivo `classificacao_satelite.ipynb`.
5. Faça o download do arquivo satelite.zip e adicione esse arquivo ao seu drive.
6. Siga as instruções no notebook para executar o código.

## Pré-requisitos

Para executar o classificador, você precisará ter os seguintes pré-requisitos instalados:

- Python 3.x
- Bibliotecas Python: numpy, opencv-python, matplotlib, tensorflow, scikit-learn

Você pode instalar as dependências usando o comando pip:

Pelo google colab não há necessidade de instalar nenhum software adicional, pois o Google Colab já possui todas as dependências necessárias.


## Executando o Classificador

Abra o notebook `classificacao_satelite.ipynb` em um ambiente Python e execute as células do código. O notebook contém explicações detalhadas sobre cada etapa.

## Resultados

O classificador fornecerá métricas de avaliação, como precisão, recall e um relatório de classificação para as quatro classes.


