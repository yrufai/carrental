
# 🚗 Car Rental Service Web Application

A modern, responsive car rental web application built with **React**.
This platform allows users to browse available vehicles, view detailed specifications, dynamically update pricing, and complete reservations through an interactive modal interface.

---

## 🌐 Project Overview

The Car Rental Service application simulates a real-world rental platform with a clean and intuitive user interface.

Users can:

* Browse a fleet of vehicles
* View rental price per day
* See detailed vehicle specifications
* Select a vehicle dynamically
* Complete a reservation through a modal form

This project demonstrates modern frontend development practices including reusable components, state-driven UI updates, and scalable folder organization.

---

## 🛠 Tech Stack

* ⚛️ React (Create React App)
* 📦 react-scripts
* 🧠 JavaScript (ES6+)
* 🎨 CSS
* 📁 Component-based architecture

---

## 📂 Project Structure

```
carrental/
│
├── public/
│   ├── index.html
│   ├── rent-icon.png
│   └── rent-icon2.png
│
├── src/
│   ├── Pages/          # Page-level components
│   ├── components/     # Reusable UI components
│   ├── images/         # Image assets
│   ├── styles/         # CSS styling
│   ├── App.js          # Root component
│   └── index.js        # Application entry point
│
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

---

## 🚀 Features

* Interactive vehicle fleet display
* Dynamic vehicle selection
* Real-time rental pricing updates
* Vehicle details panel (Model, Year, Transmission, Fuel, AC, Doors)
* Reservation modal popup
* Personal information form
* Responsive and modern UI design

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/carrental.git
cd carrental
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Run the Application

```bash
npm start
```

The application will run locally at:

```
http://localhost:3000
```

---

## 📦 Available Scripts

### `npm start`

Runs the app in development mode.

### `npm run build`

Builds the app for production.

### `npm test`

Launches the test runner.

---

## 🧠 Architecture & Design

This application follows a modular and scalable frontend architecture:

* Reusable React components
* State-based rendering for vehicle updates
* Clear separation of styles and logic
* Organized folder structure for maintainability

The current structure allows easy future integration of:

* Backend API
* Database connection
* Authentication system
* Payment processing
* Admin dashboard

---

## 🔧 Troubleshooting

If you encounter:

```
sh: react-scripts: command not found
```

Run:

```bash
npm install
```

If the issue persists:

```bash
rm -rf node_modules package-lock.json
npm install
```

---

## 👤 Author

Rufai Yakubu
GitHub: https://github.com/yrufai

---

## 📄 License

This project is licensed under the MIT License.
