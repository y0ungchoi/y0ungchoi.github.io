---
layout: post
title: '[JAVA]01. Variables and Data Types'
author: Eun-young
date: 2019-01-07 12:00
tags: [java]
image: /files/covers/java_logo.jpg
---
# JAVA 

## Lesson 1: Variables and Data Types

### Basic

````java
System.out.println();
````

- System —> System command
- Out —> output
- Println —> print a line

1. Java is case sensitive
2. Quotation marks display the message as is
3. Semi-colon means end of statement

---

### Variables

### Integer

```java
/* Interger --> int */
int passengers; // declare
passengers = 0; // initialize
passengers = passengers +5;
passenger = passengers -3;
passenger = passenger -1 +5;
System.out.println(passengers); // answer is 6
```

- Also track multiple integers


### String 

```java
String driver; //declare
driver = “Hamish”; //initialize
int letters = driver.length; // count length od the letter
System.out.println(letters); // answer is 6
driver = Driver.toUpperCase(); // change Capital letters to lowercase
System.out.println(driver); // answer is hamish
```
```java
String driverFirstName;
driverFirstName = :Hamish”;
String driverlasgnarme;
driverLastName = “Blake”;

String driverFullName = driverFirstName + “ ” + driverLastName;
System.out.println(driverFullName); // answer is Hamish Blake
```

### Variables name Rules
- Lower Camel Case ex)theFirstNames
1. variable names are case sensitive
2. start variable names with a letter
3. cannot have white spaces

---
### Types 


### Numbers
1. Integer int
2. Long 
3. double

```Java
int maxInt = 2147483647;
long muchMore = 2147483647*10000000;
double fraction = 99.275;
```
### Text
1. string
    1. use **double quotension mark** " "
2. character
    1. use **single quotention mark** ' '
    2. accept only one character
```Java
String fullText = “(b) WILL ended 1945”;
char answer = ‘b’;
char three = ‘3’;
char ten = ’10’; //wrong
```

### Decision
1. Boolean 
```
boolean fact = true;
boolean fact = false;
```
### Arthmetic
1. adiition
2. Subtraction
3. Multiplication
4. Division

```java
int x = 2+3; // 5
int y = 4-5; // -1
int days = 7*4; // 28
double div = 5/2; // 2
double accurate = 5/2.0; // 2.5
```
- the order of operation
1. multiplication and division
2. Addition and Subtraction
3. if in doubt, use parntheses ()

> I'm studing a "Java Programming Basics" @[Udacity](https://www.udacity.com/course/java-programming-basics--ud282).

