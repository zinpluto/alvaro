#Java Problem Set 1

1. The parameter weekday is true if it is a weekday, and the parameter vacation is true if we are on vacation. We sleep in if it is not a weekday or we're on vacation. Return true if we sleep in.
  ```
  sleepIn(false, false) → true
  sleepIn(true, false) → false
  sleepIn(false, true) → true
  
  public boolean sleepIn(boolean weekday, boolean vacation) {
    
  }
  ```

2. Given an int n, return the absolute difference between n and 21, except return double the absolute difference if n is over 21.
  ```
  diff21(19) → 2
  diff21(10) → 11
  diff21(21) → 0
  
  public int diff21(int n) {
    
  }
  ```

3. Given an int n, return true if it is within 10 of 100 or 200. Note: Math.abs(num) computes the absolute value of a number.
  ```
  nearHundred(93) → true
  nearHundred(90) → true
  nearHundred(89) → false
  
  public boolean nearHundred(int n) {
    
  }
  ```

4. Given a non-empty string and an int n, return a new string where the char at index n has been removed. The value of n will be a valid index of a char in the original string (i.e. n will be in the range 0..str.length()-1 inclusive).
  ```
  missingChar("kitten", 1) → "ktten"
  missingChar("kitten", 0) → "itten"
  missingChar("kitten", 4) → "kittn"
  
  public String missingChar(String str, int n) {
  
  }
  ```
  
5. Given a string, take the last char and return a new string with the last char added at the front and back, so "cat" yields "tcatt". The original string will be length 1 or more.
  ```
  backAround("cat") → "tcatt"
  backAround("Hello") → "oHelloo"
  backAround("a") → "aaa"
  
  public String backAround(String str) {
    
  }
  ```

6. Given a string, return true if the string starts with "hi" and false otherwise.
  ```
  startHi("hi there") → true
  startHi("hi") → true
  startHi("hello hi") → false
  
  public boolean startHi(String str) {
    
  }
  ```

7. We'll say that a number is "teen" if it is in the range 13..19 inclusive. Given 3 int values, return true if 1 or more of them are teen.
  ```
  hasTeen(13, 20, 10) → true
  hasTeen(20, 19, 10) → true
  hasTeen(20, 10, 13) → true
  
  public boolean hasTeen(int a, int b, int c) {
    
  }
  ```
8. Return true if the given string begins with "mix", except the 'm' can be anything, so "pix", "9ix" .. all count.
  ```
  mixStart("mix snacks") → true
  mixStart("pix snacks") → true
  mixStart("piz snacks") → false
  
  public boolean mixStart(String str) {
    
  }
  ```
9. Given 2 int values, return whichever value is nearest to the value 10, or return 0 in the event of a tie. Note that Math.abs(n) returns the absolute value of a number.
  ```
  close10(8, 13) → 8
  close10(13, 8) → 8
  close10(13, 7) → 0
  
  public int close10(int a, int b) {
    
  }
  ```
10. Return true if the given string contains between 1 and 3 'e' chars.
  ```
  stringE("Hello") → true
  stringE("Heelle") → true
  stringE("Heelele") → false
  
  public boolean stringE(String str) {
  
  }
  ```
  
11. Given a non-empty string and an int N, return the string made starting with char 0, and then every Nth char of the string. So if N is 3, use char 0, 3, 6, ... and so on. N is 1 or more.
  ```
  everyNth("Miracle", 2) → "Mrce"
  everyNth("abcdefg", 2) → "aceg"
  everyNth("abcdefg", 3) → "adg"
  
  public String everyNth(String str, int n) {
    
  }
  ```
  
12. We have two monkeys, a and b, and the parameters aSmile and bSmile indicate if each is smiling. We are in trouble if they are both smiling or if neither of them is smiling. Return true if we are in trouble.
  ```
  monkeyTrouble(true, true) → true
  monkeyTrouble(false, false) → true
  monkeyTrouble(true, false) → false
  
  public boolean monkeyTrouble(boolean aSmile, boolean bSmile) {
    
  }
  ```
  
13. We have a loud talking parrot. The "hour" parameter is the current hour time in the range 0..23. We are in trouble if the parrot is talking and the hour is before 7 or after 20. Return true if we are in trouble.
  ```
  parrotTrouble(true, 6) → true
  parrotTrouble(true, 7) → false
  parrotTrouble(false, 6) → false
  
  public boolean parrotTrouble(boolean talking, int hour) {
    
  }
  ```
  
14. Given 2 int values, return true if one is negative and one is positive. Except if the parameter "negative" is true, then return true only if both are negative.
  ```
  posNeg(1, -1, false) → true
  posNeg(-1, 1, false) → true
  posNeg(-4, -5, true) → true
  
  public boolean posNeg(int a, int b, boolean negative) {
    
  }
  ```
  
15. Given a string, return a new string where the first and last chars have been exchanged.
  ```
  frontBack("code") → "eodc"
  frontBack("a") → "a"
  frontBack("ab") → "ba"
  
  public String frontBack(String str) {
    
  }
  ```
  
##IMPORTANT OOP CONCEPTS

* **Class**: a blueprint for how a data structure should function
* **Constructor**: instructs the class to set up the initial state of an object
* **Object**: instance of a class that stores the state of a class
* **Method**: set of instructions that can be called on an object
* **Parameter**: values that can be specified when creating an object or calling a method
* **Return value**: specifies the data type that a method will return after it runs
* **Inheritance**: allows one class to use functionality defined in another class
