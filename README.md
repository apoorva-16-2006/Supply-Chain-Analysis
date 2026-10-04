# Supply-Chain-Analysis
Analyzed supply chain data using Python, Pandas, and visualization libraries to identify shipping delays, delivery trends, and profitability patterns, providing data-driven recommendations to improve operational efficiency.

# 📦 Supply Chain Analysis: Order Delivery, Shipping Delays & Profitability

## 📌 Project Overview

This project analyzes supply chain operations to understand order delivery performance, shipping delays, and order profitability. Using Python and data analysis techniques, the project explores delivery patterns, identifies segments with higher delay rates, and develops business recommendations to support better operational decision-making.

## 🎯 Objectives

- Analyze order delivery performance and shipping delays.
- Calculate delivery KPIs and understand delay patterns.
- Compare delivery performance across regions, shipping modes, departments, and time periods.
- Explore the relationship between shipping delays and order profitability.
- Provide data-driven recommendations for improving supply chain operations.

## 📊 Key Performance Indicators

The latest notebook output reports the following metrics:

| KPI | Result |
|---|---:|
| Total Orders Analyzed | 34,727 |
| Late Deliveries | 19,491 |
| Late Delivery Rate | 56.13% |
| Non-Late Delivery Rate | 43.87% |
| 90th Percentile Delay | 3 days |
| Reported Profit Total | $1.5M |
| Delayed-Order Profit Value | $410.7K |

**Metric definitions:** The late delivery rate is based on the notebook's calculated delay metric. The non-late category includes both early and on-schedule orders. The financial figures should be interpreted according to the aggregation logic in the notebook; they do not necessarily represent net profit or losses caused by delays.

## 🛠️ Tools & Technologies

- **Python** — Data analysis
- **Pandas** — Data manipulation and cleaning
- **NumPy** — Numerical operations
- **Matplotlib & Seaborn** — Data visualization
- **Jupyter Notebook** — Analysis and documentation

## 🔍 Project Workflow

1. **Data Loading and Inspection** — Loaded the supply chain dataset and examined its structure.
2. **Data Cleaning** — Prepared date columns and excluded cancelled shipments from the analysis.
3. **Feature Engineering** — Calculated order processing time, delay, late-delivery flags, and time-based features.
4. **Exploratory Data Analysis (EDA)** — Examined delivery trends and compared operational segments.
5. **KPI Analysis** — Calculated delivery and profitability metrics.
6. **Business Recommendations** — Identified areas for further investigation and potential operational improvements.

## 📈 Key Findings

- The latest notebook classifies 56.13% of analyzed orders as late using its calculated delay metric.
- Delivery performance can be compared across regions, shipping modes, departments, and time periods to identify areas requiring investigation.
- Order profitability varies across delay categories, but these differences alone do not establish that delays cause lower profits.
- The results highlight the importance of validating delivery metrics and investigating operational factors before implementing changes.

*Note: Detailed delay-distribution and segment-level findings should be recalculated on the latest filtered dataset before being reported as final results.*

## 💡 Business Recommendations

- Review shipping schedules and compare promised delivery times with observed performance.
- Investigate regions and service segments with elevated delay rates.
- Monitor delivery KPIs consistently across operational groups.
- Evaluate profitability alongside delivery performance and order characteristics.
- Test targeted improvements and measure their impact before scaling them.

## ⚠️ Limitations

- Delivery delay is calculated from parsed order and shipping dates relative to scheduled shipping days.
- The calculated delay metric may differ from the dataset's original delivery-status or late-risk fields.
- The reported profit total and delayed-order value depend on the aggregation logic used in the notebook.
- Observational patterns do not establish causation.
- Segment-level results should be interpreted alongside group sizes and data quality.

## 📁 Repository Contents

- `supply_chain_analysis.ipynb` — Data cleaning, exploratory analysis, KPI calculations, and visualizations.
- `Supply_Chain_Analysis_Presentation.pptx` — Project presentation for portfolio and interview discussions.
- `README.md` — Project overview, workflow, findings, and recommendations.

*Update the filenames above if your repository uses different names.*

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `supply_chain_analysis.ipynb`.
5. Ensure the dataset is available at the path referenced in the notebook.
6. Run all cells from top to bottom to refresh the analysis and outputs.

## 👩‍💻 Author

**Apoorva Jaliminchi**  
BCA — AI & Data Analytics  

---

*This project demonstrates practical skills in data cleaning, exploratory data analysis, KPI development, data visualization, and translating analytical findings into business recommendations.*
