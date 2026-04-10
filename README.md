# Supply Chain Analytics — DataCo

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![Python](https://img.shields.io/badge/Python-3.12+-blue?logo=python)
![Plotly](https://img.shields.io/badge/Plotly-interativo-blueviolet?logo=plotly)

Análise de dados logísticos com o dataset **DataCo Smart Supply Chain**, cobrindo mais de 180 mil pedidos de e-commerce global entre 2015 e 2018.

## Objetivos

- Calcular KPIs essenciais de supply chain: **OTIF**, **lead time** e **taxa de atraso**
- Identificar gargalos por região, categoria de produto e modal de envio
- Construir um dashboard interativo para visualização da performance logística

## Notebooks

| Notebook | Descrição |
|---|---|
| `01_eda.ipynb` | Análise exploratória — shape, distribuições, missing values, perfil dos dados |
| `02_kpis.ipynb` | KPIs de logística: OTIF, lead time médio, taxa de atraso por corte |
| `03_dashboard.ipynb` | Dashboard interativo com Plotly: mapa global, rankings e sunburst |
| `04_causas_atraso.ipynb` | Análise de causa raiz: prazo prometido, sazonalidade, heatmap modal × região, Random Forest |

## Stack

- **Python 3.12** · Pandas · NumPy · Scikit-learn
- **Plotly** — visualizações interativas
- **Jupyter Notebook**

## Dataset

[DataCo Smart Supply Chain — Kaggle](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)

> ~180 mil pedidos · 53 variáveis · Período: 2015–2018

## Autor

**Rodrigo Cruz dos Santos**
[LinkedIn](https://www.linkedin.com/in/rodrigopresidati) · [GitHub](https://github.com/RodrigoPresida)
