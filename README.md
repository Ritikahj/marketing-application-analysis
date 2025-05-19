# 📊 Marketing & Application  Analysis

This project analyzes customer application data across different lease grades, marketing campaigns, and store locations to uncover actionable insights that help improve campaign ROI, credit utilization, and operational efficiency.

It integrates four data sources and covers five analysis tasks, generating visualizations and metrics to support data-driven decision-making for marketing, credit, and strategy teams.

---

##  Dataset Overview

The analysis is based on four interrelated datasets:

| Dataset        | Description                                                           |
|--------------  |-----------------------------------------------------------------------|
| `applications` | Includes application date, approval status, approved and used amounts |
| `customers`    | Contains demographics like income, age, and associated campaign       |
| `marketing`    | Campaign metadata like name and spend                                 |
| `stores`       | Store-level data including state, industry, and size                  |

---

##  Analysis Tasks

###  **Task 1: Application Trends Over Time**
- Visualizes trends for total, approved, and used applications month over month
- Identifies seasonal dips (e.g., in Q1) and strong months (Q3–Q4)

###  **Task 2: Amount Analysis**
- Tracks average approved and used dollar amounts over time
- Helps understand customer credit usage patterns and changes in policy or demand

###  **Task 3: Store Performance Metrics**
- Computes KPIs like approval rate, usage rate, and utilization rate by store
- Generates a heatmap of applications by state
- Supports regional performance optimization

###  **Task 4: Marketing Campaign Effectiveness**
- Compares campaigns by used dollars and marketing spend
- Produces ROI-like metric: dollars used per dollar spent
- Visualized by year and by campaign

###  **Task 5: Advanced Insights**
- Combines lease grade, state, campaign, and store data
- Evaluates credit behavior across demographic and regional segments
- Visualizes utilization rate by campaign across top 10 states using a heatmap
