# 🔐 API Security Risk Analysis

## 📌 Project Overview
This project analyzes common API security vulnerabilities using public APIs and Postman.

---

## 🎯 Objectives
- Identify security issues in APIs
- Understand authentication & authorization flaws
- Learn API testing basics

---

## 🧰 Tools Used
- Postman
- Public APIs (JSONPlaceholder)

---

## 🔍 API Tested
- /users
- /users/{id}
- /posts

---

## 🚨 Findings

### 1. No Authentication
API allows access without login.

### 2. Broken Authorization
Users can access other users' data.

### 3. No Rate Limiting
Unlimited requests allowed.

### 4. Data Exposure
Sensitive user data is visible.

### 5. Input Validation Issues
API accepts invalid inputs.

---

## 📸 Screenshots
Screenshots are available in the `/screenshots` folder.

---

## 📄 Report
Full report available in `/report/api-security-report.pdf`

---

## 🧠 Conclusion
This project demonstrates basic API security flaws and how to identify them.

---

## 👨‍💻 Author
Sai Manikanta
