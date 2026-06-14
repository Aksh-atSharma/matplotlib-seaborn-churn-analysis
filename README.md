# matplotlib-seaborn-churn-analysis

## 📊 Customer Churn Analysis using Python, Matplotlib & Seaborn

Welcome to my **Customer Churn Analysis** project, where I’ve used Python and its visualization libraries to analyze telco customer churn behavior. This project covers **data cleaning, preprocessing, exploratory data analysis (EDA), and rich visual storytelling** using `matplotlib` and `seaborn`.

---

### 🔍 Project Overview

In this project, I explored a telecom dataset to understand **which customers are churning and why**. Key steps included:

* Cleaning and standardizing mixed-format data
* Creating custom plots to interpret customer behavior
* Performing visual analysis on demographics, services, contracts, and payments
* Interpreting customer churn patterns with count plots, pie charts, heatmaps, and more

---

### 🧰 Tools & Libraries Used

* Python 🐍
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* Pandas
* NumPy
* Google Colab

---

### 🧼 Data Cleaning 

* Converted `"Yes"/"No"` and `1/0` columns to consistent Boolean values
* Handled missing or blank values in `TotalCharges` and other columns
* Created new labeled columns (e.g., `Senior_label`) for better readability
* Dropped/merged unnecessary duplicates and temporary columns

---

### 📈 Visualizations Created

#### ✅ **Matplotlib**

* **Line Plot** – Sales over days of the week
* **Bar Chart** – Sales per product
* **Pie Chart** – Regional sales distribution
* **Histogram** – Student marks distribution
* **Scatter Plot** – Hours studied vs marks
* **Subplots** – Combining multiple plot types in one figure

#### ✅ **Seaborn**

* **Histplot** – Distribution of features like `not_distracted`
* **Jointplot** – Relationship between speeding and alcohol involvement
* **KDE, Pairplot, Rugplot** – Exploratory multivariate analysis
* **Box, Violin, Strip, Swarm Plots** – Tip distribution by day and gender
* **Heatmap** – Correlation matrix of crash data
* **Clustermap** – Monthly passenger flow pattern
* **Countplots** – Churn rate by:

  * Gender
  * Senior citizenship
  * Services used (Phone, Internet, Security, Backup, etc.)
  * Contract type
  * Payment method

---

### 📊 Key Insights from Churn Analysis

* 🔹 **73%** of customers did **not churn**, while **27%** did.
* 🔹 Customers on **month-to-month** contracts are **more likely to churn**.
* 🔹 **Electronic check** payment users have the **highest churn rate**.
* 🔹 Churn is significantly higher among:

  * Customers **without tech support**
  * Customers **without online backup**
  * Customers **using fiber optic internet**
* 🔹 Tenure is negatively correlated with churn — **longer-tenure customers churn less**.

---

### 📁 File Structure

```bash
matplotlib_seaborn_churn_analysis.py   # Full code (EDA, visualizations, insights)
telco_churn.csv                        # Dataset used for data cleaning practice
README.md                              # This file
```

---

### 📌 Future Improvements

* Create a **dashboard in Power BI** with these insights
* Add a **predictive model** to forecast churn risk
* Use **plotly** for interactive visualizations

---

### 🎓 What I Learned

* Deep understanding of **Matplotlib vs Seaborn** strengths
* Hands-on experience with **data cleaning and feature transformation**
* Effective use of **visual analysis to drive insights**
* How to communicate results clearly through charts

---

### 📷 Sample Visuals

> ![image](https://github.com/user-attachments/assets/d9fbdd83-3056-4c86-b6be-6c44233324d5)

> ![image](https://github.com/user-attachments/assets/db63de88-f2ea-4118-af2e-5bef304b8623)



