# GOODREADS-BOOK-REVIEWS

Esse projeto foi desenvolvido com o objetivo de entender as avaliações de livros por usuários dentro da plataforma Goodreads, e de criar modelos preditivos para sugerir a probabilidade de um livro ser bem avaliado.

### Conjunto de Dados
O conjunto de dados utilizados consiste em diversos arquivos contendo informações sobre os livros e as interações entre usuários e livros. O conjunto pode ser encontrado [aqui](https://www.kaggle.com/datasets/pypiahmad/goodreads-book-reviews1/data).

Para esse projeto foram utilizados os seguintes arquivos (todos podem ser encontrados no link acima):
- [goodreads_books.json](https://www.kaggle.com/datasets/pypiahmad/goodreads-book-reviews1/data?select=goodreads_books.json)
- [goodreads_book_authors.json](https://www.kaggle.com/datasets/pypiahmad/goodreads-book-reviews1/data?select=goodreads_book_authors.json)
- [goodreads_book_genres_initial.json](https://www.kaggle.com/datasets/pypiahmad/goodreads-book-reviews1/data?select=goodreads_book_genres_initial.json)

### Modelos criados
- Random Forest
- XGBoost

### Dependências Necessárias
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

<br>

Instalando as dependências
```sh
pip install -r requirements.txt
```

### Estrutura do Projeto
Todos os arquivos se encontram dentro do diretório ```src```, e seguem a seguinte ordem:
- `data_load.ipynb`: Carregamento e junção dos datasets utilizados em um único arquivo
- `data_cleaning.ipynb`: Separação do dataset em conjuntos de treino, validação e testes e tratamento inicial dos dados
- `data_analytics.ipynb`: Análise exploratória dos dados
- `data_preparation.ipynb`: Tratamento dos dados
- `random_forest.ipynb`: Treinamento e avaliação do modelo de Random Forest
- `xgboost.ipynb`: Treinamento e avalição do modelo de XGBoost