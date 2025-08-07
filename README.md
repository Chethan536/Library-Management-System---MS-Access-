## 📚 **Library Management System – Microsoft Access Project**

### 🔍 **Overview**

A complete Library Management System built using **Microsoft Access**, designed to simplify and automate the tracking of books, students, and issue/return transactions in a small to medium-sized library.

---

### 🎯 **Key Features**

* Add, update, and manage book and student/member records
* Track book issue and return activity
* Automatic fine calculation for late returns
* Generate reports: inventory, issued/overdue books, borrowing history
* User-friendly form-based interface for easy data handling

---

### 🧱 **Database Design (Entities & Tables)**

* **Books:** BookID, Title, Author, Genre, Publisher, Availability
* **Students:** StudentID, Name, Class, Contact Info
* **IssueRecords:** Track which student borrowed which book, with issue/due dates
* **Returns (Optional):** Return status and penalties
* **Users (Optional):** Admin access or user roles

---

### 📄 **Forms (UI)**

* Book Entry Form
* Student Registration Form
* Issue Book Form
* Return Book Form
* Search & Filter Forms

---

### 📊 **Reports**

* List of currently issued books
* Overdue books with fines
* Book inventory
* Student borrowing history

---

### ⚙️ **Technologies Used**

* Microsoft Access (.accdb)
* SQL (Access Queries)
* VBA (Visual Basic for Applications)
* Macros (Optional)

---

### 📝 **How to Use**

1. Open the `.accdb` file in Microsoft Access (2016 or later recommended)
2. Navigate using the main menu or switchboard
3. Use forms for entry, updates, and book tracking
4. Generate reports from the reports tab or print-friendly views

---

### 💡 **Use Cases**

* School or college libraries
* Community or personal library systems
* Database learning projects for students

---

### 📥 **Future Enhancements**

* Barcode scanner integration
* Role-based multi-user login system (Admin, Librarian, etc.)
* Email reminders for due books
* Export reports to PDF

---
