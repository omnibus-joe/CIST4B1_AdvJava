# CIST4B1_AdvJava
A repository to document my Java learning journey

## About Me
I am a student currently enrolled at WVC and taking the Data Structures using Advanced Java (CIST 004B1) course.

## Goals for This Course
1. Learn advanced Java topics
2. Apply common data structures purposefully and efficiently
3. Be able to measure and evaluate the performance of algorithms

## In-Class Java Coding Warm Up
```java
public class Class1 {
  private int a = 10;

  public void print() {
    System.out.println("" + a);
  }
}

public class Class2 extends Class1 {
  public void print() {
    super.print();
  }
}

public class Week1 {
  publlc static void main(String[] args) {
    Class2 c2 = new Class2();
    c2.print();
  }
}
```
