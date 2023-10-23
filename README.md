# SistemaRecomendacao_TOPN

## Descrição Projeto

**Conjunto de dados:**
O dataset a ser utilizado será o [MovieLens](https://grouplens.org/datasets/movielens/). Com dados distribuídos da sequinte forma:
- `item id`: identificador do filme
- `title`: título do filme
- `genres`: lista com os gêneros associados ao filme

Além do dataset de filmes, também será utilizado um dataset com as avaliações desses filmes, com os dados distribuídos através das colunas:
- `user id`: identificador do usuário
- `item id`: identificador do filme
- `rating`: avaliação do filme
- `timestamp`: tempo que foi realizada a avaliação

**Arquivo:** .parquet

**Objetivo:**
Executar dois exemplos de código de recomendação Top N:  Top N consumidos (os N itens mais consumidos pelos usuários) e Top N avaliados (os N itens melhores avaliados pelos usuários), levando em consideração dados de um dataset com informações de filmes e outro dataset com avaliações desses filmes.

Algoritmos de recomendação Top-N são algoritmos que recomendam um conjunto de itens para um usuário, com base em suas preferências e histórico de interações. Eles são amplamente utilizados em sistemas de recomendação, como os usados por empresas de comércio eletrônico, serviços de streaming de vídeo e música, entre outros.   
**IDE:** Colab

**Linguagem:** Python 

**Principais bibliotecas utilizadas:**
•	Cycler, para personalizar cores em gráficos;
•	Pandas, para manipulação e tratamento dos dados;
•	Matplotlib, para criação e visualização de gráficos;
•	Google.colab, para importar arquivos da núvem;
•	Numpy, para realizar cálculos numéricos;
•	Datetime, para manipulação de dados no formato de data.

**Sequencia processos:**

1° Instalação bibliotecas; 

2° Pré processamento datasets;

3° Função para Recomendação Top N Consumidos:

4° Função para Recomendação Top N Avaliados.

**Resultado:**
Através da sequência de processos realizadas, e embasado pelos dados dos datasets estudados, foi possível gerar um acervo com recomendações de 10 filmes melhores avaliados e 10 filmes mais consumidos.
