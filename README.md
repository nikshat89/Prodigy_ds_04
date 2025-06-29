# Prodigy_ds_04
# 🧠 Twitter Sentiment Analysis & Visualization

This project analyzes and visualizes public sentiment on Twitter using the [Twitter Entity Sentiment Analysis dataset](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis). The goal is to understand public opinion toward various entities (e.g., brands, products, people) through sentiment classification and visualization techniques.

---

## 📁 Dataset

- **Source:** Kaggle  
- **File:** `twitter_training.csv`  
- **Columns:**
  - `id`: Tweet/sample ID
  - `entity`: Brand or topic in the tweet
  - `sentiment`: Sentiment label (`Positive`, `Negative`, `Neutral`, `Irrelevant`)
  - `content`: Tweet text

---

## 🚀 Project Workflow

### ✅ 1. Data Loading & Preprocessing
- Loaded dataset using `pandas`
- Added proper column names
- Checked data structure and missing values

### ✅ 2. Sentiment Distribution
- Counted the number of tweets for each sentiment
- Visualized using a bar plot

### ✅ 3. Word Clouds for Each Sentiment
- Generated word clouds for:
  - Positive tweets
  - Negative tweets
  - Neutral tweets

### ✅ 4. Top Entities by Sentiment
- Identified the top 10 most mentioned entities
- Visualized sentiment counts per entity using a grouped bar plot

### ✅ 5. Heatmap of Sentiment by Entity
- Created a heatmap showing frequency of each sentiment for each top entity

---

## 📊 Visualizations

-  Sentiment distribution 
-  Word clouds for each sentiment
-  Top entity sentiment bar plot
-  Sentiment heatmap per entity

---

## 🛠️ Libraries Used

```bash
pandas
matplotlib
seaborn
wordcloud

