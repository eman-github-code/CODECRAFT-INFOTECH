# 🛡️ Software Quality Assurance: Calculator Functional Testing
**Organization:** CODE CRAFT  
**Internship Track:** Software Tester (ST)  
**Task ID:** TASK-01  

---

## 📌 Executive Summary
This repository contains a comprehensive test suite for a web-based Calculator application. The objective is to validate arithmetic precision, handle edge cases, and ensure robust error management for invalid inputs through structured manual testing.

## 🧪 Testing Strategy
* **Methodology:** Black Box Functional Testing.
* **Documentation:** All test cases are authored in Markdown for version-controlled clarity.
* **Environment:** Tested on the provided [Demo Site](https://dunizb.github.io/sCalc/) across various browser viewports.

---

## 📊 Detailed Test Suite

| Test ID | Scenario | Preconditions | Execution Steps | Expected Result | Result |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **TC-01** | Integer Addition | App initialized | 1. Input "15"<br>2. Press "+"<br>3. Input "25"<br>4. Press "=" | Display shows "40" | **PASS** |
| **TC-02** | Decimal Precision | App initialized | 1. Input "5.5"<br>2. Press "*"<br>3. Input "2"<br>4. Press "=" | Display shows "11" | **PASS** |
| **TC-03** | Divide by Zero | App initialized | 1. Input "10"<br>2. Press "/"<br>3. Input "0"<br>4. Press "=" | System displays "Infinity"  | **PASS** |
| **TC-04** | BODMAS Logic | App initialized | 1. Input "2 + 3 * 4"<br>2. Press "=" | Result is "14" (Priority check) | **PASS** |
| **TC-05** | Percentage Operation | App initialized | 1. Input "80"<br>2. Press "%" | Display shows "0.8" | **PASS** |
| **TC-06** | Clear Entry (CE) | Display has active value| 1. Click "CE" button | Display resets to "0" | **PASS** |

---

## 🔍 Quality Insights
* **Edge Case Handling:** The calculator correctly identifies division by zero without crashing the UI.
* **UI Responsiveness:** Layout remains stable during multi-digit input operations.
* **Tooling:** Documentation generated using GitHub Flavored Markdown (GFM).

---
**Verification by:** Eman Nasir  
**Status:** Task Complete ✅
