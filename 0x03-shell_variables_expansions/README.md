# 0x03. Shell, init files, variables and expansions

## Learning Objectives:bulb:

* What happens when you type $ ls -l *.txt
* What are the /etc/profile file and the /etc/profile.d directory
* What is the ~/.bashrc file
* What is the difference between a local and a global variable
* What is a reserved variable
* How to create, update and delete shell variables
* What are the roles of the following reserved variables: HOME, PATH, PS1
* What are special parameters
* What is the special parameter $??
* What is expansion and how to use them
* What is the difference between single and double quotes and how to use them properly
* How to do command substitution with $() and backticks
* How to perform arithmetic operations with the shell
* How to create an alias
* How to list aliases
* How to temporarily disable an alias
---

### [0. `<o>`](./0-alias)
* Create a script that creates an alias.


### [1. Hello you](./1-hello_you)
* Create a script that prints hello user, where user is the current Linux user.


### [2. The path to success is to take massive, determined action](./2-path)
* Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.


### [3. If the path be beautiful, let us not ask where it leads](./3-paths)
* Create a script that counts the number of directories in the PATH.

### [4. Global variables](./4-global_variables)
* Create a script that lists environment variables.


### [5. Local variables](./5-local_variables)
* Create a script that lists all local variables and environment variables, and functions.


### [6. Local variable](./6-create_local_variable)
* Create a script that creates a new local variable.

### [7. Global variable](./7-create_global_variable)
* Create a script that creates a new global variable.


### [8. Every addition to true knowledge is an addition to human power](./8-true_knowledge)
* Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.


### [9. Divide and rule](./9-divide_and_rule)
* Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.

### [10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath](./10-love_exponent_breath)
* Write a script that displays the result of BREATH to the power LOVE

### [11. There are 10 types of people in the world -- Those who understand binary, and those who don't](./11-binary_to_decimal)
* Write a script that converts a number from base 2 to base 10.


### [12. Combination](./12-combinations)
* Create a script that prints all possible combinations of two letters, except oo.


### [13. Floats](./13-print_float)
* Write a script that prints a number with two decimal places, followed by a new line.


### [14. Decimal to Hexadecimal](./100-decimal_to_hexadecimal)
* Write a script that converts a number from base 10 to base 16.

### [15. Everyone is a proponent of strong encryption](./101-rot13)
* Write a script that encodes and decodes text using the rot13 encryption. Assume ASCII.


### [16. The eggs of the brood need to be an odd number](./102-odd)
* Write a script that prints every other line from the input, starting with the first line.

### [17. I'm an instant star. Just add water and stir.](./103-water_and_stir)
* Write a shell script that adds the two numbers stored in the environment variables WATER and STIR and prints the result.


### [18. Life is a series of commas, not periods](./103-commas)
* Write a command that lists all the files and directories of the current directory, separated by commas (,).


### [19. File type: School](./school.mgc)
* Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
