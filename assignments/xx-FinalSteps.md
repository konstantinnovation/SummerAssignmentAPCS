# Enough codingbat

Codingbat does not teach you to write a complete program, instead it helps you automatically test your functions with premade test cases.

# Write a complete java program

Your goal is to write a complete java program with a main that will test a couple of other functions.


* create a class in a file named `Tester.java` and include the main method.
* create two functions: `isPrime(x)` and `nthPrime(n)` The function headers are included below.
* In your main: create two arrays, one with input values for `nthPrime()`, and the other with the expected values. e.g. n: `[0,1,2]` and primes: `[2,3,5]`
* DO NOT use your function to generate the expected values, you need to know them ahead of time. Try googling prime values for ones that are larger (100th, 200th, etc) 
* Run your function on the input values, and see if the match the expected values, print either `"pass"` if the values match, or when they don't you should print: `"fail expected x, but value returned was y"` (replace x and y accordingly) 

```
//return true if and only if x is prime,false otherwise.
public static boolean isPrime(int x){
  //just check divisibility for all values from `2` through `x - 1` inclusive.
  //(This is not a good algorithm, just use it)
}

//return the nth prime,
//e.g. nthPrime(0) returns 2, nthPrime(1) returns 3, etc.
public static int nthPrime(int n){
  //Loop through values and check if they are prime until you find n of them
  //use your isPrime function.
} 
```
# Submission

Please have a digital copy accessible (in your email or flash drive) and have it handy when your teacher asks for it.
