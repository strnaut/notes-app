# Notes App

A full-stack web application for creating, managing, and sharing rich-text notes[cite: 1, 2]. This project is built with a monorepo architecture, separating the client and server environments into their respective directories.

## 🚀 Tech Stack

- **Frontend:** React (Vite), Tailwind CSS, TipTap (Rich Text Editor)
- **Backend:** Node.js, Express, Prisma ORM
- **Database:** PostgreSQL (Containerized via Docker)[cite: 1, 2]

## ✨ Features

- **Authentication:** Secure user registration and login flow[cite: 1, 2].
- **Rich Text Notes:** Create, read, update, and delete notes seamlessly using the TipTap editor[cite: 1, 2].
- **Visibility Control:** Toggle notes between `private` (default) and `public` via a confirmation dialog[cite: 1, 2].
- **Explore & Search:** Browse public notes on the Explore feed and find specific content using full-text search[cite: 1, 2].
- **Bookmarks:** Save and manage your favorite public notes[cite: 1, 2].

## 📂 Project Structure

This repository uses a monorepo setup:

- `/client`: Contains the React frontend application[cite: 2].
- `/server`: Contains the Node.js/Express backend API[cite: 2].
- `docker-compose.yml`: Contains the PostgreSQL database service configuration for local development.
