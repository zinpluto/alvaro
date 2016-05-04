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
2. 
