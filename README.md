# PalindromeCheckerApp

The program takes a string input from the user using Scanner.

It preprocesses the string by removing spaces and converting it to lowercase.

A Stack (LIFO) and a Queue (FIFO) are created.

Each character of the processed string is pushed into the stack and enqueued into the queue.

The stack stores characters in reverse order (LIFO behavior).

The queue stores characters in original order (FIFO behavior).

The program compares stack.pop() with queue.remove() for each character.

If all characters match, it prints “Palindrome”; otherwise, it prints “Not a Palindrome.”