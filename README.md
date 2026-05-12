# Integrated Library System

A web-based Library Management System for managing books, members, book issuing, returns, transactions, overdue records, and library reports.

## Features

- Admin login system
- Dashboard with library summary cards
- Add and manage members
- Add and manage books
- Auto-generated member and book IDs
- Issue books to registered members
- Return multiple books
- Due date tracking
- Overdue fine calculation
- Transaction history
- View all members and books
- Export reports as CSV
- Print transaction and overdue reports
- JSON-based local data storage
- C backend demo for linked-list based book operations

## Tech Stack

- HTML
- CSS
- JavaScript
- Node.js
- Express.js
- JSON
- C

## Project Structure

```text
library-system/
├── backend/
│   └── library.c
├── data/
│   ├── books.json
│   ├── members.json
│   ├── member.json
│   └── transactions.json
├── frontend/
│   ├── login.html
│   ├── dashboard.html
│   ├── style.css
│   └── script.js
└── middleware/
    ├── server.js
    ├── package.json
    └── package-lock.json
