# Medical Center Manager 🏥

A Java-based desktop/web application to manage medical center operations: patient records, appointments, doctor assignments, billing, and more—with optional MySQL support for persistent data.

---

## 🚀 Key Features

### 🙋 Patient Management
- Register new patients with personal details (name, age, gender, contact).
- Search and view patient records.
- Edit or remove patient profiles.

### 📅 Appointment Scheduling
- Schedule appointments by assigning doctors and time slots.
- View daily or weekly appointment calendars.
- Update or cancel appointments as needed.

### 👨‍⚕️ Doctor & Staff Handling
- Add doctors and staff with relevant information (speciality, availability).
- Link assigned physicians to patients during scheduling.

### 🧾 Billing & Payments
- Create and manage bills for consultations, tests, and treatments.
- Automatically calculate amounts and track pending payments.

### 📊 Reporting (Optional)
- Generate simple reports:
  - Patients registered today
  - Appointments scheduled per day or doctor

---

## 🧰 Tech Stack

- **Core Language**: Java  
- **Optional UI**: Console menu or Java Swing-based GUI  
- **Persistence (Optional)**:  
  - MySQL with JDBC  
  - Files or in-memory data structures if DB isn't used  
- **OOP Design**: Modular classes like `Patient`, `Appointment`, `Doctor`, `Billing`, and `DatabaseHelper`.

---

📂 Project Structure
pgsql
Copy
Edit
src/
 ├─ model/            – Entity classes: Patient, Doctor, Appointment, Billing
 ├─ service/          – Business logic handlers
 ├─ dao/              – Database access layer (JDBC helpers)
 ├─ ui/               – Command-line or Swing UI drivers
Main.java             – Application entry point (CLI or GUI)
schema.sql            – Database schema ( MySQL used)

---


🧠 What I Learned
Implemented CRUD capabilities for patients, appointments, and billing.
Designed modular OOP structure—separate model, service, and DAO layers.
Integrated JDBC with MySQL for data storage and retrieval.
Built interactive menus or GUI for real-world user flow.
Learned basics of error handling, input validation, and project structure best practices.


---


## 📧 Contact

For any questions or collaboration:
- **GitHub**: @PrakharS524  
- **Email**: prakhars2202@gmail.com  

---

Thank you for checking out the project!  
