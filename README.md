# 🌮 Taco Recipe Selector App

This is a simple Node.js web application that allows users to view detailed recipes for various tacos — Chicken, Beef, and Fish. Built with **Express.js**, **EJS**, and **vanilla JavaScript**, it displays recipes dynamically based on user input.

---

## 🧠 How It Works

- The application holds a predefined list of taco recipes (in JSON format).
- Users can select a taco type.
- Based on the selection, the corresponding recipe is displayed on the page using server-side rendering via EJS.

---

## 🚀 Features

- Dynamic taco recipe rendering
- Ingredient breakdown by type (protein, salsa, toppings)
- Pre-defined JSON structure for scalability
- Clean separation of concerns using routes and views

---

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: EJS templating, HTML/CSS
- **Middleware**: body-parser

---

## 📁 Project Structure

taco-recipe-app/
│
├── public/ # Static assets (e.g., CSS or images)
├── views/
│ └── index.ejs # Main template to render recipe
├── app.js # Main Express application
├── package.json
└── README.md

---

## ▶️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/taco-recipe-app.git
cd taco-recipe-app"

2. Install dependencies
npm install

3. Run the app
node app.js
Visit http://localhost:3000 in your browse
