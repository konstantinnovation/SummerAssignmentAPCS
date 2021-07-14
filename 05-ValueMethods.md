

# References
* [Think Java | 6](https://books.trinket.io/thinkjava/chapter6.html)
* [Sedgwick / Wayne 2.1,2.2](https://introcs.cs.princeton.edu/java/10elements/)

# Value Methods
Earlier we looked at the anatomy of a method:

``` java
public static RETURNTYPE NAME(ARGUMENTS){
 BODY
}
```

We discussed all the components except the **RETURNTYPE**. In addition
to having a **RETURNTYPE** of **void** we can specify any other data type
as the **RETURNTYPE**. In the example below, the method **returnHello**
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
          printHello();
          s = returnHello();
          System.out.println(s);
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


# Practice

Write a program named Methods.java with methods that solve exercises 2, 3, and
8 from Chapter 6 in Think Java. [Think Java | 6](https://books.trinket.io/thinkjava/chapter6.html)
