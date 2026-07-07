---
tags:
  - course
  - shell
  - command_line
status: Completed
start_date: 2026-06-25
end_date: 2026-07-03
course_url: https://www.datacamp.com/courses/introduction-to-shell
level: Basic
prerequisites: None
---

# Course: Introduction to Shell

# 1. Summary & Goals

The Unix shell provides a text-based interface for navigating a filesystem, inspecting and transforming data, combining small programs, automating repeated work, and turning command sequences into reusable tools.

## Course Promise

Build a working mental model of how the shell interprets commands, paths, inputs, outputs, variables, loops, and scripts so that filesystem and data-processing tasks can be performed efficiently and combined safely.

## Learning Goals

- Navigate, inspect, create, move, rename, copy, and remove files and directories.
- View, filter, and manipulate text data with core Unix command-line tools.
- Control command behavior with options, arguments, help systems, and command history.
- Connect commands through redirection, pipes, wildcards, sorting, and duplicate removal.
- Use variables and loops to process collections of files.
- Save command sequences as shell scripts and pass filenames or other arguments into them.

## Course Format

This course is organized around interactive exercises rather than videos. Exercise snapshots will be grouped into conceptual preparation sessions; an individual exercise is not automatically treated as a separate learning unit.

---

# 2. Core Concepts & Notes

## Chapter 1: Manipulating files and directories

_Establish the shell as an interface to the operating system, then learn how the current working directory and filesystem paths control where commands act. Practice identifying, navigating, creating, copying, moving, renaming, and deleting files and directories._

- [[Shell Filesystem Context and Operations]]

## Chapter 2: Manipulating data

_Move from managing filesystem objects to reading and selecting the data stored inside files. Use command options, built-in help, history, and foundational text-processing tools to inspect files, select columns, and filter lines._

- [[Shell Commands, Flags, and Arguments]]  
- [[Shell Text Selection and Data Semantics]]

## Chapter 3: Combining tools

_Use standard input and output as connection points between commands. Build multi-step transformations with redirection and pipes, address groups of files with wildcards, and organize textual results with counting, sorting, and duplicate removal._

- [[Shell Redirection and Pipeline Dataflow]]  
- [[Shell Wildcards and Filename Expansion]]  
- [[Sort and Uniq in Shell Pipelines]]

## Chapter 4: Batch processing

_Extend single-command pipelines to repeated work over many files. Learn how shell and environment variables store information and how loops bind one item at a time so the same command sequence can process a collection._

- [[Shell Variables, Expansion, and Argument Boundaries]]  
- [[Shell For Loops and Per-Item Command Execution]]

## Chapter 5: Creating new tools

_Turn successful interactive commands and pipelines into reusable shell scripts. Edit and save command sequences, accept command-line arguments, combine several operations, and place loops inside scripts._

- [[Shell Scripts and Reusable Command Execution]]  
- [[Shell Script Arguments and Positional Parameters]]  
- [[Command-Like Shell Script Workflows]]

---

# 3. Key Takeaways & Reflections

- **Everything covered in this course:** [[Introduction to Shell - Major Takeaways]]
- **Cheat Sheet:** [[Introduction to Shell - Cheat Sheet]]

---

# 4. Related Projects & Applications

- **Exercises:** [[Introduction to Shell - Exercise Plan]]
