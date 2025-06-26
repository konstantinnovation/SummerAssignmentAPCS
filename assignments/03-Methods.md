
# Methods

You will need to write methods to solve problems that are required for this summer homework. This required problemset is linked at the bottom of each page that shows you a new tool to practice.

Functions sometimes return values to be used by other parts of the program. Here are two examples of functions that return a value (they become the value returned):

```java
int y = 10;
double x = sqrt(y); //x becomes the result of the function sqrt
```
In this case sqrt(y) would return the value of the square root of 10.

```java
double theta = 3.1415926535;
System.out.println( sin(theta) );//print the result of the sin function.
```
In this case the print function needs a value to print, and the sin function returns the sine of pi.

Not all functions return values however. 


# Void methods

Just to see how methods (functions) are written in java, we will start with the ones that do not return a value. These are called **void methods**.

Take our Hello.java:

```java
  public class Hello {
      public static void main(String[] args){
          System.out.println("Hello world!");
      }
  }
```

The file contains a class (don't worry about class for now) named Hello. 
The  **main** that we wrote inside the Hello class is a **method** (function). 
For those of you with Python or Javascript backgrounds, for the time being you 
can think of a method as a function declared inside of a class.

Let's look at the anatomy of a method
```java
public static RETURNTYPE NAME(ARGUMENTS){
 BODY
}
```

For now we'll treat **public** and **static** as boilerplate. This is 
code that must be there, but you don't know why right now. We'll
explain them when we get to Objects. 

The name of the method can be any valid identifier. 

The method name **main** though, has a special meaning. It's what the Java Virtual Machine (JVM) runs automatically when you run your program. 

The return type for main is **void**. That means it doesn't return any value. 

For this section we will limit ourselves to **void** methods. 

The println method is a void method because it doesn't return a value, it instead outputs something to the terminal.
Here's a program  with two methods. The first is void and prints out **Hello world!**, the second
is our required **main** method.


```java
  public class Hello {

      public static void printHello(){
          System.out.println("Hello world!");
      }

      public static void main(String[] args){
          String s;
          printHello();
      }

  }
```


Java does have a **return** statement like other languages but in the
case of a void method, if you omit it, the function will just return
to the caller after the last statement. If a void method has and
encounters a **return** statement, control is immediately returned to
the caller.

The last piece of the method are the ARGUMENTS. The ARGUMENTS are a
list of arguments sent to the method. This acts in the same way as
arguments to a Python or Javascript function except you have to
specify types. 

For example, if you had a Python function f that accepted
first an integer into parameter **a** and a then  string into parameter
**b** and returned a string you would write


```python
def add(a,b):
  # do stuff
  print(a+b)
```


In Java the corresponding method would be:
```java
public static void add(int a, String b){
  // dostuff
  System.out.println(a+b);
}
```


# Value Methods

We discussed all the components except the **RETURN TYPE**. In addition
to having a **RETURN TYPE** of **void** we can specify any other data 
type (int, String, double, etc.) as the **RETURN TYPE**. 

A simple example would be to change the add method above to return the sum, instead of printing it:
```java
public static int add(int a, String b){
  return a+b;
}
```

In the example below, the method **returnHello**
does not output anything. Instead it returns a String value. Note how
this differs from **printHello** which outputs "Hello World!" but
returns nothing.


```java
  public class Hello {

      public static void printHello(){
          System.out.println("Hello world!");
      }

      public static String returnHello(){
          return "Hello world!";
      }

      public static void main(String[] args){
          String s;
          
          //This line will print something
          printHello();
          
          //This line assigns the returned String to s.
          s = returnHello();
          //This line prints the String stored in s.
          System.out.println(s);
          
          //Note: These two lines are equivalent to : System.out.println(returnHello());
          
      }

  }
```


Finally, a method can call another method:

```java
  import java.io.**;
  import java.util.**;

  public class Hello {

      public static void printHello(String name){
          String result;
          result = returnHello(name);
          System.out.println(result);
      }

      public static String returnHello(String name){
          String result;
          return "Hello " + name + "!";
      }

      public static void main(String[] args){
          String s;
          printHello("Thomas");
          s = returnHello("Jane");
          System.out.println(s);
      }

  }
```


# Required Work: 
Now you can start to solve codingbat questions that your teacher will verify you completed.

* Go to [codingbat.com](codingbat.com/home/konstans@stuy.edu/summerapcs)
* Please create an account using your stuy.edu email address. Problems you complete WHILE LOGGED IN will be saved to your account. 
* If you forget to log in, you have to do them again. 
* Important: Only submit work that you write. 
* Do not do all of them at once, please do the reading prior to each section even if you think you know some java. 
* Now complete the section **Functions with no loops/conditionals (average3, force, roundToPlace, sumOfSines)**.

**Summer Problem Set**: [codingbat.com/home/konstans@stuy.edu/summerapcs](https://codingbat.com/home/konstans@stuy.edu/summerapcs)

