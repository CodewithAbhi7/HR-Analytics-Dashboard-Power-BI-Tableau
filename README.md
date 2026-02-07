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
<img width="901" height="510" alt="Screenshot_20260207_103839_Chrome" src="https://github.com/user-attachments/assets/044b22e5-329b-48a2-b2ea-d984b387c96b" />
<img width="908" height="497" alt="Screenshot_20260207_103848_Chrome" src="https://github.com/user-attachments/assets/376f7c22-bbff-416a-856a-29224e81a025" />
<img width="898" height="518" alt="Screenshot_20260207_103856_Chrome" src="https://github.com/user-attachments/assets/da24a9a2-250a-4d6d-811c-6e09ce92034b" />
<img width="912" height="511" alt="Screenshot_20260207_103907_Chrome" src="https://github.com/user-attachments/assets/0d425091-9f32-44b4-a3ad-c97c990e7ab9" />
<img width="903" height="509" alt="Screenshot_20260207_103914_Chrome" src="https://github.com/user-attachments/assets/6a6a2acc-18d8-4eef-9a46-7b8e84140dac" />

### Tableau
<img width="915" height="568" alt="SmartSelect_20260206_165911_Drive" src="https://github.com/user-attachments/assets/5204118e-0aac-4617-ae79-1c2ea67a83db" />
<img width="937" height="571" alt="SmartSelect_20260206_165936_Drive" src="https://github.com/user-attachments/assets/fa775ee6-b892-46ca-a5a0-6389154a7b20" />

## How to Use
1. **Clone the Repository**:
2. **Open the Power BI or Tableau Dashboard**
3. **Interact with Filters & Visuals**
4. **Analyze Trends & Generate Reports**

---



