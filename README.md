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

In mathematics, a  **binary operation**  is a  **rule that combines two elements** , called  **operands** , to produce  **another element using an operator.**

The most common binary operations are  **addition** ,  **subtraction** ,  **multiplication** , and  **division** , collectively known as the  **four basic arithmetic operations** .

$1 + 2$

$5 - 3$

$2 \times 3$

$8 \div 4$

Here  $+$   $-$   $\times$   $\div$ is called  **binary [operator](https://learn.microsoft.com/en-us/dotnet/fsharp/language-reference/symbol-and-operator-reference/)** .

![image](https://raw.githubusercontent.com/ken-okabe/web-images4/main/img_1712224131411.png)

These combine two numbers to produce a new number.

These operations are widely used in everyday life, throughout mathematics, and in various programming languages.

# 💡 What is Operator Associativity?

<video controls muted=false
  src="https://gist.github.com/assets/1316994/4d5fecc6-df1e-4a64-bfc2-883446383b6d" type="video/mp4">
</video>

Let's consider an expression:

$$
1 + 2
$$

This is a  [binary operation](https://en.wikipedia.org/wiki/Binary_operation) .

![image](https://raw.githubusercontent.com/ken-okabe/web-images4/main/img_1712224131411.png)

Let's consider another expression:

$$
1 + 2 + 3
$$

This is a combination of two binary operations.

$$
(1 + 2) + 3
$$

![image](https://raw.githubusercontent.com/ken-okabe/web-images4/main/img_1713912989196.png)

In mathematics, the addition operator **(+) is left-associative** , meaning we perform calculations  **from left to right**  when evaluating expressions containing  **multiple (+)  signs** .

$$
\begin{align*}
&\quad ~ ~ ~ 1 + 2 + 3  \\
&= (1 + 2) + 3 \\
&= 3 + 3  \\
&= 6 
\end{align*}
$$

 **Parentheses ( )**  can override this order.
This results in the same answer in both cases, but it highlights the importance of  **associativity**  and the use of  **parentheses to control the order of evaluation** .

<img width="100%" src="https://raw.githubusercontent.com/ken-okabe/web-images/main/note.svg">

In contrast, a  **right-associative operator**  is an operator that is evaluated from right to left. For example, the exponentiation operator ( $\textasciicircum$ ) is  **right-associative** in many languages, so the following expression is evaluated as follows:

$$
2 \textasciicircum 3 \textasciicircum 2 = 2 \textasciicircum (3 \textasciicircum 2) = 128
$$

It is important to understand the associativity of operators when writing expressions, as it can affect the order of operations and the final result.

It is important to understand the associativity of operators when writing expressions, as it can affect the order of operations and the final result.

> In [programming language theory](https://en.wikipedia.org/wiki/Programming_language_theory "Programming language theory"), the **associativity** of an [operator](https://en.wikipedia.org/wiki/Operator_(programming) "Operator (programming)") is a property that determines how operators of the same [precedence](https://en.wikipedia.org/wiki/Order_of_operations "Order of operations") are grouped in the absence of [parentheses](https://en.wikipedia.org/wiki/Bracket_(mathematics) "Bracket (mathematics)"). If an [operand](https://en.wikipedia.org/wiki/Operand "Operand") is both preceded and followed by operators (for example, `^ 3 ^`), and those operators have equal precedence, then the operand may be used as input to two different operations (i.e. the two operations indicated by the two operators). The choice of which operations to apply the operand to, is determined by the **associativity** of the operators. Operators may be **associative** (meaning the operations can be grouped arbitrarily), **left-associative** (meaning the operations are grouped from the left), **right-associative** (meaning the operations are grouped from the right) or **non-associative** (meaning operations cannot be chained, often because the output type is incompatible with the input types). The associativity and precedence of an operator is a part of the definition of the programming language; different programming languages may have different associativity and precedence for the same type of operator.

<img width="100%" src="https://raw.githubusercontent.com/ken-okabe/web-images/main/notefooter.svg">





