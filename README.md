# Building my own database
An attempt to learn & understand how databases work by building a simple database

Will be documenting my journey of learning & building a simple database from scratch using C.
In short, learning how does a database **work**?

I am buiding a clone of [sqlite](https://www.sqlite.org/arch.html) from scratch in C in order to understand, and I am going to document my process as I go.


## Table of Contents
1. Introduction and setting up the REPL




### Part 1 - Introduction and Setting up the REPL
- We'll write a simple read-execute-print loop which would take user input & perform some functions. As this is the first step, we'll only write simple functions to take input from user & exit the program.

### Part 2 - Tiny SQL Compiler and Virtual Machine
- Frontend of sqlite is a sql compiler that parses the string (user command) and outputs the internal representation as bytecode.
- <img width="308" alt="Screenshot 2025-05-05 at 12 07 00 AM" src="https://github.com/user-attachments/assets/ec7e7121-4924-4cd7-8a5b-1d3f2a91e215" />
