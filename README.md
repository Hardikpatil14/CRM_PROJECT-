Customer Relationship Management (CRM) System
A web-based Customer Relationship Management (CRM) system developed as a semester 5 project for M.L. Parmar College Of Computer Science & IT. This application helps businesses manage customer interactions, track support tickets, and streamline sales and marketing processes.

📖 Introduction
The concept of CRM shifted business focus from being purely transactional to relational. This project aims to improve customer experience, automate repetitive tasks, lower customer acquisition costs, and boost overall business growth by managing healthy relationships with customers using Information Technology.

✨ Features
Based on the project objectives, this system includes:

User & Admin Portals: Separate interfaces for users and administrators.

Ticket Management: Users can create support tickets which are managed by the admin.

Quote Requests: Users can request quotes for services/products.

Profile Management: Users can manage their profiles and change passwords.

Sales & Marketing Support: Tools to help track customer data, improve operational efficiency, and increase customer retention.

Business Intelligence: Dashboards for admins to get a quick overview of company performance and customer engagement.

🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript, Bootstrap

Backend: PHP

Database: MySQL

Local Server Environment: XAMPP (Apache Server)

Design & Modeling: ER Diagrams, DFD (Data Flow Diagrams)

⚙️ Hardware & Software Requirements
Server / Development Machine:

Processor: Intel(R) Core(TM) i5-6300U (or equivalent)

RAM: 8.00 GB (Minimum)

Storage: 160 GB HDD

OS: Microsoft Windows 10 or above

Software: XAMPP, MySQL

Client Machine:

Any PC with Windows 10 or above compatibility

2 GB RAM

A modern web browser (Chrome, Firefox, Edge, etc.)

🚀 How to Run the Project Locally
Follow these steps to set up the project on your local machine:

Install XAMPP: Download and install XAMPP from apachefriends.org.

Start Services: Open the XAMPP Control Panel and start Apache and MySQL.

Clone the Repository:


git clone https://github.com/your-username/your-repo-name.git
Move Files: Move the cloned project folder into the htdocs directory of your XAMPP installation (e.g., C:\xampp\htdocs\crm-project).

Setup Database:

Open your browser and go to http://localhost/phpmyadmin/.

Create a new database (e.g., crm_database).

Import the .sql file provided in the project folder (if available) into this database.

Configure Connection: Open the PHP database connection file (usually db_connect.php or config.php) and update the database name, username (root), and password (usually blank by default) as per your setup.

Run the App: Open your browser and navigate to http://localhost/crm-project/.

