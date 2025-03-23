# 🚖 Chicago Taxi Data Analysis  

## 📌 Project Overview  
This project focuses on **exploratory data analysis (EDA) and hypothesis testing** using Python. It analyzes taxi trip data in Chicago to uncover insights about company performance, ride demand by location, and factors affecting trip duration.  

## 📂 Datasets Used  
- **Taxi Company Data** (`project_sql_result_01.csv`):  
  - `company_name`: Name of the taxi company.  
  - `trips_amount`: Number of trips completed on November 15-16, 2017.  

- **Dropoff Location Data** (`project_sql_result_04.csv`):  
  - `dropoff_location_name`: Chicago neighborhoods where trips ended.  
  - `average_trips`: Average number of trips ending in each neighborhood (November 2017).  

- **Weather & Trip Duration Data** (`project_sql_result_07.csv`):  
  - `start_ts`: Pickup timestamp.  
  - `weather_conditions`: Weather at trip start.  
  - `duration_seconds`: Trip duration in seconds.  

## 🚀 Key Tasks & Methodology  
### **1️⃣ Exploratory Data Analysis (EDA)**
- Imported and cleaned datasets.  
- Ensured correct data types.  
- Identified **top 10 neighborhoods** with the highest drop-offs.  
- Created **visualizations**:  
  - **Taxi companies vs. number of trips.**  
  - **Top 10 neighborhoods by ride completions.**  

### **2️⃣ Hypothesis Testing**
- Tested: *"The average trip duration from the Loop to O’Hare Airport changes on rainy Saturdays."*  
- Applied statistical hypothesis testing to determine **if weather significantly impacts trip time.**  

## 📊 Key Findings  
- Identified the **most popular taxi companies** in Chicago.  
- Determined **which neighborhoods had the highest ride demand**.  
- Analyzed the impact of **weather on trip duration** using statistical tests.  

## 🛠 Technologies Used  
- **Python** (pandas, NumPy, SciPy, Matplotlib, Seaborn)  
- **Jupyter Notebook**  
- **SQL** (Data Extraction)  

## 🏁 How to Use  
1. Clone the repository:  
   ```bash
   git clone https://github.com/inorja12/Sprint_8.git
