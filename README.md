# DevTasks - Team Task Manager

DevTasks is a lightweight and efficient team task management system built with PHP and MySQL. This project demonstrates a strong grasp of full-stack web development, including backend logic, database management, and modern frontend design.

## Features
- **User Authentication** (Login & Registration with PHP Sessions)
- **Project Management** (CRUD operations for projects)
- **Task Management** (Assign tasks to team members, update status)
- **Role-Based Access Control** (Admin & User roles)
- **Real-Time Updates** (AJAX-based task status updates)
- **Responsive UI** (Built with Bootstrap/TailwindCSS)
- **Secure System** (Prepared Statements, XSS Protection, Password Hashing)
- **REST API Support** (Optional integration for future scalability)
- **Easy Deployment** (Run locally with XAMPP or Docker)

## Installation
### Requirements
- **PHP 8+**
- **MySQL 5.7+**
- **Apache/Nginx (or use XAMPP/Docker)**
- **Composer (for PHP package management)**

### Setup
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/devtasks.git
   cd devtasks
   ```
2. Install dependencies:
   ```sh
   composer install
   ```
3. Configure environment variables:
   ```sh
   cp .env.example .env
   ```
   Update `.env` with your database credentials.
4. Create the database and tables:
   ```sh
   php database/migrate.php
   ```
5. Start the development server:
   ```sh
   php -S localhost:8000 -t public/
   ```
6. Open `http://localhost:8000` in your browser.

## 🔧 Usage
- **Sign up and log in** to create your account.
- **Create new projects** and invite team members.
- **Assign tasks**, update progress, and track status in real-time.


## Contributing
Feel free to fork this project, submit issues, or create pull requests!

## License
This project is licensed under the MIT License.

