# 📚 BiblioSphere

**BiblioSphere** is a full-featured e-commerce platform specifically tailored for book-centric businesses. Built with a modern tech stack, it seamlessly integrates a responsive React frontend with a robust Spring Boot backend, providing both users and admins a powerful and secure experience.

---

## 🧩 Features

- 🔐 **JWT-based authentication & role-based access control**  
  Secure login for users, admins, and sales managers with distinct privileges.

- 🧑‍💼 **Admin & Sales Manager Panels**  
  Manage categories, inventory, product listings, pricing, orders, and refund requests.

- 💻 **React + Tailwind Frontend**  
  Responsive and clean user interface with a mobile-first design.

- 🧠 **Spring Boot + MongoDB Backend**  
  RESTful API built on a scalable Java backend using NoSQL document storage.

- ☁️ **Cloudinary Integration**  
  Upload and host book images on the cloud.

- 📄 **PDF Invoice Generation**  
  Automatically create downloadable invoices for each completed order.

- 📦 **Real-time Stock & Sales Updates**  
  Live inventory changes and sales tracking.

- 📧 **Email Notifications**  
  Confirmation and status update emails sent via EmailJS.

- 📊 **Dashboard Charts**  
  Sales and product analytics using Chart.js.

---

## 🛠️ Tech Stack

**Frontend**  
- React  
- Tailwind CSS  
- EmailJS  
- Chart.js  

**Backend**  
- Java  
- Spring Boot  
- MongoDB  
- JWT Authentication  

**Other**  
- Cloudinary (media hosting)  
- HTML-to-PDF (for invoice generation)

---

## 🎯 Goals & Use Cases

BiblioSphere aims to provide a professional, scalable, and customizable online bookstore platform. This project demonstrates:

- End-to-end full-stack application design  
- Real-world implementation of authentication, media management, and analytics  
- Modular backend/frontend separation with clear role responsibilities

---

## 📂 Project Structure (Simplified)

```bash
BiblioSphere/
├── backend/             # Spring Boot application
│   └── src/main/java/com/bibliosphere
├── frontend/            # React frontend
│   └── src/components/
├── uploads/             # Cloudinary integration logic
└── README.md
