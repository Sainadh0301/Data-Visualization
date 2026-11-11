# 📊 Data Visualization

## 📌 Project Overview

This project focuses on analyzing and visualizing taxi trip data using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

The project uses the built-in Seaborn Taxis dataset to explore taxi trips, analyze fare amounts, understand payment methods, and identify relationships between different numerical variables through visualizations.

## 🎯 Project Objectives

- Load and explore the Taxis dataset.
- Identify and handle missing values.
- Perform data cleaning using Pandas.
- Create different types of visualizations.
- Analyze taxi fares, trip distances, tips, and payment methods.
- Understand relationships between numerical variables.

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Dataset

**Dataset Name:** Taxis Dataset

The dataset is loaded directly from Seaborn.

```python
import seaborn as sns

df = sns.load_dataset("taxis")

print(df.head())
```

### Dataset Features

- Pickup
- Dropoff
- Passengers
- Distance
- Fare
- Tip
- Tolls
- Total
- Payment
- Pickup Borough
- Pickup Zone

## 🔍 Project Workflow

### 1. Loading the Dataset

Loaded the built-in Taxis dataset using Seaborn.

### 2. Handling Missing Values

- Checked missing values.
- Identified columns containing missing data.
- Filled numerical missing values using median.
- Filled categorical missing values using mode.
- Removed rows with missing pickup timestamps.

### 3. Data Visualization Using Matplotlib

Created the following visualizations:

| Visualization | Description                             |
| ------------- | --------------------------------------- |
| Line Chart    | Fare over time                          |
| Bar Chart     | Total fare by pickup borough            |
| Pie Chart     | Distribution of trips by payment method |
| Histogram     | Distribution of trip distance           |
| Box Plot      | Tip distribution by pickup borough      |

### 4. Data Visualization Using Seaborn

Created the following visualizations:

| Visualization | Description                                        |
| ------------- | -------------------------------------------------- |
| Count Plot    | Number of trips by pickup borough                  |
| Scatter Plot  | Relationship between distance and fare             |
| Heatmap       | Correlation between numerical variables            |
| Pair Plot     | Pairwise relationships between numerical variables |
| Violin Plot   | Fare distribution by payment method                |

## 📈 Key Learnings

- Understanding data visualization techniques.
- Working with real-world datasets.
- Handling missing values.
- Creating charts using Matplotlib and Seaborn.
- Analyzing numerical and categorical data.
- Understanding correlations and data distributions.



## 📁 Project Structure

```text
Data-Visualization/
│
├── Data_Visualization.ipynb
├── README.md
└── images/
    ├── Fare_over_time.png
    ├── Total_fare_bypickup_borough.png
    ├── Trips_by_paymentmethod.png
    ├── Taxi_trip_distance.png
    ├── Tip_dis_bypickup_borough.png
    ├── Numof_trips_bypickup_borough.png
    ├── Dis_btw_dis&fare.png
    ├── Heatmap.png
    ├── pickup_zone.png
    └── Fare_dist_by_paymentmethod.png
```

## 👨‍💻 Author

**SAI NADH&#x20;**

Python | Data Analytics | Data Visualization

## ⭐ Conclusion

This project demonstrates how Python can be used to explore, clean, analyze, and visualize real-world taxi trip data. Using Matplotlib and Seaborn, different visualizations help understand fare patterns, trip distances, payment methods, and relationships between variables.

---

⭐ If you find this project useful, please give this repository a star!
