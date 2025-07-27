<div  style="display: flex;">
    <img alt="Logo da empresa Alura" src="https://www.cuponation.com.br/images/fit-in/256x/images/a/alura_logo.png", style = "width:100px;">
    <img class="company-logo__img" src="https://cdn2.gnarususercontent.com.br/1/1221562/b6256fa6-5fde-4cdd-a4a3-d33ebc90bb6c.png" alt="Logo da empresa - Oracle ONE - Br Geral 8">
   

# Challenge Telecom X 2

Este repositório contém o desafio final de um estudo de caso (com exercício prático) integrante do curso do programa Oracle Next Education - Alura. O objetivo é continuar analisando dados de clientes de uma empresa fictícia de telecomunicações chamada Telecom X, visando entender as causas do alto índice de evasão (churn) dos clientes.

---

## Objetivo

Identificar **clientes com maior risco de evasão (churn)** em uma empresa de telecomunicações, analisando quais variáveis mais influenciam esse comportamento e propondo ações para reduzir a perda de clientes.

---

##  Dados Utilizados

- **Fonte:** Dataset tratado a partir da etapa 1 do projeto Telecom X.
- Inclui informações de:
  - Perfil do cliente
  - Serviços contratados
  - Cobranças
  - Tempo de contrato
  - Variável alvo: `Churn` (evasão)

---

##  Tecnologias e Ferramentas

- **Linguagem:** Python
- **Bibliotecas principais:** 
  - `pandas`, `numpy` para tratamento de dados
  - `scikit-learn` para modelos preditivos
  - `seaborn`, `matplotlib` para visualizações
- **Jupyter Notebook** para análise e documentação.
- **Git e GitHub** para versionamento.
- **Trello** para gestão das etapas do desafio.

---

##  Etapas Realizadas

1. **Preparação de Dados**
   - Carregamento do dataset tratado
   - Limpeza de dados inconsistentes e colunas irrelevantes
   - Transformação de variáveis categóricas

2. **Análise Exploratória de Dados (EDA)**
   - Visualização de distribuição de churn
   - Análise de correlação entre variáveis

3. **Modelagem Preditiva**
   - Modelos aplicados: **Random Forest** e **Regressão Logística**
   - Divisão em dados de treino e teste
   - Avaliação de métricas: Accuracy, Recall, Precision, F1-Score, AUC

4. **Interpretação**
   - Identificação das variáveis mais relevantes
   - Recomendações para retenção de clientes

---

##  Principais Resultados

- Variáveis como **`Contract`**, **`tenure`** e **`MonthlyCharges`** foram as mais relevantes para prever o churn.
- Clientes com contratos mensais e altas cobranças têm maior risco de evasão.
- Recomenda-se ações de fidelização e ofertas personalizadas para este perfil.

---

##  Observações
Este projeto faz parte da trilha de formação em Data Science do programa Oracle One Next Education com a Alura.

---
##  Licença
Este projeto, embora público, é apenas para fins educacionais e não deve ser utilizado comercialmente.

---

