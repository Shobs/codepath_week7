# codepath_week7
Wordpress vulnerability testing



WordPress 4.2 Stored XSS 
https://klikki.fi/adv/wordpress2.html

Allows a user to write html and javascript in a comment and have it executed remotely every time the page loads.

<script>alert(" Stored XSS ");</script>  was used in this instance.

![](commentXSS/screenshot.png)

