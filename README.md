# networkwalks-B082-week3-Cybersecurity-lab-Password-Cracking
Cyber Security Home Lab Password Cracking Week 03



# WEEK 3 | PROJECT MODULE 1

# PASSWORD SECURITY AUDITING WITH JOHN THE RIPPER (JTR)

## Background

John the Ripper (JTR) is a widely used cybersecurity tool that helps security professionals assess the strength of passwords in authorized environments. Originally developed for Unix-based systems, JTR is now available for Windows, Linux, and macOS.

John the Ripper supports many password-hashing formats and can be used in controlled security laboratories to demonstrate how weak passwords may be vulnerable to automated password-guessing techniques. The purpose of using JTR in this laboratory is to understand password-security risks and learn how organizations can identify and improve weak password practices.

**Johnny** is a graphical user interface (GUI) for John the Ripper. It provides a simple point-and-click interface that makes password-security testing easier for beginners and students to understand.

This laboratory uses a **sample, authorized password-protected PDF** to demonstrate password-security assessment. The exercise is intended for educational and defensive purposes only. It helps students understand how password-protection mechanisms can be evaluated and why strong, unique passwords are essential for protecting digital information.

---

## Task

Perform a controlled password-security assessment of the attached sample PDF, **“My Locked PDF1.pdf,”** using **John the Ripper (JTR)** and **Johnny** on a Windows PC.

The objective is to recover the password **only from the authorized laboratory file** and understand how password complexity affects resistance to password-guessing attacks.

### Ethical Use and Authorization

Before performing the exercise, follow these rules:

* Use JTR only on files, accounts, or systems for which you have explicit authorization.
* Use only the PDF provided for this laboratory exercise.
* Do not attempt to crack passwords belonging to other individuals.
* Do not use these techniques to access confidential, personal, or unauthorized information.
* Keep any recovered password and password hashes within the approved laboratory environment.
* Do not upload sensitive or personal documents to third-party websites.
* Follow your institution's cybersecurity, privacy, and acceptable-use policies.

Unauthorized password cracking may violate organizational policies and applicable laws.

---

# Related Information

If you are using **Kali Linux**, John the Ripper may already be installed and available from the system.

For Windows users, JTR can be downloaded from an official and trusted source.

---

# PROCEDURE

## STEP 1 — Download John the Ripper

Download John the Ripper from the official Openwall website:

