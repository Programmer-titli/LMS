# LMS


This Java console application lets you manage a small library collection: add books, display the catalogue, borrow/return titles, search, and delete entries.

<img width="310" height="202" alt="Image" src="https://github.com/user-attachments/assets/010139a2-858f-4f70-90ac-8fbf31a3eddc" />

## Project: "LMS (Console Edition)"
This will be a Library Management System (LMS) where users can:
- Add new books.
- View a list of books.
- Search for books by title or author.
- Borrow books.
- Return books.
- Remove books.

<br/>

## Features:
- *Add Book*: Users can add a new book with details like title, author, ISBN, genre, and availability.
- *Display Books*: Display all the books with their details.
- *Search Books*: Search by title or author.
- *Borrow Books*: Mark a book as borrowed.
- *Return Books*: Mark a book as returned.
- *Delete Book*: Delete a book from the system.
- *Command-line interface (CLI)*: Interact with the system via console commands.
- Clear, table‑like catalogue display with availability status.
- Real‑time count of total and available books.

<br/>

## Quick Start
1. Compile:
```bash
javac Main.java
```
2. Run:
```bash
java Main
```

<br/>

## Project Structure
- ```Book.java```: Book data model (ID, Title, Author, Status)
- ```Library.java```: Core library operations(add, display, borrow, return, delete)
- ```Main.java```: Program entry point

<br/>

## Usage Guide
1. Launch the program: ```java Main```
2. Follow the on - screen menu:<br/>
  <img width="261" height="222" alt="Image" src="https://github.com/user-attachments/assets/96bc8b97-ec54-4999-99b5-9c106a127a1c" />
3. Enter the choice number and supply any requested details (book ID, title, etc.)
4. Exit the application from the menu when done.

<br/>

## Output
<img width="1906" height="1031" alt="Image" src="https://github.com/user-attachments/assets/906baa7f-e043-468f-9b59-bd174bb37f4a" />
<img width="1917" height="1025" alt="Image" src="https://github.com/user-attachments/assets/52bdb6c2-6b87-44b3-8919-bdce4bfecaef" />
<img width="1541" height="670" alt="Image" src="https://github.com/user-attachments/assets/7cd57ef2-a34e-4d15-beb0-726370aa667f" />
## Notes & Limitations
- Data resides only in memory; it resets every time the program stops.
- Input validation is minimal; invalid data may cause errors.

<br/>

## License
This project is released under the MIT License - see the [LICENSE](LICENSE) file for details.
