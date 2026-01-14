# Postfix Expression Evaluator (C++)

This project implements a **Postfix (Reverse Polish Notation) Expression Evaluator** using **C++**, **Stacks**, and **Object-Oriented Programming (OOP)** concepts.  
It evaluates arithmetic expressions written in postfix form efficiently.

---

## 🎯 Objective

The objective of this project is to:
- Understand **stack-based expression evaluation**
- Apply **OOP concepts** in C++
- Practice handling operators and operands
- Learn postfix (Reverse Polish) notation

---

## 🧠 Concepts Used

- Stack Data Structure  
- Object-Oriented Programming (OOP)  
- Classes and Member Functions  
- Conditional Statements  
- Character and Digit Handling  
- Expression Evaluation Logic  

---

## 🧾 Program Description

- A **PostfixEvaluator** class is created
- Uses a stack to store operands
- Iterates through the postfix expression:
  - If a digit is found → push to stack
  - If an operator is found → pop two operands, apply operation, push result back
- Final stack value is the evaluated result

---

## 🧩 Class Structure

### Class: `PostfixEvaluator`

**Member Function**
- `int evaluate(string exp)`

---

## ▶️ Example Expression

