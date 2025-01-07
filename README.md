# 🎉 Event Management System

## 🎯 About
Event Management System is a robust web application built using Spring Boot that streamlines the process of event planning, booking, and management. It provides a user-friendly interface for both event organizers and attendees while offering powerful administrative tools for system management.

## ✨ Features

### For Users
- 👤 User registration and authentication
- 🔍 Browse and search events by category, date, or location
- 📅 Event booking and registration
- 💳 Secure payment processing
- 📧 Email notifications for bookings and updates
- 👥 User profile management
- 📱 Responsive design for mobile access

### For Event Organizers
- 📊 Event creation and management dashboard
- 📈 Analytics and reporting tools
- 👥 Participant management
- 📨 Mass email communication
- 📅 Event scheduling tools

### For Administrators
- 👑 Complete system control
- 👥 User management
- 🎫 Event approval system
- 📊 Advanced analytics dashboard
- ⚙️ System configuration management

## 🛠 Technology Stack
- **Backend**
  - Java 11
  - Spring Boot 2.6.1
  - Spring Security
  - Spring Data JPA
  - Spring Mail

- **Frontend**
  - JSP & JSTL
  - Bootstrap 5
  - JavaScript
  - jQuery
  - AJAX

- **Database**
  - MySQL 8.0

- **Tools & Utilities**
  - Maven
  - Apache Tomcat
  - Git

## 📋 Prerequisites
- JDK 11 or later
- Maven 3.6.x or later
- MySQL 8.0
- IDE (Spring Tool Suite/Eclipse/IntelliJ IDEA)
- Git

## 🚀 Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/Event-Management-System.git
   cd Event-Management-System
   ```

2. **Database Setup**
   ```sql
   CREATE DATABASE event_management;
   ```
   - Update database configuration in `src/main/resources/application.properties`
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/event_management
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```

3. **Build the Project**
   ```bash
   mvn clean install
   ```

4. **Run the Application**
   ```bash
   mvn spring-boot:run
   ```
   Access the application at `http://localhost:8080`

## 📁 Project Structure
```
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── Event/
│   │           ├── controllers/
│   │           ├── models/
│   │           ├── repositories/
│   │           ├── services/
│   │           └── config/
│   ├── resources/
│   │   └── application.properties
│   └── webapp/
│       ├── assets/
│       │   ├── css/
│       │   ├── js/
│       │   └── images/
│       └── views/
└── test/
```

## 👥 User Roles & Capabilities

### 1. Guest User
- View events
- Register account
- Search events

### 2. Registered User
- Book events
- Manage profile
- View booking history
- Rate and review events

### 3. Event Organizer
- Create and manage events
- View participant lists
- Generate event reports
- Send notifications

### 4. Administrator
- Manage all users
- Approve/reject events
- System configuration
- Generate system reports

## 📸 Screenshots

### Home Page
![Home Page](screenshots/home.png)

### Event Creation
![Event Creation](screenshots/event-creation.png)

### Admin Dashboard
![Admin Dashboard](screenshots/admin-dashboard.png)

### User Profile
![User Profile](screenshots/user-profile.png)




