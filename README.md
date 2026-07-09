# Palindrome String Checker in Python

## 📌 Overview

This project checks whether a given string is a **palindrome** using the **two-pointer technique**.

A palindrome is a word, phrase, or sequence that reads the same forward and backward. The program compares characters from both ends of the string and moves toward the center until a mismatch is found or all characters match.

This approach is efficient because it avoids creating a reversed copy of the string.

---

## 🚀 Features

* Checks whether a string is a palindrome
* Uses the two-pointer algorithm
* Efficient comparison from both ends
* Prints `True` if the string is a palindrome
* Prints `False` if the string is not a palindrome
* Beginner-friendly implementation

---

## 🛠️ Technologies Used

* Python 3

---

## 📂 Project Structure

```text
├── palindrome_checker.py
└── README.md
```

---

## 💻 Source Code

```python
s = "ADGHREVBGH"

n = len(s)
left = 0
right = n - 1

while left < right:
    if s[left] != s[right]:
        print(False)
        break

    left += 1
    right -= 1
else:
    print(True)
```

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/python-palindrome-checker.git
cd python-palindrome-checker
```

### Run the Program

```bash
python palindrome_checker.py
```

---

## 📋 Sample Output

### Example 1

```text
Input : MADAM
Output: True
```

### Example 2

```text
Input : RADAR
Output: True
```

### Example 3

```text
Input : ADGHREVBGH
Output: False
```
---

## 🧠 Concepts Covered

* Strings
* While Loop
* Two-Pointer Technique
* Conditional Statements
* Loop Control (`break`)
* `while-else` Statement

---

## 🔍 How It Works

1. Store the string in a variable.
2. Initialize two pointers:

   * `left` → first character
   * `right` → last character
3. Compare the characters at both pointers.
4. If they differ, print `False` and stop.
5. If they match, move the pointers toward the center.
6. If the loop completes without finding a mismatch, print `True`.

---

## ⏱️ Complexity Analysis

| Operation        | Complexity |
| ---------------- | ---------- |
| Time Complexity  | **O(n)**   |
| Space Complexity | **O(1)**   |

Where **n** is the length of the string.

---

## 🔮 Future Improvements

* Accept user input instead of a fixed string
* Ignore spaces and punctuation
* Perform case-insensitive palindrome checking
* Support palindrome checking for numbers
* Build a GUI version using Tkinter

---

## 🎯 Learning Outcomes

After completing this project, you will understand:

* How to traverse strings efficiently
* The two-pointer algorithm
* The use of `while-else` in Python
* Basic algorithm design and optimization

---

## 👨‍💻 Author

**Pranay Jadhao**

Electronics & Telecommunication Engineer

Aspiring Software Engineer | Python | Java | SQL | Data Analytics

---

## 📄 License

This project is open-source and available for educational and learning purposes.

<img width="875" height="821" alt="image" src="https://github.com/user-attachments/assets/bc90e904-3b36-4fdb-ab7a-d0c17c3d92fd" />
