Project Overview:
HealthConnect Portal is a responsive, full-stack web application that digitises the daily workflow of a small clinic.
Doctors can register patients, record appointments and diagnoses, issue prescriptions and review a patient’s complete medical
history. Patients can securely log in to view their own appointments and prescriptions and to update their contact details. 
The application uses a Flask backend, a MySQL relational database and a Bootstrap 5 interface that adapts to desktop, 
tablet and mobile screens.

Key Features:
Role-based access for doctors and patients, using session-based authentication
Patient registration with duplicate security-ID validation
Appointment and diagnosis records, and prescription management
On-demand medical-history viewer that loads without a page refresh (AJAX)
Patient self-service profile editing in a modal window
Responsive layout, flash notifications and cache control after logout

Technology Stack:
Backend:Python, Flask, Jinja2
Database:	MySQL, mysql-connector-python
Frontend:	HTML5, CSS3, Bootstrap 5, Bootstrap Icons,JavaScript,AJAX

Programming Concepts and Skills Demonstrated:
Responsive design with the Bootstrap grid system
AJAX requests to the application’s own Flask endpoints, exchanging JSON, to update parts of a page without reloading
Request routing in Flask: GET and POST methods, dynamic URL parameters
Session management and authentication for two separate user roles
Custom Python decorator (no_cache) to control browser caching
Server-side rendering with Jinja2 templates, including partial templates
Post/Redirect/Get pattern to prevent duplicate form submissions

Database design and access:
Relational schema with primary and foreign keys
Parameterized SQL queries to prevent SQL injection
JOIN queries across related tables
CRUD operations with transaction handling (commit and rollback)


