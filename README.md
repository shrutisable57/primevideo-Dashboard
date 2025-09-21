# 🎬 Amazon Prime Video Content Dynamics: Global Library Analysis

A comprehensive data visualization of the Amazon Prime Video content library from 1920 to 2021, focusing on key metrics like total titles, content type distribution, genre popularity, content rating, and geographical representation.

---

## Short Description / Purpose

The **Amazon Prime Video Content Dynamics Dashboard** is an analytical report designed to provide a high-level, visual overview of the platform's content catalog. It displays crucial key performance indicators (KPIs) such as **Total Movies (9,655)**, **Total Directors (5,771)**, and the **time span of content (1920–2021)**. The primary goal is to help content strategists, media analysts, and researchers understand the **scale, composition, and historical growth** of the Amazon Prime Video content library.

---

## Tech Stack

The dashboard was built using the following tools and technologies:

* **📊 Data Visualization Platform:** Power BI Desktop or Tableau (Standard Business Intelligence tools).
* **📂 Data Transformation:** Power Query Python for the necessary data cleaning and preparation pipeline.
* **🧠 Calculations/Measures:** DAX (Data Analysis Expressions).
* **📝 Data Source:** A structured dataset Kaggle containing Amazon Prime Video title records.
* **📁 File Format:** .pbix (Power BI) for development and **.jpg/.png** for the dashboard snapshot.

---

## Data Source

Source: **Kaggle Dataset** derived from Amazon Prime Video catalog listings.

---

## Features / Highlights

### Business Problem

As a major player in the streaming wars, Amazon Prime Video requires immediate, actionable insights into its vast library to compete effectively. Analyzing over 9,600 titles in raw data makes strategic decisions cumbersome.

Key questions addressed by the dashboard:
* How does the volume of movies compare to TV shows?
* What are the most common content ratings and genres?
* How has the content addition rate changed over time?

### Goal of the Dashboard

To deliver an **interactive visual tool** that summarizes the library's composition, enabling users to:
1.  Quantify the **scale** of the content library (9,655 titles).
2.  Identify the **dominant content type** (Movie vs. TV Show).
3.  Analyze the **historical trend** of content additions.
4.  Highlight the **most frequent genres and ratings**.

### Walkthrough of Key Visuals (Briefly!)

* **Key KPIs (Top Row):** Shows significant scale: **9,655 Total Movies**, **519 Total Genres**, **5,771 Total Directors**, and a content range from **1920 to 2021**.
* **Rating by Total movies (Bar Chart):** Shows the distribution of content ratings, with **13+** (Teen), **16+** (Young Adult), and **ALL** (General Audience) being the most common, indicating a broader family/teen focus than some competitors.
* **Genres by Total Shows (Bar Chart):** Ranks popular genres, with **Drama**, **Comedy**, and **Drama, Suspense** dominating the top spots.
* **Total Shows by Country (Map):** A heat map showing content presence, though less pronounced than other platforms, with concentrations in **North America and Europe**.
* **Movies and TV shows (Donut Chart):** Displays the decisive content split: **Movies (7.81K or 80.82%)** heavily outweigh **TV Shows (1.85K or 19.18%)**.
* **Total Movies by Release Year (Area/Line Chart):** The most critical visual, showing an **exponential growth in content volume starting heavily around 2000-2010**, peaking in recent years, consistent with streaming market expansion.

### Business Impact & Insights

* **Content Strategy:** Prime Video's library is overwhelmingly **Movie-focused (over 80%)**, suggesting a heavy investment in film acquisition/licensing over long-form TV show development.
* **Audience Targeting:** The strong representation of **13+** and **16+** ratings indicates a strategic aim toward broader teen and young-adult audiences, alongside general viewing (**ALL**).
* **Historical Growth:** The release year trend confirms that Prime Video's major catalog expansion began in the 21st century, with the largest volume added post-2010.

---

## Screenshots / Demos

![Amazon Prime Video Dashboard Snapshot](https://github.com/shrutisable57/primevideo-Dashboard/blob/main/primevideo_Sanpshot_of_%20Dashboard.png)
