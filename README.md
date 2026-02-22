# 🎓 Smart Student Management System

A full-stack Student Management System built using **Java Spring Boot**, **MySQL**, and a simple **HTML/CSS/JavaScript frontend**.  
This application allows users to perform complete CRUD operations on student records.

---

## 🚀 Features

✅ Add new students  
✅ View all students  
✅ Update student details  
✅ Delete students  
✅ RESTful API architecture  
✅ Database integration with MySQL  
✅ Simple and responsive frontend UI  

---

## 🛠️ Technologies Used

**Backend**
- Java 17
- Spring Boot
- Spring Data JPA
- Hibernate

**Database**
- MySQL

**Frontend**
- HTML
- CSS
- JavaScript (Fetch API)

**Build Tool**
- Maven

---

## 📂 Project Structure


studentmanagement
│── src/main/java/com/souj/studentmanagement
│ ├── controller
│ ├── service
│ ├── repository
│ ├── entity
│
│── src/main/resources
│ ├── static (Frontend)
│ ├── application.properties


---

## ⚙️ Setup & Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/studentmanagement.git
cd studentmanagement
2️⃣ Configure Database

Create a MySQL database:

CREATE DATABASE student_db;

Update application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/student_db
spring.datasource.username=your_username
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
3️⃣ Run Application

Using Maven:

mvn spring-boot:run

Application runs at:

http://localhost:8080
🌐 API Endpoints
Method	Endpoint	Description
POST	/students	Add student
GET	/students	Get all students
GET	/students/{id}	Get student by ID
PUT	/students/{id}	Update student
DELETE	/students/{id}	Delete student
💡 Example JSON
{
  "name": "Soujanya",
  "email": "soujanya@gmail.com",
  "department": "CSE"
}
🎯 Learning Outcomes

This project demonstrates:

✔ Spring Boot fundamentals
✔ REST API development
✔ Database integration with JPA
✔ Full-stack communication
✔ Frontend-backend interaction
