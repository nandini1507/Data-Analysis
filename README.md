# Data-Analysis
This project analyzes a sample sales dataset using Pandas and Matplotlib.  It demonstrates loading CSV data, exploring with summary statistics, grouping by product and region,  filtering high sales, and visualizing trends with bar and line charts.  Key insights highlight top-performing products, regional contributions, and overall sales trends.

---

##  Steps in Notebook

### 1. Import Libraries
- Load Pandas and Matplotlib for analysis and visualization.

### 2. Load Dataset
- Read `sales.csv` using `pd.read_csv()`.
- Preview with `.head()`.

### 3. Explore Data
- Check shape, info, and summary statistics.
- Identify missing values.

### 4. Grouping & Aggregation
- Group sales by **Product**.
- Group sales by **Region**.

### 5. Filtering
- Filter rows where **Sales > 1000**.
- Identify high‑performing products and regions.

### 6. Visualizations
- **Bar chart**: Total Sales by Product  
- **Bar chart**: Total Sales by Region  
- **Line chart**: Sales Trend Over Time  

### 7. Key Insights
- Product A has the highest total sales.  
- The North region contributes the most revenue.  
- Sales show an upward trend over time.  

---

##  How to Run

1. Install dependencies:
   ```bash
   pip install pandas matplotlib
