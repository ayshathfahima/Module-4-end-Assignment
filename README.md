# Module-4-end-Assignment
# ABC Company Employee Data Analysis

## Project Overview

This project involves analyzing employee data from ABC Company. The dataset contains 458 rows and 9 columns of employee information, including details about their team, position, age, height, weight, salary, and college. The objective of this project is to preprocess the data, perform an analysis, and present the findings through visualizations.

### Tasks Completed

1. **Preprocessing**: 
   - Corrected the data in the "height" column by replacing non-numeric values with random numbers between 150 and 180 to ensure data consistency.

2. **Analysis Tasks**:
   - **Team Distribution**: Analyzed the distribution of employees across different teams and calculated their percentage split.
   - **Position Distribution**: Segregated employees based on their positions within the company.
   - **Age Group**: Identified the predominant age group among employees.
   - **Salary Expenditure**: Found the team and position with the highest salary expenditure.
   - **Correlation between Age and Salary**: Investigated if there is any correlation between employee age and salary.

3. **Visualizations**:
   - For each of the analysis tasks, appropriate graphical representations were created using `matplotlib` and `seaborn`.

4. **Data Story**:
   - A summary of the findings, highlighting key trends and insights from the dataset, was provided.

---

## Dataset

The dataset contains the following columns:

1. **Name**: The name of the employee.
2. **Team**: The team the employee belongs to (e.g., Boston Celtics, Brooklyn Nets).
3. **Number**:  employee ID.
4. **Position**: The job position or role of the employee (e.g., PG, SG, PF, C).
5. **Age**: The age of the employee.
6. **Height**: The height of the employee (with data preprocessing to replace invalid entries).
7. **Weight**: The weight of the employee.
8. **College**: The college attended by the employee.
9. **Salary**: The salary of the employee.

---

## Steps done for Completing the Project

### 1. Data Preprocessing
- The **"Height"** column contains some invalid values (e.g., non-numeric entries). These values were replaced with random integers between 150 and 180 using `numpy` and `pandas`.

### 2. Data Analysis
- **Team Distribution**: Calculated the distribution of employees across teams and computed the percentage split.
- **Position Distribution**: Segregated employees based on their positions and visualized the data.
- **Age Group Distribution**: Employees were categorized into age groups to identify the most common age range.
- **Salary Expenditure**: The total salary expenditure for each team and position was calculated.
- **Correlation Analysis**: A scatter plot was created to visually assess the correlation between age and salary.

### 3. Visualizations
- A series of **bar charts**, **pie charts**, and **scatter plots** were created using `matplotlib` and `seaborn` to present the analysis results effectively.



## Technologies Used

- **Python**: The primary programming language.
- **Pandas**: Used for data manipulation and analysis.
- **Matplotlib**: Used for creating visualizations (charts, graphs).
- **Seaborn**: Used for advanced visualizations like scatter plots.
- **Jupyter Notebook**: The development environment used for creating and presenting the analysis.

---

