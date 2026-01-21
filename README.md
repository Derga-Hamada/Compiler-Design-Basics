# Compiler Design Basics: Lexical Analyzer

![Language](https://img.shields.io/badge/language-C-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-Educational-orange.svg)

## 📖 Overview
**Compiler-Design-Basics** is a lightweight Lexical Analyzer (Scanner) implemented from scratch in **C**. 

This project demonstrates the first phase of compiler design: breaking down raw source code into meaningful **Tokens**. It serves as an educational tool to understand how compilers process text, handle state transitions, and categorize code elements like keywords, identifiers, and operators.

## 🚀 Features
* **Tokenization:** Converts a stream of characters into defined tokens.
* **Keyword Recognition:** Detects reserved words (e.g., `begin`, `end`, `if`, `then`, `program`).
* **Type Detection:** Distinguishes between:
    * Identifiers (Variables)
    * Numbers (Integers)
    * Operators (`+`, `-`, `=`, etc.)
    * Delimiters
* **Whitespace Handling:** efficiently ignores spaces, tabs, and newlines.
* **Error Handling:** Flags unknown characters/tokens.

## 🛠️ Installation & Usage

### Prerequisites
* GCC Compiler (or any standard C compiler).

### Build and Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Derga-Hamada/Compiler-Design-Basics.git](https://github.com/Derga-Hamada/Compiler-Design-Basics.git)
    cd Compiler-Design-Basics
    ```

2.  **Compile the source code:**
    ```bash
    gcc src/main.c -o lexer
    ```

3.  **Run the analyzer:**
    ```bash
    ./lexer
    ```

## 💻 Example

**Input Source Code:**
```c
begin 
  var a = 100; 
  if a > 50 then end;
