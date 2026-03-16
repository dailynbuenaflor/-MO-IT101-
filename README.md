# -MO-IT101-
MotorPH Payroll System - Milestone 2 Initial Code Submission
# MotorPH Basic Payroll System

## Program Overview

The **MotorPH Basic Payroll System** is a Java console-based application developed to process employee payroll using data stored in CSV files.

The system reads employee details and attendance records from the **resources folder** and calculates payroll based on the company working schedule.

The standard working schedule is:

**8:00 AM – 5:00 PM**  
Extra hours are **not included**.

The program processes payroll from **June to December** and calculates the following:

- Total Hours Worked
- Gross Salary
- Government Deductions
- Net Salary

Government deductions are applied **only during the second cutoff period**.

---

## System Features

- Login authentication
- Employee information viewing
- Payroll processing for one employee
- Payroll processing for all employees
- Automatic salary calculation
- Automatic government deductions

---

## Login Credentials

**Employee**  
Username: `employee`  
Password: `12345`  

**Payroll Staff**  
Username: `payroll_staff`  
Password: `12345`  

---

## Payroll Computation

- **Total Hours Worked**: Only between 8:00 AM and 5:00 PM  
- **Gross Salary** = Total Hours Worked × Hourly Rate  
- **Government Deductions** (SSS, PhilHealth, Pag-IBIG, Withholding Tax) applied only in second cutoff  
- **Net Salary** = Gross Salary − Total Deductions  

---

## Repository Structure
