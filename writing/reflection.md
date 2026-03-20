# CS101 Spring 2026 — Practice Midterm Reflection

Name: Lis Reitmeyer
Date: 3/20/2026

After completing the practice test, please reflect on your experience by
answering the questions below. Replace each `TO-DO` with a thoughtful response
(a few sentences each). Your responses help you consolidate what you learned
and identify areas to review before the real midterm.

---

## 1. Self-Assessment

**Question:** How did you feel about your performance on the practice test?
Which topics felt most comfortable, and which ones felt most difficult?

**Your Answer:**

I think I was very confident through the whole thing. There were a couple questions I was pretty sure of, but not 100% sure, so I double checked some of the questions in JupyterLite, and I did end up getting the majority of those correct. 

---

## 2. Tricky Questions

**Question:** Identify one question you got wrong (or were unsure about).
Explain the concept being tested and describe why the correct answer is right.

**Your Answer:**

Question 11 was tricky for me

"""
### 11. Which of the following is a valid Python **integer** literal?

a) 3.14  
b) "42"  
c) True  
d) 0xFF
"""

"A" has a decimal point, so it is likely a float
"B" is a string because of the quotes
"C" is a boolean
I was unsure of "D", I'm still a little unsure of what it really means, but through process of elimination I think it must be correct. I also looked it up and apparently 0xFF is equal to 255, which would be an integer, but I am unsure how.

---

## 3. Loops and Iteration

**Question:** In your own words, explain the difference between `range(a, b, step)`
with a positive step versus a negative step. Give one original example of each.

**Your Answer:**

Positive steps make the first number count up to the second one, negative steps makes the first number count down to the second one.

range(0, 6, 2) = 0,2,4
range(10, 5, -1) = 10,9,8,7,6

---

## 4. Data Structures

**Question:** Python has lists, tuples, dictionaries, and sets. Describe one key
difference between a list and a tuple, and one key difference between a
dictionary and a set. When would you choose each?

**Your Answer:**

Lists are changable and tuples are not.
Dictionaries have keys and sets do not.

Lists are good for when you need an easily changable group of information. They are good for when you need your information ordred.
Dictionaries are good for when you need information to be easily sorted with keys. They are also sorted and changable.
Tuples are good for when you need to have a few things ordered and indexed, but not changable.
Sets are good for when you want unique values, because they do not allow duplicates, but they are not ordered.

---

## 5. Functions

**Question:** What is a default parameter in a Python function? Write a short
example function that uses a default parameter, and explain what happens when
the caller omits that argument.

**Your Answer:**

def additionfunction(x = 10, y = 5):
    z = x+y
    print(f"The sum of {x} and {y} is {z}")

if the caller puts in arguments for x and y it will add the numbers they chose, if they don't put in arguments it will add 10 and 15 because they are placeholder values.

---

## 6. List Comprehensions

**Question:** List comprehensions can include an optional filter condition.
Rewrite the following traditional loop as a list comprehension:

```python
result = []
for n in range(1, 11):
    if n % 3 == 0:
        result.append(n * 2)
```

**Your Answer:**

result = [x*2 for x in range(1,11) if x % 3 == 0]

---

## 7. Operator Precedence

**Question:** Python evaluates `**` (exponentiation) right-to-left.
What is the value of `2 ** 2 ** 3`? Show your step-by-step reasoning.

**Your Answer:**

Because python evaluates exponentation from right to left 2**2**3 would be the same as 2**(2**3) which would equal 2**8 and 2**8 is equal to 256

---

## 8. Classes 

**Question:** What are classes in Python programming? Explain why they are necessary in programming.

**Your Answer:**

Classes can be used to run many separate functions in one go. They help separate and sort your code more easily. They can really help with organization and making your code easily understandable to a larger audience.

---

(Did you remember to add your name and date at the top of this document?)
