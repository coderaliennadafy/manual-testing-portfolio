Test Plan – Secure Page & Session Management

1. Test Plan ID

TP-SESSION-001

2. Project Overview

This test plan defines the testing strategy for validating session management and secure page access after authentication.
The objective is to ensure that authenticated sessions behave correctly and unauthorized access is prevented.

3. Application Under Test (AUT)

https://the-internet.herokuapp.com/login

https://the-internet.herokuapp.com/secure

4. Objectives

Verify access control to secure pages

Validate session persistence and expiration

Ensure logout properly terminates the session

Prevent unauthorized access via URL, back button, or refresh

Validate session behavior across multiple tabs and incognito mode

5. Test Scope

In Scope:

Access secure page after successful login

Direct URL access without login

Logout behavior

Back button after logout

Page refresh after logout

Session behavior in:

New tab

Incognito window

Cookie & session validation (basic checks)

Out of Scope:

Penetration testing

Load / performance testing

Server-side security testing

6. Test Approach

Manual testing

Black-box testing

Exploratory testing for session behavior

7. Test Environment

Browser: Google Chrome

OS: Windows

Network: Stable internet connection

8. Test Data

Valid username

Valid password

Invalid credentials

Logged-in session

Logged-out session

9. Entry Criteria

Application is accessible

Login page loads correctly

10. Exit Criteria

All session-related test cases executed

All observed issues documented

Expected session behavior validated

11. Deliverables

Test Plan

Test Cases (Excel)

Bug Reports (if any)

README documentation

12. Risks & Assumptions

Application behavior depends on demo environment

Session handling is browser-based

13. Tools Used

Excel / Google Sheets

Browser Developer Tools

GitHub