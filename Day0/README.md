# Day 0: C# Fundamentals - Practice Challenges

Welcome! This folder contains 20 beginner-friendly C# challenges designed to build your programming foundation. Each challenge focuses on a core concept that you'll use throughout your coding journey.

## 📚 Challenges Overview

### 0. Hello World (`0_hello.cs`)
**What it does:** Prints "Hello, World!" to the screen.

**Key Concepts:**
- Your first C# program
- `Console.WriteLine()` - outputs text
- Program structure (class, Main method)

**Common Challenges:**
- Forgetting semicolons at the end of lines
- Case sensitivity: `WriteLine` vs `writeline`

---

### 1. Sum of Two Numbers (`1_sum.cs`)
**What it does:** Adds two numbers together and displays the result.

**Key Concepts:**
- Reading user input with `Console.ReadLine()`
- Converting text to numbers using `int.Parse()`
- Basic arithmetic (+)

**Common Challenges:**
- Understanding that `Console.ReadLine()` always returns text (string)
- Remembering to convert strings to integers before doing math

---

### 2. Average Calculator (`2_avg.cs`)
**What it does:** Calculates the average of three numbers.

**Key Concepts:**
- Working with multiple inputs
- Division in programming
- Using `double` for decimal results

**Common Challenges:**
- Integer division: `5/2 = 2` (not 2.5!)
- Need to use `double` or cast to get decimal answers
- Forgetting to divide by the correct count

---

### 3. Even or Odd Checker (`3_evenodd.cs`)
**What it does:** Tells you if a number is even or odd.

**Key Concepts:**
- `if-else` statements for decision making
- Modulo operator `%` (gives remainder)
- Even numbers: divisible by 2 (remainder = 0)

**Common Challenges:**
- Understanding the modulo operator: `10 % 3 = 1` (10 ÷ 3 = 3 remainder 1)
- Using `==` for comparison, not `=` (assignment)

---

### 4. Factorial Calculator (`4_factorial.cs`)
**What it does:** Calculates factorial (e.g., 5! = 5 × 4 × 3 × 2 × 1 = 120).

**Key Concepts:**
- `for` loops for repetition
- Multiplying in a loop
- Starting with result = 1 (not 0!)

**Common Challenges:**
- Remembering to initialize result to 1, not 0
- Off-by-one errors in loop conditions
- Understanding that 0! = 1 (special case)

---

### 5. Fahrenheit to Celsius (`5_f_to_c.cs`)
**What it does:** Converts temperature from Fahrenheit to Celsius.

**Key Concepts:**
- Formula: C = (F - 32) × 5/9
- Order of operations matters
- Using doubles for precision

**Common Challenges:**
- Getting the formula wrong
- Integer division killing your decimals
- Parentheses placement affecting calculation order

---

### 6. Fibonacci Sequence (`6_fibbonaci.cs`)
**What it does:** Prints Fibonacci numbers (1, 1, 2, 3, 5, 8, 13...).

**Key Concepts:**
- Each number = sum of previous two
- Tracking multiple variables in a loop
- Swapping values

**Common Challenges:**
- Managing three variables (current, previous, next)
- Getting the first two numbers right
- Understanding the swap logic

---

### 7. Palindrome Checker (`7_palindrome.cs`)
**What it does:** Checks if a word reads the same forwards and backwards (like "racecar").

**Key Concepts:**
- String manipulation
- Reversing strings
- String comparison

**Common Challenges:**
- Case sensitivity: "Racecar" vs "racecar"
- Understanding string indexing and loops
- Building reversed strings character by character

---

### 8. Prime Number Checker (`8_prime.cs`)
**What it does:** Determines if a number is prime (only divisible by 1 and itself).

**Key Concepts:**
- Loop through possible divisors
- Early exit with `break`
- Boolean flags (isPrime)

**Common Challenges:**
- Edge cases: 1 is NOT prime, 2 IS prime
- Optimization: only need to check up to square root
- Understanding when to stop checking

---

### 9. Find Maximum in Array (`9_max_array.cs`)
**What it does:** Finds the largest number in a list of numbers.

**Key Concepts:**
- Arrays and lists
- Looping through collections
- Keeping track of maximum value

**Common Challenges:**
- Initializing max to first element (not 0!)
- Comparing each element correctly
- Understanding array indexing [0], [1], [2]...

---

### 10. Reverse a String (`10_reverse.cs`)
**What it does:** Flips a word backwards ("hello" → "olleh").

**Key Concepts:**
- String indexing
- Looping backwards
- Building new strings

**Common Challenges:**
- String immutability in C#
- Loop direction (counting down from length-1 to 0)
- Starting index at length-1, not length

