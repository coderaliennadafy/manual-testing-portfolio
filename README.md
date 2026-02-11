# 🔐 Secure Page Session Management – Manual Testing

## 📌 Project Overview

This mini project focuses on **manual testing** of authentication, session management, security, and basic UI/UX behaviors for a secure web page.

The goal is to validate that the application correctly handles user sessions, prevents unauthorized access, and provides clear feedback to users.

---

## 🧪 Application Under Test (AUT)

* URL: [https://the-internet.herokuapp.com/login](https://the-internet.herokuapp.com/login)
* Secure Page: [https://the-internet.herokuapp.com/secure](https://the-internet.herokuapp.com/secure)
* Test Credentials:

  * **Username:** tomsmith
  * **Password:** SuperSecretPassword!

---

## 🎯 Test Objectives

* Verify correct authentication behavior (login / logout)
* Validate session persistence and invalidation
* Ensure secure pages are protected from unauthorized access
* Identify session management and security issues
* Check basic UI/UX behavior and usability

---

## ✅ Test Coverage

### 1️⃣ Authentication Tests

* Valid login
* Invalid username / password
* Empty credentials
* Logout behavior

### 2️⃣ Session Management Tests

* Refresh secure page after login
* Access secure page using browser back button after logout
* Open secure page in a new tab
* Access secure page after clearing cookies
* Session behavior in incognito/private mode

### 3️⃣ Security Tests

* Direct access to `/secure` without login
* Access secure page after logout using copied URL
* Session invalidation after logout

### 4️⃣ UI / UX Tests

* Flash message visibility and color
* Close (X) button functionality
* Message behavior on refresh
* Page behavior on resize / zoom

---

## 🐞 Bugs Identified

* Secure page accessible after logout using browser back button *(Session Management issue)*

Detailed bug information is available in the **Bug Reports** section.

---

## 🛠 Tools Used

* Google Sheets / Excel (Test Cases & Bug Reports)
* GitHub (Version control & portfolio)
* Web Browser (Chrome)

---

## 📂 Project Structure

```
Secure-Page-Session-Management/
├── Test_Cases/
│   └── Session_Management_Test_Cases.xlsx
├── Bug_Reports/
│   └── Back_Button_Session_Issue.md
└── README.md
```

---

## 🧠 Skills Demonstrated

* Manual Testing
* Test Case Design
* Session Management Testing
* Security Testing (basic)
* Bug Reporting
* QA Logical Thinking
