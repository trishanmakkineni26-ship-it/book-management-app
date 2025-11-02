# Book Management App

Simple web app to manage books with SQLite database.

## Database Schema
```sql
CREATE TABLE Book (
    book_id INTEGER PRIMARY KEY,
    title TEXT,
    author TEXT,
    price REAL
)
```

## API Endpoints
- **GET /books** - Get all books
- **POST /books** - Add new book

## Setup & Run

1. Install dependencies:
```bash
npm install
```

2. Start server:
```bash
npm start
```

3. Open browser: http://localhost:3000

## Files
- `server.js` - Backend API
- `public/index.html` - Frontend UI
- `package.json` - Dependencies
