---
layout: post
title: '[JAVA]04. Loops'
author: emily.choi
date: 2019-01-10 13:00
tags: [java]
image: /files/covers/java_logo.jpg
---
# JAVA 

## Lesson 4: Loops

### While Loops

```java
public void alarm() {
    boolen on = checkAlarm();
    if(on){
        beep();
        on=checkAlarm();
    }
    if(on){
        beep();
        on=checkAlarm();
    }
    if(on){
        beep();
        on=checkAlarm();
    }
    ---//until someone turn off the alarm    
}
```

```java
/*Using While Loop*/
public void alarm(){
    boolean on = checkAlarm();
    while(on){
        beep();
        on = checkalarm();
    }
}
```
```java
String googol = '1';
int len = googol.length();
while(len <101){
    googol = googol + "0";
    len= googol.length();
}
```
```java
public void raiseAlarm(int numOfWarnings) {
    int i = 1;
    while(i <= numOfWarnings) {
        System.out.println("warning");
        i++;
    }
    
}
```

### For Loops

```java
public void raiseAlarm(int numOfWarnings) {
    for(int i = 1; i<= numOfWarnings; i++){
        System.out.println("Warning #" + i);
    }
}
```

```java
/*
Adds the numbers 15+116+ .. + 20
@return the total sum
*/
public int addNmbers() {
    int sum = 0;
    for(int i = 15; i <= 20; i++){
        sum = sum + i;
    }
    return sum;
}
```

```java
/* Counting Down */
for(int i = 3; i >= 1; i--){
    System.out.println(i);
}
```

```java
i = i+1 == i++
i = i + 5 == i += 5 
```

```java
/*Using break;*/
public int martingale() {
 int money = 1000;
 int target = 1200;
 int bet = 10;
 while (money > bet) {
  boolean win = play();
  if (win) {
   money += bet;
   bet = 10;
  } else {
   money -= bet;
   bet *= 2;
  }
  // Add the break here:
  if(money >= target)
     break;
 }
 return money;
}
```

### Arrays
- cell : value
- index 

```java
int [] numbers = {12,1,777,3,4,0,0,121,1,-4,0,-100,2};
System.out.println(number[0]); // answer is 12
System.out.println()
```  

```java
String [] nesOutlet = {"KBS", "MBC", "SBS", "TVN", "JTBC", "BBC", "FOX", "CNN", "ABC"};
double lucky = Math.random();
//Multiply by 10 to get a fractional number between 0 - 10
luckey *= 10;
//cast to integer to get an integer number between 0 - 9
int luckyIndex = int lucky;
System.out.print(newOutlet[luckyIndex]);
```

### Arrays and Loops
```java
prublic double calculateAverage(double [] temperatures) {
    int size = temperatures.length;
    double total = 0;
for(int i=0; i<size; i++){
    total += temperatures[i];
}
double average = total.size;
return average;
}
```

```java
/* Array Search - find longest name*/
public String findLongestName(String [] names){
    int size = names.length;
    String longestNames = names[0];
    for(int i=0; i<size; i++){
        if(names[i].length() > longestNames.length()){
            longestNames = names[i];
        }
    }

    return longestNames;
}
```

### 2D arrays
```java
public static double englishAverage(int [][] grades, int student) {
    int subjects = grades.length;
    int total = 0;
    for(int i=0;i<subjects;i++) {
        total = grade[i][student];
    }
    double average = total/(double)subjects;
    return average;
}
```

> I'm studing a "Java Programming Basics" @[Udacity](https://www.udacity.com/course/java-programming-basics--ud282).

