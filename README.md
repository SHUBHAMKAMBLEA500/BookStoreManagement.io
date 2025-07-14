# BookStoreManagement.io
# 📚 Bookstore Management System

A full-stack web application built using **Spring Boot**, **MySQL**, **Thymeleaf**, and **Spring Data JPA** to manage a bookstore’s inventory, customers, and transactions. This system allows users to register, log in, and perform CRUD operations on books.

---

## 🔧 Technologies Used

- **Backend:**
  - Java 17
  - Spring Boot
  - Spring Data JPA
  - Spring Security (Optional)
  - Hibernate
  - Maven

- **Frontend:**
  - HTML5
  - CSS3
  - Bootstrap 5
  - Thymeleaf

- **Database:**
  - MySQL

---

## 💡 Features

### 🔐 Authentication
- User Registration
- User Login
- Password validation & error messages

### 📘 Book Management
- Add New Books
- View All Books
- Edit Book Details
- Delete Books

### 🔍 Search & Sort
- Search books by name/author
- Sort books by price/title

### 📄 Responsive Pages
- Home page
- Login/Register
- Dashboard
- Book list
- Book form (add/edit)

---

## 🗃️ Project Structure

bookstore-management/
├── src/
│ ├── main/
│ │ ├── java/
│ │ │ └── com.example.bookstore/
│ │ │ ├── controller/
│ │ │ ├── entity/
│ │ │ ├── repository/
│ │ │ ├── service/
│ │ │ └── BookstoreApplication.java
│ │ ├── resources/
│ │ │ ├── templates/
│ │ │ │ ├── home.html
│ │ │ │ ├── register.html
│ │ │ │ ├── login.html
│ │ │ │ ├── book_list.html
│ │ │ │ └── book_form.html
│ │ │ ├── static/
│ │ │ ├── application.properties
├── pom.xml

---

## ⚙️ Setup Instructions

### Prerequisites
- Java 17+
- Maven
- MySQL Server

### Database Setup

sql
CREATE DATABASE bookstoredb;

# Step 1: Clone the project
git clone https://github.com/SHUBHAMKAMBLEA500/BookStoreManagement.io
cd bookstore-management

# Step 2: Build the project
mvn clean install

# Step 3: Run the Spring Boot app
mvn spring-boot:run
Visit http://localhost:1001 in your browser.

🧑‍💻 Developer Info
Author: Shubham Kamble

Email: Shubhamkamblea500@gmail.com

LinkedIn: linkedin.com/in/Shubhamkamble

📸 Screenshots (Optional)
Add screenshots/ and include examples of:

Home page
<img width="1898" height="940" alt="image" src="https://github.com/user-attachments/assets/9c64ecee-1f15-4cd9-9a23-080b2247c442" />

Register/Login
<img width="1912" height="947" alt="image" src="https://github.com/user-attachments/assets/1332072d-35dc-4c05-bc26-e37ed6f1b258" />


Book List
<img width="1900" height="922" alt="image" src="https://github.com/user-attachments/assets/ca141027-0e57-4506-b391-26f05c1a30e4" />


Add/Edit book
<img width="1912" height="945" alt="image" src="https://github.com/user-attachments/assets/dfaa30c6-f3d6-413e-94e2-db9612caa228" />


<img width="1918" height="928" alt="image" src="https://github.com/user-attachments/assets/f18375f3-089b-4174-a31a-3ac4eb1f6ce5" />
