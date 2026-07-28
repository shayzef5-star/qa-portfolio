# Form Authentication

## Information

**Website:** https://the-internet.herokuapp.com/login

**Module:** Authentication

**Author:** Shady

**Date:** 28.07.2026

---

# Test Cases

## TC-001 — Login with valid credentials

**Preconditions**

* User is on the Login page.

**Steps**

1. Enter a valid username.
2. Enter a valid password.
3. Click the **Login** button.

**Expected Result**

The user is successfully logged in and redirected to the secure area.

---

## TC-002 — Login with invalid password

**Preconditions**

* User is on the Login page.

**Steps**

1. Enter a valid username.
2. Enter an invalid password.
3. Click the **Login** button.

**Expected Result**

The user cannot log in. An error message is displayed.

---

## TC-003 — Login with invalid username

**Preconditions**

* User is on the Login page.

**Steps**

1. Enter an invalid username.
2. Enter a valid password.
3. Click the **Login** button.

**Expected Result**

The user cannot log in. An error message is displayed.

---

## TC-004 — Login with empty username

**Preconditions**

* User is on the Login page.

**Steps**

1. Leave the **Username** field empty.
2. Enter a valid password.
3. Click the **Login** button.

**Expected Result**

The user cannot log in. An error message is displayed.

---

## TC-005 — Login with empty password

**Preconditions**

* User is on the Login page.

**Steps**

1. Enter a valid username.
2. Leave the **Password** field empty.
3. Click the **Login** button.

**Expected Result**

The user cannot log in. An error message is displayed.

---

## TC-006 — Login with a leading space in the username

**Preconditions**

* User is on the Login page.

**Steps**

1. Enter a valid username with a leading space.
2. Enter a valid password.
3. Click the **Login** button.

**Expected Result**

The user cannot log in. An error message is displayed.

---

## TC-007 — Login with a trailing space in the password

**Preconditions**

* User is on the Login page.

**Steps**

1. Enter a valid username.
2. Enter a valid password with a trailing space.
3. Click the **Login** button.

**Expected Result**

The user cannot log in. An error message is displayed.

---

## TC-008 — Login with empty username and password

**Preconditions**

* User is on the Login page.

**Steps**

1. Leave both **Username** and **Password** fields empty.
2. Click the **Login** button.

**Expected Result**

The user cannot log in. An error message is displayed.

---

## TC-009 — Login with invalid username and invalid password

**Preconditions**

* User is on the Login page.

**Steps**

1. Enter an invalid username.
2. Enter an invalid password.
3. Click the **Login** button.

**Expected Result**

The user cannot log in. An error message is displayed.

---

## TC-010 — Login with a very long username

**Preconditions**

* User is on the Login page.

**Steps**

1. Enter a username longer than the allowed limit.
2. Enter a valid password.
3. Click the **Login** button.

**Expected Result**

The user cannot log in. An error message is displayed.

---

## TC-011 — Login with a very long password

**Preconditions**

* User is on the Login page.

**Steps**

1. Enter a valid username.
2. Enter a password longer than the allowed limit.
3. Click the **Login** button.

**Expected Result**

The user cannot log in. An error message is displayed.

---

## TC-012 — Login using a copied username

**Preconditions**

* User is on the Login page.

**Steps**

1. Copy a valid username.
2. Paste it into the **Username** field.
3. Enter a valid password.
4. Click the **Login** button.

**Expected Result**

The user is successfully logged in.

---

## TC-013 — Login using a copied password

**Preconditions**

* User is on the Login page.

**Steps**

1. Enter a valid username.
2. Copy a valid password.
3. Paste it into the **Password** field.
4. Click the **Login** button.

**Expected Result**

The user is successfully logged in.

---

## TC-014 — Login using copied credentials

**Preconditions**

* User is on the Login page.

**Steps**

1. Copy a valid username.
2. Paste it into the **Username** field.
3. Copy a valid password.
4. Paste it into the **Password** field.
5. Click the **Login** button.

**Expected Result**

The user is successfully logged in.

---

## TC-015 — Login using the Enter key

**Preconditions**

* User is on the Login page.

**Steps**

1. Enter a valid username.
2. Enter a valid password.
3. Press **Enter** while the cursor is in the **Password** field.

**Expected Result**

The user is successfully logged in and redirected to the secure area.
