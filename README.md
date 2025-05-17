# 📝 Post-Comment Service

A backend service that allows users to create posts and comments, designed with scalability, clean architecture, and database integrity in mind. Built using **Node.js**, **Express.js**, and **MySQL**, this project demonstrates a modular backend system ideal for blogging or discussion-based platforms.

---

## 🔧 Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MySQL

---

## 💡 Why MySQL?

- **Structured Data**: Perfect for relational data like posts and comments.
- **Foreign Keys**: Ensures referential integrity between users, posts, and comments.
- **Performance**: Efficient for read-heavy applications.
- **ACID Compliance**: Ensures data consistency and reliability.

---

## 📁 Folder Structure

├── .env
├── .gitignore
├── app.js

├── config/
│   └── db.js

├── controllers/
│   ├── authController.js
│   ├── commentController.js
│   └── postController.js

├── middleware/
│   └── auth.js

├── models/
│   ├── Comment.js
│   ├── Post.js
│   └── User.js

└── routes/
    ├── auth.js
    ├── comments.js
    └── posts.js


