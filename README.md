<div align="center">

#  Manual Testing Portfolio
### Ali Ennadafy — QA Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR_LINKEDIN)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aennadafy@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/coderaliennadafy)

*Aspiring QA Engineer | Manual Testing Specialist | Passionate about Software Quality*

</div>

---

##  About This Portfolio

This portfolio demonstrates professional manual QA testing skills through real-world projects on publicly available web applications. Each project follows industry-standard QA workflows including test planning, test case design, test execution, defect reporting, and test summary documentation.

> **Note:** All testing was performed on publicly available demo environments. No production data, real payment information, or proprietary systems were accessed.

---

##  Projects Overview

| # | Project | Application | Test Cases | Bugs Found | Status |
|---|---------|-------------|------------|------------|--------|
| 1 | [Login Functionality Testing](#1-login-functionality-testing) | the-internet.herokuapp.com | 20+ | 0 | ✅ Completed |
| 2 | [Secure Page & Session Management](#2-secure-page--session-management) | the-internet.herokuapp.com | 24 | 1 Critical | ✅ Completed |
| 3 | [E-Commerce End-to-End Testing](#3-e-commerce-end-to-end-testing) | nopCommerce Demo Store | 284+ | 12 | ✅ Completed |

---

## 1.  Login Functionality Testing

**Application:** [https://the-internet.herokuapp.com/login](https://the-internet.herokuapp.com/login)

### What Was Tested
- ✅ Positive login scenarios (valid credentials)
- ✅ Negative login scenarios (invalid email, wrong password, empty fields)
- ✅ Validation messages and UI feedback

### Deliverables
| File | Description |
|------|-------------|
| `Login_Test_Cases.xlsx` | 20+ structured test cases |
| `Bug Report Template.xlsx` | Template (no defects found this cycle) |

### Key Finding
No defects found during this test cycle. All validation messages and authentication flows work correctly.

---

## 2.  Secure Page & Session Management

**Application:** [https://the-internet.herokuapp.com/login](https://the-internet.herokuapp.com/login)

### What Was Tested
- ✅ User authentication (valid & invalid scenarios)
- ✅ Session management & cookie security
- ✅ Direct URL access control (protected pages)
- ✅ Multi-browser session behavior
- ✅ Logout behavior and session invalidation
- ✅ HttpOnly & Secure cookie flags

### Test Results
| Metric | Value |
|--------|-------|
| Total Test Cases | 24 |
| Passed | 23 |
| Failed | 1 |

###  Critical Bug Found
> **BUG-001 — Back Button Allows Access to Secure Page After Logout**  
> After logging out, clicking the browser back button restores access to the secure page.  
> **Impact:** Incomplete session invalidation / improper cache handling.  
> **Severity:** High | **Priority:** High

---

## 3.  E-Commerce End-to-End Testing

**Application:** [https://demo.nopcommerce.com/](https://demo.nopcommerce.com/)  
**Type:** Professional end-to-end manual QA simulation

### Project Highlights

```
✅ 284+ Test Cases Designed & Executed
✅ 12 Modules Fully Covered
✅ 12 Defects Identified & Documented
✅ Industry-Standard Documentation
✅ Complete Requirement Traceability
✅ Risk-Based Testing Approach
```

### Module Coverage

| Module | Test Cases | Pass | Fail | Blocked/N/A | Status |
|--------|-----------|------|------|-------------|--------|
| 📝 Registration | 40 | 37 | 3 | 0 | ✅ Completed |
| 🔑 Login | 38 | 35 | 1 | 2 | ✅ Completed |
| 🚪 Logout & Session | 17 | 17 | 0 | 0 | ✅ Completed |
| ⏱️ Session Expiry | 9 | 9 | 0 | 0 | ✅ Completed |
| 📦 Product Listing | 45 | 38 | 0 | 7 | ✅ Completed |
| 🔍 Product Details | 20 | 19 | 1 | 0 | ✅ Completed |
| 🔎 Search & Filter | 20 | 19 | 1 | 0 | ✅ Completed |
| 🛒 Shopping Cart | 15 | 15 | 0 | 0 | ✅ Completed |
| 💳 Checkout | 14 | 13 | 0 | 1 | ✅ Completed |
| ✅ Order Confirmation | 9 | 9 | 0 | 0 | ✅ Completed |
| 📋 Order History | 19 | 19 | 0 | 0 | ✅ Completed |
| 👤 User Profile | 38 | 30 | 5 | 3 | ✅ Completed |
| **TOTAL** | **284** | **260** | **11** | **13** | **~91.5% Pass Rate** |

###  Key Defects Found

| Bug ID | Module | Title | Severity |
|--------|--------|-------|---------|
| BUG_REG_001 | Registration | Internal server error on 1000+ char input | High |
| BUG_REG_004 | Registration | Password with only spaces accepted | High |
| BUG_LOG_001 | Login | No field-level validation on empty password | Medium |
| BUG-PD-001 | Product Details | Image zoom not working | Medium |
| BUG-SF-01 | Search & Filter | No results with combined filters | Medium |
| BUG_UP_01 | User Profile | No password complexity enforcement | High |
| BUG_UP_06 | User Profile | Sessions not invalidated after password change | **Critical** |
| BUG_UP_09 | User Profile | No session timeout policy | **Critical** |
| BUG_UP_27 | User Profile | DB error exposed on oversized input | High |
| BUG_OH_01 | Order History | Missing pagination for large datasets | Medium |

###  Project Structure

```
3-E-Commerce-Manual-Testing-Project/
│
├── 1-Test_Plan/
│   └── Test_Plan.xlsx              ← Full test plan with scope, strategy, risks
│
├── 2-Test_Cases/
│   ├── 1-TC_Registration.xlsx
│   ├── 2-TC_Login.xlsx
│   ├── 3-TC_logout_session_Management.xlsx
│   ├── 4-Test_Cases_Product_Listing.xlsx
│   ├── 5-Test_Cases_Product_Details.xlsx
│   ├── 6-Test_cases_Search_Filter.xlsx
│   ├── 7-Test_Cases_Shopping_Cart.xlsx
│   ├── 8-Test_Cases_Checkout.xlsx
│   ├── 9-Test_Cases_Order_Confirmation.xlsx
│   ├── 10-order_history.xlsx
│   └── 11-Test_Cases_User_Profile.xlsx  ← 38 detailed test cases
│
├── 3-Bug-Report/
│   ├── 1-Bug_Report_Registration.xlsx   ← 8 bugs
│   ├── 2-Bug_Report_Login.xlsx          ← 1 bug
│   ├── 3-Bug_Report_Product_Listing.xlsx
│   ├── 4-Bug_Report_Product_Details.xlsx ← Image zoom bug
│   ├── 5-Bug_Report_Search_Filter.xlsx
│   ├── 6-Shopping_Cart_Bug_Report.xlsx
│   ├── 7-Bug_Report_Checkout.xlsx
│   ├── 8-Order_Confirmation_Bug_Report.xlsx
│   ├── 9-Order_History_Pagination_Bug.xlsx
│   └── 10-Bug_Report_User_Profile.xlsx  ← 9 bugs incl. 2 Critical
│
├── 4-Test_Summary_Report/
│   └── Test_Summary_Report_Complete.xlsx ← Full report all 12 modules
│
├── 5-RTM/
│   └── RTM_Complete.xlsx               ← 48 requirements traced
│
└── README.md
```

###  Tools & Technologies

| Category | Tool |
|----------|------|
| Test Documentation | Microsoft Excel |
| Browser Debugging | Chrome DevTools (Network, Console, Application tabs) |
| Browser | Google Chrome (Latest) |
| OS | Windows 10 |
| Version Control | GitHub |

### Testing Techniques Applied

| Technique | Applied In |
|-----------|-----------|
| Boundary Value Analysis | Registration, User Profile, Input fields |
| Equivalence Partitioning | Login, Search, Validation testing |
| Negative Testing | All modules |
| Error Guessing | Security modules, edge cases |
| Session Testing | Login, Logout, User Profile |
| Security Testing | Authentication, User Profile, SQL/XSS |
| UI/UX Testing | All front-end modules |

---

##  Future Plans

- [ ] **API Testing** — Postman collection for nopCommerce API endpoints
- [ ] **Performance Testing** — JMeter load tests on key flows
- [ ] **Test Automation** — Selenium + Python framework for regression suite
- [ ] **CI/CD Integration** — Automated test runs on GitHub Actions

---

##  Overall Portfolio Stats

| Metric | Value |
|--------|-------|
| Total Projects | 3 |
| Total Test Cases | 300+ |
| Total Bugs Found | 13 |
| Modules Covered | 14 |
| Documentation Files | 35+ |
| Testing Techniques | 7+ |

---

##  Contact

**Ali Ennadafy**  
📧 aennadafy@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/YOUR_LINKEDIN)  
💻 [GitHub](https://github.com/coderaliennadafy)

---

<div align="center">

*This portfolio demonstrates real-world manual QA skills on publicly available demo applications.*  
*All testing follows ethical practices. No production systems or real user data were used.*

**If you found this project useful, please ⭐ star the repository!**

*Last Updated: March 2026*

</div>