# codepath_week7
Wordpress vulnerability testing


EXPLOIT #1
------------------------------------------------------------
VULNERABILITY:
WordPress <= 4.2 - Unauthenticated Stored Cross-Site Scripting (XSS)
https://wpvulndb.com/vulnerabilities/7945
https://klikki.fi/adv/wordpress2.html

AFFECTED WP:
4.2     fixed in version 4.2.1
4.1.2   fixed in version 4.2.1
4.1.1   fixed in version 4.2.1
3.9.3   fixed in version 4.2.1


CLASSIFICATION:
Type            XSS
OWASP Top 10    A3: Cross-Site Scripting (XSS)
CWE             CWE-79

DETAILS:
Allows a user to write html and javascript in a comment and have it executed remotely every time the page loads.

<script>alert(" Stored XSS ");</script>  was used in this instance.

IMAGES:
![](commentXSS/screenshot.png)
------------------------------------------------------------


------------------------------------------------------------

