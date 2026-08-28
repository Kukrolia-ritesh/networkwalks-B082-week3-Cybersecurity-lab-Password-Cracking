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





# WEEK 3 | PROJECT MODULE 2

# PASSWORD SECURITY AWARENESS WITH NETWORKWALKS TOOLS

## Background

Password security is an important part of protecting digital information. Password-auditing techniques can be used by cybersecurity professionals to evaluate whether passwords and password-protected files are sufficiently protected.

A password-protected file may contain information that allows software to verify whether an entered password is correct. In some security-testing scenarios, this information can be represented as a password hash. Security professionals can analyze authorized password hashes to demonstrate the risks associated with weak or predictable passwords.

Files such as PDFs, ZIP archives, and Office documents can be protected with passwords. In a controlled cybersecurity laboratory, students can use a sample file and its corresponding test data to understand how password-security assessments work.

In this laboratory, Networkwalks tools are used to demonstrate the concept of password auditing through a web browser. The **Hash Calculator** can be used with an approved laboratory file to demonstrate how password-related test data may be obtained, while the **Password Cracker** demonstrates how weak test passwords can be identified through automated password-guessing techniques.

The purpose of this exercise is **education and security awareness**. It is designed to help students understand why weak passwords create security risks and why strong, unique passwords are important.

---

# Task

Perform a **controlled password-security assessment** of the attached laboratory PDF, **“My Locked PDF1.pdf,”** using the Networkwalks Hash Calculator and Password Cracker tools.

The exercise must be performed only on the **authorized sample file provided for the laboratory**.

The objective is to understand the principles of password auditing and demonstrate the importance of strong password protection.

---

# Ethical and Safety Requirements

Before beginning the exercise, observe the following requirements:

* Use the tools only for authorized educational or security-testing purposes.
* Use only the sample PDF supplied for this laboratory.
* Never attempt to recover passwords from another person's files or accounts without explicit authorization.
* Do not upload confidential, personal, academic, financial, or organizational documents to public websites.
* Do not use recovered passwords to access any account, system, or file outside the laboratory.
* Treat password hashes and recovered passwords as sensitive information.
* Follow your institution's cybersecurity, privacy, and acceptable-use policies.

**Important:** Password-auditing tools should be used only within an approved scope. Unauthorized password recovery may violate organizational policies and applicable laws.

---

# PROCEDURE

## STEP 1 — Obtain the Laboratory PDF

Download the **authorized sample PDF** supplied by your instructor or laboratory.

Use only the designated test file for this exercise.

If the laboratory provides the file through the Networkwalks project page, access it through the approved course materials.

