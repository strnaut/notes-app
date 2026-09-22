# Notes App

A full-stack web application for creating, managing, and sharing rich-text notes. This project is built with a monorepo architecture, separating the client and server environments into their respective directories.

## 🚀 Tech Stack

- **Frontend:** React (Vite), Tailwind CSS, TipTap (Rich Text Editor)
- **Backend:** Node.js, Express, Prisma ORM
- **Database:** PostgreSQL (Containerized via Docker)

## ✨ Features

- **Authentication:** Secure user registration and login flow.
- **Rich Text Notes:** Create, read, update, and delete notes seamlessly using the TipTap editor.
- **Visibility Control:** Toggle notes between `private` (default) and `public` via a confirmation dialog.
- **Explore & Search:** Browse public notes on the Explore feed and find specific content using full-text search.
- **Bookmarks:** Save and manage your favorite public notes.

## 📂 Project Structure

This repository uses a monorepo setup:

- `/client`: Contains the React frontend application.
- `/server`: Contains the Node.js/Express backend API.
- `docker-compose.yml`: Contains the PostgreSQL database service configuration for local development.
