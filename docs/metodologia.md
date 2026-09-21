# Metodologia do Projeto

## 1. Objetivo

O projeto foi desenvolvido para transformar dados operacionais de vendas e compras em informações capazes de apoiar decisões relacionadas a:

- mix de produtos;
- compras;
- fornecedores;
- vendas;
- estoque;
- redução de custos;
- eficiência operacional.

---

## 2. Modelo analítico

A solução utiliza um modelo de dados estruturado para relacionar informações de vendas, compras, produtos, clientes, fornecedores e calendário.

A modelagem permite analisar os indicadores sob diferentes perspectivas de tempo e dimensão.

---

## 3. Principais análises

### Vendas

A análise de vendas permite acompanhar:

- faturamento;
- quantidade vendida;
- ticket médio;
- evolução temporal;
- desempenho por produto;
- desempenho por categoria;
- comportamento por dia da semana.

### Compras

A análise de compras permite avaliar:

- valor comprado;
- volume de compras;
- fornecedores;
- produtos adquiridos;
- categorias;
- evolução temporal.

---

## 4. Curva ABC

A classificação ABC é utilizada para segmentar os produtos de acordo com sua participação no faturamento.

A análise permite identificar:

- produtos de alta relevância;
- produtos de relevância intermediária;
- produtos de baixa participação.

Os produtos classificados na Curva C podem ser avaliados individualmente para determinar se existe oportunidade de:

- reduzir estoque;
- reduzir variedade;
- revisar o mix;
- alterar frequência de compra;
- retirar produtos de baixa relevância.

A classificação não representa automaticamente uma decisão de retirada do produto. Ela funciona como uma ferramenta para direcionar a análise.

---

## 5. Análise de compras

Uma das aplicações do BI é comparar o comportamento das compras com o comportamento das vendas.

Essa análise pode ajudar a identificar situações como:

**Compra elevada + baixa saída**

Possível oportunidade de investigação de excesso de estoque ou capital imobilizado.

**Compra elevada + alta saída**

Pode indicar necessidade de planejamento de abastecimento e negociação com fornecedores.

**Baixa compra + alta demanda**

Pode indicar oportunidade de revisão do processo de abastecimento.

---

## 6. Análise temporal

O dashboard permite analisar o comportamento das vendas ao longo do tempo.

Entre as perspectivas analisadas estão:

- mês;
- dia;
- dia da semana;
- evolução do faturamento;
- comportamento da demanda.

Essa análise pode apoiar decisões relacionadas a:

- planejamento de compras;
- abastecimento;
- estoque;
- negociação com fornecedores;
- planejamento comercial.

---

## 7. Business Intelligence aplicado à decisão

O objetivo do projeto não é apenas apresentar indicadores.

A lógica é utilizar os indicadores para gerar perguntas de negócio.

### Exemplo

**Curva ABC**

↓

Identificação de produtos de baixa participação

↓

Análise de vendas e compras

↓

Avaliação do estoque e frequência de compra

↓

Possível redução de SKUs ou compras

↓

**Potencial redução de capital imobilizado**

---

## 8. Tecnologias

- Microsoft Power BI
- DAX
- Power Query
- Modelagem de dados
- Business Intelligence
- Data Analytics
- Data Visualization
