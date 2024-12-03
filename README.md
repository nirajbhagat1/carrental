# Car Rental System

This Car Rental System project is designed to automate the vehicle rental and reservation process, allowing users to book vehicles online with ease. The system eliminates the need for manual bookings, reducing the chances of errors and improving overall customer satisfaction. It provides a user-friendly interface and robust functionality for managing vehicle reservations.

## Features

- **Online Booking**: Users can browse available vehicles and book them based on their preferred brands and price range.
- **Admin Dashboard**: Admin users have the ability to manage vehicle listings, user information, and reservations.
- **User Feedback**: Customers can provide feedback or complaints about the vehicles or services, which is stored in a secure database.
- **Reservation Validation**: The system ensures that bookings are correctly processed, preventing any double booking or errors.
- **Database Management**: All user and vehicle information is stored and managed in a secure MySQL database.

## Technologies Used

- **Frontend**: Basic PHP for dynamic web pages
- **Backend**: PHP for server-side scripting
- **Database**: MySQL for storing user and vehicle data
- **Server**: XAMPP (Apache, MySQL) for local server hosting
- **Editor**: Sublime Text for code editing
- **Version Control**: GitHub for version control and collaboration

## Tools and Libraries

- **XAMPP**: To set up Apache and MySQL servers for local development.
- **PHP**: For server-side scripting and handling user requests.
- **MySQL**: Database management for storing information like user data, bookings, and vehicle inventory.
- **Sublime Text**: A text editor used for writing and editing code.
- **GitHub**: For version control and project hosting.




## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/carrental.git
   
### 2. Set up XAMPP

- Install and launch **XAMPP** (Apache and MySQL services should be running).
  - You can download XAMPP from [here](https://www.apachefriends.org/index.html).
  - Once installed, open the **XAMPP Control Panel** and start the **Apache** and **MySQL** services.

### 3. Configure the Database

- Open **phpMyAdmin** from your browser (usually at `http://localhost/phpmyadmin`).
- Create a new database (DB name: `carrental`).
- Import the database schema:
  - Navigate to the `database` folder in this project and import the SQL file to create the necessary tables and data.

### 4. Run the Project

- Copy the project files into the `htdocs` directory in your XAMPP folder. 
  - Typically, the path will be something like `C:\xampp\htdocs\` on Windows or `/Applications/XAMPP/htdocs/` on macOS.
- Open your browser and navigate to `http://localhost/carrental` to access the system.
