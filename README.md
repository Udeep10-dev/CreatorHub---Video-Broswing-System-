# 🎬 C Hub – Online Video Browsing System

## 📌 Overview
**C Hub** is a robust, Java-based Online Video Browsing System developed as a **Year 2, Semester 1 OOP group project** at Sri Lanka Institute of Information Technology - Malabe.

It allows users to **browse, search, watch, upload, and manage videos**, including new movies, in a user-friendly interface while demonstrating core **Object-Oriented Programming principles**.

---

## 🛠 Technologies Used
| Component | Technology | Role |
| :--- | :--- | :--- |
| **Backend** | **Java** | Core backend logic, business rules, and strict OOP implementation. |
| **Frontend** | **HTML, CSS** | Structure, presentation, and styling of the user interface. |
| **Interactivity** | **JavaScript** | Dynamic behavior, form validation, and client-side processing. |
| **Database** | **MySQL**  | Persistence layer for storing video metadata, user profiles, and system settings. |

---

## 💡 Key Features

### 1. User Authentication & Profile Management
* Secure Login, logout, and robust session management.
* Edit profile: Update personal details, email, phone number, and profile picture.

### 2. Video Browsing & Search
* Browse a variety of videos and new movie releases by category.
* Search content efficiently using keywords, categories, and filters.
* Functionality to sort and preview videos before watching.

### 3. Watch & Upload Videos
* Watch videos online via an embedded video player.
* Content creators can upload videos, including adding necessary metadata and thumbnails.

### 4. Video Management & Moderation
* Creators can delete and edit their uploaded videos.
* Content moderator module reviews uploaded videos to ensure policy compliance before publishing.

### 5. System Security & Administration
* Admin dashboard for platform security updates and user activity monitoring.
* Tools to manage all videos, content, and core system settings.
* Handle user reports, complaints, and platform performance monitoring.

---

## 📐 Project Architecture (OOP Concepts)

This project was specifically structured to exemplify the four pillars of Object-Oriented Programming:

| OOP Concept | Application in C Hub | Related Module/Class |
| :--- | :--- | :--- |
| **Encapsulation** | Used for user profile security (e.g., hiding password hashing logic and controlling data access). | `User` Class |
| **Inheritance** | Implemented to define user roles with distinct permissions and features. | `User` $\rightarrow$ `Creator` $\rightarrow$ `Admin` |
| **Polymorphism** | Handling content types (Video vs. Movie) via a common interface (e.g., a single `play()` method). | `Content` Interface/Abstract Class |
| **Abstraction** | Hiding complex business logic like database connectivity and search algorithms from the service layer. | `DatabaseService` |

---

## 📂 Project Structure
