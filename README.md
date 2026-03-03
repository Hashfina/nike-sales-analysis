# Nike Sales Analysis

This project analyzes a Nike sales dataset to turn raw, uncleaned data into clear business insights using Python, Pandas, Matplotlib, and Seaborn.

---

## 📌 Project Overview

The goal of this project is to explore Nike sales performance across products, regions, and time, and to identify patterns that can support data‑driven decisions in marketing, inventory, and pricing.

Main objectives:
- Clean and prepare the raw Nike sales data.
- Explore sales trends over time and across key dimensions.
- Visualize important patterns using clear, colourful charts.
- Summarize the main insights and recommendations.

---

## 🧾 Dataset

The project uses a synthetic Nike sales dataset containing transactional‑level information.  
Typical columns include (example list, adjust to your file):

- `Order Date` / `Invoice Date`
- `Region` / `Country`
- `Product` / `Category`
- `Quantity`
- `Unit Price`
- `Revenue` or `Total Sales`
- `Channel` (Online / Retail)

Files in this repository:
- `data/Nike_Sales_Uncleaned.csv` – Raw dataset with original values.
- `data/Nike_Sales_Cleaned.csv` – Cleaned dataset used for analysis.

> Update these names if your CSV files are slightly different.

---

## 🛠️ Tools and Libraries

The analysis was done in Jupyter Notebook with the following libraries:

- **Python**  
- **Pandas** – data loading, cleaning, transformation  
- **NumPy** – numerical operations  
- **Matplotlib** – base plotting  
- **Seaborn** – advanced and colourful visualizations  

---

## 📁 Project Structure

```text
nike-sales-analysis/
│
├── data/
│   ├── Nike_Sales_Uncleaned.csv
│   └── Nike_Sales_Cleaned.csv
│
├── notebooks/
│   └── Nike_Sales_EDA_and_Data_Visualisations.ipynb
│
├── README.md
└── (other files if any)

