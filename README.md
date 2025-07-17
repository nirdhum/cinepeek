# 🎬 CinePeek

CinePeek is a modern, responsive movie discovery app built with **React**, **Tailwind CSS**, and the **TMDB API**. It allows users to explore trending, upcoming, and top-rated movies, search for specific titles, and view detailed information including trailers, cast, and metadata — all in a sleek, cinematic UI.

👉[CinePeek Live View](https://cinepeek.vercel.app/)

<!-- ![CinePeek Live View](./public/preview.png)  -->

---

## 🚀 Features

- 🔍 **Search Movies**: Type and search in real-time via TMDB.
- 📱 **Responsive Design**: Fully mobile-first layout with Tailwind.
- 🌐 **TMDB API Integration**: Fetch real-time movie data and media.

---

## 🛠️ Tech Stack

- **React** – Front-end UI framework
- **Tailwind CSS** – Utility-first styling
- **TMDB API** – Movie and TV show data
- **React Router DOM** – Routing between pages

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/nirdhum/cinepeek.git

# Navigate into the project directory
cd cinepeek

# Install dependencies
npm install

# Start development server
npm run dev
```

### Make sure to add your own TMDB API key (see below).

## 🔑 Getting Your TMDB API Key

Sign up at https://www.themoviedb.org.

Go to your API settings and generate an API key.

Create a .env.local file in the root directory and add:

```bash
VITE_TMDB_API_KEY=your_tmdb_api_key_here
```

## 📁 Project Structure

```bash
cinepeek/
├── public/
├── src/
│   ├── components/
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .env.local
└── vite.config.js

```

## 🧠 Planned Future Enhancements

- Add better pagination or infinite scroll
- Implement favorites/watchlist using localStorage
- Add 404 page for invalid routes
- Improve loading states and error boundaries
- Implement movie details page with trailer view and watch more section
- Implement categories, genre, filters etc

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

Nirdhum
