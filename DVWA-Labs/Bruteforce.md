# Brute Force – DVWA (Low)

## Description
Brute Force attack attempts multiple passwords until the correct one is found.

## Steps
1. Set DVWA security level to Low.
2. Open Brute Force page.
3. Enter the following credentials:
Username: admin
Password: password
--The application is vulnerable to Brute Force attacks. Multiple login attempts were allowed without any restriction. By trying common passwords for the user "admin", valid credentials were successfully discovered-- example = admin, password, letmein 12345 
4. Click Login.

## Result
Login was successful without any restriction.

## Proof
![Bruteforce Result](DVWA-Labs/images/Bruteforce.png)
