---
num: "Lecture 7"
desc: "Midterm 1 Review"
ready: true
date: 2018-10-18 14:00:00.00-7:00
---

Link to Sample Midterm 1 Exam from S18:
[sample midterm 1](http://cs.ucsb.edu/~richert/cs32/exams/sampleM1.pdf)

```
Logistics
- Bring studentID and writing utensil
- No electronic devices
- No notes, no books

Format
- Will be a mix of questions
- Short Answer
	- Briefly define, describe, state, ...
- Write code (includes makefiles)
- Fill in the blank / complete the table
- Given code, write the output (be the compiler)
- Given a statement, tell me if it's true / false
	- if false, briefly state why
- Expect it to take ~ one hour (maybe sooner)
	- but we have the entire class period
- Will cover a broad range of topics, but probably not everything

Topics
- Will cover everything up to Tuesday's lecture (10/16)

Makefiles
- Know how to create one when multiple files are linked to form an
executable
- Know the build process
	- Proprocessing, Compiling, Linking
- Know what the default rules are, flags, special symbols (as discussed in lecture)

Standard Template Library
- Reviewed some details about vectors
	- Operations like [], at, front, back, pop_back, push_back, size, constructors
- Reviewed iterators
	- begin(), end(), ++, <, *, erase
- Sets
	- Definition, insert, find, iterators
- STL Maps and unordered_maps
	- [], find, iterators, pairs, insert, erase

Class Design
- Abstract Data Types
- How to design an interface (.h file) and its implementation (.cpp)
- Public vs. Private
- Accessors (getters) vs Mutators (setters)
- Constructors (default, overloaded, copy)
- Header guards
- Scope Resolution operator (::) and .cpp method definitions
- Shallow vs. Deep Copy
- Big Three (Rule of Three): copy constructor, destructor, assignment operator

Structs and Classes
- What are the difference(s)?
- Memory Padding (how they are stored in memory)

Namespaces
- Avoid naming collisions
- How to create namespaces in your code
- Global namespace (how to specifiy using "::")

Binary Search
- Recursive (and iterative (non-recursive)) implementation
- Performance (running time), O-notation

Quadratic Sorting Algorithms
- bubbleSort
	- Optimized version
- selectionSort
- insertionSort
- Performance (best / worst case scenarios), O-notation

Hash Table
- Definitions of open-address hashing, double hashing, collisions, chained hashing
- unordered_map vs map
	- performance for certain operations
	- underlying structure of each
```