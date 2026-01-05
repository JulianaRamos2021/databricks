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




# Cartões Emitidos x Inflação (EUA)

O gráfico apresenta a evolução da quantidade de cartões de crédito emitidos no Brasil em comparação com a inflação dos Estados Unidos (CPI).

Observa-se que a emissão de cartões mantém uma trajetória de crescimento ao longo do período, com variações pontuais, enquanto a inflação dos EUA apresenta movimentos cíclicos mais voláteis. Assim como no caso dos cartões ativos, não há uma relação visual forte ou imediata entre as duas séries.

O comportamento sugere que a decisão de emissão de novos cartões no Brasil está mais associada a estratégias de mercado, expansão do crédito e fatores domésticos, do que a variações diretas da inflação americana.

Este resultado é consistente com a correlação positiva, porém fraca, encontrada na análise quantitativa.
<img width="949" height="502" alt="image" src="https://github.com/user-attachments/assets/d97add56-5f0c-4cdc-99fd-8c1082811388" />

# Quantidade de Transações x Inflação (EUA)

O gráfico apresenta a evolução mensal da quantidade de transações com cartões de crédito no Brasil em comparação com a inflação dos Estados Unidos (CPI).

Observa-se um padrão fortemente sazonal na quantidade de transações, com picos recorrentes ao longo dos anos. Esses picos indicam períodos específicos de maior uso do cartão, possivelmente associados a ciclos de consumo, datas sazonais ou características do próprio dado agregado.

Por outro lado, a inflação dos EUA apresenta uma variação muito mais suave e gradual, sem acompanhar os movimentos bruscos observados na série de transações. Visualmente, não há coincidência consistente entre os picos de transações e aumentos ou quedas relevantes da inflação.

Esse comportamento reforça a conclusão de que a quantidade de transações no Brasil não é diretamente influenciada por variações inflacionárias externas, sendo predominantemente explicada por fatores internos e padrões sazonais de consumo.

O gráfico é consistente com a correlação fraca observada na análise estatística.
<img width="955" height="503" alt="image" src="https://github.com/user-attachments/assets/a2f8b54b-ecc6-4635-83b6-c24319b99a4f" />





