# Loops

# References
* [Think Java 7](https://books.trinket.io/thinkjava/chapter7.html)
* [Sedgwick / Wayne 1.3](https://introcs.cs.princeton.edu/java/10elements/)
* [Kjell 15-20](https://chortle.ccsu.edu/Java5/index.html#03)

# Reading
Read Chapter 7 of Think Java.

Java has loops that are very similar to Javascript. The Java while
loop is essentially the same as the Python while loop but the for loop
is a little different. The differences are outlined below:

# While
The Java **while** loop is pretty much the same as the javscript or
Python while

``` java
// Example A
while (boolean)
  statement;

// Example B
while (boolean) {
  statemnts;
}

```

Although you don't need the brackets when you only have a single statement,
it's considered bad form to omit them.

# for

Java's **for** loop is similar to Javscript but not the same as
Python's. The Python for loop is considered a **foreach** loop and we'll
look at Java's equivalent later.

The Java and Javascript for loops are really just a while loop in
disguise.

Let's look at this while loop:

``` java
a = 1; // INITIALIZION (assumes a has been declared already)
while (a < 10){  // TEST
  do stuff;
  a = a + 1; // INCREMENT
}

```

In addition to the stuff you're doing, there are three basic
parts. The INITIALIZATION **a=1** which sets the starting value of the
loop variable, the TEST which is **a<10** which determines when the loop
terminates adn the INCREMENT of **a=a+1** which changes the value of the
test so that we eventually exit.

A for loop is of the form:
```java
for (INITIALIZATION, TEST, INCREMENT) {
  do stuff;
}
```

so the above while loop can be rewritten using a for:
```java
for (a=1; a<10; a++){
  do stuff;
}
```


That's all it is - just a shorthand for writing a while loop.


# do while

Java also supports a do while but it's used less frequently. The
chapter will go over the details.



# Practice

Write a program named **Loops.java** which has solutions to excercises 3, 4, and
5 from chapter 7 of Think Java.
