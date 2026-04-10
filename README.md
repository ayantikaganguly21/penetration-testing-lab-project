# penetration-testing-lab-project
# Penetration Testing Assignment: OWASP Top 10

**Author:** Ayantika Gangopadhyay
**Roll No:** UG/02/BTCSECSF/2023/004
**Registration No:** AU/2023/0009110
**Section:** E
**Course:** Penetration Testing Lab

## 📌 Overview
This repository contains three web applications demonstrating OWASP Top 10 vulnerabilities and their secure remediations.

1. **Login System (PHP/MySQL):** SQL Injection -> Fixed with Prepared Statements.
2. **User Profile (Node.js/Express):** Broken Access Control (IDOR) -> Fixed with Session Authorization.
3. **Password Storage (Python/Flask):** Cryptographic Failure -> Fixed with Password Hashing.

## 🚀 Quick Setup

* **App 1 (PHP/SQLi):** Host the folder via XAMPP/WAMP. Create a local `test` DB with a `users` table.
* **App 2 (Node.js/IDOR):** Open terminal in folder. Run `npm install express`, then `node server.js`.
* **App 3 (Python/Crypto):** Open terminal in folder. Run `pip install flask werkzeug`, then `python app.py`.
