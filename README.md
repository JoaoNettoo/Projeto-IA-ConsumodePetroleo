⛽ Predição do Consumo de Petróleo

✨ Sobre o Projeto

Este projeto utiliza Machine Learning para prever as variações no consumo de petróleo ao longo dos anos. A abordagem usada é a de classificação, categorizando os anos em "Aumento", "Diminuição" ou "Estável" com base nos padrões históricos.

📈 Tecnologias Utilizadas

Linguagem: Python

Bibliotecas: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Ambiente: Google Colab

Base de Dados: "World Largest Oil Reserves & Consumption Dataset" (Kaggle)

🔄 Processamento de Dados

Remoção da coluna "entity", substituída por valores numéricos em "Entity_World".

Criação da coluna total_consumo_anual somando os valores de consumo por ano.

Normalização e categorização do consumo em "Baixo", "Médio" e "Alto".

🌟 Modelos Utilizados

O projeto compara 5 modelos de classificação para prever a variação no consumo:

RandomForestClassifier ✅ 

LogisticRegression ✅ 

GradientBoostingClassifier ✅

SVM ⚠️ 

DecisionTreeClassifier ⚠️

📊 Métricas de Avaliação

Acurácia

Matriz de confusão

Precisão, Recall e F1-Score

🚀 Melhorias Futuras

✅ Testar novos modelos

✅ Implementar predição para anos futuros

✅ Criar API para consumir previsões