---

### 11. Count Vowels (`11_vowels.cs`)
**What it does:** Counts how many vowels (a, e, i, o, u) are in a text.

**Key Concepts:**
- Character iteration with `foreach`
- OR operator `||` for multiple conditions
- Converting to lowercase for easier checking

**Common Challenges:**
- Case sensitivity: checking both 'A' and 'a'
- Using `.ToLower()` simplifies checking
- OR operator syntax: `||` not `|`

---

### 12. Multiplication Table (`12_mult_table.cs`)
**What it does:** Prints the times table for a number (e.g., 5×1=5, 5×2=10...).

**Key Concepts:**
- Nested loops (optional) or simple loop
- String formatting for output
- Basic multiplication

**Common Challenges:**
- Formatting output nicely
- Loop range (typically 1 to 10)
- Understanding when to use nested vs single loops

---

### 13. Count Digits (`13_digits.cs`)
**What it does:** Counts how many digits are in a number.

**Key Concepts:**
- Converting number to string
- String length property
- Alternative: division by 10 in a loop

**Common Challenges:**
- Choosing between string method or math method
- Handling negative numbers (minus sign counts!)
- Dealing with 0 (special case: 1 digit)

---

### 14. Sum of Digits (`14_sum_digits.cs`)
**What it does:** Adds up all digits in a number (e.g., 123 → 1+2+3 = 6).

**Key Concepts:**
- Extracting individual digits
- Modulo to get last digit: `num % 10`
- Integer division to remove last digit: `num / 10`

**Common Challenges:**
- Understanding the extract-and-remove pattern
- Loop continues while number > 0
- Order doesn't matter for addition!

---

### 15. Grade Calculator (`15_grade.cs`)
**What it does:** Converts a percentage to a letter grade (A, B, C, D, F).

**Key Concepts:**
- Multiple `if-else` statements
- Comparison operators: `>=`, `<`
- Logical flow and conditions

**Common Challenges:**
- Getting the ranges right (90-100=A, 80-89=B, etc.)
- Order matters! Check highest grade first
- Edge cases: exactly 90, exactly 80, etc.

---

### 16. Count Words (`16_words.cs`)
**What it does:** Counts how many words are in a sentence.

**Key Concepts:**
- String splitting: `.Split(' ')`
- Array length
- Handling multiple spaces

**Common Challenges:**
- Extra spaces creating empty array elements
- Different ways to split (space, tab, newline)
- Trim extra whitespace first

---

### 17. Leap Year Checker (`17_leap.cs`)
**What it does:** Determines if a year is a leap year.

**Key Concepts:**
- Complex logical conditions with AND `&&` and OR `||`
- Leap year rules:
  - Divisible by 4 AND
  - (NOT divisible by 100 OR divisible by 400)

**Common Challenges:**
- Getting the logic right (three conditions!)
- Understanding the exception to the exception
- Order of operations with && and ||

---

### 18. Sort Numbers Ascending (`18_ascending.cs`)
**What it does:** Arranges numbers from smallest to largest.

**Key Concepts:**
- Sorting algorithms (bubble sort, selection sort)
- Nested loops for comparisons
- Swapping values
- Or using built-in `Array.Sort()`

**Common Challenges:**
- Understanding sorting algorithms
- Nested loop logic can be tricky
- Swap requires temporary variable
- Built-in sort is easier but less educational!

---

### 19. Simple Calculator (`19_calculator.cs`)
**What it does:** Performs basic math operations (+, -, ×, ÷) based on user choice.

**Key Concepts:**
- `switch` statements for multiple options
- User input validation
- Different operations in one program

**Common Challenges:**
- Division by zero error
- Handling invalid operators
- Switch vs if-else decision
- `break` statements in each case

---

## 🎯 General Challenges I Faced

### Syntax Errors
- **Missing semicolons**: Every statement needs one!
- **Case sensitivity**: `Console` not `console`, `Main` not `main`
- **Brackets matching**: Every `{` needs a `}`

### Data Type Confusion
- **String vs int**: `"5"` is different from `5`
- **Integer division**: `5/2 = 2` in integer math
- **Parse errors**: Trying to convert non-numeric text to numbers

### Logic Errors
- **Off-by-one errors**: Arrays start at 0, lengths start at 1
- **Infinite loops**: Forgetting to update loop variables
- **Comparison vs assignment**: `==` checks equality, `=` assigns

### Input/Output Issues
- **ReadLine() always returns string**: Must convert to numbers
- **Newline characters**: `ReadLine()` removes them, but be aware
- **Type conversion**: `int.Parse()`, `Convert.ToInt32()`, etc.

