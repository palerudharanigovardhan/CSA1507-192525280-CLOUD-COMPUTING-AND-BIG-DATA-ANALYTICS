# Experiment 6: Payroll Processing System Using Zoho One (SaaS)

## Aim

To create a cloud-based **Payroll Processing System** using **Zoho One / Zoho Creator** to process employee salary details and automatically calculate **Gross Pay** and **Net Salary** using Deluge scripting, thereby demonstrating **Software as a Service (SaaS)**.

---

## Problem Statement

To develop a cloud-based Payroll Processing System that collects employee details such as Employee ID, Employee Name, experience, Basic Pay, DA, HRA, CCA, PF, Income Tax, and LOP, and automatically calculates the Gross Pay and Net Salary based on the applicable allowances and deductions.

---

## Software Requirements

- Zoho One
- Zoho Creator
- Web Browser
- Internet Connection
- Deluge Script

---

## Fields Used

| Field Name | Description |
|---|---|
| Employee ID | Unique identification number of the employee |
| Employee Name | Name of the employee |
| Experience in Present Organization | Experience in the current organization |
| Overall Experience | Total work experience |
| Basic Pay | Basic salary of the employee |
| DA | Dearness Allowance percentage |
| HRA | House Rent Allowance percentage |
| CCA | City Compensatory Allowance |
| PF | Provident Fund percentage |
| Income Tax | Income Tax percentage |
| LOP | Loss of Pay deduction |
| Gross Pay | Automatically calculated gross salary |
| Net Salary | Automatically calculated salary after deductions |

---

## Procedure

1. Log in to **Zoho One**.
2. Open **Zoho Creator** from the Zoho One applications.
3. Create a new application named **Payroll Processing**.
4. Create a new form named **Pay Roll Process**.
5. Add the required employee and salary fields.
6. Configure the appropriate field types for each field.
7. Enter the employee's Basic Pay, DA, HRA, CCA, PF, Income Tax, and LOP values.
8. Create a workflow or form action using **Deluge Script**.
9. Calculate the DA amount based on the Basic Pay.
10. Calculate the HRA amount based on the Basic Pay.
11. Calculate the Gross Pay by adding Basic Pay, DA, HRA, and CCA.
12. Calculate the PF amount based on the Basic Pay.
13. Calculate the Income Tax based on the Gross Pay.
14. Calculate the Net Salary after subtracting PF, Income Tax, and LOP.
15. Store the calculated Gross Pay and Net Salary in their respective fields.
16. Save and execute the Deluge script.
17. Enter sample employee details.
18. Submit the form.
19. Verify that the Gross Pay and Net Salary are calculated automatically.
20. Verify the submitted payroll record in Zoho Creator.

---

## Salary Calculation

### DA Amount

```text
DA Amount = Basic Pay × DA / 100
