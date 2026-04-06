# Login Form Test Cases

## Overview

This module contains a set of test cases designed to validate the functionality of the Login Form.  
The test suite covers positive, negative, and edge case scenarios to ensure correct behavior of the authentication process.

All test cases are written for demonstration purposes and may differ from real project standards.

---

## Structure

The folder includes the following files:

- [Positive Test Cases](Login_Positive.md) – contains positive test cases  
- [Negative Test Cases](Login_Negative.md) – contains negative test cases  
- [Edge Cases](Login_Edge_Cases.md) – contains edge case test scenarios  

---

## Test Coverage

### 1. Positive Scenarios
Covered in `Login_Positive.md`

These test cases verify that the system works correctly with valid input and expected user behavior.

Includes:
- Login with valid credentials  
- Login with "Remember me" functionality  
- Login using Enter key  
- Login using browser autofill  
- Login using copy-paste  
- Login after session timeout  

---

### 2. Negative Scenarios
Covered in `Login_Negative.md`

These test cases verify system behavior with invalid input and incorrect user actions.

Includes:
- Login with invalid password  
- Login with non-existing user  
- Login with empty fields  
- Login with empty password  
- Login with empty username  
- Login with incorrect credentials format  

---

### 3. Edge Cases
Covered in `Login_Edge_Cases.md`

These test cases verify system behavior in boundary and uncommon scenarios.

Includes:
- Login with leading and trailing spaces  
- Login with case sensitivity variations  
- Login with maximum allowed input length  
- Multiple rapid clicks on Login button  

---
