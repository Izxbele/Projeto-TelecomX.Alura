# 📊 Análise de Evasão de Clientes - Projeto Telecom X

Este projeto faz parte do desafio do Programa ONE (Oracle Next Education) em parceria com a Alura, com foco em **análise de dados** e **ciência de dados aplicada**. O objetivo é entender os fatores que influenciam a evasão de clientes (churn) em uma empresa de telecomunicações fictícia, chamada **Telecom X**.

## 📁 Arquivo Principal

- `TelecomX_BR.ipynb` → Notebook contendo todas as etapas de **extração**, **transformação**, **análise exploratória**, **visualizações** e **relatório final**.

---

## 🚀 Objetivo

- Realizar o processo completo de ETL (Extração, Transformação e Análise).
- Identificar padrões de comportamento e variáveis relacionadas ao cancelamento de clientes.
- Produzir insights visuais para ajudar na **redução da taxa de churn**.
- Fornecer recomendações práticas com base em dados reais simulados.

---

## 🧪 Etapas Realizadas

1. **📥 Extração dos Dados**
   - Leitura do dataset em formato `.json`.

2. **🔧 Transformação**
   - Normalização dos dados aninhados.
   - Padronização de colunas e tradução para português.
   - Conversão de variáveis categóricas em binárias.
   - Criação de novas colunas como `Contas_Diarias` e `Qtd_Servicos`.

3. **📊 Análise Exploratória de Dados (EDA)**
   - Análise descritiva com histogramas e medidas estatísticas.
   - Gráficos de barras, pizza e boxplots para investigar relações com churn.
   - Matriz de correlação para identificar relações entre variáveis.
   - Análises segmentadas por variáveis categóricas e numéricas.

4. **📝 Relatório Final**
   - Documento completo dentro do notebook com:
     - Introdução
     - Tratamento de Dados
     - Análises
     - Conclusões
     - Recomendações

---

## 📎 Ferramentas Utilizadas

- Python 
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Google Colab

---

## 📌 Resultados e Insights

- Clientes com **contrato mensal, cobrança alta e poucos serviços** apresentaram maior risco de evasão.
- Contratos anuais e métodos de pagamento automáticos estão associados à permanência.
- Recomendado segmentar clientes com maior risco para **ações preventivas**.

---

## ✅ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/TelecomX-Projeto.git
