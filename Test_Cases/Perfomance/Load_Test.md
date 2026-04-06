# Load Test – Performance Test Cases

---

- **Note**: These test cases simulate typical user load to evaluate system responsiveness and stability.

---

## TC-LOAD-101 – API response time under normal load

**Title:** Measure API response time with regular traffic  
**Type:** Performance  
**Priority:** High  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual / Automated  
**Preconditions:** API available and stable  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Send standard API request | Response received within acceptable time (≤ 1 sec) |

**Postconditions:**  
API remains stable  

**Expected Result:**  
Consistent response time under normal load  

---

## TC-LOAD-102 – Pagination performance

**Title:** Navigate through paginated data  
**Type:** Performance  
**Priority:** Medium  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual Only  
**Preconditions:** Page contains paginated list  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Switch between pages (1→5) | Pages load quickly without delay |

**Postconditions:**  
Navigation remains smooth  

**Expected Result:**  
Pagination does not cause lag  

---

## TC-LOAD-103 – File download under moderate usage

**Title:** Download file while multiple users are active  
**Type:** Performance  
**Priority:** Medium  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual Only  
**Preconditions:** File available for download  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Start file download | Download begins immediately |
| 2 | Simulate other active users | Download speed remains stable |

**Postconditions:**  
File downloads successfully  

**Expected Result:**  
No interruptions or failures  

---

## TC-LOAD-104 – Navigation between pages

**Title:** Switch between multiple pages under load  
**Type:** Performance  
**Priority:** Medium  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual Only  
**Preconditions:** Multiple pages available  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Navigate across 5+ pages | Each page loads within acceptable time |

**Postconditions:**  
Navigation remains responsive  

**Expected Result:**  
No delays or broken transitions  

---

## TC-LOAD-105 – Notification delivery under load

**Title:** Receive notifications during normal system load  
**Type:** Performance  
**Priority:** Low  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual / Automated  
**Preconditions:** Notifications enabled  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Trigger notification event | Notification is generated |
| 2 | Observe delivery time | Notification appears promptly |

**Postconditions:**  
User receives notification  

**Expected Result:**  
Notifications delivered without delay or loss  
