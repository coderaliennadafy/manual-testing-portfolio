# 🛒 E-Commerce Manual Testing Project

Environment: OpenCart Demo Store (Non-Production Environment)
Purpose: Manual Testing Practice

## 🌐 Test Environment

Application Under Test (AUT): OpenCart Demo Store  
URL: https://demo.nopcommerce.com/ 

Platform Type: Web Application  
Testing Type: Manual Testing  
Domain: E-Commerce

## 📌 Project Overview
This project focuses on manual testing of a simulated E-Commerce web application.  
The objective is to validate functionality, usability, security basics, and business logic across key modules.

This project is part of my QA Manual Testing practice and portfolio development.

---

## 🎯 Project Objectives

This project aims to perform comprehensive manual testing on an E-Commerce web application (OpenCart Demo Store), covering major modules such as Registration, Login, Product Management, Cart, Checkout, and Order Processing.

- Validate core e-commerce functionalities
- Apply functional and non-functional testing concepts
- Practice writing professional test cases
- Create structured bug reports
- Simulate real-world QA workflow

---

## 🧩 Modules Covered

| Module | Status |
| :--- | :--- |
| Registration | ✅ **Completed** |
| Login | ✅ **Completed** |
| Logout & Session Expiry | 🟡 **In Progress** |
| Product Listing | ⬜ Pending |
| Product Details | ⬜ Pending |
| Search & Filter | ⬜ Pending |
| Cart | ⬜ Pending |
| Checkout | ⬜ Pending |
| Order Confirmation | ⬜ Pending |
| Order History | ⬜ Pending |
| User Profile / Account Settings | ⬜ Pending |


Logout & Session Expiry Coverage
📂 Sub-Module 1: Logout

TC-LOG-01 → TC-LOG-17

📂 Sub-Module 2: Session Expiry
🔹 Idle Timeout

TC-SES-01

TC-SES-02

TC-SES-03

TC-SES-04

🔹 Activity Reset

TC-SES-05

🔹 Background AJAX Behavior

TC-SES-06

---

## 🧪 Testing Types Applied

- Functional Testing
- Negative Testing
- Validation Testing
- Boundary Value Analysis
- Basic Security Testing
- UI Testing

---

## 📂 Project Structure


---

## 🚀 Current Focus: Registration Module

### Scope of Registration Testing:
- Required field validation
- Email format validation
- Password rules validation
- Duplicate account handling
- Boundary value testing
- Basic security scenarios (SQL injection, script input)

---

## 📝 Test Case Structure Used

Each test case includes:

- Test Case ID
- Title
- Module
- Preconditions
- Steps
- Test Data
- Expected Result
- Actual Result
- Status
- Priority

---

## 🐞 Bug Reporting

All identified defects will be documented with:

- Bug ID
- Title
- Environment
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Priority
- Status
- Severity
- Priority
- Impact
- Comment
---

## 📈 Project Progress

Currently working on:
> Registration Module – Foundation Phase

Next step:
> Complete Registration test cases before moving to Login module.

---

## 📌 Requirement Traceability Matrix

| Requirement ID | Description | Related Test Cases |
|---------------|-------------|-------------------|
| R-01 | User must logout successfully | TC-LOG-01 → TC-LOG-05 |
| R-02 | Session must be invalidated after logout | TC-LOG-11, TC-LOG-12 |
| R-03 | Protected pages require authentication | TC-LOG-04, TC-LOG-05 |
| R-04 | Session expires after inactivity | TC-SES-01 |
| R-05 | Expired session token rejected | TC-SES-08, TC-SES-09 |

---

## 👨‍💻 Author
Ali Ennadafy  
Manual QA Enthusiast  
