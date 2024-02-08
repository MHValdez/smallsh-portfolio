**\*\* The [actual repo](https://github.com/MHValdez/CS344_smallsh) for this project is private per the instructor. Collaborator invite avaiable upon request. \*\***

# Small Shell
A miniature Bash-like shell; Main project for Operating Systems class

## Introduction

This code replicates the functionality of Bash in many ways, deviates in some ways, and is non-functional in many other ways.

The primary purpose of the assignment was to demonstrate an understanding of:
- Forking
- Signal Handling
- Redirection

The original, unaltered assignment specifications are provided below. They seemed to have become quite bloated by the time I took the course and the (new) professor expressed his displeasure with them. The course was undergoing redesign and I was in the last cohort to do this version.

## Truncated Assignment Specification

Introduction

In this assignment you will write smallsh your own shell in C. smallsh will implement a command line interface similar to well-known shells, such as bash. Your program will

    Print an interactive input prompt
    Parse command line input into semantic tokens
    Implement parameter expansion

    Shell special parameters $$, $?, and $!
    Generic parameters as ${parameter}

    Implement two shell built-in commands: exit and cd
    Execute non-built-in commands using the appropriate EXEC(3) function.

    Implement redirection operators ‘<’,  ‘>’ and '>>'
    Implement the ‘&’ operator to run commands in the background

    Implement custom behavior for SIGINT and SIGTSTP signals

Learning Outcomes

After successful completion of this assignment, you should be able to do the following

    Describe the Unix process API (Module 4, MLO 2)
    Write programs using the Unix process API (Module 4, MLO 3)
    Explain the concept of signals and their uses (Module 5, MLO 2)
    Write programs using the Unix API for signal handling (Module 5, MLO 3)
    Explain I/O redirection and write programs that can employ I/O redirection (Module 5, MLO 4)
