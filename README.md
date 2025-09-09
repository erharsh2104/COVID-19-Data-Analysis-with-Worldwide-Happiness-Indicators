# COVID-19-Data-Analysis-with-Worldwide-Happiness-Indicators
This project analyzes the relationship between **COVID-19 cases/deaths** and the **World Happiness Report indicators**.   It combines real-world datasets, cleans and preprocesses them, performs exploratory data analysis (EDA), and visualizes global trends and correlations.

---

## 📊 Datasets Used

1. **COVID-19 Confirmed Cases** (`covid19_Confirmed_dataset.csv`)  
   - Daily confirmed cases worldwide, by country and date.
2. **COVID-19 Deaths** (`covid19_deaths_dataset.csv`)  
   - Daily deaths worldwide, by country and date.
3. **World Happiness Report** (`worldwide_happiness_report.csv`)  
   - Happiness scores and indicators (GDP per capita, social support, life expectancy, freedom, generosity, corruption).

---

## 🔍 Analysis Workflow

1. **Data Loading** – Import all three datasets using pandas.  
2. **Data Cleaning & Preprocessing** – Handle missing values, standardize country names, and aggregate COVID-19 data at country level.  
3. **Exploratory Data Analysis (EDA)** –  
   - COVID-19: Identify top 10 countries by cases and deaths.  
   - Happiness: Analyze top happiest countries and key indicators.  
4. **Merging Datasets** – Combine COVID-19 totals with happiness indicators.  
5. **Correlation Analysis** – Explore relationships between pandemic impact and happiness indicators using heatmaps and scatter plots.  
6. **Insights & Conclusion** – Summarize findings (e.g., no strong evidence that happier countries had better COVID outcomes).

---

## 📈 Key Insights

- The **US and Western Europe** had the highest COVID-19 cases and deaths (as of April 2020).  
- The **Nordic countries** (Finland, Denmark, Norway, etc.) remain the happiest, but did not face the highest COVID tolls early in the pandemic.  
- **Correlation analysis** showed no strong negative link between happiness and COVID impact — wealthier/happier nations often reported **more cases**, not fewer.  
- Conclusion: *The hypothesis that “happier countries had better COVID-19 outcomes” is not supported by this dataset slice.*

---

## 🛠️ Technologies Used

- **Python 3**  
- **Jupyter Notebook**  
- **pandas** – Data manipulation  
- **NumPy** – Numerical computing  
- **Matplotlib** / **Seaborn** – Data visualization  

---
## 📌 Author

- **Harsh Tripathi**
- ***Engineering Student @ IIIT Raichur***
- Passionate about AI, Data Science, and meaningful data-driven insights.
