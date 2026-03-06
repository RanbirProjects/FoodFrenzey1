# 🍔 FoodFrenzey1 – Restaurant Management System

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&duration=3000&pause=1000&color=F75C7E&center=true&vCenter=true&width=700&lines=Restaurant+Management+System;Spring+Boot+Full+Stack+Project;Customer+Inventory+Order+Management;Java+Spring+Boot+MySQL" />
</p>

<p align="center">
<img src="https://komarev.com/ghpvc/?username=RanbirProjects&label=Repository%20Views&color=blue&style=for-the-badge" />
</p>

<p align="center">
<img src="https://skillicons.dev/icons?i=java,spring,mysql,html,css,js,git,github,vscode" />
</p>

---

# 🚀 Project Overview

**FoodFrenzey1** is a complete **Restaurant Management System** designed to manage customers, inventory, and orders efficiently.

The system provides secure authentication, role-based access control, and seamless database integration using **MySQL**. It is built using **Spring Boot and Thymeleaf**, providing a dynamic and responsive web interface for administrators and staff members.

This application helps restaurant teams manage operations smoothly with organized data management and an intuitive user interface.

---

# 🧠 Project Architecture

```
            ┌───────────────┐
            │   User/Admin  │
            └───────┬───────┘
                    │
                    ▼
           ┌─────────────────┐
           │  Thymeleaf UI   │
           │ (HTML/CSS/JS)   │
           └───────┬─────────┘
                   │
                   ▼
          ┌───────────────────┐
          │ Spring Boot App   │
          │  (Controllers)    │
          └───────┬───────────┘
                  │
        ┌─────────┴─────────┐
        ▼                   ▼
┌───────────────┐   ┌───────────────┐
│ Service Layer │   │ Repository    │
│ Business Logic│   │ Spring Data   │
└───────────────┘   └───────┬───────┘
                            ▼
                     ┌─────────────┐
                     │   MySQL DB  │
                     └─────────────┘
```

---

# ✨ Features

- 👥 Customer Management (Add, Update, Delete customers)
- 📦 Inventory Management with stock tracking
- 🧾 Order Management system
- 🔐 Secure authentication system
- 👤 Role-based access control
- ⚡ Dynamic UI using Thymeleaf templates
- 🗄️ MySQL database integration
- 📊 Organized admin dashboard

---

# 📸 Application Screenshots

## 🏠 Dashboard

<img src="https://github.com/user-attachments/assets/1382d32f-3cbb-40c3-b6b5-9fc55cd5176f" width="900"/>

---

## 🍽️ Website Interface

<img src="https://github.com/user-attachments/assets/3e34f54c-c986-42ac-96a4-ed7ad18035a6" width="900"/>

<img src="https://github.com/user-attachments/assets/a4046d4e-8c3d-4629-8913-5543d709e80e" width="900"/>

<img src="https://github.com/user-attachments/assets/09c92348-ec06-4607-9ae4-88b28cc1e0ec" width="900"/>

<img src="https://github.com/user-attachments/assets/0e73aece-a28c-413d-9363-245358a0e439" width="900"/>

<img src="https://github.com/user-attachments/assets/ac26bd92-0fcd-473d-a175-9bc45fdb12ba" width="900"/>

---

# 🏗️ Technology Stack

### Backend
- Java 8
- Spring Boot
- Spring MVC
- Spring Data JPA (Hibernate)

### Frontend
- Thymeleaf
- HTML
- CSS
- JavaScript

### Database
- MySQL

### Development Tools
- Maven
- Eclipse / Spring Tool Suite (STS)

---

# 📂 Project Structure

```
src/
├── main/
│   ├── java/
│   │   └── com.example.foodfrenzy/
│   │       ├── controller/
│   │       ├── model/
│   │       ├── repository/
│   │       └── service/
│   │
│   ├── resources/
│   │   ├── templates/
│   │   ├── static/
│   │   └── application.properties
│   │
│   └── webapp/
│       └── WEB-INF/
│           └── views/
│
└── test/
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/FoodFrenzey1.git
cd FoodFrenzey1
```

---

## 2️⃣ Configure MySQL Database

Create a database in MySQL and update **application.properties**

```
spring.datasource.url=jdbc:mysql://localhost:3306/foodfrenzy
spring.datasource.username=root
spring.datasource.password=root
spring.jpa.hibernate.ddl-auto=update
```

---

## 3️⃣ Run the Project

```bash
mvn spring-boot:run
```

---

## 4️⃣ Access the Application

Open your browser and visit:

```
http://localhost:8080
```

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository  
2. Create a feature branch  
3. Commit your changes  
4. Push to GitHub  
5. Open a Pull Request  

---

# 👨‍💻 Author

**Ranbir Singh**

💼 Full Stack Developer  
📍 Bangalore, India  

📧 ranbirsingh9156@gmail.com  

🔗 GitHub  
https://github.com/RanbirProjects  

🔗 LinkedIn  
https://linkedin.com/in/ranbirsingh14  

---

# 📜 License

This project is licensed under the **MIT License**.
