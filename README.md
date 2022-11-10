# Homework 3

Explain each subject below, and provide at least one example.

* Main and Print  
* Syntax
* Data Types 
* Variable  & Const 
* String interpolation 
* Operators 
* Null Safety


- Main and Print

Main :
هي الوظيفة الرئيسيه المسؤله عن جميع انواع التنفيذ، تستخدم مرة واحدة .
Example:

Void main{

print(“hello”);

}
يبداء الكمبيوتر ب قراءة main وتنفيذ العمليات داخله 

Example2:

void main(){

print(“ hello’);

}

print(“HI “);

سوف تتم طباعة جملة hello ولن تتم طباعة hi لأنها خارج main  

Print :
تقوم print method بطباعة محتوياتها ، اذا كنت تريد طباعة نص او رقم يمكنك استخدام print

Example:

void main(){

print(“ hello “);

}

-Syntax

تحدد syntax مجموعة القواعد لكتابة البرنامج على سبيل المثال في لغة dart يجب ان ينتهي كل سطر برمجي بفاصلة منقوطة.


Example:

void main() {


var A = 2;
Var B = 3;


print( A + B );
}

ينتهي كل سطر برمجي ب فاصلة منقوطة


-Data Types

تصنيف يحدد نوع القيمة التي يمتلكها المتغير ونوع العمليات الحسابية او المنطقية التي يمكن تطبيقها بدون التسبب في خطاء

أمثلة انواع البينات:

String >>تمثل البينات النصية مثل الاحرف و النصوص
int>> تمثل الأعداد الصحيحة
Double >>تمثل الأرقام العشرية
Boolean>> true / false

Example :

var name = “ asma”;
مثال لمتغير من نوع string 

vae age = 23 ;
مثال لمتغير من نوع int

var number = 7.5;
مثال لمتغير من نوع double اسندت إليها قيمة عشرية



-Variable & Const

Variable:
هي مساحة في الذاكرة لها اسم و نخزن فيها القيم

Example:

void main(){

var name;
name = “asma”;

}
حجزنا مكان في الذاكرة بأسم name 
ثم اسندنا لها قيمة asma


Const:
هي نفس المتغيرات مساحة في الذاكرة نخزن فيها القيم لاكن لايمكن تغيير القيم المخزنه فيها

Example:

void main(){

const id = “12345678”:

}



-String interpolation

عملية وضع قيم المتغيرات في سلسلة حرفية

Example:

void main(){

var name =“Ahmad”:
var massage =“my name is $name”;

print( massage );

}


-Operators

هي العمليات الحسابية و المنطقية وعمليات المقارنه التي نستخدمها في البرمجة

عمليات المقارنة:

>         ترجع  true اذا كانت القيمة اليمنى اكبر من القيمة اليسرى
<         ترجع  true اذا كانت القيمة اليسرى اكبر من القيمة اليمني
>=       ترجع  true اذا كانت القيمة اليمنى اكبر من او يساوي القيمة اليسرى 
<=      ترجع  true اذا كانت القيمة اليسرى اكبر من  او يساوي القيمة اليمني
=!       ترجع قيمة true في حال كانت القيمة اليمنى لا تساوي القيمة اليسرى
==     ترجع true  في حال كان القيمة اليمنى تساوي اليسرى

Example:

var  x  = 5 > 2;

العمليات الحسابية:

+     عملية جمع
 -    عملية طرح
/     عملية قسمه
 *   عملية ضرب

Example:
  void main(){

var a = 3;
var b = 9;

var c = a + b ;
}


العمليات المنطقية:
 
||       or
And   &&   
    Not       ! 



-Null Safety

تمنع  null safety الأخطاء الناتجة عن القيم الفارغه

Example :

void main(){

 var name = null ;
}
