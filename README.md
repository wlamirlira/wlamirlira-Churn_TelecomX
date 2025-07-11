# 🔍 Previsão de Churn - TelecomX

Este projeto tem como objetivo prever a evasão (churn) de clientes de uma empresa de telecomunicações, utilizando técnicas de Machine Learning supervisionado.

---

## ✅ Etapas já realizadas

### 1. Carregamento dos dados
- Arquivo CSV original contendo 7267 registros de clientes.
- Variável-alvo: `Churn` (1 = cancelou, 0 = permaneceu).

### 2. Tratamento de valores ausentes
- 224 registros removidos por ausência da variável `Churn`.
- Total final: **7043 clientes válidos**.

### 3. Revisão dos tipos de variáveis
- Variáveis numéricas: como tempo de contrato e valores pagos.
- Variáveis booleanas: codificadas via One-Hot Encoding (ex: `Contract_Two year`).

### 4. Separação em treino e teste
- 80% para treino (5634 registros)
- 20% para teste (1409 registros)
- `train_test_split(random_state=42)` para garantir reprodutibilidade.

---

## ⚠️ Próxima etapa

Início da modelagem:
- Padronização dos dados numéricos
- Treinamento de modelos (Logistic Regression, Random Forest, XGBoost)
- Avaliação com métricas apropriadas
