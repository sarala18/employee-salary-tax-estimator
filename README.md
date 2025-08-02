# Employee Salary Tax Estimator

This Python project calculates the annual tax based on employee salary inputs and provides visual insights using pie charts. It is designed to demonstrate basic data processing, user input handling, tax slab logic, exception handling, and data export using Pandas.

---

## 📊 Project Objective

To build a simple, beginner-friendly Python project that:
- Takes employee details and salary input
- Calculates annual salary and estimated tax
- Visualizes tax breakdown using a pie chart
- Saves the data to a CSV file for record keeping

---

## 🧾 Dataset

There is no external dataset. User inputs are taken within the program for each employee.  
However, a sample `.csv` file is generated as output using Pandas.

---

##  Tools & Libraries Used

- Python (Core)
- Pandas
- Matplotlib
- Exception Handling

---

##  Features

- Accepts multiple employee entries
- Calculates:
  - Annual Salary
  - Tax amount based on income slabs
  - Net Salary after tax
- Visual Pie Chart of Tax vs Net Salary
- Exports all data to `employee_tax_data.csv`

---

## Tax Slabs Used (Sample)

| Annual Salary Range     | Tax Rate   |
|-------------------------|------------|
| Up to ₹2,50,000         | 0%         |
| ₹2,50,001 to ₹5,00,000  | 5%         |
| ₹5,00,001 to ₹10,00,000 | 10%        |
| Above ₹10,00,000        | 20%        |

---

## 📉 Sample Visualization

> A pie chart is generated for each employee to show the share of tax and net income.

<img width="631" height="504" alt="image" src="https://github.com/user-attachments/assets/d92ce377-801d-4240-a8b3-8d05a825d536" />

---

## 💾 Output Example

| Name   | Monthly Salary | Annual Salary | Tax  | Net Salary |
|--------|----------------|----------------|------|------------|
| Srinu | ₹67,500      | ₹9,00,000      | ₹9,000 | ₹8,10,000 |

---

## ▶️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/sarala18/employee-salary-tax-estimator.git
