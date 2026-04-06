# WCAG Checks – Accessibility Test Cases  

## TC-WCAG-101 – Audio control

**Title:** Verify audio can be paused or stopped  
**Type:** Accessibility  
**Priority:** High  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual Only  
**Preconditions:** Page contains auto-playing audio  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Load page with audio | Audio starts playing |
| 2 | Locate audio controls | Controls are visible |
| 3 | Pause/stop audio | Audio stops immediately |

**Postconditions:**  
User can control audio playback  

**Expected Result:**  
Audio can be paused or stopped by user  

---

## TC-WCAG-102 – Captions for video

**Title:** Verify videos include captions  
**Type:** Accessibility  
**Priority:** High  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual Only  
**Preconditions:** Page contains video content  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Play video | Video starts |
| 2 | Enable captions | Captions appear synchronized |

**Postconditions:**  
Video content is accessible to hearing-impaired users  

**Expected Result:**  
All videos include accurate captions  

---

## ⏱️ TC-WCAG-103 – Adjustable time limits

**Title:** Verify user can extend or disable time limits  
**Type:** Accessibility  
**Priority:** Medium  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual Only  
**Preconditions:** Page has time-limited actions (e.g. session timeout)  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Trigger time-limited session | Timer starts |
| 2 | Wait for warning | Warning is displayed |
| 3 | Extend time | Time limit increases |

**Postconditions:**  
User retains session  

**Expected Result:**  
User can adjust or extend time limits  

---

## TC-WCAG-104 – Orientation support

**Title:** Verify content supports both portrait and landscape orientation  
**Type:** Accessibility  
**Priority:** Medium  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual Only  
**Preconditions:** App opened on mobile device  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | View page in portrait mode | Content displays correctly |
| 2 | Rotate device to landscape | Layout adapts without loss |

**Postconditions:**  
Content remains usable  

**Expected Result:**  
No restriction to a single orientation  

---

## TC-WCAG-105 – Text resizing

**Title:** Verify text can be resized up to 200% without loss of content  
**Type:** Accessibility  
**Priority:** High  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual Only  
**Preconditions:** Page contains text  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Increase browser zoom to 200% | Text scales up |
| 2 | Review layout | No content is cut off |

**Postconditions:**  
Text remains readable  

**Expected Result:**  
Content remains accessible at increased zoom  

---

## TC-WCAG-106 – Error identification

**Title:** Verify form errors are clearly identified  
**Type:** Accessibility  
**Priority:** High  
**Status:** Approved  
**Execution Status:** Not Executed  
**Automation:** Manual Only  
**Preconditions:** Page contains form inputs  

| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Submit empty/invalid form | Errors appear |
| 2 | Review error messages | Fields with errors are highlighted |

**Postconditions:**  
User can identify and fix errors  

**Expected Result:**  
Errors are clearly described and associated with inputs   
