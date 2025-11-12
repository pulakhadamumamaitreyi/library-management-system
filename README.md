# library-management-system
## 🚀 Features

### 📘 Book Management
- Add new books to the library with details: title, author, ISBN, genre, and quantity.
- Update or remove existing books.
- Display all available books.

### 👤 Borrower Management
- Add new borrowers (name, contact, membership ID).
- Update borrower details.
- Remove borrowers from the system.

### 🔄 Book Borrowing & Returning
- Borrow books by linking a borrower’s membership ID with a book’s ISBN.
- Automatically assign a due date for return.
- Handle overdue book returns.
- Return books and update availability.

### 🔍 Search & Availability
- Search books by **title**, **author**, or **genre**.
- Display availability (number of copies left).

---


## 🧠 Class Design Overview

| Class | Responsibility |
|--------|----------------|
| **Book** | Represents a single book record and supports updates. |
| **Borrower** | Represents a library member with borrowing records. |
| **Library** | Core system managing books, borrowers, borrowing, and returns. |


