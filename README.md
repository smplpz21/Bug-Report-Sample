# 🐞 Bug Report Portfolio – Web App QA Testing

**Project:** Buggy Cars Rating Web Application  
**Tested URL:** [https://buggy.justtestit.org](https://buggy.justtestit.org)  
**Reported by:** Sam Lopez  
**Date:** April 15, 2025  
**Environment:**
- **OS:** Windows 10  
- **Browser:** Chrome v135.0.7049.85 (64-bit)

---

## 📋 Summary

This project showcases a comprehensive manual bug reporting effort on the **Buggy Cars Rating** application. The bug reports include:

- Functional issues  
- Validation failures  
- UI inconsistencies  
- Navigation problems  
- Pagination & sorting errors  

A total of **16 bugs** were identified, categorized by severity and accompanied by clear reproduction steps, expected vs. actual results, and suggested behavior.  
Screen recordings were also captured for some bugs to provide better test evidence.

---

## 🗂️ Bug List

| Bug ID | Title                                                       | Severity | Status |
|--------|-------------------------------------------------------------|----------|--------|
| 001    | Registration allows whitespace-only names                   | Medium   | New    |
| 002    | Incorrect error when Last Name is cleared                   | Low      | New    |
| 003    | Missing author name after voting with a comment             | Medium   | New    |
| 004    | Pagination input not working                                | Medium   | New    |
| 005    | Sorting broken for Model/Rank columns                       | Medium   | New    |
| 006    | Can paginate beyond total number of pages                   | Medium   | New    |
| 007    | Broken image for Lancia Ypsilon                             | Low      | New    |
| 008    | Rank column sort not functioning properly                   | Low      | New    |
| 009    | Spacing issue in Author/Comment columns                     | Low      | New    |
| 010    | “Buggy Rating” header not clickable                         | Medium   | New    |
| 011    | Car image redirects to home page                            | Low      | New    |
| 012    | Table resets state after row details view                   | Medium   | New    |
| 013    | No redirect after login from registration page              | Medium   | New    |
| 014    | Logged-in users can re-access and use registration page     | Medium   | New    |
| 015    | Navbar flickers on page refresh                             | Low      | New    |
| 016    | Profile refresh redirects user to dashboard                 | Low      | New    |

---

## 🧪 Sample Bug Detail

### 🐞 BUG-001: Registration Allows Whitespace-Only Names

**Severity:** Medium  
**Priority:** Medium  

**Steps to Reproduce:**
1. Navigate to [Registration Page](https://buggy.justtestit.org/register)  
2. Enter a valid username  
3. Enter only spaces in First and Last Name fields  
4. Provide and confirm a valid password  
5. Click "Register"

**Actual Result:**  
Registration is successful despite whitespace-only names.

**Expected Result:**  
Validation should block submissions with whitespace-only values in required fields.

---

## 📄 Download Full Report

➡️ [Download Bug Report WORD](https://github.com/smplpz21/Bug-Report-Sample/blob/a24dba71514f8f4bd4431f404ba53442c53c4a6b/Bug%20Reports%20-%20Sam%20Lopez.docx)

---

## 🧰 Tools Used

- Manual Web Testing  
- Google Chrome (Dev Tools)  
- Screen Recorder for Bug Evidence  
- FPDF for PDF Report Styling  
- Markdown for GitHub Documentation  

---

## ✍️ Author

**Sam Lopez**  
QA Automation Engineer | Manual & Automated Testing  
[LinkedIn](#) | [GitHub](#)

