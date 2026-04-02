# 🛒 Online Shopping Management System (C++)

---

## 1. 📝 Introduction
The Online Shopping Management System is a **console-based application** developed in **C++** using **Object-Oriented Programming (OOP)** concepts.  
This project allows managing products, customers, and shopping operations efficiently.  

It reduces manual work, simulates a real shopping experience, and provides **cart management, billing, and product storage**.

---

## 2. 🎯 Objectives of the Project
- Implement **Object-Oriented Programming** concepts  
- Manage **product records** efficiently  
- Perform operations like **add product, view products, add to cart, and generate bills**  
- Understand the use of **vectors (dynamic arrays)** and **file handling**  
- Simulate a **real-world online shopping system**  

---

## 3. 🛠 Methodology / System Design
The system is designed using **OOP principles**:

- **Class & Object** → `Product`, `CartItem`, `ShoppingSystem`, `User`, `Admin`, `Customer`  
- **Encapsulation** → Data accessed using member functions  
- **Inheritance** → `Admin` and `Customer` classes inherit from abstract `User` class  
- **Polymorphism** → `menu()` function is overridden in `Admin` and `Customer`  
- **Data Structure Used** → **Vector** for dynamic storage of products and cart items  
- **File Handling** → Save/load products from a file (`products.txt`)  

### 🔄 System Flow:
1. User selects **Admin** or **Customer** from the main menu  
2. Admin can **add products** and **view products**  
3. Customer can **view products, add items to cart, view cart, and generate bill**  
4. Product data is **stored in a file** for persistence  
5. Menu repeats until the user exits  

---

## 4. 💻 Implementation / Source Code
The project is implemented in **C++** and includes the following features:

- **Add Product** (Admin only)  
- **View Products** (Admin & Customer)  
- **Add to Cart** (Customer only)  
- **View Cart** (Customer only)  
- **Generate Bill** (Customer only)  
- **File Handling** to save and load product data  

### 🛠 Technologies Used:
- **C++ Programming Language**  
- **Standard Template Library (STL - vector)**  
- **File Handling** for persistent storage  

---

## 5. ✅ Conclusion
This project demonstrates how **Object-Oriented Programming** can be applied to a **real-world online shopping system**.  
It improves understanding of **inheritance, polymorphism, encapsulation, and data management**.

### 🔮 Future Improvements:
- Add **user authentication** for Admin and Customer  
- Add **inventory management** (stock quantity control)  
- Create a **graphical user interface (GUI)**  
- Connect with a **database** (MySQL or SQLite)  

---

## 👤 Author
- Roshani  
- Prachi  
- Margi  

---

## ▶ How to Run
1. Make sure **C++ compiler** is installed  
2. Compile the program:  
```bash
g++ -o shopping_system main.cpp
