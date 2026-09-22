---

# 📊 Python Project: EDA & Customer Cohort Analysis

This project analyzes an e‑commerce dataset using Python and pandas.  
The main goal is to explore customer behavior, calculate cohort retention, analyze revenue dynamics, and generate a simple HTML report suitable for a data analytics portfolio.

---

## 🧩 Business Question

**How do customer retention and revenue change across monthly cohorts, and which cohorts generate the highest long‑term value over time?**

### Additional Questions

- How many new customers joined each monthly cohort?  
- How does the number of new orders change month by month?  
- How does monthly revenue evolve over time?  
- How does customer retention change throughout the customer lifecycle?  
- Which cohorts generated the highest total and cumulative revenue?  
- Which payment methods are most frequently used overall and across cohorts?  
- Which acquisition channels are most effective throughout the customer lifecycle?  
- What additional analyses could help better understand customer behavior?

---

## 🛠 Tools & Technologies

- Python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- Google Colab  
- HTML report  
- GitHub  
- GitHub Pages  

---

## 📁 Project Structure

```text
python-eda-cohort-analysis/
|
├── README.md
├── data/
│   └── client_base.xlsx
|
├── notebooks/
│   └── retention_cohort_analysis_colab.ipynb
|
├── docs/
│   └── index.html
|
└── requirements.txt
```

---

## 📓 Notebook

This project was initially developed in **Google Colab**.  
The notebook includes the full analytical workflow:

- data loading  
- exploratory data analysis (EDA)  
- cohort creation  
- retention analysis  
- revenue analysis  
- acquisition channel analysis  
- payment method analysis  
- visualizations  
- HTML report generation  

**Link: Open in Google Colab**  
*(You will add the link here)*

---

## 📄 HTML Report

The project includes an exported HTML report — a static version of the analysis with charts and summary sections.  
If GitHub Pages is enabled for this repository, the report can be viewed online.

**Link: HTML Report — EDA & Customer Cohort Analysis**  
*(You will add the link here)*

---

## 🔍 Analysis Steps

- Loaded and validated customer and order datasets  
- Checked dataset structure and missing values  
- Created *Cohort Month* and *Cohort Index* columns  
- Calculated cohort sizes by registration month  
- Analyzed monthly revenue and order volume  
- Built customer retention tables  
- Calculated retention rates by cohort  
- Analyzed cohort revenue and cumulative revenue  
- Built acquisition channel tables  
- Analyzed acquisition channels across cohorts  
- Built payment method tables  
- Analyzed payment methods across cohorts  
- Summarized key insights and defined next steps  

---

## 📌 Key Insights

Based on the 2005 dataset:

- **July** had the largest cohort with **452 new customers**.  
- Monthly revenue peaked in **August** at **$179,603**.  
- August also had the highest number of orders — **1,409**.  
- Average retention after the first month is **~54%** (range: 49–60%), followed by a sharp decline — suggesting the need for a loyalty program.  
- The **July cohort** generated the highest total revenue — **$259,783**.  
- Main acquisition drivers: **Instagram, Facebook, Google Ads**.  
- Main trust & retention channels: **Referral and Email**.  
- Card payments dominate overall; mobile payments (Apple Pay, Google Pay) show strong growth in July — worth further development.

---

## 🔧 Recommendations & Next Steps

### Recommendations

The business should shift focus from mass acquisition to **retention and long‑term customer value**.  
Investing in high‑retention channels such as **Google Ads** and **Email** is key to sustainable growth.

### Next Steps

- Analyze why the July 2025 cohort performed strongest in size and revenue.  
- Compare retention rates across acquisition channels.  
- Check whether payment method or order status affects revenue and retention.  
- Add segmentation by age, gender, city, or acquisition channel.  
- Build a Tableau or Power BI dashboard based on cohort analysis results.

---

## 🔒 Data Privacy Note

The dataset used in this repository is **synthetic** and prepared for educational purposes.  
It does not contain real customer information.

---

## 📘 How to Use This Repository

1. Open the notebook in Google Colab.  
2. Upload `client_base.xlsx` or connect your Google Drive.  
3. Run all notebook cells.  
4. Export results as `.ipynb` or HTML if needed.

---

## 🎯 Portfolio Value

This project demonstrates:

- Python data analysis fundamentals  
- EDA workflow  
- Cohort analysis logic  
- Customer retention analysis  
- Revenue analysis  
- Acquisition channel analysis  
- Payment method analysis  
- Data visualization  
- Ability to present results as a polished portfolio project  

---

Марія, цей README.md вже готовий для GitHub — структурований, чистий, професійний і повністю англійською.  
Хочеш — можу зробити коротку версію для рекрутерів або додати GitHub‑бейджі.
