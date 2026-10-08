# Ayokunmi Lawal

Data Science student at York University, Toronto. I build the whole path from raw data to decision: ingestion, a tested warehouse, a model, and a dashboard someone actually uses.

Long term, I want to work inside a football club in analytics and recruitment. Most of my sports work points there, and the same skills carry over to finance, retail, and tech.

**Currently:** Sports Analyst Intern, York University Athletics. Varsity football game databases in Python, SQL, and R, plus player performance dashboards in Power BI for coaching staff. Also Finance Executive for the York University Data Science Club.

**Previously:** Financial Data Analyst Intern, Lekki Cooperative Multipurpose Society (remote, 2024). Tracked cryptocurrency rate movement and automated recurring investor reports with SQL and Power BI.

**Open to:** Winter 2027 (Jan to Apr) or 8 month (Jan to Aug 2027) co-op in data, analytics, or actuarial roles.

---

## Featured work

### [Player Undervaluation Model](https://github.com/ayokumo/player_undervaluation_model) *(in progress)*
**Question:** Do players moving from outside the top five leagues succeed after transfer, and were they undervalued at the time? **Building:** A 12 phase project that uses only pre transfer data, with player stats stored in PostgreSQL and a LangChain RAG scouting assistant feeding the model. Currently in phase 1.
`Python` `SQL` `PostgreSQL` `LangChain`

### [Toronto Housing Analytics Platform](https://github.com/ayokumo/toronto-housing-project)
**Question:** Do Bank of Canada rate changes show up in Toronto shelter demand, and can it be forecast? **Built:** ELT over five public sources into DuckDB, dbt star schema on a 433,362 row fact table, 26 automated tests. **Found:** Occupancy rose about 0.64pp per 1% rate increase at a 6 month lag. SARIMA and Prophet both lost to a naive baseline over 37 fold rolling origin CV, so the forecast layer was cut rather than shipped.
`Python` `SQL` `dbt` `DuckDB` `statsmodels`

### [Toronto Shelter Overdose Spatial Analysis](https://github.com/ayokumo/toronto-overdose-spatial)
**Question:** What actually predicts overdose incidence across Toronto's 158 neighbourhoods? **Built:** Geocoded 2018 to 2025 incidents, spatial diagnostics, spatial lag and error models, then Poisson, Random Forest, and Gradient Boosting under repeated k fold CV. **Found:** Low income prevalence drives most of the clustering. Model error fell from 52 to 33 incidents, and the remainder traces to individual addresses below neighbourhood scale.
`Python` `geopandas` `PySAL` `scikit-learn`

### [Premier League Match Predictor](https://github.com/ayokumo/pl-predictor)
**Question:** Can a transparent model produce daily predictions at zero cost? **Built:** Scheduled GitHub Actions pipeline (daily, hourly on match weekends, 15 minute checks near kickoff) feeding a weighted factor model and a live dashboard on GitHub Pages. Ingestion fails safe by keeping prior data.
`Python` `GitHub Actions` `REST APIs`

**Up next:** a Player Transfer Predictor and a Recruitment Similarity Model.

---

## Stack

**Analysis:** Python (pandas, NumPy, scikit-learn, statsmodels, geopandas), SQL, R, SAS
**Modelling:** OLS and Poisson regression, Random Forest, Gradient Boosting, SARIMA, Prophet, spatial regression, cross validation, LangChain RAG
**Data:** dbt Core, DuckDB, PostgreSQL, SQLite, AWS, ETL and ELT design, automated data quality tests
**Football data:** FBref, Understat, StatsBomb open data, soccerdata, mplsoccer
**Reporting:** Power BI (DAX, Power Query, row level security), Excel, Tableau, Streamlit
**Tooling:** Git, GitHub Actions, Docker, pytest

---

## Contact

[LinkedIn](https://www.linkedin.com/in/ayokunmilawal) · [Portfolio](https://ayokunmilawal.netlify.app) · [X](https://x.com/ayokunm1) · lawalayokunmi25@gmail.com
