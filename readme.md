## Etapas do projeto:
![diagrama.webp](https://raw.githubusercontent.com/julia-freitas/TCC-2023/main/diagrama.webp)

### Data Collection
    - leitura de arquivo

### Data Preparation

    - EDA
        - Estudo de correlação das variáveis
        - histograma das doenças em comorbidade
        - histograma de agrupamento de idades
        - histograma idades x genero

    - Data preprocessing (Transformação de dados)
        - Dados nulos (dados faltantes)
        * String em coluna numérica (como tratar?)
        * Normalização dos Dados  - Normalization vs Standardization
        * Balanceamento das Classes (SMOTE e variantes)
        * Engenharia de Variáveis (Feature Engineering)

    * Data Splitting


### Treinamento dos modelos
    * Escolha dos algoritmos
    * Overfit e regularização
    * Tuning de Hiperparametros

### Avaliação dos modelos
    
    * Avaliação dos algoritmos
        * Matriz de Confusão (porcentagens de TP, FP, TN, FN)
        * Classification
            * acuracia = (TP+TN)/(TP+ TN + FP + FN)
            * precisão = TP / (TP + FP)
            * recall = TP / (TP + FN)
            * f1-score = (2 * Precision X recall) / (precision + recall)
        
    * Feature Importance
    * Training/inference cost

----------------------------------------------------------------------------------------------
### Trabalhos futuros:

* [Categorizacao da performance cognitiva com base nos outros testes de memoria (memoria imediata, memoria recente e fluencia verbal)](https://alz-journals.onlinelibrary.wiley.com/doi/epdf/10.1002/alz.12820) - [aggregated information from 4 cognitive tests (memory (immediate and delayed), time orientation, verbal fluency, processing speed) to obtain cognitive function scores](https://agsjournals.onlinelibrary.wiley.com/doi/full/10.1111/jgs.15312) 

 * Padroes nos aspectos cognitivos no desenvolvimento de outras doencas e transtornos mentais, no geral
    * [Walking Speed, Cognitive Function, and Dementia Risk in the English Longitudinal Study of Ageing](https://agsjournals.onlinelibrary.wiley.com/doi/full/10.1111/jgs.15312)    
