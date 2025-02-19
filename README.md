# HR Dashboard Tableau Project

## **Project Background & Objective:**  

The HR department plays a crucial role in managing workforce stability, employee engagement, and organizational growth. However, challenges such as **high attrition rates, salary disparities, and demographic shifts** require a **data-driven approach** to workforce planning. This project focuses on leveraging HR analytics to provide insights into hiring trends, attrition patterns, and salary structures to enhance employee retention and decision-making.  

The goal is to develop a **comprehensive HR dashboard** that enables HR managers to:  

* **Track workforce trends** – Analyze hiring, attrition, and employee distribution across locations.  
* **Identify attrition drivers** – Assess key factors like department, salary, and tenure impacting employee turnover.  
* **Evaluate salary distribution** – Compare salary trends across education levels, gender, and job roles.  
* **Improve workforce planning** – Provide actionable insights for retention strategies and organizational growth.  

This dashboard will include **high-level summaries and detailed employee records**, allowing HR to make informed, strategic decisions.

## **Dataset and Data Discription:**
The provided dataset consists of information on 8950 employees. Below is a detailed explanation of the dataset and its attributes:

* Employee ID: Unique identification number assigned to each employee.
* First Name: First name of the employee.
* Last Name: Last name of the employee.
* Gender: Gender of the employee, categorized as Male or Female.
* State and City: The location where the employee works.
* Hire Date: The date when the employee was hired at the company.
* Department: The department or division in which the employee works within the organization.
* Job Title: Specific role or position held by the employee within the organization.
* Education Level: The highest education qualification of the employee.
* Performance Rating: The employee’s performance evaluation which is categorized as ‘Excellent’, ‘Good’, ‘Satisfactory’, or ‘Needs Improvement’.
* Overtime: Indicates whether the employee has worked overtime.
* Salary: The employee’s earnings based on department and job title.
* Birth Date: The date of birth of the employee.
* Termination Date: The date when the employee left the company.
* Adjusted Salary: The salary adjustment calculated based on gender, education level, and age.

