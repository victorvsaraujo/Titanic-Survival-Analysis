# Análise de Dados de Sobrevivência do Titanic

Este projeto visa explorar os dados do Titanic para entender os fatores que influenciaram a sobrevivência dos passageiros. Utilizando análise exploratória de dados (EDA), técnicas de limpeza e engenharia de dados, foram analisadas variáveis como idade, sexo, classe, tarifa e porto de embarque para identificar padrões e insights sobre as taxas de sobrevivência.

## O que foi feito:

- **Limpeza de Dados**:
  - Tratamento de valores ausentes em colunas como 'Idade', 'Cabine' e 'Embarked'.
  - Substituição de valores ausentes por valores apropriados (como média, moda ou 'Unknown').

- **Engenharia de Recursos**:
  - Reclassificação da coluna 'Survived' para valores legíveis: 0 = 'Não Sobreviveu', 1 = 'Sobreviveu'.
  - Criação da coluna 'Fare_Range' para categorizar os valores da tarifa em 'Alto', 'Médio' e 'Baixo'.

- **Análise Exploratória de Dados (EDA)**:
  - Análise das distribuições de variáveis chave (como Idade, Tarifa e Pclass) e suas correlações.
  - Investigação do impacto de variáveis como 'Sexo', 'Classe' e 'Porto de Embarque' sobre as taxas de sobrevivência.

- **Análise Estatística**:
  - Cálculo de estatísticas descritivas como média, mediana, desvio padrão e assimetria das colunas.
  - Identificação de outliers na coluna 'Fare' (Tarifa).

## Objetivo

O objetivo deste projeto é fornecer uma visão detalhada sobre os fatores que influenciaram a sobrevivência no desastre do Titanic, utilizando técnicas de análise de dados. Além disso, busca-se gerar insights que possam ser aplicados em modelos preditivos e na tomada de decisões.

## Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn

## Como Rodar

1. Clone este repositório:
   ```bash
   git clone https://github.com/victorvsaraujo/Titanic-Survival-Analysis.git
