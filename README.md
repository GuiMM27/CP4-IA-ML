# 💳 Detecção de Fraudes em Cartões de Crédito

Este projeto tem como objetivo detectar transações financeiras fraudulentas lidando com o desafio de um conjunto de dados **altamente desbalanceado** (apenas ~0,17% das transações são fraudes). 

Para isso, foi feita uma comparação crítica entre duas abordagens de Machine Learning:
* **Supervisionada:** Regressão Logística (aplicando balanceamento de classes e regularização).
* **Não Supervisionada:** Isolation Forest (focado em detecção de anomalias estruturais).

Em ambas as abordagens, a análise foi realizada **com e sem a aplicação de PCA** (Análise de Componentes Principais), avaliando o desempenho através de Matrizes de Confusão e priorizando métricas de negócio (Recall e Precision) em vez de simples Acurácia.

## 🛠️ Tecnologias Utilizadas
* Python
* Pandas & NumPy (Manipulação de dados)
* Scikit-Learn (Modelagem de Machine Learning, PCA, Métricas)
* Matplotlib & Seaborn (Visualização de dados)

## ⚠️ Como executar este projeto
Devido ao limite de tamanho de arquivos do GitHub (100 MB), o conjunto de dados original não está neste repositório. Para rodar o notebook (`.ipynb`) na sua máquina ou no Google Colab:

1. Faça o download do dataset no Kaggle: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
2. Extraia o arquivo `creditcard.csv`.
3. Coloque o arquivo CSV no mesmo diretório do notebook.
4. Execute as células do notebook sequencialmente.
