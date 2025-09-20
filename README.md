# 🍴 Zomato Data Analysis  

This project explores and analyzes the **Zomato dataset** to uncover insights into restaurant trends, pricing, ratings, and customer preferences.  

The analysis is focused on **cleaning the dataset, preparing it for analysis, and visualizing patterns** to derive meaningful business insights.  

---

## 📊 Project Overview  

- Cleaned and preprocessed raw dataset  
- Explored relationships between **cuisines, location, price ranges, and ratings**  
- Performed **exploratory data analysis (EDA)**  
- Visualized insights using **Matplotlib** and **Seaborn**  
- Highlighted trends that help understand **customer behavior and market dynamics**  

---

## 🧹 Data Cleaning & Preparation  

The raw dataset contained **duplicates, missing values, and irrelevant columns**. I performed the following steps:  

1. **Handled Missing Values**  
   - Replaced null values in categorical columns (like cuisine type) with `"Unknown"`.  
   - Removed rows with completely missing critical information (like restaurant name or rating).  

2. **Removed Duplicates**  
   - Dropped duplicate restaurant entries based on restaurant ID and name.  

3. **Standardized Columns**  
   - Cleaned inconsistent entries (e.g., `"North Indian, Chinese"` vs `"Chinese, North Indian"`).  
   - Converted textual numeric columns (like cost) into integers for analysis.  

4. **Feature Selection**  
   - Dropped irrelevant/unnecessary columns (like URLs, phone numbers, and identifiers not useful for analysis).  

5. **Data Transformation**  
   - Created new categorical bins for price ranges and ratings.  
   - Converted string ratings like `"4.5/5"` into numeric values.  

---

## 🔧 Technologies Used  

- **Python**  
- **Pandas** (Data Cleaning & Manipulation)  
- **Matplotlib / Seaborn** (Data Visualization)  
- **Jupyter Notebook**  

---

## 📈 Key Insights  

- The most popular cuisines across major locations  
- How price range impacts average restaurant ratings  
- Voting & rating distribution across restaurant types  
- Correlation between online order availability and customer satisfaction  

---

## 📧 Contact
📧 Email: hafsazahoor63@gmail.com 
🔗 LinkedIn: https://www.linkedin.com/in/hafsa-zahoor-6a4b01373?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app
