HR Data Analytics – Multinational Corporation (MNC) (2 Million Records)
📌 Project Overview

This project involves analyzing HR Data of a Multinational Corporation (MNC) containing 2 million employee records.
The dataset provides valuable insights into workforce distribution, salary trends, attrition patterns, performance evaluation, and employment modes.

Using Python (Pandas, Matplotlib, Seaborn, NumPy), we performed exploratory data analysis (EDA) to answer key HR-related business questions.
The analysis will be useful for HR professionals, business analysts, and decision-makers to identify workforce trends and support strategic HR planning.

📂 Dataset Information

File Type: CSV

Size: 2 Million Records (~20 Lakhs)

Columns & Features:

Employee_ID – Unique identifier for each employee

Full_Name – Employee’s name

Department – Department (e.g., IT, HR, Marketing, Operations)

Job_Title – Employee’s designation/role

Hire_Date – Joining date

Location – City, Country

Performance_Rating – Numeric score (higher = better)

Experience_Years – Years of professional experience

Status – Employment status (Active, Resigned, Retired, Terminated)

Work_Mode – Mode of work (On-site, Hybrid, Remote)

Salary_INR – Annual salary (in INR)

Note: An auto-generated Unnamed: 0 column was dropped during preprocessing.

🔍 Business Questions Answered

We explored the dataset and answered the following HR analytics questions:

Distribution of Employee Status (Active, Resigned, Retired, Terminated)

Distribution of Work Modes (On-site, Remote, Hybrid)

Number of employees in each Department

Average Salary by Department

Job Title with the highest average salary

Average salary by Department & Job Title

Employees Resigned & Terminated in each department

Salary trends based on Years of Experience

Average Performance Rating by Department

Country with the highest concentration of employees

Correlation between Performance Rating & Salary

Hiring trends per year (Hire_Date analysis)

Salary comparison: Remote vs. On-site employees

Top 10 highest-paid employees in each Department

Departments with the highest attrition rate (Resigned %)

🛠 Tools & Libraries

Programming Language: Python

Libraries Used:

pandas – Data manipulation

numpy – Numerical operations

matplotlib – Data visualization

seaborn – Statistical visualization

datetime – Date handling

📊 Key Insights

Some major insights derived from the analysis (sample):

Most employees work On-site, but remote employees are growing in recent years.

IT Department has the largest workforce size.

Employees with 10–15 years of experience earn the highest average salary.

Resignation is the primary cause of attrition, especially in HR and Marketing.

Performance rating and salary show a moderate correlation.

Remote employees tend to earn slightly higher salaries on average compared to On-site employees.

📈 Visualizations

This project includes multiple visualizations for deeper insights.

1️⃣ Employee Status Distribution

2️⃣ Work Mode Distribution

3️⃣ Department-wise Employee Count

4️⃣ Average Salary by Department

5️⃣ Salary vs. Experience Trend

6️⃣ Correlation Heatmap (Salary vs Performance)

📌 Save your generated plots in the images/ folder so they automatically appear in the README.

🚀 How to Run the Project

Clone this repository

git clone https://github.com/your-username/hr-data-analytics.git
cd hr-data-analytics


Install dependencies

pip install -r requirements.txt


Run the Jupyter Notebook

jupyter notebook HR_Data_MNC.ipynb

📌 Use Cases

HR Analytics & Workforce Planning

Attrition Prediction & Retention Strategies

Salary Benchmarking

Performance vs Compensation Insights

Global Workforce Distribution Analysis

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

📜 License

This project is licensed under the MIT License.
