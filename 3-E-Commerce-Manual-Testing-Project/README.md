🛒 E-Commerce Manual Testing Project
📌 Purpose

Manual end-to-end functional and session testing practice on a real-world E-Commerce demo application.

🌐 Test Environment

Application Under Test: https://demo.nopcommerce.com/

Platform Type: Web Application

Domain: E-Commerce

Testing Type: Manual Functional & Session Testing

Browser: Google Chrome (Latest Version)

Operating System: Windows 10

🛠 Tools Used

Microsoft Excel (Test Case Documentation)

Chrome DevTools (Session & Network Inspection)

🗂 Test Data Strategy

Valid registered test account for positive scenarios

Invalid credentials for negative login testing

Expired session validation scenarios

Same account tested across multiple browser sessions

No real production data used

📌 Project Overview

This project simulates real-world QA validation of an E-Commerce web application.

It focuses on:

Functional validation

Session management verification

Basic security checks

Business logic validation

Requirement traceability

Structured defect documentation

The objective is to replicate an industry-standard QA workflow including test design, execution, documentation, and reporting.

🎯 Project Objectives

Validate core e-commerce functionalities

Apply functional and non-functional testing techniques

Validate authentication & session handling

Simulate real-world QA process

Create structured test documentation & traceability

🧩 Modules Covered
Module	Status
Registration	✅ Completed
Login	✅ Completed
Logout & Session Expiry	✅ Completed
Product Listing	🟡 In Progress
Product Details	⬜ Pending
Search & Filter	⬜ Pending
Cart	⬜ Pending
Checkout	⬜ Pending
Order Confirmation	⬜ Pending
Order History	⬜ Pending
User Profile / Account Settings	⬜ Pending
🔐 Authentication & Session Coverage
📂 Registration Coverage

Required field validation

Email format validation

Password rule validation

Duplicate account handling

Boundary value analysis

Basic security input validation

📂 Login Coverage

Valid login scenario

Invalid credentials handling

Error message validation

Session creation verification

📂 Logout & Session Expiry Coverage
🔹 Logout

TC-LOG-01 → TC-LOG-17
Coverage includes:

Successful logout

Redirect validation

Session invalidation

Protected page access after logout

Console error monitoring

Response time validation

🔹 Session Expiry
Idle Timeout

TC-SES-01 → TC-SES-04

Activity Reset

TC-SES-05

Background AJAX Behavior

TC-SES-06

Coverage includes:

Session timeout behavior

Idle detection validation

Protected endpoint rejection

Token invalidation scenarios

Multi-tab session handling

🛍️ Product Listing Coverage (In Progress)

TC-PL-01 → TC-PL-XX

Coverage Areas:

Page load validation

Product data display validation

Product image verification

Price & discount validation

Navigation to Product Details

Add to Cart from listing

Sorting functionality

Filtering functionality

Pagination behavior

Empty category handling

Out-of-stock display

Console error validation

Performance observation

🧪 Testing Types Applied

Functional Testing

Negative Testing

Validation Testing

Boundary Value Analysis

Basic Security Testing

UI Testing

Session Testing

📝 Test Case Structure

Each test case includes:

Test Case ID

Title

Module

Preconditions

Steps

Test Data

Expected Result

Actual Result

Status

Priority

🐞 Bug Reporting Structure

Each defect includes:

Bug ID

Title

Environment

Steps to Reproduce

Expected Result

Actual Result

Severity

Priority

Status

Impact

Comments

📌 Requirement Traceability Matrix (RTM)
Requirement ID	Description	Related Test Cases
R-01	User must logout successfully	TC-LOG-01 → TC-LOG-05
R-02	Session must be invalidated after logout	TC-LOG-11, TC-LOG-12
R-03	Protected pages require authentication	TC-LOG-04, TC-LOG-05
R-04	Session expires after inactivity	TC-SES-01
R-05	Expired session token rejected	TC-SES-08, TC-SES-09
📈 Project Status

Current Focus:

Completing Product Listing module with full functional & business validation coverage.

Next Steps:

Complete Product Details testing

Expand coverage to Cart & Checkout

Add API Testing layer (Postman)

Enhance traceability & documentation

👨‍💻 Author

Ali Ennadafy
Manual QA Engineer (In Progress Portfolio)
