# 📊 TelecomX: Predição de Evasão de Clientes (Churn Prediction)

Este repositório contém um notebook interativo focado na **análise de dados e modelagem preditiva para prever a evasão de clientes em uma empresa de telecomunicações**.  
O projeto utiliza Python e bibliotecas poderosas como `pandas`, `scikit-learn`, `matplotlib` e `seaborn`.

---

## 🎯 Objetivo do Projeto
O objetivo principal é **construir um pipeline de machine learning** para prever se um cliente vai ou não abandonar a empresa (churn).  

As etapas incluem:
- Limpeza e transformação de dados  
- Codificação de variáveis categóricas  
- Análise exploratória e seleção de variáveis relevantes  
- Modelagem supervisionada  
- Avaliação de desempenho com métricas apropriadas  

Este projeto é um exemplo prático da aplicação de ciência de dados em um **cenário real de negócio**, ajudando empresas a entender e reduzir a evasão de clientes.

---

## 🧪 Estrutura do Notebook

### `TelecomX_2.ipynb`

#### Etapas do projeto:

1. **Importação e Inspeção dos Dados**
   - Leitura do dataset tratado (`dados_tratados.csv`)
   - Visualização inicial das colunas e amostras

2. **Remoção de Colunas Irrelevantes**
   - Exclusão de identificadores que não contribuem para a modelagem

3. **Encoding de Variáveis Categóricas**
   - Aplicação de **OneHotEncoder** para variáveis como gênero, contrato, método de pagamento, entre outras
   - Padronização de nomes das colunas após a transformação

4. **Análise de Evasão**
   - Verificação da proporção de clientes que cancelaram (`Evasao`)
   - Visualizações com `matplotlib` e `seaborn`

5. **Correlação e Seleção de Variáveis**
   - Cálculo da matriz de correlação
   - Identificação das variáveis mais relevantes para a evasão

6. **Modelagem Preditiva** *(seção prevista pelo fluxo do notebook)*
   - Construção de modelos de classificação supervisionada
   - Avaliação de desempenho com métricas como:
     > - Acurácia  
     > - Precisão  
     > - Recall  
     > - F1-Score  
     > - Matriz de confusão  

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas
- **Linguagem:** Python  
- **Manipulação de dados:** Pandas, NumPy  
- **Visualização:** Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn  

---

## 📌 Exemplo de Saída (proporção de evasão)

```
Acurácia (Árvore de decisão): 0.7753324163227877
Precisão (Árvore de decisão): 0.3672014260249554
Recall (Árvore de decisão): 0.6041055718475073
F1-Score (Árvore de decisão): 0.4567627494456763
```
