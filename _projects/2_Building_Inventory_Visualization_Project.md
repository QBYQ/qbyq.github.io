---
name: Building Inventory Visualization Project
tools: [Python, HTML, vega-lite, Altair]
image: assets/pngs/building_inventory.png
description: This is a project showcasing visualizations created using Altair and vega-lite for interactive analysis of building inventory data!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

# Building Inventory Data Visualization

This project explores the building inventory dataset through two interactive visualizations created using Python, Altair, and Vega-Lite. These visualizations provide insights into temporal trends of acquisitions and constructions, as well as building usage patterns categorized by square footage. The interactive features, such as tooltips and filtering options, enhance data exploration and understanding.
<vegachart schema-url="/assets/json/chart.json" style="width: 100%"></vegachart>

---

## Data & Methods

Below are links to both the data and the analysis code, provided as buttons for easier access:

<div class="left">
{% include elements/button.html link="https://github.com/QBYQ/qbyq.github.io/blob/56a13abe3a3f1cfe33bcaa79e11c7b511337548c/assets/json/chart.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/QBYQ/qbyq.github.io/blob/56a13abe3a3f1cfe33bcaa79e11c7b511337548c/python_notebooks/Workbook.ipynb" text="The Analysis" %}
</div>

---

## About the Project

The temporal analysis chart examines trends in building acquisitions and constructions, while the usage categorization chart explores building size variability across usage types. Both visualizations leverage Altair's interactivity and Vega-Lite's declarative grammar for creating clean and insightful visualizations.

For more information, check out the analysis notebook linked above!
