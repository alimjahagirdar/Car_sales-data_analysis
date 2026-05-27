# Car Sales Data Analysis
An end-to-end data analysis project following the full data analysis lifecycle — from data cleaning and transformation to exploratory analysis and interactive Tableau dashboard. The project uncovers sales trends, manufacturer performance, pricing patterns, and the relationship between engine size and vehicle price.

# Tools
1. ETL: jupyter Notebook(python)
2. Visualization : Tableau 

# Process
## Data cleaning: [Car_sale_dataset](https://github.com/alimjahagirdar/data_analysis/blob/master/Car_Sale_Dataset.ipynb)

## Data process:[Car_sale_dataset](https://github.com/alimjahagirdar/data_analysis/blob/master/Car_Sale_Dataset.ipynb)

## Data Analyze and Act:
1. the first chart shows the number of models produced by the manufacturing companies in the data sets, in which Ford and Dodge are the two top companies with more models as compared with others.
2. 2nd chart shows the types of vehicles present in the dataset
3. 3rd chart shows the sum of the model's prices and the sum of sales of models of the manufacturer, where the prices of Mercedes-B models are much higher than others but they have a lower number of sales compared to Ford which has a higher number of sales
4. 4th chart shows the correlation between the prices of models and engine size, the trend shows that as the engine size increases the model price also increases/
5. 5th chart digs more deeply into analyzing Mercedes-B and Ford model prices and sales which shows Ford sales are much more than Mercedes-B as they produced affordable models whereas Mercedes-B  has lower sales but produces more costly premium models than Ford. 

## View the Tableau Dashboard : [Dashboard](https://public.tableau.com/views/Car_Sales_16876854650990/Dashboard1?:language=en-GB&:display_count=n&:origin=viz_share_link)

## Live Dashboard
![Dashboard 1 (1)](https://github.com/alimjahagirdar/data_analysis/assets/69685661/66c1ee57-7c7c-426b-b77a-47f1d3090148)


## 🛠️ Tools & Technologies
 
| Stage | Tool |
|---|---|
| Data Cleaning & ETL | Python (Pandas, NumPy) — Jupyter Notebook |
| Exploratory Analysis | Python (Matplotlib, Seaborn) |
| Visualization & Dashboard | Tableau Public |
 

📁 Project Structure
Car_sales-data_analysis/
│
├── Car_Sale_Dataset.ipynb   # Full analysis: cleaning, EDA, and visualization
└── README.md

# 🔄 Analysis Process
 
This project follows the six-stage data analysis framework:
 
### 1. Ask
Define business questions to guide the analysis:
- Which manufacturers produce the most models?
- Which vehicle types dominate the market?
- How do pricing and sales volumes compare across brands?
- Is there a relationship between engine size and vehicle price?
- Why do high-priced brands sometimes have lower sales volumes?
### 2. Prepare
- Loaded the car sales dataset into a Pandas DataFrame
- Reviewed data types, column structure, and overall shape
- Identified missing values and inconsistencies for treatment
### 3. Process (Data Cleaning & ETL)
- Handled missing values and null records
- Standardized data types across columns
- Removed duplicates and corrected inconsistent entries
- Transformed and structured data for downstream analysis
### 4. Analyze
- Aggregated sales and pricing data by manufacturer and model
- Segmented by vehicle type to understand market composition
- Calculated correlations between engine size and model price
- Compared volume leaders (Ford) vs premium brands (Mercedes-Benz)
### 5. Share (Key Findings)
 
**📌 Finding 1 — Model Volume by Manufacturer**
Ford and Dodge lead the dataset in number of models produced, significantly outpacing other manufacturers in model variety.
 
**📌 Finding 2 — Vehicle Type Distribution**
The dataset spans multiple vehicle types, with clear concentration in specific segments that reflect broader consumer demand patterns.
 
**📌 Finding 3 — Price vs. Sales Volume Trade-off**
Mercedes-Benz models command significantly higher prices than competitors, but Ford outperforms in total sales volume by producing affordable, mass-market models. This highlights the classic volume vs. margin trade-off in automotive markets.
 
**📌 Finding 4 — Engine Size & Price Correlation**
A clear positive correlation exists between engine size and model price — as engine size increases, model price increases proportionally. This trend holds consistently across manufacturers.
 
**📌 Finding 5 — Ford vs. Mercedes-Benz Deep Dive**
A focused comparison revealed that Ford's strength lies in high-volume, affordable model lines, while Mercedes-Benz prioritizes premium pricing with a smaller, higher-margin model range. Neither strategy is superior — they serve fundamentally different market segments.
 
### 6. Act
- Built an interactive Tableau dashboard consolidating all findings
- Dashboard enables filtering by manufacturer and vehicle type for self-serve exploration
- Insights support strategic decisions around pricing, model positioning, and market targeting
---
 
## 💡 Business Value
 
This analysis demonstrates how data-driven insights can directly inform:
- **Product strategy** — understanding which segments to compete in
- **Pricing decisions** — benchmarking against market positioning
- **Sales planning** — identifying volume drivers vs. premium revenue streams
- **Competitive intelligence** — comparing manufacturer strategies across price and volume dimensions
---
 
## ⚙️ How to Run
 
### Prerequisites
- Python 3.8+
- Jupyter Notebook
### Setup
```bash
git clone https://github.com/alimjahagirdar/Car_sales-data_analysis.git
cd Car_sales-data_analysis
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook Car_Sale_Dataset.ipynb
```
 
---
 
## 👨‍💻 Author
 
**Alim Jahagirdar**
Data Analyst | Dubai, UAE
[LinkedIn](https://www.linkedin.com/in/alimjahagirdar) · [GitHub](https://github.com/alimjahagirdar) · [Tableau Public](https://public.tableau.com/views/Car_Sales_16876854650990/Dashboard1)
 
