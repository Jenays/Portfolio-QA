# Negative Login Test Cases  

## TC-LOGIN-101 - Login with invalid password

**Title:** Login with invalid password  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** High  
**Status:** Approved  
**Defects:** -  
**Execution status:** Not Executed  
**Precondition:** User exists with valid username  

**Steps and Results:**  

| Step | Action                                      | Expected Result                                  |
|------|---------------------------------------------|--------------------------------------------------|
| 1    | Open login page                             | Login form is displayed                          |
| 2    | Enter valid username and invalid password   | Input is accepted                                |
| 3    | Click "Login"                               | Error message is displayed; login is not allowed |

**Postcondition:**  
User session is not created  


## TC-LOGIN-102 - Login with non-existing user

**Title:** Login with non-existing user  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** High  
**Status:** Approved  
**Defects:** -  
**Execution status:** Not Executed  
**Precondition:** User does not exist  

**Steps and Results:**  

| Step | Action                                         | Expected Result                                  |
|------|------------------------------------------------|--------------------------------------------------|
| 1    | Open login page                                | Login form is displayed                          |
| 2    | Enter non-existing username and any password   | Input is accepted                                |
| 3    | Click "Login"                                  | Error message is displayed; login fails          |

**Postcondition:**  
User session is not created  


## TC-LOGIN-103 - Login with empty fields

**Title:** Login with empty username and password  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** High  
**Status:** Approved  
**Defects:** -  
**Execution status:** Not Executed  
**Precondition:** Login page is open  

**Steps and Results:**  

| Step | Action                              | Expected Result                                      |
|------|-------------------------------------|------------------------------------------------------|
| 1    | Open login page                     | Login form is displayed                              |
| 2    | Leave username and password empty   | Fields remain empty                                  |
| 3    | Click "Login"                       | Validation error is displayed; login is not performed|

**Postcondition:**  
User session is not created  


## TC-LOGIN-104 - Login with empty password

**Title:** Login with empty password  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** Medium  
**Status:** Approved  
**Defects:** -  
**Execution status:** Not Executed  
**Precondition:** Login page is open  

**Steps and Results:**  

| Step | Action                                         | Expected Result                                      |
|------|------------------------------------------------|------------------------------------------------------|
| 1    | Open login page                                | Login form is displayed                              |
| 2    | Enter valid username and leave password empty  | Input is partially accepted                          |
| 3    | Click "Login"                                  | Validation error is displayed for password field     |

**Postcondition:**  
User session is not created  


## TC-LOGIN-105 - Login with empty username

**Title:** Login with empty username  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** Medium  
**Status:** Approved  
**Defects:** -  
**Execution status:** Not Executed  
**Precondition:** Login page is open  

**Steps and Results:**  

| Step | Action                                         | Expected Result                                      |
|------|------------------------------------------------|------------------------------------------------------|
| 1    | Open login page                                | Login form is displayed                              |
| 2    | Leave username empty and enter valid password  | Input is partially accepted                          |
| 3    | Click "Login"                                  | Validation error is displayed for username field     |

**Postcondition:**  
User session is not created  


## TC-LOGIN-106 - Login with incorrect credentials format

**Title:** Login with incorrect credentials format  
**Section:** Login_Form  
**Type:** Functional  
**Priority:** Low  
**Status:** Approved  
**Defects:** -  
**Execution status:** Not Executed  
**Precondition:** Login page is open  

**Steps and Results:**  

| Step | Action                                           | Expected Result                                      |
|------|--------------------------------------------------|------------------------------------------------------|
| 1    | Open login page                                  | Login form is displayed                              |
| 2    | Enter invalid format username (e.g. spaces only) | Input is accepted or restricted                      |
| 3    | Click "Login"                                    | Validation or error message is displayed; login fails|

**Postcondition:**  
User session is not created
