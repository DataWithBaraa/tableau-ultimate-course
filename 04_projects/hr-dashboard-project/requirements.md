# Project Requirements

A PDF version of this document is in [Project_Requirements.pdf](Project_Requirements.pdf).

As an HR manager, I want a dashboard to analyze the HR data: summary views for high-level insights, and employee records for in-depth analysis.

## Summary View (Overview, Demographics, Income)

### Overview
- Display the total number of hired, active and terminated employees.
- Visualize the hired and the terminated employees over the years.
- Break down the employees by department and job title.
- Compare the employees at the HQ (New York) and in the branches.
- Show how the employees are distributed by city and state.

### Demographics
- Present the gender ratio in the company.
- Visualize the employees across age groups and education levels.
- Show the number of employees in each age group and education level.
- Present how education correlates with performance rating.

### Income
- Compare salaries by education level and gender, to find gaps or patterns.
- Present how age correlates with salary for the employees of each department.

---

## Employee Records View
- List all employees with the necessary information: name, department, position, gender, age, education and salary.
- Let the users filter the list by any of its columns.

---

## The Dataset (how it was made)

The dataset is generated: 8,950 employee records. The Python script was made with ChatGPT from the prompt below. The script is [generate_data.py](generate_data.py) in this folder, and the dataset is [dataset.csv](dataset.csv).

### The Prompt
Generate a Python script that creates a realistic dataset of 8,950 human resources records, with these attributes:
- **Employee ID**: a unique identifier.
- **First Name** and **Last Name**: randomly generated.
- **Gender**: 'Female' with a 46% probability, 'Male' with 54%.
- **State and City**: randomly assigned from a list of states and their cities.
- **Hire Date**: randomly generated, with a probability for each year from 2015 to 2024.
- **Department**: chosen from a list of departments, each with its probability.
- **Job Title**: chosen by department, each job title with its probability.
- **Education Level**: chosen from the education levels that fit the job title.
- **Performance Rating**: 'Excellent', 'Good', 'Satisfactory' or 'Needs Improvement', each with its probability.
- **Overtime**: 'Yes' with a 30% probability, 'No' with 70%.
- **Salary**: within a range for each department and job title.
- **Birth Date**: from the age groups and the job title, consistent with the hire date.
- **Termination Date**: for 11.2% of the employees, with a probability for each year from 2015 to 2024, at least 6 months after the hire date.
- **Adjusted Salary**: the salary with multipliers for gender, education level and age.

Structure the code cleanly, with functions where they fit, and comments that explain each step.
