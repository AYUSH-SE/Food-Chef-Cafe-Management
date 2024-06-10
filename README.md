# Food-Chef-Cafe-Management

Food Chef is a comprehensive cafe and restaurant management website, featuring both user and admin panels for streamlined operations.

## Installation Guide

Follow these steps to set up the Food Chef project on your local machine.

### Prerequisites
- **XAMPP or WAMPP**: Download and install one of these web server solutions.

### Setup Instructions

1. **Start XAMPP/WAMPP Services**
   - Open the XAMPP Control Panel.
   - Start the `[Apache]` and `[MySQL]` modules.

2. **Download the Project**
   - Clone the repository using Git Bash:
     cd C:\xampp\htdocs\
     git clone https://github.com/Sankhala-Rohit/Food-Chef-Cafe-Management.git

   - Alternatively, [download the project from GitHub](https://github.com/Sankhala-Rohit/Food-Chef-Cafe-Management.git) and extract the files to `C:\xampp\htdocs\`.

3. **Database Setup**
   - Open your browser and navigate to [phpMyAdmin](http://localhost/phpmyadmin).
   - Click on the "New" option in the sidebar.
   - Create a new database named `project`.
   - After creating the database, click on the "Import" tab.
   - Browse and select the SQL file located at `Food-Chef-Cafe-Management/database/project.sql`.
   - Click "Go" to import the database.

4. **Run the Project**
   - Open any browser and go to:
     - [User Panel](http://localhost/project)
     - [Admin Panel](http://localhost/project/admin)

5. **Admin Login Details**
   - **Username**: `admin`
   - **Password**: `admin123`
