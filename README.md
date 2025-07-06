# MVP: Análise Exploratória e Pré-Processamento - Plataforma de Streaming Disney+

Este projeto apresenta uma análise exploratória de dados (EDA) e um pipeline de pré-processamento utilizando um dataset público contendo informações sobre os filmes e séries disponíveis na plataforma de streaming **Disney+**.

---

## Objetivo

O objetivo principal é aplicar técnicas fundamentais de **Ciência de Dados** para:

- Explorar os dados de forma visual e estatística
- Tratar dados ausentes e inconsistências
- Realizar o pré-processamento necessário para projetos futuros de **modelagem supervisionada ou não supervisionada**

---

## Dataset

O dataset utilizado é o [`disney_plus_titles.csv`](https://www.kaggle.com/datasets/shivamb/disney-movies-and-tv-shows), disponível no Kaggle.

Ele contém informações como:

- Nome do título
- Tipo (filme ou série)
- Data de inclusão na plataforma
- Ano de lançamento
- Duração
- Diretores e elenco
- Países
- Classificação indicativa
- Gêneros (`listed_in`, campo multivalorado)

---

## Etapas do Projeto

### 1. Importação e Visualização Inicial
- Leitura do arquivo `.csv`
- Verificação de tipos de dados, valores ausentes e estrutura do dataset

### 2. Análise Exploratória de Dados (EDA)
- Conversão de datas e demais tipos numéricos
- Extração e padronização de colunas como `duration` e `listed_in`
- Agrupamentos para melhor visualização e análise
- Geração de gráficos de barras, pizza, histograma e boxplots
- Correlação entre variáveis numéricas
- Comparações entre filmes e séries
- Conversão de datas
- Extração e padronização de colunas como `duration` e `listed_in`

### 3. Pré-processamento
- Remoção de duplicatas e tratamento de nulos
- One-hot encoding para variáveis categóricas
- Criação de colunas multivaloradas separadas
- Normalização e padronização para futuros modelos

---

## 📂 Organização do Repositório

📁 main

├── disney_plus_titles_W43.csv # Dataset original

├── MVP_Analise_Dados_Boas_Praticas_VivianeMMatos.ipynb # Notebook com EDA e pré-processamento

├── README.md # Arquivo descritivo do projeto

---

## Principais Conclusões

- A classificação etária predominante é a Classificação livre.
- Há grande diversidade de gêneros/categorias, especialmente entre as séries.
- O tempo médio entre o ano de lançamento e a inclusão na plataforma diminuiu ao longo dos anos.
- O campo `listed_in` traduzido como gênero é multivalorado e exige tratamento específico para modelagem.

---

## Tecnologias e Bibliotecas

- Python 3.10+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Aprendizados

Este MVP reforça a importância das etapas de preparação e análise exploratória, sendo fundamentais para decisões futuras sobre a escolha de modelos, atributos e abordagem de problemas.

---

## Referência

Dataset: [Disney+ Movies and TV Shows | Kaggle](https://www.kaggle.com/datasets/shivamb/disney-movies-and-tv-shows)

---

