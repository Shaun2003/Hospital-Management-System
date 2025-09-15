🏥 Hospital Management System (HMS)
<p align="center"> <img src="https://img.shields.io/badge/PHP-8A2BE2?style=for-the-badge&logo=php&logoColor=white" /> <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" /> <img src="https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white" /> <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" /> <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" /> </p>

A Facility Management System built in PHP that focuses on handling medical records and streamlining hospital operations.

This system provides features for managing patients, staff, reports, pharmacy inventories, and lab records — all within a secure and user-friendly environment.

✨ Features

👨‍⚕️ Doctor/Employee Panel

Login using Doctor ID & Password

Manage patient records, pharmacy, and lab reports

View and update inventories

Access detailed patient information and medical history

🛠 Admin Panel

Manage all personnel and patient data

Insert and update medication information

Track medicine stock and availability

Oversee overall system operations

📊 Reports & Records

Generate, view, and manage patient reports

Update laboratory and pharmacy information

👤 Profile Management

Doctors and staff can update their own profiles

🚀 Tech Stack

Backend: PHP

Database: MySQL

Server: XAMPP / Apache

🔑 Login Credentials
Admin

Email: admin@mail.com

Password: (leave blank if none provided)

Doctor

ID: YDS7L

Password: (enter assigned password)

📂 Project Structure
Hospital-Management-System/
│── backend/
│   ├── config/        # Database & configuration files
│   ├── assets/        # Styles, scripts, and includes
│   ├── doc/           # Doctor panel
│   ├── admin/         # Admin panel
│── database/          # SQL dump (if available)
│── index.php          # Entry point

⚙️ Installation Guide

Clone the repository:

git clone https://github.com/your-username/hospital-management-system.git


Move the project into your XAMPP htdocs folder:

C:/xampp/htdocs/HMS


Import the database:

Open phpMyAdmin

Create a new database (e.g., hms_db)

Import the provided .sql file

Configure the database in config.php:

$conn = new mysqli("localhost", "root", "", "hms_db");


Start Apache and MySQL from XAMPP.

Open the project in your browser:

http://localhost/HMS

📸 Screenshots (Optional)

<img width="1365" height="736" alt="Screenshot 2025-09-15 124544" src="https://github.com/user-attachments/assets/2746aa1c-9b6a-4223-bd86-adc08b183378" />
<br>
<img width="1358" height="734" alt="Screenshot 2025-09-15 124201" src="https://github.com/user-attachments/assets/74a70196-e86a-44c3-831b-0f0d3843acd1" />
<br>
<img width="1364" height="736" alt="Screenshot 2025-09-15 124225" src="https://github.com/user-attachments/assets/5c7f4625-e630-43e6-975c-ca4c5782912a" />
<br>
<img width="855" height="553" alt="Screenshot 2025-09-15 124427" src="https://github.com/user-attachments/assets/80f1e9b3-8729-4d0b-9486-e8a64eb9cfb4" />
<br>
<img width="1361" height="732" alt="Screenshot 2025-09-15 124508" src="https://github.com/user-attachments/assets/a8163f3e-019f-45d9-9b81-375d1e8a79ef" />
<br>
<img width="1365" height="731" alt="Screenshot 2025-09-15 124526" src="https://github.com/user-attachments/assets/80024e6e-5e77-499a-b56f-a1f4296197b4" />

<br>

🤝 Contributing

Contributions are welcome! If you’d like to improve this project:

Fork the repo

Create a new branch (feature/your-feature)

Commit changes

Push and open a Pull Request

📜 License

This project is open-source and available under the MIT License.
