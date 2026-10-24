---
# An instance of the Markdown widget.
widget: markdown

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Projects
subtitle: 'See also my [GitHub](https://github.com/felipeVsc) profile'
---

### [Smart Cities Data Lakehouse](https://github.com/felipeVsc/lakehouses)

An end-to-end Data Lakehouse for public transport data, built to test whether a single lakehouse can serve both data lake and data warehouse workloads for smart-city analytics. It ingests real-time bus positioning data from the public APIs of Rio de Janeiro, Curitiba, Brasília and São Paulo, refines it through a Medallion architecture (Bronze, Silver, Gold) and models the Gold layer as a star schema. Analyses include bus speed comparisons across cities and a coverage heatmap for São Paulo.

*Technologies:* Delta Lake, Apache Spark, Apache Airflow, Apache Kafka, Pandas, Python, Medallion architecture, dimensional modeling (star schema).

### [Storm Events Data Warehouse](https://github.com/felipeVsc/stormevents)

A Kimball star schema built from the NOAA Storm Events Database, integrating previously disconnected event, location and fatality files to enable economic and human impact analysis. It is the data foundation for a SQL-inspired declarative query system for event data, with operators for classification (kNN, Decision Tree), clustering (DBSCAN, k-Means) and similarity search over text (NLP embeddings) and space (Haversine distance). A case study predicts tornado Enhanced Fujita ratings and finds flood-related events near Oklahoma City.

*Technologies:* Python, SQL, scikit-learn, Matplotlib, Jupyter, dimensional modeling (Kimball), ETL.

### [Textual Mining on News](https://github.com/felipeVsc/textual_mining)

A text mining project that simulates an assistant for journalists: given a news article, it classifies its category and aims to generate a headline, summary and keywords. It uses the HuffPost News Category Dataset (~210k articles), with preprocessing (deduplication, category merging), sentence embeddings, and classifiers tuned with grid search and feature selection against a DummyClassifier baseline.

*Technologies:* Python, Pandas, Sentence Transformers, scikit-learn (kNN, GridSearchCV), XGBoost, OpenAI API, Jupyter.
