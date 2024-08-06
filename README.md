# Payroll Management System

A console-based C++ application for managing employee records and payroll information.

## Features

- Dual login system: Manager and Employee modes
- Employee management:
  - Add new employees
  - Display all employee records
  - Search for specific employees
  - Modify employee details
  - Delete employee records
- Payroll functions:
  - Generate pay slips
  - Calculate net salary with allowances and deductions

## Employee Data

The system stores the following information for each employee:
- ID
- Name
- Age
- Years of experience
- Salary
- Auto-generated password
- Salary status (received or not)

## Usage

- Managers have full access to all features
- Employees can view their own information and generate their pay slip

## Technical Details

- Implemented in C++
- Uses file handling for data storage
- Includes basic security features (password-protected logins, masked password input)

## How to Run

1. Compile the C++ file
2. Run the executable
3. Follow the on-screen prompts to navigate the system

## Note

This project is designed for educational purposes and may require additional security measures for real-world use.
