# 0x03. Shell, variables and expansions

This project is part of the ALX System Engineering & DevOps curriculum. It focuses on learning shell variables, expansions, and related concepts in Bash.

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

- What are the different types of shell variables
- How to create, update and delete shell variables
- What are the roles of the following reserved variables: HOME, PATH, PS1
- What are special parameters
- What is variable expansion
- What is command substitution
- What is arithmetic expansion
- How to manipulate the PATH environment variable
- How to create and use aliases

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- All your scripts will be tested on Ubuntu 20.04 LTS
- All your scripts should be exactly two lines long (`$ wc -l file` should print 2)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/bin/bash`
- A `README.md` file, at the root of the folder of the project, describing what each script is doing
- You are not allowed to use backticks, `&&`, `||` or `;`
- All your scripts must be executable

## Tasks

### 0. <o>
Create a script that creates an alias.

- File: `0-alias`

### 1. Hello you
Write a script that prints `hello user`, where user is the current Linux user.

- File: `1-hello_you`

### 2. The path to success is to take massive, determined action
Write a script that adds `/action` to the `PATH`. `/action` should be the last directory the shell looks into when looking for a program.

- File: `2-path`

### 3. If the path be beautiful, let us not ask where it leads
Write a script that counts the number of directories in the `PATH`.

- File: `3-paths`

### 4. Global variables
Write a script that lists environment variables.

- File: `4-global_variables`

### 5. Local variables
Write a script that lists all local variables and environment variables, and functions.

- File: `5-local_variables`

### 6. Local variable
Write a script that creates a new local variable.

- File: `6-create_local_variable`

### 7. Global variable
Write a script that creates a new global variable.

- File: `7-create_global_variable`

### 8. Every addition to true knowledge is an addition to human power
Write a script that prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE`, followed by a new line.

- File: `8-true_knowledge`

### 9. Divide and rule
Write a script that prints the result of `POWER` divided by `DIVIDE`, followed by a new line.

- File: `9-divide_and_rule`

### 10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath
Write a script that displays the result of `BREATH` to the power `LOVE`

- File: `10-love_exponent_breath`