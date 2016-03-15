## Practice Problems

##### While loops
*Remember to use while loops in all the solutions!* <br><br>


1. Define a function take takes an integer as an input, and returns a list with all even numbers up to and including that input. Restrictions: Use a while loop

2. Define a function that takes a string as its first parameter and an integer as its second parameter. The function should print the string reversed "x" number of times. In this case, "x" is the second paramter. 

3. Define a function that takes an integer "num" as its first parameter and a list "lst" as its second parameter. The function will return the number of times the integer "num" occurs in the list. 

4. Define a function that takes an integer "num" as it's first parameter and a list "lst" as its second parameter. The function should return true if the integer "num" exists in the list "lst". 

5. Define a function that takes a list "lst1" and another list "lst2" as its first and second parameter respectively. The function should return a list with only the unique elements between the two lists. 

  ```python
  # The following function call should return ["charlie", "tango", 1, 99, 90, 47, "bears"]. Notice all of the elements in the final list are unique.
  
  uniques(["charlie", "tango", 1, 99, 90, 99, "tango"], ["charlie", "tango", 47, "bears"])
  ```

6. Define a function that takes an integer "num" as an input and returns the sum of all uneven numbers till that integer "num". Note: We want the sum of all the numbers that are not even. 

7. Define a function that takes a list as its parameter and returns True/False based on if the list is strictly increasing or decreasing. 

  ```python
  #For example, 
  #[1, 3, 6, 9, 11, 99, 666] should return true
  #[44, 43, r17, 12, 9, 3] should return true
  #[3, 2, 4] should return false
  ```
8. Do the fibonacci sequnce :D . You are more than ready!!!


##### Learning how manipulate strings and lists

1. Write a function that takes a long string as its parameter. The function should return a list containing two strings. One being the first half of the original string and second being the second half of the original string. For this, use python's slicing functionality with the colons. 
  ```python
  #For example, if the string parameter was the following
  #some_str = "Damn Daniel, back at it again with those white vans!"
  #The function should return ["Damn Daniel, back at it ag", "ain with those white vans!"]
  ```
2. Solve the following:
..*lst = ["ch", "i", "o", "c", "100"] Print out the last three elements
..*str = "Failure cannot cope with persistence." Print out "persistence"
..*str = "asdfd;lkjj sdkdkj slkjsd" Print everything between the spaces

```python
# Demo Problem
str = "apple"
print(str[1:]) # "pple"
print(str[:-1]) # "appl"
print(str[2:3]) # "p"
```

##### Dictionairies... are you ready? 

1. Create a function that takes an empty dict as a parameter. Add your name and profession with the values without hard coding it.
  ```python
  # You add key and value pairs to dictionaries like this:
  # guy = {}
  # guy["name"] = "Tom"
  # guy["profession"] = "Golfer"
  # guy = { "name": "Tom",
            "profession": "Golfer }
  ```

2. Create a function that takes in a list as its parameter. It should return a dictionary with keys being the elements and values being the elements' length. 
  ```python
  #Sample
  #If lst = ["charlie", "tango", "Bravo", "Daniel"]
  #It should return { "charlie": 7, "tango": 5, "Bravo": 5, "Daniel": 6 }
  /*{ "charlie": 7, 
      "tango": 5, 
      "Bravo": 5, 
      "Daniel": 6 }*/
  ```
  
3. Create function that takes in a 

