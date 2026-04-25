# 📊 Power BI Analyst — Desafio de Projeto DIO

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DIO-Forma%C3%A7%C3%A3o%20Power%20BI%20Analyst-blue?style=for-the-badge" />
</p>

---

## 📌 Sobre o Projeto

Relatório interativo desenvolvido no **Power BI Desktop** como entrega do desafio de projeto da trilha **Formação Power BI Analyst**.

O relatório foi construído com base na amostra **Sample Financials** do Power BI e conta com duas páginas analíticas completas, navegação por botões, segmentadores de dados, indicadores (bookmarks) e alternância entre visuais.

---

## 🖥️ Páginas do Relatório

### Página 1 — Sales Report (Visão Geral de Vendas)

> Visão consolidada das métricas de vendas com filtro por período, produtos, segmentos e países.

| Elemento | Descrição |
|---|---|
| 📅 Seletor de Data | Filtro de intervalo: 01/09/2013 a 01/12/2014 |
| 💳 KPIs (Cards) | Total de Vendas · Unidades Vendidas · Soma de Discounts · Soma de COGS |
| 📈 Gráfico de Área | Soma de Sales por Mês (tendência ao longo do ano) |
| 🔵 Gráfico de Rosca | Sales x Segmento — com alternância entre Pie Chart e Bar Chart via botões |
| 📊 Gráfico de Barras | Sales x Produto (Paseo, VTT, Velo, Amarilla, Montana, Carretera) |
| 🗺️ Sales x Country | Alternância entre Treemap e Mapa interativo (Map Chart) via botões |
| ➡️ Botão de Navegação | Navega para a Página 2 (Report de Lucro Detalhado) |

---

### Página 2 — Report de Lucro Detalhado

> Análise aprofundada de lucratividade por ano, país, trimestre e segmento.

| Elemento | Descrição |
|---|---|
| 💰 Card Total | Soma de Profit: **16.893.702,26** |
| 🌳 Decomposition Tree | Profit decomposto por Ano → Country (hierarquia interativa) |
| 📊 Gráfico Cascata | Soma de Profit por Trimestre (Aumentar / Diminuir / Total) |
| 🟦 Treemap | Soma de Profit por Segment (Government, Small Business, Channel Partners…) |
| 🔷 Radar Chart | Visual personalizado: RadarChart — distribuição por dimensões |
| 🔘 Chiclet Slicer | Segmentador customizado: filtro por Ano e Country |
| ⬅️ Botão de Navegação | Retorna para a Página 1 (Sales Report) |

---

## ✨ Recursos Utilizados

### 🧭 Navegação
- Botões com ação **Navegação de Páginas** configurados em ambas as páginas
- Ícones associados aos botões para identificação visual intuitiva

### 🔖 Indicadores (Bookmarks)
- **Sales x Segmento:** alternância entre `Bar Chart` e `Pie Chart`
- **Sales x Country:** alternância entre `Treemap` e `Map Chart`
- Cada par de visuais sobreposto com botões de seleção dedicados

### 🎛️ Segmentadores
- Seletor de intervalo de datas (Date Range Slicer)
- **Chiclet Slicer** personalizado para filtro de Ano e Country (Página 2)

### 📐 Layout
- Barra lateral com logo e identidade visual da DIO
- Cabeçalho com título e subtítulo por página
- Área de KPIs no topo da Página 1
- Rodapé com botões de navegação

### 🔌 Visuais Personalizados (AppSource)
| Visual | ID |
|---|---|
| Chiclet Slicer | `ChicletSlicer1448559807354` |
| Radar Chart | `RadarChart1446119667547` |

---

## 📊 Dados Utilizados

**Fonte:** Sample Financials — dataset de exemplo nativo do Power BI

| Campo | Tipo | Uso |
|---|---|---|
| `Sales` | Numérico | KPI principal, gráficos de vendas |
| `Profit` | Numérico | Análise de lucratividade |
| `Units Sold` | Numérico | KPI de volume |
| `Discounts` | Numérico | KPI de desconto |
| `COGS` | Numérico | Custo dos produtos vendidos |
| `Month Name` | Texto | Eixo temporal dos gráficos |
| `Product` | Texto | Segmentação por produto |
| `Segment` | Texto | Segmentação por tipo de cliente |
| `Country` | Texto | Segmentação geográfica |
| `Date` | Data | Filtro por período e trimestre |

---

## 🚀 Como Abrir o Relatório

### Localmente (Power BI Desktop)

1. Instale o [Power BI Desktop](https://powerbi.microsoft.com/pt-br/desktop/) gratuitamente
2. Clone ou baixe este repositório
3. Abra o arquivo `desafio2.pbix` no Power BI Desktop
4. Para os visuais personalizados (Chiclet Slicer e Radar Chart), instale-os via **Inserir → Mais Visuais → AppSource**


---

## 🛠️ Tecnologias

<p>
  <img src="https://img.shields.io/badge/Power%20BI%20Desktop-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Power%20BI%20Service-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/DAX-0078D4?style=flat-square&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Sample%20Financials-Dataset-lightgrey?style=flat-square" />
</p>

---


