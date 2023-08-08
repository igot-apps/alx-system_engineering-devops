# Bash Script Collection

This repository contains a collection of Bash scripts that demonstrate various concepts and functionalities. Each script is named according to its purpose and includes a brief description. You can use these scripts to learn more about Bash scripting and experiment with different commands.

## Scripts

### 0-alias

This script creates an alias named `ls` with the value `rm *`.

### 1-hello_you

Prints a personalized greeting using the `echo` command and the `$USER` environment variable.

### 2-path

Adds a new directory (`/action`) to the `PATH` environment variable.

### 3-paths

Counts the number of directories in the `PATH` environment variable.

### 4-global_variables

Prints all global environment variables using the `printenv` command.

### 5-local_variables

Prints all local variables using the `set` command.

### 6-create_local_variable

Creates a local variable named `BEST` with the value "School".

### 7-create_global_variable

Attempts to print the sum of a global variable `$BEST` and the string "School" (Note: This script might not behave as expected).

### 8-true_knowledge

Attempts to print the value of a global variable `$TRUEKNOWLEDGE` incremented by 128 (Note: This script might not behave as expected).

### 9-divide_and_rule

Attempts to print the result of dividing the values of global variables `$POWER` and `$DIVIDE` (Note: This script might not behave as expected).

### 10-love_exponent_breath

Attempts to print the result of raising the value of the variable `$BREATH` to the power of `$LOVE` (Note: This script might not behave as expected).

### 11-binary_to_decimal

Attempts to convert a binary value stored in the variable `$BINARY` to decimal.

### 12-combinations

Generates combinations of two letters from the alphabet, excluding "oo".

### 13-print_float

Prints a list of floating-point numbers stored in the variable `$NUM`, formatted to two decimal places.

### 100-decimal_to_hexadecimal

Converts a decimal value stored in the variable `$DECIMAL` to hexadecimal.

### 101-rot13

Performs the ROT13 cipher on input text.

### 102-odd

Prints only the lines with odd line numbers from input using Perl.

### 103-water_and_stir

Attempts to decode encoded text from variables `$WATER` and `$STIR` into a meaningful word (Note: This script might not behave as expected).

## Note

Please be cautious when using some of these scripts, as they might contain unintended or erroneous behavior. They are meant for educational purposes and experimentation.
