# 📚 Advanced Library Management System  
*A Smart and Efficient Approach to Library Operations*

---

## 🚀 Overview

The **Advanced Library Management System** streamlines library operations including book and member management, handling transactions, and generating reports. It integrates a user-friendly frontend with a secure and efficient backend to manage book inventory, member records, and transaction history.

---

## 📌 Features

### 📖 Book Management
- Add, remove, and update books in the library inventory.
- Each book has:
  - Title
  - Author
  - Genre
  - Publication Year
  - Unique Identifier (ISBN/Barcode)
  - Availability Status

### 👥 Member Management
- Register new members.
- Maintain member records including:
  - Name, Address, Contact Information
  - Borrowing History
- Borrow and return book functionality.
- Fine calculation for overdue returns.

### 🔍 Search and Browse
- Search the catalog by:
  - Title
  - Author
  - Genre
  - Publication Year

### 📊 Reporting
- Generate detailed reports for:
  - Book inventory
  - Member statistics
  - Borrowing trends
  - Overdue fines

---

## 🧩 Class Design

- **Book**: Represents a book object.
- **Member**: Stores details of each registered member.
- **Transaction**: Records of each borrowing/returning activity.

---

## 🗄️ Database Design

- Relational Database Schema using **MySQL**:
  - `Books`
  - `Members`
  - `Transactions`
  - `Login`

*ER Diagram and flowchart representations are available for clarity.*

---

## 🖥️ User Interface

Designed using **Java Swing**, the GUI provides:
- Login panel
- Book management screen
- Member registration form
- Book issue/return interface
- Report generation panel

### 📸 Interface Snapshots

#### 🔐 Login Panel
![Login Panel](https://github.com/Sugamshaw/Advance-Library-Management-System/blob/main/src/Image/p1.png)

#### 📚 Book Management
![Book Management](https://github.com/Sugamshaw/Advance-Library-Management-System/blob/main/src/Image/p2.png)

#### 👥 Student Registration
![Student Registration](https://github.com/Sugamshaw/Advance-Library-Management-System/blob/main/src/Image/p3.png)

#### 🔄 Add Book
![Add Book](https://github.com/Sugamshaw/Advance-Library-Management-System/blob/main/src/Image/p4.png)

#### 📊 Book Issue
![Book Issue](https://github.com/Sugamshaw/Advance-Library-Management-System/blob/main/src/Image/p5.png)

#### 📊 Return Book
![Return Book](https://github.com/Sugamshaw/Advance-Library-Management-System/blob/main/src/Image/p6.png)

#### 📚 Book Details
![Book Details](https://github.com/Sugamshaw/Advance-Library-Management-System/blob/main/src/Image/p7.png)

---


## ⚙️ Backend

- Language: **Java**
- Database: **MySQL**
- Connectivity: **JDBC**
- Secure login using prepared statements to prevent SQL injection.

**Key Component**: `ConnectMySQL.java` – Handles DB connections and query executions.

---

## 🔄 Integration

- Frontend (Swing) communicates with the backend via **Java JDBC**.
- Login actions trigger database validation.
- Successful login redirects to the Home screen; failures prompt error messages via `JOptionPane`.

---

## 🛠️ Deployment

To deploy:
1. Install Java JDK and MySQL server.
2. Import the database schema from the provided `.sql` file.
3. Run the project from your Java IDE (e.g., IntelliJ, Eclipse).
4. Ensure JDBC driver is configured in your build path.

---

## 📈 Performance & Scalability

- Optimized SQL queries for high performance.
- Scalable to handle large volumes of books and transactions.
- Modular design for easy future enhancements.

---

## 📚 Training & Documentation

- Training sessions for library staff.
- Included help manual within the software.
- Clean UI ensures minimal learning curve.

---

## 📌 Sample Workflow Diagram

![Workflow Diagram](https://github.com/Sugamshaw/Advance-Library-Management-System/blob/main/src/Image/flowchart.png)

---

## ✅ Future Enhancements

- Add barcode scanning support.
- Integrate email/SMS reminders for due dates.
- Enable online member registration and remote catalog access.

---


