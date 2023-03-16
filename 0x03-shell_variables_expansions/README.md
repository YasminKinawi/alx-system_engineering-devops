# 0x02. Shell, I/O Redirections and filters

## Learning Objectives
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

#### 0. \<o>
[Create a script that creates an alias.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/0-alias)

#### 1. Hello you
[Create a script that prints hello user, where user is the current Linux user.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/1-hello_you)

#### 2. The path to success is to take massive, determined action
[Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/2-path)

#### 3. If the path be beautiful, let us not ask where it leads
[Create a script that counts the number of directories in the PATH.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/3-paths)

#### 4. Global variables
[Create a script that lists environment variables.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/4-global_variables)

#### 5. Local variables
[Create a script that lists all local variables and environment variables, and functions.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/5-local_variables)

#### 6. Local variable
[Create a script that creates a new local variable.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/6-create_local_variable)

#### 7. Global variable
[Create a script that creates a new global variable.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/7-create_global_variable)

#### 8. Every addition to true knowledge is an addition to human power
[Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/8-true_knowledge)

#### 9. Divide and rule
[Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/9-divide_and_rule)

#### 10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath
[Write a script that displays the result of BREATH to the power LOVE](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/10-love_exponent_breath)

#### 11. There are 10 types of people in the world -- Those who understand binary, and those who don't
[Write a script that converts a number from base 2 to base 10.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/11-binary_to_decimal)

#### 12. Combination
[Create a script that prints all possible combinations of two letters, except oo.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/12-combinations)

#### 13. Floats
[Write a script that prints a number with two decimal places, followed by a new line.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/13-print_float)

#### 14. Decimal to Hexadecimal
[Write a script that converts a number from base 10 to base 16.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/100-decimal_to_hexadecimal)

#### 15. Everyone is a proponent of strong encryption
[Write a script that encodes and decodes text using the rot13 encryption. Assume ASCII.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/101-rot13)

#### 16. The eggs of the brood need to be an odd number
[Write a script that prints every other line from the input, starting with the first line.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/102-odd)
  
