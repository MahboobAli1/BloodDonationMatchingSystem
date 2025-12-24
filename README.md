# 🩸 Blood Donation & Matching System

![Java](https://img.shields.io/badge/Language-Java-orange) 
![MySQL](https://img.shields.io/badge/Database-MySQL-blue)
![DSA](https://img.shields.io/badge/DSA-ArrayList%20%7C%20Queue-brightgreen)
![GUI](https://img.shields.io/badge/GUI-Swing-lightgrey)

**Course:** Data Structures & Algorithms  
**Department:** Artificial Intelligence, Aror University of Art, Architecture, Design & Heritage, Sukkur, Sindh  

---

## 🌟 Project Overview
The **Blood Donation & Matching System** streamlines connecting blood donors with recipients.  
It efficiently manages donor data, matches blood types, and ensures timely communication — reducing delays in emergencies and increasing the availability of compatible donors.

---

## 🛑 Problem Statement
Finding compatible blood donors quickly is often difficult.  
Traditional systems are **slow, unorganized, and manual**, causing critical delays.  
This project implements an **automated, data-driven system** to make blood donation and matching **efficient and reliable**.

---

## 🎯 Objectives
- Quick matching between donors and recipients  
- Maintain an updated donor database (blood type, location, contact)  
- Real-time donor info during emergencies  
- Promote voluntary blood donation digitally  

---

## ⚙️ Recommended Model
**Incremental Model** — development in small, manageable parts:  
1. Initial increments: Donor registration & matching  
2. Later increments: Location tracking, notifications, medical verification  

---

## 🖥️ System Design
- **Database:** Donor & recipient details  
- **Matching Algorithm:** Compare blood groups & show compatible matches  
- **User Interface:** Register, search, and contact donors/recipients  
- **Data Structures:** ArrayList, Queue for efficient data handling  

---

## 🔹 Features

### 1️⃣ User Roles
| Role | Function |
|------|---------|
| Donor | Register / Search donors |
| Admin | Manage donors, blood requests, tests |
| Request/Patient | Submit requests & search for compatible donors |

### 2️⃣ Donor Registration
- Fields: Name, Blood Group, City, Phone, Distance (km)  
- Submit using **Register Donor** button  

### 3️⃣ Patient Request Submission
- Fields: Patient Name, Blood Group, City, Hospital, Distance, Urgency  
- Submit using **Submit Requests** button  

### 4️⃣ Donor Searching / Filtering
- Filter by blood group & city  
- Search results show:  
  ID | Name | Blood Group | City | Phone | Availability | Screening Status  

### 5️⃣ Request Searching / Filtering
- Filter by blood group & city  
- Search results show:  
  Patient Name | Blood Needed | City | Hospital | Urgency | Status  

### 6️⃣ Administration & Fulfillment
- **Manual Fulfillment:** Assign donors to requests  
- **Automated Queue:** Process next pending request  
- Enter donor screening results (HIV, Hepatitis B & C, Syphilis, Malaria, Dengue, HTLV)  
- Track Pending & Available donors/requests  

---

## ✅ Expected Results
- Faster compatible donor search  
- Efficient blood management  
- Increased voluntary donations  

---

## 📅 Timeline
| Week | Tasks |
|------|-------|
| 1-2  | Requirement gathering & design planning |
| 3-4  | Database & core algorithm implementation |
| 5-6  | GUI development & integration testing |
| 7-8  | Final testing, debugging, documentation |

---

## 💻 How to Run
```bash
# Clone the repository
git clone https://github.com/YourUsername/BloodDonationMatchingSystem.git


## Open in Java IDE (Eclipse/IntelliJ)

Ensure MySQL is running & DB is set up

Run Main.java to start the GUI

Register donors, submit requests, and manage the system
