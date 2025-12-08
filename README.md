🎬 MovieApp — A Letterboxd-Inspired Film Discovery Platform

A modern, cinematic web application for discovering films, tracking watches, writing reviews, and exploring curated movie data — designed and built by Group 7.

<img width="1918" height="953" alt="image" src="https://github.com/user-attachments/assets/abdb1bea-6219-46b5-947a-0f15bbac2dd0" />
📌 Project Overview
Attribute	Details
Project Name	MovieApp
Role	Frontend UI/UX Developer & Stylist
Team	Cameron Bentley, Finn Isler, Cindi Flowers, Haylee Hauser, Nick Kanampiu
Timeline	Fall 2025 • 12 weeks • 3 Sprints
Live Demo	Hosted on Netlify
Figma Design	Letterboxd Redesign – Group 7

Tech Stack: React, TypeScript, Tailwind CSS, Local JSON DB, Netlify Deployment

MovieApp is a responsive, Letterboxd-inspired film discovery app where users can browse films, log watches, leave ratings, and interact socially through likes and watchlists — all through a clean, modern UI with smooth animation and strong accessibility.

🚀 Technologies Used
Frontend

React (SPA)

React Router

TypeScript

Tailwind CSS + CSS variables

Data & Assets

Local JSON (films.json)

Locally hosted poster images

Lazy image loading

Deployment

Netlify CI/CD

GitHub repo integration

🎨 My Specific Contributions
🖌️ UI/UX & Styling

Full responsive layout for all screens

Tailwind component styling

Custom CSS variables

Glassmorphism navbar & card interactions

🔍 Search & Filtering (Films.tsx)
const filteredFilms = filmsDB.FilmsDB.filter((film: Film) =>
  film.title.toLowerCase().includes(searchQuery.toLowerCase()) ||
  film.director.toLowerCase().includes(searchQuery.toLowerCase()) ||
  film.genre.toLowerCase().includes(searchQuery.toLowerCase())
);

❤️ Interactive Components

Like button animations

Hover overlays

Accessible ARIA buttons

🧭 Navbar Enhancements

Sticky glass effect

Active link highlighting (#40bcf4)

Mobile hamburger menu

🏠 Home Page

Hero with greeting

CTA buttons

Stats cards

Recent watches grid

📱 Responsiveness & Accessibility

Redesigned mobile layouts

High contrast support

Keyboard navigation

⚡ Performance

Lazy loading

Poster placeholders

CSS-only animations

95+ Lighthouse score

🖼️ Screenshots

All images placed above their titles + in correct order.

<img width="1918" height="953" alt="image" src="https://github.com/user-attachments/assets/abdb1bea-6219-46b5-947a-0f15bbac2dd0" />
Home Page Hero
<img width="1915" height="956" alt="image" src="https://github.com/user-attachments/assets/bdf7631e-8285-490d-afd5-7fb167df5e91" />
Films Grid with Search
<img width="1918" height="954" alt="image" src="https://github.com/user-attachments/assets/7925e4c6-c3bc-4fe5-b268-58cc46e48f3a" />
Profile Screen
<img width="1917" height="954" alt="image" src="https://github.com/user-attachments/assets/61e880b9-4fe2-4816-80e0-522297aea10c" />
Friends Screen
<img width="1918" height="957" alt="image" src="https://github.com/user-attachments/assets/41fd63e9-abe7-42a9-8acc-c61216428df4" />
Achievements Screen
<img width="1279" height="594" alt="image" src="https://github.com/user-attachments/assets/843cd9b1-d96a-4b39-ab4b-b421d30abcc5" />
Recent Activity Screen
<img width="1903" height="954" alt="image" src="https://github.com/user-attachments/assets/9beb741f-f424-4828-84b4-62c627c0c4e8" />
Movie Filter Screen
<img width="1902" height="952" alt="image" src="https://github.com/user-attachments/assets/648c750d-6a91-4359-8f22-9b809c479fe7" />
Working Search Bar
<img width="1311" height="918" alt="image" src="https://github.com/user-attachments/assets/595f8679-e498-4872-b843-549bc1379317" />
Watchlist Screen
<img width="1902" height="954" alt="image" src="https://github.com/user-attachments/assets/83e88c34-1bb3-4a5e-8840-e930bdc36a4e" />
Film Details Screen
<img width="930" height="594" alt="image" src="https://github.com/user-attachments/assets/b03e53b3-11f0-45eb-a55f-65f14589229a" />
<img width="950" height="875" alt="image" src="https://github.com/user-attachments/assets/6446fe70-ea45-47a4-915c-0b2906ccd0fc" />
<img width="1035" height="563" alt="image" src="https://github.com/user-attachments/assets/eb336d7b-e218-4a01-8e8a-d3016e892983" />
All Reviews Screen
<img width="1901" height="921" alt="image" src="https://github.com/user-attachments/assets/0ed39b93-fe2b-4b9b-981d-72f0a7d24834" />
Movie Cards With Interactive Elements





🧩 Features
🔎 Dynamic Film Discovery

Real-time search

Multi-field filtering

Responsive grid

❤️ Social Interactions

Like/unlike

Add to watchlist

Track watched films

📄 Film Details

Poster

Metadata

User rating system

📱 Fully Responsive

Mobile → tablet → desktop

Smooth animations

🧠 My Journey & Takeaways

This project strengthened my skills in:

React state management

UI/UX and accessibility

Tailwind mastery

Performance optimization

SPA deployment

Git collaboration

MovieApp became a portfolio-quality app that reflects real-world development workflow.

💻 Getting Started

Clone the repo:

git clone https://github.com/Finn-Isler1/group7/tree/main
cd group7


Install dependencies:

npm install


Run locally:

npm run dev


Build for production:

npm run build

🌐 Figma & Live Demo

👉 Figma:
https://www.figma.com/design/tdhI5RmN7b78IBEdJK0DGz/Letterboxd-Redesign-Group-7?node-id=0-1&p=f

👉 Live Site:
[<Netlify link>](https://finn-isler1.github.io/group7/#/)

🤝 Team 7 — Contributors
Name	Role
Cameron Bentley	Visual Design
Maya Balkissoon	UX Research
Haylee Hauser	Prototyping
Cindi Flowers	Project Management
Finn Isler	Information Architecture
Nick Kanampiu	Front-end Development

⭐ If you like this project, leave a star on GitHub!
