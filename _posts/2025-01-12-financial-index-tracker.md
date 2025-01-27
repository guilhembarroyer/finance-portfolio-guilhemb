---
layout: post
title: Financial Index Tracker
subtitle: Interactive financial indices creation and analysis tool with Streamlit
gh-repo: guilhembarroyer/financial-index-tracker
gh-badge: [star, fork, follow]
#cover-img: /assets/img/resultats_graphiques3.png
thumbnail-img: /assets/img/resultats_graphiques3.png
#tags: [finance, Streamlit, data-analysis, python]
comments: true
mathjax: false
author: Guilhem Barroyer
---

{: .box-success}
**Financial Index Tracker** is an interactive application built with Streamlit, allowing users to configure, create, and analyze financial indices tailored to their specific criteria. Designed for flexibility, the app supports customization of country, sector, investment style, and other key financial parameters.

---

## **Repository**

Explore the full source code on GitHub:

[![GitHub Repository](https://img.shields.io/badge/GitHub-Financial_Index_Tracker-blue?style=flat-square&logo=github)](https://github.com/guilhembarroyer/financial-index-tracker)

---

## **Key Features**

### 1. **Index Configuration**
{: .box-note}
- Define the stock universe based on countries, sectors (BICS1-4), or existing indices.
- Customize index size (e.g., less than 15 stocks to optimize loading times).
- Set specific constraints like dividend yields or qualitative characteristics.
- Choose the type of index:
  - Market Cap Index
  - Growth Index (PB/PE)
  - Value Index (PB/PE)
  - Dividend Yield Index
- Enable or disable annual rebalancing.
- Define the currency and weighting type (equal-weighted or market-cap-weighted).

### 2. **Dynamic Index Creation**
{: .box-note}
- Validate configurations to ensure data consistency.
- Generate indices dynamically using historical prices and qualitative data.

### 3. **Interactive Visualization**
{: .box-note}
- Explore sector, country, and investment style allocations through interactive charts.
- Compare the custom index against benchmarks.
- Track index evolution over time.
- Analyze stock inflows and outflows during rebalancing.
- Export results easily for further analysis or reporting.

---

## **Project Structure**

![Structure du dossier](assets/img/structure_index.png)

