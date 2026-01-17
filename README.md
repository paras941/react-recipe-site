🍽️ RecipeX

A modern, responsive recipe web application built with React and Vite, demonstrating real-world usage of core React concepts like useState, useEffect, props, routing, and component-based architecture, with modular SCSS styling.

This project is built to showcase clean frontend structure and best practices for portfolio, internships, and placement interviews.

🚀 Tech Stack

React (Vite)
JavaScript (ES6+)
React Router DOM
SCSS (Modular Styling)
Responsive Design

📂 Project Structure
react-recipe-app/
├── public/
│   └── images/
├── src/
│   ├── components/
│   │   ├── Navbar/
│   │   ├── RecipeCard/
│   │   ├── SearchBar/
│   │   └── Footer/
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── RecipeDetails.jsx
│   │   └── Favorites.jsx
│   ├── styles/
│   │   ├── partials/
│   │   │   ├── _variables.scss
│   │   │   ├── _mixins.scss
│   │   │   └── _reset.scss
│   │   └── index.scss
│   ├── App.jsx
│   └── main.jsx
│
├── index.html
├── package.json
├── vite.config.js
└── README.md
## ⚛️ React Concepts Used

| Feature / Hook            | Where Used                 | Purpose                               |
|--------------------------|----------------------------|----------------------------------------|
| `useState`               | Search, Favorites, Filters| Manage UI and recipe state              |
| `useEffect`              | Recipe Fetching           | Handle API calls and side-effects       |
| Props                    | All Components            | Data flow between components            |
| React Router             | App.jsx                   | Client-side routing                     |
| Conditional Rendering    | RecipeList, Loader        | Dynamic UI rendering                    |
| Reusable Components      | RecipeCard, Navbar        | Clean component architecture             |

🧠 Core Functionalities

Browse Recipes
Recipe Details Page
Search & Filter Recipes
Add to Favorites
Responsive Layout
SCSS Modular Styling

🛠 Installation
git clone https://github.com/your-username/react-recipe-app.git
cd react-recipe-app
npm install
npm run dev

🔮 Future Improvements

API Integration (Spoonacular / Edamam)
User Authentication
Meal Planner
Dark / Light Theme
Nutrition Information
