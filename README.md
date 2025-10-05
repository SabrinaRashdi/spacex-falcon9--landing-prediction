# 🛰️ SpaceX Falcon 9 First Stage Landing Prediction

## 📖 Project Overview  
This project aims to predict the likelihood of a successful **Falcon 9 first-stage landing** using SpaceX launch data.  
By analyzing launch records, payload characteristics, and booster versions, we can estimate the probability of successful recovery — a key cost-saving factor for SpaceX.  

The project was developed as part of the **IBM Data Science Capstone**, combining skills in **data collection, data wrangling, exploratory data analysis, visualization, and machine learning**.

---

## 🎯 Objectives
- Collect launch data using SpaceX’s **REST API** and **web scraping**  
- Clean and wrangle the data into a usable form  
- Perform **exploratory data analysis (EDA)** using SQL and visualization  
- Build **interactive visualizations** using **Folium** and **Plotly Dash**  
- Apply **machine learning models** (Logistic Regression, SVM, Decision Tree, KNN) to predict first-stage landing success  
- Compare model performances to determine the best predictor  

---

## 🧰 Tools & Technologies

| Category | Tools |
|-----------|-------|
| Data Collection | SpaceX REST API, BeautifulSoup |
| Data Wrangling | Pandas, NumPy |
| EDA (SQL + Visualization) | SQLite, Matplotlib, Seaborn |
| Interactive Visualization | Plotly Dash, Folium |
| Machine Learning | Scikit-learn |
| Environment | Jupyter Notebook, Python 3.x |

---

---

## 🔍 Methodology Summary
1. **Data Collection**  
   - Acquired SpaceX launch data using the **SpaceX REST API** and **web scraping**  
   - Merged multiple datasets into a unified structure for analysis  

2. **Data Wrangling**  
   - Cleaned data by handling missing values, normalizing fields, and formatting categorical features  
   - Created new derived features such as `Class` (landing success) and payload mass bins  

3. **Exploratory Data Analysis (EDA)**  
   - SQL queries were used to extract key insights on launch success, booster version, and payload distribution  
   - Visualized relationships between launch sites, payload mass, orbit type, and success rate  

4. **Interactive Visualization**  
   - **Folium maps**: Displayed launch site locations, distances to coastline, and clustering  
   - **Plotly Dash**: Built an interactive dashboard with dropdowns, pie charts, and scatter plots  

5. **Predictive Analysis (Machine Learning)**  
   - Trained classification models (Logistic Regression, SVM, Decision Tree, KNN)  
   - Tuned hyperparameters using **GridSearchCV**  
   - Evaluated model performance using accuracy and confusion matrices  
   - **Best model:** Decision Tree (Accuracy: **0.8732**)  

---

## 📊 Key Results
- Identified payload ranges and booster versions most correlated with successful landings  
- Demonstrated that **Decision Tree Classifier** outperformed other models  
- Built an **interactive dashboard** and **geographical map** for exploring launch insights dynamically  

---


