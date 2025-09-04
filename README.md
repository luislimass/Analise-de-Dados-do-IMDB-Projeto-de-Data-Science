README do Projeto de Análise de Dados IMDB

Este projeto consiste em um notebook Jupyter (LH_CD_LUISEDUARDO.ipynb) que realiza uma análise exploratória de dados (EDA) de um dataset de filmes do IMDB, seguido pela aplicação de modelos de Machine Learning para prever a nota do IMDB e o gênero do filme.

Pré-requisitos

Para executar este projeto, você precisará ter o Python instalado, juntamente com as seguintes bibliotecas:

•
pandas

•
matplotlib

•
seaborn

•
scikit-learn (sklearn)

•
jupyter (para abrir e executar o notebook)

Instalação

1.
Clone o repositório (se aplicável) ou baixe os arquivos do projeto.

2.
Crie um ambiente virtual (recomendado):

3.
Instale as dependências:

Uso

1.
Certifique-se de que o arquivo de dados desafio_indicium_imdb.csv esteja no mesmo diretório que o notebook LH_CD_LUISEDUARDO.ipynb.

2.
Inicie o Jupyter Notebook:

3.
No navegador, navegue até o arquivo LH_CD_LUISEDUARDO.ipynb e clique nele para abri-lo.

4.
Execute as células do notebook sequencialmente. Você pode fazer isso clicando em Cell > Run All no menu do Jupyter, ou executando cada célula individualmente (Shift + Enter).

O notebook realizará as seguintes etapas:

•
Carregamento e visão geral dos dados.

•
Tratamento de valores ausentes e duplicação.

•
Limpeza e transformação de colunas (Gross, Runtime).

•
Análise exploratória de dados com visualizações.

•
Previsão da nota do IMDB usando RandomForestRegressor.

•
Previsão do gênero do filme usando LogisticRegression e TfidfVectorizer.

•
Salvamento de um modelo treinado (modelo_genero.pkl).

Estrutura do Projeto

•
LH_CD_LUISEDUARDO.ipynb: O notebook Jupyter principal contendo toda a análise e os modelos.

•
desafio_indicium_imdb.csv: O dataset de entrada utilizado no projeto.

•
modelo_genero.pkl: (Gerado após a execução do notebook) O modelo de regressão logística treinado para prever o gênero.

