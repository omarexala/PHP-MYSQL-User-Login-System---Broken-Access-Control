# PHP-MYSQL-User-Login-System---Broken-Access-Control

Affected Web App: https://github.com/keerti1924/PHP-MYSQL-User-Login-System

Title: Broken Access Control with the help of SQL Injection

Affected Component: /edit.php

CWE-284: Improper Access Control

CVSS 3.1 Score: 7.1 (self - rated with the help of online CVSS calculator)

Impact: Broken Access Control poses a significant security risk, potentially leading to unauthorized access and compromising the confidentiality, integrity, and availability of sensitive data. This vulnerability can result in privacy breaches, data manipulation, and account takeovers, exposing users to various risks. Robust access control measures and regular security assessments are essential to mitigate these impacts and ensure that only authorized users have appropriate access levels, preventing potential breaches and their associated consequences.

Proof of Concept: To reproduce this attack, signup as a new user and login. Update your username and add an SQL payload: ' '# '. This will result to all usernames being updated.
![image](https://github.com/omarexala/PHP-MYSQL-User-Login-System---Broken-Access-Control/assets/159004359/d4828733-2c5e-4dbc-b788-2db62ec76327)

To further maximize this, this broken access control may lead to passwords being changed and other details of the website users.

Remediation: To remediate broken access control, establish and enforce precise access policies, implement Role-Based Access Control (RBAC), and ensure strong session management. Regularly audit and monitor user access, review logs, and set up alerts for suspicious activities. Strengthen authentication mechanisms and conduct thorough authorization checks. These measures collectively enhance system security, mitigating the risks associated with broken access control and safeguarding data integrity and user privacy.
