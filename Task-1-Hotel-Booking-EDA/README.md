# Task 1- Python & Pandas EDA
# Hotel Booking Demand – Exploratory Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Hotel Booking Demand dataset using **Python, Pandas, Matplotlib, and Seaborn**.

The objective is to understand the structure, quality, distributions, relationships, and important patterns present in hotel booking data.

## 📊 Dataset

The dataset used for this project is the **Hotel Booking Demand Dataset**, containing hotel reservation records for both City Hotel and Resort Hotel.

**Dataset source:**
Hotel Booking Demand – Kaggle
https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand

The dataset contains information related to:

* Hotel type
* Booking status
* Lead time
* Arrival date
* Length of stay
* Number of guests
* Meal type
* Market segment
* Distribution channel
* Room types
* Deposit type
* Customer type
* Average Daily Rate (ADR)
* Special requests
* Reservation status

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🔍 EDA Process

The following steps were performed during the analysis:

1. Imported required Python libraries
2. Loaded the dataset
3. Performed sanity and structural checks
4. Examined dataset shape and data types
5. Analyzed missing values
6. Identified duplicate records
7. Checked categorical values for undefined/garbage values
8. Generated descriptive statistics for numerical variables
9. Analyzed categorical variable frequencies
10. Visualized numerical distributions using histograms
11. Identified potential outliers using box plots
12. Studied relationships using scatter plots
13. Analyzed correlations using a correlation heatmap
14. Performed appropriate missing-value treatment
15. Removed exact duplicate records
16. Performed appropriate outlier treatment
17. Created business-oriented visualizations
18. Summarized the key findings from the analysis

## 📈 Visualizations

The analysis includes visualizations answering questions such as:

* Which hotel type receives more bookings?
* Which months have the highest booking volume?
* What is the distribution of booking lead time?
* How does ADR vary between hotel types?
* Is there a relationship between lead time and ADR?
* Which numerical variables have stronger correlations?

## 🎯 Key Objectives

The main objectives of this project are to:

* Understand the characteristics of hotel bookings
* Identify data-quality issues
* Understand booking distributions and patterns
* Analyze relationships between important variables
* Identify unusual observations and outliers
* Generate meaningful insights from the data

## 📁 Project Structure

```text
Python_Pandas_EDA/
│
├── hotel_bookings.csv
├── Hotel_Booking_EDA.ipynb
└── README.md
```

## 🚀 How to Run

1. Clone or download this repository.
2. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Open:

```text
Hotel_Booking_EDA.ipynb
```

5. Run the notebook cells sequentially.

## 📌 Conclusion

The project demonstrates a complete exploratory data analysis workflow using Python and Pandas, covering data inspection, data-quality analysis, descriptive statistics, visualization, relationship analysis, and interpretation of important patterns in hotel booking data.
