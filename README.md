# Previsão de Avaliações em Estações de Carregamento de Veículos Elétricos

Este projeto tem como objetivo prever se uma estação de carregamento de veículos elétricos possui avaliação (rating) ou não, com base em suas características. A variável alvo utilizada é `has_rating`, que indica a presença (1) ou ausência (0) de uma avaliação.

## Etapas do Projeto

1. **Importação das Bibliotecas**: Utilização de bibliotecas para manipulação de dados, visualização e modelagem.
2. **Carregamento dos Dados**: Leitura da base de dados `ev_data.csv` e criação da variável alvo.
3. **Análise Exploratória de Dados (EDA)**: Visualizações e estatísticas para entender os dados.
4. **Pré-processamento**: Transformações e padronizações com uso de pipelines e PCA.
5. **Treinamento e Validação**: Avaliação de múltiplos modelos de Machine Learning.
6. **Otimização de Parâmetros**: Uso de `GridSearchCV` para encontrar os melhores hiperparâmetros.
7. **Avaliação dos Modelos**: Comparação de desempenho com métricas como AUC e matriz de confusão.
8. **Comparativo de Modelos**: Comparativo de Acurácia dos Modelos 
9. **Conclusão**: Identificação dos modelos mais eficazes e insights sobre os fatores que influenciam a presença de avaliações.

## Modelos Utilizados

- Random Forest
- Naive Bayes
- SVM
- KNN
- XGBoost
- LightGBM

## Resultados

Os modelos XGBoost, LightGBM e Random Forest apresentaram os melhores resultados em termos de acurácia e AUC, sendo os mais eficazes na previsão da presença de avaliações.

## Aplicações

Este projeto pode auxiliar empresas na escolha de locais e estratégias para melhorar a experiência do usuário em estações de carregamento de veículos elétricos.
