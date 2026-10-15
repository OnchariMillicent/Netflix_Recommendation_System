# Netflix Recommendation System

An end-to-end data science project analyzing Netflix content through exploratory analytics, recommendation systems, predictive modeling, time-series forecasting, interactive visualization, and business insights.

# Netflix Business Insights

## Project Overview

The Netflix Business Insights project explores Netflix's content catalog using data cleaning, exploratory data analysis (EDA), interactive visualization, and predictive modeling.

The project examines catalog composition, content ratings, movie runtimes, TV Show season counts, genre representation, geographic distribution, and original release-year trends. It translates these findings into business recommendations and identifies opportunities for deeper analysis using audience engagement and viewing data.

The goal is to demonstrate how data analysis can help stakeholders understand a content portfolio, identify patterns, and make more informed business decisions.

## Business Problem

Streaming platforms manage extensive content catalogs with different formats, genres, ratings, release periods, and geographic origins. Understanding how a catalog is structured can help stakeholders assess content representation and identify areas that deserve further investigation.

This project addresses the need for a structured analysis of Netflix's catalog by exploring its composition and distribution. It also highlights an important limitation: catalog counts alone cannot establish audience demand, viewing engagement, or profitability.

The analysis therefore provides an initial view of the content portfolio and identifies additional data needed to evaluate content performance more reliably.

## Project Objectives

- Assess the quality and structure of the Netflix catalog dataset.
- Compare the distribution of Movies and TV Shows.
- Examine catalog additions over time.
- Analyze content ratings and duration patterns.
- Identify the most represented genres and countries.
- Explore the distribution of original release years.
- Build interactive visualizations to communicate findings.
- Translate analytical results into practical, evidence-based business recommendations.
- Explore Movie-versus-TV-Show classification as a predictive modeling task.

## Data Source

The project uses a Netflix titles dataset containing information about Movies and TV Shows, including title, content type, director, country, date added, release year, rating, duration, and listed genres.

A cleaned version of the dataset is used for the analysis. Data preparation includes handling missing or placeholder values, standardizing fields, and creating additional features to support exploratory analysis.

**Dataset source:** Provided by the Institution

**Dataset used:** `netflix_cleaned.csv`

The analysis reflects the records available in the dataset and should not be interpreted as a complete representation of Netflix's current catalog or audience behavior.

## Stakeholders

The analysis is designed to support stakeholders who need to understand the composition and characteristics of a streaming content catalog.

- **Content Strategy Teams:** Understand genre, content type, release year, and geographic representation.
- **Business and Data Analysts:** Identify catalog patterns and communicate findings through reports and interactive visualizations.
- **Content Acquisition Teams:** Use catalog insights as a starting point for further investigation into content portfolio gaps and opportunities.
- **Management and Decision-Makers:** Review evidence-based findings to inform questions about content portfolio strategy.

These stakeholders would need additional audience engagement, viewing, and cost data before making decisions about content performance or investment.

## Tools and Technologies

- **Python:** Data cleaning, analysis, and predictive modeling.
- **Pandas and NumPy:** Data manipulation and preparation.
- **Matplotlib and Seaborn:** Statistical and exploratory visualisation.
- **Plotly:** Interactive data visualisations.
- **Scikit-learn:** Machine learning and model evaluation.
- **Jupyter Notebook:** Analysis documentation and experimentation.
- **Git and GitHub:** Version control and project sharing.

## Methodology

The project follows a structured data analysis workflow:

1. **Data preparation:** Inspect the dataset, assess data quality, handle missing or placeholder values, and prepare fields for analysis.
2. **Exploratory data analysis:** Examine catalog composition, content additions, ratings, duration, genres, countries, and original release years.
3. ** Visualization:** Build interactive charts to make distributions and patterns easier to explore.
4. **Predictive modeling:** Explore classification of titles as Movies or TV Shows using available metadata.
5. **Business interpretation:** Translate observed patterns into recommendations while documenting data limitations.
6. **Reporting:** Consolidate the analysis, findings, and recommendations into a structured notebook.

## Key Findings

- **Content composition:** The dataset contains 8,790 titles, including 6,126 Movies and 2,664 TV Shows.
- **Catalog additions:** Movie additions peaked in 2019 with 1,424 titles, while TV Show additions peaked in 2020 with 595 titles.
- **Content ratings:** TV-MA is the most frequent rating among both Movies and TV Shows in the dataset.
- **Duration:** Movies have a median runtime of 98 minutes, while the median recorded TV Show duration is one season.
- **Genre representation:** International Movies, Dramas, and Comedies are among the most represented Movie genres; International TV Shows, TV Dramas, and TV Comedies are among the leading TV Show genres.
- **Geographic representation:** The United States has the highest country-associated title counts for both Movies and TV Shows.
- **Release years:** The 2010s are the most represented release decade, and 2018 is the most represented individual release year.

These findings describe catalog characteristics and do not directly measure viewing demand, audience engagement, or profitability.

## Business Recommendations

Based on the catalog analysis, the following opportunities warrant further investigation:

1. **Evaluate content portfolio balance:** Compare the distribution of Movies and TV Shows with audience engagement and viewing patterns to assess whether the current mix aligns with business objectives.
2. **Investigate genre representation:** Combine genre counts with viewing hours, completion rates, and subscriber feedback to understand which content categories attract and retain audiences.
3. **Explore regional content representation:** Use regional viewing data and market research alongside country-associated title counts to assess the alignment between catalog composition and audience needs.
4. **Assess content recency:** Compare viewing performance across release years to investigate the relationship between release recency and audience engagement.
5. **Improve metadata quality:** Validate unusual duration records and maintain consistent catalog metadata to support reliable analysis.
6. **Expand performance analysis:** Integrate viewing, engagement, retention, and content cost data to support stronger evaluations of content performance and investment decisions.

These are proposed directions for further analysis. The catalog dataset alone does not establish audience demand or commercial performance.

## Limitations

- The dataset represents the records provided for this project and may not reflect Netflix's current catalogue.
- Missing or placeholder metadata may limit the completeness of country and other categorical analyses.
- Titles associated with multiple countries or genres can appear in more than one category, so category counts may overlap.
- Catalogue counts do not measure viewing hours, audience preferences, completion rates, subscriber retention, or profitability.
- Unusual duration values require validation before they are interpreted as typical movie runtimes.
- Predictive classification of Movies versus TV Shows does not predict popularity, demand, or commercial success.
- The analysis is observational and should not be used to infer causal relationships.

