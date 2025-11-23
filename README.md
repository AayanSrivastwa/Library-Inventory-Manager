# Library Inventory Manager

**Course:** Programming for Problem Solving using Python  
**Assignment:** Lab Assignment 3

A command-line library inventory manager that demonstrates object-oriented design, file persistence (CSV), exception handling, and a menu-driven CLI.

## Overview

This project is a small yet functional library management system built as part of a Python programming course. It showcases fundamental programming concepts including OOP principles, file I/O operations, error handling, and user interface design through a command-line interface.

## Features

- **Add Books** – Add new books to the library catalog with details like title, author, ISBN, and availability status
- **Issue Books** – Mark books as issued to students/staff
- **Return Books** – Mark issued books as available again
- **Search Books** – Find books by title or ISBN
- **View All Books** – Display the entire catalog with current status

## Project Structure

```
library-inventory-manager/
│
├── cli/
│   ├── __init__.py
│   └── main.py                 # Menu-driven command-line interface
│
├── library_manager/
│   ├── __init__.py
│   ├── book.py                 # Book class
│   └── inventory.py            # LibraryInventory class and CSV persistence
│
├── tests/
│   ├── __init__.py
│   └── test_library.py         # Unit tests using unittest
│
├── data/
│   └── catalog.csv             # Stored catalog (created on first run)
│
├── README.md
├── requirements.txt
├── .gitignore
├── setup.py
└── Output
```

## Installation

### Prerequisites
- Python 3.x or higher
- pip package manager

### Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/AayanSrivastwa/Library-Inventory-Manager.git
cd Library-Inventory-Manager
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python -m cli.main
```

The program will automatically create `data/catalog.csv` on first run to store catalog data.

## Usage

### Running the CLI

Start the application:
```bash
python -m cli.main
```

You'll be presented with a menu-driven interface with the following options:

1. **Add Book** - Enter book details (title, author, ISBN)
2. **Issue Book** - Mark a book as issued by ISBN
3. **Return Book** - Mark an issued book as available
4. **Search Book** - Search by title or ISBN
5. **View All Books** - Display complete catalog
6. **Exit** - Save and exit the program

### Example Workflow

```
Library Inventory Manager
-------------------------
1. Add Book
2. Issue Book
3. Return Book
4. Search Book
5. View All Books
6. Exit

Choose an option: 1
Enter title: The Great Gatsby
Enter author: F. Scott Fitzgerald
Enter ISBN: 978-0743273565
Book added successfully!
```

## Assignment Tasks Completed

✅ **Task 1: Book Class Design**  
Implemented the `Book` class in `library_manager/book.py` with proper attributes and methods

✅ **Task 2: Inventory Manager**  
Created the `LibraryInventory` class in `library_manager/inventory.py` to manage book operations

✅ **Task 3: File Persistence (CSV)**  
Implemented CSV-based storage for catalog data in `data/catalog.csv`

✅ **Task 4: Menu-Driven CLI**  
Developed an interactive command-line interface in `cli/main.py`

✅ **Task 5: Exception Handling & Logging**  
Added robust error handling and logging throughout the application

✅ **Task 6: Project Packaging**  
Structured the project with proper packages and `setup.py` for distribution

## Components

### `library_manager/book.py`
Contains the `Book` class that represents individual books with attributes like title, author, ISBN, and availability status.

### `library_manager/inventory.py`
Contains the `LibraryInventory` class that manages the collection of books, handles CSV file operations, and provides methods for adding, issuing, returning, and searching books.

### `cli/main.py`
Provides the menu-driven command-line interface for user interaction.

### `data/catalog.csv`
CSV file that stores the library catalog persistently between sessions.

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## Testing

Run the test suite:
```bash
python -m pytest tests/
```


## Authors
Aayan Srivastwa
2501410049
B.Tech CSE Cyber Security(First Semester)
22nd November 2025
Programming With Python - Lab Assignment 3
