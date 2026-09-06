# 🧪 OrangeHRM Manual Testing Project

> **Build. Test. Improve. Scale.**

A hands-on **Manual Testing project** based on the OrangeHRM web application.
The objective of this project is to practice the complete Software Testing Life Cycle (STLC) by creating test documentation, executing test cases, identifying defects, and preparing detailed bug reports.

---

## 📌 Project Overview

This project covers end-to-end manual testing of a sample HR Management web application.

The testing process includes:

**Test Planning → Test Case Design → Test Execution → Defect Reporting → Retesting → Test Summary**

The project is designed to simulate a real-world QA testing workflow.

---

## 🎯 Objectives

* Understand and apply the **STLC**
* Create a structured **Test Plan**
* Design **30+ functional test cases**
* Execute test cases and record actual results
* Identify and document reproducible defects
* Create detailed **Bug Reports**
* Maintain a **Requirement Traceability Matrix (RTM)**
* Perform retesting of fixed defects
* Prepare a final **Test Execution & Summary Report**

---

## 🌐 Application Under Test

**Application:** OrangeHRM Demo
**Application Type:** Web-based HR Management System
**Testing Approach:** Manual Testing

---

## 🧩 Modules Tested

The following functional areas are covered:

* 🔐 Login
* 📊 Dashboard
* ⚙️ Admin
* 👨‍💼 PIM / Employee Management
* 🏖️ Leave Management
* 👥 Recruitment
* 👤 My Info
* 🔧 User Profile
* 🚪 Logout

---

## 🔍 Testing Types

* Functional Testing
* UI Testing
* Positive Testing
* Negative Testing
* Boundary Value Testing
* Validation Testing
* Regression Testing
* Retesting
* Exploratory Testing

---

## 📝 Test Documentation

### 1. Test Plan

The Test Plan defines the testing scope, objectives, approach, environment, entry/exit criteria, risks, and testing activities.

📁 `Test-Plan/`

---

### 2. Test Cases

Designed **30+ functional test cases** covering major application modules.

Each test case includes:

* Test Case ID
* Module
* Test Scenario
* Test Steps
* Test Data
* Expected Result
* Actual Result
* Status
* Priority

📁 `Test-Cases/`

---

### 3. Test Execution

Test cases were executed against the application and results were recorded as:

* ✅ Pass
* ❌ Fail
* ⏸️ Blocked

📁 `Test-Execution/`

---

### 4. Requirement Traceability Matrix (RTM)

The RTM maps application requirements to their corresponding test cases and execution results.

**Requirement → Test Case → Execution → Bug**

📁 `RTM/`

---

### 5. Bug Reports

For every reproducible failed test case, a detailed bug report is created containing:

* Bug ID
* Summary
* Module
* Severity
* Priority
* Environment
* Preconditions
* Steps to Reproduce
* Expected Result
* Actual Result
* Status
* Screenshot

📁 `Bug-Reports/`

> **Note:** Only reproducible defects observed during testing are reported.

---

## 🛠️ Tools Used

| Tool            | Purpose                                   |
| --------------- | ----------------------------------------- |
| OrangeHRM Demo  | Application Under Test                    |
| Microsoft Excel | Test Cases, Execution, RTM & Bug Tracking |
| Jira            | Defect Tracking / Bug Management          |
| Google Chrome   | Web Browser                               |
| Git & GitHub    | Version Control & Project Documentation   |

---

## 📂 Project Structure

```text
OrangeHRM-Manual-Testing/
│
├── README.md
│
├── Test-Plan/
│   └── Test-Plan.xlsx
│
├── Test-Cases/
│   └── Test-Cases.xlsx
│
├── Test-Execution/
│   └── Test-Execution.xlsx
│
├── RTM/
│   └── RTM.xlsx
│
└── Bug-Reports/
    ├── Bug-Report.xlsx
    │
    └── Screenshots/
        ├── BUG-001.png
        ├── BUG-002.png
        └── BUG-003.png
```

---

## 🔄 QA Workflow

```text
Requirement Analysis
        ↓
Test Planning
        ↓
Test Scenario Identification
        ↓
Test Case Design
        ↓
Test Case Execution
        ↓
Pass / Fail
        ↓
Bug Reporting
        ↓
Developer Fix
        ↓
Retesting
        ↓
Regression Testing
        ↓
Test Summary Report
```

---

## 📚 Key Learning Outcomes

Through this project, I gained practical experience in:

* Writing effective manual test cases
* Designing positive and negative test scenarios
* Executing test cases systematically
* Identifying and reporting software defects
* Understanding Severity vs Priority
* Creating RTM documentation
* Performing retesting and regression testing
* Maintaining QA documentation
* Following a structured manual testing workflow

---

## 👨‍💻 Project Author

**Dev Patel**

This project was created as part of a **QA / Software Testing learning journey** to gain hands-on experience with real-world manual testing practices.

---

⭐ If you find this project useful, feel free to explore the test documentation and testing artifacts in this repository.
