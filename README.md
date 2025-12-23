# 📄 Document Tracking System (DTS)

Document Tracking System (DTS) is an Android application built using **Java** and **Firebase** that digitizes and automates multi-level document approval workflows in an academic environment. The system replaces manual paperwork with a secure, role-based, and real-time approval mechanism for students and faculty/admin users.

---

## 🚀 Features

### 👨‍🎓 Student Module
- Secure login using Firebase Authentication
- Submit documents and track real-time status
- View approval flow and current approver
- Remarks timeline with complete action history
- Search and filter documents by status:
  - Not Submitted
  - Pending
  - Approved
  - Rejected

### 👨‍🏫 Admin / Faculty Module
- Role-based login (Faculty, HOD, Academic Section, etc.)
- View and manage student document requests
- Approve or reject documents with optional remarks
- Centralized admin dashboard with search and filters
- Profile management and password update

---

## 🧠 Workflow Overview

1. User logs in using Firebase Authentication.
2. Role (Student / Admin / Faculty) is identified at login.
3. Students submit documents for approval.
4. Documents move through a predefined approval chain.
5. Admins take actions (Approve / Reject / Comment).
6. Status and remarks are updated in real time.
7. Students can track the complete approval history.

---

## 🛠️ Tech Stack

- **Language:** Java  
- **UI:** XML (Material Design Components)  
- **Backend:** Firebase Authentication, Firebase Realtime Database  
- **Architecture:** Activity-based modular structure  
- **Tools:** Android Studio, RecyclerView, Material UI  

---

## ⭐ Technical Highlights (Resume Ready)

- 🔹 **Implemented role-based authentication and access control** using Firebase Authentication, dynamically routing users to Student or Admin dashboards.
- 🔹 **Designed a multi-level document approval workflow system** with real-time status tracking and current approver visibility.
- 🔹 **Integrated Firebase Realtime Database** to ensure instant synchronization of document status, remarks, and approval history.
- 🔹 **Developed reusable and scalable UI components** using RecyclerView, MaterialCardView, ChipGroup filters, and custom approval dialogs.
- 🔹 **Built a complete remarks timeline system** providing an immutable audit trail with timestamps and role-based actions.

---

## 📱 Screens Implemented

- Login & Role Selection  
- Forgot Password  
- Student Dashboard  
- Student Document Detail & Approval Timeline  
- Admin Dashboard  
- Admin Action Dialog (Approve / Reject / Add Remark)  
- Profile & Password Management  

---

## 🎥 App Demo Video

A working demo of the application can be found here:

▶️ **[Click here to watch the demo](Video.mp4)**

> Note: If the video does not play directly on GitHub, please upload it to Google Drive or YouTube (Unlisted) and replace the link above.

---

## 📌 Use Cases

- Bonafide Certificate approval  
- NOC requests  
- Internship and project approvals  
- Scholarship and academic document verification  

---

## 📜 Conclusion

The Document Tracking System (DTS) is a scalable and production-ready Android application demonstrating strong fundamentals in Android development, Firebase integration, UI/UX design, and workflow automation. It serves as an effective academic solution and a strong portfolio project for Android and mobile application development roles.
