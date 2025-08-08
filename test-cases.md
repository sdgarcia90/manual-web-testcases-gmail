# Manual Test Cases – Gmail Web

---

## Test Case 1: Login with valid credentials
- **Test ID**: TC001
- **Module**: Login
- **Preconditions**: User is on Gmail login page
- **Test Steps**:
  1. Enter valid email
  2. Click "Next"
  3. Enter valid password
  4. Click "Login"
- **Expected Result**: User is successfully logged in and redirected to the inbox.

---

## Test Case 2: Login with incorrect password
- **Test ID**: TC002
- **Module**: Login
- **Preconditions**: User is on Gmail login page
- **Test Steps**:
  1. Enter valid email
  2. Click "Next"
  3. Enter incorrect password
  4. Click "Login"
- **Expected Result**: Error message: "Wrong password. Try again or click Forgot password."

---

## Test Case 3: Compose and send an email
- **Test ID**: TC003
- **Module**: Compose Email
- **Preconditions**: User is logged in
- **Test Steps**:
  1. Click "Compose"
  2. Enter recipient email
  3. Enter subject and message
  4. Click "Send"
- **Expected Result**: Email is sent successfully, appears in Sent folder.
