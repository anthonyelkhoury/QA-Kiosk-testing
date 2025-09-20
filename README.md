# QA Case Study – Kiosk Ordering Software

## Project Overview
This repository contains a QA and testing case study for a **Kiosk Ordering Software** developed for a restaurant environment.  
The goal of this project was to ensure that the system’s **frontend functionalities, usability, and reliability** met the required standards through **manual testing and structured test cases**.

---

## Objectives
- Validate core features of the kiosk ordering flow (navigation, cart, payment).  
- Identify usability and security issues (e.g., HTTPS, input validation).  
- Provide actionable recommendations to improve the customer experience.  
- Document all test cases, results, and severity levels.  

---

## Tools & Techniques
- **Manual Testing**  
- **Browser Developer Tools (Console inspection)**  
- **Excel** – Test case management  
- **Word (PDF Report)** – QA documentation  

---

## Repository Contents
- `Kiosk.pdf` → Full QA report with test cases, screenshots, and results.  
- `Kiosk.xlsx` → Structured test case sheet with expected/actual results.  

---

## Key Findings
- **Website Security:** Application used HTTP instead of HTTPS → major security risk.  
- **Translation Issues:** Inconsistent language switching (English ↔ French).  
- **Cart Functionality:** Glitches with item duplication and incorrect totals.  
- **Input Validation:** Weak validation on phone numbers and forms.  
- **Design & Responsiveness:** Overlapping UI elements and poor responsiveness on different screen sizes.  

---

## Example Test Cases
| Test Case | Description | Expected Result | Actual Result | Status |
|-----------|-------------|-----------------|---------------|--------|
| TC_LP_02  | Continue button redirects to next page | User is redirected | Works correctly | ✔️ Pass |
| TC_CA_05  | Cart glitch when adding/removing pizzas | Cart updates smoothly | Cart duplicated pizzas & incorrect totals | ❌ Fail |
| TC_SEP_04 | Email receipt delivery | User receives order receipt | No email received | ❌ Fail |

---

## Deliverables
- **QA Report (PDF)** → Structured document with detailed findings and screenshots.  
- **Test Case Sheet (Excel)** → Covers landing, navigation, cart, payment, and receipt flows.  

---

## Author
**Anthony El Khoury**  
- Full-Stack Developer  
- [LinkedIn Profile](www.linkedin.com/in/anthony-el-khoury-b67992228) | [Email](anthonyelkhoury03@gmail.com)  

---

## 🚀 How to Use
1. Download the attached report and test case sheet.  
2. Review the QA findings and test executions.  
3. Use as a reference for **QA methodologies, documentation style, and test case design**.  
