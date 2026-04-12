## BUG_001 - Login allows invalid email format

Steps:
1. Open login page
2. Enter email without "@" (example: testemail.com)
3. Enter any password
4. Click "Login"

Expected result:
Validation error message should be displayed

Actual result:
System accepts invalid email and proceeds