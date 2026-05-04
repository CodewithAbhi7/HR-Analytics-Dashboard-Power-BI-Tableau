# HR Analytics Dashboard

## Project Overview

This project is an interactive **HR Analytics Dashboard** built using **Power BI** and **Tableau**. It provides insights into employee performance, attrition trends, job satisfaction, and salary distribution using CSV-based datasets. The dashboard includes KPIs such as employee tenure, attrition rates, and performance ratings to help HR teams make data-driven decisions.
---

## Features
- **Employee Performance Analysis**: Track performance ratings and trends.
- **Attrition Rate Insights**: Identify patterns in employee attrition.
- **Job Satisfaction Trends**: Evaluate satisfaction levels across departments.
- **Salary Distribution Overview**: Analyze salary trends by role and department.
- **Interactive Dashboards**: Filter and visualize key metrics dynamically.

---

### **Objective**
Build an interactive dashboard in both PowerBI and  Tableau to analyze employee performance, satisfaction, and retention trends.

### **Scope**
- Analyze employee demographics, performance ratings, and attrition.
- Include KPIs like **average salary, job satisfaction levels, attrition rates, and tenure trends**.

### **Risk Assessment & Mitigation**
- **Risk: Inconsistent employee data** → Solution: Data validation techniques.
- **Risk: Dashboard performance issues** → Solution: Optimize DAX queries and data model.

---

## Dataset Overview
The project uses multiple CSV datasets, including:
- **Employee.csv**: Contains details such as EmployeeID, Name, Age, Gender, Job Role, etc.
- **EducationLevel.csv**: Employee education levels.
- **PerformanceRating.csv**: Performance rating scores.
- **RatingLevel.csv**: Rating categories.
- **SatisfiedLevel.csv**: Employee satisfaction levels.

### **Primary Dataset Structure (Employee.csv)**
| Column Name | Description |
|-------------|------------|
| EmployeeID | Unique identifier for each employee |
| FirstName | Employee’s first name |
| LastName | Employee’s last name |
| Gender | Employee gender |
| Age | Employee age |
| BusinessTravel | Travel frequency |
| Department | Employee's department |
| DistanceFromHome | Distance from home to work (KM) |
| State | Location state |
| Ethnicity | Employee ethnicity |
| Education | Education level |
| EducationField | Field of study |
| JobRole | Job position |
| MaritalStatus | Marital status |
| Salary | Employee salary |
| StockOptionLevel | Stock options granted |
| OverTime | Whether the employee works overtime |
| HireDate | Date of hiring |
| Attrition | Whether the employee has left the company |
| YearsAtCompany | Total years with the company |
| YearsInMostRecentRole | Years in current role |
| YearsSinceLastPromotion | Years since last promotion |
| YearsWithCurrManager | Years with current manager |

---

## Data Preparation & Cleaning
1. **Handling Missing Values**:
   - Identify and fill or remove null values in important columns.
2. **Data Formatting**:
   - Convert HireDate to datetime format.
   - Standardize categorical values (e.g., Yes/No to 1/0).
3. **Merging Datasets**:
   - Use EmployeeID as the primary key to join relevant CSV files.
4. **Creating Calculated Columns**:
   - `Employee Tenure = Current Year - Hire Year`
   - `Attrition Status = Binary classification for attrition analysis`

---

## Key Performance Indicators (KPIs)
- **Employee attrition rate**
- **Average salary per job role**
- **Performance rating distribution**
- **Job satisfaction levels**
- **Years at company vs. attrition 
---

## Screenshots
### PowerBI
<img width="1376" height="775" alt="Screenshot 2026-05-04 154645" src="https://github.com/user-attachments/assets/dbed7f49-7362-4ed2-9b3b-c4081df3ceee" />
<img width="1369" height="766" alt="Screenshot 2026-05-04 154858" src="https://github.com/user-attachments/assets/acef93ed-4e1a-4aad-8195-63a3f596845f" />
<img width="1366" height="761" alt="Screenshot 2026-05-04 154917" src="https://github.com/user-attachments/assets/fadcd678-0cd5-458b-a8fc-8dfd956f1d2d" />
<img width="1364" height="762" alt="Screenshot 2026-05-04 154930" src="https://github.com/user-attachments/assets/0336f10a-fc5f-4f17-9ee4-163ddc63a787" />
<img width="1364" height="762" alt="Screenshot 2026-05-04 154944" src="https://github.com/user-attachments/assets/118e53f4-0725-416a-8b0a-b44c5d570cc2" />

### Tableau
<img width="1378" height="799" alt="Screenshot 2026-05-03 222131" src="https://github.com/user-attachments/assets/de920e12-2d0a-4ed3-ae4d-ed0f32d61efe" />
<img width="1384" height="796" alt="Screenshot 2026-05-03 222152" src="https://github.com/user-attachments/assets/214ebf3a-e54f-4b95-93db-8eed2274614e" />


## How to Use
1. **Clone the Repository**:
2. **Open the Power BI or Tableau Dashboard**
3. **Interact with Filters & Visuals**
4. **Analyze Trends & Generate Reports**

---



