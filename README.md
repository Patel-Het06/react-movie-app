# 🎬 React Movie App

A movie discovery web application built with **React and Vite**, powered by The Movie Database (TMDB) API. Browse popular movies, search for your favorite films, and save movies to your personal favorites list.

## ✨ Features

- 🎥 **Popular Movies** — Browse a collection of popular movies.
- 🔍 **Search Movies** — Search for movies by title.
- ❤️ **Favorites** — Add movies to or remove movies from your favorites list.
- 💾 **Local Storage** — Favorites are saved in the browser and persist after refreshing the page.
- 🧭 **Navigation** — Navigate between the Home and Favorites pages.
- 📱 **Responsive Styling** — CSS styling designed to adapt to different screen sizes.
- ⚡ **Fast Development** — Powered by Vite for a fast development experience.

## 🛠️ Technologies Used

- **React** — Building reusable UI components.
- **Vite** — Development server and build tool.
- **React Router** — Client-side navigation.
- **JavaScript (ES6+)** — Application logic and API requests.
- **CSS3** — Styling and responsive layouts.
- **TMDB API** — Movie data and poster images.
- **Local Storage** — Persisting favorite movies in the browser.
- **Git & GitHub** — Version control and project hosting.

## 📂 Project Structure

```text
react-movie-app/
├── public/
├── src/
│   ├── components/
│   │   ├── MovieCard.jsx
│   │   └── NavBar.jsx
│   ├── context/
│   │   └── MovieContext.jsx
│   ├── css/
│   │   ├── App.css
│   │   ├── Favorites.css
│   │   ├── Home.css
│   │   ├── MovieCard.css
│   │   ├── Navbar.css
│   │   └── index.css
│   ├── pages/
│   │   ├── Home.jsx
│   │   └── Favorties.jsx
│   ├── services/
│   │   └── api.js
│   ├── App.jsx
│   └── main.jsx
├── .gitignore
├── package.json
├── index.html
└── README.md
```

## 🚀 Getting Started

Follow these steps to run the project locally.

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/react-movie-app.git
```

Replace `YOUR_USERNAME` with your GitHub username.

### 2. Navigate to the project directory

```bash
cd react-movie-app
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure the TMDB API

Get an API key from [The Movie Database (TMDB)](https://www.themoviedb.org/).

Create a `.env.local` file in the project root:

```env
VITE_TMDB_API_KEY=your_tmdb_api_key
```

Update your API service to read the key from `import.meta.env.VITE_TMDB_API_KEY` instead of hardcoding it.

**Note:** Vite environment variables prefixed with `VITE_` are included in client-side code. Do not treat this key as a secret; restrict it appropriately and never commit your environment file.

### 5. Start the development server

```bash
npm run dev
```

Open the local URL shown in your terminal to view the application.

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Build the production application |
| `npm run preview` | Preview the production build |
| `npm run lint` | Check the code with ESLint |

## 🎯 Learning Objectives

This project helped me practice:

- Building reusable React components.
- Managing state with `useState`.
- Fetching API data asynchronously.
- Using `useEffect` to load popular movies.
- Sharing state with React Context.
- Implementing client-side routing with React Router.
- Persisting data with `localStorage`.
- Rendering movie lists using `.map()` and unique keys.
- Handling search forms and user interactions.

## 🔮 Future Improvements

- Add movie details pages.
- Add movie ratings and reviews.
- Improve loading states and error handling.
- Add pagination or infinite scrolling.
- Add genre filters and sorting options.

## 🙌 Acknowledgements

- [The Movie Database (TMDB)](https://www.themoviedb.org/) for movie data and poster images.
- [React](https://react.dev/) for the UI library.
- [Vite](https://vite.dev/) for the development tooling.

---

⭐ If you find this project useful, consider giving the repository a star!

**Built with ❤️ using React.**