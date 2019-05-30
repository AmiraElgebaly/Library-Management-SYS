# Library-Management-SYS
The library, contains tens of thousands of books and members which must be organized in order to prevent chaos. Write C++ program that allow performance of the actions needed to manage the library in a simple and comfortable way.  The actions will include addition/removal of books, addition/removal of members, member and book searches, and much more. 
The system will support two distinct types of users Librarians and Readers. For each user (reader/librarian) exists a unique Id and password, used for user authentication to prove identity of the user.
Reader should have (FirstName, LastName, Address, Cellphone, Email, isBlocked)


Here are the types and the actions available for each type of users:

1) Librarians that can:
Add/Remove a book from the library.
Add/Remove a user from the library.
Search for books or members.
Add/Remove users from Book- Order list
Blocking of users who return books late
Rent a book.

2) Readers that can:
-Searching of books or users.
-Addition of self to Book- Order list.
-Rent or buy a book.


Request should have (ID, ISBN, Request date, Due date), and It has two types (Buy or Borrow).

Books should have (ISBN,Title,Author,Location,Number of Copies, Genre, price)