## Dashborad Overview:
![Screenshot 2024-05-13 095723](https://raw.githubusercontent.com/Premith96/HR_Dashboard_Analytics_Project/refs/heads/main/HR%20_Analysis_Dashboard.png)

The summary view consists of three main sections:  

1️⃣ **Overview** – Key HR metrics and trends.  
2️⃣ **Demographics** – Workforce composition analysis.  
3️⃣ **Income Analysis** – Salary insights across different employee groups.  

### **Key Performance Indicators (KPIs)**  

| **Metric**          | **2019**  | **2020**  | **2021**  | **2022**  | **2023**  | **Change (2019-2023)** |
|--------------------|---------|---------|---------|---------|---------|------------------|
| **Total Employees** | 7,800   | 8,200   | 8,500   | 8,750   | 8,950   | **+14.7% 📈** |
| **Total Attrition** | 725     | 850     | 923     | 945     | 966     | **+33.3% 📉** |
| **Attrition Rate**  | 9.3%    | 10.4%   | 10.9%   | 10.8%   | 10.8%   | **+1.5% 📉** |
| **Active Employees** | 7,075  | 7,350   | 7,577   | 7,805   | 7,984   | **+12.8%** |
| **Average Salary**  | $67,200 | $69,500 | $71,100 | $71,950 | $72,415 | **+7.8% 💰** |
| **Average Age**     | 40.5 yrs | 41.0 yrs | 41.3 yrs | 41.6 yrs | 41.8 yrs | **+1.3 yrs** |
| **Average Tenure**  | 5.3 yrs | 5.4 yrs | 5.2 yrs | 5.1 yrs | 5.12 yrs | **-0.18 yrs** |

✅ **Key Insights:**  
📉 Attrition has steadily increased, peaking at **10.9% in 2021**.  
📈 Workforce size grew by **14.7%**, showing company expansion despite attrition challenges.  
💰 Salaries have increased by **7.8%**, but this has not significantly reduced attrition.  
⏳ **Average tenure slightly declined (-0.18 years)**, suggesting lower retention rates.  

✅ **Recommendations:**  
🔸 Improve retention strategies (e.g., mentorship programs, career growth opportunities).  
🔸 Re-evaluate compensation strategies to retain top talent.  

### **Workforce Growth & Attrition Trends**  

| **Year** | **New Hires** | **Terminations** | **Attrition Rate** |
|---------|-------------|--------------|----------------|
| **2019** | 1,050       | 725          | **9.3%**      |
| **2020** | 1,280       | 850          | **10.4%**     |
| **2021** | 1,320       | 923          | **10.9%**     |
| **2022** | 1,150       | 945          | **10.8%**     |
| **2023** | 1,180       | 966          | **10.8%**     |

✅ **Key Insights:**  
- Hiring **peaked in 2021** (1,320 new employees) due to post-pandemic recovery.  
- **Attrition remained high**, requiring stronger employee engagement and retention policies.  
- **Slight hiring slowdown in 2022 & 2023**, indicating a focus on stabilizing workforce size.  

✅ **Recommendations:**  
🔸 Enhance employee benefits & flexible work options to reduce voluntary resignations.  
🔸 Conduct exit interviews to identify attrition drivers.  

### **Gender Distribution**  

| **Gender** | **2019** | **2023** | **Change** |
|----------|---------|---------|------------|
| **Male**   | 62.1%   | 60.8%   | **-1.3% 🔽** |
| **Female** | 37.9%   | 39.2%   | **+1.3% 🔼** |

✅ **Key Insights:**  
📈 **Increase in female workforce representation (+1.3%)**, but still male-dominated.  
💡 **Diversity initiatives** may be contributing to gender balance improvements.  

✅ **Recommendations:**  
🔸 Enhance leadership opportunities for women through **mentorship programs**.  

### **Age Group Distribution**  

| **Age Group** | **Employees** | **Attrition Rate** |
|-------------|------------|----------------|
| **Under 25**  | 710        | **17.8% 🔴** |
| **25-34**     | 2,850      | **14.2% 🟠** |
| **35-44**     | 2,560      | **9.6% 🟡**  |
| **45-54**     | 1,580      | **7.4% 🟢**  |
| **55+**       | 1,250      | **5.2% 🟢**  |

✅ **Key Insights:**  
📉 Younger employees (<35 years) have the **highest attrition (14.2%-17.8%)**.  
🟢 Older employees (45+) are **more stable**, possibly due to long-term career security.  

✅ **Recommendations:**  
🔸 Develop **career pathways** for younger employees to improve retention.  
🔸 Provide **skill-building programs** to support younger workforce development.  

### **Salary vs Education Level**  

| **Education Level** | **Average Salary ($)** | **Attrition Rate** |
|-------------------|----------------|----------------|
| **High School**   | 54,100         | **15.3% 🔴**  |
| **Associate Degree** | 61,250         | **13.8% 🟠**  |
| **Bachelor’s Degree** | 74,600         | **10.1% 🟡**  |
| **Master’s Degree**   | 88,750         | **7.9% 🟢**  |
| **Doctorate**        | 102,300        | **4.8% 🟢**  |

✅ **Key Insights:**  
📉 **Higher education correlates with lower attrition**.  
💰 **Bachelor’s degree holders** make up the **largest workforce segment** but still face **moderate attrition (10.1%)**.  

✅ **Recommendations:**  
🔸 Offer **tuition reimbursement & training programs** to encourage upskilling.  

## **Conclusion & Next Steps**  

### **Final Recommendations & Action Plan**  

✅ **Retention Strategies for High Performers**  
→ **Higher salary incentives, leadership programs, and structured promotions.**  

✅ **Address Burnout in High-Attrition Departments**  
→ **Better workload management, wellness initiatives, and flexible work arrangements.**  

✅ **Salary Adjustments for Middle-Income Employees**  
→ **Regular pay reviews & performance-based bonuses.**  

✅ **Support for NYC Employees**  
→ **Hybrid work & cost-of-living salary adjustments.**  

**Next Steps:** 
🔸 Implement **targeted engagement programs** for younger employees.  
🔸 Optimize **recruitment and compensation strategies** to reduce voluntary turnover.  
🔸 Utilize **HR dashboards** for continuous monitoring & predictive attrition analytics.  

🚀 **This data-driven HR strategy will help reduce attrition & improve workforce stability!**
