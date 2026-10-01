
# Hacker101 CTF - Cody's First Blog Writeup

## 1. Introduction to the Challenge and Objective
This write-up covers the resolution of the **Cody's First Blog** challenge from **Hacker101 CTF**. The primary objective is to analyze a beginner-friendly blogging web application, uncover common vulnerabilities such as SQL injection or broken access controls, and capture the hidden flags.

---

## 2. Reconnaissance & Surface Analysis
* **Core Functionality:** The site provided a simple platform for publishing and viewing blog posts, with administrative backend capabilities for content management.
* **Vulnerability Hunt:** Investigating inputs, error messages, and endpoint routing exposed flaws in how user-supplied data was processed and validated by the backend.

---

## 3. Exploitation Strategy
1. **Input Inspection:** Tested parameters for unexpected behavior or error disclosures to map database interactions and backend logic.
2. **Privilege Bypass / Injection:** Leveraged identified flaws to access restricted administrative panels or manipulate database queries.
3. **Flag Recovery:** Successfully retrieved the challenge flags by navigating the unlocked privileged areas.

---

## 4. Lessons Learned
* **Input Validation & Sanitization:** All user inputs must be strictly sanitized and parameterized to prevent injection vectors.
* **Secure Administration Interfaces:** Administrative dashboards must never rely on obscurity and should enforce rigid authentication and authorization controls.

---

## 5. References
* [Hacker101 CTF](https://hacker101.com/) - Official security challenge platform.
* [OWASP SQL Injection Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html)

---

## Acknowledgments
Special thanks to **HackerOne** and the creators of **Hacker101** for providing an exceptional platform for hands-on web security practice.

---

> 📝 **Note on Flags:** All flags in this repository have been replaced with the standard placeholder format (`^FLAG^xxxxxxxx...$FLAG$`) to comply with platform guidelines.
