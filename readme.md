Etapas do projeto:

* Data Collection
    * leitura de arquivo

* Data Preparation

    * EDA
        * Estudo de correlação das variáveis
        * histograma das doenças em comorbidade
        * histograma de agrupamento de idades
        * histograma idades x genero

    * Data preprocessing (Transformação de dados)
        * Dados nulos (dados faltantes)
        * String em coluna numérica (como tratar?)
        * Normalização dos Dados  - Normalization vs Standardization
        * Balanceamento das Classes (SMOTE e variantes)
        * Engenharia de Variáveis (Feature Engineering)

    * Data Splitting


* Treinamento dos modelos
    * Escolha dos algoritmos
    * Overfit e regularização
    * Tuning de Hiperparametros

* Avaliação dos modelos
    
    * Avaliação dos algoritmos
        * Matriz de Confusão (porcentagens de TP, FP, TN, FN)
        * Classification
            * acuracia = (TP+TN)/(TP+ TN + FP + FN)
            * precisão = TP / (TP + FP)
            * recall = TP / (TP + FN)
            * f1-score = (2 * Precision X recall) / (precision + recall)
        
    * Feature Importance
    * Training/inference cost
