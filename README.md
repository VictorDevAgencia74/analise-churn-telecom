# 📊 Análise de Churn - Telecom

[![Python](https://img.shields.io/badge/Python-3.12-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0-green.svg)](https://pandas.pydata.org/)
[![Metabase](https://img.shields.io/badge/Metabase-Dashboard-orange.svg)](https://www.metabase.com/)
[![Supabase](https://img.shields.io/badge/Supabase-PostgreSQL-3ecf8e.svg)](https://supabase.com/)
[![License](https://img.shields.io/badge/License-Educational-lightgrey.svg)]()

## 📌 Visão Geral

Projeto completo de análise de churn (cancelamento de clientes) para uma empresa de telecomunicações. O objetivo é identificar padrões de cancelamento, entender quem são os clientes que mais cancelam e fornecer recomendações acionáveis para reduzir a taxa de churn.

**📈 Taxa de Churn identificada: 26,6%**

## 📁 Fonte dos Dados

- **Dataset:** Telco Customer Churn (Kaggle)
- **Link:** [https://www.kaggle.com/datasets/blastchar/telco-customer-churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Descrição:** Dados anonimizados de 7.043 clientes de uma empresa de telecomunicações
- **Uso:** Apenas para fins educacionais e de portfólio

## 🛠️ Ferramentas Utilizadas

| Etapa | Ferramenta |
|-------|------------|
| **Limpeza e tratamento** | Python (Pandas, NumPy) + Jupyter Notebook |
| **Banco de dados na nuvem** | Supabase (PostgreSQL) |
| **Dashboard** | Metabase |
| **Queries SQL** | Análises customizadas |
| **Versionamento** | Git + GitHub |

## 📈 Principais Resultados

| Métrica | Valor |
|---------|-------|
| **Taxa de Churn Geral** | 26,6% |
| **Clientes ativos** | 5.163 (73,4%) |
| **Clientes cancelados** | 1.869 (26,6%) |
| **Perda mensal média** | 156 clientes |
| **Churn mensal equivalente** | 2,2% |

### 🔍 Insights-Chave

1. **Contrato mensal é o maior problema** - 88,6% dos cancelamentos vêm deste grupo
2. **Primeiros 6 meses são críticos** - Churn de 45% neste período vs 8% após 2 anos
3. **Pagamento por boleto tem maior risco** - Taxa 2x maior que débito automático
4. **Perfil de maior risco** - Contrato mensal + Boleto + 0-6 meses = 68% de churn

## 📊 Dashboard Interativo

🔗 **Acesse o dashboard online:** [http://localhost:3000/public/dashboard/7cc54f1b-bd5c-4817-8dfd-c7f9a8c5d409](http://localhost:3000/public/dashboard/7cc54f1b-bd5c-4817-8dfd-c7f9a8c5d409)

### Componentes do Dashboard

| Card | Tipo | O que mostra |
|------|------|--------------|
| 01 | Número grande | Taxa de Churn (26,6%) |
| 02 | Gráfico de barras | Churn por tipo de contrato |
| 03 | Gráfico de barras | Churn por forma de pagamento |
| 04 | Gráfico de barras | Churn por tempo de uso (tenure) |
| 05 | Tabela | Perfil de risco (top 10 combinações) |
| 06 | Texto | Insights e recomendações de negócio |

## 📁 Estrutura do Projeto
