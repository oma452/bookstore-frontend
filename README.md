# Bookstore Frontend

A React + Vite frontend for managing a bookstore catalog. This application allows users to view, create, edit, and delete books through a clean and responsive UI.

The project is designed to work with a bookstore backend API and provides an interactive interface for CRUD operations on books.

## Features

- Display books in table or card view
- Add a new book
- View detailed book information
- Edit existing book records
- Delete books with confirmation
- Responsive user interface using Tailwind CSS
- Client-side routing with React Router
- Toast notifications for user feedback

## Tech Stack

- React
- Vite
- JavaScript
- Tailwind CSS
- Axios
- React Router DOM
- React Icons
- Notistack

## Project Structure

```text
bookstore-frontend/
├── dist/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   └── home/
│   ├── pages/
│   │   ├── CreateBooks.jsx
│   │   ├── DeleteBook.jsx
│   │   ├── EditBook.jsx
│   │   ├── Home.jsx
│   │   └── ShowBook.jsx
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .eslintrc.cjs
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
└── README.md
```

## Installation

1. Clone the repository.
2. Navigate to the project folder.
3. Install dependencies:

```bash
npm install
```

## Running the App

Start the development server:

```bash
npm run dev
```

This will run the app in development mode, usually on:

```text
http://localhost:5173
```

## API Connection

This frontend connects to a bookstore backend API running locally. The app currently uses:

```text
http://localhost:5555/books
```

Make sure the backend is running before using the app.

## Available Pages

- Home page: list the books in either table or card format
- Create book page: add a new book
- Book details page: view information about a selected book
- Edit book page: update book details
- Delete book page: confirm and remove a book

## Example Book Data

```json
{
  "title": "The Alchemist",
  "author": "Paulo Coelho",
  "publishYear": 1988,
  "description": "A philosophical novel about finding one's destiny."
}
```

## Scripts

```bash
npm run dev
npm run build
npm run preview
npm run lint
```

## Notes

- This repository is the frontend only.
- It expects a working backend API for book data.
- Styling is handled with Tailwind CSS, and the UI is configured for a modern bookstore dashboard experience.

## License

This project is licensed under the ISC license.
