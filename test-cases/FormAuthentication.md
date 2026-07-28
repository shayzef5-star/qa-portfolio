# Form Authentication

## Information

Website:
https://the-internet.herokuapp.com/login

Date:
28.07.2026

---

## Test Cases

### TC-001

**Title**

Login with valid credentials

**Steps**

1. Open Login page.
2. Enter valid username.
3. Enter valid password.
4. Click Login.

**Expected Result**

User is successfully logged in.

---

### TC-002

**Title**

Login with invalid password

**Steps**

1. Open Login page.
2. Enter valid username.
3. Enter invalid password.
4. Click Login.

**Expected Result**

Error message is displayed.

---

### TC-003

**Title**

Login with empty username

**Steps**

1. Open Login page.
2. Leave username empty.
3. Enter password.
4. Click Login.

**Expected Result**

User cannot log in.

---

### TC-004

**Title**

Login with empty password

**Steps**

1. Open Login page.
2. Enter username.
3. Leave password empty.
4. Click Login.

**Expected Result**

User cannot log in.

---

### TC-005

**Title**

Login with empty fields

**Steps**

1. Open Login page.
2. Leave both fields empty.
3. Click Login.

**Expected Result**

User cannot log in.
