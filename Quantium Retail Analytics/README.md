# 📊 Quantium Retail Analytics Virtual Internship (Forage)

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![tidyverse](https://img.shields.io/badge/tidyverse-1A162D?style=for-the-badge)
![ggplot2](https://img.shields.io/badge/ggplot2-Data%20Visualization-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📌 Project Overview

This project was completed as part of the **Quantium Retail Analytics Virtual Experience Program** on **Forage**.

The objective was to analyze a large retail transaction dataset to understand customer purchasing behaviour, evaluate a store layout trial, and provide data-driven business recommendations to the Category Manager.

The project covers the complete analytics workflow from **data cleaning** to **customer segmentation**, **exploratory analysis**, **control store selection**, **trial assessment**, and **business insights**.

---

# 🎯 Objectives

- Clean and validate retail transaction data
- Merge customer and transaction datasets
- Engineer new analytical features
- Analyze customer purchasing behaviour
- Identify high-value customer segments
- Select statistically similar control stores
- Evaluate the impact of trial store layouts
- Generate business recommendations supported by data

---

# 🛠 Tools & Technologies

- R
- RStudio
- tidyverse
- dplyr
- ggplot2
- readxl
- stringr
- lubridate

---

# 📂 Project Structure

```
Quantium-Retail-Analytics/

│
├── data/
│   ├── QVI_transaction_data.xlsx
│   ├── QVI_purchase_behaviour.csv
│
├── cleaned_data/
│   ├── cleaned_transaction.csv
│
├── scripts/
│   ├── 01_data_cleaning.R
│   ├── 02_customer_analysis.R
│   ├── 03_trial_analysis.R
│
├── outputs/
│   ├── csv/
│   ├── graphs/
│
├── images/
│
└── README.md
```

---

# 📋 Project Workflow

## 1️⃣ Data Cleaning

Performed extensive data quality checks including:

- Missing value analysis
- Duplicate detection
- Outlier identification
- Brand name standardization
- Packet size extraction
- Date conversion
- Data type validation

---

## 2️⃣ Feature Engineering

Created new variables including:

- Brand
- Pack Size
- Month
- Customer Metrics
- Store Metrics

---

## 3️⃣ Exploratory Data Analysis

Analyzed:

- Total Sales
- Monthly Sales Trend
- Customer Count
- Transactions per Customer
- Chips Purchased
- Average Unit Price

Visualizations were created using **ggplot2**.

---

## 4️⃣ Customer Segmentation

Customer behaviour was analyzed using:

- LIFESTAGE
- PREMIUM_CUSTOMER

Key metrics included:

- Total Sales
- Purchase Frequency
- Average Spend
- Customer Contribution

---

## 5️⃣ Trial Store Analysis

Evaluated trial stores:

- Store 77
- Store 86
- Store 88

Measured:

- Monthly Sales
- Customer Count
- Transactions per Customer

---

## 6️⃣ Control Store Selection

Control stores were selected using:

- Pearson Correlation
- Magnitude Distance
- Composite Similarity Score

Selected Control Stores:

| Trial Store | Control Store |
|-------------|---------------|
| 77 | 233 |
| 86 | 155 |
| 88 | 237 |

---

## 7️⃣ Statistical Analysis

Performed:

- Percentage Difference Analysis
- Standard Deviation
- Confidence Interval Comparison
- Trial vs Control Assessment

---

# 📈 Key Insights

- Identified customer segments contributing the highest sales.
- Evaluated purchasing behaviour across different life stages.
- Measured the effectiveness of trial store layouts.
- Compared trial stores with statistically matched control stores.
- Produced business recommendations supported by quantitative analysis.

---

# 💼 Business Recommendation

The analysis indicates that:

- Trial Stores **77** and **88** demonstrated a positive impact during the trial period.
- Trial Store **86** showed weaker evidence of improvement and may require additional investigation.
- Results suggest the trial layout has potential for wider rollout, subject to further validation.

---

# 📚 Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Customer Segmentation
- Retail Analytics
- Statistical Analysis
- Business Analytics
- Data Visualization
- R Programming

---

# 📊 Dataset

The datasets were provided as part of the **Quantium Retail Analytics Virtual Experience Program** hosted on **Forage**.

---

# 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Quantium-Retail-Analytics.git
```

2. Open the project in **RStudio**

3. Install required packages

```r
install.packages(c(
  "tidyverse",
  "readxl",
  "stringr",
  "lubridate",
  "ggplot2"
))
```

4. Run the scripts in order:

```
01_data_cleaning.R

↓

02_customer_analysis.R

↓

03_trial_analysis.R
```

---

# 📜 Virtual Experience

**Organization:** Quantium

**Platform:** Forage

Project Type:

Retail Strategy & Analytics Virtual Internship

---

## 👨‍💻 Author

**Rachit Shukla**

Aspiring Data Analyst | Python | SQL | R | Power BI | Data Analytics

---

⭐ If you found this project helpful, feel free to star the repository.
