
📘 TheBook — Social Media Networking Platform

A full-stack social networking prototype built with Go and MySQL

🚀 Overview

TheBook is a lightweight social media networking platform that supports user creation, post publishing, and personalized feed retrieval.
The system includes a Go-powered backend, a simple HTML frontend, and a MySQL database for persistent storage.

This project demonstrates core concepts of social media architecture — authentication, post handling, feed generation, and efficient API design.

🌟 Features
👤 User Management

Create new users

Authenticate users

Store profile data in MySQL

📝 Posts & Feed

Publish text-based posts

Fetch personalized feeds based on recent activity

Efficient database queries for fast response times

🔐 Security & Middleware

CORS middleware implemented to allow secure and controlled frontend–backend communication

⚡ Performance

Prototype tested with 50+ users

100+ posts handled during load tests

Average API response time: < 200ms

🛠️ Tech Stack
Component	Technology
Backend	Go (Golang), net/http
Database	MySQL
Frontend	HTML, CSS
Others	CORS Middleware, RESTful APIs
📂 Project Structure
/backend
   ├── main.go
   ├── go.mod
   ├── go.sum
/frontend
   ├── login.html
   ├── create.html
   ├── about.html
   ├── jbook.html

🔧 Setup & Installation
1️⃣ Clone the repository
git clone https://github.com/your-username/TheBook.git
cd TheBook/backend

2️⃣ Install dependencies
go mod tidy

3️⃣ Setup MySQL database

Create a database (e.g., thebook_db) and update your DB credentials in main.go.

4️⃣ Run the backend
go run main.go

5️⃣ Open the frontend

Simply open any .html file from the frontend/ folder in your browser
(e.g., login.html or jbook.html).


👥 Contributors

This project was built collaboratively as part of a group assignment.

Bhoomija Garg
Kanishka Bhardwaj



📌 Future Enhancements

JWT-based authentication

Follow/unfollow user system

Like and comment features

Real-time feed updates

Dockerized deployment
