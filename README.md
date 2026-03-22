# 🏡 Airbnb Data Analysis Project

## 📌 Overview

This project focuses on analyzing an Airbnb dataset to extract meaningful insights about listing prices, room types, neighborhood distributions, and review trends over time.

Using Python libraries such as **Pandas, Matplotlib, and Seaborn**, the dataset is cleaned, processed, and visualized.

---

## 📂 Dataset

* File: `Airbnb_Open_Data.csv`
* Contains information about:

  * Listing names
  * Host names
  * Prices
  * Service fees
  * Room types
  * Neighborhood groups
  * Reviews and dates

---

## ⚙️ Data Cleaning Steps

The dataset required preprocessing before analysis:

* Converted `last review` column to datetime format
* Handled missing values:

  * Filled `reviews per month` with 0
  * Replaced missing dates with the earliest review date
* Removed rows with missing `NAME` and `host name`
* Cleaned `price` and `service fee` columns:

  * Removed `$` and `,`
  * Converted values to float
* Removed duplicate records

---

## 📊 Exploratory Data Analysis (EDA)

### 1. Price Distribution

* Histogram with KDE curve
* Shows how listing prices are distributed

### 2. Room Type Distribution

* Count plot of different room types
* Identifies the most common listing types

### 3. Neighborhood Analysis

* Count plot of listings by neighborhood group
* Highlights areas with the highest activity

### 4. Price vs Room Type

* Boxplot comparing prices across room types
* Shows median, spread, and outliers

### 5. Reviews Over Time

* Line chart grouped by month
* Displays trends in review activity over time

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn

---

## 📈 Key Insights

* Price distribution is highly skewed (many low-price listings, few expensive ones)
* Certain room types dominate the market
* Some neighborhoods have significantly more listings
* Review activity varies over time, showing trends and seasonality

---

## 🚀 How to Run

1. Clone the repository
2. Install required libraries:

   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Update the dataset path:

   ```python
   file_path = "your_path/Airbnb_Open_Data.csv"
   ```
4. Run the script

---

## 📌 Future Improvements

* Add interactive dashboards (Plotly / Power BI)
* Apply machine learning for price prediction
* Perform deeper statistical analysis

---

## 👨‍💻 Author

Canberk Yılmaz
Aspiring Data Analyst & AI Enthusiast

---
