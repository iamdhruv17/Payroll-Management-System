# Payroll-Management-System

A web-based Payroll Management System that automates salary processing, attendance and leave tracking, and payslip generation for organizations, with separate access for HR administrators and employees.

## 📌 Project Overview
The Payroll Management System streamlines the entire payroll cycle — from marking attendance and applying for leave to calculating salaries and generating payslips. The system supports two primary actors, **HR** and **Employee**, each with a distinct set of permissions and workflows, as defined in the project's use case diagram.

## 👥 User Roles & Features :

### HR (Admin)
- Login / Authenticate Users
- Manage Employee Details
- Manage Attendance
- Manage Leave requests
- Manage Allowances & Deductions
- Process Payroll *(includes: Manage Allowances & Deductions, Calculate Salary, Generate Payslip)*
- Generate Payslip
- Generate Payroll Reports *(extends to: Export Report)*
- View Payroll History

### Employee :
- Login / Authenticate Users
- View Profile
- View Attendance
- Apply for Leave *(includes: Check Leave Availability)*
- View Salary
- View Payslip *(extends to: Download Payslip)*
- View Payroll History

### Shared :
- **Authenticate Users** — both HR and Employee logins route through a common authentication use case (`<<include>>`), ensuring a single, consistent login/security flow across the system.

## 👨‍👩‍👧‍👦 Team Members :
| Name | Role |
|------|------|
| Ayush Goel | Project Owner |
| Ayush Kumar Dingra | Lead Developer |
| Dhruv Singhal | Developer |
| Divyansh Kaushik | Database Administrator |
