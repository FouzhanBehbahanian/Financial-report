# First Dashboard 
# Financial Report – Product and Channel Analysis

## Introduction
This dashboard provides a financial reporting view of sales performance by product and channel.  
It was built in **Power BI** using a public sample dataset and is designed to help executives track product profitability and channel performance across regions.

---

## Dataset
- **Source**: Public e-commerce dataset (non-confidential)  
- **Scope**: Products, sales price, channels, and regional sales  
- **Granularity**: Product-level analysis across multiple geographies

---

## Objectives
- Compare sales prices across product lines  
- Analyze profitability by channel and region  
- Identify top-performing and underperforming products  
- Provide a breakdown of sales distribution for strategic planning

---

## Dashboard Features and Graph Analysis

### 1. Bar Chart – Sale Price by Product
- Highlights product-level pricing differences.  
- **Paseo has the highest sale price (22K)**, followed by VTT and Velo.  
- Business implication: Premium pricing could indicate strong demand or higher quality positioning.

### 2. Clustered Bar – Total Sales by Product and Channel
- Shows product-level revenue distribution across different countries.  
- **Paseo dominates** with consistently high sales across markets.  
- Some products (e.g., Carretera, Montana) show weaker channel coverage.  
- Insight: Sales strategies may need to be realigned for underperforming products.

### 3. Horizontal Bar – Total Sales by Product and Channel
- **Top performers**: Paseo ($2.60M), Velo ($1.58M), VTT ($1.46M).  
- **Lower performers**: Montana and Carretera (≈ $1.1M).  
- Insight: Portfolio concentration in a few products highlights risk exposure.

### 4. Empty Placeholder (ROI by State and Channel)
- ROI analysis placeholder indicates potential to integrate **state-level profitability**.  
- Suggests the design is scalable for advanced ROI and channel contribution analysis.

---

## Results
- **Paseo, Velo, and VTT** drive the majority of revenue, while Carretera and Montana underperform.  
- Pricing analysis shows significant product differentiation, with Paseo commanding premium pricing.  
- Geographic distribution reveals gaps where some products under-penetrate certain channels.  

---

## Real-World Application
This type of dashboard is valuable in:  
- **Consumer Goods**: Understanding product-level performance across markets.  
- **Retail and E-commerce**: Comparing product profitability across multiple sales channels.  
- **Manufacturing**: Aligning product portfolios with demand and identifying weaker product lines.

**Example Business Problem Solved:**  
A consumer goods company with uneven product performance could use this dashboard to:  
- Identify underperforming products (Carretera, Montana) for promotional focus.  
- Benchmark premium products (Paseo) against lower-value lines.  
- Allocate resources to strengthen weaker geographies and channels.

---
# 2) Second Dashboard – Financial Report: Profitability and Key Influencers
# Financial Report – Profitability and Key Influencers

## Introduction
This dashboard focuses on profitability, sales, and discount analysis.  
Built in **Power BI**, it integrates KPI tracking with an AI-driven Key Influencers visual to identify factors impacting profit.

---

## Dataset
- **Source**: Public e-commerce dataset (non-confidential)  
- **Scope**: Sales transactions, discounts, profit, and pricing variables  
- **Purpose**: To identify profitability drivers and areas where discounts or pricing strategies affect margins

---

## Objectives
- Track overall financial performance through key metrics  
- Understand the impact of discounts and pricing on profitability  
- Use machine learning-powered visualizations to identify key influencers of profit  
- Support executives in making data-driven pricing and discounting decisions  

---

## Dashboard Features and Graph Analysis

### 1. KPI Tiles
- **Total Sales**: $118.73M  
- **Total Profit**: $16.89M  
- **Total Discount**: $9.21M  
- These high-level metrics summarize the organization’s financial performance.

### 2. Key Influencers Visual
- Identifies drivers that impact **profit increases**.  
- **Discounts greater than 55,387** significantly increase average profit by $51.47K.  
- A **unit price increase of ~137** also boosts profit by $35.92K.  
- Insight: While discounts typically reduce profit, in this dataset, large discounts correlate with higher sales volumes, offsetting margin erosion.

### 3. Bar Chart – Profit by Discount Range
- Shows profit distribution across different discount levels.  
- Profit rises sharply when discounts exceed 55,000, confirming the influencers' analysis.  
- Business implication: Strategic high-volume discounting can increase profitability, but requires careful balance.

---

## Results
- The business generates strong sales ($118.73M) but relatively low profit margins ($16.89M).  
- Discounts play a **critical role in driving profit**, with large discount thresholds yielding significant gains.  
- Pricing adjustments also show potential for margin improvement.  

---

## Real-World Application
This dashboard is directly applicable in:  
- **Retail and E-commerce**: Optimizing discounting strategies while protecting profitability.  
- **Wholesale and Distribution**: Identifying the trade-off between volume discounts and profit margins.  
- **Consumer Electronics / Consumer Goods**: Balancing promotional discounts with profitability goals.

**Example Business Problem Solved:**  
A retailer struggling with declining profit margins could use this dashboard to:  
- Identify the tipping point where discounts start increasing profit.  
- Apply targeted pricing strategies to boost margins.  
- Justify promotional campaigns with clear ROI visibility.  
## File Structure


/financial-report/product-channel
├── financial_report.png
└── README.md


---

## Preview
[Financial]
<img width="1536" height="889" alt="Financial report" src="https://github.com/user-attachments/assets/d84f472b-4ad7-42ea-809f-33330e9f3486" />
<img width="1526" height="894" alt="Financial report 2" src="https://github.com/user-attachments/assets/ab01591c-c0e5-4d98-9d70-ce783c357bcb" />

[another design-same dataset]
<img width="1528" height="902" alt="image" src="https://github.com/user-attachments/assets/0f0abf29-bbed-43e1-a306-87365a3d8fa9" />


