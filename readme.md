# JavaScript Style Guide`:`

## Coding conventions are style guidelines for programming. They typically cover`:`
-  Naming and declaration rules for variables and functions.
- Rules for the use of white space,
  indentation
  comments.

## Coding conventions secure quality `:`

- Improves code readability
- Make code maintenance easier

# Variable Names`:`

- we use camelCase for identifier names `(variables and functions)`.
- All names start with a letter.
- Never use var use let instead

## Like this `:`

```
firstName = "Majid";
lastName = "Ashraf";
price = 19.90;
tax = 0.20;
```

# Spaces Around Operators`:`

Always put spaces around operators `( = + - \ * / ) ,` and after commas `:`
arr,math

## Code Indentation `:`

Always use `2 spaces` for indentation of code blocks`:`
fr

# Statement Rules`:`

## i ) General rules for simple statements`:`

Always end a simple statement with a semicolon.

## ii ) General rules for complex (compound) statements`:`

- Put the opening bracket at the end of the first line.
- Use one space before the opening bracket.
- Put the closing bracket on a new line, without leading spaces.
- Do not end a complex statement with a semicolon.
  `Functions, loops conditions`

# Object Rules

## General rules for object definitions `:`

- Place the opening bracket on the same line as the object name.
- Use colon plus one space between each property and its value.
- Use quotes around string values, not around numeric values.
- Do not add a comma after the last property-value pair.
- Place the closing bracket on a new line, without leading spaces.
- Always end an object definition with a semicolon.

## Naming conventions in JavaScript`:`

- let should be camelCase
- const if at the top of a file use upper case snake case. MY_CONST. If not at the top of the file use camelCase
- class should be PascalCasing.
- functions should be camelCase.

# Underscores`:`

Many programmers prefer to use underscores `(date_of_birth)`, especially in SQL databases.

# PascalCase`:`

PascalCase is often preferred by `C` programmers.

# camelCase`:`

- camelCase is used by JavaScript itself, by `jQuery`, and other `JavaScript` libraries.

- When comparing use `===` instead of `==`
This is important due to JavaScript being a dynamic language so using `==` might give you unexpected results due to it allowing the type to be different

```
wrong if (val == 2)
pass if (val === 2)
```


## Use const instead of let`:`

- This stops developers trying to changing things they shouldn't and really helps with readability.

- Use template literals when contacting strings.

- Try and reduce nesting an if within if can get messy and very hard to read, very quickly.

- Use ternary operator instead of if for small statement.

- Use shortcuts for booleans`:`

- Try and avoid unneeded ternary statements`:`

## Use lowercase file names`:`
MyFile.js should be myFile.js
