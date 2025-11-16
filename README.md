# Exploratory-Analysis---Netflix-dataset
Netflix Data Analysis - Python EDA exploring content trends, actor networks, and recommendation systems. Features TF-IDF vectorization, NetworkX graph analysis, Louvain clustering, and trend visualization of Netflix's catalog strategy.
# Netflix Movies and TV Shows Analysis

![Netflix](https://img.shields.io/badge/Netflix-Data%20Analysis-red) ![Python](https://img.shields.io/badge/Python-3.x-blue) ![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-lightgrey)

## 📊 Project Overview

This project conducts a comprehensive exploratory analysis of Netflix's content catalog to uncover strategic insights about their global content distribution, content similarity, and collaboration networks within the entertainment industry.

## 🎯 Business Objectives

- **Content Geography**: Analyze content availability and distribution across different countries
- **Content Recommendation**: Identify similar content using text-based feature matching
- **Network Analysis**: Examine collaboration patterns among actors and directors
- **Trend Analysis**: Investigate Netflix's strategic focus shift between movies and TV shows over recent years

## 🛠️ Tech Stack

- **Programming Language**: Python 3
- **Libraries**: 
  - Data Processing: `Pandas`, `NumPy`
  - Network Analysis: `NetworkX`, `python-Louvain`
  - Machine Learning: `Scikit-learn` (TF-IDF, Cosine Similarity)
  - Visualization: `Matplotlib`

## 📁 Dataset

The dataset contains listings of all movies and TV shows available on Netflix as of mid-2021, with details including:
- Title, type (Movie/TV Show)
- Director, cast
- Country, date added
- Release year, rating
- Duration, listed genres
- Description

## 🔍 Methodology & Key Insights

### 1. Content Availability by Country
- Calculated distinct content availability per country
- Mapped content distribution globally
- Identified countries with highest content volume for further analysis

### 2. Similar Content Detection
- Implemented NLP-based recommendation system using movie descriptions
- Utilized TF-IDF vectorization for text processing
- Applied cosine similarity to measure content similarity
- Generated top 5 similar content recommendations for each title

### 3. Actor Network Analysis
- Constructed co-star networks from the country with highest content volume
- Nodes represent actors, edges represent co-star relationships
- Edge weights indicate number of collaborative movies
- Applied Louvain clustering algorithm to identify community structures
- Revealed distinct actor clusters and collaboration patterns

### 4. Director-Actor Collaboration Network
- Built directed graph representing director-actor relationships
- Directed edges from directors to actors indicate collaborations
- Computed centrality measures to identify influential figures
- Analyzed collaboration frequency and network influence

### 5. Content Strategy Trends
- Aggregated movies vs TV shows data by year
- Visualized trends using Matplotlib line graphs
- Identified strategic shifts in content focus over time

  
## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook

### Installation
1. Clone the repository:
```bash
git clone https://github.com/sanjayanms/Exploratory-Analysis---Netflix-dataset
cd Exploratory-Analysis---Netflix-dataset

2. Install required packages:
pip install pandas numpy networkx scikit-learn matplotlib python-louvain

3. Run the analysis:
jupyter notebook Netflix\ analysis.ipynb
