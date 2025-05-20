# 🛡️ JWT Auth API with Express, MongoDB, and Joi

A simple authentication and product API built using **Node.js**, **Express**, **MongoDB**, **JWT**, and **Joi**. 
This project demonstrates secure signup/login flows, route protection with JWT, and input validation.

---

## 📦 Features

- ✅ User Signup with password hashing (`bcrypt`)
- ✅ User Login with JWT token generation
- ✅ Route protection using JWT
- ✅ Input validation using Joi
- ✅ Product route accessible only to authenticated users
- ✅ Clean modular code structure

---

🛣️ API Endpoints
👤 Auth Routes
Method	   Endpoint     	  Description
POST	     /auth/signup	    Register a new user
POST	     /auth/login	    Login and receive JWT

🔐 Protected Routes
Method	 Endpoint	    Description
GET	    /products	    Get products (requires JWT)
GET	    /ping	        Health check route


