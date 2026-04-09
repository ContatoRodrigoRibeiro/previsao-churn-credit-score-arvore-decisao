# Previsão de Churn Bancário com Árvore de Decisão

**Projeto de Ciência de Dados | Módulo 21**

Modelo de **Árvore de Decisão** para prever churn de clientes bancários (Credit Score / Churn).

## 🎯 Objetivo
Prever se um cliente vai sair do banco (Churn) utilizando dados de crédito, idade, saldo, produtos, etc.

## 🛠️ Tecnologias Utilizadas
- Python
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn (DecisionTreeClassifier)
- Comparação com modelo anterior (Naive Bayes - Módulo 20)

## ✨ Principais Etapas
- Carregamento e validação das bases de treino/teste
- Treinamento de Árvore de Decisão (critério Gini)
- Avaliação completa (Acurácia, Recall Macro, Classification Report)
- Redução de features (apenas as 2 mais importantes)
- Visualização da árvore
- Comparação de desempenho com o modelo de Naive Bayes

## 📊 Resultados

| Modelo                        | Acurácia (Teste) | Recall Macro |
|-------------------------------|------------------|--------------|
| Naive Bayes (Módulo 20)       | ~0.72            | ~0.68        |
| Árvore com todas as features  | 0.7900           | 0.7056       |
| Árvore com **Top 2 features** | **0.8451**       | **0.7272**   |

**Melhor modelo:** Árvore de Decisão com apenas 2 features (`Qtd_Produtos` + `Idade`)

## 📁 Estrutura do Projeto
