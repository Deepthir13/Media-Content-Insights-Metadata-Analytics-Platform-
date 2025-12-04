
# 🎬 Media Content Insights & Metadata Analytics Platform 

---

## 📝 Project Overview

This project showcases my **end-to-end BI and data engineering skills** by transforming the massive **IMDb open dataset (100M+ records)** into actionable business insights using **Azure Data Factory, Snowflake, and Tableau**.

---

### 👨‍💻 My Role

✅ Designed scalable ETL pipelines  
✅ Cleaned, normalized, and modeled nested TSV data  
✅ Built a dimensional data warehouse in Snowflake  
✅ Developed BI dashboards for deep movie and series insights

---

## 💡 Business Questions Answered

- 🎭 What are all professions (actors, directors, writers) linked to a person?  
- 🎞️ Which movies are top-rated by genre, region, and year?  
- 📊 How do movie lengths and ratings vary over time?  
- 🧑‍🤝‍🧑 How do cast, crew, and characters distribute across titles?  
- 🌍 What are the multi-language title variations per country?  
- 📈 What are the trends in series seasons, episodes, and ratings?

---

## 📂 Datasets Processed

| File                   | Description                     | Records   |
|------------------------|---------------------------------|-----------|
| name.basics.tsv        | People & professions info       | 14M+      |
| title.basics.tsv       | Movie/show metadata             | 11.4M     |
| title.akas.tsv         | Alternate titles & languages    | 51M+      |
| title.crew.tsv         | Directors & writers             | 11.4M     |
| title.episode.tsv      | TV episodes & series linkage    | 8.8M      |
| title.principals.tsv   | Cast & crew details             | 90M+      |
| title.ratings.tsv      | Ratings and votes               | 1.5M      |

---

## 🛠️ Tech Stack

- **Profiling & Cleaning:** Alteryx, Python, YData Profiler  
- **ETL & Pipelines:** Azure Data Factory,Hadoop, SQL, Alteryx  
- **Data Warehouse:** Snowflake (Medallion Architecture)  
- **Modeling:** ER Studio (Star Schema)  
- **Visualization:** Tableau

---

## 🔧 My Data Engineering Process

### 🏗️ Architecture

Implemented **Bronze → Silver → Gold layers** using Snowflake and ADF:

1. **Bronze:** Raw TSV ingestion into Snowflake  
2. **Silver:** Cleaning, flattening, and normalization in Alteryx  
3. **Gold:** Dimensional star schema for analytics and BI

---

### 🧹 Key Cleaning & Transformations

- Replaced all `\N` nulls with `"Unknown"` or `0`  
- Split multi-value fields (genres, known titles) into rows  
- Trimmed whitespace, standardized types (e.g. ratings as float)  
- Mapped ISO country and language codes for localization analysis  
- Built normalized genre, job, and character tables for seamless joins

---

## 🗃️ Star Schema Design

✅ Fact and dimension tables created for efficient querying:

- **Dimensions:** DIM_TITLE, DIM_GENRE, DIM_PERSON, DIM_REGION, DIM_LANGUAGE  
- **Facts:** FACT_RATING, FACT_EPISODE, FACT_JOB, FACT_CHARACTER

---

## 📊 Tableau Dashboards

### 🎬 Dashboard 1: Movie Trends

- Yearly release trends  
- Adult vs. non-adult movie insights  
- Country-wise counts  
- Ratings distributions

![Dashboard_P1_MovieTrendsAndReleases](https://github.com/user-attachments/assets/83e9400f-4f64-4136-a217-f12e472ab7b0)

### 🎭 Dashboard 2: Genre & People Analysis

- Top genres  
- Role-based contribution (actors, directors, writers)  
- Profession & job role distributions

![Dashboard_P2_AgeWiseDataTrends](https://github.com/user-attachments/assets/7ec86fb6-526b-4587-a6be-f6e00703e370)

---

## 💼 Key Skills Demonstrated

✔️ Designing scalable ETL pipelines  
✔️ Advanced data cleaning and parsing large TSV datasets  
✔️ Dimensional modeling in Snowflake  
✔️ Automating data loads via Azure Data Factory  
✔️ Creating BI dashboards aligned to real business questions

---

## 🎯 What This Project Proves

- Confidence working with **large-scale, multilingual, nested data**  
- Mastery of **cloud data warehousing and pipeline orchestration**  
- Ability to convert raw data into **meaningful business insights**

---

## 📊 Dimensional Model

![Dimensional_Model](https://github.com/user-attachments/assets/fc7f9737-c2a7-4d58-b08e-95777d39295f)

---

## 🔄 Pipeline (Azure Data Factory)

![Pipeline](https://github.com/user-attachments/assets/2af68739-f7fd-4c4e-a9f1-e5c971e07a62)

---

## 🤝 Let’s Connect

I enjoy turning complex data into impactful stories. If you’re looking for an intern or entry-level analyst/engineer who loves **data pipelines, warehousing, and BI**, feel free to reach out on [LinkedIn](https://www.linkedin.com/in/deepthiramesh23/).

---

**⭐ Feel free to fork, explore, and share your thoughts.**

---
