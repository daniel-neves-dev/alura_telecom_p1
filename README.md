<div  style="display: flex;">
    <img alt="Logo da empresa Alura" src="https://www.cuponation.com.br/images/fit-in/256x/images/a/alura_logo.png", style = "width:100px;">
    <img class="company-logo__img" src="https://cdn2.gnarususercontent.com.br/1/1221562/b6256fa6-5fde-4cdd-a4a3-d33ebc90bb6c.png" alt="Logo da empresa - Oracle ONE - Br Geral 8">
    <h1>Turma 8</h1>
</div>

# 📈 Customer Churn Analysis part 1

## 🎯 Main goal: This project performs an in-depth exploratory data analysis (EDA) on a telecom company's customer dataset. The primary objective is to identify the key drivers of customer churn and transform these insights into actionable business strategies to improve customer retention.

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
    <img src="https://github.com/user-attachments/assets/74e469c4-6220-4e80-a2dd-ccfed5df3dce", width="300">
</div>
</br>

* Dropouts occur mostly in the firt 12 months.
<div align = center>
    <img src="https://github.com/user-attachments/assets/d42cafc1-d14c-4f25-a63c-7a14e4393a75", width="800">
</div>
</br>

* Contract & Tenure are Decisive: The churn rate is highest for customers on month-to-month contracts and within their first 12 months of service. Customer loyalty increases significantly with longer tenure.
* Payment Method Influence: Customers paying via Electronic Check show a notably higher tendency to churn compared to those using automatic payment methods.
* High-Risk Demographics: Senior citizens (65 years old or more) exhibit a significantly higher churn rate compared to younger customers.

## 💡 Strategic Recommendations
### Based on the findings, the following actions are recommended to reduce customer churn:

Incentivize Long-Term Contracts: Develop campaigns offering discounts or perks to encourage month-to-month customers to switch to annual or two-year plans.

Enhance New Customer Onboarding: Implement a dedicated program to support and engage customers during their critical first 3-6 months to demonstrate value and build loyalty early.

Promote Service Bundles: Proactively offer bundles that include key support services to increase customer integration and make the service "stickier".

Create Targeted Campaigns: Develop specific retention strategies for high-risk segments, such as senior citizens and customers using electronic checks.

📈 Key Visualizations
Churn Rate by Month of Tenure
This line chart clearly shows that the churn rate is highest in the earliest months and stabilizes over time, highlighting the importance of early customer engagement.

(You can place your churn_rate_by_tenure.png image here)

Churn Rate by Contract Type
This bar chart illustrates the dramatic difference in churn rates, with month-to-month customers being far more likely to leave than those on long-term contracts.

(You can place your bar chart for contract churn here)

🛠️ Technologies Used
Python

Pandas: For data manipulation and analysis.

Matplotlib & Seaborn: For data visualization.

Jupyter Notebook: As the development environment.
