# 🎬 Movie Tickets App

A modern React-based Movie Tickets web application where users can browse movies and add them to favorites.

## 🚀 Features
- 🎥 View list of movies
- ❤️ Add to Favorites
- 🔍 Clean and responsive UI
- 🧭 Navigation using components
- 📦 Organized folder structure
- ⚡ Built with React + Vite

## 🛠️ Tech Stack

- React.js
- JavaScript (ES6+)
- CSS
- Vite
- ESLint

## 📂 Project Structure
Movie-Tickets/
│
├── public/ # Static public files
├── src/
│ ├── assets/ # Images and icons
│ │ └── react.svg
│ │
│ ├── components/ # Reusable UI components
│ │ ├── MovieCard.jsx
│ │ └── NavBar.jsx
│ │
│ ├── contexts/ # React Context API files
│ │
│ ├── css/ # Stylesheets
│ │ ├── App.css
│ │ ├── Favorites.css
│ │ ├── Home.css
│ │ ├── index.css
│ │ ├── MovieCard.css
│ │ └── Navbar.css
│ │
│ ├── pages/ # Application pages
│ │ ├── Home.jsx
│ │ └── Favorites.jsx
│ │
│ ├── services/ # API logic
│ │ └── api.js
│ │
│ ├── App.jsx # Main App component
│ └── main.jsx # Entry point
│
├── index.html # Root HTML file
├── package.json # Project dependencies
├── package-lock.json
├── eslint.config.js # ESLint configuration
├── .gitignore
└── README.md

## ⚙️ How It Works

1. 🏠 When the application starts, the Home page displays a list of movies.

2. 🎬 Each movie is shown using the MovieCard component with details like title, poster, and action buttons.

3. ❤️ Users can add movies to their Favorites list by clicking the favorite icon/button.

4. 📌 Favorite movies are stored using React state (and Context if implemented).

5. ⭐ The Favorites page displays all selected movies.

6. 🔄 Users can remove movies from favorites anytime.

7. 🧭 Navigation between Home and Favorites is handled using components.

8. 📡 Movie data is fetched from an API service (`api.js`) or predefined data.

9. 📱 The UI is responsive and works on desktop and mobile devices.

📌 Author
- Satheesh

