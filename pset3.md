
# Practice Problem set 3

* Create a temperature Converter. Your program should ask the user for a temperature input following up with whether to convert to fahrenheit or celcius questions. 

``` python
#sample

Temperature converter

Enter a temperature: 20
Convert to (F)ahrenheit or (C)elsius? F

20 C = 68 F

```

* Loan and payment calculator

**Description**

The interest due on a loan can be calculated according to the simple formula:

I = P × R × T

where I is the interest paid, P is the amount borrowed (principal), R is the interest rate, and T is the length of the loan.

It is common for loans to be amortized which allows the lendor to collect their interest early in the loan period. We will ignore amortization for the purpose of this program. For bonus points, figure out how to do amortization and print an amortization schedule with the payment schedule. There is an excellent explanation of the amortization formula at Interest.com.

Write a program that calculates the interest due on a loan and prints a payment schedule. Make sure you round the output to two decimal places. For bonus points, figure out how to calculate amortization and print an amortization schedule. It will be your responsibility to find an appropriate format for the amortization printout.

Make sure you handle the dollars correctly! Floating point numbers in Python (and other programming languages) are subject to rouding errors when doing floating point arithmetic. For an explanation of this phenomenon, see the floating point arithmetic section of the Python tutorial. One of the most common strategies to solve the problem is to do all money-related calculations in pennies, converting back to dollars when the results are displayed. If you don't handle this issue correctly, your program won't give correct answers in all cases.

**Input**

The program will prompt the user for the amount borrowed, interest rate as a percentage (in annual interest terms), and the term of the loan in years.

**Output**

The program will print the amount borrowed, total interest paid, the amount of the monthly payment, and a payment schedule.

``` python
Sample session

Loan calculator

Amount borrowed: 100
Interest rate: 6
Term (years): 1

Amount borrowed:    $100.00
Total interest paid:  $6.00

           Amount     Remaining
Pymt#       Paid       Balance
-----      -------    ---------
  0        $ 0.00      $106.00
  1        $ 8.84      $ 97.16
  2        $ 8.84      $ 88.32
  3        $ 8.84      $ 79.48
  4        $ 8.84      $ 70.64
  5        $ 8.84      $ 61.80
  6        $ 8.84      $ 52.96
  7        $ 8.84      $ 44.12
  8        $ 8.84      $ 35.28
  9        $ 8.84      $ 26.44
 10        $ 8.84      $ 17.60
 11        $ 8.84      $  8.76
 12        $ 8.76      $  0.00

```

* Literary Analysis

**Description**

  Your English teacher has just asked you to write a paper comparing two of the works from the free, online literature library at Project Gutenberg. Since you are a computer scientist, you decide to put your skills to use. You plan to compare your two favorite works of classic literature in terms of the vocabulary used in each. Since this a bit outside the scope of the assignment as described by your English teacher, you ask for permission before you proceed. Intruiged by your proposal, your English teacher agrees and you are ready to go.

  You plan to write a program that will take a text file as input and return a report listing alphabetically all the words in the file and the number of occurances of each.


* Write a program called caysinLatin.py that takes in a text file as an input file. Your program should read the file and change all the vowels in the word to "ay" and write the content to a new file called caysinLatin.txt. 

* Write a function that takes in x, y as parameters both being numbers. Create a two dimensional array of x rows and y columns with values incrementing. 

* Write a function that takes in 10 parameters all being strings. The program should print out each string with its length to the console each having an incrementing id. 

``` python
# Sample

1. jamba juice 11
2. tenzin 6
3. alvaro font 11
4. hobo 4
5. jacky 5
```

* Write a function that takes in two parameters both being lists. The program should return a new list including both lists, however, each element in both lists have to go one after the other in order. 

``` python
#sample

first list = ["charlie", "tango", "bravo"]
second list = ["dog", "cat", "monkey"]

final list = ["charlie", "dog", "tango", "cat", "bravo", "monkey"]

```

* Write a function that takes in 3 parameters all being lists. Now do the same as above. 

``` python
# sample

first_list = ["a", "z", "b"]
second = [1, 5, 3]
third = [True, False, False]

Final = ["a", 1, True, "z", 5, False, "b", 3, False]
```

* Write a function that takes in a long string, a sentence, as a parameter. The program should check each word and divide it right in the middle and reverse join the words and return the new sentence. 

**Note** If the words are not even, you can round down or up. 

``` python
sentence = "I Like going to the movie"

final = "I keli inggo ot het viemo"
```

* Write a function that takes in a string as a parameter. The program should return new string as shown in the following example.

``` python
input: "tango"

output: "tango ango ngo go o"

```

* Write a function that takes in two parameters both being strings. Convert both into lists and combine them into one big list. Once that is done, join them into a reversed string and then return the string after stripping the first and last letter.

``` python
input: mat lib

output: ilta

```

* Write a function that takes in a string as an input. The program should return a list containing all the strings in as the following example. 
**Bonus** reverse the list at the end.
``` python
input: charlie

output: ["charlie", "harlie", "arlie", "rlie", "lie", "ie", "e"] make sure to reverse this.

```

* Write a function that takes in a string as a parameter. Slice it half way and return the string with hyphens between each letter. 

``` python
input: banana

output: b-a-n #ban is half of banana and there is hyphen between each but not the last one

```












