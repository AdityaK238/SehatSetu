This project is a comprehensive application designed to streamline the management processes within a hospital. This system features three main dashboards for different types of users: Admin, Doctor, and Patient. Each user can log in to their respective accounts using their email and password. The system is designed to ensure efficient management of patient prescriptions, medication reminders, and more.

Features Admin Dashboard Manage Doctors: Add, update, and delete doctor profiles. Prescriptions: Send prescriptions to patients. Reminders: Send timely medication reminders to patients. Translation: Use Google Translate API to translate prescription details from English to Kannada for better patient understanding. Text-to-Speech: Use Google Cloud API for converting text to speech for patients who need audio guidance. Doctor Dashboard View Patient Profiles: Check which patient is having his apointment and get to know how many patients have booked the appointment. View his upcomming sessions and manage his sessions Patient Dashboard View Prescriptions: Access prescriptions sent by the admin. Medication Reminders: Receive notifications for medication timings. View the available slots for appointments. Book appointments to docters of there choice Translate Prescriptions: Use the translate feature to understand prescriptions in Kannada. Audio Guidance: Utilize text-to-speech functionality for hearing prescription instructions.

Technology Stack Frontend:Html,css,bootstrap Backend: PHP Database: MySQL APIs: Google Translate API (for translating text from English to Kannada) Google Cloud Text-to-Speech API (for converting text to speech) Installation To get started with the project, clone the repository and follow the steps below:

Clone the repository:

sh Copy code git clone <repository-url> cd foldername

HOW TO GET STARTED? 1.Open your XAMPP Control Panel and start Apache and MySQL. 2.Extract the downloaded source code zip file. 3.Copy the extracted source code folder and paste it into the XAMPP's "htdocs" directory. 4.Browse the PHPMyAdmin in a browser. i.e. http://localhost/phpmyadmin 5.Create a new database naming edoc. 6.Import the provided SQL file. The file is known as SQL_Database_edoc.sql located inside the source code root folder. 7.Browse the Doctor's Appointment System in a browser. i.e. http://localhost/edoc-echanneling-main/. Usage Login: Admin:admin@edoc.com psw:123 , doctors, and patients can log in using their registered email and password.

Contribution Contributions to this project are welcome. To contribute, please fork the repository, create a new branch for your feature or bugfix, and submit a pull request for review.

Further Exploration For a detailed exploration of the features and functionalities, clone the repository and explore the codebase.
