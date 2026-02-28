# 🎓 Mentor Bright – Tutor Support System

🚀 *A modern mentoring platform connecting students and university lecturers, built with the MERN stack.*

## 📌 Overview

**Mentor Bright** is a comprehensive web-based mentoring support system designed for students at **Ho Chi Minh City University of Technology (HCMUT)**. The platform enables students to connect with lecturers and mentors to receive academic guidance, resolve learning difficulties, and participate in structured mentoring programs throughout a semester.

> **📝 Note:** Detailed system architecture, database design, and use cases can be found in the attached [`CNPM_Report.pdf`](./CNPM_Report.pdf).

---

## 🧠 Core Concept & Workflow

The system follows a strict **semester-based mentoring workflow**, managed seamlessly between administrators, lecturers, and students:

### 🟦 Phase 1: Beginning of Semester (July)
* Admin creates a new Semester (Status: `UPCOMING`).
* Students complete survey forms → Generate *Mentoring Requests*.

### 🟨 Phase 2: Preparation (August)
* Admin reviews mentoring requests and demands.
* Admin selects subjects to open and assigns lecturers (tutors).
* Semester status updated to `OPEN_REGISTRATION`.
* Students register for subjects → Admin approves *Registrations*.

### 🟩 Phase 3: Learning Starts (September)
* Semester status updated to `IN_PROGRESS`.
* Lecturers publish available schedules → Create *Slots*.
* Students browse subjects, select a lecturer, and book a slot → Create *Bookings*.
* Automated system notifications are sent to participants.

### 🟪 Phase 4: During the Semester
* Students check in for online or offline mentoring sessions.
* Sessions are completed and students provide ratings/feedback.
* Lecturers continuously update their availability.

---

## 🛠️ Tech Stack

### Frontend
| Technology | Usage |
| :--- | :--- |
| **React** | UI component development |
| **Vite** | Fast frontend build tool |
| **Tailwind CSS** | Utility-first styling and responsive design |
| **React Router** | Client-side routing and protected routes |
| **Axios** | HTTP client for API requests |

### Backend
| Technology | Usage |
| :--- | :--- |
| **Node.js & Express.js** | RESTful API server environment |
| **MongoDB** | NoSQL database for flexible data modeling |
| **JWT** | Secure authentication & authorization |
| **Cloudinary** | Cloud media storage (avatars, materials) |

---

## 🚀 Quick Start

### 1️⃣ Clone Repository
```bash
git clone [https://github.com/phongwd2311/Tutor-Support-System.git](https://github.com/phongwd2311/Tutor-Support-System.git)
cd Tutor-Support-System
```
### 2️⃣ Run Backend Server
```bash
cd server
npm install
npm run dev
# Backend server runs at: http://localhost:8080
```
### 3️⃣ Run Frontend Client
```bash
cd client
npm install
npm run dev
# Frontend application runs at: http://localhost:5173
```
📏 Code Standards & Workflow
   ESLint: Custom rules enforced for clean code (Single quotes, 2-space indentation, strict React Hooks usage).
   Git Workflow: Follows strict branching strategies (main, dev, feature/*). Pull Requests are mandatory for merging into production branches.
📬 Contact
For any questions or collaboration, feel free to reach out:
* Name: Võ Quốc Phong
* Email: vo.quoc.phong.qt@gmail.com
* Phone: 0942 059 127
* GitHub: github.com/phongwd2311
