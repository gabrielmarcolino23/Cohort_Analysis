# Análise de Cohort em Python

Este repositório contém um código Python para realizar uma análise de cohort e uma explicação sobre o que é essa análise.

## O que é Análise de Cohort?

A análise de cohort é uma técnica poderosa usada em análises de dados para entender melhor o comportamento dos clientes ao longo do tempo. Ela agrupa os clientes em diferentes segmentos com base no momento em que eles realizaram uma determinada ação ou evento, como a primeira compra.

Por exemplo, em um negócio de comércio eletrônico, podemos agrupar os clientes em cohorts com base no mês em que fizeram sua primeira compra. Em seguida, podemos analisar como esses cohorts se comportam ao longo do tempo em termos de retenção de clientes, taxa de compra repetida, valor médio do pedido, entre outros indicadores-chave de desempenho.

## Como funciona o código?

O código fornecido neste repositório é escrito em Python e usa bibliotecas populares como Pandas, NumPy, Matplotlib e Seaborn para realizar uma análise de cohort. Ele lê um conjunto de dados de exemplo (Online_Retail.xlsx), realiza algumas etapas de pré-processamento nos dados, como renomear colunas e criar um cohort para cada cliente. Em seguida, ele calcula a retenção de clientes ao longo do tempo e gera um heatmap para visualizar os resultados.

## Como usar o código?

Para usar o código, siga estas etapas:

1. Clone este repositório em seu ambiente local:

```bash
git clone https://github.com/gabrielmarcolino23/Cohort_Analysis.git
```

2. Certifique-se de ter as bibliotecas necessárias instaladas. Você pode instalá-las executando:

```bash
pip install pandas numpy matplotlib seaborn
```

3. O script lerá o conjunto de dados fornecido, realizará a análise de cohort e gerará um heatmap para visualizar os resultados.

## Contribuições

Contribuições são bem-vindas! Se você tiver sugestões de melhorias para o código ou quiser adicionar exemplos adicionais, sinta-se à vontade para enviar uma solicitação pull.
