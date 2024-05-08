# FUNCTIONAL PROGRAMMING IN 60 SECONDS

# 💡 What is Functional Programming?

What is  **Functional Programming** ? It's a programming paradigm that uses **Expressions** as the building blocks of the code.

In contrast,  **Imperative Programming**  is a paradigm that uses  **Statements**  to control the flow of the code.

<video controls>
  <source src="https://gist.github.com/assets/1316994/39a55e67-a4a8-4e88-a6fb-1700609be09a" type="video/mp4">
</video>

https://gist.github.com/assets/1316994/39a55e67-a4a8-4e88-a6fb-1700609be09a

Both programming paradigms have expressions and statements, but in Functional Programming, expressions are primarily used to compose other expressions, while in Imperative Programming, statements are primarily used to control the flow of execution.

# 💡 How does Functional Code Drive?

https://gist.github.com/assets/1316994/18c31c0c-0727-4863-8780-a750eec7c7f8

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

### Functions

$double (1 + 2 + 3)$

---

https://gist.github.com/assets/1316994/ef76c242-9487-48ef-945a-f3fae1301354

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