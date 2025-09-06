# Docpocket

*Profile Android App*

## Table of Contents
1. [Overview](#-overview)  
2. [Features](#-features)  
3. [Project Structure](#%EF%B8%8F-project-structure)  
4. [Tech Stack](#%EF%B8%8F-tech-stack)  
5. [Getting Started](#-getting-started)  
   - [Prerequisites](#prerequisites)  
   - [Installation](#installation)  
6. [Important Files](#-important-files)  
7. [Future Improvements](#-future-improvements)  
8. [License](#-license)
   
---

## 📌 Overview

This is an Android application developed using Java and Android Studio. The app appears to be a health-related profile & booking system, offering features like doctor appointments, health tracking, COVID updates, and emergency support.

---

## ✨ Features

- User profile management
- Doctor appointments and scheduling
- Health tracking for Heart, Brain, Kidney, Digestive system
- COVID-19 data integration
- Emergency services section
- Map integration for nearby healthcare
- Payments & Booking
- Multi-fragment navigation (Home, Appointments, Health, Profile, etc.)

---

## 🏗️ Project Structure

<img width="400" height="525" alt="Screenshot 2025-09-06 201712" src="https://github.com/user-attachments/assets/4a450840-e74a-4714-9137-89e5e4e6a324" />

---
 
## 🛠️ Tech Stack

- Language: Java
- Framework: Android SDK
- Database/Storage: (Check if using Firebase / SQLite – google-services.json suggests Firebase)
- Build System: Gradle

---

## 🚀 Getting Started

### Prerequisites
- Android Studio (latest version recommended)
- Android SDK 24+
- Gradle installed (comes with Android Studio)

---

## 📂 Important Files
- **`MainActivity.java`** – Entry point of the application

- **`ApiService.java`** – Handles API/network calls

- **`DoctorAdapter.java`**,**`CovidRegionAdapter.java`** – RecyclerView adapters

- **`google-services.json`** – Firebase configuration

---

## 🔮 Future Improvements
- Add user authentication (Firebase Auth)
- Improve UI/UX with Material Design
- Push notifications for appointments and reminders

---

## 📜 License

This project is for learning/development purposes. You may modify and use it as needed.
