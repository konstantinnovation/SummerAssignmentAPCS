

# First Program

**PRO TIP**: Do not copy and paste code from either online sources or earlier assignments. Type it in. This will help you remember the Java constructs and will make later sections of the program easier.

Create a file named **HelloWorld.java** and save it in your APCS folder. Note that the **H** is upper case. In that file, write and this program:

```java
public class Hello{
      public static void main(String[] args){
          System.out.println("Hello world!");
      }
}
```


# Compile and run
Open your APCS folder with a terminal (remember the BeforeYouCode section), you will need to use it here.

Now, from the terminal run the **ls** command (Linux, Mac, GitBash, Powershell) or **dir**
command (windows command prompt) after typing the command press enter. Note that your directory should have one file
named **Hello.java**. If you do not see the file, then you didn't open the same folder the file is located in.

To compile **Hello.java** into Java Byte Code that can be run by the Java
Virtual Machine, type **javac Hello.java** and press enter. If the prompt comes back
with no errors, everything worked. If you see any errors, read them
carefully and try to fix your program. Repeat until your program
compiles.

Look at the files in the directory again (ls, dir) and you'll see an
additional file named **Hello.class** - this is the compiled Java Byte
Code that can be run. Now run your program by typing **java Hello** and pressing enter.

Here is a sample of what you would see if you did everything correctly:
```
C:\Users\K\Documents\APCS> ls
    Directory: C:\Users\K\Documents\APCS
Mode                 LastWriteTime         Length Name
-a----         7/14/2021   1:58 PM            125 Hello.java

C:\Users\K\Documents\APCS> javac Hello.java

C:\Users\K\Documents\APCS> java Hello
Hello world!

C:\Users\K\Documents\APCS> ls
    Directory: C:\Users\K\Documents\APCS
Mode                 LastWriteTime         Length Name
-a----         7/14/2021   2:02 PM            416 Hello.class
-a----         7/14/2021   1:58 PM            125 Hello.java

PS C:\Users\konstans\Desktop\APCS>
```

# What do errors look like?

Most of the time you will not type the commands correctly and it cannot compile. See what this looks like by putting an error in your program - remove a quote or a bracket and recompile using **javac Hello.java** - read the error. Fix it and try to
generate another error. Finally fix and text the program again so that
it works.

# References for this assignment:
Reference | Chapter(s)   
* [Sedgwick / Wayne | 1.1.1, 1.1.2](https://introcs.cs.princeton.edu/java/10elements/)
* [Kjell  | 1 through 7](https://chortle.ccsu.edu/Java5/index.html#03)

 Please review and consider the questions at the end of the chapters.

Congratulations again, you've successfully written your first program!
