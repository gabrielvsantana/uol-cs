# Computational Mathematics

---

# Week 1 - Number bases

## Introduction to number bases
Babylonian number system  - 60

Decimal system - 10

Binary system - 2

  - We start at 0 at the right most power

<div align="center">
<!-- White theme only -->
  <img src="https://render.githubusercontent.com/render/math?math={2^3, 2^2, 2^1, 2^0}##gh-light-mode-only" />

<!-- Dark theme only -->
  <img src="https://render.githubusercontent.com/render/math?math=\color{white}{2^3, 2^2, 2^1, 2^0}#gh-dark-mode-only}" />
</div>

Base 16 Hexadecimal
 
This is the generic way to convert to the decimal system:
    4613 to base 2:
    
<div align="center">
  <img src="https://render.githubusercontent.com/render/math?math=4*2^3%2B6*2^2%2B1*2^1%2B3*2^0" />
</div>

<!-- 4 * 2^3 + 6 * 2^2 + 1 *  2^1 + 3 *  2^0 -->

---

- Reading (Write the book here)

Bits - Binary Digits

**Q:** Describe one way of converting decimal numbers to binary numbers
> **A:** Dividing the number by two until you get zero, and keep track of the remainders

**Q:** What number is the binary system based upon?
> **A:** 2

**Q:** How many different digits occur in the binary system?
> **A:** 0 1

Formula for the highest decimal number that can be written useing N Binary digits:

<!-- White theme only -->
<div align="center">
  <img src="https://render.githubusercontent.com/render/math?math={2^N - 1 = 256 - 1}##gh-light-mode-only" />
</div>

<!-- Dark theme only -->
<div align="center">
  <img src="https://render.githubusercontent.com/render/math?math=\color{white}{2^N - 1 = 256 - 1}#gh-dark-mode-only" />
</div>

---

# Week 2 - Number bases (cont.)

How to convert bases when you have a fractional number?

### Decimal to Binary

In binary we convert the integer part separately from the fractional part.

Then with the fractional part, we do the following:
**e.g.** 17.375 (base 10)
```
17 (base 10) = 10001 (base 2)

0.375 x 2 = 0.75 = 0 + 0.75
 0.75 x 2 = 1.5  = 1 + 0.5
  0.5 x 2 = 1.0  = 1 + 0

0.375 (base 10) = 011 (base 2)

= 17.375 (base 10) = 10001.011 (base 2)
```
  - Differently than the integer part, that we get the remainders from bottom to top, when we're calculating the fractional part of a decimal number, we keep track of the integers from top to bottom.

### Operation in binary numbers
If we want to perform operations, we can convert the number to the base we prefer, and do the operation, but if it's more convenient, we can perform those operations in the same base.

### Addition

Addition is the same

### Subtraction

Subtracion is the same, but instead of using the 10 when we're borrowing a the number from the left to the right, we use 2
```
  110
- 101
  ---
= 001
```

### Multiplication

Multiplication is exactly the same
```
      1100     
      1111x
      ----
      1100   
     1100  
    1100   
   1100
  --------
= 10110100
```

   Convert it to decimal to check if it's correct

### Division

TODO

---

# Week 3 - Sequences and series
