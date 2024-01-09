# DBMS-PROJECT-18CSL58
# Garage Go

Garage Go is a web-based garage management system developed using HTML, CSS, JavaScript, PHP, XAMPP, Apache servers, and MySQL database. It provides a user-friendly interface for managing various aspects of a garage, such as customer details, vehicle information, service records, and billing.

## Features

- User registration and login functionality.
- CRUD (Create, Read, Update, Delete) operations for customers, vehicles, services, and invoices.
- Search and filter functionality for easy data retrieval.
- Dashboard to display key statistics and summaries.
- Integration with MySQL database for data persistence.

## Technologies Used

- HTML: Markup language used for structuring the web pages.
- CSS: Styling language used for visually enhancing the application.
- JavaScript: Programming language used for client-side interactions and validations.
- PHP: Server-side scripting language used for handling dynamic content.
- XAMPP: A web server solution that bundles Apache, MySQL, and PHP for local development.
- Apache: Web server software used for hosting the application locally.
- MySQL: Relational database management system used for data storage.

## Installation and Setup

1. Install XAMPP: Download and install XAMPP from the official website (https://www.apachefriends.org/).

2. Clone the Repository: Use the following command to clone the Garage Go repository:

   ```shell
   git clone https://github.com/your-username/garage-go.git
   ```

3. Start XAMPP: Launch the XAMPP control panel and start the Apache and MySQL servers.

4. Import Database: Open the phpMyAdmin interface (http://localhost/phpmyadmin) and import the provided `garage_go.sql` file to create the required database structure and tables.

5. Configure Database Connection: In the project directory, locate the `config.php` file and update the database connection details such as host, username, password, and database name.

6. Run the Application: Open a web browser and visit `http://localhost/garage-go` to access the Garage Go application.
