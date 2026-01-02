# Cross-Site Scripting (XSS) – DVWA (Low)

## Description
XSS allows attackers to execute JavaScript code in the victim’s browser through user input.

## Steps
1. Set DVWA security level to Low.
2. Open XSS (Reflected) page.
3. Enter the following payload: <img src=x onerror=alert('XSS')>
4. Submit the input.

## Result
A JavaScript alert was executed successfully.

## Proof
![XSS Result](images/xss.png)
