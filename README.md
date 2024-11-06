JAVASCRIPT :- 

- Javascript is used for building logics of a web page. 
- javascript is a high level programming language, used in both client side as well as server side. 
- javascript comes from echma script so we see the latest version of javascript in the form of echma script. 
- Now we used javascript version 6 i.e ES6 (echma script 6)
- In another way we called ES6 as the vanilla Javascript.
- Node JS is the run time environment of javascript. 

Variable :- 

- variable is a container to store some data.
- in javascript there are 3 types of variable are there...

1. var :-

- var is a type of variable which is used for changing the variable in later stage. 
- var is used in oldest browser so now a days we are don't use var most of the cases. 

2. let :- 

- let is a type of variable which is also used for changing the variable in later stage.
- Now these days, most of the cases we used let for changing the variable.
- let is a block scope code so we have been used let in most cases. 

3. const :- const means constant. 

Rules for creating variable name :- 

- variables names are case sensative "a" & "A" is different.
- Only letter, digits, underscore & special character is allowed. (do not keep white space over here).
- only letter, underscore or special character should be the 1st character only. 
- reserved words cannot be a variable name. 
ex. for, while, var , let, this, boolean etc... 

Datatype in Javascript :- 

- datatypes is an attributes associated with a peice of data that tells a computer system how to interprit its value. 
- in datatype we used "typeof" operator to know what type of data it is. 
- mainlly in javascript there are 2 type of datatypes are there. 

1. primitive Datatype :- 

- in javascript there are 7 types of primitive datatypes are there like..

1. Number - Numbera re the type of datatypes those it contains some numerical values
2. Boolean - in boolean datatype we got boolean value like true/false
3. Undefiend - data is not define
4. Null - in this datatype we got null for the value means nothing
5. bigInt - in bigint we will get the big integer value (-999999999 to +999999999) on the above.
6. String - string is a type of datatype that can hold some character like names or words etc.. 
7. Symbol - in symbol we got one symbol of more than one value.

2. Reference Datatype

- reference datatypes are the type of datatype which can hold multiple element in a single frame.
- reference datatypes are -> array, object, function

1. Array :- 

- Array is a coolection of similar type of datatype which can hold contigious memory location. 
- array indexing start from "0".

ex. let arr = ["hari", "sita", "ram"]
                 0        1       2

2. Object :- 

- object is a reference type of datatype where we can store more then one element is a single frame. 
- mainly object are working on (key:value) pair.

ex:- 

let hari = {
    "name" : "hari bandu sahoo",
    "phone no" : 56789032,
    "address" : "bhubaneswar",
    "carrier" : "good"
}

- in the above example left side element are the keys & right side elements are the values of that key.


3. FUNCTION:-

- In function, we repeatedlly do the task in a function.
- Function reduce our code complexity and time & space complexcity.
- Syntax :-


function:->

function my_schedule(){
    console.log("we woke up at 6 am");
    console.log("we go for a morning walk");
}

function calling:->

my_shedule();

Operator in JS:-

- Operator are the key features to do some task or operate some task.
- ex. A + B
- In the above example A & B are the operands, "+" is our operator.
- In javaScript, there are 5 types of operator they are...


1. Arithmatic operator ->(+,-,*,/),%(modulus),**(expnent)
2. assignment Operator ->(=,+=,-=,*=,/=,%=,**=)
3. Comparision Operator ->(==,!==,===)
4. Logical Operator -> Logical AND(&&), Logical OR(||), Logical NOT()
5. Unary Operator


logical AND

A  B  AND(&&)
T  T     T
T  F     F
F  T     F
F  F     F


logical OR(||)

A  B  OR(||)
T  T     T
T  F     T
F  T     T
F  F     F

conditional statement:-

- To implement some condition in the code.
- There are 3 types of conditional statements they are 

1. if condition :-

- if condition is true then statement is true.
- syntax :-
  if(condition){
    statement
  }


2. if-else condition:-
 
- if condition is true then statement is true otherwise false.
- syntax:-
 if(condition){
    statement
 }else {
    statement
 }

3. if-elif condition or switch condition:-

- it checks the condition multiple times, where the condition is true , it returns the syntax.
- in else if case else condition is the default condition so if the condition doesn't satisfy any of the case yhen he print the default condition
- syntax:-
  if (condition){
    statement
  }else if(condition){
    statement
  }else if (condition){
    statement
  }else{
    statement
  }

practice task:-

write a code which can give grades to student according to their score.
1. 80-100(A)
2. 70-79(B)
3. 60-69(C)
4. 50-59(D)
5. 0-49(fail - go for aganwadi)


Loops in JavaScript:-

- loops are used to execute a pice of code again and again.
- There are 5 types of loops are there 
1. For loop:-

- syntax:- 
for(initialization; condition; updation;){
  statement
}

ex. - we want to print "Web Bocket" 5 times,

for(let i= 1; i<= 5; i++){
  console.log("Web Bocket")
}

working :-


i = 1 -> web bocket
i = 2 -> web bocket
i = 3 -> web bocket
i = 4 -> web bocket
i = 5 -> web bocket


2. While loop:-

-syntax:-
initialize;
 while (condition){
  statement;
  update;
 }

 ex -> Print "GIFT" 5 times in while loop

 let i = 1
 while (i <= 5){
  console.log("GIFT");
  i++;
 }


3. Do-while loop:-

- syntax:-

initialize;
do{
  statement;
  updation;
} while(condition)

4. For-of loop:-
- it iterates on String & Array

5. For-in loop:-
- it iterates on Objects

<!-- ex. 
let i = hari

let arr = ["sita", "hari", "bibhu", "ram"] -->