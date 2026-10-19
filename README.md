# portswigger-web-security-labs
Hands-on web application security labs using Burp Suite to learn and develop knowledge.

#Server-side Vulnerabilities Path:
Difficulty - Apprentice
  Lab 1: Exploration of "Path Traversal"
  Use of '../../../etc/passwd' to access file storage by intercepting and modifying an image retrieval request
  Takeaway - how retrieval requests can be intercepted to retrieve other information on the same database without permission

  Lab 2: Unprotected Admin Functionality "Access Control"
  Exploit of "robots.txt" to find the "administrator-panel" directory to delete a user
  Takeaway - how hidden directories from users can be found using exploits, thereby accessing admin control without permission and when not protected

  Lab 3: Unprotected Admin Functionality with Unpredictable URL "Access Control"
  Exploit of inclusion of admin URL within the java script of the user UI
  Takeaway - Do not hold administrative URLs within public java script, and protect them
