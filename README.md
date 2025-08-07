# 🍽️ Grandma's Recipes – Full Stack Recipe Management Platform

A full-stack recipe management system developed as part of the "Web Development Environments" course.  
The platform allows users to register, search and view recipes, create and save their own (including family recipes), and interact with the content through a polished and responsive UI.

---

## 📚 Overview

This project is composed of:

- **Frontend (Vue.js 3 + BootstrapVue)** – A Single Page Application for recipe browsing, creation, and personalization
- **Backend (Node.js + Express + MySQL)** – A RESTful API server with full user/session management and dynamic integration with the [Spoonacular API](https://spoonacular.com/food-api)

The system supports real-time interactions, user-specific content (favorites, views, personal recipes), and a clear separation between local and external recipes using a custom ID strategy.

---

## 🚀 Key Features

- 👥 **User Management** – Register, login/logout, session handling via HTTP-only cookies
- 🍽️ **Recipe Search** – Filter by cuisine, diet, intolerance; sort by popularity or time
- 💾 **Personal & Family Recipes** – Create and manage private or family-shared recipes
- ❤️ **Favorites & History** – Save and track liked/viewed recipes
- 🔍 **Detailed Recipe View** – Ingredients, instructions, and related suggestions
- 🎨 **Polished UI** – BootstrapVue styling, responsive layout, and visual feedback
- 🌐 **External API Integration** – Live recipe search powered by Spoonacular

---

## ⚙️ Technologies

### 🌐 Frontend
- Vue.js 3
- Vue Router & Store
- BootstrapVue
- Axios (API requests)
- SCSS

### 💻 Backend
- Node.js + Express
- MySQL
- Spoonacular API
- dotenv (env config)
- Swagger (OpenAPI Spec)
- RESTful Design
- Postman (API Testing)

### 🧪 Tools
- Swagger UI (via YAML)
- Postman collections
- SQL scripts for DB initialization

---

## 🗂️ Project Structure
```
.
Recipes-Website/
├── client/ # Frontend (Vue.js)
│ ├── src/
│ │ ├── components/ # UI components: search, forms, previews
│ │ ├── pages/ # Main screens (Home, Login, Recipes, etc.)
│ │ ├── router/ # Vue Router setup
│ │ ├── store.js # Global state management
│ │ └── main.js / App.vue
│ ├── public/
│ └── package.json

├── server/ # Backend (Express.js)
│ ├── routes/ # API routes: auth, users, recipes
│ │ ├── utils/ # Utility files (get/post logic, DB)
│ ├── sql_scripts/ # SQL table creation & data inserts
│ ├── dist/ # Swagger definition (openapi.yaml)
│ ├── .env # Credentials and keys
│ ├── main.js # App entry point
│ └── package.json

├── README.md # This file
└── .gitignore
```

