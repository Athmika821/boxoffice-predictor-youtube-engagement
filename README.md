# 🎬 Box Office Prediction Using YouTube Trailer Engagement

### 📊 End-to-End Data Analytics & Machine Learning Project  
Predicting movie box office performance using YouTube engagement metrics, TMDB data, and Power BI insights.

---

## 🧩 Project Overview
This project explores how **YouTube trailer engagement** (views, likes, comments, publish date) can predict a movie’s **box office success**.  
It combines **data collection through APIs**,**web scraping**, **machine learning modeling**, and **interactive visualizations** in Power BI.

The workflow mirrors real-world data analytics pipelines used in entertainment analytics and marketing intelligence.

---

## 🧠 Objectives
- Collect and analyze YouTube trailer engagement data using the **YouTube Data API**.  
- Integrate metadata from the **TMDB API** (movie title, release date, genre, etc.).
- Scrape **budget and box office collection** data from a reliable film source
- Identify key engagement features influencing box office success.  
- Build and evaluate **machine learning models** to predict box office revenue.  
- Visualize performance metrics and insights through **Power BI dashboards**.

---

## 🔍 Data Sources
- 🎥 **YouTube Data API** — Trailer engagement metrics (views, likes, comments).  
- 🎞️ **TMDB API** — Movie metadata (genre, release date, budget, revenue).
- 💰 **Web Scraping** — Budget and box office collections from verified web sources  
- 📊 **Aggregated Datasets** — Additional pre-processed or validated data for modeling and comparison.

---

## ⚙️ Tools & Libraries

**Languages:** Python, DAX (Power BI)

**APIs:**  
- YouTube Data API  
- TMDB API  

**Python Libraries:**  
`pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `requests`,  
`json`, `datetime`, `scikit-learn`, `re`, `os`, `BeautifulSoup` (for web scraping)

**Visualization & Reporting:**  
- Power BI for interactive dashboards and KPI visualizations

---

## 🧪 Notebooks Included
1. **`RecentMovieTrailerEngagement&Success.ipynb`**  
   → Extracts data from YouTube and TMDB APIs, merges datasets, cleans and transforms data for analysis.  

2. **`BoxOffice_Prediction_RandomForest.ipynb`**  
   → Uses web-scraped box office data, applies feature engineering, builds a Random Forest regression model, evaluates it using R² and RMSE, and visualizes residuals.

---

## 📈 Power BI Dashboard Highlights
- 🎬 Movie and genre-wise performance comparison  
- 📆 Release year vs. revenue trend analysis  
- 💬 Engagement-to-revenue correlation visuals  
- 🏆 KPI cards showing top-performing genres and studios  

*(Add dashboard screenshot here, e.g. `/images/powerbi_dashboard.png`)*

---

## 🤖 Machine Learning Insights
- **Model Used:** Random Forest Regressor  
- **Evaluation Metrics:** R² score, MAE, RMSE  
- **Top Predictors:** YouTube views, likes-to-comments ratio, trailer release timing, genre, and movie budget  
- **Outcome:** Reliable prediction of revenue potential based on trailer engagement

---

## 📂 Folder Structure
boxoffice-prediction-youtube-powerbi/
│
├── data/                         # Raw, cleaned, and web-scraped datasets
│
├── notebooks/
│   ├── RecentMovieTrailerEngagement&Success.ipynb   # API extraction & data prep
│   └── BoxOffice_Prediction_RandomForest.ipynb      # Feature engineering & modeling
│
├── powerbi/
│   └── Trailer Buzz vs Box Office Performance.pbix   # Power BI dashboard
│
├── images/                    
│
├── README.md
│
└── requirements.txt              


## 🧭 Key Learnings
- Built a **complete data pipeline** from API extraction and web scraping to visualization.  
- Strengthened **data cleaning, feature engineering, and ML modeling** skills.  
- Learned to **blend structured (API) and unstructured (scraped) data** effectively.  
- Created **business-oriented Power BI visuals** for non-technical audiences.

---

## 🚀 Future Enhancements
- Incorporate **comment sentiment analysis** for deeper audience emotion insights.  
- Compare multiple ML models (XGBoost, Linear Regression, Gradient Boosting).  
- Deploy a simple **Streamlit app** to predict revenue for upcoming releases.  
- Automate scraping and API refresh for dynamic updates.

---

## 👩‍💻 Author
**Athmika TP**  
Aspiring Data Analyst | Power BI Enthusiast | Machine Learning Explorer  

📫 [LinkedIn](#) | [athmikatp1234@gmail.com](#)

---

## 🏷️ Tags
`#DataAnalytics` `#MachineLearning` `#YouTubeAPI` `#TMDBAPI` `#WebScraping` `#PowerBI` `#RandomForest` `#DataVisualization` `#BoxOfficePrediction`


