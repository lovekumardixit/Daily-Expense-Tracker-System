# Daily Expense Tracker System

## Overview

The **Daily Expense Tracker System** is a web-based personal finance management application designed to help users efficiently monitor and manage their daily financial activities. The platform enables users to record expenses, manage income sources, track lending/borrowing, and generate analytical reports for better financial decision-making.

This project was developed using a traditional full-stack web architecture with PHP as the backend, MySQL as the database, and HTML/CSS/JavaScript for the frontend.

---

## Purpose of the Project

Managing personal finances manually can be time-consuming and prone to errors. This system provides users with:

* Daily expense tracking
* Income management
* Lending and borrowing records
* Financial reports and analytics
* User account management
* Secure login and signup system

The goal is to simplify personal financial management through automation and digital record keeping.

---

## Key Features

### User Authentication

* Secure user registration
* User login system
* Session management
* Planned JWT authentication for API security

### Expense Management

* Add daily expenses
* Edit/Delete expense records
* Manage categorized expenses
* Expense history tracking

### Income Management

* Add income records
* Manage multiple income sources
* Income history reports

### Lending Management

* Record borrowed money
* Record lent money
* Manage lending transactions

### Analytics & Reports

* Visual graphs for spending analysis
* Monthly and daily reports
* Financial summaries
* Dashboard insights

### Settings

* User profile settings
* Account customization

---

## Technologies Used

| Technology    | Role                           |
| ------------- | ------------------------------ |
| PHP           | Backend server-side scripting  |
| MySQL         | Relational database management |
| HTML5         | Web page structure             |
| CSS3          | User interface styling         |
| JavaScript    | Dynamic frontend functionality |
| Bootstrap     | Responsive UI framework        |
| XAMPP/WAMP    | Local server environment       |
| phpMyAdmin    | Database management            |
| JWT (Planned) | Secure API authentication      |

---

## Project Architecture

### Frontend:

* HTML
* CSS
* JavaScript
* Bootstrap

### Backend:

* PHP

### Database:

* MySQL

### Development Environment:

* XAMPP or WAMP

---

## Folder Structure

```bash
Daily-Expense-Tracker/
│
├── includes/           # Backend configuration and reusable components
├── images/             # Project assets
├── fonts/              # Font resources
├── .env                # Environment variables and DB credentials
├── expenditure.sql     # Database structure
├── index.php           # Main entry point
└── API_DOCS.md         # API documentation
```

---

## Installation Guide

### Prerequisites

Make sure the following are installed:

* XAMPP / WAMP
* PHP >= 7.x
* MySQL
* Web browser

---

### Setup Steps

#### Step 1: Clone or Download the Repository

```bash
git clone <repository-url>
```

Or download the ZIP file and extract it.

---

#### Step 2: Move Project Files

* For XAMPP: Place project folder in:

```bash
C:\xampp\htdocs\
```

* For WAMP: Place project folder in:

```bash
C:\wamp\www\
```

---

#### Step 3: Start Server

Open XAMPP/WAMP Control Panel and start:

* Apache
* MySQL

---

#### Step 4: Database Setup

1. Open phpMyAdmin:

```bash
http://localhost/phpmyadmin
```

2. Create a new database.

3. Import the SQL file:

```bash
expenditure.sql
```

---

#### Step 5: Configure Environment Variables

Update the `.env` file with your database credentials:

```env
DB_HOST=localhost
DB_NAME=your_database_name
DB_USER=root
DB_PASS=
```

---

#### Step 6: Run the Project

Open in browser:

```bash
http://localhost/Daily-Expense-Tracker-Using-PHP-and-MySQL
```

---

## Demo Credentials

```txt
Email: user@gmail.com
Password: 12345678
```

---

## Future Enhancements

The project roadmap includes:

* AI-powered expense categorization
* LLM-based financial chatbot
* UPI transaction auto-tracking
* Mobile app version
* OAuth authentication
* Cloud deployment
* Advanced analytics

---

## Advantages

* Easy financial management
* User-friendly dashboard
* Organized data storage
* Secure user system
* Scalable for future upgrades
* Suitable for personal budgeting

---

## Limitations

* Traditional codebase structure
* Limited scalability compared to modern frameworks
* Basic security implementation
* No real-time banking integration yet

---

## Recommended Modern Upgrades

For production-grade improvements:

* Spring Boot / Node.js backend
* React / Flutter frontend
* OAuth2 authentication
* Cloud database integration
* AI recommendation engine
* RESTful API optimization

---

## Conclusion

The Daily Expense Tracker System is a practical financial management solution that digitizes personal budgeting and expense monitoring. Built using PHP and MySQL, it serves as an excellent academic and real-world project while offering strong potential for modernization through AI, mobile development, and advanced financial automation.

---

## License

This project is licensed under the Apache-2.0 License.

---

## Contribution

Contributions are welcome for:

* Code optimization
* Feature enhancement
* Security improvements
* Mobile app development
* AI integrations

---

**Developed for efficient personal financial management and future-ready scalability.**

Auther:
Lav K. Dixit
