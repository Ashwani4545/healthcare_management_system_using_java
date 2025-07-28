🏥 HealthCare Management System

📘 Overview
The HealthCare Management System (HCMS) is a desktop-based Java application designed to manage core functions in a hospital environment. It helps in streamlining operations like patient registration, diagnosis management, doctor assignment, billing, and administrative tasks. This project is suitable for clinics, hospitals, and medical institutions looking to digitize their workflows.

🧾 Key Features
👤 Patient Management
Register new patients

Update patient details

Discharge summaries

🩺 Doctor Panel
Assign doctors to patients

Record symptoms and diagnostics

Generate prescriptions

🛠 Admin Panel
Manage users (add/update/remove)

Track staff activity

View diagnostic & billing reports

💰 Billing and Reports
Calculate charges based on services

Generate diagnostic and payment reports

Maintain transaction records

🗂 Project Structure
bash
Copy
Edit
📁 Project Root
├── 📁 code/                # Contains Java source files (.java) and compiled files (.class)
├── 📁 DOCUMENTATION/       # Includes abstracts, PPTs, and UML diagrams
│   ├── ABSTRACT.docx
│   ├── HCMS.doc            # Detailed system documentation
│   ├── TIME_PPT.pps        # Project presentation
│   └── Screens/            # 20+ GUI screenshots (.bmp)
├── 📁 uml/                 # UML diagrams: use case, class, sequence
├── 📄 .jpg/.bmp            # Background images and UI graphics
⚙️ Technologies Used
Component	Technology
Frontend	Java Swing (GUI)
Backend	Java SE (Standard)
Database	(Likely MS Access or MySQL, as inferred from docs)
Reporting	Java + manual document export
Platform	Desktop (Windows preferred)

📸 UI Screenshots
Found in DOCUMENTATION/Screens/, the screenshots show:

Login form

Patient dashboard

Add/Edit patient form

Doctor panel

Report summary

Billing window

🧠 UML Diagrams
Located in DOCUMENTATION/uml/:

Use Case Diagram

Class Diagram

Sequence Diagrams

Collaboration Diagram

These diagrams help in understanding the system architecture and flow of control.

▶️ How to Run the Project
Open the project in a Java IDE (e.g., Eclipse, NetBeans, or IntelliJ).

Make sure all .java files from the code/ directory are included in your source directory.

Compile the project (build).

Identify and run the main class (e.g., Main.java or HospitalMain.java).

The GUI interface will launch.

⚠️ Note:

Ensure the JDBC configuration (if used) matches the database path.

Images (.jpg, .bmp) must be kept in the expected directories as referenced by the GUI.

📄 Abstract (Summary)
The HealthCare Management System offers a robust and efficient platform for automating healthcare operations. It digitizes patient records, enhances accuracy in diagnostics, simplifies administrative workflow, and reduces human error. It is designed to handle small to mid-sized healthcare institutions.

You can find the full abstract in:
📄 DOCUMENTATION/ABSTRACT.docx

🧑‍💻 Author & Acknowledgments
📁 Project Source: Enggroom.com (Engineering mini-project repository)

👨‍💻 Customized & Documented by: Your Name Here

📅 Year: 2024

📝 License
This project is for educational and learning purposes only.
Credit to original contributors is required if reused or modified.