# Comparação AdaBoost vs Gradient Boosting Machine (GBM)

Este repositório apresenta uma comparação prática e teórica entre **AdaBoost** e **Gradient Boosting Machine (GBM)**, incluindo variações como **Stochastic GBM**, utilizando Python e a biblioteca Scikit-learn.

---

## 📌 Conteúdo
- Diferenças conceituais entre AdaBoost e GBM.
- Exemplos de classificação e regressão.
- Otimização de hiperparâmetros com **GridSearchCV**.
- Comparação entre GBM tradicional e **Stochastic GBM**.
- Código totalmente executável em **Jupyter Notebook**.

---

## 🔍 Diferenças principais

| Característica           | AdaBoost | GBM |
|--------------------------|----------|-----|
| **Base Learners**        | Um modelo fraco por vez, ajustando pesos. | Múltiplos modelos que corrigem erros residuais. |
| **Foco do ajuste**       | Pesos das amostras incorretas. | Gradientes dos erros residuais. |
| **Função de perda**      | Minimiza exponencial da perda de classificação. | Flexível: regressão ou classificação. |
| **Método de atualização**| Peso global do modelo fraco. | Redução dos gradientes. |
| **Velocidade**           | Geralmente mais rápido. | Mais lento, mas mais flexível. |

---

## 🛠 Tecnologias utilizadas
- Python
- Scikit-learn
- NumPy / Pandas
- Matplotlib

---

## 📊 Resultados de exemplo

**Classificação (GradientBoostingClassifier)**  
Acurácia: ~0.9279 no conjunto de teste.  

**Regressão (GradientBoostingRegressor)**  
MSE: ~3.33 no conjunto de teste.  

---
