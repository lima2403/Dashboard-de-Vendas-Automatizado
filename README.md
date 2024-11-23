# Dashboard-de-Vendas-Automatizado

Esse é um projeto de Análise de Vendas no Power BI automatizado de vendas que desenvolvi para poder simular um cenario aonde dados são gerados de maneira constante e o Dashboard precisa ser atualizado constante mente 

Foram usadas 4 tecnologias para criar esse Dashboard: 

## Power BI: 
Ambiente de desenvolvimento do relatório.

## Figma
Ambiente para criar as imagens e backgronds usados.

## Python e Google Colab
Funciona como um gerador de dados aletórios.

## Big Query (Google Cloud)
Recebe os dados gerados no Google Colab e envia para o Power BI de maneira automatica.


DE maneira mais detalhada, ele funciona da seguinte maneira: 
1 - Usando o Google Colab, criei um script em Python usando bibliotecas Faker, Pandas e Random para que fosse gerada uma base de dados de maneira aleatória, e usando bibliotecas do Google Cloud e Big Query, envia para a base de dados no Big Query.
2 - O Big Query, que esta conectado em tempo real ao Power BI, recebe os dados gerados, organiza eles em forma de tabela e envia para o Dashboard.
3 - O Power BI recebe os dados e, usando um Gateway, atualiza os graficos e métricas com a nova adição de dados.


Para ter acesso a versão online do Dashboard, acesse o link:
https://app.powerbi.com/view?r=eyJrIjoiMGU4OWRiYTItMTA4MS00YzdjLWJhYjUtNTJjZTdhOTRlZmM0IiwidCI6ImIxMDUxYzRiLTNiOTQtNDFhYi05NDQxLWU3M2E3MjM0MmZkZCJ9

