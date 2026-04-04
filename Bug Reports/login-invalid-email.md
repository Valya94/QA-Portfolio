## Title
Login allows invalid email format

## Description
The system allows users to log in using an invalid email format (without "@"), which violates standard email validation rules.

## Steps to Reproduce
1. Open the website  
2. Enter an invalid email format (without "@")  
3. Enter a valid password  
4. Click the "Login" button  

## Actual Result
The system allows login with an invalid email format.

## Expected Result
The system should allow login only with a valid email format.

## Environment
OS: Windows 10  
Browser: Google Chrome  
Device: Laptop  

## Type
Functional  

## Severity
Major  

## Priority
High
