# csharp-fundamentals

👨‍💻 **Author**: Karabo  
📚 **Systems Development Learner @ DynamicDNA**  
🎯 **Focused on mastering software engineering fundamentals**

---

## 📖 Overview

This repository contains beginner-friendly C# practice challenges organized by learning days. Each challenge is designed to teach you core programming concepts step-by-step, building your foundation in software development.

**Perfect for**: Beginners learning C#, students working through programming fundamentals, anyone wanting to master the basics before diving into advanced concepts.

---

## 📁 Repository Structure

```
csharp-fundamentals/
├── Day0/                    # 20 fundamental C# challenges
│   ├── 0_hello.cs          # Hello World
│   ├── 1_sum.cs            # Sum of Two Numbers
│   ├── 2_avg.cs            # Average Calculator
│   ├── 3_evenodd.cs        # Even/Odd Checker
│   ├── 4_factorial.cs       # Factorial Calculator
│   ├── 5_f_to_c.cs         # Temperature Conversion
│   ├── 6_fibbonaci.cs      # Fibonacci Sequence
│   ├── 7_palindrome.cs     # Palindrome Checker
│   ├── 8_prime.cs          # Prime Number Checker
│   ├── 9_max_array.cs      # Find Maximum in Array
│   ├── 10_reverse.cs       # String Reversal
│   ├── 11_vowels.cs        # Count Vowels
│   ├── 12_mult_table.cs    # Multiplication Table
│   ├── 13_digits.cs        # Count Digits
│   ├── 14_sum_digits.cs    # Sum of Digits
│   ├── 15_grade.cs         # Grade Calculator
│   ├── 16_words.cs         # Count Words
│   ├── 17_leap.cs          # Leap Year Checker
│   ├── 18_ascending.cs     # Sort Numbers
│   ├── 19_calculator.cs    # Simple Calculator
│   └── README.md           # Detailed Day0 explanations
└── README.md               # This file
```

---

## 🚀 Getting Started

