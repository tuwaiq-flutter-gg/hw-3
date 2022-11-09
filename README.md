# Homework 3

Explain each subject below, and provide at least one example.

* Main and Print  

main: basically is the start point for program execution, or may call it entry point at run time.\
For example:
```
void main() { "Any function" } //Start point "main" function
```

print: a function to "print" or display a msg in the output.\
For example:
```
void main() {
    print('Salem'); // To print in the output "Salem" and it is inside the main function, which is "the start point"
}
```
* Syntax

هي القوانين او القواعد اللي تكوّن اوامر اللغة بطريقة معينة ومرتبة وتخلي الجهاز يقدر يقراها وينفذها.

For example:
```
var x = 1; // in Java script "Used to create variables"
cout << "Salem"; // in C++ "Used to print a msg" in this case, the msg is "Salem"
```
* Data Types

هي مجموعة من القيم او العمليات المسجلة, الداتا تايب تعطي الكمبايلر الطريقة اللي يستخدم فيها الداتا

For example:
```
String SF = "Salem Fahad"; //Text
int num = 999; //Numbers
etc...
```
* Variable  & Const

Const: القيمة الثابتة, اي بمعنى اذا سويت كونستنت ما راح تتغير قيمته بأي متغير اخر في الكود , طريقة تغييره فقط تكون يدوية اي انك تحتاج تغيرها بنفسك من الكود \
For example:
```
const x = 1; // js
```
Variable: قيم متغيره, تتغير قيمتها حسب الحالة او المدخل في الكود, وليست ثابتة القيمه مثل الكونستنت\
For example:
```
let x = 1; // js
```

* String interpolation 

هو تكنيك يخليك تستخدم قيم المتغيرات في السترينق\
For example:
```
int students = 22;
print('Flutter class has $students students.'); //The result will be: Flutter class has 22 students.`
```

* Operators 

سمبلز تستخدم للكمبايلر على شان يسوي مهام او معادلات معينة بطريقة معينة للقيم او المتغيرات\
مثال + للجمع و - للطرح\
و == للشرطية , يتأكد اذا كان اللي يمين السمبل يساوي اللي يساره\
و && للتاكد من ان الشرط اللي يمينها ويسارها كلها صحيحه\
etc...


* Null Safety

تستخدم النل سيفتي لتخطي اخطاء الـ Null\
في بعض المهام او الاوامر نستخدم متغيرات مالها قيمة وهذا يسبب الخطأ, ف النل سيفتي يخليك تتخطى هذا الايرور\
For example:
```
String? Flutter;
```
في حالة ان الكود استخدم المتغير اللي فوق, راح يشتغل البرنامج ويعطينا قيمته نول لأن المتغير ما انضافت له قيمة
