# Hi, I'm Ayo 👋

I'm a Data Science student at York University in Toronto. I like taking messy, real world data and turning it into something people can actually use to make a decision, whether that's a coach planning for Saturday or a city trying to understand who needs help.

Right now I'm a **Sports Analyst Intern at York University**, querying varsity football databases with SQL and Python and writing R code for two weekly coaching reports used in game preparation. I'm also Finance Executive for the York University Data Science Club, and before all this I worked as a Financial Data Analyst Intern, automating recurring Power BI reports on cryptocurrency rate movement for investors and senior leadership.

### What I care about

Beyond the technical side, I think a lot about what data does to people. A few things I keep coming back to:

- **AI ethics.** Who gets to decide what a model optimizes for, and who pays when it gets it wrong.
- **Data safety and privacy.** Most people have no idea how much of their life is sitting in someone's database. I'd like to be one of the people handling it responsibly.
- **Data, social media, and everyday life.** How the numbers behind feeds and recommendations shape what we see, buy, and believe.

It's a big part of why some of my projects use public data to look at real social issues, not just clean benchmark datasets.

---

## Projects

### [Football Player Undervaluation Model with RAG Scouting Assistant](https://github.com/ayokumo/player_undervaluation_model)
**Status: in progress.** Are players who move from nine leagues outside Europe's top five into top five clubs undervalued by the market? I'm testing that using only data from before each transfer. The data scope and the scouting assistant scaffold are in the repo. No model results or benchmark scores are published yet. Planned stack: PostgreSQL with pgvector, scikit-learn, PyTorch, LangChain and LangGraph.
`Python` `SQL`

### [Premier League Match Prediction Pipeline](https://github.com/ayokumo/pl-predictor) · [Live dashboard](https://ayokumo.github.io/pl-predictor/)
**Status: running, trained model in progress.** An automated pipeline on GitHub Actions that refreshes fixtures, form and standings, scores upcoming matches with a transparent weighted factor model, and updates a live dashboard. A trained model validated across past seasons is the next piece. No accuracy figures are published yet.
`Python` `GitHub Actions` `REST APIs`

### [Toronto Housing and Shelter Forecasting Pipeline](https://github.com/ayokumo/toronto-housing-project)
**Status: analysis complete, rate based forecast in progress.** I wanted to know if Bank of Canada rate changes actually show up in Toronto shelter demand. I pulled five public sources into a tested dbt and DuckDB warehouse (433K row fact table, 26 automated tests) and found occupancy rose about 0.64pp for every 1% rate increase, roughly six months later. Univariate SARIMA and Prophet forecasts did not beat a naive baseline.
`Python` `SQL` `dbt` `DuckDB` `statsmodels`

### [Toronto Shelter Overdose Spatial Analysis](https://github.com/ayokumo/toronto-overdose-spatial) · [Interactive map](https://ayokumo.github.io/toronto-overdose-spatial/overdose_map.html)
**Status: analysis complete, cluster analysis in progress.** What actually predicts where overdoses happen across Toronto's 158 neighbourhoods? Using spatial models and machine learning on 2018 to 2025 data, low income prevalence turned out to explain most of the clustering, and I cut model error from 52 incidents down to 33.
`Python` `geopandas` `PySAL` `scikit-learn`

---

## What I work with

**Languages:** Python, SQL, R, SAS
**Data:** dbt, DuckDB, PostgreSQL, SQLite, AWS, Docker
**Modelling:** regression, Random Forest, Gradient Boosting, time series, spatial models, LangChain
**Visualizing:** Power BI, Tableau, Streamlit, Excel
**Football data:** FBref, Understat, StatsBomb, mplsoccer

---

## Outside of code

You'll usually find me playing or watching football, coaching kids, or losing a chess game I thought I was winning.

## Let's talk

I'm available for a **4 month work term from January 2027** in data and analytics. If you're working on something interesting, especially where data meets people, I'd love to hear about it.

[LinkedIn](https://www.linkedin.com/in/ayokunmilawal) · [Portfolio](https://ayokunmilawal.netlify.app) · [X](https://x.com/ayokunm1) · lawalayokunmi25@gmail.com
