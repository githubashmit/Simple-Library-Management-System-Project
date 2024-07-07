
# Project Title
The code implements a simple library management system using C++. The system allows 
librarians to manage books and users, and students to issue and return books. The main 
functionalities include adding, deleting, searching books, and managing user accounts. The 
code uses hash tables for efficient storage and retrieval of books and users.
Upon starting the program, the user is presented with the main menu:
-------------------------------------------------------------------------------------------------------------
| |
| - W E L C O M E T O T H E LIBRARY - |
| |
-------------------------------------------------------------------------------------------------------------
Please Choose an appropriate option : 
=======================================
0. Exit
1. LogIn as Librarian
2. LogIn as Student
Please Pick any one option: 
Login:
If the user selects "LogIn as Librarian":
-----------------------------------------------------
| |
| LogIn as Librarian |
| |
-----------------------------------------------------
 Username : admin

  Password : admin

  If login is successful:

  Access granted.

  If login fails:

  Error : Invalid username or password.

  You have 2 tries left.

  If the user selects "LogIn as Student":

  -----------------------------------------------------
  | |
  | LogIn as Student |
  | |
  -----------------------------------------------------
   Username : admin

    Password : admin

    If login is successful:

    Access granted.

    If login fails:

    Error : Invalid username or password.

    You have 2 tries left.

    Librarian Menu:

    After a successful login as a librarian, the following menu is displayed:

    ++++++++++ M E N U ++++++++++

    Welcome [Librarian Name]

    0. Exit

    1. Display All Books

    2. Insert a Book

    3. Delete a Book

    4. Search Book

    5. Show Books by Genre

    6. Register a Student

    7. LogOut

    Select an option:

    Option 1: Display All Books

    ID: 12345

    Book Name: Harry Potter

    Author: JK Rowling

    Genre: Fiction

    Quantity Available: 5

    [List of all books]

    Option 2: Insert a Book

    Book Name: The Hobbit

    Author Name: J.R.R. Tolkien

    Book Genre: Fantasy

    Book Quantity: 10

    Option 3: Delete a Book

    Book Name: The Hobbit

    Author Name: J.R.R. Tolkien

    Book Genre: Fantasy

    [BOOK DELETED]

    Option 4: Search Book

    Book Name: The Hobbit

    Author Name: J.R.R. Tolkien

    Book Genre: Fantasy

    [BOOK FOUND]

    Book Title Book Author Book Genre Book Quantity

    The Hobbit J.R.R. Tolkien Fantasy 10

    Option 5: Show Books by Genre

    Enter Genre: Fantasy

    The Hobbit by J.R.R. Tolkien

    [List of all books in the specified genre]


    Option 6: Register a Student

    Student Name: John Doe

    Password: ****

    [USER ADDED]

    Option 7: LogOut

    Student Menu:

    After a successful login as a student, the following menu is displayed:

    ++++++++++ M E N U ++++++++++

    Welcome [Student Name]

    0. Exit

    1. Display All Books

    2. Issue a Book

    3. Return a Book

    4. Show all Issued Books

    5. Search Book

    6. Show Books by Genre

    7. LogOut

    Option 1: Display All Books

    ID: 12345

    Book Name: Harry Potter

    Author: JK Rowling

    Genre: Fiction

    Quantity Available: 5

    [List of all books]

    Option 2: Issue a Book

    Book Name: The Hobbit

    Author Name: J.R.R. Tolkien

    Book Genre: Fantasy

    [ISSUED]

    Option 3: Return a Book

    Book Name: The Hobbit

    Author Name: J.R.R. Tolkien

    Book Genre: Fantasy

    [RETURNED]

    Option 4: Show all Issued Books

    [BOOKS ISSUED BY: John Doe]

    Book Title Book Author Book Genre

    The Hobbit J.R.R. Tolkien Fantasy

    Option 5: Search Book

    Book Name: The Hobbit

    Author Name: J.R.R. Tolkien

    Book Genre: Fantasy

    [BOOK FOUND]

    Book Title Book Author Book Genre Book Quantity

    The Hobbit J.R.R. Tolkien Fantasy 10

    Option 6: Show Books by Genre

    Enter Genre: Fantasy

    The Hobbit by J.R.R. Tolkien

    [List of all books in the specified genre]

    Option 7: LogOut
    



