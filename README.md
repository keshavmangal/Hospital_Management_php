Hospital Management System (HMS)
How to run the Auto/Taxi Stand Management Project Using PHP and MySQL

. Download the zip file
2. Extract the file and copy hospital folder
3.Paste inside root directory(for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/html)
4. Open PHPMyAdmin (http://localhost/phpmyadmin)
5. Create a database with name hms
6. Import hms.sql file(given inside the zip package in SQL file folder)
7.Run the script http://localhost/hospital (frontend)
Login Details
Login Details for admin : admin/Test@12345
Login Details for Patient: johndoe12@test.com/Test@123
Login Details for Doctor: anujk123@test.com/Test@123

Introduction
The **Hospital Management System (HMS)** is a comprehensive and integrated software solution designed to streamline and enhance the administrative and clinical operations of healthcare facilities, such as hospitals, clinics, and medical centers. It serves as the digital backbone of modern healthcare institutions, providing a wide range of functionalities to facilitate efficient patient care, resource management, and overall hospital administration.

Key Features

1. Patient Information Management
- Centralized database of patient records.
- Includes personal details, medical history, diagnosis, treatment plans, and billing information.
- Streamlines patient registration and ensures easy access to critical information.

2. Appointment Scheduling
- Allows patients to book appointments online or through the hospital's reception.
- Enables healthcare providers to manage their schedules efficiently.

3. Electronic Health Records (EHR)
- Digital storage and management of patient medical records.
- Real-time access and updates to patient data.
- Facilitates better-informed clinical decisions.

4. Billing and Invoicing
- Automates the billing process, generating invoices, tracking payments, and managing insurance claims.
- Simplifies financial operations within the healthcare facility.

5. Inventory Management
- Manages the inventory of medical supplies, equipment, and pharmaceuticals.
- Ensures items are well-stocked and facilitates reordering when necessary.

6. Pharmacy Management
- Manages drug inventories, prescriptions, and dispensing.
- Ensures accurate administration of medications to patients.

7. Laboratory and Imaging Management
- Tracks lab tests and imaging services, including test requests, results, and digital imaging storage.

8. Staff Management
- Manages employee records, attendance, and payroll.
- Facilitates staff scheduling and allocation of duties.

9. Data Security and Compliance
- Ensures compliance with data protection regulations (e.g., HIPAA in the United States).
- Maintains confidentiality and security of patient information.

10. Reporting and Analytics
- Generates reports on various aspects of hospital operations.
- Enables data-driven decision-making and performance analysis.

11. Telemedicine Integration
- Facilitates remote consultations and video conferencing with patients.
- Enhances accessibility and convenience for patients and healthcare providers.

12. Mobile Access
- Provides mobile apps for healthcare providers and patients.
- Enhances accessibility and convenience.
- 
1. Patient Registration:
   - Capture and manage patient demographic information.
   - Assign unique patient identifiers.
   - Maintain patient records and history.





2. Appointment Scheduling:
   - Schedule and manage patient appointments with doctors and other healthcare providers.
   - Send appointment reminders to patients.





3. Electronic Health Records (EHR):
   - Store and manage patient medical records electronically.
   - Support for creating, updating, and accessing patient health information.
   - Security measures to protect sensitive patient data.



4. Electronic Medical Records (EMR):
   - Maintain patient-specific medical histories.
   - Easily share medical records with authorized personnel.



5. Reporting and Analytics:
   - Generate reports on various aspects of hospital operations.
   - Analyze data for decision-making and performance improvement.


6.Staff Management:
-Maintain records of hospital staff, including doctors, nurses, and support staff.
-Manage employee schedules and payroll.








6. Patient Portal:
   - Allow patients to access their medical records and appointment details online.
   - Enable patients to communicate with healthcare providers securely.



7. Telehealth Support:
   - Enable virtual consultations and telemedicine services.
These features help streamline hospital operations, improve patient care, reduce administrative overhead, and enhance the overall efficiency of healthcare facilities. The exact feature set and customization options may vary depending on the specific HMS solution and the needs of the hospital.

















Technologies Used
- **Backend**: Node.js
- **Frontend**: Angular, HTML, CSS
- **Database**: MySQL, MongoDB
- **Others**: GitHub for version control, Mongoose for managing MongoDB data, and other tools and libraries as needed.

Installation and Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/HospitalManagementSystem.git
   ```

2. **Install the necessary dependencies**:
   ```bash
   cd HospitalManagementSystem
   npm install
   ```

3. **Set up the database**:
   - Ensure MySQL and MongoDB are installed and running.
   - Create the required databases and configure the connection settings in the application.

4. **Run the application**:
   ```bash
   npm start
   ```

5. **Access the application**:
   - Open your browser and go to `http://localhost:3000` (or the port you've configured).

Contribution
Contributions to the HMS project are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Contact
For any inquiries or feedback, please reach out:

Email: keshav.mangal02@gmail.com
LinkedIn: [Keshav Mangal](https://www.linkedin.com/in/keshav-mangal-14a36623b/)

---

This README file provides a comprehensive overview of your Hospital Management System project, including key features, technologies used, installation instructions, and contribution guidelines. Feel free to adjust any details specific to your implementation!
