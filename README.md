
  - README.md
  - 0x16. C - Simple Shell
  - AUTHORS (Oniyor Jr Ayinde, Akanni Ismail)
  - main.h (header file with function prototypes)
  - main.c (initializes the program with an infinite loop)
  - prompt.c (uses getline to read user input and manages an infinite loop with fork)
  - special_character (identifies special inputs like '/', 'exit', or 'env')
  - string.c (handles string operations such as length, writing, searching in directories, and concatenation)
  - cmd.c (locates the user-entered command)
  - execute.c (executes the command)

**Learning Objectives:**
- After completing this project, you should be able to explain the following without the need for external references:
  - Key figures in the design and implementation of the original Unix operating system.
  - The author of the first version of the UNIX shell.
  - The inventor of the B programming language, which directly preceded the C programming language.
  - The significance of Ken Thompson.
  - How a shell functions.
  - The concepts of PID (Process ID) and PPID (Parent Process ID).
  - Manipulating the environment of the current process.
  - Differentiating between a function and a system call.
  - Creating processes.
  - Understanding the three prototypes of the `main` function.
  - How the shell uses the PATH to locate programs.
  - Executing other programs with the `execve` system call.
  - Suspending process execution until one of its children terminates.
  - The meaning of EOF (end-of-file).

**Requirements:**
- **General Requirements:**
  - Allowed text editors: vi, vim, emacs.
  - Compilation on Ubuntu 20.04 LTS using gcc with specific compiler flags.
  - All files should end with a new line.
  - A mandatory README.md file at the project's root folder.
  - Code must adhere to the Betty style guidelines and will be checked using betty-style.pl and betty-doc.pl.
  - The shell should not have any memory leaks.
  - Limit of 5 functions per file.
  - Use system calls only when necessary.

**GitHub:**
- Each project group should maintain one project repository. It's essential to avoid having identical repository names in both collaborators' accounts.

**Output Requirements:**
- The program should produce the same output as the standard Unix shell (/bin/sh) and identical error output. The only difference is when an error is printed, the program's name should match argv[0].

**List of Allowed Functions and System Calls:**
- A list of permitted functions and system calls for implementation is provided.

**Compilation:**
- The shell can be compiled using the following command:
  ```
  gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
  ```

If you have any specific questions or need further assistance related to this project, please feel free to ask.
