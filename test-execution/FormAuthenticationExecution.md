# Form Authentication - Test Execution

## Information

**Website:** https://the-internet.herokuapp.com/login

**Date:** 29.07.2026

---

| ID | Test Case | Status | Notes |
|----|-----------|--------|-------|
| TC-001 | Login with valid credentials | Pass | User successfully logged in. |
| TC-002 | Login with invalid password | Pass | Error message displayed. |
| TC-003 | Login with invalid username | Pass | Error message displayed. |
| TC-004 | Login with empty username | Pass | Login was rejected. |
| TC-005 | Login with empty password | Pass | Login was rejected. |
| TC-006 | Login with a leading space in the username | Pass | Login was rejected. |
| TC-007 | Login with a trailing space in the password | Pass | Login was rejected. |
| TC-008 | Login with empty username and password | Pass | Login was rejected. |
| TC-009 | Login with invalid username and invalid password | Pass | Error message displayed. |
| TC-010 | Login with a very long username | Pass | Login was rejected. |
| TC-011 | Login with a very long password | Pass | Login was rejected. |
| TC-012 | Login using a copied username | Pass | Login successful. |
| TC-013 | Login using a copied password | Pass | Login successful. |
| TC-014 | Login using copied credentials | Pass | Login successful. |
| TC-015 | Login using the Enter key | Pass | Login successful. |
