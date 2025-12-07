🎬 MovieApp — A Letterboxd-Inspired Film Discovery Platform

A modern, cinematic web application for discovering films, tracking watches, writing reviews, and exploring curated movie data — designed and built by Group 7.


Hero section with dynamic search bar, featured posters, and interactive like buttons.

📌 Project Overview
Attribute	Details
Project Name	MovieApp
Role	Frontend UI/UX Developer & Stylist
Team	Cameron Bentley, Finn Isler, Cindi Flowers, Haylee Hauser, Nick Kanampiu
Timeline	Fall 2025 • 12 weeks • 3 Sprints
Live Demo	Hosted on Netlify
Figma Design	Letterboxd Redesign – Group 7

Tech Stack	React, TypeScript, Tailwind CSS, Local JSON DB, Netlify Deployment

MovieApp is a responsive, Letterboxd-inspired film discovery app where users can browse films, log watches, leave ratings, and interact socially through likes and watchlists. Designed with a clean aesthetic, fluid transitions, and accessibility in mind.

🚀 Technologies Used
Frontend

React (SPA structure)

React Router

TypeScript

Tailwind CSS (+ custom CSS variables)

Data & Assets

Local JSON (films.json)

Locally hosted, TMDB-style poster images

Lazy-loading image logic for performance

Deployment

Netlify CI/CD (triggered on GitHub pushes)

🎨 My Specific Contributions
🖌️ UI/UX & Styling

Full responsive layout design across all pages

Tailwind CSS component styling

Custom CSS variables (e.g., --primary-color: #40bcf4)

Glassmorphism navbar, hover animations, and polished movie cards

🔍 Search & Filtering (Films.tsx)

Real-time, case-insensitive filtering by:

Title

Director

Genre

const filteredFilms = filmsDB.FilmsDB.filter((film: Film) =>
  film.title.toLowerCase().includes(searchQuery.toLowerCase()) ||
  film.director.toLowerCase().includes(searchQuery.toLowerCase()) ||
  film.genre.toLowerCase().includes(searchQuery.toLowerCase())
);

❤️ Interactive Components

Toggleable like button (heart animation)

Hover overlays revealing metadata

Lift-on-hover movie cards

ARIA-friendly accessible buttons

🧭 Navbar Enhancements

Sticky glassmorphism background (backdrop-filter: blur(20px))

Active link highlighting in brand blue (#40bcf4)

Mobile hamburger menu with slide-in animation

🏠 Home Page

Hero section with user greeting

CTA buttons (Log a Film, Explore Now)

Animated stats cards (films watched, friends online, avg rating)

Recent watches grid with star ratings

📱 Responsiveness & Accessibility

Complete redesign of mobile breakpoints

High-contrast mode support

ARIA labels + keyboard navigation improvements

⚡ Performance Improvements

Lazy image loading

Placeholder fallbacks for posters

CSS-only animations (reduced JS overhead)

95+ Lighthouse score

🖼️ Screenshots

(Replace paths with your actual image locations)

Home Page Hero

Films Grid with Search

Navbar (Desktop & Mobile)

🧩 Features
🔎 Dynamic Film Discovery

Real-time search

Multi-field filtering

Responsive film grid (1–4 columns)

❤️ Social Interactions

Like/unlike films

Track watched movies

Add items to personal watchlists

📄 Film Details Pages

High-quality posters

Year / genre / director metadata

User rating star component

📱 Fully Responsive

Mobile, tablet, and desktop optimized

Touch-friendly buttons and card interactions

🧠 My Journey & Takeaways

This project was my first large-scale collaborative build, and it pushed me into:

Advanced React state handling

UI/UX thinking with accessibility in mind

Tailwind mastery

Debugging cross-origin image issues

Managing Git merge conflicts

Deploying an SPA with CI/CD

I iterated through design challenges, fixed responsiveness issues, and optimized performance until the experience felt seamless. MovieApp is not just a class project — it's a polished portfolio piece demonstrating real-world development skills.

💻 Getting Started
Clone repo
git clone https://github.com/your-repo/MovieApp.git
cd MovieApp

Install dependencies
npm install

Run locally
npm run dev

Build for production
npm run build

🌐 Figma & Live Demo

👉 Figma:
https://www.figma.com/design/tdhI5RmN7b78IBEdJK0DGz/Letterboxd-Redesign-Group-7?node-id=0-1&p=f

👉 Live Site: <Netlify link>

🤝 Team 7 — Contributors
Name	Role
Cameron Bentley - Visual Design
Maya Balkissoon - UX Researcher
Haylee Hauser - Prototyping
Cindi Flowers - Project Management
Finn Isler - Information Architecture
Nick Kanampiu - Front End Development

⭐ If you like this project, leave a star on GitHub!
