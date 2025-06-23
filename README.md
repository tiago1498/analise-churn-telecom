# 📊 Análise de Evasão de Clientes (Churn) — TelecomX

Este projeto tem como objetivo identificar os principais fatores que influenciam a evasão de clientes em uma empresa de telecomunicações fictícia chamada **TelecomX**. Através de uma análise exploratória de dados, buscamos gerar **insights práticos** e **recomendações estratégicas** para reduzir o churn.

---

## 🔍 Sobre o Projeto

- 📁 Dados públicos fornecidos em formato `.json`
- 📌 Separação e tratamento de diferentes tabelas (clientes, serviços, contas)
- 🧹 Limpeza e padronização dos dados
- 📊 Análise exploratória com gráficos e correlações
- 💡 Geração de insights e recomendações de retenção

---

## 🛠 Tecnologias Utilizadas

- Python 3.x
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Google Colab 
---

## 📁 Organização dos Dados

O arquivo JSON contém informações em 4 blocos:
- `customer`: informações do cliente
- `phone`: plano telefônico
- `internet`: serviços de internet
- `account`: cobrança e contrato

---

## 📈 Principais Análises Realizadas

- Comparação de churn por tipo de contrato, serviço e forma de pagamento
- Distribuição de tempo de permanência (`tenure`) e faturamento total
- Criação de métricas auxiliares como `contas_diarias`
- Visualizações com `countplot`, `boxplot`, `histplot` e `heatmap`

---

## ✅ Conclusões e Recomendações

- Contratos mensais possuem maior risco de churn
- Pagamentos automáticos reduzem evasão
- Serviços adicionais como segurança e suporte técnico melhoram retenção
- Recomendação de programas de fidelidade e incentivos para contratos mais longos

---

## 📎 Arquivos no Repositório

- `TELECOM_X_FINAL.ipynb`: Notebook completo com tratamento, análise e relatório
- `README.md`: Este arquivo
---

## 🤝 Contribuições

Este projeto foi desenvolvido como parte de um desafio educacional de Data Science. Sugestões, melhorias e forks são bem-vindos!



