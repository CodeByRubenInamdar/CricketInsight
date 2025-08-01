# 🏏 CricketInsight  

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2.8-green?logo=springboot)  
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue?logo=mysql)  
![License](https://img.shields.io/badge/License-MIT-yellow)  
![Build](https://img.shields.io/badge/Build-Passing-brightgreen)

CricketInsight is a **comprehensive cricket management system** built with **Spring Boot, MySQL, and modern web technologies**. It allows users to manage players, matches, teams, and statistics while providing an intuitive interface for admins and users.

---

## 🚀 Features  
✅ **Player Management** – Add, update, and view player details  
✅ **Team Management** – Create and manage cricket teams  
✅ **Match Scheduling** – Organize matches with dates, venues, and teams  
✅ **Scoreboard & Stats** – Track live match scores and player statistics  
✅ **User Roles** – Admin and User functionalities with role-based access  
✅ **Search & Filters** – Find players, teams, and matches quickly  

---

## 🛠 Tech Stack  

| Technology       | Purpose                     |
|------------------|-----------------------------|
| **Java (Spring Boot)** | Backend REST API           |
| **MySQL**        | Database for persistent storage |
| **Spring Data JPA** | ORM for database operations |
| **Thymeleaf / Bootstrap** | Frontend UI (if web-based) |
| **Maven**        | Build & Dependency Management |

---

## 📂 Project Structure  

```
CricketInsight/
 ├── src/main/java/com/ruben/cricketinsight/
 │   ├── controller/     # REST Controllers
 │   ├── entity/         # JPA Entities
 │   ├── repository/     # Spring Data Repositories
 │   ├── service/        # Business Logic
 │   └── CricketInsightApplication.java
 ├── src/main/resources/
 │   ├── application.properties
 │   └── templates/ (if Thymeleaf used)
 └── pom.xml
```

---

## ⚙️ Setup & Installation  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/CodeByRubenInamdar/CricketInsight.git
cd CricketInsight
```

### 2️⃣ Configure MySQL Database  
Create a MySQL database named `cricketinsight`  
Update `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/cricketinsight
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD
spring.jpa.hibernate.ddl-auto=update
```

### 3️⃣ Build & Run  
```bash
mvn clean install
mvn spring-boot:run
```

---

## 📌 API Endpoints  

| Endpoint                  | Method | Description            |
|---------------------------|--------|------------------------|
| `/players`                | GET    | Get all players        |
| `/players/{id}`           | GET    | Get player by ID       |
| `/players`                | POST   | Add new player         |
| `/teams`                  | GET    | Get all teams          |
| `/matches`                | POST   | Schedule a new match   |

---

## 📸 Screenshots (Optional)  
_Add UI screenshots if you have a frontend._

---

## 🤝 Contributing  
1. Fork the repository  
2. Create a new branch (`feature-xyz`)  
3. Commit your changes  
4. Push to your branch and create a PR  

---

## 📬 Contact  

👤 **Ruben Inamdar**  
📧 Email: rubeninamdar86@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/ruben-inamdar)  
💻 [GitHub](https://github.com/CodeByRubenInamdar)
