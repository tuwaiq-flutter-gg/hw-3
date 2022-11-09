# Homework 3 Answers

Explain each subject below, and provide at least one example.

* Main and Print  
* Syntax
* Data Types 
* Variable  & Const 
* String interpolation 
* Operators 
* Null Safety

---

1.**Main**\
The main function its an important function, which is the starting point to run the program, and it is the programmatically recognized method in all programming languages, and it is responsible for implementing all libraries and functions.\
``void main() { 
print(“Sarah”);
}``*Output:Sarah*


2.**Print**\
It is a print function, showing us the content it's include it between parentheses.\
`Print(“Hello Everyone!”);`*Output:Hello Everyone!*

3.**Syntax**\
Every programming language has a specific syntax and rules that depend on it. and to use the dart language we must learn The dart syntax.\
`void main(){
    bool  red = false;
    String y="Yes";
    String n="No";
    red? print(y) : print(n);
}`*Output: No*

4.**Data Types**\
We have several types of data in Dart language.
| Data Type | Example |
|-----------|---------|
| Number    | `int door = 4;` , `double a = 5.10;`|
| Strings   | `String name ="Sarah";`|
|Booleans   | `bool  isChecked = false;`|
|Lists      | `List number = [1,2,3];`|
| Maps      | `Map c = {'A':'1','B': 2, 'C': true};`|
| set |    `Set months = {'Jan','Feb','Mar','Apr'};`| 

5.**Variable**\
A value that takes space of memory and we can change the value every time.\
`void main(){
    String a ="Sarah";
    String b = "Gala";
    a = b;
    print(a);}`
    *Output:Gala*
    
 6.**Const**\
 Makes the value constant and cannot be changed. It can only be edit by the owner of the program "Programmer".\
 `const int size = 10;`
 
 7.**String interpolation**\
 Instead of repeating the print function, we can put the strings and variables in one print function sequentially.\
 `void main(){
    String s="Sarah";
    String l = "Abdulrahman";
    const int size = 2;
    print("Hello I'm ${s}\t${l}\n${size}");
}`*Output: Hello I'm Sarah	Abdulrahman\2*

8.**Operators**\
There are several types of operators, which are used to achieve a results.
and here below we have the different types of the Operator.\

-Arithmetic Operators
|Operator | Example|Output|
|---------|--------|------|
| Add +   | `void main(){int a = 5; int b = 10; print("A + B = ${a+b}");}`| A + B = 15 |
|Subtraction -| `void main(){ int a = 5; int b = 10; print("A - B = ${a-b}");}`|A - B = -5|
|Divide / | `void main(){ int a = 5; int b = 10; print("A / B = ${a/b}");}`| A / B = 0.5 |
|Multiplication | `void main(){ int a = 5; int b = 10; print("A * B = ${a*b}");}`| A * B = 50 |
|Modulus %        | `void main(){ int a = 5; int b = 10; print("A % B = ${a%b}");}`| A % B = 5 |


-Relational Operators
|Operator | Example| Output |
|---------|--------|-------|
|>        |`void main(){ int a = 5; int b = 10; print("A > B = ${a>b}");}`| A > B = false |
|<        |`void main(){ int a = 5; int b = 10; print("A < B = ${a<b}");}`|A < B = true |
|>=       |`void main(){ int a = 5; int b = 10; print("A >= B = ${a>=b}");}`| A >= B = false|
|<=       |`void main(){ int a = 5; int b = 10; print("A <= B = ${a<=b}");}`|A <= B = true|
|==       |`void main(){ int a = 5; int b = 10; print("A == B = ${a==b}");}`| A == B = false|
|!=       |`void main(){ int a = 5; int b = 10; print("A != B = ${a!=b}");}`|A != B = true|



-Test Operators
|Operator | Example|Output|
|---------|--------|------|
|is       | `void main(){int a = 5; int b = 10; print(a is int);}`|true|
|is!      | `void main(){int a = 5; int b = 10; print(a is! int);}`|false|

-Bitwise Operators
|Operator | Example| Output| Note|
|---------|--------|-------|-----|
| AND &| `void main(){ int a = 8; int b = 14; print("A & B = ${a&b}");}`|A & B = 8| - |
| OR | `void main(){ int a = 8; int b = 14; print("A / B = ${a/b}");}`|A / B = 14 |The sign of OR opreator mess up the table i replace it by this sign /|
|XOR ^ | `void main(){ int a = 8; int b = 14; print("A ^ B = ${a^b}");}`|A ^ B = 6| -|
| NOT ~a| `void main(){ int a = 8; print("~A = ${~a}");}`| ~A = -9 | -|
|Left shift <<| `void main(){ int a = 8; int b = 14; print("A << B = ${a<<b}");}`| A << B = 131072| - |
|Right shift >>| `void main(){ int a = 8; int b = 14; print("A >> B = ${a>>b}");}`|A >> B = | - |

-Assignment Operators
|Operator | Example|Output|
|---------|--------|------|
| = |`void main(){int a = 2; print ("A=2 = ${a=2}");}`|A=2 = 2|
|+=|`void main(){int a = 2; print ("A+=2 = ${a+=2}");}`| A+=2 = 4|
|-=|`void main(){int a = 2; print ("A-=2 = ${a-=2}");}`| A-=2 = 0|
|Multiplication=|`void main(){int a = 2; print ("A*=2 = ${a*=2}");}`|A*=2 = 4
|/=|`void main(){double a = 2; print ("A/=2 = ${a/=2}");}`| A/=2 = 1.0|
|~/=| `void main(){int a = 2; print ("A~/=2 = ${a~/=2}");}`| A~/=2 = 1|
|%=| `void main(){int a = 2; print ("A%=2 = ${a%=2}");}`| A%=2 = 0 |
|<<=|`void main(){int a = 2; print ("A<<=2 = ${a<<=2}");}`| A<<=2 = 8|
|>>=|`void main(){int a = 2; print ("A>>=2 = ${a>>=2}");}`| A>>=2 = 0|



-Logical Operators
|Operator | Example|Output| Note|
|---------|--------|-----|------|
| AND &&  |`void main(){  bool a = true; bool b = false; print(a && b);}`|false| Nothing here :) |
| OR   |`void main(){  bool a = true; bool b = false; print(a // b);}`|true | The sign of OR opreator mess up the table i replace it by this sign /|
| Not !   | `void main(){  bool a = true; bool b = false; print(!(a // b));}` |false| The sign of OR opreator mess up the table i replace it by this sign /|



9.**Null Safety**\
Don't allow the variable to be empty"null". but when we adding this sign "?" after the variable type ,The variable will be saved the null until we Assigned him a value.\
`void main(){
   int? a;
   print(a);
}`*Output=null*
