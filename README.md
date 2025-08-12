# Semester-Project-SecureSyntax

# Pathfinder: Career Guidance & Recommendation System

## 📌 Overview
**Pathfinder** is a web-based **Career Guidance & Recommendation System** designed to help students make informed career choices through **personalized recommendations** and **expert mentorship**.  
Built with a **Java backend**, the platform intelligently matches students to suitable career paths and mentors based on their preferences, skills, and academic performance.

The system integrates a **Recommendation API** that processes a student's **city**, **preferred language**, **interest tags**, and **test scores** to provide tailored career field suggestions. Students can book mentorship sessions, access verified educational resources, and track their career guidance journey.

---

## 🎯 Key Features
- **Student Registration & Profile Management**
- **Personalized Career Recommendations**
- **Skill-Based Matching with Mentors**
- **Mentor Onboarding & Admin Approval**
- **Session Booking System** (Pending, Accepted, Completed statuses)
- **Career Field Information**:
  - Average Salary
  - Required Skills
  - Top Colleges
  - Curated Resources (PDFs, Videos)
- **Multilingual Resource Support**
- **Admin Management Dashboard**
- **Secure & Scalable Java Backend**

---

## 🗄 Database Structure (PathfinderDB)
The system uses **six core entities**:
1. **Student** – Profile, skills, preferences, academic scores.
2. **Mentor** – Expertise area, experience, language, location.
3. **Career Fields** – Field details, required skills, average salary, top colleges.
4. **Bookings** – Session scheduling between students and mentors.
5. **Resources** – Educational materials (PDF, video, articles).
6. **Admin** – Approval and management of mentors & platform data.

---

## 🛠 Tech Stack
**Backend:** Java  
**Database:** MySQL (PathfinderDB)  
**Frontend:** HTML, CSS, JavaScript (or chosen frontend framework)  
**Recommendation API:** Custom-built skill-based matching algorithm  
**Version Control:** Git & GitHub

---

## 📂 Project Structure
Pathfinder/
│── backend/ # Java backend source code
│── frontend/ # UI/UX files
│── database/ # SQL scripts for PathfinderDB
│── docs/ # Project documentation & resources
│── README.md # Project documentation file

