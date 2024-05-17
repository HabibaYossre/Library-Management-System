# Library Management System

This library management system is designed to manage library operations efficiently. It includes functions for handling book information, user management (students and administrators), borrowing and returning books, searching for books by author or category, and displaying relevant information to users and administrators. The system ensures secure login, password management, and user registration functionalities.

## Function Descriptions

### Book Management
- **ModifyBookInfo**: Allows administrators to modify information about existing books.
- **Modify_order**: Manages the order of book modifications or updates.
- **addbook**: Adds a new book to the library's collection.
- **deletebook**: Deletes a book from the library's collection.
- **display_booklist**: Displays a list of all books in the library.
- **display_available_books_only**: Displays a list of books that are currently available for borrowing.
- **book_info**: Provides detailed information about a specific book.
- **borrowbook**: Handles the process of borrowing a book.
- **returnbook**: Handles the process of returning a borrowed book.
- **search_author**: Allows users to search for books by a specific author.
- **search_category**: Allows users to search for books by category.

### User Management
- **sign_up**: Allows new students to sign up for a library account.
- **login_student**: Handles the login process for students.
- **login_admin**: Handles the login process for administrators.
- **forgot**: Manages the process for students to recover forgotten passwords.
- **change_password**: Allows users to change their passwords.
- **hide_password**: Hides the password input field for security during user input.
- **hide_password_check**: Hides the password input field during password confirmation.

### User Information and Profile
- **info_stud**: Displays detailed information about a student.
- **myprofile**: Displays the profile of the logged-in user (student).
- **displaystudentinfo**: Displays information about students for administrators.
- **displaystudentinfo_for_admin**: Specifically displays student information accessible by administrators.
- **displayfeedback**: Displays feedback provided by students.

### Administrative Functions
- **main_admin**: The main interface for administrators, providing access to administrative functions.
- **main_student**: The main interface for students, providing access to student functions.
- **bookservices**: Provides book-related services such as borrowing and returning.
- **logging**: Manages logging of system events and user actions for security and audit purposes.
- **Modify_order**: Manages the modification order for book updates or other administrative tasks.

### Loading and Utility Functions
- **loading1, loading2, loading3, loading4**: Functions to handle different stages of loading processes.
- **date**: Manages date-related information and operations.

## Class Descriptions

- **class library**: Represents the library, managing collections of books and overall library operations.
- **class student_info**: Represents student information, managing details related to library users.

## Main Function
- **main**: The main entry point for the system, initializing and managing the overall application flow.

This system aims to streamline library operations, ensuring easy access to books and user management, and providing a secure and user-friendly interface for both students and administrators.