### Prerequisites
- .NET SDK installed ([Download here](https://dotnet.microsoft.com/download))
- A text editor (VS Code, Visual Studio, or similar)
- Basic understanding of programming concepts (optional)

### Running the Programs

**Using the C# compiler (csc):**
```bash
# Compile
csc Day0/0_hello.cs

# Run
0_hello.exe  (Windows)
./0_hello    (Mac/Linux)
```

**Using .NET CLI:**
```bash
dotnet new console -n HelloWorld
cd HelloWorld
# Copy the challenge code into Program.cs
dotnet run
```

**Using an IDE:**
1. Open Visual Studio or VS Code
2. Create a new C# console project
3. Copy the code from any challenge file
4. Press F5 to run

---

## 📚 Day 0: Fundamentals (20 Challenges)

Day 0 covers the essential building blocks of C# programming. See [Day0/README.md](./Day0/README.md) for detailed explanations of each challenge.

### Quick Challenge List

| # | Challenge | Concepts | Difficulty |
|---|-----------|----------|-------------|
| 0 | Hello World | Program structure, Console.WriteLine() | ⭐ Easy |
| 1 | Sum of Two Numbers | Input/Output, Type conversion, Arithmetic | ⭐ Easy |
| 2 | Average Calculator | Multiple inputs, Division, Decimals | ⭐ Easy |
| 3 | Even/Odd Checker | Conditionals, Modulo operator | ⭐ Easy |
| 4 | Factorial | Loops, Multiplication, Pattern recognition | ⭐⭐ Medium |
| 5 | Temperature Conversion | Formula implementation, Order of operations | ⭐ Easy |
| 6 | Fibonacci Sequence | Loops, Variable tracking, Sequences | ⭐⭐ Medium |
| 7 | Palindrome Checker | String manipulation, Reversal | ⭐⭐ Medium |
| 8 | Prime Number Checker | Logic, Loops, Boolean flags | ⭐⭐ Medium |
| 9 | Find Max in Array | Arrays, Loops, Comparisons | ⭐⭐ Medium |
| 10 | Reverse String | String indexing, Backwards loops | ⭐⭐ Medium |
| 11 | Count Vowels | String iteration, OR conditions | ⭐ Easy |
| 12 | Multiplication Table | Loops, Formatting | ⭐ Easy |
| 13 | Count Digits | Type conversion, String length | ⭐ Easy |
| 14 | Sum of Digits | Number manipulation, Extraction | ⭐⭐ Medium |
| 15 | Grade Calculator | Multiple conditions, Ranges | ⭐⭐ Medium |
| 16 | Count Words | String splitting, Arrays | ⭐⭐ Medium |
| 17 | Leap Year Checker | Complex logic, AND/OR operators | ⭐⭐ Medium |
| 18 | Sort Numbers | Sorting algorithms, Nested loops | ⭐⭐⭐ Hard |
| 19 | Simple Calculator | Switch statements, Operations | ⭐⭐ Medium |

---

## 💡 Key Concepts Covered

### Fundamentals
- ✅ Program structure (using, class, Main method)
- ✅ Console input/output (ReadLine, WriteLine)
- ✅ Variables and data types (int, double, string, bool)
- ✅ Type conversion (int.Parse, Convert.ToInt32)

### Control Flow
- ✅ if-else statements
- ✅ switch statements
- ✅ Logical operators (&&, ||, !)
- ✅ Comparison operators (==, !=, <, >, <=, >=)

### Loops
- ✅ for loops (fixed iterations)
- ✅ while loops (conditional iterations)
- ✅ foreach loops (collection iteration)
- ✅ Loop control (break, continue)

### Data Structures
- ✅ Arrays (single-dimensional)
- ✅ Array indexing and iteration
- ✅ Array properties (.Length)

### String Operations
- ✅ String concatenation (+)
- ✅ String methods (.Length, .ToLower(), .ToUpper())
- ✅ String splitting (.Split())
- ✅ String indexing []

### Operators
- ✅ Arithmetic (+, -, *, /, %)
- ✅ Assignment (=, +=, -=, etc.)
- ✅ Increment/Decrement (++, --)
- ✅ Modulo (%) for remainders

---

## 🎯 Learning Path

### Beginner (Challenges 0-5)
Start here! Master basic input/output and simple arithmetic.
- 0_hello.cs
- 1_sum.cs
- 2_avg.cs
- 3_evenodd.cs
- 4_factorial.cs
- 5_f_to_c.cs

### Intermediate (Challenges 6-15)
Now you're ready for more complex logic and algorithms.
- 6_fibbonaci.cs
- 7_palindrome.cs
- 8_prime.cs
- 9_max_array.cs
- 10_reverse.cs
- 11_vowels.cs
- 12_mult_table.cs
- 13_digits.cs
- 14_sum_digits.cs
- 15_grade.cs

### Advanced (Challenges 16-19)
Put it all together with complex problems.
- 16_words.cs
- 17_leap.cs
- 18_ascending.cs
- 19_calculator.cs

---

## 🐛 Common Challenges I Faced

### 1. **Syntax Errors**
- **Problem**: Forgetting semicolons or curly braces
- **Solution**: Use an IDE with auto-completion and error highlighting
- **Tip**: Every statement ends with `;` and every block ends with `}`

### 2. **Type Confusion**
- **Problem**: Mixing strings and integers (`"5"` vs `5`)
- **Solution**: Always convert user input with `int.Parse()` or `Convert.ToInt32()`
- **Tip**: `Console.ReadLine()` ALWAYS returns a string!

### 3. **Integer Division**
- **Problem**: `5 / 2 = 2` instead of `2.5`
- **Solution**: Use `double` for at least one operand
- **Code**: `double result = (double)5 / 2;  // result = 2.5`

### 4. **Off-by-One Errors**
- **Problem**: Array loops skipping elements or going out of bounds
- **Solution**: Arrays start at index 0, length starts at 1
- **Tip**: `for (int i = 0; i < array.Length; i++)`

### 5. **Loop Variable Updates**
- **Problem**: Infinite loops from forgetting to update the loop variable
- **Solution**: Always update your loop variable in the loop
- **Code**: `for (int i = 1; i <= 10; i++)` or `while (n > 0) { n--; }`

### 6. **String Immutability**
- **Problem**: Thinking you can modify strings directly
- **Solution**: Create new strings, don't modify existing ones
- **Code**: `string reversed = ""; for (int i = str.Length - 1; i >= 0; i--) reversed += str[i];`

### 7. **Case Sensitivity**
- **Problem**: `console.WriteLine()` doesn't work (should be `Console.WriteLine()`)
- **Solution**: C# is case-sensitive! Match the exact casing
- **Tip**: Use IDE autocomplete to avoid this

### 8. **Comparison vs Assignment**
- **Problem**: Using `=` instead of `==` in conditions
- **Solution**: `==` compares values, `=` assigns values
- **Code**: `if (age == 18) { }` NOT `if (age = 18) { }`

### 9. **Modulo Operator Confusion**
- **Problem**: Not understanding how `%` works
- **Solution**: `a % b` gives the REMAINDER when a is divided by b
- **Example**: `10 % 3 = 1` (10 ÷ 3 = 3 remainder 1)

### 10. **Logic Errors in Conditions**
- **Problem**: Complex if-statements with wrong AND/OR logic
- **Solution**: Break down conditions step-by-step
- **Tip**: Test with specific values to verify logic

---

## ✅ Tips for Success

1. **Start Simple**: Run each program to see what it does before modifying it
2. **Add Debug Prints**: Use `Console.WriteLine()` to check variable values
3. **Read Error Messages**: They tell you exactly what's wrong and where
4. **Test Edge Cases**: What happens with 0, negative numbers, very large numbers?
5. **Comment Your Code**: Explain what each line does
6. **Practice Incrementally**: Don't skip challenges; they build on each other
7. **Use Keyboard Shortcuts**: Learn VS Code/Visual Studio shortcuts to code faster
8. **Discuss with Others**: Explain your code to someone else to find bugs
9. **Refactor After Success**: Once it works, make it cleaner and more efficient
10. **Build a Portfolio**: Keep these challenges as proof of your learning

---

## 📖 What to Learn Next

After mastering Day 0:
- **Object-Oriented Programming (OOP)**: Classes, objects, inheritance, polymorphism
- **Collections**: Lists, Dictionaries, HashSets
- **LINQ**: Language Integrated Query for powerful data manipulation
- **File I/O**: Reading and writing files
- **Exception Handling**: Try-catch blocks
- **Methods & Functions**: Reusable code blocks
- **Algorithms**: Sorting, searching, graph algorithms
- **Data Structures**: Stacks, queues, linked lists

---

## 🤝 Contributing

If you find improvements or have additional challenges to add:
1. Fork this repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

## 📝 License

Free to use for learning purposes.

---

## 🎓 About This Learning Journey

This repository documents my journey as a Systems Development Learner at DynamicDNA, focused on mastering the fundamentals of software engineering. Each challenge represents a concept I've learned, struggled with, and ultimately conquered. My goal is to help others navigate the same path more smoothly.

**Remember**: Every expert programmer was once a beginner. These challenges helped me understand the core concepts that power modern software development. Use them wisely, and don't give up!

---

**Happy Coding! 🚀**
