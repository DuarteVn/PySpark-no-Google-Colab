# PySpark-no-Google-Colab

1. Notebook 1:  
- Carregar os dados de vendas a partir do arquivo CSV para um DataFrame do Spark. 
- Leitura e Visualização dos Dados; 
- Carregar 3 DataFrame com dados de CLIENTE, GERENCIA e DEPARTAMENTO; 
- SALVAR os dados do DATAFRAME em arquivos CSV no formato da tabela de GERENCIA e  DEPARTAMENTO. Considere os atributos do modelo de dados; 
- SALVAR os dados do DATAFRAME em arquivos CSV da tabela CLIENTE. Os nomes de clientes e das  cidades devem ficar em MAIUSCULO. Considere a estrutura do modelo de dados. 


2. Notebook 2:  
- Carregar os dados de vendas a partir do arquivo CSV para um DataFrame do Spark. 
- Conectar ao banco MYSQL; 
- Carregar os dados de DEPARTAMENTO a partir do arquivo CSV gerado no NOTEBOOK 1; - Carregar DataFrame com dados de PRODUTO; 
- SALVAR os dados do DATAFRAME em arquivos CSV de PRODUTO, considerando a estrutura do modelo de dados e dados do dataframe de departamento. Utilizar JOIN. Os registros que contém o  nome do produto "Aparalho de Barbear Elétrico" transformar para "Barbeador Elétrico". 

3. Notebook 3:  
- Carregar os dados de vendas a partir do arquivo CSV para um DataFrame do Spark. 
- Carregar DataFrame com dados de VENDAS; 
- SALVAR os dados do DATAFRAME em arquivos CSV de VENDAS, considerando os atributos do modelo  de dados.  
- Criar um dataframe com um dado consolidado que apresente a soma de vendas por ano-mês  (AAAAMM), cidade, produto. Salve estes dados no formato em PARQUET.  
- Exibir os dados consolidados do DATAFRAME, apenas primeiras 20 linhas. 
- Criar um dataframe com um dado consolidado que apresente a soma de vendas por ano (AAAAMM), produto. 
- Exibir os dados consolidados do DATAFRAME. 
