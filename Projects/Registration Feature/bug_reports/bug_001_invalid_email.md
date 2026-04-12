## BUG_001 - Registration accepts invalid email format

Steps:
1. Open registration page
2. Enter email without "@"
3. Enter valid password
4. Confirm password
5. Click "Register"

Expected result:
Validation error should be displayed

Actual result:
System accepts invalid email and proceeds