# Localization Test Cases  

## TC-L10N-001 - UI language detection based on browser settings

**Title:** UI language detection based on browser settings  
**Section:** Login_Form  
**Type:** Usability / Localization  
**Priority:** Medium  
**Status:** Draft  
**Defects:** [DEF-002](../../Bug_Reports/DEF-002-Language-detection.md)  
**Execution status:** Not Executed  
**Precondition:** Browser language is set to Spanish (es-ES); user is not logged in  

**Steps and Results:**  

| Step | Action                          | Expected Result                                                   |
|------|---------------------------------|-------------------------------------------------------------------|
| 1    | Open login page                 | UI is displayed in Spanish                                         |
| 2    | Observe labels and buttons      | "Username", "Password", "Login" are translated (e.g., "Usuario", "Contraseña", "Iniciar sesión") |

**Postcondition:**  
Login form is displayed in browser language  

---

## TC-L10N-002 - Error message consistency after language change

**Title:** Error message consistency after language change  
**Section:** Login_Form  
**Type:** Functional / Localization  
**Priority:** High  
**Status:** Draft  
**Defects:** -  
**Execution status:** Not Executed  
**Precondition:** Application supports English and French; user exists  

**Steps and Results:**  

| Step | Action                                        | Expected Result                                      |
|------|-----------------------------------------------|------------------------------------------------------|
| 1    | Open login page (English)                     | UI is displayed in English                            |
| 2    | Switch language to French                     | UI updates to French                                  |
| 3    | Enter valid username and invalid password    | Input is accepted                                     |
| 4    | Click "Login"                                 | Error message appears in French (e.g., "Mot de passe incorrect") |

**Postcondition:**  
All error messages match the selected language  

---

## TC-I18N-003 - Input with accented characters

**Title:** Input with accented characters  
**Section:** Login_Form  
**Type:** Functional / Internationalization  
**Priority:** Medium  
**Status:** Draft  
**Defects:** -  
**Execution status:** Not Executed  
**Precondition:** System allows Latin characters with accents  

**Steps and Results:**  

| Step | Action                          | Expected Result                                     |
|------|---------------------------------|-----------------------------------------------------|
| 1    | Open login page                 | Login form is displayed                              |
| 2    | Enter username "josé123" and valid password | Input is accepted                            |
| 3    | Click "Login"                   | Login succeeds OR validation message is shown if unsupported |

**Postcondition:**  
System processes accented characters correctly  

---

## TC-L10N-004 - Layout validation for long French text

**Title:** Layout validation for long French text  
**Section:** Login_Form  
**Type:** UI / Localization  
**Priority:** Low  
**Status:** Draft  
**Defects:** -  
**Execution status:** Not Executed  
**Precondition:** Application supports French language  

**Steps and Results:**  

| Step | Action                          | Expected Result                                           |
|------|---------------------------------|-----------------------------------------------------------|
| 1    | Open login page                 | Login form is displayed                                    |
| 2    | Switch language to French       | Language is applied                                        |
| 3    | Observe "Login" button and labels | Button text (e.g., "Se connecter") is fully visible; no overlap or truncation |

**Postcondition:**  
UI layout remains stable with longer localized text  

---

## TC-I18N-005 - Unicode input with emoji or special symbols

**Title:** Unicode input with emoji or special symbols  
**Section:** Login_Form  
**Type:** Functional / Compatibility  
**Priority:** Medium  
**Status:** Draft  
**Defects:** -  
**Execution status:** Not Executed  
**Precondition:** Input fields accept Unicode characters  

**Steps and Results:**  

| Step | Action                          | Expected Result                                               |
|------|---------------------------------|---------------------------------------------------------------|
| 1    | Open login page                 | Login form is displayed                                        |
| 2    | Enter username "user😊" and valid password | Input is accepted or validation message is shown       |
| 3    | Click "Login"                   | Login fails or succeeds according to validation rules; no crash or encoding issues |

**Postcondition:**  
System handles special Unicode characters safely  
