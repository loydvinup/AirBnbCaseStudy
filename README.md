# Airbnb Data Analysis - New York City  

## Overview  
This project explores **Airbnb listings in New York City**, analyzing **pricing trends, neighborhood popularity, room types, and host activity**. The dataset contains nearly **49,000 listings** with attributes like **price, location, availability, and reviews**.  

## Dataset  
📂 **File:** `Airbnb_NYC.csv`  
📊 **Rows:** ~49,000  
🔢 **Columns:** 16  

### **Key Features:**  
- **neighbourhood_group** – Boroughs (Manhattan, Brooklyn, etc.)  
- **neighbourhood** – Specific neighborhood (Williamsburg, Harlem, etc.)  
- **room_type** – Entire home/apt, private/shared room  
- **price** – Price per night ($USD)  
- **minimum_nights** – Minimum stay required  
- **availability_365** – Number of days available per year  
- **number_of_reviews** – Total reviews for a listing  
- **reviews_per_month** – Frequency of reviews  

---

## **Project Workflow**  

### **1️⃣ Data Cleaning & Preprocessing**  
- Renames columns for clarity  
- Handles **missing values** (`listing_name`, `reviews_per_month`)  
- Removes **duplicates** and unnecessary columns  
- Detects and removes **outliers in price** using the **IQR method**  

### **2️⃣ Exploratory Data Analysis (EDA)**  
- **Price Distribution** – Histogram & Boxplot of nightly prices  
- **Listings per Neighborhood Group** – Most listings in Manhattan & Brooklyn  
- **Average Price by Neighborhood** – Top 10 most expensive areas  
- **Room Type Analysis** – Price comparison of Entire Home vs. Private Room  
- **Most Active Hosts** – Hosts with the highest number of listings  
- **Review Analysis** – Listings with the most reviews  

### **3️⃣ Correlation Analysis & Visualization**  
- **Heatmap** – Identifies relationships between price, availability, and reviews  
- **Pair plot** – Shows interactions between numerical variables  
- **Summary statistics** – Mean, median, and quartiles of price per room type  

---

## **Technologies Used**  
🚀 **Python, Pandas, NumPy, Matplotlib, Seaborn**  

## **Results & Insights**  
- **Manhattan has the highest prices**, followed by Brooklyn  
- **Entire home/apt listings dominate in expensive neighborhoods**  
- **Review frequency is higher for lower-cost listings**  
- **Outlier detection helps in removing extreme prices**  

## **Future Improvements**  
🔹 Predict pricing using **Machine Learning**  
🔹 Analyze trends over time with **time-series forecasting**  
🔹 Identify fraudulent listings using **anomaly detection**  
