# PRODIGY_BD_03 -> JWT-Based Authentication & Authorization

📦 This repository contains "Task 3" for my Backend Development Internship at "Prodigy InfoTech" 🚀.

🎯 The goal of this project is to implement authentication and authorization using JSON Web Tokens (JWT). It extends the system to handle secure user registration and login, store securely hashed passwords using the BCrypt library, and return a signed JWT token to the client upon successful authentication. Additionally, it protects specific routes (such as `/users`) and implements strict role-based access control (e.g., admin, user, owner) to restrict unauthorized endpoint access.

🌟 Current Progress --> Day 1 🚀 -> Configured the core security setup by integrating Spring Security and JJWT dependencies, implementing BCrypt password hashing, and building the authentication endpoints to handle user registration and login token generation.

Day 2 💾 -> Set up the core application framework by creating the primary `DemoApplication.java` bootstrap class, the `User.java` JPA entity to map table attributes, and the `UserRepository.java` data access interface.
