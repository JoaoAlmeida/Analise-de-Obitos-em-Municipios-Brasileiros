# Análise de Óbitos em Municípios Brasileiros
 Este repositório contém uma análise de óbitos utilizada para aprender Big Query.
 
 ## Pacotes
 
 Para reproduzir os Notebooks é necessário ter instalado os pacotes pandas, matplotlib e numpy. Para instalar os pacotes, apenas digite o comando abaixo no prompt de comando (necessário ter Python instalado):
 
 ```
 pip install <nome_pacote>
 ```

## Datasets

 Os datasets "municipio_causa.csv" e "municipio.csv" estão disponíveis publicamente no Mendeley Data. É necessário fazer o download neste [link](https://data.mendeley.com/datasets/vbg6ws3src/2) e colocá-lo no diretório raiz do repositório.

 
 ### BigQuery
 
 Ative o BigQuery API e o BigQuery Connection API no [Google Cloud Platform](https://console.cloud.google.com/home/dashboard) para poder executar as querys existentes no caderno.
 
 Antes de executar o caderno, verifique se está autenticado no Google Cloud, digitando o seguinte comando:
 
 ```
 gcloud auth application-default login
 ```
 
 Em seguida, instale os pacotes necessários;
 
 ```
 pip install --user --upgrade google-api-python-client
 pip install --user pandas-gbq -U
 ```
