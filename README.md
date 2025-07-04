# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: RUQSAR FIRDOUS

*INTERN ID*: CT04DG2858

*DOMAIN*: DATA ANALYST

*DURATION* : 4 WEEKS

*MENTOR*: NEELA SANTOSH



## ✅ 📄 `README.md` — **Flight Delays Analysis and Prediction**

---

# ✈️ Flight Delays Analysis and Prediction — 2015 US Flights

## 📌 Overview

This project demonstrates how to handle and analyze **large real-world datasets** using Python’s scalable data science tools. The dataset used is the **2015 US Flight Delays and Cancellations**, which contains records of millions of commercial flights across the United States, with detailed information about airlines, airports, departure and arrival delays, and other operational metrics.

The goal of this project was to **merge multiple data sources**, perform thorough **data cleaning**, conduct clear **exploratory data analysis (EDA)**, and build a simple yet functional **classification model** to predict whether a flight will be delayed by more than 15 minutes.

---

## ⚙️ Tools Used

* **Google Colab:** for scalable, cloud-based Python development.
* **pandas:** for data manipulation and merging multiple CSVs.
* **seaborn & matplotlib:** for creating meaningful visualizations.
* **scikit-learn:** for feature encoding, splitting data, training a Logistic Regression model, and evaluating predictions.

---

## 📚 Dataset Details

* **Flights:** Detailed information about each flight, including airline code, origin and destination airports, scheduled departure and arrival times, and recorded delays.
* **Airlines:** Mapping of airline codes to their full names.
* **Airports:** Details about airports including city and state.

---

## ✅ Steps Completed

### 1️⃣ Data Loading and Merging

* Loaded three large CSV files: `flights.csv`, `airlines.csv`, and `airports.csv`.
* Merged `flights` with `airlines` to map airline codes to airline names.
* Merged the combined dataset with `airports` to enrich each flight with its origin city and state.

---

### 2️⃣ Data Cleaning and Preparation

* Checked for missing values after joins.
* Filled missing airline names, cities, and states with default labels like **"Unknown Airline"** or **"Unknown City"** to prevent nulls during modeling.
* Created a new target column, **`DELAYED`**, where any flight with a departure delay greater than 15 minutes was labeled as delayed (`1`), and otherwise labeled as on time (`0`).

---

### 3️⃣ Exploratory Data Analysis (EDA)

Used **seaborn** and **matplotlib** to create:

* Distribution plots of delayed vs. on-time flights.
* Bar plots showing average departure and arrival delays by airline.
* Count plots for the top origin cities and states with the most flights.
* Comparison of states with the highest numbers of delays.

These plots provided clear insights about which airlines or states typically experience higher delays and how delays are distributed across the country.

---

### 4️⃣ Feature Encoding and Model Preparation

* Selected categorical features like **airline code, origin city, and state**.
* Encoded them using `pd.get_dummies` for compatibility with scikit-learn.
* Split the data into training and testing sets (80% train, 20% test).

---

### 5️⃣ Modeling

* Trained a simple **Logistic Regression** model to predict whether a flight would be delayed.
* Evaluated the model using **accuracy score**, **confusion matrix**, and **classification report**.
* The results show how even a simple model can provide a reasonable baseline for predicting delays based on origin and airline information.

---

### 6️⃣ Scalability Demonstrated

This task used **pandas** and **scikit-learn**, both of which can handle large datasets when combined with Colab’s cloud resources.
The same project can be scaled further using **PySpark or Dask** if the dataset size grows beyond single-machine memory.

---

## 📝 Conclusion

Through this project, I demonstrated my ability to:

* Work with **multiple large files** and perform joins.
* Clean and prepare complex real-world data.
* Use visual analysis to find trends in flight delays.
* Build a simple ML model with clear input-output.
* Write readable, clean Python code that is easy to maintain.

The project reflects practical skills needed in any **big data** or **data science** internship — from raw data to final predictions and clear, documented results.

---

## 🚀 Future Work

To extend this project, the following improvements can be made:

* Use **PySpark** to process truly massive datasets.
* Engineer more features: weather, seasonal patterns, airport traffic.
* Train more advanced models like **Random Forest**, **XGBoost**, or even time-series models for delay forecasting.
* Build a simple **web app** to demonstrate predictions in real-time.

---

## 📞 Contact

**Author:** \[RUQSAR FIRDOUS]
**Tools:** Python, pandas, scikit-learn, seaborn, matplotlib, Google Colab
**Status:** ✅ Completed basic version, open for improvements!

---

**Feel free to fork, star ⭐️, and suggest ideas!**
Thank you for checking out this project — happy analyzing! ✈️📊✨

---

If you want, I can also wrap this in a **Markdown file** for you — just say **“Yes, generate `.md`!”** and I’ll prepare it as a file. 🚀
