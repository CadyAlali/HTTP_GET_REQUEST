# HTTP_GET_REQUEST
# Robot Direction Control and ESP32 Data Fetching

This project demonstrates how to control a robot's direction using a web interface and how to fetch data from a web server using an ESP32. The project consists of two main tasks:

1. Building a web page to control the robot's movement direction and connecting it to a database.
2. Using an ESP32 to send HTTP requests and fetch data from a web server.

## Task 1: Web Page for Robot Control

### Description

The first task is to build a web page that allows users to control the movement direction of a robot. The web page sends commands to a PHP script, which stores the commands in a database.

### Files

- index.html: The main web page containing the control buttons.
- control.php: The PHP script that handles the direction commands and interacts with the database.
- db_config.php: The database configuration file.
- style.css: (Optional) Additional styling for the web page.

### Instructions

1. Setup Database:
   - Create a MySQL database and a table to store the direction commands.
     

2. Configure Database Connection:
   - Update the db_config.php file with your database credentials.

3. Run Web Server:
   - Use XAMPP or any other local web server to host the index.html and PHP files.
   - Start the server and navigate to http://localhost/index.html.

### Usage

- Open the web page in your browser.
- Click the buttons to send direction commands (Forward, Backward, Left, Right, Stop).
- The commands are sent to control.php and stored in the database.
