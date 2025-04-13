# 📚 BookStore MERN Stack Application

A full-stack BookStore web application built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). This app allows users to browse, add, update, and delete books from the store.


## Features

- 📘 View all books
- 🔍 Search for books by title or author
- ➕ Add a new book (Admin only)
- ✏️ Update existing book details (Admin only)
- ❌ Delete books (Admin only)
- 🧾 Book details page


## Tech Stack

**Frontend**  
- React.js  
- React Router DOM  
- Axios  
- Tailwind CSS 

**Backend**  
- Node.js  
- Express.js  
- MongoDB  
- Mongoose  
- JSON 


##  Installation

### Prerequisites

- Node.js and npm
- MongoDB (local or cloud)
- Git


## 📂 Folder Structure

BookStore-MERN/
├── backend/
│   ├── models/
│   │   └── bookModel.js
│   ├── routes/
│   │   └── booksRoute.js
│   ├── config.js
│   ├── index.js
│   └── package.json
│
├── frontend/
│   ├── public/
│   │   └── vite.svg
│   ├── src/
│   │   ├── assets/
│   │   │   └── react.svg
│   │   ├── components/
│   │   │   ├── home/
│   │   │   │   ├── BookModal.jsx
│   │   │   │   ├── BookSingleCard.jsx
│   │   │   │   ├── BooksCard.jsx
│   │   │   │   ├── BooksTable.jsx
│   │   │   ├── BackButton.jsx
│   │   │   └── Spinner.jsx
│   │   ├── pages/
│   │   │   ├── CreateBooks.jsx
│   │   │   ├── DeleteBook.jsx
│   │   │   ├── EditBook.jsx
│   │   │   ├── Home.jsx
│   │   │   └── ShowBook.jsx
│   │   ├── App.jsx
│   │   ├── index.css
│   │   └── main.jsx
│   └── package.json
└── README.md




## Acknowledgments
MERN Stack tutorials from freeCodeCamp
