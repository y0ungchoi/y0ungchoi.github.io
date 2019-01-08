---
layout: post
title: '[JAVA]Lesson03. Functions'
author: emily.choi
date: 2019-01-08 13:00
tags: [java]
image: /files/covers/java_logo.jpg
---
# JAVA 

## Lesson 3: Functions

### Basic
> how to make a good decision?
### if Statement
```java
boolean isRaining = true;
if(isRainging){ //if isRaining true, operate this scope
    System.out.println("Close the window"); 
}
//if not nothing
```

### else Statement
```java
boolean isRaining = true;
if(isRaining){
    System.out.println("Close the window");
}
else{
    System.out.println("It's Sunny outside");
}
```
### else-if Statement

```java
int passcode = 555;
String coffeeType;
if(passcode == 555) {
    coffeeType = "E";
} else if(passcode == 312) {
    coffeeType = "V";
} else if(passcode == 629) {
    coffeeType = "D";
} else{
    coffeeType = "U"
}
System.out.println(coffeeType);
```

### Boolean Expressions

```java
boolean isLightGreen = 3>5;//This means false, so pass the scope

if(isLightGreen){
    System.out.println("Drive!");
}
```

### Logical Operators
1. AND(&&) : true when all expressions are true.
2. OR(||) : true when one expressrion is true
3. NOT(!) : turns a value into its opposite

- the order of operations is
1. Parenthese
2. NOT
3. AND
4. OR


## switch Statement
- switch
- case 
- break : break out of each case
- default : typically comes at the end of a switch statement and its code will execute whenever the other cases aren’t met

```java
int passcode =;
String coffeeType;
switch(passcode){
    case 555: coffeeType = "E"; // :colon, not a semicolon
    break;
    case 312: coffeType = "V";
    break;
    case 629: coffeType = "D";
    break;
    default: coffeType = "U";
    break;
}
System.out.println(coffeType);
```

> I'm studing a "Java Programming Basics" @[Udacity](https://www.udacity.com/course/java-programming-basics--ud282).

