# Arrays

# References
* [Think Java 8](https://books.trinket.io/thinkjava/chapter8.html)
* [Sedgwick / Wayne 1.4](https://introcs.cs.princeton.edu/java/10elements/)
* [Kjell 46-49](https://chortle.ccsu.edu/Java5/index.html#03)

# Reading
Read chapter 8 from the Think Java.

Arrays in Java are similar to Arrays in Javascript or lists in
Python. They are, however, more primitive.

In Java you have to declare variables with their types so while a Java
array can hold many items they all have to be of the same type. You
also have to specify the number of items an array can hold when you
create it.

The following code would create an array that can store 5 integers:

``` java
int[] a;
a = new int[5];
```

The first one is stored in **a[0]** the fifth in **a[4]**. If you try to
access an array out of bounds say, a[-1] or a[5] in this case, you'll
get an error. You also can't print it all in one shot like you can in
Python or Java. The chapter has the rest of the details.

# Practice

Write a program named Arrays.java and in it solve exercises 1, 4 and 5
from chapter 8 in Think Java.
