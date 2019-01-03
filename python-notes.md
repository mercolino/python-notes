# Python Training
## Module 1
### Your First Program
#### What happens when Python encounters a Function?
  1. Python Checks if the name of the function is valid
  2. Python Checks the function's requirements for the arguments
  3. Python leaves your code and goes to the function
  4. Function Executes its code
  5. Python returns to your code and returns the data

#### How can you pas arguments to a function
  - You can pass arguments into a function with in the positional way, meaning that the assignment is dictated by its position
  - The other ways is by the keyword argument, this method use a keyword to identify the argument and it is not related to the position
  - You can mix them but, the keyword arguments should be placed **after** the positional arguments

#### Print Function
  - Print always include a newline character at the end of a string
  - If multiple arguments are passed separated with comma, a space is introduced between arguments and the output is delivered in one line
  - Print has two keyword arguments:
    - **end** this is the character that the print functions add to the string passed by default is "\n"
    - **sep** separator keyword, this will indicate the character used to separate multiple arguments if they are passed, by default is "\s"

### Python Literals
A literal is data whose values are determined by the literal itself i.e. "123" = One Hundred and twenty three (123)

#### Literals - integers
11111111 == 11_111_111

0o == Octal [0-7]

0x == Hexadecimal [0-9, 10(A), 11(B), 12(C), 13(D), 14(E), 15(F)]

#### Literals - floats
The decimal point is essentially important in recognizing floating=point numbers in Python
0.4 == .4

4.0 == 4.

3E8 == 300000000

3.0E8 == 300000000.0

#### Literals - strings
"st'ring" == str'ing

'str"ing' == str"ing

"str\"ing" == str"ing

'str\'ing' == str'ing

#### Literals - boolean values
True --> Note the uppercase T
False --> Note the uppercase F

### Operators - data manipulation tools
Operators = + - * / // % **

#### Arithmetic operators - exponentiation
2**3 --> Base == 2 , Exponent == 3, 2 to the power of 3
2**3 --> the result is an integer
2.\**3, 2\**3., 2.\**3. --> The result is a floating point

### Arithmetic operators - multiplication
If both numbers are integer then the result is integer
If on of the numbers is a float then the result is a float

#### Arithmetic operators - division
All the divisions done with (/) will throw a type float result

#### Arithmetic operators - integer division
The divisions done with (//) will return an integer if both operands are integer, if not will return float
But the result will be only the integer part of the result, i.e. 6/4 == 1.5, 6//4 == 1, 6.//4 == 1.0
It will round to the lesser integer i.e. 6//4 == 1 but -6//4 == -2

#### Arithmetic operators - remainder
Also called modulo is the remainder after the integer division

### Arithmetic operators - addition
Addition between integers will give an integer as a result, if one of the operands is a float then the result will be a float

## Unary vs binary operatos
Unary are operators that affect one argument, binary affects two arguments. i.e. -2 (unary), 2-1 (binary)
