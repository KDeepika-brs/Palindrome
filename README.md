# Palindrome

##### The isPalindrome function checks if a given string str is a palindrome, which means it reads the same forwards and backwards. It uses two pointers, i and j, initialized at the beginning and the end of the string, respectively. While i is less than j, it compares the characters at the ith and jth positions. If they are not equal, it immediately returns false, indicating that the string is not a palindrome. If the characters are equal, it moves i one step forward and j one step backward, continuing the comparison until i is no longer less than j.

##### If the function reaches this point without returning false, it means the string is a palindrome, and it returns true. The time complexity of this algorithm is O(n), where n is the length of the input string, as it needs to compare each character at most once.

#### Dear Students, Check out the live app [here](https://kdeepika-brs.github.io/Palindrome/).

