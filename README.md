# E-Commerce Sales Analysis

Analyzed the purchasing behavior of 349 e-commerce customers using Python and Power BI to surface insights on membership value, geography, demographics, and discount strategy.

## 🛠️ Tech Stack
* **Python** (Pandas, Matplotlib, Seaborn)
* **Jupyter Notebook**
* **Power BI**

## 📁 Dataset
* **File:** `E-commerce Customer Behavior - Sheet1.csv`
* **Details:** 349 records, 11 features including *Gender, Age, City, Membership Type, Total Spend, Items Purchased, Discount Applied,* and *Satisfaction Level*.

## 🔍 Analysis Phases
1. **Data Preparation:** Cleaned missing values and grouped customers into specific age brackets (20-30, 31-40, 41-50) for cohort analysis.
2. **Membership Tier Analysis:** Calculated average and total revenue contributions across different loyalty tiers.
3. **Geographical Revenue Analysis:** Evaluated total spend distribution across various cities to identify top-performing markets.
4. **Demographic Analysis:** Broke down purchasing habits by gender and age group to define the core buyer persona.
5. **Discount Effectiveness:** Investigated the correlation between applied discounts, average items purchased, and overall customer satisfaction.

## 📊 Power BI Dashboard Metrics

| Metric | Value |
| :--- | :--- |
| **Total Revenue** | $295.03K |
| **Avg. Spend per Customer** | $847.79 |
| **Top City** | San Francisco |
| **Top Age Cohort** | Age 30 |
| **Top Membership Tier** | Gold (52% of revenue) |
| **Gender Split (Avg Spend)** | Female 58.26% / Male 41.74% |

## 💡 Key Findings
* **Retention Priority:** Gold members drive 52% of total revenue ($153.4K), making them the most critical segment for retention efforts.
* **Geographic Focus:** San Francisco and New York are the top revenue-generating cities by a significant margin.
* **Core Demographics:** Age 30 is the single highest-spending cohort, and the 20-30 age group outspends older segments overall. Female customers account for 58.26% of the average spend.
* **The "Discount Paradox":** Discounted customers do not buy more items on average and actually show a higher proportion of unsatisfied responses, suggesting discounts are currently failing as a sales incentive.

## 🚀 How to Run

```bash
# Install required Python libraries
pip install pandas matplotlib seaborn jupyter

# Launch the Jupyter Notebook
jupyter notebook Customer_Behavior_Analysis.ipynb