---

## 💡 Tips for Success

1. **Start small**: Run each program to see what it does
2. **Add Console.WriteLine()**: Debug by printing variable values
3. **Read error messages**: They tell you exactly what's wrong
4. **Test edge cases**: What if input is 0? Negative? Very large?
5. **Comment your code**: Future you will thank present you
6. **Practice daily**: Programming is a skill built through repetition

---

## 🚀 Running the Programs

```bash
# Compile a program
csc filename.cs

# Run the compiled program
filename.exe

# Or use dotnet (if you have .NET SDK)
dotnet run filename.cs
```

---

## 📖 What's Next?

After mastering these basics, you'll be ready for:
- Object-oriented programming (classes, objects)
- More complex data structures (lists, dictionaries)
- File I/O operations
- Exception handling
- LINQ queries

Keep coding! Every expert was once a beginner. 🌟

---

## 👋 Insanely Simple Code Breakdowns

Here are SUPER simple explanations of each challenge's code. If you don't understand something, re-read this section.

### Challenge 0: Hello World - The Simplest Ever

```csharp
using System;                    // Import the System library (it has Console)

class Program                     // Create a class called Program
{
    static void Main()            // Main method - where your code starts running
    {
        Console.WriteLine("Hello, World!");  // Print text to screen
    }
}
```

**Word by word:**
- `using System;` = "Get me the System tools"
- `class Program {` = "Create a container for my code"
- `static void Main() {` = "This is where execution starts"
- `Console.WriteLine(" ");` = "Print something to the screen"

**What it does:** Prints "Hello, World!" to your screen. That's it!

---

### Challenge 1: Sum - Adding Two Numbers

```csharp
using System;

class Program
{
    static void Main()
    {
        int a = int.Parse(Console.ReadLine());   // Get first number from user
        int b = int.Parse(Console.ReadLine());   // Get second number from user
        Console.WriteLine("Sum: " + (a + b));    // Add them and print
    }
}
```

**Simple explanation:**
1. Ask user for first number: `Console.ReadLine()` (gets text)
2. Convert text to number: `int.Parse()` (turns "5" into 5)
3. Store in variable `a`
4. Repeat for `b`
5. Add `a + b` and print result

**The hard part:** `int.Parse()` converts text to numbers. `Console.ReadLine()` ALWAYS gives you text!

---

### Challenge 3: Even or Odd

```csharp
using System;

class Program
{
    static void Main()
    {
        int num = int.Parse(Console.ReadLine());  // Get number
        
        if (num % 2 == 0)                          // If remainder is 0
            Console.WriteLine("Even");             // It's even!
        else
            Console.WriteLine("Odd");              // It's odd
    }
}
```

**The SECRET:** `%` (modulo) gives the remainder
- `10 % 2 = 0` (even - no remainder)
- `11 % 2 = 1` (odd - remainder of 1)

**Logic:**
- If `number % 2 == 0` → even
- Otherwise → odd

---

### Challenge 4: Factorial

```csharp
using System;

class Program
{
    static void Main()
    {
        int n = int.Parse(Console.ReadLine());  // Get number (e.g., 5)
        int result = 1;                          // Start with 1
        
        for (int i = 1; i <= n; i++)            // Loop from 1 to n
            result *= i;                         // Multiply: result = result * i
        
        Console.WriteLine(result);               // Print 120 (for 5!
    }
}
```

**Magic step:** `result *= i` means "multiply result by i and save it"
- Start: result = 1
- i=1: result = 1 * 1 = 1
- i=2: result = 1 * 2 = 2
- i=3: result = 2 * 3 = 6
- i=4: result = 6 * 4 = 24
- i=5: result = 24 * 5 = 120

**Critical tip:** Start with `result = 1`, NOT 0! (multiplying by 0 gives 0)

---

### Challenge 6: Fibonacci

```csharp
using System;

class Program
{
    static void Main()
    {
        int n = int.Parse(Console.ReadLine());   // How many numbers to print
        int a = 0, b = 1;                        // First two numbers
        
        for (int i = 0; i < n; i++)
        {
            Console.Write(a + " ");              // Print a
            int temp = a + b;                    // Add them
            a = b;                               // Shift: a becomes b
            b = temp;                            // b becomes the new number
        }
    }
}
```

**The sequence:** 0, 1, 1, 2, 3, 5, 8, 13...
- Each number = previous two added
- `a` and `b` are the two numbers
- `temp` holds the new number temporarily
- Then we shift: `a` becomes `b`, and `b` becomes the new number

