# PHP Admin Panel

A simple admin panel built with **PHP** and **MySQL**, created as a learning project during my full-stack development journey in 2022. This was my first backend project, designed to manage users and content through a web-based interface.

## Features
- **User Authentication**: Secure admin login and logout functionality using PHP sessions.
- **Dashboard**: A central interface to view key statistics or manage data.
- **CRUD Operations**: Create, read, update, and delete records (e.g., users or content) stored in a MySQL database.
- **Responsive Interface**: Basic HTML/CSS frontend, styled for usability on desktop and mobile devices.
- **Database Integration**: MySQL database to store and manage application data.

## Technologies Used
- **PHP**: Server-side scripting for backend logic.
- **MySQL**: Relational database for data storage.
- **HTML/CSS**: Frontend structure and styling.
- **JavaScript**: Basic interactivity (e.g., form validation).

## Prerequisites
To run this project locally, you need:
- A web server with PHP support (e.g., Apache via XAMPP, WAMP, or MAMP).
- MySQL database server.
- A modern web browser.

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/vickypandey14/php-admin-panel.git
   ```
2. **Set Up the Database**:
   - Create a MySQL database (e.g., `admin_panel`).
   - Import the `database.sql` file (located in the repository) into your database.
   - Update the database connection settings in `config.php` with your MySQL credentials:
     ```php
     $host = 'localhost';
     $user = 'your_username';
     $password = 'your_password';
     $database = 'admin_panel';
     ```
3. **Configure the Web Server**:
   - Place the project folder in your web server’s root directory (e.g., `htdocs` for XAMPP).
   - Ensure the server is running (Apache and MySQL).
4. **Access the Application**:
   - Open your browser and navigate to `http://localhost/php-admin-panel`.
   - Log in with the default admin credentials (check `database.sql` for details or set up a new admin user).

## Usage
- **Login**: Use the admin credentials to access the dashboard.
- **Manage Data**: Add, edit, or delete records via the interface.
- **Logout**: End your session securely.

## Notes
- This is a learning project and may not include advanced security features (e.g., prepared statements or password hashing). Use it for educational purposes only.
- Feel free to fork the repository and enhance it with additional features or improved security.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add new feature"`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## About the Developer
Hi, I'm Vivek (Vicky), a full-stack web developer passionate about building web applications. This project was built in 2022 as part of my learning journey. Check out my other projects on GitHub and consider leaving a ⭐ if you find this project helpful!
