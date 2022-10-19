# FootballPredictions - previsão do resultado de jogos do Campeonato Brasileiro
Neste repositório você encontrará algumas analises, modelos e dados que utilizei
para avaliar a previsibilidade dos resultados dos jogos do brasileirão.

## Dados, modelos e resultados
Os dados estão disponíveis neste repositório, mas foram extraídos do Kaggle e o link está nas referências. O conjunto de dados com estatísticas das partidas foi utilizado também para prever (classificar) os resultados das partidas. Apesar destas informações só estarem disponíveis posteriormente ao jogo, caso os resultados fossem bons, poderiam ser estimadas antes do jogo por algum modelo treinado nessa tarefa.

Até o momento eu testei alguns modelos de machine learning, mas os resultados na cross-validation tem acurácia média menor que 50%, o que fez com que esse projeto ainda não evoluísse para uma estratégia de apostas, como era a ideia inicial.

Suponho que as dificuldades para as previsões são:
### 1. Presença de empates
Mesmo com muitos chutes, posse de bola e outros aspectos, um time pode não fazer gols ou não fazer gols o suficiente para vencer um adversário inferior.
### 2. Jogo com baixo score
Similar ao item 1, o futebol tem poucos "pontos", o que também parece dificultar a predição dos resultados das partidas.

## Conclusões
A primeira vista, parece promissor, mas outras informações relevantes precisariam ser incorporadas, como: escalações, análises de sentimentos de redes sociais (NLP), odds de casas de apostas, análises de comentaristas esportivos (NLP) e etc. 

## Referências
Dataset: https://www.kaggle.com/datasets/adaoduque/campeonato-brasileiro-de-futebol

Notebook interessante: https://www.kaggle.com/code/sslp23/modelo-de-previs-o-para-o-campeonato-brasileiro

Artigo: Tax, N. and Joustra, Y.: Predicting The Dutch Football Competition Using Public Data: A Machine Learning Approach. Transactions on Knowledge and Data Engineering, Vol X. No. X, 2015.
