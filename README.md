# Employee Management System (Full Stack)

This is a full stack **Employee Management System** built with **React + Vite** for the frontend and **Spring Boot (Spring Web, Spring Data JPA, MySQL, Lombok)** for the backend. It allows users to manage employee records with full CRUD functionality.

---

## 📁 Project Structure

full-stack/
├── ems-frontend/ # React + Vite frontend
└── ems-backend/ # Spring Boot backend

## 🚀 Tech Stack

### 🖥 Frontend
- React
- Vite
- Axios
- Tailwind CSS (optional)
- React Router DOM

### ⚙ Backend
- Java 17+
- Spring Boot
  - Spring Web
  - Spring Data JPA
  - MySQL Driver
  - Lombok

### 🗄️ Database
- MySQL

---

## 🧑‍💻 Features

- Add, edit, and delete employee records
- View all employees in a tabular format
- Connect frontend and backend via RESTful APIs
- Proper error handling and validation
- Persistent storage with MySQL

## 🔧 Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/ems-fullstack.git
cd ems-fullstack

2️⃣ Backend Setup (ems-backend)
🔹 Prerequisites:

- Java 17+

- Maven

- MySQL

🔹 Configuration:
Update application.properties inside src/main/resources/:

properties
Copy
Edit
spring.datasource.url=jdbc:mysql://localhost:3306/ems_db
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

🔹 Run Backend:
```bash

cd ems-backend
./mvnw spring-boot:run
The backend will start on: http://localhost:8080

3️⃣ Frontend Setup (ems-frontend)
🔹 Prerequisites:
Node.js (v16+ recommended)

npm

🔹 Install Dependencies:

cd ems-frontend
npm install

🔹 Configure API URL (if needed)
Update baseURL in your Axios instance to match your backend URL (http://localhost:8080).

🔹 Run Frontend:

npm run dev
The frontend will be live on: http://localhost:5173


🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

📄 License
This project is licensed under the MIT License.

📬 Contact
Chirag Malik
GitHub
Email: chiragmalik1700@gmail.com
