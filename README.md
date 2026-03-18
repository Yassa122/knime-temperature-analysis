# 🌍 Global Temperature Analysis using KNIME

This project presents a data analytics workflow built using **KNIME Analytics Platform** to analyze global and city temperature datasets.

## 📌 Objective

The goal of this project is to:
- Analyze temperature trends across countries and years
- Compare city-level temperatures with global averages
- Identify countries with the highest deviations from global temperature
- Visualize temperature distributions and trends

---

## 🛠️ Tools Used

- KNIME Analytics Platform
- CSV datasets (city & global temperature data)

---

## 📊 Workflow Overview

The workflow is divided into multiple steps corresponding to the assignment questions:

### Q1 – Average Temperature per Country
- Used **GroupBy** node
- Calculated mean temperature for each country

### Q2 – Temperature Categorization
- Used **Numeric Binner**
- Classified temperatures into Low / Mid / High

### Q3 – Difference from Global Temperature
- Filtered datasets by year
- Joined city and global datasets using **Joiner**
- Calculated difference using **Math Formula**

### Q4 – Top 5 Countries with Largest Difference
- Grouped by country
- Calculated mean difference
- Sorted results
- Used **Top k Row Filter** to extract top 5

### Q5 – Histogram of Global Temperatures
- Used **Histogram node**
- Visualized distribution of global temperatures

### Q6 – City vs Global Temperature Comparison
- Selected a city using **Row Filter**
- Joined with global data
- Used **Line Plot** to compare trends over time

---

## 📷 Results

### Histogram (Global Temperature Distribution)
![Histogram](Q5_Histogram_Global_Temperature.png)

### City vs Global Temperature Trend
![Line Plot](Q6_City_vs_Global_Temperature.png)

---

## 📁 Files Included

- `Yassa Ashraf - Test.knwf` → KNIME workflow file
- `Q5_Histogram_Global_Temperature.png`
- `Q6_City_vs_Global_Temperature.png`

---

## 🚀 How to Run

1. Download and install **KNIME Analytics Platform**
2. Import the `.knwf` file:
   - File → Import KNIME Workflow
3. Execute all nodes
4. Open the views for visualization nodes

---

## 👤 Author

**Yassa Ashraf**  
Software Engineer  

---

## 📬 Notes

This project was completed as part of a technical assessment.  
All workflows are designed to be clear, modular, and easy to understand.