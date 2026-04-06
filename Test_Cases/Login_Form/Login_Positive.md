# Positive Login Test Cases  

## TC-LOGIN-001 - Login with valid credentials

**Title:** Login with valid credentials  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** High  
**Status:** Approved  
**Defects:** -  
**Execution status:** Passed  
**Precondition:** User must exist and have valid login credentials  
  
**Steps and Results:**  

| Step | Action                            | Expected Result                                    |
|------|-----------------------------------|----------------------------------------------------|
| 1    | Open login page                   | Login form is displayed                            |
| 2    | Enter valid username and password | Input is accepted                                  |
| 3    | Click "Login"                     | User is redirected to dashboard with valid session |

**Postcondition:**
User session is active; Access is granted

---

## TC-LOGIN-002 - Login with Remember me checked 

**Title:** Login with Remember me checked  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** Medium  
**Status:** Approved  
**Defects:** [DEF-001](../../Bug_Reports/DEF-001-REMEMBER-ME-session-persistence.md)  
**Execution status:** Failed  
**Precondition:** User must exist check the "Remember me" on login form  
  
**Steps and Results:**  
  
| Step | Action | Expected Result | 
|------|-----------------------------------|-----------------------------------------------------------------------| 
| 1 | Open login page | Login form is displayed | 
| 2 | Enter valid username and password | Input is accepted | 
| 3 | Check the "Remember me" box | Checkbox is selected; login session will persist after browser closed | 
| 4 | Click "Login" | User is redirected to dashboard with valid session | 
| 5 | Reopen browser | User session is active | 
  
**Postcondition:** User session is active after closing a browser  

---
  
## TC-LOGIN-003 - Login using Enter key  

**Title:** Login using Enter key  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** Medium  
**Status:** Approved  
**Defects:** -  
**Execution status:** Passed  
**Precondition:** User exists and is on login page  

**Steps and Results:**  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Open login page | Login form is displayed |
| 2 | Enter valid username and password | Credentials are entered successfully |
| 3 | Press Enter key | User is logged in and redirected to dashboard |

**Postcondition:**  
User session is active  

---

## TC-LOGIN-004 - Login using browser autofill  

**Title:** Login using browser autofill  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** Low  
**Status:** Approved  
**Defects:** -  
**Execution status:** Passed  
**Precondition:** Credentials are saved in browser  

**Steps and Results:**  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Open login page | Login form is displayed |
| 2 | Use browser autofill | Username and password fields are filled correctly |
| 3 | Click "Login" | User is redirected to dashboard; session is created |

**Postcondition:**  
User session is active  

---

## TC-LOGIN-005 - Login using copy-paste  

**Title:** Login using copy-paste credentials  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** Low  
**Status:** Approved  
**Defects:** -  
**Execution status:** Passed  
**Precondition:** Valid credentials are available  

**Steps and Results:**  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Open login page | Login form is displayed |
| 2 | Paste username and password | Credentials are inserted correctly |
| 3 | Click "Login" | User is redirected to dashboard; session is created |

**Postcondition:**  
User session is active  

---

## TC-LOGIN-006 - Login after session timeout  

**Title:** Login after session timeout  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** High  
**Status:** Approved  
**Defects:** -  
**Execution status:** Passed  
**Precondition:** Previous session has expired  

**Steps and Results:**  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Open login page | Login form is displayed |
| 2 | Enter valid username and password | Credentials are entered successfully |
| 3 | Click "Login" | User is authenticated; new session is created; dashboard is displayed |

**Postcondition:**  
New user session is active  
