# OOP_Exercise_Shopping_Cart.ipynb


# 🛒 Shopping Cart - OOP Lab in Python

## 📌 Introduction

Welcome to the **Shopping Cart Lab**! In this project, you’ll apply your knowledge of **object-oriented programming (OOP)** in Python to simulate the functionality of a shopping cart. You'll build a class that allows users to:

- Add items of different prices and quantities
- Apply discounts
- Track items added to the cart
- Void the last transaction

This lab provides a hands-on approach to practicing how objects and classes can be used to model real-world systems.

---

## 🎯 Objectives

By completing this lab, you will be able to:

- Define and call instance methods
- Define and access instance attributes
- Use instance methods inside other instance methods
- Write methods to calculate statistics based on object attributes
- Design a basic domain model using object-oriented programming principles

---

## 🛠️ Instructions

1. Open the `shopping_cart.py` file to begin working with the `ShoppingCart` class.
2. Implement and modify class methods to fulfill the cart's functionality.
3. Use a Jupyter notebook (or any Python environment) to test your changes. 
4. Use autoreload (in Jupyter) to automatically reload your code updates, but remember to **reinitialize your class instances** after each change.

Here’s a basic template to get you started in your notebook:

```python
%load_ext autoreload
%autoreload 2

from shopping_cart import ShoppingCart

cart = ShoppingCart()
```

---

## 🧠 Key Concepts Covered

- Object Initialization (`__init__`)
- Instance Methods and Attributes
- Aggregation of Data (e.g., total price, discounts)
- Method Composition
- Error Handling and Input Validation

---

## 📁 File Structure

```
project-directory/
│
├── shopping_cart.py       # Main class file to be edited
├── README.md              # You're here!
└── your_notebook.ipynb    # Jupyter notebook for testing (optional)
```

---

## ✅ Completion Checklist

Make sure your `ShoppingCart` class can:

- [x] Add an item with name, price, and quantity
- [x] Keep track of items in the cart
- [x] Calculate and apply discounts
- [x] Void the last transaction
- [x] Calculate total cost of items in the cart

---

## 🚀 Happy Coding!

Let me know if you'd like a sample `ShoppingCart` class or want to generate an example test notebook!
