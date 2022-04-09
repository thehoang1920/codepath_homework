# Project 8 - Pentesting Live Targets

Time spent: **X** hours spent in total

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

Vulnerability #1: Session Hijacking



Description:
The blue site is vulnerable to hijacking attacks. Using the supplied public/hacktools/change_session_id.php tool, a session created in one browser was successfully used in a different

<img src="blue-vuln1.gif">

Vulnerability #2: SQL Injection

Description:
On the salesperson page, when you look through all the employee's page in the URL you notice how they all have id=__ . By replacing the ___ with ' OR SLEEP(5)=0--'. The URL's ending changes to %27%20OR%20SLEEP(5)=0--%27. The page then refreshes for a couple of seconds than loads to Daron Burke.

<img src="blue-vuln2.gif">

## Green

Vulnerability #1: __________________

Description:

<img src="green-vuln1.gif">

Vulnerability #2: __________________

Description:

<img src="green-vuln2.gif">


## Red

Vulnerability #1: __________________

Description:

<img src="red-vuln1.gif">

Vulnerability #2: __________________

Description:

<img src="red-vuln2.gif">


## Notes

Describe any challenges encountered while doing the work
