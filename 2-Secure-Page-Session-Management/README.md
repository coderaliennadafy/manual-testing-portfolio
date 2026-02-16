🔎 Project Title

Manual Testing – Authentication & Session Management Test Suite

📖 Project Description

This project contains a complete manual test suite for the login and secure area functionality of a web application.

The goal of this project is to validate authentication behavior, session management, security controls, and UI feedback messages using structured manual testing techniques.

Application under test:
https://the-internet.herokuapp.com/login

🎯 Test Scope

The following areas were tested:

User Authentication (valid & invalid scenarios)

Session Management

Direct URL access control

Logout behavior

Multiple browser sessions

Cookie security flags (HttpOnly & Secure)

Flash message behavior

UI validation (color, text, visibility)

🧪 Test Types Covered

Functional Testing

Negative Testing

Session Testing

Security Testing

UI Testing

📊 Test Coverage

Total Test Cases: 24

Passed: 23

Failed: 1 (Back button allows access after logout)

🐞 Bug Identified

Issue:
After logging out, using the browser back button allows access to the secure page.

Impact:
This may indicate improper client-side cache handling or incomplete session invalidation.

🛠 Tools Used

Manual Testing

Google Sheets

Chrome DevTool