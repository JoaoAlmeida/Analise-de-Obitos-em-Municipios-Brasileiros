# Teste - CIDACS
 Este repositório contém o teste prático realizado para a seleção de Analista de Dados no CIDACS.
 
 ## Pacotes
 
 Para reproduzir os Notebooks é necessário ter instalado os pacotes pandas, matplotlib e numpy. Para instalar os pacotes, apenas digite o comando abaixo no prompt de comando (necessário ter Python instalado):
 
 ```
 pip install <nome_pacote>
 ```
 
 ## Datasets
 
 A tabela "municipio_causa.csv" não está no repositório do Github. É necessário fazer o download neste [link](https://fiocruzbr-my.sharepoint.com/personal/selecao_cidacs_fiocruz_br/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fselecao%5Fcidacs%5Ffiocruz%5Fbr%2FDocuments%2FSele%C3%A7%C3%A3o%20Visualiza%C3%A7%C3%A3o%2FAnalista%2FTeste%20pr%C3%A1tico%20Analista&originalPath=aHR0cHM6Ly9maW9jcnV6YnItbXkuc2hhcmVwb2ludC5jb20vOmY6L2cvcGVyc29uYWwvc2VsZWNhb19jaWRhY3NfZmlvY3J1el9ici9FcGxjVlM5M1JiQkRwRnFnWFpra2xOUUJ5d2E5RVFqbUkyNTlfZFhtR2FFdHlRP3J0aW1lPTdLWjYxdnVTMkVn) e colocá-lo no diretório raiz do repositório.
 
 ### BigQuery
 
 Não foi necessária nenhuma etapa adicional ao descrito no anexo do e-mail. Ative o BigQuery API e o BigQuery Connection API no [Google Cloud Platform](https://console.cloud.google.com/home/dashboard) para poder executar as querys existentes no caderno.
 
 Antes de executar o caderno, verifique se está autenticado no Google Cloud, digitando o seguinte comando:
 
 ```
 gcloud auth application-default login
 ```
 
 Em seguida, instale os pacotes necessários;
 
 ```
 pip install --user --upgrade google-api-python-client
 pip install --user pandas-gbq -U
 ```
