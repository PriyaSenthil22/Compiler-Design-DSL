End-to-End Compiler for Custom DSL

 Project Overview

This project implements a simplified **end-to-end compiler** for a custom Domain-Specific Language (DSL). It simulates the complete compilation pipeline from source code to output by performing lexical analysis, parsing, semantic handling, and execution.

 Objective

* To design a basic compiler pipeline using C
* To process DSL statements
* To simulate compilation phases (Lexer, Parser, Semantic Analysis)
* To generate output from given DSL code

 Technologies Used

* **Programming Language:** C
* **Concepts:**

  * Strings
  * Arrays
  * Parsing using `sscanf()`
  * Conditional statements
  * Basic compiler design principles

 How It Works

1. Input

* DSL statements entered by the user
* Example commands:

  * `let x = 10`
  * `let z = x + y`
  * `print z`

2. Data Processing

* Input is read line by line
* Statements are parsed using string functions
* Variables and values are stored

3. Feature Computation

* Arithmetic operations (like addition) are evaluated
* Variable values are updated accordingly

4. Execution

* When a `print` statement is encountered, the result is displayed

5. Output

* Displays computed result of the DSL program

 How to Run

1. Open the `.c` file in Dev-C++ / Code::Blocks
2. Compile the program
3. Run the executable
4. Enter DSL statements line by line
5. Type `END` to stop execution

 Sample Input

let x = 10
let y = 20
let z = x + y
print z
END

 Sample Output

Output: 30

 Feature Justification

* Simple DSL syntax improves readability
* Step-by-step execution simulates compiler phases
* Use of C ensures efficient processing
* Demonstrates core compiler concepts in a simplified way

 File Structure

```id="r3y0av"
RegNo_Name_Compiler.c
RegNo_Name_Output.png
RegNo_Name_Explanation.pdf
README.md
```

Conclusion

This project demonstrates a simplified end-to-end compiler for a custom DSL. It shows how source code can be processed through different stages to produce output, helping in understanding core compiler design concepts.

