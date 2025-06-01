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
```
2. Instale os pacotes
```bash
pip install -r requirements.txt
```

## Conclusão (resumo)
O projeto alcançou resultados satisfatórios na tarefa de previsão de churn, com a Regressão Logística apresentando o melhor desempenho geral entre os modelos testados (AUC = 0.83 e AP = 0.62). XGBoost e Random Forest com SMOTE também mostraram performance consistente, ambos com AUC = 0.81.

As curvas ROC e Precision-Recall indicam boa capacidade de discriminação dos modelos. No entanto, as matrizes de confusão revelaram uma tendência considerável à geração de falsos positivos, o que merece atenção especial, principalmente em contextos onde ações baseadas em previsões equivocadas possam implicar custos ou experiências negativas para clientes.

Para uma análise mais detalhada, incluindo gráficos comparativos e insights sobre os modelos utilizados, acesse a seção Conclusão no final do notebook Churn.ipynb.
