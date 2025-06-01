# Churn Prediction com Python, SQL e Machine Learning

Este projeto tem como objetivo prever o cancelamento de clientes (churn) em uma empresa de telecomunicações. Utilizando Python, SQL e algoritmos de Machine Learning, o modelo analisa padrões de comportamento e características dos clientes para antecipar a evasão.

---

## Objetivo

- Entender os fatores que influenciam o churn
- Criar e comparar diferentes modelos preditivos
- Ajustar limiares (thresholds) para melhor desempenho
- Tratar desbalanceamento com técnicas como **SMOTE**

---

## Tecnologias Utilizadas

- **Python** (Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, XGBoost, imbalanced-learn)
- **SQL** (para análises exploratórias e manipulação de dados)
- **Google Colab**
- **Gráficos**: ROC, Precision-Recall, Matriz de Confusão

---

## Modelos Aplicados

- **Regressão Logística** com ajuste de threshold
- **Random Forest + SMOTE**
- **XGBoost**

Todos avaliados com:
- Accuracy
- Precision
- Recall
- F1-Score
- Curva ROC
- Curva Precision-Recall

---

## Visualizações Criadas

- Matriz de confusão
- Curva ROC (Receiver Operating Characteristic)
- Curva Precision-Recall
- Importância das features

---

## Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/gabrielbdoc/churn-prediction.git
cd churn-prediction
```
2. Instale os pacotes
```bash
pip install -r requirements.txt
