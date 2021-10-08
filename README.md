Java file = All of our code
.md file = Text, definitions, etc;

## Intro to Java

A Java program can be characterized as an **object** represented in a **class**.
Currently our program has a *Main* object. Inside this object we have the *Main* class.

## Output
In Java, to output an item to the console, we use `System.out.print()` and `System.out.println()`

`System.out.println()` prints the statement and moves to the next line.
`System.out.print()` prints the statement but does not move to the next line.

## Comments

A comment is used as user annotation with the purpose of being human readable.

**Line Comments** follow double forward slashes. `//`

**Block Comments** are contained within `/* Comments */`

## Identifiers

In Java use the term **identifier** to describe a variable, parameter, constant, user-defined method, or user-defined class.

- Cannot begin with digit
- Can only contain letters, digits, and underscores
- Case sensitive `age != Age` (age is not equal to Age)

*Note:*
- class name starts with a capital letter
- reserved words are entirely lowercase and may not be used as identifiers (Reserved words will show up in blue.)

## Types
**Primitive**, or **built-in** types in Java are
- `int` An integer
- `boolean` True or False
- `double` Floating-point number (2.73)
- `char` Single character

*Note: * Integers have a fixed amount of memory, so there is a limit to how many single digits you can store (2^31-1)

## Variables
Variables are a type of identifier that stores a value of a specific type

We can create variables using **declaration**
- `int age;`
- `boolean found;`
- `double x, y;`
- `char letter;`

We can also initialize a variable its **declaration**
- `int count = 1;`
- `double p = 3.14;`
- `char c = '8';`

## Chars
[ASCII CHART](https://docs.google.com/document/d/1oubLTqAHmdkadtjbR8xxREG7auvuUqiQ/edit)

Each character is associated with an ASCII value.


## Type cast 

One type can be cast to another compatible type if appropriate

`char letter = 'c';`
```

int total, n;
double average;
average = (double)total/n //total cast to double to ensure real division is used
```

*Note: * Casting a floating point number to an integer simply truncates the number (rounds down)