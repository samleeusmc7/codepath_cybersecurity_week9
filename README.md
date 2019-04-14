# Project 8 - Pentesting Live Targets

Time spent: **10** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQL Injection (SQLi)
  - GIF - https://imgur.com/Kr9MqF9
    - First go to the blue target web page
    - Then at the top click on (Find a Salesperson)
    - Next click on any name and in the url change the number to an apostrophe (')
    - Database Query Failed

Vulnerability #2: __________________


## Green

Vulnerability #1: Username Enumeration

  - GIF - https://imgur.com/PmjXaVZ
    - First go to the green target web page
    - Then type in any username and password
    - Next open up a red/blue target web page
    - Then type in any username and password
    - The text "Log in was unsuccessful" is in BOLD for red/blue target web page
    - However the text "Log in was unsuccesful" is not in bold for the green target web page

Vulnerability #2: __________________


## Red

Vulnerability #1: XSS attack

  - GIF - https://imgur.com/IJDixMD

Vulnerability #2: Insecure Direct Object Reference (IDOR)
  - GIF - https://imgur.com/GsbMWbH


## Notes

Describe any challenges encountered while doing the work
