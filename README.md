# Singlish to Sinhala Translator – Automated Testing

## Module
**IT3040 – IT Project Management (ITPM)**  
**Assignment 1 – Semester 1**

## Student
- **Name:** Kodni Diyana  
- **Registration Number:** IT23678668  

## Repository Link
https://github.com/KodniDiyana/singlish-to-sinhala-translator-testing--it23678668

---

## 📌 Project Overview
This project evaluates the **accuracy, robustness, and UI behavior** of the **Singlish to Sinhala translation feature** available at:

🔗 https://www.swifttranslator.com/

The testing focuses on how well the system converts Singlish input into correct Sinhala output under various real-world input conditions.  
Backend APIs, performance, and security testing are **out of scope**, as specified in the assignment.

---

## 🎯 Objectives
- Validate correct Singlish-to-Sinhala conversion for valid inputs
- Identify failure cases and incorrect conversions
- Verify UI behavior such as **real-time output updates**
- Automate all identified test scenarios using **Playwright**

---

## 🧪 Test Coverage
The automated test cases cover:

- Simple, compound, and complex sentence structures
- Interrogative and imperative sentence forms
- Positive and negative sentence forms
- Daily conversational language
- Polite vs informal phrasing
- Word combinations and frequent collocations
- Joined vs segmented words (spacing issues)
- Repeated words used for emphasis
- Tense variations (past, present, future)
- Singular and plural usage
- Mixed Singlish + English inputs
- English technical terms and abbreviations
- Punctuation, numbers, dates, and currency formats
- Long paragraph-style inputs
- Slang and colloquial expressions
- One UI-related test scenario (real-time output update)

A total of:
- **24 Positive Functional Test Cases**
- **10 Negative Functional Test Cases**
- **1 UI Test Case**

---

## 🛠️ Tools & Technologies
- **Playwright**
- **JavaScript**
- **Node.js**
- **VS Code**
- **Microsoft Excel** (for test case documentation)

Workflow->
Install dependencies :npm install

Install Playwright browsers->
npx playwright install


Run the Tests->
npx playwright test

To view the HTML report:-->
npx playwright show-report





---

## 📂 Project Structure
