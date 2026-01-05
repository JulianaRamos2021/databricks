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
Este projeto tem caráter apenas exploratório.




# Análise Gráfica — Cartões Ativos x Inflação (EUA)

O gráfico compara a evolução do número de cartões de crédito ativos no Brasil com a inflação dos Estados Unidos (CPI) ao longo do tempo.

Visualmente, é possível observar que:

O número de cartões ativos apresenta uma tendência de crescimento contínuo, com variações ao longo dos anos.

A inflação dos EUA possui movimentos cíclicos, com períodos de aceleração e desaceleração bem definidos.

Não há um movimento claramente sincronizado entre as duas séries, reforçando a ideia de que o comportamento dos cartões no Brasil não reage diretamente às variações da inflação americana.

Essa percepção visual está alinhada com o resultado quantitativo da correlação, que indicou uma relação positiva, porém fraca, entre as variáveis.

Em termos práticos, o gráfico sugere que, embora indicadores macroeconômicos globais possam exercer alguma influência indireta, o crescimento do uso de cartões de crédito no Brasil é majoritariamente guiado por fatores domésticos, como renda, crédito local e dinâmica econômica interna.

<img width="954" height="515" alt="image" src="https://github.com/user-attachments/assets/89b0bce9-c861-490f-9a47-47f063d2c55f" />



