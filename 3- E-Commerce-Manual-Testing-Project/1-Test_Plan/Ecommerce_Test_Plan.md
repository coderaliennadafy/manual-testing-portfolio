E-Commerce Website – Test Plan
Module: User Registration

Application Under Test: OpenCart Demo Store
Environment Type: Non-Production (Demo)

1️⃣ Objective

To verify that the User Registration functionality of the E-Commerce web application operates correctly, securely, and according to defined business requirements.

2️⃣ Scope
2.1 In Scope

The following modules are covered under this test plan:

User Registration

Login

Product Browsing

Cart

Checkout

Order Management

2.2 Out of Scope

Payment gateway real transaction validation

Performance testing

Load testing

Backend database validation

3️⃣ Test Approach

The Registration module will be tested using the following testing techniques:

Functional Testing

Validation Testing

Boundary Value Analysis

Negative Testing

Basic Security Testing

UI Testing

4️⃣ Test Environment

Application: OpenCart Demo Store

Platform Type: Web Application

Environment: Demo / Non-Production

Browser Used: (Specify your browser)

Operating System: (Specify your OS)

5️⃣ Registration Module Analysis
5.1 Fields Identified
Personal Details

First Name (Required)

Last Name (Required)

Email (Required)

Telephone (Required)

Password Section

Password (Required)

Confirm Password (Required)

Additional Options

Newsletter Subscription (Optional – Yes / No)

Privacy Policy Checkbox (Mandatory)

5.2 Business Rules
First Name

Must not be empty

Must respect minimum and maximum length constraints

Must not contain only whitespace

Last Name

Must not be empty

Must respect minimum and maximum length constraints

Must not contain only whitespace

Email

Must not be empty

Must follow valid email format (example@mail.com
)

Must be unique (duplicate accounts are not allowed)

Email comparison is case-insensitive

Telephone

Must not be empty

Must contain valid numeric input

System behavior regarding special characters (+, -, spaces) will be validated during testing

Password

Must not be empty

Must meet minimum length requirement (to be confirmed during testing)

Must respect maximum length constraint

No strict complexity enforcement observed in demo environment

Confirm Password

Must exactly match the Password field

Comparison is case-sensitive

Privacy Policy

Must be selected before form submission

Registration cannot proceed without acceptance

5.3 Expected Success Flow

When valid data is submitted:

The account is successfully created.

User is redirected to the “Account Created” confirmation page.

User is automatically logged into the system.

5.4 Assumptions

Email verification is not required in the demo environment.

CAPTCHA validation is not implemented.

Demo data may reset periodically.

5.5 Risks

Demo environment may not reflect real production behavior.

Server response time may vary.

Data may be reset without notice.

6️⃣ Entry Criteria

Application is accessible

Registration page is available

Test environment is stable

7️⃣ Exit Criteria

All planned test cases are executed

All critical and high-severity defects are documented

Test execution results are recorded
