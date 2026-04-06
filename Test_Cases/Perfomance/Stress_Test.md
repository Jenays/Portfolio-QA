# Stress Test – Performance Test Cases

---

- **Note**: These test cases simulate extreme conditions to observe system behavior under stress.

---

## TC-STRESS-101 – High frequency API requests

**Title:** Send rapid API requests in short time  
**Type:** Performance  
**Priority:** High  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual / Automated  
**Preconditions:** API endpoints available  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Trigger 50+ API requests in 10 sec | Requests are processed or throttled |

**Postconditions:**  
System remains responsive  

**Expected Result:**  
No crashes or unhandled errors under load  

---

## TC-STRESS-102 – Large dataset rendering

**Title:** Load page with large dataset  
**Type:** Performance  
**Priority:** High  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual Only  
**Preconditions:** Page supports large data lists  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Load dataset with 1000+ records | Data renders without freeze |

**Postconditions:**  
UI remains usable  

**Expected Result:**  
Rendering is optimized (no lag or crash)  

---

## TC-STRESS-103 – Concurrent user actions

**Title:** Perform multiple actions simultaneously  
**Type:** Performance  
**Priority:** High  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual Only  
**Preconditions:** Multiple interactive elements available  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Click buttons rapidly while typing | Actions execute correctly |

**Postconditions:**  
No input loss  

**Expected Result:**  
System handles concurrent interactions without errors  

---

## TC-STRESS-104 – Rapid login/logout cycles

**Title:** Repeated login and logout actions  
**Type:** Performance  
**Priority:** Medium  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual / Automated  
**Preconditions:** User account exists  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Login and logout 10+ times quickly | Sessions handled correctly |

**Postconditions:**  
Session state remains consistent  

**Expected Result:**  
No authentication errors or lockups  

---

## TC-STRESS-105 – Background tab activity

**Title:** Keep app running in inactive tab  
**Type:** Performance  
**Priority:** Low  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual Only  
**Preconditions:** App opened in browser  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Leave app in background for 30+ min | No unexpected behavior |
| 2 | Return to tab | App resumes normally |

**Postconditions:**  
Session remains stable  

**Expected Result:**  
No data loss or forced reload  
