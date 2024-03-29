# Project 8 - Pentesting Live Targets

Time spent: **4** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: SQLi

Description: We can force the website to be asleep by injecting a SQL sleep code line.

<img src="https://github.com/hoonman/cybersecurityWeek9/blob/main/blue1.gif">

Vulnerability #2: __________________

Description:

<img src="blue-vuln2.gif">

## Green

Vulnerability #1: XSS

Description: entering a XSS alert script allows for displaying alerts on admin page for feedback.

<img src="https://github.com/hoonman/cybersecurityWeek9/blob/main/green1.gif">

Vulnerability #2: User Enumeration

Description: entering the correct username gives the user hints that the username exists since the message becomes bolded when attempting to login with a username that already exists.

<img src="https://github.com/hoonman/cybersecurityWeek9/blob/main/green2.gif">


## Red

Vulnerability #1: Changing session IDs. URL / IDOR type attack

Description: changing the session ID redirects us to links that we are not supposed to have access to.
ID from 1-9 gives us normal salesperson information. 

<img src="https://github.com/hoonman/cybersecurityWeek9/blob/main/red1.gif">

Vulnerability #2: __________________

Description:

<img src="red-vuln2.gif">


## Notes

Describe any challenges encountered while doing the work

