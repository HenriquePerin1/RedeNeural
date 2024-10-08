# Projeto de Rede Neural para Classificação de Espécies de Iris

## Descrição
Este projeto implementa uma rede neural simples usando TensorFlow e Keras para classificar as espécies de flores Iris (Setosa, Versicolor e Virginica) com base em quatro características: comprimento e largura das pétalas e sépalas.

## Objetivo
Aplicar técnicas de redes neurais para resolver um problema clássico de classificação multiclasse, utilizando camadas densas, funções de ativação (ReLU e Softmax) e métodos de regularização (Dropout) para melhorar a generalização do modelo. O projeto inclui visualizações dos resultados e análise de previsões.

## Funcionalidades
- **Carregamento e Pré-processamento de Dados**: O conjunto de dados Iris é carregado e padronizado com `StandardScaler`.
- **Criação e Treinamento do Modelo**:
  - Modelo com camadas densas e Dropout para reduzir overfitting.
  - Utiliza `sparse_categorical_crossentropy` como função de perda e o otimizador `adam`.
  - Treinamento com validação cruzada e `Early Stopping` para melhorar a eficiência.
- **Visualização de Resultados**:
  - Gráfico da acurácia durante o treinamento.
  - Matriz de confusão para avaliar o desempenho do modelo.
- **Análise de Resultados**: Exibição de tabelas com as melhores e piores previsões, permitindo uma análise detalhada do desempenho.

## Tecnologias Utilizadas
- **Linguagem**: Python
- **Bibliotecas**:
  - TensorFlow / Keras: criação e treinamento do modelo.
  - Pandas e NumPy: manipulação de dados.
  - Matplotlib: visualizações gráficas.
  - Scikit-learn: pré-processamento e avaliação do modelo.

## Resultados
O modelo apresenta alta acurácia na classificação das espécies de Iris, com métricas claras de desempenho. As tabelas de melhores e piores resultados oferecem uma visão detalhada das forças e fraquezas do modelo.
