# prime-number-checker
This program checks whether a given number is a prime number or not. A prime number is a number greater than 1 that has no divisors other than 1 and itself.
# 🔢 Prime Number Checker

This is a simple Python program to check whether a number is a **prime number** or not.

---

## 📌 What is a Prime Number?

A **prime number** is a number greater than 1 that has **only two factors**:  
**1 and itself.**  
Examples of prime numbers: 2, 3, 5, 7, 11, 13, etc.

---

## 🧠 How the Program Works

1. The user is prompted to enter a number.
2. The program checks if the number is less than or equal to 1.  
   If yes, it's **not a prime number**.
3. Then, it checks if the number is divisible by any number between **2 and (number - 1)**.
4. If it's divisible by any of them, it's **not prime**.
5. If no divisors are found, the number **is a prime number**.

---

## 🛠️ Technologies Used

- Python 3

---

## 🚀 How to Run the Program

1. Make sure Python is installed on your system.
2. Copy the code into a file, for example: `prime_checker.py`
3. Open a terminal or command prompt.
4. Run the program:
   ```bash
   python prime_checker.py
