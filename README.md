# Global-Video-Game-RFR
Esse repositório faz parte do trabalho final do projeto "TIC em Trilhas", na Trilha de Introdução a Machine Learning.

# 1. Bibliotecas e DataFrame
Acontece a importação das bibliotecas principais como pandas, numpy, matplotlib e seaborn, para a manipulação
e visualização de dados. Em seguida, o dataset é carregado a partir de um arquivo em "CSV" e mantido em um dataframe.

# 2. Análise Exploratória de Dados
Certas colunas foram tiradas de foco como "index", "Publisher" e "Rank". 

# Visualização 
Na análise, também se fazem presente os seguintes pontos:
- localizar os 10 jogos mais vendidos; 
- as avaliações desses jogos;
- os gêneros que mais venderam no mundo;
- a média de avaliações dos gêneros;
- as plataformas que lideraram as vendas globais;
- os generos que mais venderam em um intervalo de tempo arbitrário.

# 3. Modelagem preditiva
Por fim, para prever as vendas de jogos no japão, foi utilizado um modelo de regressão.
Após a criação do modelo, o código avalia seu desempenho usando o coeficiente de determinação (R ao quadrado)
e o erro quadrático médio (RMSE).

O modelo é aprimorado a partir da utilização de hiperparâmetros, onde acontece a importação do Grid Search
que testa todas as combinações possíveis de valores para os hiperparâmetros já definidos.
O modelo aprimorado é avaliado novamente utilizando as métricas citadas.

Este código demonstra uma análise ampla dos dados de vendas de videogames e aplica técnicas de tratamento,
visualização e modelagem preditiva em Python ao fazer uso bibliotecas populares como numpy, matplotlib, pandas e scikit-learn.


