# Library-Inventory-Manager

**Course:** Programming for Problem Solving using Python

**Author:** Aayan Srivastwa
## Overview
A small command-line library inventory manager that demonstrates object-oriented design, file persistence (CSV), exception handling, and a menu-driven CLI.

## Files
- `library_manager/book.py` — `Book` class
- `library_manager/inventory.py` — `LibraryInventory` class and CSV persistence
- `cli/main.py` — Menu-driven command-line interface
- `data/catalog.csv` — Stored catalog (created on first run)
- `tests/test_library.py` — unit tests using `unittest`

## How to run

1. Run the CLI:

```bash
python -m cli.main
```

The program stores catalog data in `data/catalog.csv`.

**Folder Structre**

library-inventory-manager-yokshit-csv/
│
├── cli/
│   ├── __init__.py
│   └── main.py
│
├── library_manager/
│   ├── __init__.py
│   ├── book.py
│   └── inventory.py
│
├── tests/
│   ├── __init__.py
│   └── test_library.py
│
├── data/
│   └── catalog.csv
│
├── README.md
├── requirements.txt
├── .gitignore
├── setup.py
├── Output
<img width="419" height="190" alt="Screenshot 2025-11-23 204703" src="https://github.com/user-attachments/assets/1b2e1640-54ba-4bf5-84ff-46412ec02741" />
<img width="1041" height="335" alt="Screenshot 2025-11-23 204947" src="https://github.com/user-attachments/assets/447bb6e7-c407-4fff-bd4d-13470f7c52c9" />
<img width="1063" height="372" alt="Screenshot 2025-11-23 205027" src="https://github.com/user-attachments/assets/613d3772-d5c0-470d-b4ad-88b98af65ae9" />

#Features
Add Books – Add new books to the library catalog
Issue Books – Mark books as issued to students/staff
Return Books – Mark issued books as available again
Search Books – Find books by title or ISBN
View All Books – Display the entire catalog



**Bibliography**

- `Youtube` = Brocode
- `Google`
- `W3Schools.com`
