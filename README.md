## Análise de Dados de Varejo Online

## Descrição

Este projeto tem como objetivo analisar um conjunto de dados de varejo online para obter insights sobre o comportamento dos clientes, padrões de compra e tendências de vendas. 

Utilizaremos Python e bibliotecas como Pandas e Matplotlib para explorar, limpar, transformar e visualizar os dados. O objetivo final é extrair informações relevantes que possam auxiliar na tomada de decisões estratégicas para o negócio.
Para isso vamos responder com dados 20 perguntas:

1.	Qual é o valor total de vendas ao longo do período?
2.	Quais são os produtos mais vendidos?
3.	Quais são os países que geram mais receita?
4.	Existe alguma sazonalidade nas vendas? (Ex: picos em datas comemorativas)
5.	Como as vendas se distribuem ao longo dos dias da semana ou meses do ano?
6.	Qual é o valor médio das compras por cliente?
7.	Existe uma correlação entre a quantidade de produtos comprados e o valor total da compra?
8.	Quais produtos são frequentemente comprados juntos?
1.	Quantos clientes únicos existem no dataset?
2.	Qual é a frequência de compra dos clientes?
3.	Existe diferença no comportamento de compra entre clientes de diferentes países?
4.	Quais clientes são os mais valiosos em termos de receita gerada?
5.	É possível segmentar os clientes em grupos com base em seus padrões de compra?
6.	Qual a taxa de retenção de clientes?
1.	Quantos produtos diferentes são vendidos?
2.	Qual é a distribuição de preços dos produtos?
3.	Existem produtos que são frequentemente devolvidos?
4.	Quais produtos geram mais lucro?
5.	Existe alguma relação entre a descrição do produto e sua popularidade?
6.  É possível prever as vendas futuras com base nos dados históricos?



## Dados

Os dados utilizados neste projeto são provenientes do arquivo `online_retail.csv`. O conjunto de dados contém informações sobre transações de varejo online, incluindo:

* **InvoiceNo:** Número da fatura.
* **StockCode:** Código do produto.
* **Description:** Descrição do produto.
* **Quantity:** Quantidade do produto.
* **InvoiceDate:** Data da fatura.
* **UnitPrice:** Preço unitário do produto.
* **CustomerID:** ID do cliente.
* **Country:** País do cliente.


## Etapas da Análise

1. **Carregamento e Inspeção dos Dados:**
    - Importar o arquivo `online_retail.csv` utilizando a biblioteca Pandas.
    - Verificar as primeiras linhas do DataFrame para entender a estrutura dos dados.
    - Obter informações sobre os tipos de dados, valores ausentes e estatísticas descritivas usando os métodos `info()`, `isnull().sum()` e `describe()`.
2. **Limpeza e Pré-processamento dos Dados:**
    - Tratar valores ausentes (se necessário).
    - Converter a coluna `InvoiceDate` para o tipo datetime.
3. **Análise Exploratória dos Dados:**
    - Investigar a distribuição das variáveis.
    - Identificar padrões e tendências nas vendas.
    - Analisar o comportamento dos clientes por país, produto, etc.
4. **Visualização dos Dados:**
    - Criar gráficos e tabelas para apresentar os resultados da análise de forma clara e concisa.

## Resultados

* Este projeto ainda está em desenvolvimento
