# Demoblaze Bug Reports

## Information

**Website:** https://www.demoblaze.com/

**Testing Type:** Manual Testing

**Browser:** Firefox

**OS:** Windows

**Tester:** Shady

**Date:** 02.08.2026

---

# Bug Reports

## Bug ID: BR-001

**Summary:**

Checkout form accepts invalid data in the Credit Card field.

**Environment:**

- Browser: Firefox
- OS: Windows

**Preconditions:**

No authentication is required. User can access the checkout form.

**Steps to Reproduce:**

1. Open https://www.demoblaze.com/
2. Add any product to the cart.
3. Open the cart.
4. Click **"Place Order"**.
5. Enter letters in the **Credit Card** field.
6. Click **"Purchase"**.

**Expected Result:**

The system should reject invalid characters and display a validation message.

**Actual Result:**

The system accepts invalid characters and completes the purchase successfully.

**Severity:**

Medium

**Priority:**

Medium

---

## Bug ID: BR-002

**Summary:**

Selected product category is reset after changing the catalog page.

**Environment:**

- Browser: Firefox
- OS: Windows

**Preconditions:**

User is on the main catalog page.

**Steps to Reproduce:**

1. Open https://www.demoblaze.com/
2. Click the **"Phones"** category.
3. Click **"Next"** to open the next catalog page.

**Expected Result:**

The selected category should remain active after changing the page.

**Actual Result:**

The category filter is reset and all products are displayed.

**Severity:**

Medium

**Priority:**

Medium

---

## Bug ID: BR-003

**Summary:**

Long username breaks the layout after login.

**Environment:**

- Browser: Firefox
- OS: Windows

**Preconditions:**

User is registered with a very long username.

**Steps to Reproduce:**

1. Open https://www.demoblaze.com/
2. Register a new account with a very long username.
3. Log in using the created account.

**Expected Result:**

The username should be displayed correctly without breaking the page layout.

**Actual Result:**

The username extends beyond the visible area and breaks the page layout.

**Severity:**

Low

**Priority:**

Low

---

## Bug ID: BR-004

**Summary:**

Contact form accepts an invalid email address.

**Environment:**

- Browser: Firefox
- OS: Windows

**Preconditions:**

No authentication is required.

**Steps to Reproduce:**

1. Open https://www.demoblaze.com/
2. Click the **"Contact"** button.
3. Enter an invalid email address (for example: `abc`).
4. Click **"Send message"**.

**Expected Result:**

The system should validate the email format and display an error message.

**Actual Result:**

The message is sent successfully despite an invalid email address.

**Severity:**

Medium

**Priority:**

Medium
