# FLO.kz Market Intelligence & Retail Strategy 👟📊

This project delivers a comprehensive data science pipeline to analyze the footwear market in Kazakhstan using data from **flo.kz**. We transition from raw web scraping to machine learning-driven insights to define a market entry strategy for a new retail venture.

## 👥 The Team (Algoth Project)
* **Yernar (Team Lead)** — Strategic synthesis, project management, and final documentation.
* **Yerkebulan** — Data Engineering: Scraper architecture (Selenium/BS4) and pipeline automation.
* **Zhayik** — Data Science: Statistical validation, hypothesis testing, and outlier management.
* **Dinmukhambet** — Analytics & Visualization: Interactive dashboards and qualitative text analysis.

## 🛠 Technical Stack
* **Languages:** Python 3.x
* **Data Handling:** `pandas`, `numpy`
* **Scraping:** `BeautifulSoup4`, `selenium`
* **Machine Learning:** `scikit-learn` (Random Forest Regressor for feature importance)
* **Visualization:** `matplotlib`, `seaborn`, `plotly`, `wordcloud`
* **Statistics:** `scipy.stats`

## 📊 Key Project Phases

### 1. Web Scraping & Cleaning
- Automated extraction of product names, brands, prices, and categories.
- Data normalization: Converting currency strings to numeric formats and handling missing discount values.

### 2. Exploratory Data Analysis (EDA)
- **Distribution Analysis:** Identifying price skews and market concentration.
- **Brand Mapping:** Segmenting the market into "Mass-market" (Polaris, Lumberjack) vs "Premium" (Nike, Adidas, Reebok).
- **Interactive Dashboards:** Multi-dimensional scatter plots to visualize price-to-discount correlations.

### 3. Machine Learning Insights
- **Feature Importance:** Using a **Random Forest** model to identify price drivers.
- **Result:** The `Brand_Price_Diff` feature was identified as the primary predictor of market positioning (Importance: 0.423).

### 4. Text Mining
- Word cloud generation to identify product versioning trends (e.g., the prevalence of "5Fx", "4Fx", and "XPr" series).

## 📋 How to Run
1. **Clone the repo.**
2. **Install requirements:**
   ```bash
   pip install pandas numpy beautifulsoup4 selenium matplotlib seaborn plotly wordcloud scikit-learn scipy