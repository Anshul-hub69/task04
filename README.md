# 🚦 Task 04 - Traffic Accident Analysis

## 📌 Project Overview
This project is part of my internship at **SkillCraft Technology**.  
The goal was to analyze a **Traffic Accident Dataset** (from Kaggle) and explore the key factors influencing accidents through **Exploratory Data Analysis (EDA)** and visualizations.

---

## 📂 Dataset
The dataset contains detailed records of road accidents, including:
- **Date & Time** of accident  
- **Severity** of the accident  
- **Weather conditions**  
- **Road surface conditions**  
- **Light conditions**  
- **Geographical location** (latitude & longitude, if available)  

---

## ⚙️ Steps Performed
1. **Data Loading** – Imported the dataset into Pandas.  
2. **Data Cleaning** – Handled missing values, standardized column names.  
3. **Feature Engineering** – Extracted year, month, day, hour, day of week from datetime.  
4. **Exploratory Data Analysis (EDA)** –  
   - Accident counts by **severity**  
   - Accidents by **hour of day**  
   - Accidents by **day of week**  
   - Accidents by **month**  
   - Accidents by **weather** and **road conditions**  
5. **Geospatial Analysis (optional)** – Mapped accident hotspots using **Folium** if latitude & longitude were available.  

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas, NumPy** – data cleaning & preprocessing  
- **Matplotlib, Seaborn** – data visualization  
- **Folium** – accident hotspot mapping (if coordinates present)  
- **Google Colab** – implementation environment  

---

## 📊 Key Visualizations
- Accidents by **severity**  
- Accidents by **time of day (hourly trends)**  
- Accidents by **day of week**  
- Accidents by **month**  
- Accidents by **weather & road conditions**  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Task04-Traffic-Accident-Analysis.git
