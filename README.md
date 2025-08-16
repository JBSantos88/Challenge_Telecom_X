# Análise de Evasão de Clientes (Churn) - Projeto Telecom

## Descrição do Projeto
Este projeto tem como objetivo analisar o **problema de evasão de clientes (Churn)** de uma empresa de telecomunicações.  
A análise utiliza dados de clientes para identificar padrões, fatores associados à evasão e gerar insights para auxiliar a **redução da perda de clientes**.

O projeto inclui:
- Limpeza e tratamento de dados
- Análise exploratória
- Visualizações gráficas
- Matrizes de correlação
- Distribuição de evasão por categorias demográficas e serviços
- Recomendações estratégicas para fidelização de clientes

---

## Tecnologias e Bibliotecas Utilizadas
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Estrutura dos Dados
O dataset contém informações sobre clientes, incluindo:

| Coluna | Descrição |
|--------|-----------|
| customerID | Identificação única do cliente |
| Churn | Indica se o cliente evadiu (1) ou não (0) |
| customer.gender | Gênero do cliente |
| customer.SeniorCitizen | Idoso (1) ou não (0) |
| customer.Partner | Possui parceiro (1) ou não (0) |
| customer.Dependents | Possui dependentes (1) ou não (0) |
| customer.tenure | Meses de contrato |
| phone.PhoneService | Assinatura de serviço telefônico |
| internet.* | Serviços de internet adicionais |
| account.* | Tipo de contrato, faturamento e forma de pagamento |

---

## Passos Realizados

1. **Importação e Limpeza de Dados**
   - Conversão de valores binários (`Yes/No`) em 1 e 0.
   - Tratamento de valores ausentes.
   - Conversão de colunas numéricas.

2. **Análise Exploratória de Dados**
   - Distribuição de evasão por categoria: gênero, dependentes, parceiro, idade.
   - Distribuição de evasão por tipo de contrato e serviços contratados.
   - Matrizes de correlação entre serviços, faturamento e evasão.
   - Distribuição do faturamento mensal por evasão.

3. **Visualizações**
   - Gráficos de barra e pizza para evasão por categoria.
   - Heatmaps para análise de correlação.
   - Histogramas e KDE para distribuição de faturamento.

4. **Insights**
   - Maior evasão nos primeiros 12 meses de contrato.
   - Suporte técnico reduz levemente a evasão.
   - Clientes sem parceiro ou dependentes têm maior tendência a evadir.
   - Gasto mensal não é um fator determinante isoladamente.



## Como Executar o Projeto

1. Clone o repositório:

git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git

2. Instale as dependências:
pip install pandas numpy matplotlib seaborn

# Resultados e Visualizações

    Matrizes de correlação entre serviços, faturamento e evasão

    Distribuição de evasão por gênero, parceiro, dependentes e idade

    Distribuição de faturamento mensal por clientes evadidos e ativos

    Insights estratégicos para reduzir evasão

## Conclusão

Este projeto fornece uma visão da evasão de clientes da empresa fictícia "TelecomX", ajudando a direcionar esforços de fidelização e retenção de forma mais eficiente.

## Autor:

### Belarmino Santos. 

---
