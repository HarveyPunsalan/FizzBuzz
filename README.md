# 🎲 FizzBuzz

Classic FizzBuzz implementation in Python - prints numbers 1-100 with "Fizz" for multiples of 3, "Buzz" for multiples of 5, and "FizzBuzz" for multiples of both.

## ✨ Features

- Prints numbers 1 to 100
- "Fizz" for multiples of 3
- "Buzz" for multiples of 5
- "FizzBuzz" for multiples of both 3 and 5
- Written in ≤10 lines of code

## 🛠️ Technologies Used

- Python 3.11
- F-strings for formatted output

## 🎯 Learning Goals

This project focuses on:
- For loops with range()
- Modulo operator (%) for divisibility checks
- Conditional logic and order of operations
- Writing concise, efficient code

## 🚀 How to Run
```bash
python fizzbuzz.py
```

## 📝 Output Sample
```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
...
```

## 🧠 What I Learned

- Why order matters in conditionals (check 15 before checking 3 or 5)
- The power of the modulo operator for pattern detection
- How to write compact, readable code
- F-strings make output formatting cleaner

## 💡 Code Insights

The key insight is checking divisibility by 15 FIRST:
```python
if i % 15 == 0:  # Must check this before % 3 or % 5
    print("FizzBuzz")
```

---

**Built as part of my ML Engineering Roadmap - December 2025**
