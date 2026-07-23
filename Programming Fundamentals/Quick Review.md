# Table of Content

### Core Topic

[Variables](#variables)
1. Variables

[Data Types](#data-types)
1.   Primitive Data Types
2.   Non-Primitive Data Types
3.   Numeric Types
4.   Boolean Type
5.   Character & String
6.   Static vs Dynamic Typing
7.   Strong vs Weak Typing
8.   Type Inference
9.   Type Conversion
10.   Null / None / Nil

[Functions]()

[Scope]()

[Recursion]()

[Arrays]()

[Strings]()

[Pointers / References]()

[Memory Management]()

[Object-Oriented Programming]()

[Interfaces]()

[Generic Programming]()

[Lambda / Delegates (language dependent)]()

[Exception Handling]()

[Const Correctness]()

[Static vs Dynamic Allocation]()

[Resource Lifetime]()

***

# Variables


## 1. Variables
### One Sentence Definition
A **variable** is a named storage location that holds a value, allowing a program to store, retrieve, and modify data during execution.

### Why Do We Need It?
Variables allow data to be stored, reused, updated, and shared between different parts of a program instead of hardcoding values everywhere.

It's the core component making program capable of handling changing data.

### Core Idea
A variable consists of three essential parts:

-   **Name (Identifier):** How the program refers to the stored data.
-   **Type (in statically typed languages):** Defines what kind of value can be stored.
-   **Value:** The actual data currently stored.

"A container with name tag, and a restriction declare what can be store in it."

### Key Characteristics
-   Has a unique identifier (name).
-   Stores a value that may change over time.
-   Has a data type (explicit or inferred in many languages).
-   Exists only within a certain scope and lifetime.
-   Can usually be read and written multiple times unless declared as immutable or constant.

### Advantages
N/A

### Disadvantages
N/A

### Common Use Cases
Every where in programming realm. No variable mean no way of constructure a dynamic program, it's madatory for input handling, calculation, confuguration, counter and even more.

### Comparison
| Concept | Purpose |
| --- | --- |
| Variable | Stores data that can usually change. |
| Constant | Stores data that should not change after initialization. |
| Literal | A fixed value written directly in code (e.g., `10`, `"Hello"`). |
| Expression | Produces a value, often using variables and operators. |

### Things People Often Confuse
N/A

### Things You MUST Remember
-   Every variable has a scope and lifetime, even if you don't explicitly see them.
-   A variable's value may change, but its identity (its name) remains the same.

### One-Minute Summary
N/A

***

# Data Types

##### What is a Data Type?

The foundation of the chapter.

Covers:

-   Definition of a data type
-   Why variables need types
-   How types determine what values and operations are allowed

## 1. Primitive (Basic) Data Types
### One Sentence Definition
**Primitive data types** are the most basic, built-in data types provided by a programming language that store a single, simple value.

### Why Do We Need It?
Computers process different kinds of information—numbers, text, and logical values. Primitive data types define the fundamental categories of data, allowing the compiler or interpreter to know how to store, interpret, and operate on each value efficiently.

Without primitive data types, a programming language would have no standardized way to represent basic information.

### Core Idea
Primitive data types are the **building blocks** of all other data types. They represent a single piece of data and are directly supported by the language and hardware.

Most complex data structures (such as arrays, classes, or objects) are ultimately built using primitive data types.

Common primitive data types include:

-   **Integer** – Whole numbers
-   **Floating-point** – Decimal numbers
-   **Boolean** – `true` or `false`
-   **Character** – A single text character

> **Note:** The exact set of primitive data types varies by programming language. For example, some languages treat `String` as a primitive type, while others treat it as an object.

### Key Characteristics
-   Built into the programming language.
-   Store a **single** value.
-   Usually have a fixed size and range.
-   Optimized for speed and memory efficiency.
-   Serve as the foundation for more complex data types.
