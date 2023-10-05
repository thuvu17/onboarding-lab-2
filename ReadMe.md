# Week 2 Lab: System Verilog

## Why do you think the reason for these different testing approaches are? What are their advantages and disadvantages?
### Exercise 1
- Exhaustively test all possible inputs
- The reason: Simple program, only that many test cases so it's small enough to test them all
- Works on smaller programs, but for ones that have more input combinations, this will be inefficient and sometimes not possible
### Exercise 2
- Samples some possible initial values for a hundred cycles
- The reaon: This is the Fibonacci LSFR program, if it works for the first few inputs, it will work for the rest
- Don't have to go through all inputs, but only work for certain programs with patterns
### Exercise 3
- Randomly tests inputs for a hundred cycles
- The reason: Use random inputs to find unexpected bugs
- Might miss the important functionalities or even edgecases
