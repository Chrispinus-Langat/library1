Classes:
Book: Represents a book with attributes such as title, author, and availability status.

User: Represents a library user with a name.

Library: Manages books and users, provides functionalities such as adding books, removing books, searching for books, borrowing books, and returning books.

Operations:
Adding a Book: Users can add books to the library by providing the title and author.

Removing a Book: Books can be removed from the library by specifying the title.

Searching for Books: Users can search for books by providing a search term. The search term is matched against both the title and author of each book.

Borrowing a Book: Users can borrow a book from the library by specifying the title. If the book is available, its availability status is updated, and the user is informed.

Returning a Book: Users can return a borrowed book to the library by specifying the title. If the book is not already available, its availability status is updated, and the user is informed.

Sample Usage:
Adding sample books to the library.

Searching for books containing the term "Scott".

Borrowing "The Great Gatsby" and "To Kill a Mockingbird" by a user named "John Doe".

Returning "To Kill a Mockingbird".

Searching for books containing the term "Scott" after borrowing.

Readme:
Compilation: Compile the program using a C++ compiler. For example, using g++, run g++ -o library_management library_management.cpp.

Execution: Execute the compiled program. For example, ./library_management.

Usage: Follow the instructions displayed in the program's output to interact with the library management system.

Customization: You can customize the program by modifying the main() function to add more books, perform different operations, or create multiple users.

Dependencies: The program uses standard C++ libraries and does not require any external dependencies.

Contributions: Contributions to the program, such as adding new features or improving existing ones, are welcome. Please follow the existing code style and conventions.

License: This program is provided under an open-source license. See the accompanying license file for details.

Feedback: If you encounter any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request on the project's repository.
