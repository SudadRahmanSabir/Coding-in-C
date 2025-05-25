🎉 Solved "Hello, World!" in C – My First HackerRank Challenge

📄 Post Content:
markdown
Copy
Edit
## 💻 HackerRank Challenge: "Hello, World!" in C

This is my solution to the first C programming problem on HackerRank. It's a simple task but marks the beginning of my journey into C programming.

---

### 📌 Problem Statement:

> In this challenge, you must print two lines of output:
> 
> 1. The string `"Hello, World!"`
> 2. The input string provided by the user (which may contain spaces)
> 
> ### Input Format:
> One line of input text (a string).
> 
> ### Output Format:
> Print:
> ```
> Hello, World!
> <user input>
> ```

---

### 📥 Sample Input:
Welcome to C programming.

shell
Copy
Edit

### 📤 Sample Output:
Hello, World!
Welcome to C programming.

cpp
Copy
Edit

---

### ✅ My Solution in C:

```c
#include <stdio.h>

int main() {
    char s[100];  // Declare a string to hold user input

    // Read a line of input including spaces
    fgets(s, sizeof(s), stdin);

    // Print the required output
    printf("Hello, World!\n");
    printf("%s", s);

    return 0;
}
🧠 What I Learned:
How to use #include <stdio.h> for I/O in C

How to use fgets() instead of scanf() to read full lines

How to print strings using printf() and %s

📌 This is a great beginner problem to get familiar with C syntax, and I'm excited to continue solving more challenges!
