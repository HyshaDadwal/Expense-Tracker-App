#  Expense Tracker App (Full Stack)

##  Overview

A full-stack **Expense Tracker Web Application** that allows users to securely manage their expenses with authentication, CRUD operations, and a responsive UI.

This project is built using **Spring Boot (Backend)** and **React (Frontend)**, following a clean layered architecture.

---

##  Features

###  Authentication

* User Registration & Login
* JWT-based Authentication
* Secure API access

###  Expense Management

* Add Expense
* View All Expenses
* Edit Expense
* Delete Expense
* User-specific data handling

###  Frontend (React)

* Responsive UI
* API integration using Axios
* Token-based session handling

---

##  Tech Stack

### Backend:

* Java
* Spring Boot
* Spring Security
* JWT (JSON Web Token)
* JPA / Hibernate

### Frontend:

* React.js
* Axios
* HTML, CSS, JavaScript

### Database:

* MySQL

---

##  Project Structure

```
expense-tracker-app/
├── expense-app-frontend/        # React Frontend
└── expense-intelligence-system/ # Spring Boot Backend
```

---

##  Setup & Installation

###  Backend Setup

```bash
cd expense-intelligence-system
mvn spring-boot:run
```

* Runs on: `http://localhost:8080`

---

###  Frontend Setup

```bash
cd expense-app-frontend
npm install
npm start
```

* Runs on: `http://localhost:3000`

---

##  API Endpoints

### Auth

* `POST /auth/register` → Register user
* `POST /auth/login` → Login & get JWT

### Expenses

* `GET /expenses` → Get all expenses
* `POST /expenses` → Add expense
* `PUT /expenses/{id}` → Update expense
* `DELETE /expenses/{id}` → Delete expense

---

##  Testing

* Tested using Postman
* Verified:

  * Authentication flow
  * CRUD operations
  * Secure endpoints

---

##  Future Enhancements

* Personal Finance Upgrade (Income + Expense tracking)
* Transaction Analytics Dashboard
* Graphs & Insights
* Budget Tracking
* Cloud Deployment (AWS / Render / Vercel)

---


