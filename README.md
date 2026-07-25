# 🚀 Hacking The Future

> **An interactive STEM learning platform** that empowers **Young Students, Parents, and Educators** through gamified learning, educational events, quizzes, and community engagement. The platform aims to make STEM education engaging while supporting the **United Nations Sustainable Development Goals (SDGs)**.

---

# 📖 Overview

**Hacking The Future** is a JavaFX desktop application developed for the **WIA1002 Data Structure Group Project** at Universiti Malaya.

The application bridges traditional STEM education with interactive learning through quizzes, educational events, parent-child collaboration, leaderboards, and social features.

### 🌍 Supported SDGs

- 📚 **SDG 4** – Quality Education
- 💡 **SDG 9** – Industry, Innovation and Infrastructure
- 🤝 **SDG 17** – Partnership for the Goals

---

# ✨ Features

## 🔐 Authentication System

A complete user authentication system with secure account management.

### Features

- 👤 User Registration
- 🔑 Secure Login
- 📧 Login using Username or Email
- 🔒 SHA-3 Password Hashing
- 🔄 Forgot Password via Email
- ✅ Username & Password Validation
- 📍 Automatic User Coordinate Generation
- 🎭 Multi-role Registration
  - 👦 Young Student
  - 👨‍👩‍👧 Parent
  - 👩‍🏫 Educator

---

## 👥 Role-Based Access Management

Different users have access to different functionalities.

### 👦 Young Student

- 📝 Attempt STEM Quizzes
- 📅 Register for Events
- 🏆 Earn Reward Points
- 👤 View Profile
- 💬 Participate in Discussions
- 🤝 Manage Friends

### 👨‍👩‍👧 Parent

- 🎫 Book STEM Destinations
- 👶 Manage Children
- 📅 View Events
- 📋 View Booking History
- 💬 Participate in Discussions

### 👩‍🏫 Educator

- ➕ Create Events
- ➕ Create Quizzes
- 📊 Monitor Student Participation
- 👤 View Contribution Statistics
- 💬 Participate in Discussions

---

## 👤 User Profile

Each user has a personalized profile.

### Includes

- Username
- Email
- User Role
- Location Coordinates
- Current Points
- Friends List
- Parent-Child Relationship
- Booking History (Parents)
- Created Quizzes & Events (Educators)

---

## 📅 Event Management

Educators can organize STEM learning activities.

### Features

- ➕ Create Events
- ✏️ Edit Events
- 🗑️ Delete Events
- 📍 Venue Management
- 📆 Event Scheduling
- 📝 Event Description
- 👥 Student Registration
- 🎁 Reward Point System
- ⚠️ Clash Detection

---

## 🧠 Quiz System

Interactive STEM quizzes designed to encourage learning.

### Features

- 🎯 Theme-based Quizzes
- 🔍 Filter by Category
- 📝 Attempt Quizzes
- 🏅 Reward Points
- 🌐 Quizizz Integration
- 👩‍🏫 Educator-created Quizzes

---

## 🎫 STEM Destination Booking

Parents can arrange educational trips for their children.

### Features

- 📍 Suggested STEM Destinations
- 📏 Distance Calculation
- 🕒 Available Time Slots
- ⚠️ Booking Clash Detection
- 👶 Child Selection
- 📅 Booking Management

---

## 👨‍👩‍👧 Parent-Child Relationship

Supports family-based learning.

### Features

- 👨‍👩‍👧 Link Parent & Child Accounts
- 📊 Monitor Learning Progress
- 🏆 View Children's Reward Points
- 👨‍👩‍👧 Multiple Children Support
- 🔗 Parent Information in Student Profile

---

## 🏆 Global Leaderboard

Gamification encourages continuous learning.

### Features

- 🥇 Student Rankings
- ⭐ Point Tracking
- 📈 Live Score Updates
- 👀 Compare Performance
- 🎖️ Achievement Motivation

---

## 🤝 Friend System

Build a STEM learning community.

### Features

- 🔍 Search Users
- ➕ Send Friend Requests
- 📧 Email Notifications
- ✅ Accept / Reject Requests
- 👥 Friend List Management
- ❌ Remove Friends
- 👤 View Friend Profiles

---

## 💬 Discussion Forum

Encourages collaboration among students, parents, and educators.

### Features

- 💭 Create Discussions
- 💬 Reply to Discussions
- 👨‍👩‍👧 Community Interaction

---

# 🔒 Security Features

The application prioritizes user security through multiple mechanisms.

- 🔐 SHA-3 Password Hashing
- 🔑 Secure Authentication
- 📧 Email-based Password Recovery
- ✅ Input Validation
- 🛡️ Protected User Credentials

---

# 🗄️ Data Storage

The project uses both **CSV files** and **SQLite Database**.

### 📄 CSV Storage

- 👤 User Information
- 👥 Friend Lists
- 🤝 Friend Requests
- 📍 Booking Destinations

### 🗄️ SQLite Database

- 📅 Events
- 🧠 Quizzes
- 📝 Event Registrations
- 🏅 Reward Points

---

# ⚙️ Technologies Used

| Technology | Purpose |
|------------|---------|
| ☕ Java | Core Application Development |
| 🎨 JavaFX | Desktop Graphical User Interface |
| 🗄️ SQLite | Event & Quiz Database |
| 📄 CSV Files | Persistent User Data Storage |
| 🔐 SHA-3 | Password Hashing |
| 📧 JavaMail API | Email Notifications |
| 🧩 Object-Oriented Programming | System Architecture |
| 📚 Data Structures | Arrays, Lists & Queues |

---

# 🏗️ System Architecture

```text
Users
│
├── 👦 Young Student
│   ├── Attempt Quiz
│   ├── Register Event
│   ├── Earn Points
│   ├── Manage Friends
│   └── View Leaderboard
│
├── 👨‍👩‍👧 Parent
│   ├── Book STEM Destinations
│   ├── Manage Children
│   └── Monitor Learning Progress
│
└── 👩‍🏫 Educator
    ├── Create Quiz
    ├── Create Event
    └── Manage Activities

            │
            ▼

     CSV Storage + SQLite Database

            │
            ▼

     JavaFX Desktop Application
```

---

# 🎯 Project Objectives

The platform aims to:

- 🌍 Promote STEM Education
- 🎮 Encourage Learning through Gamification
- 📚 Increase Student Engagement
- 👨‍👩‍👧 Strengthen Parent-Child Collaboration
- 👩‍🏫 Provide Educators with Management Tools
- 🤝 Support the United Nations Sustainable Development Goals

---

# 👨‍💻 Team Members

**Group:** **DUBIDUBIDU**

- 👨‍💻 Khor Rui Zhe
- 👨‍💻 Chow Shino
- 👨‍💻 Ooi Rui Zhe
- 👨‍💻 Ong Zhao Qian
- 👨‍💻 Matthewdass A/L Sandanadass

---

# 🚀 Future Improvements

Potential enhancements include:

- 🌐 REST API Integration
- 📱 Mobile Version
- ☁️ Cloud Database Synchronization
- 🤖 AI-powered STEM Recommendations
- 🏅 Achievement Badges & Missions
- 📊 Learning Analytics Dashboard
- 💬 Real-time Chat
- 🔔 Push Notifications
- 🗺️ GPS-based STEM Activity Recommendations

---

# 📜 License

This project was developed as part of the **WIA1002 Data Structure** course at **Universiti Malaya** for academic purposes.
