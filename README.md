<div  style="display: flex;">
    <img alt="Logo da empresa Alura" src="https://www.cuponation.com.br/images/fit-in/256x/images/a/alura_logo.png", style = "width:100px;">
    <img class="company-logo__img" src="https://cdn2.gnarususercontent.com.br/1/1221562/b6256fa6-5fde-4cdd-a4a3-d33ebc90bb6c.png" alt="Logo da empresa - Oracle ONE - Br Geral 8">
    <h1>Turma 8</h1>
</div>

# 📈 Customer Churn Analysis part 1

🎯 Main goal: This project performs an in-depth exploratory data analysis (EDA) on a telecom company's customer dataset. The primary objective is to identify the key drivers of customer churn and transform these insights into actionable business strategies to improve customer retention.

Telecom Customer Churn Analysis
This project performs an in-depth exploratory data analysis (EDA) on a telecom company's customer dataset. The primary objective is to identify the key drivers of customer churn and transform these insights into actionable business strategies to improve customer retention.

## 📋 Objectives
* Clean and Prepare Data: Process raw, nested JSON data into a clean, usable format.
* Identify Churn Drivers: Analyze how different factors—such as tenure, contract type, services, and demographics—impact customer churn.
* Visualize Findings: Create clear and effective visualizations to communicate the main insights.
* Propose Strategies: Formulate data-driven recommendations for the business to reduce customer churn.

## 📊 Key Findings
### The analysis successfully identified several key factors that strongly correlate with a customer's likelihood to churn:

* Overall 26% of clients has churned.
<div align = center>
    <img src="https://github.com/user-attachments/assets/74e469c4-6220-4e80-a2dd-ccfed5df3dce", width="400">
</div>
</br>

* Dropouts occur mostly in the firt 12 months.
<div align = center>
    <img src="https://github.com/user-attachments/assets/d42cafc1-d14c-4f25-a63c-7a14e4393a75", width="800">
</div>
</br>

* Contract & Tenure are Decisive: The churn rate is highest for customers on month-to-month contracts and within their first 12 months of service. Customer loyalty increases significantly with longer tenure.
<div align = center>
    <img src="https://github.com/user-attachments/assets/38998a83-1d1c-4a6a-8282-98a50c4bc7d7", width="400">
</div>
</br>

* Payment Method Influence: Customers paying via Electronic Check show a notably higher tendency to churn compared to those using automatic payment methods.
<div align = center>
    <img src="https://github.com/user-attachments/assets/0ff4820a-24b1-476c-9cdc-401469e71fec", width="400">
</div>
</br>

* High-Risk Demographics: Senior citizens (65 years old or more) exhibit a significantly higher churn rate compared to younger customers.
<div align = center>
    <img src="https://github.com/user-attachments/assets/0918480b-1941-4a0d-b7ca-246f20f9f919", width="400">
</div>
</br>

## 💡 Strategic Recommendations
### Based on the findings, the following actions are recommended to reduce customer churn:

- Encourage annual contracts:

    Offer discounts or benefits (a free month, higher connection speed, technical support, etc.) for customers on monthly plans to switch to one or two-year contracts.

- Improve new customer onboarding:

    Create a dedicated program for customers in their first 3 to 6 months to ensure they have a positive experience and understand the value of the services. Offer "Adhesion" service packages such as Technical Support and Online Security, especially for new customers or those on monthly plans.

- Targeted Retention for Seniors:

    Develop specific communication or retention campaigns to meet the needs of senior citizens.

## 🛠️ Technologies Used
Python version 3

Pandas: For data manipulation and analysis.

Matplotlib & Seaborn: For data visualization.

Colab: As the development environment.

# Project versions:
# 🔗 Colab:
[Colab](https://github.com/daniel-neves-dev/alura_telecom_p1/blob/main/TelecomX_Data.ipynb)
