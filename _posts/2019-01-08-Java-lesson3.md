---
layout: post
title: '[JAVA]03. Functions'
author: emily.choi
date: 2019-01-08 13:00
tags: [java]
image: /files/covers/java_logo.jpg
---
# JAVA 

## Lesson 3: Functions

### Function
> What is a Fuction?
> Organize and group code
> Perform a specific task

- Function definition
1. Contains the code a finction executes
2. Calling a function is equivalent to execution the cide in the definition

```java
public void chorus() {
    if(playButton){

    }
    else{

    }
}
```
- public : access modigier
- void : return type
- function name : how ew call our function ex)chorus is function name at that code

- Function Calling

```java
public void chorus() {
    if(x= null)
}
chorus(); //call a function
```

- Parameters and Arguments

```java
public void greeting(String location){ //Argument : location)
    System.out.println("Hello, " + location);
}
greeting(Korea); // print out : Hello Korea 
```

```java
public void weatherInterpreter(int temperature) {
    if (temperature > 30) {
        System.out.println("It's hot outside!");
    } else if (temperature < 5){
        System.out.println("Brr, consider wearing a jacket.");
    } else {
        System.out.println("Not too hot, not too cold.");
    }
}

weatherInterpreter(4); // print out : Brr, consider wearing a jacket.
weatherInterpreter(32); //print out : It's hot outside!

int degreesC = 15;
weatherInterpreter(degreesC); //print out : Not too hot, not too cold.
```

### Return Values

```java
public double makeChange(double itemCost, double dollarsProvided) {
    double change = dollarsProvided - itemCost;
    return change;
}
```
### Random Numbers

```java
//random num between 0 and (almost) 1
double randomNumber = Math.random();
// change range to 0 to (almost) 10
randomNumber = randomNumber * 10;
// casting : cast to integer (ignore decimal part)
// ex. 9.985 becomes 9
int randomInt = (int) randomNumber
```

- Random dice

```java
public int rollDice(int sides){
        // random num between 0 and (almost) 1
        double randomNumber=Math.random();

        // change range to 0 to (almost) 6
        randomNumber=randomNumber*sides;

        // shift range up one
        randomNumber=randomNumber+1;

        // cast to integer (ignore decimal part)
        // ex. 6.998 becomes 6
        int randomInt=(int)randomNumber;

        // return statement
        return randomInt;
        }
```
[Java Documentation - Class](https://docs.oracle.com/javase/8/docs/api/allclasses-noframe.html)

> I'm studing a "Java Programming Basics" @[Udacity](https://www.udacity.com/course/java-programming-basics--ud282).

