# Pseudocode

Write the pseudocode of each of the following exercises:

1. Write a function called `repeatedChars` that receives two strings and returns a new string with the characters that are repeated in both input strings:

```javascript
console.log(repeatedChars("german", "gabriela")); // "gear"
```

2. Write a function called `findLongestWordLength` that receives a string and returns the length of the longest word in the sentence.

```javascript
console.log(findLongestWordLength("The quick brown fox jumped over the lazy dog")); // 6
```

3. Write a function called `sort` that receives an array of numbers and return the array in sorted order (ascending) **without using the `sort` method**.

```javascript
console.log(sort([5, 8, 3, 0, 7])); // [0, 3, 5, 7, 8]
```

4. Write a function called `anagram` that receives two strings and returns true if the strings are anagrams, false otherwise. Two words are anagrams if one of them has exactly same characters as that of the another word

```javascript
console.log(anagram("anagram", "nagaram")); // true
console.log(anagram("hello", "world")); // false
```

5. Write a function called tictactoe that receives a matrix and returns true if it's winning for 'X' or 'O'.

```javascript
console.log(tictactoe([
  ['X', '', 'O'],
  ['', 'X', 'O'],
  ['O', '', 'X']
])); // true

console.log(tictactoe([
  ['O', 'X', 'O'],
  ['', 'X', 'O'],
  ['O', '', 'X']
])); // false
```

## Bonus

6. Write a function called `toRoman` that converts a number (in the range 1 to 3000) to its roman representation.

```javascript
console.log(toRoman(1)); // I
console.log(toRoman(4)); // IV
console.log(toRoman(10)); // X
console.log(toRoman(50)); // L
console.log(toRoman(100)); // C
console.log(toRoman(500)); // D
console.log(toRoman(476)); // CDLXXVI
