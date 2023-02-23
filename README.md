

#### 1. Sum the Numbers
Find the sum of all elements in an array and print to the console.

```js
let sum = [11, 23, 34, 54, 57];

```

#### 2. Largest Number
Find the largest element in an array and print to the console. 

```js 
const largest = [5, 7, 2, 4, 9];
```
#### 3. Smallest Number
Find the smallest element in an array and print to the console.
```js 
const smallest = [5, 7, 2, 4, 9];
```

#### 4. Even Numbers
For the given array of numbers, print each number in the array that is even.

```js 
const even = [34, 56, 43, 11, 87, 67, 55, 44, 12, 6, 4, 98, 83]
```

#### 5. Positive Numbers
For the given array of numbers,  print each number in the array that is greater than zero.

```js 
const positive = [34, -56, 16, 23, -4, -6, -8, 12, 11, 78, -3, -2, 5, -44 ]
```

#### 6. Positive Numbers II
For the given array of numbers, **create a new array** which contains every number in the given array which is positive.

```js 
const positive2 = [34, -56, 16, 23, -4, -6, -8, 12, 11, 78, -3, -2, 5, -44 ]
```
#### 7. Multiply a array
For the given array of numbers, and a factor of 5, **create a new array** consisting of each of the numbers in the array multiplied by the factor. Print this array.

```js 
const positive2 = [34, -56, 16, 23, -4, -6, -8, 12, 11, 78, -3, -2, 5, -44 ]
```

#### 8. Reverse a String
Given a string, print the string reversed. For example, reverse the string "Hello World".

#### 9. Multiply Vectors
Given two arrays of numbers of the same length, create a new array by multiplying the pairs of numbers in corresponding positions in the two arrays. Example:

```js 
[2, 4, 5] x [2, 3, 6] = [4, 12, 30]
```

#### 2. Matrix Addition
Given two two-dimensional arrays of numbers of the size 2x2 two dimensional array is represented as an array of arrays:

```js 

[ [2, -2],
   [5, 3] ]
```

Calculate the result of adding the two matrices. The number in each position in the resulting matrix should be the sum of the numbers in the corresponding addend matrices. Example: to add

```text
1 3
2 4
```

and

```text
5 2 1 0 
```

results in

```text
6 5
3 4
```

#### 3. Matrix Addition II
Use your solution in Matrix Addition, and extend it to work for a pair of matrices of any size, as long as they have the same size.

#### 4. De-dup
Given a array of numbers or strings, create a new array containing the same elements as the first array, except with any duplicate values removed. Print the array.


#### 5. Leetspeak

Given a paragraph of text as a String, print the paragraph in [leetspeak](https://en.wikipedia.org/wiki/Leet). 

To translate a String to leetspeak, you need to replace make the following character replacements (treat all input characters as uppercase):

| Letter | Translates To |
|:------:|:-------------:|
| A      | 4             |
| E      | 3             |
| G      | 6             |
| I      | 1             |
| O      | 0             |
| S      | 5             |
| T      | 7             |

Example: If your program is given the String `"I am a leet programmer"`, it should print `"1 4m 4 l337 pr0gr4mm3r"` as the leetspeak translation

#### 6. Long-long Vowels

Given a word as a string, print the result of extending any long vowels to the length of 5. 

Examples:

```
Good => Goooood 
Cheese => Cheeeeese 
Man => Man 
Spoon => Spooooon 
```

#### 7. Caesar Cipher

Given a string, print the Caesar Cipher (or ROT13) of that string. What is Caesar Cipher? [Learn about it here](http://practicalcryptography.com/ciphers/caesar-cipher/).

Use your solution to decipher the following text: "lbh zhfg hayrnea jung lbh unir yrnearq"