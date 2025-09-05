 

---

# HR Data Analytics – Multinational Corporation (MNC) (2 Million Records)

## 📌 Project Overview

This project involves analyzing **HR Data of a Multinational Corporation (MNC)** containing **2 million employee records**.
The dataset provides valuable insights into workforce distribution, salary trends, attrition patterns, performance evaluation, and employment modes.

Using **Python (Pandas, Matplotlib, Seaborn, NumPy)**, we performed exploratory data analysis (EDA) to answer key HR-related business questions.
The analysis will be useful for HR professionals, business analysts, and decision-makers to identify workforce trends and support strategic HR planning.

---

## 📂 Dataset Information

* **File Type:** CSV
* **Size:** 2 Million Records (\~20 Lakhs)
* **Columns & Features:**

  1. `Employee_ID` – Unique identifier for each employee
  2. `Full_Name` – Employee’s name
  3. `Department` – Department (e.g., IT, HR, Marketing, Operations)
  4. `Job_Title` – Employee’s designation/role
  5. `Hire_Date` – Joining date
  6. `Location` – City, Country
  7. `Performance_Rating` – Numeric score (higher = better)
  8. `Experience_Years` – Years of professional experience
  9. `Status` – Employment status (Active, Resigned, Retired, Terminated)
  10. `Work_Mode` – Mode of work (On-site, Hybrid, Remote)
  11. `Salary_INR` – Annual salary (in INR)

> Note: An auto-generated `Unnamed: 0` column was dropped during preprocessing.

---

## 🔍 Business Questions Answered

We explored the dataset and answered the following HR analytics questions:

1. Distribution of **Employee Status** (Active, Resigned, Retired, Terminated)
2. Distribution of **Work Modes** (On-site, Remote, Hybrid)
3. Number of employees in each **Department**
4. **Average Salary** by Department
5. **Job Title** with the highest average salary
6. Average salary by **Department & Job Title**
7. Employees **Resigned & Terminated** in each department
8. Salary trends based on **Years of Experience**
9. Average **Performance Rating** by Department
10. Country with the **highest concentration** of employees
11. **Correlation** between Performance Rating & Salary
12. Hiring trends **per year** (Hire\_Date analysis)
13. Salary comparison: **Remote vs. On-site** employees
14. Top 10 **highest-paid employees** in each Department
15. Departments with the **highest attrition rate** (Resigned %)

---

## 🛠 Tools & Libraries

* **Programming Language:** Python
* **Libraries Used:**

  * `pandas` – Data manipulation
  * `numpy` – Numerical operations
  * `matplotlib` – Data visualization
  * `seaborn` – Statistical visualization
  * `datetime` – Date handling

---

## 📊 Key Insights

Some major insights derived from the analysis (sample):

* Most employees work **On-site**, but remote employees are growing in recent years.
* **IT Department** has the largest workforce size.
* Employees with **10–15 years of experience** earn the highest average salary.
* **Resignation** is the primary cause of attrition, especially in HR and Marketing.
* **Performance rating** and salary show a moderate correlation.
* **Remote employees** tend to earn slightly higher salaries on average compared to On-site employees.

---

## 🚀 How to Run the Project

1. Clone this repository

   ```bash
   git clone https://github.com/your-username/hr-data-analytics.git
   cd hr-data-analytics
   ```
2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook

   ```bash
   jupyter notebook HR_Data_MNC.ipynb
   ```

---

## 📈 Visualizations

The project includes **interactive charts & plots** to visualize:

* Workforce distribution
* Salary trends
* Attrition rates
* Performance analysis
* Remote vs On-site comparison

---

## 📌 Use Cases

* HR Analytics & Workforce Planning
* Attrition Prediction & Retention Strategies
* Salary Benchmarking
* Performance vs Compensation Insights
* Global Workforce Distribution Analysis

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 📜 License

This project is licensed under the MIT License.

---

 
