# 🌍 Interactive Global Development Dashboard (1952–2007)

### Exploring the Relationship Between Income, Life Expectancy, and Global Inequality

## 📌 Project Overview

This project explores global development patterns from 1952 to 2007 using the Gapminder dataset.

The dashboard focuses on understanding the relationship between economic growth and health outcomes across different countries and continents.

It uses interactive data visualizations to explore how GDP per capita, life expectancy, and population have changed over time.

**Central Research Question:**

Does greater wealth always lead to better health?

## 🎯 Project Objectives

- Analyze changes in global life expectancy between 1952 and 2007.
- Explore the relationship between GDP per capita and life expectancy.
- Compare development patterns across five continents.
- Identify differences in health outcomes between countries.
- Present historical development trends through interactive visualizations.

## 📊 Dashboard Features

The dashboard includes six interactive visualizations:

### 1. Animated Income vs. Health Scatter Plot
Explores the relationship between GDP per capita and life expectancy across countries over time. Bubble size represents population.

### 2. Continental Life Expectancy Trends
Compares population-weighted life expectancy trends across five continents.

### 3. Top 10 Countries by Life Expectancy
Identifies and compares the countries with the highest life expectancy for each year.

### 4. Life Expectancy Distribution (1952 vs. 2007)
Compares the global distribution of life expectancy between 1952 and 2007.

### 5. Continental Life Expectancy Spread (2007)
Uses a box plot to examine variations in life expectancy between countries within each continent.

### 6. Median Life Expectancy Heatmap
Visualizes changes in median life expectancy across continents and years.

## 🔍 Key Insights

- Life expectancy and GDP per capita generally increased during the study period.
- Higher income is generally associated with better life expectancy, but the relationship is not linear.
- All five continents experienced improvements in life expectancy.
- Differences in life expectancy between continents remained visible.
- The distribution of global life expectancy shifted towards higher values between 1952 and 2007.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis and dashboard development |
| Pandas | Data manipulation and aggregation |
| Plotly Express | Interactive data visualization |
| Plotly Graph Objects | Customized interactive charts |
| Jupyter Notebook | Project development |
| Google Colab | Cloud-based notebook execution |
| HTML | Interactive dashboard presentation |

## 📂 Dataset Information

**Dataset:** Gapminder Dataset

The project uses the built-in Gapminder dataset available through Plotly Express.

```python
import plotly.express as px

df = px.data.gapminder()
```

### Dataset Features

- Country
- Continent
- Year
- Life Expectancy
- GDP per Capita
- Population

**Study Period:** 1952–2007

## 📁 Repository Structure

```text
Interactive-Global-Development-Dashboard/
│
├── Interactive_Global_Development_Dashboard.ipynb
│
├── dashboard (3).html
│
├── requirements.txt
│
└── README.md
```

## ⚙️ Installation and Execution

### Option 1: View the Interactive Dashboard

1. Download `dashboard (3).html` from this repository.
2. Open it using a modern web browser.
3. Explore the interactive charts using the available controls.

**Note:** An internet connection is required because the dashboard loads Plotly JavaScript from a CDN.

### Option 2: Run the Jupyter Notebook

**Step 1:** Clone or download this repository.

**Step 2:** Install the required Python libraries.

```bash
pip install -r requirements.txt
```

**Step 3:** Open the notebook using Jupyter Notebook or Google Colab.

**Step 4:** Run the notebook cells sequentially.

**Step 5:** Generate and download the interactive HTML dashboard.

## 📈 Project Outcome

The final outcome is an interactive global development dashboard that combines data analysis and visualization to explore historical changes in economic development and health outcomes.

It provides an accessible way to understand global development trends, compare continents, and identify inequalities across countries.

---

### 👩‍💻 Project Information

**Project:** Interactive Global Development Dashboard  
**Domain:** Data Analytics and Data Visualization  
**Tools:** Python, Pandas, Plotly, Jupyter Notebook  
**Dataset:** Gapminder  
**Study Period:** 1952–2007

---
*Developed as a data analytics project.*
