# Problem Set For Mid Term

### Two-dimensional lists

1. Create a function that takes in a 2d list as a parameter. Your program should run through the list and print out each element along with its square root and cube root values in the 2d list. Assume that there are no loops nested more than two levels deep. 
  ```python
    def juicyPrinter(2d_lst):
      return #something
      
    Input: [ [2, 3, 4], [33, 22 ,11], [2, 100, 22, 78] ]
    Output: 
    Look! This is my number 2, 4, 8
    Look! This is my number 3, 9, 27
    Look! This is my number 4, 16, 64
    Look! This is my number 33, 1089, 35937
    Look! This is my number 22, 484, 10648
    Look! This is my number 11, 121, 1331
    Look! This is my number 2, 4, 8
    Look! This is my number 100, 10000, 1000000
    Look! This is my number 22, 484, 10648
    Look! This is my number 78, 6084, 474552
    
  ```
2. Create a function that takes in four 2d lists as parameters. Your program should multiply all the corresponding numbers in the rows and return a final matrix of the products. 
  ``` python
    def multiplier(a, b, c, d):
      return #a matrix/2d list
      
    Input:
      a = [ [1, 2, 3], [5, 3, 2], [4, 3, 2] ]
      b = [ [2, 3, 1], [4, 4, 4], [2, 7, 3] ]
      c = [ [2, 3, 4], [2, 3, 4], [2, 1, 1] ]
      d = [ [2, 2, 2], [3, 3, 3], [1, 1, 1] ]
      
    Output: 
      [ [8, 36, 24], [120, 108, 96], [16, 21, 6] ]
  ```

3. Create a function that takes in a 2d list as a parameter. The function should sum up all the rows and return a one dimensional list. 
  ``` python
    def rowSum(lst):
      return # [ #, #, #, # ]
    
    Input:
      lst = [ [1, 3, 4], [9, 1, 2], [33, 1, 0], [44, 1, 2] ]
    
    Output:
      [ 8, 12, 34, 47 ]
  ```
  
4. Write a function that takes in two parameters both being 2d lists. Go through each list and return a list containing total postive numbers, total negative numbers, total even numbers, and total odd numbers. #Remember: negative numbers can be even and odds as well.
  ``` python
    def jackedCounter(lst1, lst2):
      return [#, #, #, #]
      
    Input:
      lst1 = [ [44, 22, -23], [23, 11, 2], [3, 7, -9] ]
      lst2 = [ [66, 33, 22], [999, -2, -3], [16, 92, -33] ]
    
    Output:
      final = [13, 5, 8, 10]
  ```

5. Write a function that takes in a lst as a parameter. Your function should print out the factorial for each number in the list. Once that is done, also return a 2d list which contains first list as the default list and second as the factorial list.
  ``` python
    def factorPrinter(lst):
      print #each factorial for each num
    
    Input: 
      lst = [ 4, 2, 5, 6, 9, 12 ]
    
    Output:
      24
      2
      120
      720
      60480
      479001600
      
      [ [4, 2, 5, 6, 9, 12], [24, 2, 120, 720, 60480, 479001600] ]
  ```
***

### Let's do some strings
1. Create a function that asks the user for two inputs. The first input should take a letter. The second input should be a sentence. If the sentence has the letter in it, your program should replace each of that with 'ERROR' and return it as a string.
  ``` python
    def errorFinder():
      return #some string
      
    Input:
      "a"
      "Ideas are worthless. Action is what matters."
    
    Output:
      "IdeERRORs ERRORre worthless. ERRORction is whERRORt mERRORtters."
  ```
2. Create a function that finds alvaro. That's right. The function should take a string(long sentence) as an input. Find how many times alvaro occurs in the sentence. Try without using .split() method if you can. You thought it was easy. 
  ``` python
    def findingAlvaro():
      return #someNum
      
    Input: 
      "The other day I saw Alvaro watching a video called Alvaro is coding. Turns out Alvaro has a twin. Woah! His name is Alvaro too. Turns out this alvaro has a cousin named alvaro who has a toddler named alvaro."
    
    Output:
      I found 7 alvaros. That's crazy!
  ```
3. Create a function that takes in a list of full names. Print out the initials of each name to the console. BONUS: Make the initials capitalized.
  ```
    def initialsPrinter():
      print #each initials
    Input: 
      lst = ["tenzin phuljung", "alvaro font Junior", "baby alvaro senior", "Daniel Radcliffe", "Robert Downey Junior"]
    
    Output:
      tp
      afj
      bas
      dr
      rdj
  ```
***

### Blood Problems

1. You are a surgeon in a very reputable hospital. 5 people are being transferred to the hospital for surgery. They have had severe blood loss. The hospital is ran out of blood. You need donors. And you think of a brilliant idea since you can code as well. So you set out to find the hospital's employees who have their blood type of o+ positive which can be transferred to anybody without any problem. So, you set out go through the hospital's database of employees which also has their description and blood types. Create a function that finds how many people have blood type of o postive and returns  a list of names.
  ``` python
    def bloodFinder(lst):
      return #[name, name, name]
      
    Input: 
      dict = [
      {name: "Tenzin",
       blood-type: "o+" },
      {name: "Alvaro",
       blood-type: "o+" },
      {name: "Damn Daniel",
       blood-type: "A-" },
      {name: "Batman",
       blood-type: "B+" }
      ]
      
    Output:
      The people who have a blood type of o+ are ["tenzin", "Alvaro"].
  ```
  
### Other
* Create a function that takes in a list and returns True if it's strictly increasing or decreasing. Else, return false.
  ``` python
    Input:
      lst = [1, 2, 3]
    Output: 
      True
    
    Input:
      lst = [2, 4, 3]
    Output:
      False
    
    Input:
      lst = [2, 3, 99, 99]
    Output:
      False
  ```

2. 
