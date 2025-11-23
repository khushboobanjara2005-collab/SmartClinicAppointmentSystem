# Smart Clinic Appointment Booking System

This project is a web-based appointment booking system developed as part of the Advanced Java Mini Project.  
It allows patients to register and book appointments with doctors, while storing all data in a MySQL database.
```
The system demonstrates a complete workflow including:
• database creation
• data storage and retrieval
• servlet-based processing
• JSP-based UI
• data visualization and analysis
```

---

## Features
```
• Patient registration  
• Doctor listing  
• Appointment booking  
• View appointments by doctor  
• View appointments by patient  
• Automatic database creation using SetupServlet  
• Data stored in MySQL smartclinic database
```
---

## Technologies Used
```
• Java (JDK 17)  
• JSP  
• Servlets  
• JDBC  
• Apache Tomcat 10  
• MySQL Server 8  
• NetBeans IDE  
• Excel (for data visualization)
```
---

## Project Structure
```
SmartClinicAppointmentSystem/
│
├─ src/
│  ├─ main/
│  │  ├─ java/
│  │  │  ├─ dao/
│  │  │  ├─ model/
│  │  │  ├─ servlet/
│  │  │  └─ util/ (DBUtil.java, etc.)
│  │  └─ webapp/
│  │     ├─ index.jsp
│  │     ├─ patientForm.jsp
│  │     ├─ appointmentForm.jsp
│  │     ├─ success.jsp
│  │     ├─ doctorAppointments.jsp
│  │     └─ patientAppointments.jsp
│
├─ pom.xml
├─ nb-configuration.xml
├─ SmartClinic.zip
└─ README.md
```
---

## Database

Database Name: smartclinic

Tables:
```
• patient  
• doctor  
• appointment
```
Database is automatically created and populated through SetupServlet.java.

---

## How to Run
```
1. Open the project in NetBeans
2. Start Apache Tomcat 10
3. Run the project
4. Access:
```
http://localhost:8082/SmartClinic/

---

## Data Visualization

Appointment data was exported and analyzed to generate:
```
• appointments per doctor chart  
• daily appointment trend chart  
• appointment status distribution chart
```
These visualizations were included in the project report.

---

## Author

Khushboo Banjara
BCA Student

---

## GitHub Repository Link
https://github.com/khushboobanjara2005-collab/SmartClinicAppointmentSystem
