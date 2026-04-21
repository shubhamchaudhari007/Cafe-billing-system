# ☕ Cafe Billing System – C Project

## 🚀 Overview

The Cafe Billing System is a console-based application developed in **C** that automates cafe operations with two main modes: **Admin Mode** and **Billing Mode**.

The system uses **CSV files for data storage**, allowing persistent menu management and daily sales tracking. It enables efficient billing using product IDs and maintains a history of transactions for analyzing total earnings.

---

## 🎯 Features

### 🔐 Admin Mode

* ✅ Add new items with unique product IDs
* ✅ Store item details in CSV file
* ✅ Manage menu dynamically
* ✅ Maintain daily sales history
* ✅ Track total earnings for the day

### 🧾 Billing Mode

* ✅ Select items using product ID
* ✅ Enter quantity for each item
* ✅ Automatic bill calculation
* ✅ Generate formatted receipt
* ✅ Store transaction in history file

---

## 🧠 Concepts Used

* File Handling (CSV Read/Write)
* Structured Programming in C
* Functions and Modular Design
* Arrays and Strings
* Loops and Conditional Statements
* Data Management using Files

---

## ⚙️ Technologies Used

* **Language:** C
* **Platform:** Linux / Windows
* **Compiler:** GCC

---

## 🏗️ Project Structure

```id="cafestruct2"
CafeBillingSystem/
│── main.c
│── admin.c
│── billing.c
│── file_handler.c
│── header.h
│── menu.csv        (stores items with unique IDs)
│── history.csv     (stores daily transactions)
```

---

## ▶️ How to Run

### 1. Compile the program

```bash id="cafec3"
gcc *.c -o cafe
```

### 2. Run the program

```bash id="cafec4"
./cafe
```

---

## 💻 Sample Usage

```bash id="cafesample2"
1. Admin Mode
2. Billing Mode

Enter choice: 1

[Admin]
Enter Item ID: 101
Enter Item Name: Coffee
Enter Price: 20
Item added successfully

Enter choice: 2

[Billing]
Enter Item ID: 101
Enter Quantity: 2

Total Bill: ₹40
Saved to history
```

---

## ⚠️ Limitations

* ❌ No graphical interface (CLI-based)
* ❌ No authentication for admin mode
* ❌ Limited validation for incorrect IDs

---

## 🔮 Future Enhancements

* 🔹 GUI-based version
* 🔹 Database integration (MySQL/SQLite)
* 🔹 Multi-user login system
* 🔹 Advanced analytics (weekly/monthly reports)

---

## 🧩 Challenges Faced

* Managing CSV file read/write operations
* Ensuring unique product IDs
* Maintaining accurate billing and history
* Handling invalid user inputs

---

## 📚 Learning Outcomes

* Practical use of file handling in C
* Understanding real-world data storage using CSV
* Experience in modular program design
* Improved debugging and logic building skills

---

## 📌 Author

**Shubham Chaudhari**
