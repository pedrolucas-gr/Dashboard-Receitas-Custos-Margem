# 📊 Dashboard de Receita, Custos e Margem

# 📖 Sobre o Projeto

O **Dashboard de Receita, Custos e Margem** foi desenvolvido em **Power BI** com o objetivo de fornecer uma visão estratégica do desempenho comercial da empresa, permitindo acompanhar indicadores financeiros relacionados às vendas, custos e margem de contribuição.

O projeto consolida informações de vendas e produtos para analisar o faturamento, custos, rentabilidade por categoria de produto e desempenho da equipe comercial, auxiliando gestores na identificação de oportunidades para maximizar resultados e otimizar a tomada de decisão.

---

# 🎯 Objetivos

- Monitorar os principais indicadores financeiros das vendas.
- Comparar receitas, custos e margem obtida.
- Avaliar a rentabilidade por linha e grupo de produtos.
- Identificar os vendedores com maior contribuição para o faturamento.
- Acompanhar o desempenho dos supervisores comerciais.
- Analisar a evolução da receita ao longo do tempo.
- Apoiar decisões estratégicas através de dashboards interativos.

---

# 📊 Dashboard

<p align="center">
<img src="https://github.com/pedrolucas-gr/Dashboard-Receitas-Custo-Margem/blob/main/Images/Dashboard.png" width="100%">
</p>

O dashboard apresenta uma visão executiva dos resultados comerciais, permitindo analisar o comportamento das vendas, custos e margem de lucro por diferentes perspectivas, como período, categoria de produto, vendedores e supervisores.

### KPIs Monitorados

- 💰 Receita Total
- 💵 Margem
- 💳 Custo Total

### Análises Disponíveis

- Receita por Ano, Trimestre e Mês
- Receita por Grupo de Produto
- Margem por Linha de Produto
- Margem por Grupo de Produto
- Ranking de Vendedores
- Desempenho por Supervisor
- Comparativo entre Receita e Margem por vendedor

---

# 🛠 Tecnologias Utilizadas

| Tecnologia | Aplicação |
|------------|-----------|
| Power BI | Desenvolvimento do Dashboard |
| Power Query | ETL e transformação dos dados |
| DAX | Construção das medidas |
| Microsoft Excel | Base de dados |
| Modelagem de Dados | Relacionamento entre tabelas |

---

# 🗂 Modelagem de Dados

<p align="center">
<img src="https://github.com/pedrolucas-gr/Dashboard-Receitas-Custo-Margem/blob/main/Images/Modelagem.png" width="80%">
</p>

O modelo foi desenvolvido utilizando uma estrutura simples e eficiente composta por uma **Tabela Fato** e uma **Tabela Dimensão**, proporcionando melhor desempenho nas consultas e facilidade na criação das medidas em DAX.

## 📄 Vendas

Tabela fato responsável pelos registros das vendas realizadas.

Principais informações:

- Data da Venda
- Nota Fiscal
- Produto
- Vendedor
- Supervisor
- Quantidade
- Receita
- Valor Unitário

---

## 📦 Produto

Tabela dimensão responsável pelas características dos produtos comercializados.

Principais informações:

- Código do Produto
- Fornecedor
- Grupo de Produto
- Linha de Produto
- Custo Unitário

---

## 🔗 Relacionamento

As tabelas são relacionadas através do **Código do Produto**, permitindo enriquecer os registros de vendas com informações sobre grupos, linhas e custos dos produtos, possibilitando análises detalhadas de rentabilidade.

---

# 📈 Principais Indicadores

| Indicador | Descrição |
|------------|-----------|
| Receita | Valor total das vendas realizadas |
| Custo | Soma dos custos dos produtos vendidos |
| Margem | Diferença entre a receita e os custos |
| Margem por Produto | Rentabilidade obtida por linha e grupo de produtos |
| Receita por Vendedor | Faturamento individual da equipe comercial |

---

# 💡 Insights Gerados

Com o dashboard é possível identificar:

- Evolução da receita ao longo dos períodos.
- Produtos com maior participação no faturamento.
- Linhas de produtos mais rentáveis.
- Grupos de produtos com maior margem de contribuição.
- Vendedores com melhor desempenho comercial.
- Supervisores responsáveis pelos melhores resultados.
- Produtos com maior impacto sobre os custos.
- Oportunidades para aumento da rentabilidade das vendas.

---

# 📂 Estrutura do Projeto

```text
📦 Dashboard-Receita-Custos-Margem
│
├── 📁 BaseDados
│   ├── BaseVendas.xlsx
│
├── 📁 Images
│   ├── Dashboard.png
│   └── Modelagem.png
│
├── Dashboard.pbix
└── README.md
```

---

# 🚀 Como Executar

1. Clone o repositório.

```bash
git clone https://github.com/pedrolucas-gr/Dashboard-Receitas-Custo-Margem.git
```

2. Abra o arquivo **Dashboard.pbix** utilizando o **Power BI Desktop**.

3. Caso necessário, atualize o caminho da base de dados.

4. Atualize o modelo para visualizar todas as informações.

---

# 📚 Aprendizados

Durante o desenvolvimento deste projeto foram aplicados conhecimentos em:

- Modelagem de Dados
- ETL com Power Query
- Construção de Medidas em DAX
- Desenvolvimento de KPIs Comerciais
- Análise de Margem de Contribuição
- Storytelling com Dados
- Visualização de Dados
- Dashboards Executivos
- Business Intelligence (BI)

---

# 👨‍💻 Autor

Desenvolvido por **Pedro Lucas**

- 💼 LinkedIn: https://www.linkedin.com/in/pedrolucasrodriguesdata/
- 📧 E-mail: pedrolucaspbi@gmail.com

---
