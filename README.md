

### Software Testing Project: sCalc Web Calculator

This repository contains the comprehensive **testing documentation** for **sCalc**, a modern web-based calculator application. This project was a crucial step in a comprehensive quality assurance assessment, designed to rigorously evaluate the application's core features and overall stability.

**Tester:** Junaid 
**Project Date:** AUGUST 2025
**GitHub Repository:** https://github.com/JUNAID-Web123/Prodigy_Internship

---

### Project Overview

The primary objective of this project was to conduct a detailed manual testing campaign on the sCalc application. The goal was to systematically verify its functionality, pinpoint defects, and ensure the application met stringent quality standards before any potential production release.

The structured testing process included:

* **Test Case Design:** Meticulously creating detailed, structured test cases to ensure every visible application feature was covered.
* **Test Execution:** Manually running each test case against the live application to capture real-time results and behaviors.
* **Defect Reporting:** Thoroughly documenting all identified bugs and inconsistencies with clear, actionable details for the development team.

---

### Application Under Test (AUT)

* **Application Name:** sCalc
* **URL:**https://dunizb.github.io/sCalc

---

### Testing Scope

The testing scope was designed for a thorough, feature-by-feature evaluation of the sCalc application, including:

* **Core Arithmetic Operations:** Verifying the accuracy of **Addition (+)**, **Subtraction (-)**, **Multiplication (×)**, and **Division (÷)**.
* **Advanced Operations:** Assessing the application's adherence to the **Order of Operations (BODMAS/PEMDAS)** and the correctness of **Percentage (%)** calculations.
* **Auxiliary Functions:** Testing the reliability of essential functions like the **Backspace (←)** and **Clear (CE)** keys.
* **Usability & Edge Cases:** Evaluating how the calculator handles **decimals**, **negative numbers**, and **chained operations**.
* **Robust Error Handling:** Ensuring the system provides a predictable and correct response to invalid inputs, such as **division by zero** and improper operational sequences.

---

### Test Execution Summary

The test suite consisted of **40 meticulously crafted test cases** to ensure a high level of functional coverage. The results highlight significant areas for improvement.

| Metric | Count |
| :--- | :--- |
| **Total Test Cases Executed** | 40 |
| ✅ **Passed** | 31 |
| ❌ **Failed** | 9 |
| **Pass Rate** | 77.5% |

While the majority of fundamental tests passed, several **critical and major defects** were identified in the application's core logic. These flaws significantly impact the calculator's reliability, rendering it **unsuitable for a production release** without immediate remediation.

---

### Summary of Critical Defects Found

The following high-priority bugs were identified during the rigorous test execution process:

* **BUG 1: Order of Operations (BODMAS) Ignored** 🛑: The calculator fails to adhere to the standard mathematical order of operations. It performs all calculations strictly from left to right, leading to incorrect results for common expressions (e.g., `5 + 3 * 2` incorrectly yields **16** instead of the correct result of **11**).
* **BUG 2: Percentage (%) Function Is Unstable** ⚠️: The percentage key is fundamentally flawed and unpredictable. It produces incorrect results for both multiplication and subtraction operations. Furthermore, its use causes the equals **(=)** key to malfunction, resetting the calculation to zero.
* **BUG 3: Multiplication with Negative Numbers Fails** 📉: The calculator cannot correctly multiply by negative numbers. Instead of performing multiplication, it incorrectly executes a subtraction operation (e.g., `7 * -3` results in **4** instead of the correct value of **-21**).
* **BUG 4: Incorrect Handling of Double Negatives** ➖: The calculator fails to correctly process consecutive negative signs in subtraction. For example, the expression `5 - - 2` incorrectly results in **3** instead of the correct answer of **7**.

---

### Testing Artifacts

This repository serves as a complete and centralized hub for all project documentation.

📊 **View Test Execution Report Spreadsheet** ➡️ https://github.com/JUNAID-Web123/Prodigy_Internship/blob/main/PRODIGY_ST_TASK_01.xlsx

This file contains the raw, detailed test execution data in a spreadsheet format, providing a transparent view of the testing process. This thorough testing process has successfully identified key areas for improvement and provided clear, actionable feedback for the development team.
