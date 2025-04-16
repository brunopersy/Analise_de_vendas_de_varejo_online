# Dicionário de Dados: Online Retail

Esta tabela descreve as variáveis presentes no conjunto de dados de vendas online.

| Variável    | Descrição                                                                         | Tipo (Original Provável) | Tipo (Planejado/Após Limpeza) | Observações / Pontos de Atenção                                     |
| :---------- | :-------------------------------------------------------------------------------- | :----------------------- | :---------------------------- | :------------------------------------------------------------------ |
| InvoiceNo   | Número da Fatura/Nota Fiscal. Nominal, identificador único para cada transação.    | object                   | string / category             | Se iniciar com 'c', indica um **cancelamento**.                    |
| StockCode   | Código do Produto (item). Nominal, identificador único para cada produto distinto. | object                   | string / category             | Pode conter códigos não padronizados (ex: POST, MANUAL).          |
| Description | Nome do Produto (item). Nominal.                                                  | object                   | string                        | Pode conter valores ausentes. Requer limpeza e padronização.        |
| Quantity    | Quantidade de cada produto (item) por transação. Numérico.                          | int64                    | int64                         | **Valores negativos** indicam devoluções ou ajustes.                 |
| InvoiceDate | Data e Hora da Fatura/Nota Fiscal. O dia e a hora em que a transação foi gerada.  | object                   | datetime64[ns]                | **Precisa converter** para formato Data/Hora adequado.              |
| UnitPrice   | Preço Unitário do produto em **Libras Esterlinas (£)**. Numérico.                  | float64                  | float64                       | Contém **valores zero** que podem precisar de tratamento/análise.   |
| CustomerID  | Número/ID do Cliente. Nominal, identificador único para cada cliente.             | float64 / object         | string / category             | **Muitos valores ausentes (~20-25%)**. Essencial para análise do cliente. |
| Country     | Nome do país onde o cliente reside. Nominal.                                      | object                   | string / category             | Verificar consistência e padronização dos nomes dos países.         |