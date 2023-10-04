# Previsão de aprovação de vistos de trabalho dos EUA com XGBoost e GridSearch
![global-residence-index-LPdaW746WAw-unsplash](https://github.com/silvaelaine/vistos-eua-ML-olympiad/assets/103846225/d2c5f796-603c-4955-8099-69cfcead9df2)

## Objetivo
Este projeto foi resultado da Olimpíada de Machine Learning do Google que ocorreu na Uninter usando a Metodologia Crisp-DM. O desafio tinha como objetivo prever a aprovação de vistos de trabalho dos EUA. Foi atigindo um f1-score de 0.80 usando o algoritmo XGBoost e GridSearch para otimizar hiperparâmetros.

## Tecnologias
  * Python
  * Google Colab
  * Matplotlib
  * Seaborn 
  * Pandas
  * Numpy
  * XGBoost
  * GridSearch

## Metodologia 
  * Crisp-DM

## Conclusões do Projeto
Após fazer feature engineering e treinar o modelo sem hiperparâmetros, o f1-score foi de 0.73. Após realizar padronização, que é redimensionar os recursos para a mesma escala, o f1-score foi para 0.80. Mario "Kazanova", um dos melhores competidores do Kaggle, cita considerar tudo como hiperparâmetro. Exemplo: scaling, as transformações das variáveis e até os métodos de seleção de variáveis.

Em seguida, foi usado GridSearch. Após treinar o modelo com os melhores parâmetros encontrados, o f1-score foi para 0.81, tendo pouco improviso.