[John the Ripper — Official Openwall Website](https://www.openwall.com/john/?utm_source=chatgpt.com)

Alternatively, an approved laboratory distribution may be used if it has been provided by your instructor or institution.

After downloading:

1. Install or extract John the Ripper according to the instructions provided with the package.
2. Open the JTR installation directory.
3. Locate the `run` folder.
4. Verify that the `john.exe` application is available.

**Security Awareness:**
Always obtain cybersecurity tools from trusted and verified sources. Avoid downloading executable security tools from unknown websites because modified software may contain malware.

---

# STEP 2 — Install Johnny GUI

Johnny provides a graphical interface for John the Ripper and is useful for students who are learning password-security auditing.

Download information for Johnny from Openwall:

[Johnny GUI — Openwall Information](https://openwall.info/wiki/john/johnny?utm_source=chatgpt.com)

After installing Johnny:

1. Launch the Johnny application.
2. Open the application settings.
3. Locate the option for selecting the John the Ripper executable.
4. Browse to the JTR installation directory.
5. Select the authorized `john.exe` file located in the `run` folder.
6. Save or confirm the configuration.

Johnny should now be configured to work with your John the Ripper installation.

---

# STEP 3 — Prepare the Laboratory Password Hash

Use only the **authorized sample PDF** supplied for this exercise.

A password-protected PDF does not normally expose its password as plain text. Instead, password-verification information can be extracted and used for security auditing.

For this laboratory, use an **instructor-provided hash** or an approved local method for generating the test hash.

If your instructor has provided a test hash:

1. Open Notepad or another text editor.
2. Paste the authorized laboratory hash.
3. Check that the hash has not been accidentally modified.
4. Save the file as:

`hash1.txt`

5. Store the file inside your designated laboratory folder.

### Privacy Precaution

Do **not** upload confidential, personal, company, academic, or otherwise sensitive PDFs to public online hash-extraction services.

If your instructor specifically requires an online service for this exercise, use **only the supplied non-sensitive laboratory PDF** and follow your institution's privacy requirements.

---

# STEP 4 — Load the Laboratory Hash in Johnny

Open Johnny and use the password-file option to load the authorized laboratory hash.

1. Select **Open Password File**.
2. Browse to `hash1.txt`.
3. Select the file and open it.
4. Confirm that the laboratory hash has been loaded correctly.
5. Select **Start New Attack** to begin the password-security assessment.

The assessment may take different amounts of time depending on the computer's processing capability and the strength and complexity of the test password.

This demonstrates an important cybersecurity principle:

> The stronger and more complex a password is, the more difficult it generally becomes for automated password-guessing techniques to identify it.

---

# STEP 5 — Verify the Laboratory Result

If the authorized laboratory password is successfully identified:

1. Record the result only if it is required for your laboratory report.
2. Open the supplied sample PDF.
3. Enter the recovered laboratory password.
4. Confirm that the document opens successfully.
5. Close the document after verification.

Do not use the recovered password anywhere outside the authorized laboratory environment.

After completing the exercise, remove temporary password hashes and recovered credentials if required by your instructor or laboratory policy.

---

# Security Awareness

This exercise demonstrates why password security is important.

### 1. Avoid Weak Passwords

Short, predictable, and commonly used passwords are generally easier for automated password-guessing techniques to test.

### 2. Use Long and Unique Passwords

Long passwords or passphrases provide better protection than short and predictable passwords.

### 3. Never Reuse Important Passwords

Using the same password across multiple services increases the potential impact if that password is compromised.

### 4. Enable Multi-Factor Authentication

Where available, multi-factor authentication (MFA) provides an additional layer of protection beyond the password.

### 5. Protect Password Hashes

Password hashes and recovered passwords should be treated as sensitive security information. They should not be publicly shared or stored unnecessarily.

### 6. Use Security Tools Responsibly

John the Ripper is a legitimate security-auditing tool, but its use must remain within an authorized scope.

Security professionals may use password-auditing tools for:

* Authorized penetration testing
* Security assessments
* Cybersecurity education
* Password-strength testing
* Incident response and digital forensics
* Controlled laboratory exercises

The same techniques must **not** be used to gain unauthorized access to another person's files, accounts, devices, or systems.

---

# Learning Outcomes

After completing this laboratory, students should be able to:

1. Explain the purpose of John the Ripper and Johnny.
2. Understand the basic concept of password auditing.
3. Explain how password complexity affects security.
4. Identify the risks associated with weak and reused passwords.
5. Understand the importance of authorization when performing security testing.
6. Recognize privacy risks associated with uploading files or hashes to online services.
7. Apply ethical principles when using cybersecurity tools.
8. Recommend stronger password-security practices.

---

# Conclusion

This laboratory demonstrates how John the Ripper and Johnny can be used as **defensive cybersecurity tools** to evaluate password strength in an authorized environment.

The main objective is not simply to recover a password, but to understand the security risks associated with weak passwords and the importance of responsible password management.

Users should protect their information by using long and unique passwords, avoiding password reuse, enabling multi-factor authentication, and protecting password-related information.

Most importantly, password-auditing techniques should only be performed on systems and files for which **explicit authorization has been provided**.

**End of Laboratory Exercise**





---

# Security & Ethical Use





This laboratory is intended strictly for education, experimentation, and authorized security testing.

All scanning, vulnerability assessment, exploitation, and other security-testing activities should be performed only against systems that are owned by the tester or for which explicit permission has been obtained.

The isolated laboratory environment should be used as the primary environment for practicing cybersecurity techniques and testing security tools.




Author RITESH KUKROLIA 


LinkedIn: https://www.linkedin.com/in/ritesh-kukrolia/ 




Instructor Waqas Karim CCIE Cybersecurity Professional B082 


LinkedIn: https://www.linkedin.com/in/waqaskarim/
