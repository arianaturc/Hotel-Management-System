# 🏨 Hotel Management System (Java, OOP, Swing, PostgreSQL)

## 📖 Overview
The **Hotel Management System** is a Java application that simulates the operations of a hotel reception desk.  
It supports **room management, bookings, customer check-in/check-out, facility usage, and financial reporting**, while ensuring data persistence via a PostgreSQL database.  

The system is built using **Object-Oriented Programming (OOP)** principles and includes a **Java Swing GUI** for interaction.

---

## 🎯 Purpose
The project provides a simulation of real-world hotel management tasks, aiming to:
- ✔️ Manage hotel rooms (status, type, price, capacity).  
- ✔️ Handle customer bookings, check-ins, check-outs, and cancellations.  
- ✔️ Allow booking of hotel activities (pool, spa, massage, breakfast, etc.).  
- ✔️ Support financial transactions, including cancellation fees and activity charges.  
- ✔️ Persist data (rooms, bookings, customers, activities) across sessions.  

---

## 🏗 System Design

### Main Classes
- **Hotel** → Central hub, manages rooms, users, and interactions with the database.  
- **Room** → Represents a room (number, type, capacity, status, price).  
- **User** → Superclass for all system users.  
  - **Customer** → Represents hotel guests, manages bookings, activities, and cancellations.  
  - **Employee (Receptionist)** → Manages check-ins/outs, payments, and facilities.  
- **DatabaseConnection** → Handles PostgreSQL connections.  
- **UserView (Swing GUI)** → Provides the graphical interface (buttons, panels, forms).  
- **UserController** → Connects GUI actions with backend logic.  

---

## 🖥 Features
- 🔐 **Login system** for users (customers & employees).  
- 🛏 **Room Management**: add, book, free, or cancel rooms.  
- 📅 **Booking System**: make and cancel bookings with penalty rules.  
- 💳 **Financial Management**: compute total charges (room nights + facilities).  
- 🏊 **Facilities Management**: add and book facilities (spa, breakfast, etc.).  
- 💾 **Database Integration** with PostgreSQL for persistence.  
- 🎨 **Swing GUI** for interactive use.  

---

## ⚙️ Tech Stack
- **Language**: Java  
- **Paradigm**: Object-Oriented Programming (OOP)  
- **GUI**: Java Swing  
- **Database**: PostgreSQL (via JDBC)  
