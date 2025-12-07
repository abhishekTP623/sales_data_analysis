
# 📊 Retail Sales Analysis – Exploratory Data Analysis (EDA)

## 📌 Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a retail sales dataset to understand sales trends, customer patterns, high-performing products, and revenue insights.
The analysis was done in **Google Colab**, and includes cleaning, preprocessing, visualization, and extracting business insights useful for decision-making.

---

## 📂 Dataset

* **Source:** Retail Sales Dataset (Kaggle Export)
* **Format:** CSV
* **Key Columns:**

  * `Date` – Transaction date
  * `Age` – Customer age
  * `Gender`
  * `Category` – Product category
  * `Quantity`
  * `Price`
  * `Total Amount` – Revenue
* **Preprocessing Performed:**

  * Converted `Date` column to datetime
  * Handled missing or incorrect values
  * Created new columns like:

    * Month
    * Day of Week
    * Age Group
  * Removed unwanted warnings & fixed path issues

---

## 🧪 Project Workflow

### ✔ 1. Data Cleaning

* Checked missing values
* Converted columns to correct data types
* Fixed `unicodeescape` path error
* Standardized categories

### ✔ 2. Exploratory Data Analysis

* Sales trend by **Month**
* Revenue by **Day of Week**
* Top-selling **Product Categories**
* Age group-wise revenue contribution
* Gender-wise purchase patterns

### ✔ 3. Visualizations

* Monthly revenue line plot
* Category-wise bar charts
* Day-of-week revenue comparison
* Customer age group distribution
* Sales heatmaps and countplots

---

## 📈 Key Insights

Some major business insights from the dataset:

* **Sales peak during certain months**, indicating seasonal spikes
* **Weekends show higher revenue** compared to weekdays
* **Electronics/Clothing categories perform the best**
* **Young adults contribute significantly to total sales**
* **Females show slightly higher avg spending (depending on dataset)**

(You can edit these based on your actual results.)

---

## 🛠 Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

Install all dependencies using:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## ▶ How to Run the Project

1. Download or clone this repository.
2. Place the dataset in the same directory or update the file path.
3. Open the notebook in Google Colab or Jupyter.
4. Run all cells in order to reproduce the EDA and visualizations.

---

## 🚀 Future Improvements

* Add **Forecasting models** (ARIMA, Prophet, LSTM)
* Build an **interactive dashboard** (Power BI / Plotly Dash)
* Customer segmentation using ML

---

## 👨‍💻 Author

**Abhishek T**


