# 🏡 Nashville Housing Data Analysis (2013–2016)

## 📌 Project Overview
This project analyzes **residential property sales data from Tennessee (2013–2016)**.  
Using Python (Pandas, NumPy, Seaborn, Matplotlib), the dataset was cleaned and transformed, and key housing market insights were extracted.  
The analysis was then extended with **interactive Tableau dashboards** for visualization.

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Google Colab
- Tableau Public

---

## 📂 Repository Structure
- `data/` → Dataset 
- `notebooks/` → Jupyter/Colab notebooks with analysis
- `images/` → Exported plots & visuals
- `dashboard/` → Tableau workbook & screenshot
- `README.md` → Project documentation


---

## 🔍 Data Preparation
Steps taken to clean and prepare the dataset:
- ✅ Removed duplicate rows  
- ✅ Dropped irrelevant columns (`Legal Reference`, `Suite/Condo`, etc.)  
- ✅ Standardized text formats & corrected typos in categorical data  
- ✅ Converted data types (e.g., Sale Date → datetime)  
- ✅ Handled null values and outliers  
- ✅ Engineered new features:  
  - `Price_per_SqFt`  
  - `Sale_Year`, `Sale_Month`, `Quarter`  
  - `Property_Age`  
  - `Total_Bathrooms`  
  - `Is_Vacant`  

---

## 📊 Exploratory Data Analysis

### 🕒 Time-Based Trends
- **Sales peaked in Q2–Q3** each year, showing strong seasonality  
- **2015 showed a shift** in property type trends and pricing  

### 🏙️ Location-Based Insights
- **Nashville**: highest number of property transactions & most diverse land use types  
- **Brentwood**: highest average sale price (luxury-heavy market)  
- Single-family homes dominated across most cities  

### 🧱 Property Features
- **Newer homes (≤10 years)** sold for significantly higher prices  
- **Older homes** were sold more frequently, showing demand for affordability  
- **Day care centers, dormitories, and residential combos** showed high-value potential despite lower transaction volume  

### 💰 Price Insights
- Price per square foot varied widely across land use types  
- Premium per-square-foot values observed in **mobile homes, clubs, and niche property types**  
- Consistent increase in **average sale price across most property types**  

---

## 📈 Key Insights
- 🏙️ **City Trends**: Nashville = most active, Brentwood = highest priced  
- 📅 **Seasonality**: Sales volume strongest mid-year (Q2–Q3)  
- 🏠 **Property Types**: Single-family homes dominate; niche types offer high margins  
- 🆕 **New vs Old Homes**: Newer homes = higher prices, older homes = higher sales frequency  

---

## 🧠 Recommendations
1. **Focus on Nashville & Brentwood**: Balanced volume + luxury segment  
2. **Promote renovated older homes**: Affordable, high sales turnover  
3. **Time campaigns with seasonal peaks**: Q2–Q3 optimal window  
4. **Target niche property types**: Day care centers, dormitories, and combos = untapped high-value  

---

## 🔗 Tableau Dashboard
👉 [View Interactive Dashboard](https://public.tableau.com/your-dashboard-link)  

---

## 📓 Notebook
👉 [Colab Notebook](notebooks/nashville_analysis.ipynb)  

---

## 🔜 Next Steps
- Build predictive models for property pricing (e.g., regression, XGBoost)  
- Run clustering to identify similar neighborhoods  
- Extend dashboards using Plotly or Streamlit  

---
