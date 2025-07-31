# Implementation of Decision Making Statements

## Objective

To write a C++ program that performs the following:

1. Checks whether a number is even or odd
2. Checks whether a character is a vowel or consonant
3. Determines the largest number among three user-entered integers

---

## Apparatus

- Visual Studio Code (VS Code)
- Any Online C++ Compiler (e.g., Replit, OnlineGDB, Programiz)

---

## Theory

### 1. Even or Odd Check
- Uses the modulus operator `%` to check divisibility by 2.
- If a number is divisible by 2, it is even; otherwise, it is odd.

### 2. Vowel or Consonant Check
- Uses `if` conditions to compare the character with both uppercase and lowercase vowels.
- If the character matches any vowel, it is a vowel; otherwise, it is a consonant.

### 3. Finding the Largest of Three Numbers
- Uses nested `if` and `else if` conditions to compare three numbers (x, y, z).
- Prints the number which is greater than the other two.

---

## Key Concepts Used

- Conditional Statements (`if`, `else`, `else if`)
- Relational Operators (`>`, `%`, `==`)
- Logical Operators (`||`)
- Standard Input/Output using `cin` and `cout`

---

## Algorithms

### 1. Even or Odd
1. Input a number.
2. Check `number % 2 == 0`.
3. If true, print "Even"; else, print "Odd".

### 2. Vowel or Consonant
1. Input a character.
2. Compare it with `a, e, i, o, u` and their uppercase versions.
3. If matched, print "Vowel"; else, print "Consonant".

### 3. Largest of Three Numbers
1. Input three numbers.
2. Use conditional statements to compare:
   - If `a > b` and `a > c`, `a` is largest.
   - Else if `b > c`, `b` is largest.
   - Else, `c` is largest.

---

## Learning Outcomes

- Applied decision-making statements for numerical and character data
- Understood how to check conditions using `if-else`
- Gained hands-on experience in using relational and logical operators
- Developed logic to compare, check, and categorize inputs

