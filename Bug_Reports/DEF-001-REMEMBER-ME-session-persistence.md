# DEF-001-REMEMBER-ME-session-persistence

| Field | Details |
|-------|---------|
| **Summary** | The "Remember me" functionality does not persist the user session after closing and reopening the browser. User is required to log in again. |
| **Related Test Case** | [TC-LOGIN-002 – Login with Remember me checked](../Test_Cases/Login_Form/Login_Positive.md#tc-login-002---login-with-remember-me-checked) |
| **Steps to Reproduce** | 1. Open login page<br>2. Enter valid username and password<br>3. Check the "Remember me" checkbox<br>4. Click "Login"<br>5. Close the browser completely<br>6. Reopen the browser and navigate to the application |
| **Expected Result** | User session should remain active and user should be automatically logged in. |
| **Actual Result** | User is logged out and redirected to the login page. |
| **Priority** | Medium |
| **Severity** | Major |
| **Status** | Selected for Development |
| **Environment** | - OS: Windows 11<br>- Browser: Chrome 146<br>- Platform: Web App |
| **Attachments** | - [screenshot](link-to-screenshot) *No actual screenshot provided.*<br>- [log from Chrome DevTools](link-to-logFile) *No actual log provided.* |
| **Labels** | Triage, Auth, Session |
| **Affected version** | v1.0 |
| **Fix version** | none |
| **Reported On** | April 2, 2026 |
| **Reported By** | John |
| **Assignee** | Unassigned |
