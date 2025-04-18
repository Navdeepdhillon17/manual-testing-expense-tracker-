# 🧪 Manual Testing – Expense Tracker Web App

This project contains a complete set of **manual test cases** for a Java-based **Expense Tracker** web application. The tests are written in Excel format and cover **functional**, **UI**, and **security testing**, including **SQL injection** and **XSS vulnerability** checks.

---

## 📋 Project Overview

- **Application Under Test (AUT)**: Expense Tracker Web App
- **Testing Type**: Manual Testing
- **Test Format**: Excel spreadsheet
- **Tools Used**: Browser (Chrome/Firefox), Excel
- **Tech Stack of AUT**: Java, JSP/Servlets, PostgreSQL (self-built)

---

## ✅ Test Coverage

Test cases include:

- 🔐 Authentication
- 🧾 Expense Management (Add/Edit/Delete)
- 🎨 UI & UX
- 🌐 Compatibility & Responsiveness
- 🔒 Security (XSS, SQL Injection)
- 📊 Data validation & Edge Cases

---

## 🧪 Sample Test Cases

| Case ID      | Title                             | Status |
|--------------|-----------------------------------|--------|
| TC_REG_001   | Register with valid details       | ✅ PASS |
| TC_EXP_010   | Add negative amount as expense    | ❌ FAIL |
| TC_SEC_002   | SQL Injection on Registration     | ✅ PASS |
| TC_SEC_004   | XSS in Expense Name               | ❌ FAIL |

See full coverage in the Excel sheet.

---


## 👤 Author

**Navdeep Kaur**  
Software Tester | QA Learner   
🔗 [LinkedIn](https://www.linkedin.com/in/navdeep-kaur-b70943277/)

---

## 💡 Notes

- Test cases are grouped by **Test Suites** for clarity.
- Failed test cases include actual vs expected outcomes.
- Security test cases were manually tested using crafted input strings (XSS, SQLi).

---



> This is not a live testing project. These test cases are meant for **demonstration and learning purposes**, and tested on a local web application.

---


