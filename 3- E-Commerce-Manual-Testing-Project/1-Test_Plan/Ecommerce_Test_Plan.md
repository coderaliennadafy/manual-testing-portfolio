1️⃣ Objective

Verify that the E-Commerce website functions correctly, securely, and meets business requirements.

2️⃣ Scope

Modules to be tested:

User Registration

Login

Product Browsing

Cart

Checkout

Order Management

3️⃣ Test Types

Functional Testing

Validation Testing

Boundary Testing

Security Basic Testing

UI Testing

Negative Testing


🔹Fields

1-Personal Details               

First Name *

Last Name *

Email *

Telephone *

2-Password

Password *

Password Confirm *

3-Newsletter

Subscribe Yes / No (Radio button)

4-Privacy Policy

Checkbox “I agree to Privacy Policy” *

Expected Rules:
(Business Rules)

🔹 First Name
Required
Min length 1 or 2 char
Max length (example 32 character)
no espace 

🔹 Last Name
Required
Min length 1 or 2 char
Max length (example 32 character)
no espace 

🔹 Email
Required
Format  (example@mail.com)
Unrefined mail
Case insensitive

🔹Telephone Field

Required field (cannot be empty)
Should contain numeric values
May or may not accept:
+ sign (for international numbers)
Spaces
Dashes (-)

What you need to test:
Only numbers → should be accepted
Letters → should be rejected
Special characters → should be rejected
Very long number → check max length behavior
Empty field → should show validation error
This is called Validation Testing + Boundary Testing.


🔹 Password Field

Expected Rules:
Required
Must meet minimum length
Could be 4 characters (in demo)
Could be 8 characters (in real systems)
Has a maximum length

Usually:

No strict complexity rules in demo (no forced special characters)
What you need to test:
Less than minimum length → rejected
Exactly minimum length → accepted
Very long password → check system behavior
Only spaces → should be rejected
Common characters only → accepted

This is:

Validation Testing
Boundary Value Analysis

🔹 Confirm Password Field
Rule:

Must exactly match the Password field
Case-sensitive comparison (usually)

What to test:

Matching passwords → accepted
Different passwords → error message
One field empty → error
Trailing space difference → check behavior

This is:

Functional Testing
Negative Testing


## 4. Registration Module Analysis

### 4.1 Fields Identified
- First Name (Required)
- Last Name (Required)
- Email (Required)
- Telephone (Required)
- Password (Required)
- Confirm Password (Required)
- Newsletter (Optional)
- Privacy Policy (Mandatory Checkbox)

### 4.2 Business Rules
- Email must be unique
- Password must meet minimum length
- Confirm password must match
- Privacy policy must be accepted

### 4.3 Expected Success Flow
- Account created successfully
- User redirected to success page
- User automatically logged in
