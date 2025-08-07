# 🛒 Product List CRUD Application

A full-stack web application to manage a product list with full CRUD (Create, Read, Update, Delete) functionality. This app allows users to add, edit, delete products, and manage a cart count. Built using Angular for the frontend and Node.js + Express with PostgreSQL for the backend.

## ✨ Features

- 🔄 Create, Read, Update, Delete products
- 🛍 Add to cart with count management
- 🎨 Responsive UI with Angular Material
- 📐 Layout powered by Flex Layout
- 📦 Backend with Express.js and PostgreSQL

---

## 🧑‍💻 Tech Stack

### Frontend
- [Angular](https://angular.io/)
- [Angular Material](https://material.angular.io/)
- [@angular/flex-layout](https://github.com/angular/flex-layout)

### Backend
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [Sequelize](https://sequelize.org/) *(or specify ORM if used)*

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [PostgreSQL](https://www.postgresql.org/)

### 📂 Project Structure

project-root/
│
├── express
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── server.js
│
├── frontend/ # Angular frontend
│ ├── src/
│ └── angular.json


### 🔧 Setup Instructions

#### 1. Clone the Repository

```bash
git clone https://github.com/your-username/product-list-crud.git
cd product-list-crud

cd express
npm install
# Configure your PostgreSQL credentials in a `.env` file
npm run start

cd ../frontend
npm install
npm run start
