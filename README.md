# Customer-Segmentation-Marketing-ROI-Analysis
Customer segmentation and marketing campaign analysis using Python, K-Means clustering, and customer behavior analytics.
# 📊 Customer Segmentation & Marketing ROI Analysis

## 📌 Project Overview

This project analyzes customer purchasing behavior and marketing campaign engagement to identify distinct customer segments and understand how different customer groups respond to marketing campaigns.

Using Python, Pandas, Scikit-learn, and Seaborn, the project combines exploratory data analysis, feature engineering, and K-Means clustering to segment customers based on purchasing behavior, spending patterns, purchase channels, and campaign engagement.

The analysis is designed to help businesses understand:

- Who their high-value customers are
- Which customer groups have different purchasing behaviors
- Which marketing campaigns receive higher customer acceptance
- Which purchase channels customers prefer
- How campaign response varies across customer segments
- Which customer segments may represent growth opportunities
- How customer spending relates to recency and engagement

> **Important:** The dataset contains campaign acceptance and customer spending information, but it does not provide actual campaign costs or campaign-attributed revenue. Therefore, a true financial ROI cannot be calculated from the dataset alone. Campaign acceptance, response rate, customer spending, and segment-level customer value are used as marketing performance indicators instead.

---

# 🎯 Business Objective

The main objective is to transform customer-level purchasing and campaign data into actionable customer segments and marketing insights.

### Key business questions

1. What does the customer spending distribution look like?
2. Which product categories generate the highest customer spending?
3. Which purchasing channels are most frequently used?
4. How do customers respond to different marketing campaigns?
5. Can customers be grouped into meaningful behavioral segments?
6. Which segments have higher average spending?
7. Which segments show stronger campaign engagement?
8. How does purchase-channel preference differ across customer segments?
9. Which customer segments could be targeted with different marketing strategies?
10. What limitations should be considered when interpreting campaign performance?

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and modeling |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Customer segmentation |
| K-Means | Clustering algorithm |
| StandardScaler | Feature standardization |
| Silhouette Score | Cluster evaluation |
| Jupyter Notebook | Analysis environment |
| GitHub | Project documentation and version control |

---

# 📂 Dataset

### Dataset

**Customer Personality Analysis**

The dataset contains customer demographic information, purchasing behavior, spending across product categories, purchasing channels, and marketing campaign responses.

### Main information available

- Customer demographics
- Income
- Recency
- Household composition
- Product-category spending
- Web purchases
- Catalog purchases
- Store purchases
- Deal purchases
- Campaign acceptance
- Final campaign response

### Important columns

| Column | Description |
|---|---|
| `ID` | Customer identifier |
| `Year_Birth` | Customer birth year |
| `Income` | Customer income |
| `Kidhome` | Number of children |
| `Teenhome` | Number of teenagers |
| `Recency` | Days since last purchase |
| `MntWines` | Spending on wine |
| `MntFruits` | Spending on fruits |
| `MntMeatProducts` | Spending on meat products |
| `MntFishProducts` | Spending on fish products |
| `MntSweetProducts` | Spending on sweet products |
| `MntGoldProds` | Spending on gold products |
| `NumWebPurchases` | Number of web purchases |
| `NumCatalogPurchases` | Number of catalog purchases |
| `NumStorePurchases` | Number of store purchases |
| `NumDealsPurchases` | Number of purchases using deals |
| `AcceptedCmp1`–`AcceptedCmp5` | Campaign acceptance indicators |
| `Response` | Response to the latest campaign |

---

# 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Missing Value Treatment
     ↓
Feature Engineering
     ↓
Exploratory Data Analysis
     ↓
Customer Behavior Analysis
     ↓
Feature Scaling
     ↓
K-Means Clustering
     ↓
Elbow Method
     ↓
Silhouette Score
     ↓
Customer Segmentation
     ↓
Segment Profiling
     ↓
Campaign Analysis
     ↓
Marketing Recommendations
     ↓
Export Results
