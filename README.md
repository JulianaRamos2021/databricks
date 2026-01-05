# Databricks

# Análise do Uso de Cartões de Crédito no Brasil vs Indicadores Macroeconômicos Globais

## Objetivo
Analisar a relação entre métricas de cartões de crédito no Brasil e a inflação dos EUA (CPI),
avaliando possíveis correlações temporais ao longo do período analisado.

## Dados Utilizados
 Banco Central do Brasil: dados de cartões de crédito
 API Alpha Vantage: CPI (Estados Unidos)

## Metodologia
 Ingestão e tratamento de dados no Databricks
 Padronização temporal (mensal)
 Criação de tabelas analíticas (Delta)
 Análise de correlação (Pearson)

## Principais Resultados
 Correlação fraca e positiva entre inflação dos EUA e métricas de cartões no Brasil.

## Tecnologias
 Databricks (Spark SQL, PySpark)
 Python

## Observações
Este projeto tem caráter exploratório e não implica causalidade.
