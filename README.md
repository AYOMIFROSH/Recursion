# isPalindrome Function

The `isPalindrome` function is a JavaScript algorithm that checks if a given word is a palindrome. A word is considered a palindrome if it can be read the same way forwards and backwards.

## Usage

To use the `isPalindrome` function, follow these steps:

1. Copy the function code into your JavaScript project.
2. Call the function with a word as an argument, like this: `isPalindrome("your_word")`.
3. The function will return `true` if the word is a palindrome, and `false` otherwise.

## Algorithm

The `isPalindrome` function uses a recursive approach to check if a word is a palindrome. Here's how it works:

1. If the length of the word is less than or equal to 1, return `true`. This is the base case for the recursion.
2. If the first and last characters of the word are equal, call the `isPalindrome` function recursively with the substring excluding the first and last characters.
3. If the first and last characters are different, return `false`.
4. Repeat steps 2-3 until the base case is reached.

## Example

Here's an example usage of the `isPalindrome` function:

```javascript
console.log(isPalindrome("radar")); // Output: true
console.log(isPalindrome("hello")); // Output: false