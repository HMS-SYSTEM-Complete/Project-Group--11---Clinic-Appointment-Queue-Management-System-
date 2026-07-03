# Project-Group--11---Clinic-Appointment-Queue-Management-System-
<br>
Project Proposal Document
<br>
This document serves as the foundation of our project. We collaboratively wrote it to define the initial vision, scope, and objectives of the system, setting the boundaries for what our clinic management platform would achieve and why it was necessary.
<br>
<br>
Software Requirements Specifications (SRS)
<br>
Functional & Non-Functional Requirements: We collaboratively developed the Software Requirements Specifications (SRS).
<br>
Version Control: You will find multiple versions of this document. We refined it iteratively as our understanding of the system grew, moving from the initial baseline requirements to a highly detailed functional breakdown.
<br>
<br>
Software Design Specification (SDS)
<br>
Design Document: The Software Design Document was co-authored by Najaf Ali and Farhal Abbas.
<br>
Version Control: This document evolved significantly through versioning. The earlier versions outline basic system components and logic, while the final versions detail our comprehensive 3-tier web architecture, database schemas, and security protocols.
<br>
<br>
ERD Entities Document
<br>
This document acts as our comprehensive data dictionary. It details every table, column, data type, and primary/foreign key used in the backend.
<br>
Version Control: We updated this document across different versions to reflect the normalization of our database, eventually leading to our finalized supertype/subtype 
<br>
architecture.
<br>
<br>
System Diagrams
<br>
Visualizing the architecture was a key part of our engineering process.
<br>
<br>
Use Case Diagram: This diagram describes the system’s interactions, user roles, and functional behavior.
<br>
<br>
Entity-Relationship Diagram (ERD): This diagram maps out the complete relational database architecture. It was designed utilizing standard industry Crow's Foot notation to accurately represent the strict one-to-many and one-to-one relationships between patients, doctors, appointments, and medical records.
<br>
<br>
Data Flow Diagram (DFD): This diagram illustrates how information moves through our system, tracking the data from the moment a patient registers, through the active queueing and consultation processes, down to the final billing phase.
<br>
<br>
Test Case Document
<br>
We built the Test Document to validate our finished code against our initial plans. It is split into two parts:
<br>
Functional UI Tests (Black-Box): Derived directly from our SRS to ensure the user interface meets the requirements of patients and staff.
<br>
Integration Tests (White-Box): Derived from our SDS and ERD to validate the internal database constraints, state-machine logic, and security mechanisms.
<br>
<br>
Note on Version History:
You can check the commit history of this repository to view the upload times and dates for each file. Please note that while the commit history reflects our recent repository activity, several document versions were actually created earlier in our iterative development process and are just being uploaded now.
<br>
<br>
How to Run the Project Locally:
<br>
<br>
The complete project source code and assets have been compressed and uploaded to this repository as a .rar file in Project Website Folder. Follow these steps to deploy and run the system on your personal computer:
<br>
Prerequisites:
<br>
Local Server Environment: Download and install XAMPP (or WAMP/LAMP) which includes the required Apache HTTP server and MySQL database engine.
<br>
Extraction Tool: You will need software like WinRAR or 7-Zip to extract the .rar archive.
<br>
Setup Instructions
<br>
<br>
Download and Extract:
<br>
Download the .rar file from this repository and extract its contents to a folder on your computer.
<br>
Move to the Server Directory:
<br>
Copy the extracted project folder and paste it into the htdocs directory of your XAMPP installation.
<br>
Windows default path: C:\xampp\htdocs\
<br>
<br>
Start the Local Server:
<br>
Open the XAMPP Control Panel and click Start next to both the Apache and MySQL modules.
<br>
<br>
Set Up the Database:
<br>
Open your web browser and navigate to http://localhost/phpmyadmin.
<br>
Click on New in the left sidebar to create a new database. (Check the /config/database.php file in the project folder for the exact database name expected by the system).
<br>
Select the newly created database, go to the Import tab at the top, and upload the provided .sql schema file located in the extracted project folder. Click Go to build the tables.
<br>
<br>
Launch the Application:
Open a new tab in your web browser and navigate to http://localhost/your-project-folder-name/ (replace your-project-folder-name with the actual name of the folder you placed in htdocs). The Clinic Appointment and Queue Management System should now be live!
<br>
