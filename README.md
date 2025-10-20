# 🎓 Educational Organisation using ServiceNow

![ServiceNow](https://img.shields.io/badge/Platform-ServiceNow-blue) 

A **low-code solution for educational institutions** built on **ServiceNow** that automates student admissions, tracks academic progress, and centralizes data management.

---

## 📘 Project Overview

This system is designed to simplify and automate key academic workflows:

- Efficiently handle student admissions  
- Track academic performance and results in real-time  
- Maintain accurate and secure student records  
- Minimize manual effort and errors  
- Support future expansions like fee management, faculty modules, and LMS integration  

---

## 🛠 Technologies Used

- **ServiceNow Developer Instance**  
- ServiceNow Studio  
- Form Designer  
- Client Scripts (JavaScript)  
- Process Flow Designer  
- Number Maintenance  
- Local Update Sets  

---

## 🏗 Modules

### 1️⃣ Core Student Table (Salesforce Table)
Stores core student data:  
- Auto-generated Admin Number  
- Student Name, Grade  
- Parent Details & Contact Numbers  
- Admission Date  

> Acts as the parent table for Admission and Student Progress tables.

### 2️⃣ Admission Table
Manages student enrollment:  
- Admission Status (New, In Progress, Joined, Rejected, etc.)  
- Purpose of Joining  
- School, Area, and Location Details (Auto-filled via Pincode)  

### 3️⃣ Student Progress Table
Tracks academic performance:  
- Marks for six subjects (Telugu, Hindi, English, Maths, Science, Social)  
- Total & Percentage (Auto-calculated)  
- Result (Pass/Fail)  

---

## 💡 Key Features

- Dynamic forms with real-time field updates  
- Auto-populate student details from Salesforce Table  
- Pincode-based location autofill (Mandal, City, District)  
- Automatic calculation of Total, Percentage & Result  
- Field locking to maintain data accuracy  
- Visual process flow for admission lifecycle:  

 New -> In Progress -> Joined -> Rejected -> Rejoined -> Closed -> Cancelled

---

## 📈 Benefits

- Reduces manual administrative effort  
- Ensures accurate academic calculations  
- Provides transparent admission status tracking  
- Enhances efficiency for school administrators  
- Modular and scalable for future enhancements  

---

## 🔮 Planned Enhancements

- Email & SMS notifications for admission updates  
- Mobile-friendly interface  
- Analytics dashboards  
- Faculty & class management modules  
- Fee management system  
- Report card generation & LMS integration  

---

## ⚙ Setup Instructions

1. Sign up at [ServiceNow Developer Portal](https://developer.servicenow.com)  
2. Request a **Personal Developer Instance**  
3. Open **Studio** and create custom tables: `Salesforce`, `Admission`, `Student Progress`  
4. Design forms using **Form Designer**  
5. Add **Client Scripts**, **Process Flows**, and **Number Maintenance**  
6. Capture configurations in a **Local Update Set**  
7. Test all workflows, validations, and form behavior  

---

## 🧑‍💻 Author

**Karapakula Balaji Sai Vrushadree**  
Final Year B.Tech (ECE) Student  
Annamacharya Institute of Technology & Sciences, Tirupati  
📧 kbsv2004@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/sai-vrushadree-715012255/)  

---

