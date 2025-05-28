An archive management system built using Flutter and Dart for the frontend, with MySQL, and PHP, powering the backend. This project allows users to store, retrieve, and manage archival data efficiently with a modern window interface.
________________________________________
📚 Table of Contents
•	About
•	Features
•	Installation
•	Usage
•	API Reference
•	Technologies Used
•	Acknowledgements
________________________________________
🧾 About
This system provides a robust platform for archiving documents and records digitally, offering fast search, filtering, and data retrieval. The mobile interface ensures ease of use and accessibility while the backend ensures data integrity and storage security.
________________________________________
Features
•	Window app interface built with Flutter
•	User authentication (Login/Register)
•	Archive file upload, download, and view
•	Search and filter archived data
•	Backend API with PHP and MySQL
•	Analytics and history tracking
________________________________________
🛠️ Installation
Backend (PHP & MySQL)
1.	Clone this repository.
2.	Set up a local server using XAMPP or MAMP.
3.	Import the database.sql file into MySQL.
4.	Place the backend PHP files in the htdocs directory.
5.	Configure config.php with your database credentials.

$host = "localhost";
$user = "root";
$password = "";
$database = "archive_system";
Frontend (Flutter)
1.	Ensure Flutter SDK is installed.
2.	Clone this repository and navigate to the Flutter project directory.
3.	Run:
flutter pub get
flutter run
Make sure the emulator or device is properly connected.
________________________________________
▶️ Usage
•	Register or log in to the app.
•	Upload documents to the archive.
•	Use the search feature to find existing files.
•	View details and download documents as needed.
________________________________________
🔌 API Reference
All API endpoints are served via PHP backend.
Method	Endpoint	Description
POST	/api/login.php	User login
POST	/api/register.php	User registration
GET	/api/get_archives.php	Fetch all archives
POST	/api/upload_archive.php	Upload a file
GET	/api/download.php?id={id}	Download a file
________________________________________
🧰 Technologies Used
•	Flutter (Frontend)
•	Dart
•	MySQL (Database)
•	PHP (Backend/API)
•	JSON for data handling
________________________________________
🙌 Acknowledgements
•	Flutter Documentation – https://flutter.dev/docs
•	MySQL Documentation – https://dev.mysql.com/doc/
•	PHP Manual – https://www.php.net/manual/en/
•	Inspired by Open Source contributions

