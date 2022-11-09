### MAIN & PRINT :

Main is a required function for all dart programs . there can be only one main and the execution begins with the main which means it's responsible for executing all user defined statement, functions and library functions.

#### Example:
```
void main() { 
  // main function body. everything here will be executed
}
```
To show what in the main, we need to write an important function as well, which is the print function .It is used to display the content on the screen.

#### Example:
```
void main(){
 print("my name is ...");
}
```
----------------------------------------------------------------------

### SYNTAX:

Syntax means the rules that control the structure of the symbols, punctuation, and words of a programming language.Without these rules it is impossible to write functioning code.

#### Example:
```
using the previous example 
void main(){
 print("my name is ...");
}
```
All dart programs must begin with main() followed by a left curly bracket ( { ) this convention indicates the start of the program. A right curly bracket ( } ) indicates the end.The print function (print) is called, followed by what is to print. The text to print must be surrounded by double quotation marks and enclosed in parentheses.All statements must end with a semicolon ( ; )

-------------------------------------------------------------------

### DATA TYPES:

Dart is a statically typed programming language. This means that variables always have a specific type and that type cannot change. Every variable have data type associated to it.
The built-in data types in dart :

- Numbers data type is used to hold the numeric values. Dart supports following numerical data types (integer -> represent 64 bit non-decimal number and can be used to store either signed and unsigned integer value . double -> represent a 64-bit (double-precision) floating-point numbers or numbers with larger decimal points).
#### Example:
```
integer -> int age = 22;
double  -> double size = 15.5;
```
- Strings data type is used to hold series or sequence of characters ,letters, numbers, and special characters .In Dart, string can be represented either using single quotes or double quotes
#### Example:
```
String msg= "hello ";
```
- Boolean data type is used to represent the truth values. It's commonly used in decision making statements
#### Example:
```
bool isValid = true;
```
- Lists data type is used to represent a collection of objects. it is an ordered group objects.List in dart synonymous to the concept of an array in other programming languages.
#### Example:
```
var listA = [1, 2, 3];
```
- Maps is an object that is used to represents a set of values as key value pairs. In Map, both keys and values can be of any type of object and each key can only occurs once, but the same value can be used multiple times.
#### Example:
```
var details = {'Usrname':'amjad','Password':'75jk@'};
```
- Runes is an integer representing a Unicode code point.
#### Example:
```
var laugh = '\u{1f600}';
in the output will see laughing emoji
```
- Symbols object used to refer an operator or identifier declared in a Dart program and it's commonly used in APIs that refer to identifiers by name, because an identifier name can changes but not identifier symbols.
#### Example :
```
Symbol for an identifier can be created using a hash (#) followed by the identifier name 
import 'dart:convert';

void main() {
   var symbol = #hope; // created symbol named #hope
   
    print(symbol);
}
```

in the output-> Symbol("hope")

--------------------------------------------------------------------

### VARIABLE  & CONSTANT

- Variables is an identifier used to refer memory location in computer memory that holds a value for that variable, this value can be changed during the execution of the program.

#### Example:

variables must be declared before they are used. Variables are declared using the var keyword followed by variable name that you want to declare.
```
var Size;
```
Dart is a type inferred language, you can optionally provide a type annotation while declaring a variable to suggest type of the value variable can hold
```
int Counter =5;
```
- Constants refers to an immutable values. Constants are basically literals whose values cannot be modified or changed during the execution of program.Dart prevents to change the values of a variable declared using the final or const keyword. A final variable can be set only once while const keyword represents a compile-time constant. The constant declared with const keyword are implicitly final.

#### Example:
```
const pi = 3.14; 
final max = 18;
  print(pi);
  print(max); 
```

Output:
3.14
18

-------------------------------------------------------------------

### STRING INTERPOLATION

process of evaluating a string containing placeholders, variables and interpolated expressions. When an interpolated string is evaluated the placeholders, variables and expressions are replaced with their corresponding values.$ used for string interpolation.

#### Example:

```
void main()
{
    var name = "amjad";
    var age = 22;
    print("I'm ${name} I am ${age} years old");
}
```
Output:
I'm amjad I am 22 years old

----------------------------------------------------------------------

### OPERATORS

An operator is a special symbol that is used to carry out some specific operation on its operand.There are operators for assignment, arithmetic operations, logical operations and comparison operations etc. we can use them with many types of variables or constants, but some of the operators are restricted to work on specific data types. Most operators are binary, meaning they take two operands, but a few are unary and only take one operand.

- Arithmetic Operators : contain those operators which are used to perform arithmetic operation on the operands. They are binary operators.
Operator Symbol(+,-,-expr,*,/,~/,%)

#### One example:
```
int a = 2;
int b = 3;

    var c = a + b;
    print("Sum of a and b is $c");
```
Output:

Sum of a and b is 5

- Relational Operators : contain those operators which are used to perform relational operation on the operands.
Operator Symbol(>,<,<=,>=,==,!=)

#### One example:
```
int a = 2;
int b = 3;

    var c = a > b;
    print("a is greater than b is $c");
```
Output:

a is greater than b is false

- Bitwise Operators : contain those operators which are used to perform bitwise operation on the operands.
Operator Symbol(&,|,^,~,>>,<<)

#### One example:
```
int a = 5;
int b = 7;
 
    // Performing Bitwise AND on a and b
    var c = a & b;
    print(c);
```
Output:

5

- Assignment Operators : contain those operators which are used to assign value to the operands.
Operator Symbol(=,??=)

#### One example:
```
int a = 5;
int b = 7;
 
    // Assigning value to variable d
    var d;
    d ? ? = a + b; // Value is assign as it is null
    print(d);
```
Output:

12

- Logical Operators : contain those operators which are used to logically combine two or more conditions of the operands.
Operator Symbol(&&,||,!)

#### One example:
```
int a = 5;
int b = 7;
 
    // Using And Operator
    bool c = a > 10 && b < 10;
    print(c);
```
Output:

false

-----------------------------------------------------------------------

### NULL SAFETY

variable cannot contain a 'null'value unless you initialized with null to that variable. With null safety, all the runtime null-dereference errors will now be shown in compile time.

#### Example:
```
class FoodMenu {
String FoodName = "burgar";
}
 
void main() {
   FoodMenu foods;
  print(foods.FoodName);
}
```
But when we run the above code, an error occurs.
Error: Non-nullable variable 'foods' must be assigned before it can be used.

To solve this problem:
```
class FoodMenu {
String FoodName = "burgar";
}
 
void main() {
   FoodMenu foods= new FoodMenu();
  print(foods.FoodName);
}
```
Output : burgar