[Networkwalks Project/Lab Page](https://networkwalks.com/project-task-lab-password-cracking-with-networkwalks-tools/?utm_source=chatgpt.com)

**Privacy Awareness:**
Do not substitute the laboratory file with a personal or confidential PDF.

---

## STEP 2 — Open the Networkwalks Hash Calculator

Open the Networkwalks Hash Calculator in a web browser using the approved laboratory resource:

[Networkwalks Hash Calculator](https://networkwalks.com/hash-calculator/?utm_source=chatgpt.com)

The tool can be used to demonstrate how information associated with a password-protected **test file** may be represented for security analysis.

---

## STEP 3 — Process the Authorized Test File

If instructed by your course materials, select the supplied laboratory PDF in the Hash Calculator.

The tool may produce a password-related hash representation for the test file.

Use this functionality only with the **authorized laboratory sample**.

Do not upload files containing sensitive or personal information.

---

## STEP 4 — Record the Laboratory Hash

If a hash is generated:

1. Review the displayed value.
2. Copy the complete test hash if required for the exercise.
3. Ensure that the value has been copied accurately.
4. Store it only in the designated laboratory workspace.

The hash should be treated as **sensitive security information**, even though it is not the original password.

---

## STEP 5 — Open the Password-Auditing Tool

Open the Networkwalks Password Cracker through the approved laboratory resource:

[Networkwalks Password Cracker](https://networkwalks.com/password-cracker/?utm_source=chatgpt.com)

The tool is used in this exercise to demonstrate how automated password-guessing can expose **weak laboratory passwords**.

---

## STEP 6 — Perform the Authorized Assessment

If your instructor has approved the use of the generated test hash:

1. Enter the laboratory hash into the appropriate field.
2. Start the password-security assessment.
3. Allow the tool to process the authorized test data.
4. Observe the assessment process.

Do not enter hashes obtained from unauthorized sources.

The exercise demonstrates that automated techniques may be able to identify passwords that are short, common, predictable, or otherwise weak.

---

## STEP 7 — Analyze the Result

If the laboratory password is identified, record the result only when required for your coursework.

The amount of time required for an assessment can vary depending on factors such as:

* Password length
* Password complexity
* Character combinations
* Password predictability
* Available computing resources
* Testing method used

This demonstrates an important security principle: **weak passwords can provide insufficient protection against automated password-guessing techniques.**

---

## STEP 8 — Verify the Authorized PDF

Use the recovered laboratory password only to verify the supplied test PDF.

1. Open the authorized PDF.
2. Enter the laboratory password.
3. Confirm that the document opens successfully.
4. Close the document after verification.

Do not use the recovered password anywhere else.

---

# STEP 9 — Complete the Laboratory Securely

After completing the exercise:

1. Do not publish the recovered password or hash unnecessarily.
2. Remove temporary test files if required by your instructor.
3. Do not upload the recovered credentials to public websites.
4. Keep all laboratory information within the approved course environment.
5. Report any unexpected security or privacy issue to your instructor.

**The laboratory is complete once the password-security assessment has been successfully demonstrated and the security lessons have been documented.**

---

# Security Awareness

This exercise highlights several important cybersecurity principles.

### 1. Weak Passwords Create Security Risks

Passwords that are short, predictable, or commonly used may be more susceptible to automated guessing.

### 2. Strong Passwords Improve Protection

Long, unique passwords or passphrases generally provide stronger resistance against password-guessing techniques.

### 3. Password Reuse Should Be Avoided

Using the same password across multiple services can increase the impact of a single password compromise.

### 4. Multi-Factor Authentication Adds Protection

Where available, MFA should be enabled because it provides an additional security layer beyond the password.

### 5. Protect Password-Related Information

Hashes, passwords, and other authentication-related information should be handled carefully and should not be unnecessarily shared.

### 6. Online Tools Require Privacy Awareness

Before uploading a file to any online service, consider whether it contains confidential or personally identifiable information. For educational exercises, use only non-sensitive files specifically approved for online processing.

### 7. Authorization Is Essential

Password-auditing tools are legitimate cybersecurity tools when used for authorized testing, education, and security assessment. Using them against systems, files, or accounts without permission is not ethical security testing.

---

# Learning Outcomes

After completing this module, students should be able to:

1. Explain the purpose of password-security auditing.
2. Describe the basic concept of password hashes.
3. Explain how automated password-guessing techniques can expose weak passwords.
4. Identify characteristics of strong passwords.
5. Understand the privacy risks of uploading files to online services.
6. Recognize the importance of authorization when conducting security assessments.
7. Apply ethical principles when using cybersecurity tools.
8. Recommend appropriate measures for improving password security.

---

# Conclusion

This laboratory demonstrates the concept of password-security auditing using authorized sample data and browser-based security tools.

The primary objective is **security awareness rather than unauthorized password recovery**. By observing how weak laboratory passwords may be identified, students can better understand the importance of strong and unique passwords.

To protect digital information, users should use long and unique passwords, avoid password reuse, enable multi-factor authentication where possible, and protect password-related information.

All password-security testing must be conducted **only with explicit authorization and within a clearly defined laboratory or testing scope**.

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
