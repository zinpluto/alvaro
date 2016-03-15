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
  * lst = ["ch", "i", "o", "c", "100"] Print out the last three elements
  * str = "Failure cannot cope with persistence." Print out "persistence"
  * str = "asdfd;lkjj sdkdkj slkjsd" Print everything between the spaces

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
  
3. Create function that takes in a dictionary as a parameter. It should return a list containing all the values of only the keys that are palindromes. For example, {"racecar": "ferrari", "bulls": "basketball", "pip": "cool"} should return ["ferrari", "cool"]

4. Define a function that takes a long sentence as its parameter. It should first create a key value pairs of each word to its length. And after that, return the list of the keys' values if the keys' length are greater than 4. 



##### Inputs 

1. Write a function that prompts the user for an input and returns true or false depending on if the the input is a palindrome. (Hint: You can use your pre written functions for the above problems)

2. Write a function that prompts the user for a number and returns true if the number is even and false otherwise. 

3. Write a function that prompts the user for an integer input and returns a list of all even numbers up to that integer. Try to use your prewritten functions with this. 

4. Write a function that prompts the user for a string and returns the reversed string back. Again, try to use the functions you have written for it. 

##### HYBRID

1. Write a function that prompts user for input until the user has provided 5 strings. Remember, you have to keep asking if the user provides anything other than string. Then save all those results in a list. Then, make a dictionary with key value pairs of the elements to their occurence in the list. Remember, you can use your previous functions. 

2. **Date Decoder** Write a function that takes a date as an input in the format such as MAR-8-1987. Actually prompt the user for the input. Don't put a parameter. You can see the month, date, and the year. However, the month is a string. Create a dictionary that has key value pairs that maps months to integers. Now use that dictionary to convert the month section in the input to an integer value of the month. 
  ```python
  # MAR-8-1987 should return 3-8-1987
  # OCT-1-2014 should return 10-1-2014
  ```
3. Make a function that takes a sentence and returns a dictionary with key value pairs of words to how many times it occured in the sentence. Before 

  ```python
  #For example, if the string is "I like apples because apples are so good. I heard oranges are so good too."
  #It should return a dictionary like this:
  { "I": 2,
    "like": 1,
    "apples": 2,
    "because": 1,
    "are": 2,
    "so": 2,
    "good": 2,
    "heard": 1,
    "oranges": 1,
    "too": 1 }
    
    #This one is tricky and hard but it's really cool.
  ```


##Loop Pairs**

Write a function that takes a string as an input. Then make a two dimensional array of the input's length. So essentially, a square grid with rows and columns of the input length.


