# 09.-Python---Conditional-Statements-in-Python
Below is a detailed write-up for Conditional Statements (if, elif, else) in Python, 
# Python Course: Conditional Statements (`if`, `elif`, `else`)

Welcome to the **Conditional Statements** chapter of the Python Course repository. This chapter explains how to use `if`, `elif`, and `else` statements in Python, with explanations, examples, and exercises.

---

## **Overview**

| Topic               | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Introduction**    | Explanation of conditional statements and their importance.                |
| **Syntax**          | Syntax and structure of `if`, `elif`, and `else` statements.               |
| **Key Points**      | Essential rules and notes about conditional statements.                    |
| **Examples**        | Practical examples demonstrating different types of conditions.            |
| **Practice**        | Exercises to test your understanding of conditional statements.            |
| **Errors**          | Common mistakes and debugging tips for conditional statements.             |
| **Full Program**    | A complete program combining the learned concepts.                         |
| **How to Run**      | Steps to clone and execute the code in this repository.                    |

---

## **1. Introduction**

Conditional statements control the flow of a program by executing code blocks based on conditions. They are essential for:
- Decision-making.
- Implementing logical operations.
- Controlling the sequence of execution.

---

## **2. Syntax**

| Statement | Description                                      | Example                              |
|-----------|--------------------------------------------------|--------------------------------------|
| `if`      | Executes the block if the condition is `True`.   | `if x > 0: print("Positive")`        |
| `elif`    | Checks another condition if the first is `False`.| `elif x == 0: print("Zero")`         |
| `else`    | Executes if all conditions are `False`.          | `else: print("Negative")`            |

---

## **3. Key Points**

| Rule                              | Explanation                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------|
| **Indentation**                   | Indentation is mandatory to define code blocks.                            |
| **Comparison Operators**          | Use `==`, `!=`, `<`, `>`, `<=`, `>=` to compare values.                    |
| **Logical Operators**             | Combine conditions using `and`, `or`, `not`.                              |
| **Colon (`:`)**                   | Every `if`, `elif`, or `else` statement must end with a colon.             |

---

## **4. Examples**

| Example                  | Code                                                                                   | Output                       |
|--------------------------|-----------------------------------------------------------------------------------------|------------------------------|
| Basic `if`               | `if x > 0: print("Positive")`                                                          | `Positive`                  |
| `if-elif-else`           | `if x > 0: print("Positive") elif x == 0: print("Zero") else: print("Negative")`       | Based on `x` value          |
| Nested Conditions        | `if x > 0: if x % 2 == 0: print("Positive even") else: print("Positive odd")`           | Varies by `x` value         |
| Logical Conditions       | `if x > 0 and x % 2 == 0: print("Positive even")`                                       | Based on conditions          |

---

## **5. Practice Exercises**

| Exercise Number | Description                                       | Hint                                 |
|-----------------|---------------------------------------------------|--------------------------------------|
| 1               | Check if a number is positive, negative, or zero. | Use `if-elif-else`.                  |
| 2               | Implement a grading system based on a score.      | Use `if score >= 90` as the base.    |
| 3               | Check if a year is a leap year.                   | Use `if year % 4 == 0`.              |

---

## **6. Common Errors**

| Error Type           | Cause                                                 | Solution                                   |
|----------------------|-------------------------------------------------------|-------------------------------------------|
| **IndentationError** | Missing or incorrect indentation.                     | Use consistent indentation (4 spaces).    |
| **SyntaxError**      | Missing colon (`:`) after `if`, `elif`, or `else`.    | Ensure all statements end with a colon.   |
| **TypeError**        | Comparing incompatible data types.                    | Validate inputs before comparison.         |

---

## **7. Full Program Example**

```python
# Age group classifier
age = int(input("Enter your age: "))

if age < 0:
    print("Invalid age!")
elif age <= 12:
    print("Child")
elif age <= 19:
    print("Teenager")
elif age <= 59:
    print("Adult")
else:
    print("Senior Citizen")




### **How to Use**

1. Save the above content as `README.md` in your **Conditional Statements** folder.
2. Pair it with example code files like `conditional_statements.py` and the practice exercise files.
3. Commit and push to GitHub with proper formatting.

Let me know if you need help with file structure or Git commands!
