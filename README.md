
#  Restaurant Analytics & Recommendation System

## Project Overview
This project focuses on analyzing global restaurant data to identify key factors that make restaurants “star performers” and to generate intelligent recommendations. By combining data inspection, cleaning, and exploratory data analysis (EDA), the project uncovers insights into restaurant ratings, cuisines, cost, delivery options, and geographic trends.  
The goal is to build a data-driven foundation for identifying top-performing restaurants and improving user experience on a B2C portal. Through Tableau visual analytics, decision-makers can better understand restaurant performance and customer preferences to guide business strategy and franchising decisions.

---

##  Overview about Dataset
The project uses two datasets:
- **data.csv** — contains restaurant attributes (19 columns)
- **Country-Code.csv** — provides country mapping for each restaurant  

The combined dataset includes restaurants across multiple countries, cities, and cuisines, along with details on ratings, cost, delivery availability, and customer votes.

---

##  Key Attributes Include
- **Restaurant ID:** Unique identifier for each restaurant  
- **Restaurant Name:** Name of the restaurant  
- **Country Code:** Country reference key  
- **City:** Location of the restaurant  
- **Cuisines:** Types of cuisines served  
- **Average Cost for Two:** Estimated dining cost  
- **Has Table Booking:** Indicates if table booking is available  
- **Has Online Delivery:** Indicates if delivery service is available  
- **Votes:** Number of customer votes  
- **Aggregate Rating:** Overall customer rating  
- **Rating Text:** Qualitative rating (e.g., Excellent, Good, Poor)  

---

## Objectives
- Perform data inspection and cleaning to ensure dataset quality  
- Explore the geographical and operational distribution of restaurants  
- Analyze cuisine trends, cost behavior, and delivery options  
- Study factors influencing restaurant ratings  
- Build an interactive Tableau dashboard to identify “Star Restaurants”  

---

## Workflow of Project

### **1. Initial Data Analysis**
- Checked structure, missing values, and duplicates  
- Removed duplicates and standardized categorical data  
- Merged `data.csv` with `Country-Code.csv` for comprehensive analysis  

### **2. Exploratory Data Analysis (EDA)**
- Identified cities with the highest and lowest number of restaurants  
- Analyzed franchises with national presence  
- Calculated ratios for table booking and online delivery  
- Compared votes and ratings for delivery vs. non-delivery restaurants  
- Determined top cuisines across cities and popular cuisines per country  
- Studied cost distribution and factors affecting restaurant ratings  

### **3. Dashboarding (Tableau)**
- Developed interactive Tableau dashboards for insight visualization  
- Created maps and charts for restaurant distribution and cuisine popularity  
- Displayed top-rated restaurants, average cost, and delivery availability  

---

##  Tools and Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **Visualization:** Tableau  
- **Notebook Environment:** Jupyter Notebook  
- **Version Control:** Git and GitHub  

---

##  Conclusion
The analysis provides insights into restaurant operations, customer preferences, and factors influencing ratings.  
Findings highlight:
- Popular cuisines and cost variations by city  
- The impact of delivery and table booking on customer satisfaction  
- Rating trends across geographic regions  

This project establishes a foundation for identifying “Star Restaurants” and supports the implementation of intelligent automation for restaurant recommendations. Future improvements may include machine learning models for automated rating prediction and personalized recommendations.

---













