# DEF-002-Language-detection

| Field | Value |
|-------|-------|
| **Summary** | Application does not detect browser language correctly and displays UI in English instead of Spanish (es-ES). |
| **Related Test Case** | [TC-L10N-001 – UI language detection based on browser settings](../Test_Cases/Localization/Localization_Test_Cases.md#tc-l10n-001---ui-language-detection-based-on-browser-settings) |
| **Steps to Reproduce** | 1. Set browser language to Spanish (es-ES)<br>2. Ensure user is not logged in<br>3. Open login page<br>4. Observe UI language |
| **Expected Result** | UI should be displayed in Spanish |
| **Actual Result** | UI is displayed in English; localization is not applied |
| **Priority** | Medium |
| **Severity** | Major |
| **Status** | Selected for Development |
| **Environment** | - OS: Windows 11<br>- Browser: Chrome 146<br>- Platform: Web App |
| **Attachments** | - [screenshot](link-to-screenshot) *not provided*<br>- [log from Chrome DevTools](link-to-logFile) *not provided* |
| **Labels** | Triage, Localization, UI |
| **Affected version** | v1.0 |
| **Fix version** | none |
| **Reported On** | April 2, 2026 |
| **Reported By** | John |
| **Assignee** | Unassigned |
