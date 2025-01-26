## HR Analytics Dashboard

This **Power BI dashboard** provides comprehensive insights into employee attrition data, helping HR professionals analyze trends and identify key factors contributing to workforce turnover. Below is a detailed explanation of each visual and metric.

**Dashboard Overview**
The dashboard focuses on attrition across various dimensions, such as education, age, salary, tenure, and job roles, supported by high-level KPIs and interactive visuals. It enables data-driven decisions to improve employee retention and workforce planning.

![HR Analytics Dashboard](images/HR%20Dashboard.png)

**Key Metrics (Top Row)**
1. **Total Employees:**
    - Displays the total number of employees in the dataset: **1,473**.
2. **Attrition:**
    - Represents the total number of employees who left the organization: **237**.
3. **Attrition Rate:**
    - The percentage of employees who left: **16.1%**.
4. **Average Age:**
    - Average age of employees: **37 years**.
5.** Average Salary:**
    - Average salary across the organization: **$6.5K per month**.
6. **Average Years at Company:**
    - Average tenure of employees: **7 years**.

These KPIs provide a snapshot of the organization's workforce and attrition trends.

### Charts Breakdown
1. **Attrition by Education (Donut Chart)**
    
    - Analyzes attrition based on employees’ education levels:
        - **Life Sciences (38%)** has the highest attrition, followed by **Medical (27%)**.
        - Other education categories, including Technical Degrees, Marketing, and Miscellaneous, account for smaller portions.
    - **Insight:**
        - The organization may need to explore retention strategies for employees with Life Sciences and Medical educational backgrounds.

2. Attrition by Age (Bar Chart)

    - Shows the distribution of attrition across age groups:
        - **26–35 age group** has the highest attrition (116 employees).
        - Younger employees (18–25) and mid-level employees (36–45) follow with 44 and 26 employees, respectively.
        - Attrition significantly drops for employees aged **55+**.
    - **Insight:**
        - Younger employees are more likely to leave, highlighting the importance of engagement strategies for this age group.
3. Attrition by Salary (Bar Chart)

    - Attrition segmented by salary ranges:
        - Employees earning **up to $5K** represent the largest attrition group (163 employees).
        - Attrition reduces significantly as salaries increase, with minimal attrition for those earning **$15K+**.
    - **Insight:**
        - Compensation plays a significant role in attrition. Enhancing salary packages or benefits for lower-income brackets may reduce turnover.
4. Attrition by Years at Company (Bar Chart)

    - Examines attrition based on tenure:
        - Employees with **1–3 years** of tenure experience the highest attrition (62 employees).
        - Attrition gradually decreases as tenure increases, with only a few leaving after **10+ years**.
    - **Insight:**
        - Retention strategies should target employees with shorter tenures.
5. Attrition by Job Role (Line Chart)

    - Tracks attrition across various roles:
        - **Laboratory Technicians (59 employees)** and **Sales Executives (47 employees)** face the highest attrition.
        - Roles like **Managers** and **Human Resources** have significantly lower attrition.
    - **Insight:**
        - Focused interventions are required for high-turnover roles like Laboratory Technicians and Sales Executives.
6. Attrition by Gender (Card Visual)
    - Summarizes attrition by gender:
        - **140 males** and **79 females** left the organization.
    - **Insight:**
        - This breakdown can help assess gender-based attrition trends and ensure equitable workplace policies.
7. Job Role Breakdown (Table Visual)
    - Provides a granular view of job roles and attrition counts:
        - For example, **62 Laboratory Technicians** were employed, and **59** of them left.
    - **Insight:**
        - This breakdown aids in identifying critical roles needing retention strategies.

##Features of the Dashboard
1. Interactive Filters:
    - The dashboard allows users to filter data by departments (Human Resources, Research & Development, Sales) to focus on specific business areas.
2. Clear Visualizations:
    - Donut charts, bar graphs, and line charts were utilized for intuitive data representation.
3. Actionable Insights:
    - The visuals are designed to highlight patterns and trends, aiding strategic decision-making.

##Tools and Technologies Used
    - **Power BI:** For dashboard creation and visualization.
    - **DAX:** For dynamic measures and calculations.
    - **Power Query:** For data cleaning and preparation.

##Key Insights
1. **Salary Matters:** Employees in lower salary brackets have higher attrition rates, suggesting a need to reevaluate compensation strategies.
2. **Engagement for Younger Employees:** The 26–35 age group requires attention to improve retention rates.
3. **Role-Specific Interventions:** High turnover in roles like Laboratory Technicians and Sales Executives should be addressed with focused efforts.

##How to Use This Dashboard
    - Download the dashboard from the GitHub repository: [GitHub Link Here]
    - Open the Power BI file in **Power BI Desktop** to explore the dataset and interact with filters.

