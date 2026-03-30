# world_happiness_report_2019
My first data analysis project as part of the Data Analysis Bootcamp at allWomen. I explore what drives happiness worldwide using the World Happiness Report dataset (2019).

# 🌍 World Happiness Report Analysis

## 📌 Project Overview

This project explores the **World Happiness Report dataset (2019)** to understand what drives happiness across countries.

Using data analysis techniques, the project investigates:

* How countries rank in terms of happiness
* What factors influence happiness scores
* Differences between the happiest and least happy countries

The goal is to answer a central question:

> *What makes people happy at a country level?*

---

## 📊 Key Questions

* Which are the **top and bottom happiest countries** in 2019?
* Are there noticeable differences between **developed and developing countries**?
* What factors (GDP, social support, corruption, etc.) are most correlated with happiness?
* Do the **happiest countries share common patterns**?
* Are the drivers of happiness different for the least happy countries?

---

## 🧠 Methodology

### 1. Data Cleaning

* Removed irrelevant and duplicated columns
* Handled missing values (e.g. imputing based on averages)
* Checked:

  * Null values
  * Duplicates
  * Data consistency (country names)
* Identified and evaluated outliers using:

  * Boxplots
  * IQR method
  * Z-score

---

### 2. Exploratory Data Analysis (EDA)

* Distribution analysis of key variables
* Visualization of numerical features
* Identification of trends and anomalies

---

### 3. Comparative Analysis

* Top 25 happiest countries
* Bottom 25 least happy countries
* Cross-year comparison (2018 vs 2019)

---

### 4. Correlation Analysis

* Global correlation between happiness score and factors:

  * GDP per capita
  * Social support
  * Healthy life expectancy
  * Freedom
  * Generosity
  * Perceptions of corruption

* Separate correlation analysis for:

  * Top countries
  * Bottom countries

---

## 📈 Key Insights

### 🌟 Strong Drivers of Happiness

* **GDP per capita** and **social support** show strong positive correlation with happiness
* **Life expectancy** also plays an important role

---

### 🌍 Inequality Between Countries

* Happier countries tend to be:

  * Economically developed
  * Socially stable

* Less happy countries often show:

  * Lower economic indicators
  * Weaker institutional trust

---

### 🔍 Differences Between Top & Bottom Countries

* Top countries share **consistent positive correlations across multiple factors**
* Bottom countries show **weaker or inconsistent relationships**

---

### ⚠️ Corruption & Generosity

* **Perceptions of corruption** can negatively impact happiness
* **Generosity** has a weaker and less consistent effect than expected

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn (for visualization)
* Jupyter Notebook

---

## 📁 Project Structure

```id="projstruct1"
├── data/                  # Raw dataset(s)
├── notebooks/             # Jupyter Notebook analysis
├── outputs/               # Visualizations (optional)
├── README.md
```

---

## 📌 Limitations

* Analysis is limited to available variables in the dataset (data for 2019)
* Correlation does not imply causation
* Some missing values required approximation

---

## 🔮 Future Improvements

* Include more years for trend analysis
* Apply machine learning models to predict happiness score
* Add interactive dashboards (e.g. Plotly)

---

## 👩‍💻 About the Project

This project was developed as part of a **data analysis learning journey**, focusing on:

* Data cleaning
* Exploratory analysis
* Statistical reasoning
* Data storytelling
