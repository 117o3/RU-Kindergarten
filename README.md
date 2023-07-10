# RU-Kindergarten
Data Structures Assignment: _Linked Lists Based Project_

Simulate the students standing in a line, the students on their seats, and the students playing musical chairs, using Singly & Circular Linked Lists, and 2D arrays

-----------------------------------------
Files Implemented: _RUKindergarten/src/kindergarten/Classroom.java_

enterClassroom()
setupSeats()
seatStudents()
insertMusicalChairs()
moveStudentFromChairsToLine()
insertByHeight()
eliminateLosingStudent()
seatMusicalChairsWinner()

to compile: javac -d bin src/kindergarten/*.java

to execute: java -cp bin kindergarten.Driver

-----------------------------------------
Programming Skills Utilized: _only mentioning new skills NOT mentioned in previous methods_

enterClassroom() 
  - File Handling(input): StdIn.setFile(filename)
  - Linked List: knowledge of linked list structure and operations
  - Read from File: StdIn.readString()
  - Creaing Objects: ex. Student(first name, last name, height)
  - Insert at front of Linked List
  - Sorting

setupSeats()
  - File Handling(output)
  - 2D Array Manipulation
  - Boolean Operations
  - Variable Initalization
  - File Format Parsing

seatStudents()
  - Algorithmic Thinking & Logical Reasoning: consider seating locations; handle special case of musical chairs winner
  - Insertion/Removal Operations of Linked Lists

insertMusicalChairs()
  - Nested Loops
  - Indexing
  - Control Flow: if-else, for-while loops

moveStudentFromChairsToLine()
  - Random Number Generation: StdRandom.uniform()
  - Search & Delete Operations
  - Inserting Operations: insert element into list/array

insertByHeight()
  - Looping, Iteration, & Comparison
  - Error Handling: empty lists

eliminateLosingStudent()
  - Decrease size of 

seatMusicalChairsWinner()
  - Circular Linked Lists: each node has reference; last node points to first
  - Pointers/References
