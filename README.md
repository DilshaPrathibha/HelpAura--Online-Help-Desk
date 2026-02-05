# Online Help Desk

A comprehensive web-based help desk management system built with Java that facilitates communication between students and administrators through ticket management, appointments, payments, and forum discussions.

## Features

- **User Authentication**: Secure login system for students and administrators
- **Ticket Management**: Create, view, edit, and delete support tickets
- **Appointment System**: Schedule and manage appointments with administrators
- **Forum & Chat**: Discuss issues and get help through community forums with reply functionality
- **Payment Processing**: Manage credit card information and process transactions
- **Admin Dashboard**: Monitor all system activities, manage users, and oversee support operations
- **User Profile Management**: Edit profile information and manage personal settings
- **Transaction History**: View and track payment transactions

## Project Structure

```
src/main/java/
├── model/              # Data models (Student, Admin, Ticket, Appointment, etc.)
├── services/          # Business logic services
├── servlet/           # HTTP request handlers
└── utils/             # Utility classes (Database connections, etc.)

src/main/webapp/       # Web resources (JSP pages, CSS, JavaScript)
```

## Technology Stack

- **Backend**: Java, Servlet/JSP
- **Database**: SQL-based database with JDBC connectivity
- **Frontend**: HTML, CSS, JavaScript
- **Build**: Maven/Gradle 

## Setup Instructions

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- Apache Tomcat 8.0 or higher
- MySQL or compatible database

### Installation

1. Clone the repository
2. Configure database connection in `src/main/java/utils/DBconnect.java`
3. Create the required database tables
4. Build the project and deploy to Tomcat server
5. Access the application via `http://localhost:8080/Online-Help-Desk`

## Usage

### For Students
1. Register or login to your account
2. Create and track support tickets
3. Schedule appointments with administrators
4. View transaction history and manage payment methods
5. Participate in forum discussions

### For Administrators
1. Login with admin credentials
2. View and manage all tickets and appointments
3. Process student requests
4. Monitor transactions and payments
5. Manage user accounts

## Project Status

This is an active development project for an educational/institutional help desk system.


