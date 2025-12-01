# ✅ WomanUP Test Task - Simple Todo Application

<div align="center">

![React](https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-4.9.3-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-9.14.0-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![React Router](https://img.shields.io/badge/React_Router-6.4.3-CA4245?style=for-the-badge&logo=react-router&logoColor=white)

**A simple Todo application with Firebase integration and real-time updates**

*Test task for WomanUP company - A straightforward todo list application demonstrating React, TypeScript, and Firebase integration*

[Features](#-features) • [Tech Stack](#-tech-stack) • [Project Structure](#-project-structure) • [Key Features](#-key-features)

</div>

---

## 📖 About

**WomanUP Todo List** is a simple todo application built as a **test task for WomanUP company**. The application provides a straightforward CRUD (Create, Read, Update, Delete) interface for managing todos with real-time synchronization using Firebase Firestore.

This project was developed as part of the recruitment process for WomanUP, demonstrating basic React development skills, TypeScript implementation, and Firebase integration. It features a simple user interface with visual indicators for task status, deadline tracking, and file attachments.

---

## 🛠 Tech Stack

### Core Technologies
<div align="center">

| Category | Technology | Version |
|----------|-----------|---------|
| **Library** | ![React](https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react&logoColor=black) | 18.2.0 |
| **Language** | ![TypeScript](https://img.shields.io/badge/TypeScript-4.9.3-3178C6?logo=typescript&logoColor=white) | 4.9.3 |
| **Backend** | ![Firebase](https://img.shields.io/badge/Firebase-9.14.0-FFCA28?logo=firebase&logoColor=black) | 9.14.0 |
| **Routing** | ![React Router](https://img.shields.io/badge/React_Router-6.4.3-CA4245?logo=react-router&logoColor=white) | 6.4.3 |
| **Styling** | ![SASS](https://img.shields.io/badge/SASS-1.56.1-CC6699?logo=sass&logoColor=white) | 1.56.1 |

</div>

### Firebase Services
<div align="center">

| Service | Purpose |
|---------|---------|
| **Firestore** | Real-time database for todos |
| **Storage** | File upload and storage |

</div>

## 🔥 Firebase Integration

### Firestore Database
- **Collection**: `todos`
- **Document Structure**:
  ```typescript
  {
    heading: string
    description: string
    deadLine: string
    url: string (file URL)
    timestamp: serverTimestamp()
  }
  ```
- **Real-time Listeners**: Automatic updates using `onSnapshot`
- **CRUD Operations**: Create, Read, Update, Delete

### Firebase Storage
- **File Upload**: Secure file storage
- **Download URLs**: Generated URLs for file access
- **File Management**: Upload and replace files

---

## 👨‍💻 Development Notes

This project was developed as a **test task for WomanUP company** - a simple todo application demonstrating:

- Basic React development with hooks
- TypeScript implementation and type safety
- Firebase integration (Firestore and Storage)
- Real-time data synchronization
- File upload and management
- Date handling and validation
- Simple UI design
- Clean component architecture

The application showcases basic proficiency in:
- React Router for navigation
- Firebase SDK v9+ modular API
- Real-time listeners
- Form handling and validation
- State management
- Error handling
