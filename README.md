# Formação em Dados - Escola DNC

Bem-vindo(a)! Este repositório reúne **trabalhos e desafios** realizados durante o curso de **Formação em Dados** da **Escola DNC**. Cada desafio foca em uma etapa ou técnica específica dentro do universo de Dados, desde visualizações em **Power BI**, análises com **SQL**, até modelos de regressão e classificação em **Python**.

---

## Sumário

1. [Desafio 1: Painel de E-commerce em Power BI](#desafio-1-painel-de-e-commerce-em-power-bi)  
2. [Desafio 2: Painel Gerencial Automatizado em Power BI](#desafio-2-painel-gerencial-automatizado-em-power-bi)  
3. [Desafio 3: Planos de Ação a partir de Análises com SQL](#desafio-3-planos-de-a%C3%A7%C3%A3o-a-partir-de-an%C3%A1lises-com-sql)  
4. [Desafio 4: Modelo de Regressão para Marketing](#desafio-4-modelo-de-regress%C3%A3o-para-marketing)  
5. [Desafio 5: Preparando Dataset para Modelagem de Dados (RFM)](#desafio-5-preparando-dataset-para-modelagem-de-dados-rfm)  
6. [Desafio 6: Previsão de Churn em Plataforma de Streaming](#desafio-6-previs%C3%A3o-de-churn-em-plataforma-de-streaming)  
7. [Desafio 7: Modelo de Análise das Métricas RFV (Clustering)](#desafio-7-modelo-de-an%C3%A1lise-das-m%C3%A9tricas-rfv-clustering)

---

## Desafio 1: Painel de E-commerce em Power BI

**Objetivo:**  
Criar um **painel gerencial** para um e-commerce que deseja **estudar as suas vendas** e, a partir disso, **traçar a melhor estratégia** para alavancar resultados.

**Tarefas:**
- Receber duas bases de dados (vendas e clientes);
- Criar **duas páginas** de relatório com as principais métricas;
- Elaborar **métricas** de:
  - Quantidade total de vendas
  - Valor total de vendas
  - Cotagem (ou contagem) e valor total de vendas por data
  - Quantidade e valor total por categoria
- Criar **filtros** para aprimorar a experiência do usuário;
- Aplicar **storytelling** e um bom **layout** para maior atratividade.

**Visão do Painel:**

![Captura de tela 2024-08-24 150126](https://github.com/user-attachments/assets/489eb13b-c11a-4e53-9aa9-a593507dcfd3)

---

## Desafio 2: Painel Gerencial Automatizado em Power BI

**Objetivo:**  
A empresa de Marketing Digital "X" quer **alcançar uma meta ambiciosa** neste trimestre e **identificar planos de ação** para atingi-la. Para isso, precisa de um dashboard que permita acompanhar **indicadores de desempenho** de cada campanha, facilitando a análise e a **tomada de decisões** estratégicas.

**Tarefas:**
- Criar um **dashboard** em Power BI que exiba os **KPIs** das campanhas;
- Avaliar e comparar o desempenho de cada campanha;
- Identificar **oportunidades de otimização** para alcançar a meta do quarter;
- Garantir **atualizações automatizadas** dos dados.

**Visão do Painel:**

![image](https://github.com/user-attachments/assets/fc4ed17e-7249-4173-a8ea-1375883f921a)

---

## Desafio 3: Planos de Ação a partir de Análises com SQL

**Cenário:**  
Você é um **analista de dados** em uma Edtech, focada em **crescimento do número de usuários cadastrados**. Foi solicitado que você analise diversos aspectos da **aquisição de clientes** para avaliar o status de crescimento da base de usuários.

**Tarefas:**
- Manipular bases de dados usando **SQL**;
- Criar **queries** que mostrem insights sobre o comportamento dos novos usuários;
- **Identificar oportunidades** de crescimento e gargalos no funil de aquisição;
- Propor **planos de ação** para acelerar o crescimento.

**Exemplo de Análise (Printscreen):**

![Captura de tela 2025-01-13 102644](https://github.com/user-attachments/assets/f6776f0f-8321-42ec-bf31-b1e055191680)

---

## Desafio 4: Modelo de Regressão para Marketing

**Cenário:**  
Uma empresa investe em diferentes plataformas de publicidade online (YouTube, Facebook, newspaper) para **gerar leads**. Eles registram **todos os gastos** em publicidade e **retornos de vendas** gerados.  

**Objetivos:**
1. **Entender a relação** entre as variáveis (investimentos e retornos).
2. **Identificar os fatores** que mais impactam a **geração de leads**.
3. **Criar um modelo** de predição para **estimar o retorno de vendas** a partir de um determinado investimento.

**Tarefas:**
- Explorar a base de dados para encontrar correlações;
- Construir um **modelo de regressão** (por exemplo, Regressão Linear);
- Avaliar a performance do modelo (Métricas como MSE, RMSE, R², etc.);
- Gerar insights para **otimizar gastos em publicidade**.

**Exemplo de Visualização:**

![image](https://github.com/user-attachments/assets/249de4bc-70d7-49dc-83bf-50f002a90f34)
![image](https://github.com/user-attachments/assets/58db978d-1c99-42f4-86b3-59731b8a362a)

---

## Desafio 5: Preparando Dataset para Modelagem de Dados (RFM)

**Cenário:**  
Uma empresa de e-commerce deseja levantar indicadores de **Recência (R)**, **Frequência (F)** e **Ticket Médio (M)** de seus clientes (RFM). Você recebe uma base de dados e deve gerar como saída um novo CSV contendo **apenas** a identificação do cliente e as métricas RFM.

- **Recency (R)**: Tempo em dias desde a última compra do cliente.
- **Frequency (F)**: Quantidade de compras realizadas pelo cliente.
- **Monetary (M)**: Ticket médio gasto pelo cliente (valor total gasto dividido pelo número de pedidos).

**Tarefas:**
- Ler a base de dados original em Python;
- Calcular as métricas RFM para cada cliente;
- Salvar em um **novo CSV** com colunas: ID do cliente, R, F, M.

**Imagens Ilustrativas:**

![image](https://github.com/user-attachments/assets/e7f0c03f-d36b-4451-ac9a-28e289b322a8)
![image](https://github.com/user-attachments/assets/b3681f37-5dcf-4f83-82a7-d351906aebd2)

---

## Desafio 6: Previsão de Churn em Plataforma de Streaming

**Cenário:**  
Você atua em uma **plataforma de streaming** com alto índice de **churn** (cancelamento). A diretoria acredita ser possível **prever** se um usuário tem **maiores chances de cancelar** a assinatura antes que isso aconteça, para **agir preventivamente**.

**Objetivo:**  
Criar um **modelo de classificação** (ex.: Regressão Logística, Árvore de Decisão, Random Forest etc.) que **preveja** se um usuário pode cancelar ou não sua assinatura.

**Tarefas:**
- Receber uma base de dados em CSV com características dos clientes;
- Explorar os dados para entender potenciais variáveis preditivas;
- Treinar e **avaliar** modelos de classificação;
- Fazer **propostas** de ação para reduzir o churn.

**Exemplo de Visualização:**

![image](https://github.com/user-attachments/assets/49b3a4b2-003a-4f8a-bf4d-c9ea01f3e7c2)

---

## Desafio 7: Modelo de Análise das Métricas RFV (Clustering)

**Cenário:**  
Uma empresa de e-commerce quer entender melhor o comportamento de seus clientes para **personalizar campanhas de marketing**. Você recebe um CSV com dados sobre clientes, produtos e transações realizadas entre 2010 e 2011.

**Objetivo:**  
Agrupar (clusterizar) clientes com base em **RFV** (Recência, Frequência e Valor Monetário), a fim de **identificar padrões** e **segmentar** clientes que:
- Compram os mesmos produtos;
- Têm a mesma frequência de compras;
- Gastam mais (ou menos) dinheiro nas compras.

**Tarefas:**
- Calcular métricas RFV (ou **RF** e **Valor total** para o clustering);
- Aplicar técnicas de **clusterização** (K-means, por exemplo);
- Gerar **insights** para segmentar e direcionar campanhas de marketing.

**Exemplo de Visualização:**

![image](https://github.com/user-attachments/assets/5f6af493-1020-42ed-8baa-df05b3dec6da)

---

<p align="center">
  Desenvolvido com 💛 por <strong>@mayasrl</strong>.
</p>
