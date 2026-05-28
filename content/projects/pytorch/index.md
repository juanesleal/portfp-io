---
title: Watchlist (Capstone Project)
date: 2023-05-21

tags:
  - JavaScript
  - HTML
  - CSS
  - Docker
  - React
  - HugoBlox
  - Markdown
---

WatchList is a Netflix-inspired web application built as a group capstone project, combining a React frontend with a Python/Django backend to deliver personalized movie recommendations using machine learning.
The app integrates with the TMDB API to surface a curated home feed organized by genre — trending, top rated, action, horror, sci-fi, and more — and uses a custom ML recommendation engine on the backend that generates personalized picks based on each user's rating history. Recommendations are fetched from the backend via a token-authenticated REST endpoint and hydrated with full movie details from TMDB in real time.
Key features include user authentication (sign up / login with JWT-style token management), a watch history tracker, a personal playlist, inline YouTube trailer playback on poster click, and a dual star-rating system letting users log their own score alongside the aggregate audience rating.
Built with React 18, React Router v6, and Axios on the frontend, with a Node/Express proxy server bridging the client and backend services.
Tech: React, React Router, Axios, TMDB API, YouTube embed, Node.js/Express, Django REST Framework, token-based authentication, collaborative filtering / ML recommendation engine
<!--more-->
