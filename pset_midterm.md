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

### Advanced
1. Create a function that takes two or more arrays and returns an array of the symmetric difference (△ or ⊕) of the provided arrays. Given two sets (for example set A = {1, 2, 3} and set B = {2, 3, 4}), the mathematical term "symmetric difference" of two sets is the set of elements which are in either of the two sets, but not in both (A △ B = C = {1, 4}). For every additional symmetric difference you take (say on a set D = {2, 3}), you should get the set with elements which are in either of the two the sets but not both (C △ D = {1, 4} △ {2, 3} = {1, 2, 3, 4}).
  ``` python
    def sym(args):
      return args

    sym([1, 2, 3], [5, 2, 1, 4])

    sym([1, 2, 3], [5, 2, 1, 4]) should return [3, 4, 5].
    sym([1, 2, 3], [5, 2, 1, 4]) should contain only three elements.
    sym([1, 2, 5], [2, 3, 5], [3, 4, 5]) should return [1, 4, 5]
    sym([1, 2, 5], [2, 3, 5], [3, 4, 5]) should contain only three elements.
    sym([1, 1, 2, 5], [2, 2, 3, 5], [3, 4, 5, 5]) should return [1, 4, 5].
    sym([1, 1, 2, 5], [2, 2, 3, 5], [3, 4, 5, 5]) should contain only three elements.
    sym([3, 3, 3, 2, 5], [2, 1, 5, 7], [3, 4, 6, 6], [1, 2, 3]) should return [2, 3, 4, 6, 7].
  ```
2. Compare and update the inventory stored in a 2D array against a second 2D array of a fresh delivery. Update the current existing inventory item quantities (in arr1). If an item cannot be found, add the new item and quantity into the inventory array. The returned inventory array should be in alphabetical order by item.
  ``` python
    
    def updateInventory(arr1, arr2):
        #All inventory must be accounted for or you're fired!
        return arr1
        # Example inventory lists
        curInv = [
        [21, "Bowling Ball"],
        [2, "Dirty Sock"],
        [1, "Hair Pin"],
        [5, "Microphone"]
        ]
    
        newInv = [
        [2, "Hair Pin"],
        [3, "Half-Eaten Apple"],
        [67, "Bowling Ball"],
        [7, "Toothpaste"]
        ]
    '''
    updateInventory(curInv, newInv)
  
    updateInventory() should return an array.
    updateInventory([[21, "Bowling Ball"], [2, "Dirty Sock"], [1, "Hair Pin"], [5, "Microphone"]], [[2, "Hair Pin"], [3, "Half-Eaten Apple"], [67, "Bowling Ball"], [7, "Toothpaste"]]).length should return an array with a length of 6.
    
    updateInventory([[21, "Bowling Ball"], [2, "Dirty Sock"], [1, "Hair Pin"], [5, "Microphone"]], [[2, "Hair Pin"], [3, "Half-Eaten Apple"], [67, "Bowling Ball"], [7, "Toothpaste"]]) should return [[88, "Bowling Ball"], [2, "Dirty Sock"], [3, "Hair Pin"], [3, "Half-Eaten Apple"], [5, "Microphone"], [7, "Toothpaste"]].
    
    updateInventory([[21, "Bowling Ball"], [2, "Dirty Sock"], [1, "Hair Pin"], [5, "Microphone"]], []) should return [[21, "Bowling Ball"], [2, "Dirty Sock"], [1, "Hair Pin"], [5, "Microphone"]].
    
    updateInventory([], [[2, "Hair Pin"], [3, "Half-Eaten Apple"], [67, "Bowling Ball"], [7, "Toothpaste"]]) should return [[67, "Bowling Ball"], [2, "Hair Pin"], [3, "Half-Eaten Apple"], [7, "Toothpaste"]].
    
    updateInventory([[0, "Bowling Ball"], [0, "Dirty Sock"], [0, "Hair Pin"], [0, "Microphone"]], [[1, "Hair Pin"], [1, "Half-Eaten Apple"], [1, "Bowling Ball"], [1, "Toothpaste"]]) should return [[1, "Bowling Ball"], [0, "Dirty Sock"], [1, "Hair Pin"], [1, "Half-Eaten Apple"], [0, "Microphone"], [1, "Toothpaste"]].
    '''
  ```
3. Return the number of total permutations of the provided string that don't have repeated consecutive letters. Assume that all characters in the provided string are each unique. For example, aab should return 2 because it has 6 total permutations (aab, aab, aba, aba, baa, baa), but only 2 of them (aba and aba) don't have the same letter (in this case a) repeating.
  ``` python
    
    def permAlone(str):
      return str
    
    
    permAlone('aab')
  '''
    permAlone("aab") should return a number.
    permAlone("aab") should return 2.
    permAlone("aaa") should return 0.
    permAlone("aabb") should return 8.
    permAlone("abcdefa") should return 3600.
    permAlone("abfdefa") should return 2640.
    permAlone("zzzzzzzz") should return 0.
    permAlone("a") should return 1.
    permAlone("aaab") should return 0.
    permAlone("aaabb") should return 12.
  '''
  ```
4. Convert a date range consisting of two dates formatted as YYYY-MM-DD into a more readable format. The friendly display should use month names instead of numbers and ordinal dates instead of cardinal (1st instead of 1). Do not display information that is redundant or that can be inferred by the user: if the date range ends in less than a year from when it begins, do not display the ending year. Additionally, if the date range begins in the current year and ends within one year, the year should not be displayed at the beginning of the friendly range. If the range ends in the same month that it begins, do not display the ending year or month.
  ``` python
    # Examples:
    '''
    makeFriendlyDates(["2016-07-01", "2016-07-04"]) should return ["July 1st","4th"]
    
    makeFriendlyDates(["2016-07-01", "2018-07-04"]) should return ["July 1st, 2016", "July 4th, 2018"].
    '''
    
    
    def makeFriendlyDates(lst):
      return arr
  
    makeFriendlyDates(['2016-07-01', '2016-07-04']);

  ```
  
### I\O problems
1. Create a function that takes a filepath as a parameter. Write a function that writes a new text file named vowelCounter.txt which contains the count of vowels for each line. 
  ```python
    Output :
      "the fox jumped over the fence" => 9
      "old is gold" => 3
      "apple is red" => 4
  ```
2. Write a program that takes a file path as a parameter. Then writes a new file called reversed.txt. Your function should reverse each word in the old file and write the new file.
3. Create a function that takes in a number as a parameter and writes a half pyramid to a new file with that num's height.
  ``` python
    ##
    ###
    ####
    #####
    ######
    #######
    ########
    #########
    ##########
  ```
  


