## BUG_002 - Weak password is accepted without validation

Steps:
1. Open registration page
2. Enter valid email
3. Enter password "123"
4. Confirm password
5. Click "Register"

Expected result:
Validation error for weak password

Actual result:
System accepts weak password and registers user