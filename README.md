# Browser Extension Security Audit 
A practical security exercise to audit and verify the safety of extensions installed in the Google Chrome web browser.

## Project Overview
The objective of this task was to perform a security audit of my web browser's extensions. Since extensions run with permissions within the browser, they can pose a significant security risk. This project involved systematically reviewing each installed extension, analyzing its purpose, publisher, and permissions to ensure that it was legitimate, necessary, and safe.

## Audit Process
The audit followed a systematic, multi-step process for each extension:
1.  **Enumeration:** Listed all installed extensions from the `chrome://extensions` page.
2.  **Purpose Verification:** Confirmed that I recognized each extension and understood its function.
3.  **Trust Assessment:** Verified that the extensions were from reputable publishers (e.g., Bitwarden, Grammarly) or served a specific, known purpose (e.g., NexExamShield for exams).
4.  **Permission Review:** Mentally reviewed the permissions required by each extension and confirmed they aligned with its functionality.

## Audit Results
The audit concluded that the browser has a strong security posture with a minimal and clean set of extensions. **No malicious, suspicious, or unnecessary extensions were found.** All four installed extensions (Bitwarden, Grammarly, NexExamShield, and Sider) were verified as legitimate and serving a clear purpose. The full analysis is available in the `audit_report.md` file.

## Key Concepts & Learnings
* **Attack Surface Management:** This exercise demonstrated the importance of keeping a minimal set of browser extensions. A smaller number of extensions reduces the potential "attack surface" for the browser.
* **Trust but Verify:** The key takeaway was not about finding malware, but about the security practice of actively verifying all installed software. It's crucial to know what each extension does and why it's installed.
* **The Principle of Least Privilege:** I considered the permissions of each extension. For tools like password managers (Bitwarden) and AI assistants (Sider), high permissions are necessary, which makes trusting the publisher the most critical security consideration.
* **Context is Key:** An extension like `NexExamShield` might seem suspicious on a random person's computer, but in the context of academic requirements, it is legitimate. This shows that understanding the *purpose* of software is essential to judging its safety.

## Files in This Repository
* **`README.md`**: This detailed project report.
* **`audit_report.md`**: The specific findings from my browser extension audit.
* **`installed_extensions.png`**: A screenshot showing the list of audited extensions.
