---
layout: post
title: Writing software for electornics
subtitle: null
tags: null
categories:
  - electronics
  - programming
  - software
author: Akash Gutha
header_img: img/main-bg.jpg
published: true
---

At the first glance writing software for electronics might seem like a daunting task. It may feel esoteric even to the greatest programmers with no exposure to writing software for electronics. So, if you are a beginner or an intermediate level or even an advanced level programmer you need not worry about it. Instead there is a way we can get around this and in this post i'm gonna explain the exact process.

__The programming language of Choice?__

Mostly it is `C Language`. But, some IDEs and compilers also support `CPP`.

So there is no new programming language that you have to learn in order to get started with programming hardware ( unless you don't know C ).

__What are the most important Operation that you need to know?__

1. Bit wise operators: `AND (&)`, `OR (|)`, `NOT (!)` operators.
2. Bit shift operations: `LEFT SHIFT (<<)` and `RIGHT SHIFT (>>)` operators.
3. Conditional Statements: `if`, `else`, `switch` (which i assume most of you already have experience with).
4. Loops: `for` and `while` loops.


__Bit wise operators__

`Bit wise operators` are not equivalent of the `&&` you use in a `if` statement. They are completely different. For example, if you apply a bit wise AND operator `&` between two numbers, the result is computed by passing each bit of the number through an `AND gate` from logic gates and spitting out the number.

so, let's say we have two numbers 5 and 9.
the `Bit wise AND` operation of 5 and 9 will yield 1. confused? let's take a look at the math.


5 in binary is 0000 0101

9 in binary is 0000 1001

now a bit wise and operator passes every two bits into an `AND gate`. The property of and `AND gate` is to output `1` only when both the inputs are `1`.

AND

5		0000 0101

9		0000 1001

1		0000 0001


Only the last bit of the 8 bits from both the numbers are `1`. Hence, the output for the rest of the positions is `0` and the total output is `0000 0001`.


