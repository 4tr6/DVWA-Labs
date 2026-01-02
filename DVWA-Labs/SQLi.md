# SQL Injection – DVWA (Low security)

## Description
SQL Injection vulnerability allows an attacker to manipulate database queries by injecting malicious SQL input.

## Steps
1. Open DVWA and set security level to Low.
2. Go to SQL Injection page.
3. Enter the following payload in User ID: 1' or '1'='1
4. Click Submit.

## Result
All users stored in the database were displayed.
## Proof
images/SQLi.png
