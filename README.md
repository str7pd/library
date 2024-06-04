Menu Options:

Option 1 (Add a Book):
Prompts the user for book details (title, author, year, gender).
Handles invalid year input by allowing the user to retry or exit the add operation.
Adds the book to the library if all inputs are valid.
Option 2 (Remove a Book):
Prompts the user for the book title to remove.
Calls the removeBook method to remove the book.
Option 3 (Search for a Book):
Provides sub-options to search by title or author.
Prompts the user for the search term and displays the result.
Option 4 (Display Books):
Displays the list of books in the library.
Option 5 (Exit):
Exits the loop and ends the program.
Error Handling:

Catches NumberFormatException to handle cases where the user inputs a non-integer value when an integer is expected.
This program provides a simple console-based interface for managing a library of books. It allows the user to add,
remove, search, and display books using a menu-driven approach. The Library class encapsulates the functionality for
managing the books, while the main function provides the user interface and handles user input and errors.

