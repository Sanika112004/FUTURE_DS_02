# FUTURE_DS_02
Social Media Ad Performance Analysis – Task 2

# Social Media Ad Performance Analysis – Task 2

## 📌 Dataset Overview
The dataset used in this project is sourced from Kaggle, titled **"Sales Conversion Optimization"** by **GOKAGGLERS**.  
It represents marketing and conversion data from an anonymous organization’s social media advertising campaigns on Facebook.

The dataset consists of **1,143 records** with **11 attributes**, capturing information related to ad performance, audience demographics, and conversions.

---

## 📂 Dataset Description
The dataset contains the following columns:

- **ad_id**: Unique identifier for each advertisement  
- **xyzcampaignid**: Campaign ID assigned by the organization  
- **fbcampaignid**: Facebook’s internal campaign tracking ID  
- **age**: Age group of the audience exposed to the ad  
- **gender**: Gender of the targeted audience  
- **interest**: Interest category code based on Facebook public profile data  
- **Impressions**: Number of times the ad was displayed  
- **Clicks**: Number of clicks received by the ad  
- **Spent**: Advertising cost incurred for the ad  
- **Total_Conversion**: Number of users who showed interest after viewing the ad  
- **Approved_Conversion**: Number of users who completed a purchase  

---

## 🛠 Tools Used
- **Data Cleaning & Analysis**: Microsoft Excel  
- **Data Visualization & Dashboarding**: Microsoft Power BI  

---

## 🧹 Data Cleaning & Preparation
During the data exploration phase, it was observed that there were **no missing or invalid values** in the dataset.  
However, a logical inconsistency was identified in **204 records**, where ads showed **zero clicks but non-zero conversions**, which is practically impossible.

To ensure data accuracy and reliability, these inconsistent records were removed.  
After cleaning, the final dataset contained **939 valid entries** for analysis.

---

## ⚙ Feature Engineering & KPI Creation
To evaluate campaign effectiveness, several performance metrics were derived from the existing data:

- **CPM (Cost per Mille)**  
  Measures the cost incurred for every 1,000 ad impressions.

- **CPC (Cost per Click)**  
  Indicates the average cost paid for each ad click.

- **CTR (Click-Through Rate)**  
  Represents the percentage of users who clicked on the ad after viewing it.

- **CPA (Cost per Acquisition)**  
  Calculates the cost required to acquire a single customer through advertising.

These KPIs were essential for understanding campaign efficiency, audience behavior, and overall return on ad spend.

---

## 🎯 Project Purpose
This project demonstrates how businesses can analyze social media advertising data to optimize campaign performance, improve conversion rates, and make data-driven marketing decisions using Power BI.

---

## 🎓 Internship Details
- Internship Program: Data Science & Analytics  
- Organization: Future Interns  
- Task: Social Media Campaign Performance Tracker (Task 2)  
- Track Code: DS  

---

## 📌 Disclaimer
This project is created strictly for **educational and internship purposes**.  
The dataset is publicly available on Kaggle and is used here for learning, analysis, and visualization.

