# 📚 School Admission Portal

A web-based application built using **Java Spring Boot** that simplifies and automates the **student admission process** for schools. This system helps administrators manage applications, track admission status, and maintain student records efficiently.

---

## 🚀 Features

* 📝 Online admission form submission
* 👨‍👩‍👧 Student & Parent registration
* ✅ Application approval/rejection by admin
* 📊 Dashboard for admission tracking
* 🔐 Role-based login (Admin, Student)
* 💾 Database integration for storing student details
* 📧 Email/notification support (optional)

---

## 🛠️ Tech Stack

* **Backend:** Java, Spring Boot
* **Frontend:** Thymeleaf, HTML, CSS, Bootstrap
* **Database:** MySQL / PostgreSQL
* **Build Tool:** Maven / Gradle
* **Server:** Tomcat (embedded in Spring Boot)

---

## ⚙️ Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/DivyaUbarhande/School-Admission-Portal.git
   cd School-Admission-Portal
   ```

2. **Configure Database**

   * Create a new schema in MySQL/PostgreSQL (e.g., `school_portal`).
   * Update `application.properties`:

     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/school_portal
     spring.datasource.username=your_username
     spring.datasource.password=your_password
     spring.jpa.hibernate.ddl-auto=update
     ```

3. **Build & Run the project**

   ```bash
   mvn spring-boot:run
   ```

   The app will run on **[http://localhost:8080](http://localhost:8080)**

---

## 📂 Project Structure

```bash
School-Admission-Portal/
│── src/main/java/com/school/admission/
│   ├── controller/         # Handles HTTP requests (StudentController, AdminController)
│   ├── service/            # Business logic (StudentService, AdmissionService)
│   ├── repository/         # DAO layer (StudentRepository, AdminRepository)
│   ├── entity/             # Database entities (Student, Admin, Application)
│   └── SchoolAdmissionPortalApplication.java   # Main Spring Boot Application
│
│── src/main/resources/
│   ├── static/             # CSS, JS, Images
│   ├── templates/          # Thymeleaf HTML pages (login.html, admissionForm.html, dashboard.html)
│   ├── application.properties
│
│── pom.xml                 # Maven dependencies
│── README.md               # Project documentation
```

---

## 📸 Screenshots (Add later)

* Login Page
* Admission Form
* Admin Dashboard

---

## 🔮 Future Enhancements

* Payment integration for admission fees
* Document upload for students
* SMS/Email notifications
* Multi-school support

---

## 👩‍💻 Author

* **Divya Ubarhande**
  [GitHub](https://github.com/DivyaUbarhande) | [LinkedIn](#)


