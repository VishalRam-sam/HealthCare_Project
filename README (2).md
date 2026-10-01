# 🏥 Healthcare Data Analysis

### Turning raw healthcare records into meaningful business insights

Healthcare generates large volumes of patient, admission, billing,
insurance, and clinical data. This project explores how Python can turn
those raw records into a cleaner, structured dataset and answer
practical healthcare business questions.

The analysis starts with **55,500 patient records** and focuses on data
quality, patient patterns, billing, insurance coverage, admissions, and
operational review.

------------------------------------------------------------------------

## 🎯 The Story Behind the Analysis

The first step was to make the data trustworthy.

I standardized the column names, converted admission and discharge dates
into proper datetime values, checked missing values, removed **534
duplicate records**, and handled invalid negative billing values.

I then created a new **Length of Stay** metric from admission and
discharge dates to make the dataset more useful for operational
analysis.

With the data prepared, I moved from **"What does the data look like?"**
to **"What can the data tell us?"**

### 🔎 Questions explored

-   Which medical conditions account for the most patient records?
-   What does the patient age distribution look like?
-   How does average billing change over time?
-   Is there a visible relationship between age and billing?
-   How are patients distributed across insurance providers?
-   How do emergency admissions vary by month?
-   Which high-billing cases may need financial review?
-   Which emergency cases have abnormal test results?

------------------------------------------------------------------------

## 📊 Key Results

  Metric                                                Result
  ------------------------------------------ -----------------
  Original records                                  **55,500**
  Duplicate records removed                            **534**
  Final records                                     **54,966**
  Final fields                                          **16**
  Average patient age                          **51.54 years**
  High-billing records (\>90th percentile)           **5,497**
  Emergency + abnormal test results                  **6,038**

The analysis also examined monthly billing trends across **61 months**,
from May 2019 to May 2024.

------------------------------------------------------------------------

## 💡 Business Perspective

The project goes beyond charts by creating practical review segments.

**High-billing patients** were identified using the 90th percentile of
billing amount, creating a focused group for potential financial and
billing review.

**Emergency patients with abnormal test results** were also isolated to
create a review segment for hospital operations.

> These are analytical segments for review, not clinical diagnoses or
> medical recommendations.

------------------------------------------------------------------------

## 🛠️ Tools & Skills

**Python · Pandas · NumPy · Matplotlib · Jupyter Notebook**

-   Data Cleaning & Validation
-   Exploratory Data Analysis
-   Feature Engineering
-   Date-Time Analysis
-   GroupBy & Aggregation
-   Conditional Filtering
-   Quantile Analysis
-   Data Visualization
-   Healthcare & Billing Analytics

------------------------------------------------------------------------

## 🔄 Analysis Workflow

``` text
Raw Healthcare Data
        ↓
Data Cleaning & Validation
        ↓
Duplicate & Billing Correction
        ↓
Feature Engineering
        ↓
Exploratory Data Analysis
        ↓
Visualization
        ↓
Business-Focused Analysis
```

------------------------------------------------------------------------

## 📁 Repository

``` text
Healthcare-Data-Analysis/
│
├── Healthcare_Data_Analysis.ipynb
├── healthcare_dataset.csv
└── README.md
```

------------------------------------------------------------------------

## 🚀 What I Would Build Next

The next step would be to turn this analysis into an interactive **Power
BI healthcare dashboard**, combining patient demographics, admissions,
billing, insurance, and length-of-stay KPIs into one decision-support
view.

------------------------------------------------------------------------

### 👨‍💻 Project Focus

**Healthcare Data Analytics \| Python \| Pandas \| EDA \| Data Cleaning
\| Business Insights**
