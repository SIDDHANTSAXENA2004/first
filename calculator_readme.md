
# 🧮 Simple Calculator in C

This is a simple command-line calculator program written in C. It allows users to perform basic arithmetic operations: **Addition**, **Subtraction**, **Multiplication**, and **Division**.

---

## 📋 Features

* Menu-driven interface
* Supports floating-point numbers
* Basic error handling for invalid menu options

---

## 🛠️ How It Works

1. Displays a menu with 4 options:

   * 1: Addition
   * 2: Subtraction
   * 3: Multiplication
   * 4: Division
2. User selects an operation by entering a number (1–4).
3. Prompts the user to input two numbers.
4. Performs the selected operation and prints the result.

---

## 💻 Sample Output

```
Enter a number from the list below

1. Addition
2. Subtraction
3. Multiplication
4. Division

Enter number: 1

You entered Addition

Enter first number: 10
Enter second number: 20

10.00 + 20.00 = 30.00
```

---

## 🔧 How to Compile and Run

Make sure you have a C compiler (like `gcc`) installed.

```bash
gcc calculator.c -o calculator
./calculator
```

---

## 📂 File Structure

```
calculator.c      // Main source code
README.md         // This documentation file
```

---

## ✅ Future Improvements (Optional)

* Input validation for non-numeric inputs
* Division by zero handling
* Loop for continuous use until the user exits
* Enhanced UI with color using ANSI escape codes

---

## 📄 License

This project is open-source and free to use for educational purposes.

---
