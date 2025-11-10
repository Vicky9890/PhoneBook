# 📒 PhoneBook Management System (C Project)

A simple **PhoneBook Management System** built in **C language**, designed to store, manage, and retrieve contact information efficiently using file handling.  
This project demonstrates structured programming concepts, file operations, and user interaction through console-based menus.

---

## 🚀 Features

- **Add New Record** – Add new contact details including name, address, phone number, etc.  
- **List Records** – View all saved contact records.  
- **Search Record** – Search and display details of a person by name.  
- **Modify Record** – Update or edit existing contact information.  
- **Delete Record** – Remove a contact permanently from the file.  
- **Exit Option** – Gracefully close the application.

---

## ⚙️ Functional Overview

| Function | Description |
|-----------|--------------|
| `menu()` | Displays the main menu and navigates options. |
| `addrecord()` | Adds a new contact record to the file. |
| `listrecord()` | Lists all stored records sequentially. |
| `searchrecord()` | Finds and displays a specific contact by name. |
| `modifyrecord()` | Allows modification of an existing record. |
| `deleterecord()` | Deletes a selected contact record permanently. |
| `got()` | Custom input function to handle character-by-character input. |

---

## 💾 File Handling

All records are stored in a binary file named **`project`**.  
Each operation (`add`, `list`, `modify`, `delete`, etc.) reads or writes to this file using `fread()` and `fwrite()` functions.

---

## 🖥️ How to Run the Project

### 🧱 Requirements
- **C Compiler** (e.g., GCC, Turbo C)
- Works on **Windows** and **Linux (terminal-based)** systems

### ▶️ Steps to Compile & Run

#### On Windows (GCC)
1. Install [MinGW](https://www.mingw-w64.org/) and add it to your system PATH.
2. Open CMD in your project directory.
3. Compile the code:
   ```bash
   gcc PhoneBook.c -o PhoneBook
   ```
4. Run the executable:
   ```bash
   PhoneBook
   ```

#### On Turbo C
1. Open the source file (`PhoneBook.c`) in Turbo C.
2. Press **Alt + F9** to compile.
3. Press **Ctrl + F9** to run the program.

---

## 📸 Menu Preview

```
*****WELCOME TO PHONEBOOK*****
        MENU

1. Add New      2. List        3. Exit
4. Modify       5. Search      6. Delete
```

---

## 🧠 Example Usage

### ➕ Adding a Record
```
Enter name: Vikash
Enter address: Bhubaneswar
Enter Father name: Ramesh
Enter Mother name: Sunita
Enter Phone no.: 9876543210
Enter Sex: Male
Enter e-mail address: vikash@example.com
Enter citizen no: AB1234
Record saved
```

### 🔍 Searching a Record
```
Enter name of person to search
Vikash

Detail Information About Vikash
Name: Vikash
Address: Bhubaneswar
Father name: Ramesh
Mother name: Sunita
Mobile no: 9876543210
Sex: Male
E-mail address: vikash@example.com
Citizen no: AB1234
```

### 🗑️ Deleting a Record
```
Enter CONTACT'S NAME: Vikash
RECORD DELETED SUCCESSFULLY.
```

---

## 📚 Concepts Used

- File handling in C (`fopen`, `fread`, `fwrite`, `fseek`, `remove`, `rename`)
- Structures (`struct`)
- Functions and modular programming
- Conditional and loop control
- Console I/O (`getch()`, `putch()`, `printf()`)

---

## 🧠 Future Enhancements

- Add password protection or login system.  
- Use `.csv` format for data portability.  
- Implement sorting (e.g., by name or phone number).  
- Build a GUI using C++ or Python for better visualization.  

---

## 👨‍💻 Author

**Vikash Kumar Pradhan**  
📧 [vpradhan2002@gmail.com](mailto:vpradhan2002@gmail.com)  
