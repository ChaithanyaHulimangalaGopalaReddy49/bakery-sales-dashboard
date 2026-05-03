# Bakery Sales Dashboard Analysis  
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly  
**Type:** Exploratory Data Analysis (EDA)  
**Dataset:** European Bakery Sales Dataset – 1,000 transactions  
**Focus:** Profit analysis across 5 European cities (2000–2005)  

---

## Project Objective  

The project analyses a European bakery dataset to understand how city location and product type influence profitability.  
The aim is to explore business performance using data and derive meaningful insights through visualisation.

**Key questions answered:**  
1. What is the total profit across different cities?  
2. Which confectionary products generate the highest profit?  
3. How does profit change over time?  
4. What is the relationship between revenue, cost, and profit?  
5. How consistent are profit margins across cities?  

---

## Project Structure  

| File | Description |
|------|-------------|
| bakery_analysis.ipynb | Main analysis notebook |
| README.md | Project documentation |
| chart1_profit_by_city.png | Profit by city |
| chart2_profit_by_confectionary.png | Profit by product |
| chart3_annual_trend.png | Annual profit trend |
| chart4_heatmap.png | City vs product heatmap |
| chart5_boxplot_margin.png | Profit margin distribution |
| chart6_stacked_bar.png | Profit composition |
| chart7_scatter_rev_profit.png | Revenue vs profit |

---

## Analysis Steps  

### 1. Data Loading and Exploration  
- Loaded dataset into Pandas  
- Checked shape, data types, and summary statistics  
- Identified missing values  

### 2. Data Cleaning  
- Filled missing values using relationships:  
  - Revenue = Cost + Profit  
  - Cost = Revenue − Profit  
- Filled missing Units Sold using median  
- Removed remaining null values  

### 3. Feature Engineering  
- Extracted Year and Month from Date  
- Created Profit Margin  
- Ensured consistent categorical values  

---

## Visualisations and Analysis  

- Bar chart for profit by city  
- Horizontal bar chart for product performance  
- Line chart for annual trends  
- Heatmap for city-product comparison  
- Box plot for profit margin distribution  
- Bubble chart for revenue vs profit  

---

## Key Findings  

| Finding | Detail |
|--------|--------|
| Most profitable cities | Paris and Napoli |
| Least profitable city | London |
| Best-performing product | Caramel |
| Trend | Profit increases over time |
| Insight | Product choice impacts profit more than location |

---

## Personal Insights  

One notable finding is that London shows lower total profit but similar profit margins, suggesting that the issue is related to sales volume rather than efficiency.  
This indicates that improving product strategy could be more effective than focusing only on location.

---

## Technologies Used  

| Library | Purpose |
|--------|--------|
| Pandas | Data cleaning and analysis |
| NumPy | Numerical operations |
| Matplotlib | Visualisations |
| Seaborn | Styling and statistical plots |
| Plotly | Interactive dashboard |

---

## Dataset  

- Type: Academic dataset  
- Records: 1,000  
- Time period: 2000–2005  
- Scope: 5 cities, multiple products  

---

## Author  

Chaithanya Hulimangala Gopala Reddy

MSc Data Science – Arden University  
