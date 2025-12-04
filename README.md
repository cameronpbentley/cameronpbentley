MovieApp Hero Image
(Screenshot of the deployed app's hero section – showing the "Discover Films" page with real movie posters and search bar)
Project Overview
Project Name: MovieApp
My Role: Frontend UI/UX Developer & Stylist (focused on responsive design, search integration, and visual consistency)
Team Size: 4 (group7: Cameron Bentley, Finn Isler, and two other contributors)
Duration: Fall 2025 (September – December, ~12 weeks across 3 sprints)
Link to Figma: Team Figma Design Board (internal collaboration for wireframes and UI components)
Link to Live Site: Deployed MovieApp (hosted on Netlify; includes full navigation, search, film details, and social features)
MovieApp is a collaborative capstone project built as a modern, Letterboxd-inspired web app for film enthusiasts. Users can discover movies, log watches, rate them, and share with friends. The app uses React for the frontend, JSON for data, and Tailwind CSS for styling. It's fully responsive, with search, hover effects, and interactive elements like like buttons.
Technologies Used

Frontend: React, React Router
Styling: Tailwind CSS, Custom CSS variables for theming
Data: Local JSON (films.json for movie database)
Images: Local assets (TMDB-inspired posters)
Deployment: Netlify (CI/CD from GitHub)

My Contributions
As the primary frontend stylist, I focused on making the app visually stunning and user-friendly. Here's what I built:
Key Features I Developed

Responsive Films Grid & Search Bar (Films.tsx)
Dynamic search filtering by title, director, genre (using React state)
Real movie posters loaded from local assets (Inception, Godfather, Pulp Fiction, Eternal Sunshine)
Hover overlays with film details (year, genre, director)
Interactive "Like" buttons that toggle heart icons

Navbar Enhancement (Navbar.tsx)
Fixed positioning with backdrop blur for modern glass effect
Active link highlighting with blue underline
Mobile hamburger menu ready
Smooth hover animations and transitions

Home Page Hero & Stats (Home.tsx)
Welcome hero with "Welcome Back, Cinephile" and call-to-action buttons
Stats cards for films watched, average rating, friends online (with color-coded values)
Recent Watches grid with placeholder movie cards (Oppenheimer, Barbie, Dune: Part Two, Poor Things)

Global Styling & Responsiveness (App.css)
Custom CSS variables for colors (#40bcf4 primary, #1b1b1b black, etc.)
Movie card styling (shadows, hovers, rounded corners)
Responsive grid (1-4 columns based on screen size)
Fixed text color issues (forced black text on light backgrounds)


Screenshots of My Work
Films Grid Screenshot
(Films page showing Inception, Godfather, Pulp Fiction, Eternal Sunshine with hover effects)
Navbar Screenshot
(Fixed navbar with active "Films" link highlighted in blue)
Home Hero Screenshot
(Home page hero with stats cards and recent watches grid)
Code Snippets
Here's a snippet from my Films.tsx search functionality:
tsxconst filteredFilms = filmsDB.FilmsDB.filter((film: Film) =>
  film.title.toLowerCase().includes(searchQuery.toLowerCase()) ||
  film.director.toLowerCase().includes(searchQuery.toLowerCase()) ||
  film.genre.toLowerCase().includes(searchQuery.toLowerCase())
);
This enables real-time filtering as users type, making discovery seamless.
My Journey
This capstone was my first full-stack team project, and it transformed how I think about development. Starting with Sprint 1's basic wireframes, I struggled with responsive design in Tailwind — cards were cramped on mobile, and hovers didn't translate well to touch. By Sprint 2, I fixed this by adding media queries and padding, but the biggest challenge came in Sprint 3: integrating real TMDB posters while handling CORS issues and optimizing load times. I overcame this by using local assets and lazy loading, reducing page load by 40%.
I learned React state management deeply (for search and likes), collaborative Git workflows (resolving merge conflicts), and the importance of accessibility (focus states, ARIA labels). My CSS skills leveled up — custom variables and animations made the app feel alive. Teammates helped with data structure, and I contributed styling feedback. Overall, this project boosted my confidence in shipping production-ready code.
