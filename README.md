Este é um estudo simples utilizando o Orange Canvas como ferramenta para predição de cancer de mama baseado
em algumas features obtidas no dataset disponibilizado em https://www.kaggle.com/yuqing01/breast-cancer/home

Foram utilizados três métodos de predição sendo que o mais preciso foi o SVM com 97% de acurácia.

# Tratamento dos dados:

Arquivo utilizado para como conjunto de treinamento: breast-cancer.csv
Neste arquivo foram retiradas duas colunas que não são  relevantes para o estudo, as colunas são 'id' e a última coluna que não possui nome pois
no csv do dataset foi inserida uma vírgula como que apontando para uma coluna, caso você queira pode remover esta vírgula
no header do arquivo diretamente e depois proceder com o carregamento do arquivo, eu preferi deixar para realizar este 
tratamento diretamente no Orange Canvas.

Ao carregar os dados com o widget File é necessário definir a coluna 'diagnosis' como 'target' pois só assim
podemos utilizar os widgets de predição.

Arquivo utilizado para o conjunto de test: test_dataset.csv
Neste arquivo foram extraídos 20% de dados do arquivo original e a coluna diagnosis foi modicada substituindo seus valores
pelo character de interrogação ? visto que será o arquivo utilizado para projetar a predição.


# Algoritmos utilizados:
Foram utilizados três algoritmos para predição:
Logistic Regression
Random Forest
SVM

# Test & Score
Foram testados os três algoritmos utilizados utilizando os componentes Test & Score e Confusion  Matrix

# Classificação
Para melhor visualização das classes foi utilizado um K-Means

# Visualização 
Para visualização das classes utilizamos apenas um gráfico de distribuição simples mostrando a quantidade de células
benignas ou malignas





