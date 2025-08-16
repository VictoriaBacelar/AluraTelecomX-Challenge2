# Análise de Evasão de Clientes – Telecom X

## Descrição
Este projeto realiza uma análise exploratória dos dados de clientes da Telecom X, com foco no problema de **evasão de clientes (Churn)**. O objetivo é entender o comportamento dos clientes, identificar padrões que indiquem risco de cancelamento e gerar insights para estratégias de retenção.

---

## Limpeza e Tratamento de Dados
- Importação a partir de **API** no formato JSON.  
- Conversão desses dados em **DataFrame Pandas**.  
- Verificação e tratamento de valores nulos, duplicados e padronização de formatação.  
- Expansão das colunas que eram dicionários para colunas separadas.  
- Conversão de colunas numéricas para **float**.  
- Padronização da coluna `Churn` para conter apenas `yes` e `no`.  

---

## Análise Exploratória de Dados
- Distribuição da variável `Churn` entre os clientes.  
- Relação de `Churn` com variáveis categóricas, como tipo de contrato, serviços adicionais, gênero e método de pagamento.  
- Distribuição de variáveis numéricas (`tenure`, `Contas_Diarias`) entre clientes que cancelaram e que permaneceram.  
- Visualização com **boxplots** e gráficos de contagem para identificar padrões e possíveis fatores de risco.  

---

## Conclusões
- Clientes **month-to-month** têm maior taxa de evasão.  
- Clientes com menor tempo de contrato e menor gasto diário têm maior tendência a cancelar.  
- Serviços adicionais podem influenciar na retenção dos clientes.  

---

## Recomendações de Negócio
- Incentivar descontos ou serviços para contratos mais longos.  
- Criar campanhas de marketing para reter clientes recentes e/ou c
---

## Tecnologias Utilizadas
- Python 3.x  
- Pandas  
- Numpy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook / Google Colab  

---

## Como Executar
1. Clone este repositório
2. Use algum notebook online
3. instale as dependências
```bash
git clone https://github.com/seu-usuario/telecom-churn-analysis.git
pip install pandas numpy matplotlib seaborn
