# 📉 Análise e Previsão de Evasão de Clientes (Churn) - Telecom X

## 📄 Descrição do Projeto

Este projeto tem como objetivo principal analisar e prever a evasão de clientes (churn) da empresa de telecomunicações Telecom X. Através da aplicação de técnicas de análise exploratória de dados (EDA) e modelos de Machine Learning, buscamos identificar os principais fatores que levam os clientes a cancelar seus serviços e construir um modelo preditivo capaz de sinalizar clientes de alto risco.

O resultado do projeto inclui insights valiosos sobre o perfil dos clientes que evadem e recomendações estratégicas para a empresa, visando a redução do churn.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python
* **Bibliotecas:**
    * `pandas`: Manipulação e análise de dados.
    * `numpy`: Computação numérica.
    * `scikit-learn`: Modelos de Machine Learning e pré-processamento.
    * `matplotlib` & `seaborn`: Visualização de dados.
* **Ambiente:** Google Colab

---

## 📂 Estrutura do Projeto

O notebook TeleconX_P2.ipynb está dividido nas seguintes etapas:

1.  **Carregamento e Análise Exploratória (EDA):** Carregamento do dataset tratado e inspeção inicial dos dados.
2.  **Pré-processamento dos Dados:** Tratamento de valores ausentes, codificação de variáveis categóricas e normalização de variáveis numéricas.
3.  **Modelagem Preditiva:** Divisão dos dados e treinamento de dois modelos de classificação:
    * Regressão Logística
    * Random Forest
4.  **Avaliação e Interpretação:** Análise do desempenho dos modelos e identificação das variáveis mais importantes para a previsão de churn.
5.  **Relatório Final:** Resumo das descobertas e recomendações estratégicas.

---

## 💡 Principais Descobertas (Insights)

* **Tipo de Contrato:** Clientes com **contratos mensais** apresentam a maior taxa de churn, sugerindo menor fidelização.
* **Tempo de Serviço:** A evasão é mais comum entre clientes com **pouco tempo de serviço**, indicando que a experiência inicial é crítica.
* **Serviços Adicionais:** A ausência de **serviços de internet** ou de **suporte técnico** é um forte preditor de churn.

---

## 🤖 Desempenho dos Modelos

Dois modelos foram avaliados, e o modelo de **Random Forest** demonstrou o melhor desempenho para a tarefa de previsão de churn. Ele foi capaz de identificar com maior precisão os clientes que iriam evadir.

--- Avaliação Final do Modelo Random Forest ---
Acurácia do modelo Random Forest: 0.77

Relatório de Classificação:
              precision    recall  f1-score   support

           0       0.82      0.88      0.85      1035
           1       0.58      0.46      0.51       374

    accuracy                           0.77      1409
   macro avg       0.70      0.67      0.68      1409
weighted avg       0.76      0.77      0.76      1409
---

## 🚀 Recomendações Estratégicas

Com base nos insights e na capacidade preditiva do modelo, as seguintes ações são sugeridas para a Telecom X:

* **Programas de Fidelidade:** Criar ofertas exclusivas para clientes com contrato mensal, incentivando a migração para planos de longo prazo.
* **Acompanhamento Pós-Venda:** Implementar um programa de contato proativo para novos clientes nos primeiros meses, garantindo sua satisfação e resolvendo problemas rapidamente.

---

## 💻 Como Executar o Projeto

1.  Abra o arquivo TeleconX_P2.ipynb` no Google Colab.
2.  Execute todas as células sequencialmente para reproduzir a análise e os modelos.

---

## ✍️ Autor(a)

* [Seu Nome Completo]
* [Seu LinkedIn ou Outro Contato Opcional]