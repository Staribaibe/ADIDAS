# ADIDAS
# ADVANCED SALES, PROFITABILITY, AND PRICE POINT ANALYSIS FOR ADIDAS RETAIL TECHNICAL REPORT

## Outline

- [Introduction](#introduction)
- [Story of Data](#story-of-data)
- [Data Splitting and Preprocessing](#data-splitting-and-preprocessing)
- [Pre-Analysis](#pre-analysis)
- [In-Analysis](#in-analysis)
- [Post-Analysis and Insights](#post-analysis-and-insights)
- [Data Visualizations and Charts](#data-visualizations-and-charts)
- [Recommendations and Observations](#recommendations-and-observations)
- [Conclusion](#conclusion)

## 1. Introduction

### Objective of the Project:

The primary goal of this project was to conduct a robust, multi-layered sales and profitability analysis using Adidas retail sales data. The analysis aimed to extract valuable insights into the performance of various products, sales methods, retailers, and regions to inform strategic decision-making across pricing, inventory management, and market expansion.

### Problem Being Addressed:

Adidas faced challenges in identifying which products, retailers, and geographic markets contributed most to profitability. Additionally, they needed to understand how price points and order quantities affected both revenue and profit margins. Without clear insights, the risk of overstocking unprofitable items, underpricing high-margin products, and misallocating marketing spend was significant.

### Key Datasets and Methodologies:

- Datasets: Sales transaction records encompassing products, retailers, regions, sales methods, order quantities, profits, margins, and price points.

Methodologies:

    • Data Cleaning & Validation
    • Descriptive Statistics
    • Profit Margin and Operating Margin Calculation
    • Price Point Bucketing
    • Advanced Pivot Table Analysis
    • Time Series Sales Trends
    • Comparative Margin Analysis
    • Data Visualization & Dashboard Development

## 2. Story of Data

### Data Source:

Adidas’ internal sales and operations database.

### Data Collection Process:

Sales data was automatically recorded through Adidas’ ERP and POS systems.

### Data Structure:

- Rows: Unique sales transactions.
- 
- Columns: Product category, retailer, order quantity, sales amount, profit, margin, sales method, state, and pricing details.

### Important Features:

Product Category, Retailer, Region/State, Order Quantity, Profit & Margin, Price Points.

### Data Limitations:

Minor missing values in profit and quantity fields. Seasonal effects and lack of demographic data limited deeper customer segmentation.

## 3. Data Splitting and Preprocessing

### Data Cleaning:

Removed duplicates, standardized naming conventions, and addressed outliers.

### Handling Missing Values:

Imputed or excluded records based on context.

### Data Transformations:

Created Price Point Buckets, Order Size Segments, and derived metrics like Operating Margin and Average Order Value.

### Data Splitting:

Dependent Variables: Profit, Sales Revenue, Operating Margin.

Independent Variables: Product Category, Retailer, Sales Method, Price Points, State.

### Industry Context:

Retail and consumer goods analytics.

### Stakeholders:

Sales, Marketing, Pricing, Supply Chain, and Regional Managers.

## 4. Pre-Analysis

### Key Trends:

High variability in profitability by product, retailer, and region.

### Potential Correlations:

- Order size vs. profit margin.
  
- Price point vs. sales volume and profitability.

### Initial Insights:

Volume leaders were not always profit leaders, highlighting the need for margin-focused strategies.

## 5. In-Analysis

### Hypotheses Tested:

- Higher price point products yield lower volume but higher margins.
  
- Some states and retailers offer high profits despite low sales.

### Analytical Techniques:

Pivot Tables, Advanced Formulas, Time Series Trend Analysis, and Comparative Margin Analysis.

### Preliminary Recommendations:

Shift focus to high-margin products, optimize retailer partnerships, and explore niche high-margin markets.

## 6. Post-Analysis and Insights

### Key Findings:

- Apparel outperformed footwear in profit margins.
  
- Top 3 retailers generated over 60% of profit.
  
- Small states delivered high margins.
  
- Higher-priced products achieved the best margins.

Comparison:
Volume did not equate to profitability, contradicting initial assumptions.

## 7. Data Visualizations & Charts
![image](https://github.com/user-attachments/assets/5a2b11cf-4137-489d-bda1-00c998d759b3)


## 8. Recommendations and Observations

### Actionable Insights:
1. Prioritize high-margin products.
2. Strengthen profitable retailer relationships.
3. Increase marketing in profitable regions.
4. Continue premium pricing strategies.

### Business Optimizations:
Revise pricing models, adjust inventory planning, and renegotiate retailer terms.

### Unexpected Outcomes:
Mid-priced products were less profitable than expected.

## 9. Conclusion

Key Learnings:

Profitability drivers differed from volume drivers, underscoring the importance of margin-focused decision-making.





