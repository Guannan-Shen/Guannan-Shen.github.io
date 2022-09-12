---
title: "Reading Notes Java Programming"
published: true
tag: Java
---
# Heads-up
This is not a WIKI of Java. However, the notes focus on coding and details in Java.

## Introduction
- Four types of variables in Java: instance, class, local, parameter
- Five types of literals: boolean, integer(0b, decimal, 0 octal, 0x hexa), floating-point literals(scientific, double, f for float), character with single quote and string literals.
- Operators: bitwise(~:complement, <<:left shift, >>:right, &, ^:XOR)
- instanceof Operator: "hello" instanceof String, return boolean
- Ternary Operator:  "variable = Expression ? a : b;"
- System.out.printf() provides string formatting.
- Scanner input = new Scanner(System.in);
- Adding semicolon ; to make an expression a statement.

## Flow Control
```Java
if (condition){
    // statements
}else if {

}else{
    // statements
}
// switch case (faster)
switch (expression){
    case value1:
        // statements
        break;
    
    default:
        // statements
        break; 
}

do{
  // 
}while();

// labeled break for nested loop
// similarly, labeled continue statement
while(){
    second:
    while(){
        break second;
    }
}

```
- Switch case only works with primitive data types, enumerated types, String and Wrapper classes such as Integer, Character
- Java for-each loop for arrays and collections.


## References
[Programiz](https://www.programiz.com/java-programming/)