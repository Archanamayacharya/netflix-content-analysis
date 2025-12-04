# netflix-content-analysis
Exploratory analysis and machine learning on Netflix movies and TV shows dataset

# Netflix Content Analysis & Classification

## 📌 Overview
This project explores Netflix’s movies and TV shows catalog to identify trends in genres, countries, ratings, release years, and content strategy. Feature engineering and machine learning were applied to classify content type.

📊 Dataset Size: 8,790 rows × 10 columns  
👩‍💻 Author: Archana Anil Mayacharya

---

## ✅ Problem Statement
Analyze Netflix content data to uncover insights related to:
- Content type distribution (Movies vs TV Shows)
- Genre popularity and country contribution
- Release year and platform growth trends
- Ratings and audience targeting
- Predicting content type using ML

---

## 🛠 Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🔄 Workflow
### 1. Data Cleaning
- Verified no missing or duplicate records
- Cleaned text columns and standardized formatting
- Converted date fields to datetime

### 2. Feature Engineering
- Split duration into numeric value & unit
- Created movie duration & TV show season features
- Extracted year, month, day from `date_added`
- Engineered binary flags (TV show, kids content)
- Calculated number of genres per title

### 3. Exploratory Data Analysis
- Genre distribution analysis
- Content addition trends over time
- Country-wise content contribution
- Ratings distribution
- Movie duration vs TV show seasons
- Movies vs TV show proportion

### 4. Machine Learning
- Model: Random Forest Classifier
- Task: Predict Movie vs TV Show
- Features: genre count, duration, date features, kids content
- Target: content type

---

## 📈 Results
- Movies comprise ~70% of Netflix content
- Platform focuses on recent, international, and mature-rated content
- US and India dominate content production
- Most TV shows have only 1 season

**Model Performance:**
- Accuracy: 100%
- Precision / Recall / F1-score: 1.00

> High accuracy indicates strong separability between movies and TV shows due to effective feature engineering.

---

## 💡 Key Insights
- Netflix prioritizes global and modern content
- Limited-series formats dominate TV shows
- Feature engineering plays a crucial role in predictive performance

---

## 🚀 Future Scope
- Viewer behavior analysis
- Recommendation system
- Sentiment analysis on titles/descriptions
- Dashboard deployment with Streamlit
