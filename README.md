# **Bank Marketing Campaign Analysis and Prediction Model**  

## **Overview**
This project analyzes a **Portuguese banking institution's direct marketing campaigns** to predict whether a client will **subscribe to a term deposit**. The dataset includes **41,188 records** from phone-based marketing campaigns, capturing **customer attributes, campaign details, and economic indicators**.

📄 **[View the Jupyter Notebook](./Bank%20Marketing%20Analysis_Notebook.ipynb)**  

## **Dataset**
- **Source**: [UCI Machine Learning Repository - Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)  
- **Size**: 41,188 observations, 20 input features + target  
- **Task**: Binary Classification (`yes` = client subscribed, `no` = client did not subscribe)  

### **Key Features:**
1. **Client Demographics**: Age, job, education, marital status, loans  
2. **Campaign Details**: Contact type, number of contacts, previous outcomes  
3. **Economic Indicators**: Consumer price index, confidence index, Euribor 3-month rate  

---

## **Project Structure**
This project consists of **two components**:  
**Jupyter Notebook for Machine Learning Modeling**  
**Power BI Dashboard for Interactive Insights**  

---

## **Key Analysis & Findings**
### **1️. Model Performance (RF vs. XGB)**
- **Random Forest (RF)** vs. **XGBoost (XGB)**  
- Success rate and efficiency rate comparison  
- **RF outperforms slightly in efficiency**, while both perform similarly in success rate  

### **2️. Feature Importance Analysis**
- **Key Predictors of Subscription Success**
- Categorized as:
  - **Market Conditions** (External, non-controllable)  
  - **Campaign Execution** (Controllable strategies)  
  - **Customer Attributes** (Targeting criteria)  
- **Most Predictive Feature**: **Euro Interbank Rate**, indicating economic sensitivity  

### **3️. Decile Analysis**
- **Segmentation of customers** into **10 deciles** based on likelihood to subscribe  
- **Top 20% of customers capture 66.5% of campaign successes**  
- Demonstrates strong model discrimination and actionable targeting insights  

---

## **How to Use**
### **Explore the Power BI Dashboard**
- **[Click here to access the interactive report](https://app.powerbi.com/links/5vPja9zegt?ctid=80f23f4a-91a4-4566-8db1-3bcabb21d1cb&pbi_source=linkShare)**
- Navigate through:
  - **Model Performance**
  - **Feature Importance**
  - **Decile Analysis**

### **Run the Modeling Notebook**
- **[Click to open the Jupyter Notebook](./Bank%20Marketing%20Analysis_Notebook.ipynb)**
- Covers:
  - Data preprocessing
  - Model training (Random Forest & XGBoost)
  - Feature importance extraction
  - Decile segmentation analysis

---

## ** Author**
**[Relwan Onikoyi](https://www.linkedin.com/in/relwan-onikoyi/)**  
📧 ronikoy@ncsu.edu  
🔗 [GitHub Profile](https://github.com/Ronikoyi)

---

### **Contributions**
Feel free to contribute, open issues, or suggest improvements!

---
