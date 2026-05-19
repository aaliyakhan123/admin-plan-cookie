<img width="1886" height="997" alt="Screenshot 2026-05-15 193718" src="https://github.com/user-attachments/assets/917c33c4-fa84-4f0a-9298-1c7daa54c3a2" />
<img width="1901" height="986" alt="Screenshot 2026-05-15 194919" src="https://github.com/user-attachments/assets/b1eb1545-2d3a-4beb-9db8-6ba84ca2c3ef" />
<img width="1907" height="998" alt="Screenshot 2026-05-15 193911" src="https://github.com/user-attachments/assets/b2f8f1f1-9a36-4287-a338-279b02fd5268" />
<img width="1901" height="986" alt="Screenshot 6" src="https://github.com/user-attachments/assets/e3c9d07f-53e5-454f-90b7-b3df5956dfe5" />
<img width="1907" height="1010" alt="Screenshot 3" src="https://github.com/user-attachments/assets/3804cd88-e9ef-4289-8f1a-b7c17db6f130" />
# Admin Panel Cookie Authentication Project
vedio explaining - https://docs.google.com/videos/d/1syz2XYJZK9U6pzPClUu-yaq_UKNpZmuCEdkR1cAkthU/edit?usp=sharing

## Overview

This project is a Node.js and Express-based Admin Panel application that uses cookie-based authentication.
<img width="1900" height="946" alt="Screenshot 5" src="https://github.com/user-attachments/assets/b2432a11-e182-47f8-ad3c-72fb622810ea" />
<img width="1912" height="1010" alt="Screenshot 2" src="https://github.com/user-attachments/assets/e3e42d30-3f83-4c40-8eb4-fd9db5d3755e" />
<img width="1905" height="970" alt="Screenshot 1" src="https://github.com/user-attachments/assets/0ca2fd0f-f406-4fb2-aaa3-0fba027226db" />
<img width="1905" height="970" alt="Screenshot 1" src="https://github.com/user-attachments/assets/bdafe585-498e-474d-ae77-97c1ca61477a" />
The application allows admins to register, log in, manage dashboard pages, and perform CRUD operations using a simple and clean interface built with EJS templates.

---

## Technologies Used

* Node.js
* Express.js
* MongoDB
* Mongoose
* EJS Template Engine
* Cookie Parser
* Bcrypt
* Multer

---

## Project Structure

```bash
admin-paln-cookie/
│
├── config/
│   └── db.js
│
├── controllers/
│   └── adminControllers.js
│
├── middleware/
│   └── authMiddleware
│
├── models/
│   └── adminSchema.js
│
├── public/
│   └── assets/
│
├── router/
│   └── adminRouter.js
│
├── views/
│   ├── addAdmin.ejs
│   ├── dashboard.ejs
│   ├── editAdmin.ejs
│   ├── login.ejs
│   ├── register.ejs
│   └── viewAdmin.ejs
│
├── app.js
├── package.json
└── README.md
```

---

## Features

* Admin Registration
* Admin Login System
* Cookie-Based Authentication
* Dashboard Management
* Add Admin
* Edit Admin
* View Admin List
* Delete Admin
* Secure Password Hashing using Bcrypt
* EJS Dynamic Templates

---

## Installation

### 1. Clone the Repository

```bash
git clone <your-repository-link>
```

### 2. Open Project Folder

```bash
cd admin-paln-cookie
```

### 3. Install Dependencies

```bash
npm install
```

---

## Run the Project

```bash
npm start
```

Server will start on:

```bash
http://localhost:9000
```

---

## Package Dependencies

```json
{
  "bcrypt": "^6.0.0",
  "cookie-parser": "^1.4.7",
  "ejs": "^5.0.1",
  "express": "^5.2.1",
  "mongoose": "^9.6.1",
  "multer": "^2.1.1"
}
```

---

## Database Configuration

Update your MongoDB connection inside:

```bash
config/db.js
```

Example:

```js
mongoose.connect('mongodb://127.0.0.1:27017/admin-panel');
```

---

## Authentication

This project uses:

* Cookies for session handling
* Bcrypt for password encryption
* Middleware for route protection

---

## Views Included

* Login Page
* Register Page
* Dashboard
* Add Admin Page
* Edit Admin Page
* View Admin Page

---

## Author

Created for learning and practice purposes using Node.js, Express, MongoDB, and EJS.

---

## License

This project is open-source and available under the ISC License.

