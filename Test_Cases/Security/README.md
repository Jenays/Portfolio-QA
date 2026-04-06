# SQL Injection – Test Module Overview

This file contains test cases focused on verifying that the application is protected against SQL injection attacks. The goal is to ensure that all user inputs are properly validated, sanitized, and do not allow unauthorized interaction with the database.

---

-  **Note**: The test cases in this repository are provided as examples only. Each software project may have its own conventions regarding test case structure, required fields, naming formats, documentation standards, and writing style. These samples reflect one possible approach and are not intended as the only correct format.

---

## Structure

- [SQL_Injection.md](./SQL_Injection.md) - test cases covering SQL injection attempts

---

## Scope

Test cases cover:

- Injection attempts in authentication forms (login/password)
- SQL injection via URL and numeric parameters  
- Injection through filters and user inputs  
- UNION-based injection techniques  
- Input validation and sanitization mechanisms  
