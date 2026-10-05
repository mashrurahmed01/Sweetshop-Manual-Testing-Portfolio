# 🧪 Sweetshop Web Application - Manual Testing Portfolio

![QA Testing](https://img.shields.io/badge/Quality%20Assurance-Manual%20Testing-blue.svg)
![Test Status](https://img.shields.io/badge/Test%20Execution-Completed-brightgreen.svg)
![File Format](<https://img.shields.io/badge/Format-Microsoft%20Excel%20(.xlsx)-green.svg>)
![License](https://img.shields.io/badge/License-MIT-orange.svg)

Welcome to the **Sweetshop Manual Testing Portfolio** repository! This project contains end-to-end manual test documentation, test cases, execution reports, and bug logs for an e-commerce web application (**Sweetshop**).

The purpose of this repository is to demonstrate practical knowledge of Software Testing Life Cycle (STLC), test case design techniques, defect lifecycle management, and structured test reporting.

---

## 📌 Table of Contents

- [Application Under Test (AUT)](#-application-under-test-aut)
- [Repository Structure](#-repository-structure)
- [Excel Workbook Breakdown](#-excel-workbook-breakdown)
- [Test Coverage & Scope](#-test-coverage--scope)
- [Test Case Structure & Template](#-test-case-structure--template)
- [Execution Summary & Metrics](#-execution-summary--metrics)
- [Defect Reporting & Severity Matrix](#-defect-reporting--severity-matrix)
- [Tools & Environment](#-tools--environment)
- [How to View & Download](#-how-to-view--download)
- [Author & Contact](#-author--contact)

---

## 🌐 Application Under Test (AUT)

- **Application Name:** Sweetshop Web Application
- **Domain:** E-commerce / Retail
- **Testing Type:** Manual Testing (Functional, UI/UX, Boundary Value Analysis, Equivalence Partitioning, Negative & Smoke Testing)

---

## 📁 Repository Structure

```text
├── Sweetshop Test Cases Portfolio.xlsx   # Main Excel document containing all test artifacts
└── README.md                              # Repository overview and documentation
```

---

## 📊 Excel Workbook Breakdown

The workbook `Sweetshop Test Cases Portfolio.xlsx` is divided into structured worksheets:

1. **Test Plan & Strategy:** Objectives, scope (in-scope vs. out-of-scope), deliverables, and test environments.
2. **Test Scenarios:** High-level user scenarios mapped to features.
3. **Test Cases:** Detailed positive, negative, and edge-case test steps.
4. **Bug Reports / Defect Log:** Detailed log of defects identified during execution, including steps to reproduce, expected vs. actual results, severity, and priority.
5. **Test Execution & Metrics:** Pass/Fail breakdown, execution charts, and summary status.

---

## 🎯 Test Coverage & Scope

The test suite covers key e-commerce modules and workflows within the Sweetshop application:

| Module                     | Test Coverage Highlights                                                                   |
| :------------------------- | :----------------------------------------------------------------------------------------- |
| **Navigation & Header**    | Navbar items, brand logo redirection, broken links, responsiveness.                        |
| **Product Catalog**        | Product listing display, prices, descriptions, images loading correctly.                   |
| **Search & Filtering**     | Keywords, empty search, special characters, category filter behavior.                      |
| **Shopping Basket / Cart** | Adding items, updating quantities, removing items, total price calculations.               |
| **Checkout Flow**          | Billing/Shipping address validation, coupon/discount inputs, order summary.                |
| **User Authentication**    | Login, Registration form validation, session state management.                             |
| **UI & Usability**         | Visual layout alignment, button states, field error messages, cross-browser compatibility. |

---

## 📝 Test Case Structure & Template

Each test case inside the Excel sheet follows standard IEEE/QA industry formats with the following fields:

| Field Name            | Description                                                    |
| :-------------------- | :------------------------------------------------------------- |
| `TC_ID`               | UniqueIdentifier for the test case (e.g., `TC_SW_001`)         |
| `Module / Feature`    | Target functional area                                         |
| `Test Scenario`       | Summary of what is being tested                                |
| `Pre-conditions`      | Prerequisite setup required before execution                   |
| `Test Steps`          | Step-by-step instructions for execution                        |
| `Test Data`           | Specific inputs utilized during execution                      |
| `Expected Result`     | Intended behavior per requirements                             |
| `Actual Result`       | Real behavior observed during testing                          |
| `Status`              | `Pass`, `Fail`, `Blocked`, or `Untested`                       |
| `Severity / Priority` | Severity level for failed tests (`Critical`, `Major`, `Minor`) |

---

## 📈 Execution Summary & Metrics

Below is a summary overview of the test execution results recorded in the workbook:

| Metric                 | Details / Value                   |
| :--------------------- | :-------------------------------- |
| **Total Test Cases**   | _[Insert Total Number]_           |
| **Passed Test Cases**  | _[Insert Passed Count]_           |
| **Failed Test Cases**  | _[Insert Failed Count]_           |
| **Blocked / Untested** | _[Insert Blocked/Untested Count]_ |
| **Overall Pass Rate**  | _[Insert Pass %]_                 |

---

## 🐛 Defect Reporting & Severity Matrix

Defects logged in the workbook are categorized using a standard priority/severity matrix:

- **Critical / Blocker:** Application crash, checkout process failure, or data corruption.
- **High / Major:** Core functionality impaired (e.g., Unable to add items to cart, incorrect total calculations).
- **Medium / Normal:** Secondary feature issues or layout glitches affecting user experience.
- **Low / Minor:** Minor typos, cosmetic UI misalignments, or color inconsistencies.

---

## 🛠 Tools & Environment

- **Test Management & Documentation:** Microsoft Excel / Google Sheets
- **Defect Tracking Format:** Standard QA Defect Log
- **Browsers Tested:** Google Chrome, Mozilla Firefox, Microsoft Edge
- **Dev Tools:** Chrome DevTools (Inspection, Console Logs, Network tab)
- **Version Control:** Git & GitHub

---

## 📥 How to View & Download

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mashrurahmed01/Sweetshop-Manual-Testing-Portfolio.git
   ```
2. **Direct File Download:**
   Click on [`Sweetshop Test Cases Portfolio.xlsx`](./Sweetshop%20Test%20Cases%20Portfolio.xlsx) in the file list above and click the **Download** button.
3. **Online View:** You can also preview the spreadsheet directly on GitHub or import it into Google Sheets.

---

## 👤 Author & Contact Information

- **Name:** Md Mashrur Ahmed
- **LinkedIn:** https://www.linkedin.com/in/mashrur-ahmed/
- **Email:** mashrur789@gmail.com

---

_If you find this manual testing portfolio helpful or informative, feel free to leave a 🌟 star on this repository!_
