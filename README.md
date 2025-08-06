# Box Office Mojo Scraper & Analysis

This project scrapes worldwide box office data for the years **2019–2023** from **[Box Office Mojo](https://www.boxofficemojo.com/)**. The goal is to build a consolidated dataset containing rankings, worldwide, domestic and foreign grosses, and percentage shares for films in each year, then analyze trends across the five‑year period.

## Repository Contents

- **`analysis.ipynb`** – A Jupyter notebook that performs the following:
  - Scrapes box office tables from five annual pages using `pandas.read_html`.
  - Cleans and combines the data into a single DataFrame.
  - Explores the dataset and answers four analytical questions using descriptive statistics and plots (created with Seaborn).
  - Provides narrative markdown explanations and conclusions.
- **`README.md`** – This file, describing the purpose of the project, contents of the repository, and the data source.

## Data Source

Data were scraped from the worldwide box office tables on Box Office Mojo, specifically the following pages:

- https://www.boxofficemojo.com/year/world/2019/
- https://www.boxofficemojo.com/year/world/2020/
- https://www.boxofficemojo.com/year/world/2021/
- https://www.boxofficemojo.com/year/world/2022/
- https://www.boxofficemojo.com/year/world/2023/

Each page lists films ranked by worldwide gross and includes domestic and foreign grosses and percentage shares.

## Findings Overview

The analysis shows that average revenue for the top 10 films dropped significantly in 2020 due to the COVID‑19 pandemic but recovered in later years. Domestic revenue shares remained fairly stable across the five‑year span, and films with strong domestic grosses typically also performed well internationally. A few films stood out by earning the vast majority of their box office revenue in the domestic market.
