# SQL Injection – Security Test Cases

---

- **Note**: These test cases simulate malicious input patterns to verify that the system is protected against SQL injection attacks.

---

## TC-SQL-101 – Basic SQL injection in login form

**Title:** Attempt login using `' OR '1'='1`  
**Type:** Security  
**Priority:** High  
**Status:** Approved  
**Execution Status:** Passed  
**Automation:** Automation Queue  
**Preconditions:** Login form must be active  

| Step | Action | Expected Result |
|------|-------|----------------|
| 1 | Open login page | Form is displayed |
| 2 | Enter `' OR '1'='1` as username | Input accepted |
| 3 | Enter any password | Input accepted |
| 4 | Click “Login” | Login fails, error shown |

**Postconditions:**  
No authentication granted  

**Expected Result:**  
System blocks injection and logs attempt  

---

## TC-SQL-102 – SQL injection in password field

**Title:** Attempt injection in password input  
**Type:** Security  
**Priority:** High  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Automation Queue  
**Preconditions:** Login form must be active  

| Step | Action | Expected Result |
|------|-------|----------------|
| 1 | Enter valid username | Username accepted |
| 2 | Enter `' OR '1'='1` in password field | Input accepted |
| 3 | Click “Login” | Authentication fails |

**Postconditions:**  
Access is denied  

**Expected Result:**  
System sanitizes password input and prevents injection  

---

## TC-SQL-103 – SQL injection in numeric ID field

**Title:** Inject SQL into numeric parameter  
**Type:** Security  
**Priority:** Medium  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual Only  
**Preconditions:** Page contains numeric ID parameter  

| Step | Action | Expected Result |
|------|-------|----------------|
| 1 | Modify URL parameter to `id=10 OR 1=1` | Request processed safely |

**Postconditions:**  
No extra data returned  

**Expected Result:**  
System validates numeric input and blocks injection  

---

## TC-SQL-104 – SQL injection in filter parameters

**Title:** Attempt injection through filtering inputs  
**Type:** Security  
**Priority:** Medium  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual Only  
**Preconditions:** Page contains filter or sorting parameters  

| Step | Action | Expected Result |
|------|-------|----------------|
| 1 | Enter `' OR '1'='1` into filter field | Input sanitized |
| 2 | Apply filter | Results remain correct |

**Postconditions:**  
System returns normal filtered data  

**Expected Result:**  
Filtering mechanism prevents SQL execution  

---

## TC-SQL-105 – SQL injection using UNION query

**Title:** Attempt UNION-based SQL injection  
**Type:** Security  
**Priority:** High  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual Only  
**Preconditions:** Page queries database for content  

| Step | Action | Expected Result |
|------|-------|----------------|
| 1 | Enter payload `' UNION SELECT NULL--` into input field | Request processed safely |

**Postconditions:**  
No unauthorized data exposure  

**Expected Result:**  
System blocks UNION-based injection attempts  
