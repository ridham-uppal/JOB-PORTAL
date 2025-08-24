# 🏢 Job Portal – Full Stack Web Application  

## 📌 Project Overview  
The **Job Portal** is a full-stack web application that connects **job seekers** with **recruiters**. It allows recruiters to post and manage job listings while candidates can browse, apply, and track their applications. The project demonstrates **end-to-end CRUD operations**, authentication, and responsive UI design.  

---

## 🚀 Features  
- 🔐 **Authentication** – User signup & login with role-based access (Candidate / Recruiter)  
- 📄 **Job Management (CRUD)** – Recruiters can create, update, and delete job posts  
- 🔍 **Job Search & Filter** – Candidates can browse and filter jobs based on title, location, and category  
- 📑 **Application System** – Candidates can apply for jobs and manage their applications  
- 📱 **Responsive Design** – Fully optimized for mobile & desktop using **Tailwind CSS** + **shadcn/ui**  
- ⚡ **Real-time Updates** – Powered by Supabase for database & API integration  

---

## 🛠️ Tech Stack  

### **Frontend**  
- ⚛️ React.js – Component-based UI  
- 🎨 Tailwind CSS – Utility-first styling  
- 🖌️ shadcn/ui – Prebuilt accessible UI components  

### **Backend / Database**  
- 🗄️ Supabase – Handles authentication, database (PostgreSQL), and API endpoints  

---

## 📊 Database (PostgreSQL Schema)  
- **Users Table** → Stores user info (role: candidate/recruiter)  
- **Jobs Table** → Stores job details (title, description, location, salary, recruiter ID)  
- **Applications Table** → Stores applications (candidate ID, job ID, status)  

---

## ⚡ CRUD Operations Example  
- **Create**: Recruiter adds a new job posting  
- **Read**: Candidate fetches job listings  
- **Update**: Recruiter edits job details  
- **Delete**: Candidate deletes an application  

---

## 🎯 Purpose of the Project  
This project was built as a **group capstone project** to showcase skills in:  
- **Frontend development** (React, Tailwind, shadcn/ui)  
- **Backend integration** (Supabase & PostgreSQL)  
- **Authentication, state management, and CRUD operations**  

---

## 📸 Screenshots  
 <img width="1470" height="834" alt="image" src="https://github.com/user-attachments/assets/ba92b9d7-69f9-4bd2-97f4-3abcbf182f37" />
<img width="1470" height="835" alt="image" src="https://github.com/user-attachments/assets/3dccc5f3-4c67-4b82-9eb9-4959fff08bc1" />
<img width="1470" height="824" alt="image" src="https://github.com/user-attachments/assets/c9b87835-e184-4cd4-a275-283e80ec3314" />




---

## 🚀 Future Enhancements  
- Advanced job recommendations (AI/ML)  
- Resume parsing  
- Notifications for job status updates  

---

## 📦 Installation & Setup  

1. Clone the repository  
   ```bash
   git clone https://github.com/ridham-uppal/Job_Portal.git
   cd job-portal
