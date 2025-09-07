# Lab 06

In this lab you will practice working with Comparison & Boolean operators.

Same as the previous labs, you need to set up your workspace (class and main() method).

## Let's get started!

First, let's look at the name of our .java file in the `src/` directory and name your class accordingly and remember to make it `public`. Next, **create your main() method inside your class**.

Now let's begin!

### Comparison and Boolean Operators

Exactly the same as C++. But let's refresh anyways. 

### Comparison Operators

Comparison operators are used to compare two literal values (or variables) and return a Boolean value. This is important in programming, because it helps us to find answers and make decisions.

| Operator | Name |
| ---- | ---- |
| `==` | Equal to |
| `!=` | Not equal |
| `>` | Greater than |
| `<` | Less than |
| `>=` | Greather than or equal to |
| `<=` | Less than or equal to |

### Boolean/Logical Operators

You can also compare Boolean (true or false) values using logical operators. Logical operators are useful when dealing with multiple comparisons.

| Operator | Name |
| ---- | ---- |
| `&&` | AND - Returns true if both statements are true. |
| ll | OR - Returns true if at least one statement is true. |
| `!` | NOT - Reverses the result. |

### Comparing Strings

Strings can be compared in various methods. To compare if two strings are equal to one another we can use the == operator, the equals() method, or the compareTo() method.

| Expression | Result |
| ----- | ----- |
| "Bob" == "bob" | <strong>false</strong> |
| word = "Bob" <br> word.equals("Bob") | <strong>true</strong> |
| word = "Bob" <br> word.compareTo("Arvin") | <strong>1</strong> – a positive value means "Bob" > "Arvin" |
| word = "Bob" <br> word.compareTo("Kobe") | <strong>-9</strong> – a negative value means "Bob" < "Kobe" |
| word = "Bob" <br> word.compareTo("Bob") | <strong>0</strong> – means "Bob" == "Bob" |

For more information on comparison & logical operators in Java visit: https://www.w3schools.com/java/java_operators.asp and https://www.w3schools.com/java/ref_string_compareto.asp 

## Your Assignment

### Conditional Expression Practice

For this lab assignment I want you to practice working with comparison and Boolean/logical operators. 

Create the corresponding conditional expression to match the statement inside each println method. Write your expression inside the parenthesis.

Copy the code snippet below and paste it inside your **main() method** in your java file.

```java
// Problem 1. Is 25.001f equal to 25.001?
System.out.println( /* Write your expression here. */ );

// Problem 2. Is 'C' equal to 67?
System.out.println( /* Write your expression here. */ );

// Problem 3. Is the value inside x greater than -10 and less than 10? 
int x = 0;
System.out.println( /* Write your expression here. */ );

// Problem 4. Is the value inside y either greater than 25 or less than -25? 
int y = -11;
System.out.println( /* Write your expression here. */ );

// Problem 5. Is the value inside word equal to "hello"?
String word = "Hello";
System.out.println( /* Write your expression here. */ );

// Problem 6. Is the value inside animal greater than "Zebra"?
String animal = "Aardvark"; 
System.out.println( /* Write your expression here. */ );

// Problem 7. Is the value inside food less than "Pizza"?
String food = "Hamburger"; 
System.out.println( /* Write your expression here. */ );

// Problem 8. Is the first character of letters equal to 'a'?
String letters = "abcdefg";
System.out.println( /* Write your expression here. */ );

/*
Expected Output:
false
true
true
false
false
false
true
true
*/
```

<br>

**Grading Criteria:**
| Criteria | Points |
|---|---|
| Used the correct operator or method for each conditional expression. (-10 points for each incorrect expression) | 80 |
| File and class are named Comparisons | 10 |
| Class is public | 10 |

[How to Submit Assignments to GitHub](https://joselitoguardado.dev/3326/How_to_Submit_Assignments_to_GitHub.pdf)
