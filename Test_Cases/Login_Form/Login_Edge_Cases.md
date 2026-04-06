# Login Edge Case Test Cases  

## TC-LOGIN-201 - Login with leading and trailing spaces

**Title:** Login with leading and trailing spaces  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** Medium  
**Status:** Approved  
**Defects:** -  
**Execution status:** Not Executed  
**Precondition:** User exists with valid credentials  

**Steps and Results:**  

| Step | Action                                              | Expected Result                                              |
|------|-----------------------------------------------------|--------------------------------------------------------------|
| 1    | Open login page                                     | Login form is displayed                                      |
| 2    | Enter username and password with leading/trailing spaces | Spaces are trimmed or handled correctly                 |
| 3    | Click "Login"                                       | User is logged in successfully or receives clear validation |

**Postcondition:**  
System handles spaces correctly; behavior is consistent  


## TC-LOGIN-202 - Login with case sensitivity check

**Title:** Login with different case in username/password  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** Medium  
**Status:** Approved  
**Defects:** -  
**Execution status:** Not Executed  
**Precondition:** User exists with known credentials  

**Steps and Results:**  

| Step | Action                                           | Expected Result                                              |
|------|--------------------------------------------------|--------------------------------------------------------------|
| 1    | Open login page                                  | Login form is displayed                                      |
| 2    | Enter username/password with different letter case | System processes case sensitivity according to requirements |
| 3    | Click "Login"                                    | Login succeeds or fails consistently with system rules       |

**Postcondition:**  
Case sensitivity is handled correctly  


## TC-LOGIN-203 - Login with maximum allowed input length

**Title:** Login with maximum allowed input length  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** Medium  
**Status:** Approved  
**Defects:** -  
**Execution status:** Not Executed  
**Precondition:** System defines max length for fields  

**Steps and Results:**  

| Step | Action                                              | Expected Result                                      |
|------|-----------------------------------------------------|------------------------------------------------------|
| 1    | Open login page                                     | Login form is displayed                              |
| 2    | Enter username and password at maximum allowed length | Input is accepted without truncation errors         |
| 3    | Click "Login"                                       | Login is processed correctly                         |

**Postcondition:**  
System correctly handles max-length input  


## TC-LOGIN-204 - Multiple rapid clicks on Login button

**Title:** Multiple rapid clicks on Login button  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** Medium  
**Status:** Approved  
**Defects:** -  
**Execution status:** Not Executed  
**Precondition:** User enters valid credentials  

**Steps and Results:**  

| Step | Action                                | Expected Result                                      |
|------|---------------------------------------|------------------------------------------------------|
| 1    | Open login page                       | Login form is displayed                              |
| 2    | Enter valid username and password     | Input is accepted                                    |
| 3    | Click "Login" multiple times rapidly  | Only one request is processed; no duplicate sessions |

**Postcondition:**  
Only one session is created; system remains stable  
