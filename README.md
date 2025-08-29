# Ecommerce Customer Analysis with Linear Regression

This project contains a Jupyter Notebook (`Ecommerce-Customer-Analysis-Linear-Regression.ipynb`) that uses a Linear Regression model to analyze e-commerce customer data. The main goal is to determine whether a company should focus its development efforts on its mobile app or its website to maximize yearly revenue.

---

## 🎯 Project Goal

The core objective is to analyze a dataset of customer activity and spending to answer one key question: **What is the primary driver of a customer's yearly spending?** The analysis compares the impact of time spent on the mobile app versus time spent on the website.

---

## 📂 Dataset

The dataset is publicly available on Kaggle. It contains information about e-commerce customers, including:

* **Avg. Session Length:** Average session length in the in-store style and clothing advice sessions.
* **Time on App:** The amount of time (in minutes) a customer spends on the mobile app.
* **Time on Website:** The amount of time (in minutes) a customer spends on the website.
* **Length of Membership:** The number of years a customer has been a member.
* **Yearly Amount Spent:** The total amount a customer spends in a year (this is the value we are trying to predict).

---

## 🚀 Key Findings & Recommendation

After performing the analysis, the linear regression model revealed:

* **Length of Membership** has the strongest positive correlation with Yearly Amount Spent.
* **Time on App** also has a strong positive correlation, with a higher impact on spending than Time on Website.

**Recommendation:** The company should prioritize improving the mobile app experience. The analysis suggests that a customer's yearly spending increases more significantly with every minute they spend on the app compared to the website. Additionally, focusing on customer loyalty to increase membership duration will also drive substantial revenue growth.

---

## 🛠️ How to Use This Notebook

1.  Clone the repository to your local machine.
2.  Make sure you have a Python environment with the necessary libraries installed. You can install them using pip:
    ```bash
    pip install pandas matplotlib seaborn scikit-learn
    ```
3.  Open the `Ecommerce-Customer-Analysis-Linear-Regression.ipynb` file in a Jupyter environment (like JupyterLab or Google Colab) to view and run the code.
