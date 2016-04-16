
## Practice Problems 2 

1. Write a function that takes in a list as a parameter. That "list" will contain two numbers. Return the sum of the two numbers and all the numbers between the two numbers. 

``` python
def sumAll(arr):
  return # something;

sumAll([1, 4]);
```

2. Perform a search and replace on the sentence using the arguments provided and return the new sentence. First argument is the sentence to perform the search and replace on. Second argument is the word that you will be replacing (before). Third argument is the word that you replace with (after).

``` python
def myReplace(str, before, after):
  return #something

myReplace("A quick brown fox jumped over the lazy dog", "jumped", "leaped")
```

3. Translate the provided string to pig latin. Pig Latin takes the first consonant (or consonant cluster) of an English word, moves it to the end of the word and suffixes an "ay". If a word begins with a vowel you just add "way" to the end.

``` python
function translatePigLatin(str):
  return str

translatePigLatin("consonant")
```

4. Write a function that takes two or more arrays and returns a new array of unique values in the order of the original provided arrays. In other words, all values present from all arrays should be included in their original order, but with no duplicates in the final array. The unique numbers should be sorted by their original order, but the final array should not be sorted in numerical order.

``` python
def uniteUnique(arr1, arr2, arr3):
  return arr1


uniteUnique([1, 3, 2], [5, 2, 1, 4], [2, 1])
```

5. Drop the elements of an array (first argument), starting from the front, until the predicate (second argument) returns true. The second argument, func, is a function you'll use to test the first elements of the array to decide if you should drop it or not. Return the rest of the array, otherwise return an empty array.

``` python
def dropElements(arr, func):
  // Drop them elements.
  return arr

dropElements([1, 2, 3], evenNum(n))
```

6. Sum all the prime numbers up to and including the provided number. A prime number is defined as having only two divisors, 1 and itself. For example, 2 is a prime number because it's only divisible by 1 and 2. 1 isn't a prime number, because it's only divisible by itself. The provided number may not be a prime.

``` python
def sumPrimes(num) {
  return # num;
}

sumPrimes(10);
```

7. Flatten a nested array. You must account for varying levels of nesting.

``` python
def steamrollArray(arr):
  # I'm a steamroller, baby
  return arr

steamrollArray([1, [2], [3, [[4]]]])
```

8. The DNA strand is missing the pairing element. Take each character, get its pair, and return the results as a 2d array. Base pairs are a pair of AT and CG. Match the missing element to the provided character. Return the provided character as the first element in each array. For example, for the input GCG, return [["G", "C"], ["C","G"],["G", "C"]] The character and its pair are paired up in an array, and all the arrays are grouped into one encapsulating array.

``` python
def pairElement(str):
  return str

pairElement("GCG")
```

9. Return the sum of all odd Fibonacci numbers up to and including the passed number if it is a Fibonacci number. The first few numbers of the Fibonacci sequence are 1, 1, 2, 3, 5 and 8, and each subsequent number is the sum of the previous two numbers. As an example, passing 4 to the function should return 5 because all the odd Fibonacci numbers under 4 are 1, 1, and 3.

``` python
def sumFibs(num) 
  return num

sumFibs(4)
```

10. Instead of generating a random number between zero and a given number like we did before, we can generate a random number that falls within a range of two specific numbers. To do this, we'll define a minimum number min and a maximum number max.

``` python
// Example
def ourFunction(ourMin, ourMax):
  return Math.floor(Math.random() * (ourMax - ourMin + 1)) + ourMin;


ourFunction(1, 9);


def randomRange(myMin, myMax):
  return 0 // Change this line


// Change these values to test your function
myRandom = randomRange(5, 15)
```
11. Return true if the passed string is a valid US phone number. The user may fill out the form field any way they choose as long as it is a valid US number. The following are examples of valid formats for US numbers (refer to the tests below for other variants)

Return true if the passed string is a valid US phone number.

The user may fill out the form field any way they choose as long as it is a valid US number. The following are examples of valid formats for US numbers (refer to the tests below for other variants):