**Think of it like:**
- Slot 1 (a) = 0
- Slot 2 (b) = 1
- New = Slot1 + Slot2 = 1
- Now: Slot1 = 1, Slot2 = 1
- New = 1 + 1 = 2
- Now: Slot1 = 1, Slot2 = 2
- And so on...

---

### Challenge 8: Prime Number Checker

```csharp
using System;

class Program
{
    static void Main()
    {
        int num = int.Parse(Console.ReadLine());  // Get number
        bool isPrime = true;                      // Assume it's prime
        
        if (num < 2)
            isPrime = false;                      // Numbers below 2 aren't prime
        
        for (int i = 2; i < num; i++)            // Check each number from 2 to num-1
        {
            if (num % i == 0)                    // If divisible
            {
                isPrime = false;                 // It's NOT prime
                break;                           // Stop checking
            }
        }
        
        Console.WriteLine(isPrime);              // Print true or false
    }
}
```

**The logic:**
- A prime number is only divisible by 1 and itself
- We check: "Does any number from 2 to (num-1) divide this number?"
- If YES → it's not prime → set `isPrime = false` and stop (`break`)
- If NO numbers divide it → it's prime

**Optimization:** You only need to check up to the square root, but this works too!

---

### Challenge 11: Count Vowels

```csharp
using System;

class Program
{
    static void Main()
    {
        string text = Console.ReadLine();        // Get user's text
        int count = 0;                           // Start counting at 0
        
        foreach (char letter in text)            // For each letter in text
        {
            if (letter == 'a' || letter == 'e' || letter == 'i' || letter == 'o' || letter == 'u')
                count++;                         // Found a vowel!
        }
        
        Console.WriteLine(count);                // Print how many
    }
}
```

**Simpler way:**

```csharp
string text = Console.ReadLine().ToLower();  // Convert to lowercase
int count = 0;

foreach (char letter in text)
{
    if (letter == 'a' || letter == 'e' || letter == 'i' || letter == 'o' || letter == 'u')
        count++;
}

Console.WriteLine(count);
```

**Why `ToLower()`?** So you only check lowercase vowels, not both 'A' and 'a'.

---

### Challenge 14: Sum of Digits

```csharp
using System;

class Program
{
    static void Main()
    {
        int num = int.Parse(Console.ReadLine());  // Get number (e.g., 123)
        int sum = 0;                              // Start sum at 0
        
        while (num > 0)                           // While number has digits
        {
            sum += num % 10;                      // Add last digit to sum
            num /= 10;                            // Remove last digit
        }
        
        Console.WriteLine(sum);                   // Print sum
    }
}
```

**Step by step (for 123):**
- num = 123, sum = 0
- `123 % 10 = 3` → sum = 3, `123 / 10 = 12`
- `12 % 10 = 2` → sum = 5, `12 / 10 = 1`
- `1 % 10 = 1` → sum = 6, `1 / 10 = 0`
- num = 0, stop
- Print 6 (which is 1+2+3)

**Key operators:**
- `%` = gets last digit
- `/` = removes last digit

---

### Challenge 18: Sorting (Bubble Sort)

```csharp
using System;

class Program
{
    static void Main()
    {
        int[] numbers = { 5, 2, 8, 1, 9 };      // Array of numbers
        
        for (int i = 0; i < numbers.Length - 1; i++)      // Each pass
        {
            for (int j = 0; j < numbers.Length - 1 - i; j++)  // Compare pairs
            {
                if (numbers[j] > numbers[j + 1])          // If left > right
                {
                    // Swap them
                    int temp = numbers[j];
                    numbers[j] = numbers[j + 1];
                    numbers[j + 1] = temp;
                }
            }
        }
        
        // Print sorted array
        foreach (int num in numbers)
            Console.WriteLine(num);
    }
}
```

**The idea:**
- Compare neighbors
- If left > right, swap them
- Do this over and over until sorted
- It's like bubbles rising: biggest numbers "bubble" to the end

**Swap trick:**
```
int temp = a;     // Save a in temp
a = b;            // Put b into a  
b = temp;         // Put temp (old a) into b
// Result: a and b are swapped!
```

---

## 🌟 You Did It!

You now understand the fundamental patterns:
1. **Input/Output**: `ReadLine()` and `WriteLine()`
2. **Math**: `+`, `-`, `*`, `/`, `%`
3. **Conditionals**: `if`, `else`
4. **Loops**: `for`, `while`, `foreach`
5. **Arrays**: Create, loop through, access elements
6. **Strings**: Concatenation, methods, indexing

Every single challenge in this folder uses ONLY these concepts. Master these, and you've mastered the fundamentals!

---

**Keep practicing! The more you code, the more natural it becomes!** 🚀
