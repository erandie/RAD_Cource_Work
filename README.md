# Book Club – Library Management Web Application  
## 📌 Short Description  
**Book Club** is a full-stack web application designed for a modern library in Colombo, Sri Lanka. It empowers library staff to efficiently manage **readers**, **books**, **lending transactions**, **overdue alerts**, and **audit logs** through a secure, responsive, and intuitive interface. Built with modern technologies, it ensures smooth operations and scalability for growing collections.  

---  

## ✨ Features  
* 🔐 **Secure Authentication** – JWT-based login for staff only  
* 👥 **Reader Management** – Add, edit, delete, and view registered readers  
* 📚 **Book Management** – Full CRUD for library catalog with search & filters  
* 📖 **Lending Management** – Lend/return books, track history by reader or book  
* ⏰ **Overdue Management** – Auto-detect overdue books with due date calculation  
* 📧 **Email Notifications** – Send overdue alerts via SendGrid (one-click trigger)  
* 🔍 **Search & Filter** – Instant search for books and readers  
* 📱 **Responsive Design** – Mobile-friendly UI with Tailwind CSS  
* 📜 **Audit Logging** – Track all critical actions (lend, return, delete)  

---  

## 🛠️ Tech Stack  
| Layer         | Technology                              |  
|---------------|-----------------------------------------|  
| **Frontend**  | React, TypeScript, Tailwind CSS         |  
| **Backend**   | Node.js, Express, TypeScript            |  
| **Database**  | MongoDB (with Mongoose ODM)             |  
| **Auth**      | JWT (JSON Web Tokens) + HTTP-only cookies |  
| **Email**     | SendGrid API (or Nodemailer fallback)   |  
| **Deployment**| Vercel (Frontend) + Render/Heroku (Backend) |  

---  

## 🚀 Getting Started  

### Prerequisites  
* Node.js (v18+) and npm  
* MongoDB Atlas account or local MongoDB  
* SendGrid API Key (for email)  
* Git  

### Setup & Run  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/erandie/RAD_Cource_Work.git
   cd RAD_Cource_Work
   ```  

2. **Set up environment variables:**  
   Create `.env` in both `frontend` and `backend` folders:  

   **Backend (.env):**  
   ```env
   PORT=3000
   MONGODB_URI=mongodb+srv://<user>:<pass>@cluster0.mongodb.net/bookclub
   STAFF_EMAIL=hansi@gmail.com
   STAFF_PASSWORD=*********
   ```  

   **Frontend (.env):**  
   ```env
   VITE_API_URL=http://localhost:3000/api
   ```  

3. **Install dependencies:**  
   ```bash
   # Backend
   cd backend
   npm install

   # Frontend
   cd ../frontend
   npm install
   ```  

4. **Run the app:**  
   ```bash
   # Terminal 1 - Backend
   cd backend
   npm run dev

   # Terminal 2 - Frontend
   cd frontend
   npm run dev
   ```  

5. Open [http://localhost:5173](http://localhost:5173) to view the app.  

---  

## 📂 Project Submission   
* ✅ Full CRUD + Lending + Overdue + Email Notifications  
* ✅ JWT Authentication & Role-based Access  
* ✅ Responsive UI with Tailwind CSS  
* ✅ Audit Logs & Search/Filter  
* ✅ MongoDB with Sample Data  
* ✅ Comprehensive README & Documentation  
* ✅ Environment Setup Instructions  

---  

## 📊 Evaluation Coverage  
| Criteria                      | Implemented |  
|-----------------------------|-------------|  
| **Authentication**          | JWT + Protected Routes |  
| **CRUD Operations**         | Readers, Books, Transactions |  
| **Lending & Returns**       | Due Date Auto-calculation |  
| **Overdue Detection**       | Real-time + Email Trigger |  
| **Email Notifications**     | SendGrid Integration |  
| **State Management**        | React Context + Custom Hooks |  
| **UI/UX**                   | Fully Responsive, Accessible |  
| **Security**                | Input Validation, Sanitization, Rate Limiting |  
| **Code Quality**            | TypeScript, ESLint, Prettier, Modular Structure |  
| **Audit Logging**           | MongoDB Collection for Actions |  
| **GitHub Commits**          | Regular, Meaningful Messages |  

---  

## 👩‍💻 Developer  
**Erandi Gamage**  
Undergraduate Software Engineering Student  
Institute of Software Engineering (IJSE)
📧 hansierandi7@gmail.com 
🔗 [GitHub](https://github.com/erandie) | [LinkedIn](https://www.linkedin.com/in/erandie)  

---  

> **Note:** This project is submitted as part of **ITS 2120 – Rapid Application Development** coursework.  
> **Submission File:** `GDSE69_ITS2120_ErandiGamage.zip`  
> **Submitted to:** Google Classroom (on or before due date)

---

# RAD_Cource_Work
RAD Backend - https://github.com/erandie/RADCW_BookClub_Management_System_Backend.git
RAD Frontend - https://github.com/erandie/RADCW_BookClub_Frontend.git
