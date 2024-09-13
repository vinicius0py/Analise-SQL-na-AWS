# **Análise SQL na AWS**
Autor [Vinícius Oliveira](https://www.linkedin.com/in/vinicius-oliveira-p1/)

---

**1.Objetivo do Projeto**
O objetivo deste projeto é realizar uma análise exploratória de dados (EDA) na tabela "credito", hospedada no AWS utilizando SQL com o AWS Athena e S3. A análise busca responder a perguntas-chave relacionadas a cartões de crédito, padrões de gastos e distribuição de renda, com o intuito de identificar tendências, comportamentos e dados relevantes que possam ser utilizados para tomadas de decisões estratégicas.

**1.1. TLDR**
 - **Dados**:
  - Git Hub ([Link](https://github.com/andre-marcos-perez/ebac-course-utils)).
 - **Processamento**:
  - Kaggle Notebook [Link](https://www.kaggle.com/code/vinciusoliveirap1/analise-sql-na-aws).


1.2. DADOS

Os dados representam informações de clientes de um banco e contam com as seguintes colunas:
- **idade** = idade do cliente
- **sexo** = sexo do cliente (F ou M)
- **dependentes** = número de dependentes do cliente
- **escolaridade** = nível de escolaridade do clientes
- **salario_anual** = faixa salarial do cliente
- **tipo_cartao** = tipo de cartao do cliente
- **qtd_produtos** = quantidade de produtos comprados nos últimos 12 meses
- **iteracoes_12m** = quantidade de iterações/transacoes nos ultimos 12 meses
- **meses_inativo_12m** = quantidade de meses que o cliente ficou inativo
- **limite_credito** = limite de credito do cliente
- **valor_transacoes_12m** = valor das transações dos ultimos 12 meses
- **qtd_transacoes_12m** = quantidade de transacoes dos ultimos 12 meses

A tabela foi criada no AWS Athena junto com o S3 Bucket com uma versão dos dados disponibilizados em:  [Git Hub](https://github.com/andre-marcos-perez/ebac-course-utils).
