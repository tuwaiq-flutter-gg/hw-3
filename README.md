# Homework 3

Explain each subject below, and provide at least one example.

## Main and Print  
Main is the first method that will run in the program.\
Ex: 
```dart
void main() {
  
}
```
Print is the method that is used to display anything on the screen.\
Ex: 
```dart
void main() {
  print("hello dart");
}
```
## Syntax
it's the rules that you should respect when you are writing your program.\
Ex: in dart, you should put semicolon after any instruction.

## Data Types 
an attribute associated with a the data that tells the computer how to interpret its value.\
Ex: the data type in dart could be:
1. numbers (num, double, and int)
2. string (String)
3. boolean (bool)
4. list (List)
5. map (Map)

## Variable  & Const
- Variable is the place that can be changed during the program.
  Ex: your age. age should increase over the years.
- Const is the place that can not change during the program, when you assign a value to it, you can't change it.
  Ex: your birthdate.

## String interpolation 
it's a way to insert the expression value into placeholder.\
 Ex:
 ```dart
 int age = 5;
 print("my age is $age");
 ```

## Operators 
simply they are sets of symbols that are used to do some operation on the data.\
Ex: there are types of operators like:
- Arithmetic Operators (+, -, *, ~/, /, .....)
- Relational Operators (>, >=, <, <=, ==,!=, )
- Type Test Operators  (is, is not)
- Bitwise Operators    (%, |, ^, ~, >>, <<)
- Assignment Operators (=, +=, ..... )
- Logical Operators    (&&, ||, !)
- Conditional Operator (? ; , ??)
- Cascade Notation Operator (..)

## Null Safety
null safety use to ensure there are no null data type errors at the run time.
Ex: if your method expects an integer but it recevies null. then it will be a run time error.
    but with null safety, the error will be at the compile time. the compiler will not let you make this error.
