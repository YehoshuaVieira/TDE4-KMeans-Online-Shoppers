# TDE 4 — Clusterização com K-means

## Sobre o projeto

Este projeto foi desenvolvido como parte do trabalho prático de Matemática Computacional.

O objetivo é aplicar o algoritmo K-means para realizar a clusterização do conjunto de dados **Online Shoppers Purchasing Intention Dataset**, identificando grupos de visitantes de uma loja virtual com comportamentos semelhantes.

## Dataset

- **Nome:** Online Shoppers Purchasing Intention Dataset
- **Origem:** UCI Machine Learning Repository
- **Quantidade de registros:** 12.330 sessões
- **Atributos originais:** 18

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Etapas desenvolvidas

1. Conhecimento e análise do conjunto de dados.
2. Preparação dos dados e tratamento das variáveis.
3. Padronização dos atributos.
4. Aplicação do algoritmo K-means com inicialização K-means++.
5. Escolha do número de clusters utilizando o método do cotovelo e o coeficiente de silhueta.
6. Interpretação dos grupos encontrados.
7. Avaliação crítica dos resultados.

## Resultado

Após comparar os valores do método do cotovelo e do coeficiente de silhueta, foi escolhido **K = 3**.

Foram identificados três grupos de visitantes, com diferentes níveis de interação com as páginas da loja virtual.

Os resultados também indicaram limitações na separação dos grupos, discutidas no notebook.

## Como executar

1. Abra o arquivo `.ipynb` no Google Colab.
2. Disponibilize o arquivo CSV do dataset no ambiente.
3. Execute as células na ordem apresentada.

## Integrantes

- Yehoshua vieira pimentel bezerra - 20242130146
- Herman Fernandes De Figueiredo - 20242130147
- Matheus Barros Wenes Vieira - 2022213521

## Fonte dos dados

UCI Machine Learning Repository — Online Shoppers Purchasing Intention Dataset.

[https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset)
