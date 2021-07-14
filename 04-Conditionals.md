# Conditionals

# References
* [Think Java|5](https://books.trinket.io/thinkjava/chapter5.html)
* [Sedgwick / Wayne 1.3.1](https://introcs.cs.princeton.edu/java/10elements/)
* [Kjell 12-14](https://chortle.ccsu.edu/Java5/index.html#03)

# Reading
Read chapter 5 in Think Java.

This section covers conditionals. Java **if** statements look
pretty much the same as those in Javascript

# Conditionals
You have seen conditionals previously in your CS courses. The java version can be seen here:
```java
  // Example A - simple if
  if (boolean)
    statement;

  // Example B - if with compound statement
  if (boolean){
      statement1;
      statement2;
      ...;
      statementn;
  }

  // Example C - if with else
  if (boolean){
      statements;
  } else {
      statements;
  }

  // Example D - if with else chain
  if (boolean1) {
      statements;
  } else if (boolean2) {
      statements;
  } else {
      statements;
  }
```

In Examples B through D, if you don't have multiple statements in each
section you don't need that sections curly braces but it's generally
considered good form to use them. Also, Example D can have any number
of **else if** sections.

A Python **if** is similar but different due to its use of indentation
instead of brackets and the explicit elif as opposed to the Java **else
if**.


# Assignment

There is no assignment for submission for this section.
