# Projeto de Avaliação de Métricas de Classificação (MNIST CNN)

## Objetivo

O principal objetivo deste projeto é ir além da métrica de acurácia, realizando uma **avaliação detalhada e robusta** de um modelo de classificação. O foco é implementar o cálculo das principais métricas derivadas da matriz de confusão para diagnosticar precisamente o desempenho do modelo em cada classe.

As métricas calculadas e analisadas são:
* **Precisão (Precision)**
* **Sensibilidade (Recall)**
* **Especificidade (Specificity)**
* **F1-score**

## Metodologia

O projeto segue um pipeline de Machine Learning padrão, com uma etapa de avaliação aprofundada:

1.  **Preparação dos Dados:** O dataset **MNIST** (dígitos escritos à mão) é carregado e normalizado.
2.  **Modelagem:** Uma **Rede Neural Convolucional (CNN)** é construída e treinada para a tarefa de classificação de 10 classes (dígitos de 0 a 9).
3.  **Geração da Matriz de Confusão:** O modelo faz previsões no conjunto de teste, e a matriz de confusão 10x10 é gerada, comparando os rótulos verdadeiros com as previsões.
4.  **Cálculo das Métricas:** Para cada uma das 10 classes, o problema multiclasse é transformado em uma visão **"Uma Classe vs. Todas as Outras"** para a extração dos valores de VP, VN, FP e FN.
5.  **Análise e Visualização:** As métricas são calculadas e impressas por classe, e um **heatmap** visual da matriz de confusão normalizada é exibido.

## Tecnologias Usadas

| Tecnologia | Finalidade Principal |
| :--- | :--- |
| **Python 3.x** | Linguagem de programação central. |
| **TensorFlow/Keras** | Desenvolvimento e treinamento da Rede Neural Convolucional (CNN). |
| **NumPy** | Operações matemáticas de alto desempenho e manipulação da matriz de confusão. |
| **Pandas** | Estruturação dos dados para visualização da matriz de confusão. |
| **Matplotlib/Seaborn** | Geração do mapa de calor (heatmap) para a matriz de confusão. |
