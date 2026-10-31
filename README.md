# 🍽️ Campus Food Ordering System

A web-based Campus Food Ordering System built with PHP and MySQL to help manage food ordering and campus canteen operations.

## 📖 About the Project

The Campus Food Ordering System is designed to organize food ordering through a web application. The project uses PHP for application logic, a SQL database for data storage, and Composer to manage PHP dependencies.

This repository contains the application source code, database file, routing files, and supporting resources.

## ✨ Project Components

- **Food Management** — Application modules for managing food-related data.
- **Shopping Cart** — Cart functionality for handling food selections.
- **User Access Control** — Role and permission management modules.
- **Authentication** — Authentication and authorization components.
- **Order Management** — Application modules for handling orders.
- **Email Integration** — PHPMailer dependency.
- **PDF Generation** — Dompdf dependency.
- **Google API Integration** — Google API Client dependency.

*The availability of individual features depends on the application configuration and implementation.*

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| PHP | Backend application |
| MySQL | Relational database |
| HTML, CSS, JavaScript | Web interface technologies |
| Apache | Local web server through XAMPP |
| Composer | PHP dependency management |
| PHPMailer | Email functionality |
| Google API Client | Google API integration |
| Dompdf | PDF generation |

## 📂 Project Structure

```text
Campus-Food-Ordering-System/
├── App/             # Application modules
├── Public/          # Public-facing application resources
├── inc/             # Supporting PHP files
├── routes/          # Routing definitions
├── view/            # Application views
├── vendor/          # Composer dependencies
├── composer.json    # Composer configuration
├── composer.lock    # Locked dependency versions
└── database1.sql    # SQL database file
```

## ✅ Requirements

Install the following software before running the project:

- [XAMPP](https://www.apachefriends.org/)
- [Composer](https://getcomposer.org/)
- [Git](https://git-scm.com/)
- A web browser

## 🚀 Installation and Setup

### 1. Clone the Repository

Open Git Bash or a terminal and run:

```bash
git clone https://github.com/htet-nandar-linn/Campus-Food-Ordering-System.git
```

Enter the project directory:

```bash
cd Campus-Food-Ordering-System
```

### 2. Configure XAMPP

1. Copy the project folder into `C:\xampp\htdocs`.
2. Open the XAMPP Control Panel.
3. Start **Apache** and **MySQL**.

### 3. Install PHP Dependencies

Open a terminal in the project directory and run:

```bash
composer install
```

This installs the dependencies defined in `composer.lock`.

### 4. Set Up the Database

1. Open [phpMyAdmin](http://localhost/phpmyadmin/).
2. Create a new MySQL database.
3. Select the database and open the **Import** tab.
4. Choose the `database1.sql` file from the project folder.
5. Start the import.

Configure the application's database connection settings to match your MySQL database name, username, and password. Check the project configuration files for the exact settings location.

### 5. Run the Application

Check the `Public/` directory and routing configuration to identify the correct application entry point. Open the application using the corresponding local Apache URL.

For example, if the configured entry point is under `Public/`, the URL may use:

```text
http://localhost/Campus-Food-Ordering-System/Public/
```

Adjust the URL if the project's routing or Apache configuration specifies a different entry point.

## 🔐 Security Notes

- Do not commit passwords, API keys, or other secrets.
- Keep local environment and database credentials private.
- Use appropriate permissions and validation for user input.
- Review the project's license before redistributing or modifying the original source code.

## 👩‍💻 Author

**GitHub:** [htet-nandar-linn](https://github.com/htet-nandar-linn)

## 📌 Repository

[Campus-Food-Ordering-System](https://github.com/htet-nandar-linn/Campus-Food-Ordering-System)

---

*Created for learning, development, and educational purposes.*
