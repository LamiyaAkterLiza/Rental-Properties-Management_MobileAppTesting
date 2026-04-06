## 🏠 Rental Properties Management 

## 📌 Project Overview

This repository contains comprehensive bug reports for the **Rental Properties Management APK**.

The purpose of this repository is to track, manage, and resolve application issues efficiently while maintaining clear documentation for QA and development teams.

---

## 🔗 Project Links

* APK File: https://drive.google.com/file/d/10bVwjHrl9mQWhU83GAsrOvdMUUs_1m79/view?usp=sharing

---

## 🧩 Modules Covered

### 💳 Payment & Upload Proof

Includes issues such as:

* Invalid amount validation
* Negative value acceptance
* Missing error messages
* File upload inconsistencies

---

### 📂 File Upload System

Includes issues such as:

* File sharing across forms
* No maximum upload limit
* Layout breaking on multiple uploads

---

### 🧾 Fines Management

Includes issues such as:

* Fine submission flow issues
* Missing admin notifications
* Payment submission handling bugs

---

### 🛠 Maintenance Section

Includes issues such as:

* Property selection visibility issues
* UI/UX inconsistencies

---

### 🌐 Localization

Includes issues such as:

* Incorrect unit translation
* Language-based display inconsistencies

---

## 🐞 Bug Summary

### 🔴 Critical Issues

* Negative amount accepted without validation
* No maximum file upload limit across the application

---

### 🟠 Major Issues

* Uploaded file appears across multiple forms
* No validation message for invalid input
* Unclear/generic error messages
* Submit button hidden due to layout overflow
* No admin notification after fine submission

---

### 🟡 Minor Issues

* Property address not fully visible
* Incorrect unit display in Spanish language

---

## 📁 Repository Structure

```
Rental-Bug-Reports/
│
├── Payment/
├── File-Upload/
├── Fines/
├── Maintenance/
├── Localization/
├── attachments/
└── README.md
```

---

## 📎 Attachments

All supporting files (screenshots, videos, documents) are attached via Google Drive links in each bug report.

---

## 🚨 Key Observations

* Lack of proper validation in payment-related forms
* File handling system is not isolated per module
* Missing constraints (e.g., file upload limits)
* Poor error handling and unclear messages
* UI/UX responsiveness issues in multiple sections
* Missing system notifications for critical actions

---

## ✅ Recommendations

* Implement strict validation for all input fields
* Restrict invalid and negative values in transactions
* Add maximum file upload limits
* Fix layout responsiveness issues
* Improve error messages for better user understanding
* Ensure module-wise file isolation
* Implement admin notification system for important actions

---

## 👤 Reported By

**Lamiya**– QA Engineer

---

## 📌 Status

* Some bugs: Fixed
* Some bugs: Re-test / Pending

---

## 📢 Note

This repository is intended for internal QA tracking and development collaboration. All bugs are documented based on real testing scenarios.

---

