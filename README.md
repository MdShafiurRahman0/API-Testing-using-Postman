# 🌐 JSONPlaceholder API Testing (Postman)

This project demonstrates **API testing** using **Postman** on the [JSONPlaceholder](https://jsonplaceholder.typicode.com/) dummy REST API.  
The goal of this project was to practice **CRUD operations (Create, Read, Update, Delete)**, design positive and negative test cases, and document the results in Excel.

---

## 📌 Project Overview
- **Type:** Manual API Testing with Postman  
- **API Used:** JSONPlaceholder (Dummy REST API)  
- **Focus Areas:** Functional Testing, Negative Testing, CRUD Operations  
- **Documentation:** Excel file with test cases and execution results  

---

## 🔧 Tools & Technologies
- **Postman** – for sending requests and writing tests  
- **Excel** – for documenting test cases, expected vs actual results, and screenshots  

---

## ✅ Test Scenarios
1. **GET /users** – Fetch all users  
2. **GET /users/1** – Fetch single user by ID  
3. **POST /users** – Create a new user  
4. **PUT /users/1** – Update user details  
5. **DELETE /users/1** – Delete a user  

🔹 **Negative Tests** (examples):  
- Fetch invalid user ID → Expect `404`  
- Missing/invalid fields in POST request → Expect validation error  

---

## 📊 Test Case Documentation
All test cases (positive & negative) are documented in **Excel** with details:
- Test Case ID  
- API Endpoint  
- Method  
- Input/Params  
- Expected Result  
- Actual Result  
- Status (Pass/Fail)  
- Priority  
- Notes/Screenshots  

👉 [Link to Test Cases](./TestCases.xlsx)  

---

## 📷 Screenshots
Screenshots of Postman responses are included for reference.  
👉 [See Screenshots Folder](./screenshots/)  

---

## 🎯 Key Learnings
- Designing test cases for REST APIs  
- Writing Postman test scripts (status code, JSON validation, negative testing)  
- CRUD API testing workflow  
- Documenting results in Excel with screenshots  

---

## 🧑‍💻 Author
**Shafiur Rahman**  
- 💼 Junior QA Engineer (Fresher)  
- 🌐 [LinkedIn Profile](https://www.linkedin.com/)  
- 📧 Email: yourname@example.com  

---
