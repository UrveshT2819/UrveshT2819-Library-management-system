📚 **Library Management System – C Project**
This is a console-based Library Management System built using the C programming language. It allows you to manage books and track issued books using simple binary file operations.

🔧 **Features**
✅ Add new books to the library

📃 **View all available books**
❌ Remove a book by its ID
📕 Issue a book to a student
📄 View list of all issued books

📂 **File Structure**
books.txt: Stores all added book records
issue.txt: Stores all issued book records

🖥️ **How It Works**
This project uses:
Structures (struct) to store book and student data
Binary file I/O (fopen, fwrite, fread) to store and retrieve data
Menu-driven interface for easy user interaction

🧑‍💻 **How to Run**
✅ Windows (Turbo C / Code::Blocks / Dev C++)
Open the .c file in your preferred C IDE.
Compile and run the program.
All features will work as expected including getch() and system("cls").

✅ **Online (e.g., OnlineGDB)**
Remove or comment the following lines:
#include <conio.h>
getch();
system("cls");
Use getchar(); in place of getch(); to pause output.

🧾 **Sample Menu**
<== Library Management System ==>
1. Add Book
2. Books List
3. Remove Book
4. Issue Book
5. Issued Book List
0. Exit


💡 **Future Enhancements (Optional Ideas)**
Add book quantity tracking
Add return book feature
Implement user authentication (admin vs. student)
Port to C++ with classes or GUI (e.g., using Qt)

🧑 **Author
Urvesh Thubrikar**
