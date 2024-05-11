# FUNCTIONAL PROGRAMMING IN 60 SECONDS

# 💡 What is Functional Programming?

What is  **Functional Programming** ? It's a programming paradigm that uses **Expressions** as the building blocks of the code.

In contrast,  **Imperative Programming**  is a paradigm that uses  **Statements**  to control the flow of the code.

<video controls muted=false
  src="https://gist.github.com/assets/1316994/62fdebe6-7fdf-49fb-a880-e9c80b461e5c
" type="video/mp4">
</video>

Both programming paradigms have expressions and statements, but in Functional Programming, expressions are primarily used to compose other expressions, while in Imperative Programming, statements are primarily used to control the flow of execution.

# 💡 How does Functional Code Drive?

<video controls muted=false
  src="https://gist.github.com/assets/1316994/7b2ef060-1fa6-47d8-912c-772ff317a9aa" type="video/mp4">
</video>

This insight is widely shared, and many people today may know what Functional Programming is.

However, less well-understood is  **how functional code achieves control flow without the use of explicit control statements such as `if` or `for` loops.**

## Battery included! Mathematics

The answer is  **mathematics** .

In Functional Programming,  **code is a composition of expressions, and the evaluation order of these expressions is strictly defined based on mathematical rules.**

Therefore, statements that control the flow of code, in principle, are not required in Functional Programming.

# 💡 What is Expression?

In mathematics and programming, an expression is a combination of  **values**,  **operators**  and  **functions** .

---

### Values

$1 ~ ~ ~ ~ 2 ~ ~ ~ ~ 3$

---

### Operators

![image](https://raw.githubusercontent.com/ken-okabe/web-images4/main/img_1715129229923.png)

$1 + 2+ 3$

---

$double (1 + 2 + 3)$

### Functions

---

<video controls muted=false
  src="https://gist.github.com/assets/1316994/d57a4908-f6ec-43ad-9c2b-0b1ab2ad15d4" type="video/mp4">
</video>

These elements follow a set of  **associativity** and **precedence rules**  to determine the  **order of evaluation** .

$double (1 + 2 + 3)$

$double (3 + 3)$

$double (6)$

$12$

**The expression ultimately produces a single resolved value. In programming, this resolved value can also be considered an expression itself.**

$$
1 + 2 + 3 = 6
$$

$$
double (1 + 2 + 3) = 12
$$

Expressions are essential tools for representing calculations and manipulating data in both mathematics and programming.

Their ability to combine values, operators and functions with defined evaluation rules makes them possible  **building blocks for Functional Programming**.

# 💡 What is Binary Operation?

<video controls muted=false
  src="https://gist.github.com/assets/1316994/f1261018-37d8-4de1-bf17-0d4e87c9e2e6" type="video/mp4">
</video>

In mathematics, a binary operation is a rule that combines two elements, called operands, to produce another element using an operator.

The most common binary operations are addition, subtraction, multiplication, and division, collectively known as the four basic arithmetic operations.

These combine two numbers to produce a new number.

These operations are widely used in everyday life, throughout mathematics, and in various programming languages.

