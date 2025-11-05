### PART-1

###### =>Introduction

###### =>Java

###### =>Tokens

###### =>Datatype

###### =>Variables

###### =>Operator

###### =>Decision Statement

###### =>Loops

###### =>Methods

###### =>Method Overloading

###### =>Recursion

==================================================================================

#### 1)What is JAVA? Tell me the Advantages?



==java is a high level programming language which supports the OOPs principals like Encapsulation, Inheritance ,Polymorphism, Abstraction.



\#### \\\*Advantages of JAVA:



1)is a simple language



2)Structured language



3)oops



4)Robust



5)Platform independent



6)Multi-threads



7)Secure language



8)rich built-in class

==================================================================================

#### 2)How java is a platform-independent?

==>java is 2-steps compilation language where java compiler converts Source file into class file.



=>The instruction inside the class file will be present in an intermediate level language known byte code.



=>The bytecode is understandable only by the machine which has the JVM(java virtual machine).



=>JVM read the instruction and executes them with respective machine by converting the instruction into machine understandable language hence java is a platform independent but depends on jvm.

===================================================================================

#### 3)Can we create a class and compile without main method?

=YES, we can compile without main method.

===================================================================================

#### 4)Can we run/execute a program without main method?

=NO, bcz in java the execution starts from main method itself.

==================================================================================

#### 5)Difference between println and print Statement?

= 1)System.out.println();=>



--it will print the data first and move the cursor to the "next line" initial position



--we can use println statements without passing the data



--ex:system.out.println("hi");



System.out.println("java");



hi



java



 2)System.out.print();=>



--it will print the data first and then move the cursor to the "next position"



--we cant use print statement without passing the data



--ex:System.out.print("hi");



System.out.print("java");



hijava

===================================================================================

#### 6)What is Keyword?

=--are the predefined words which are known to the java complier.

--keywords are also called as reserved words.

--note:

\*)keywords must be in lowercase

\*)we cant use keyword for any other purpose

ex: class,public,static,void,try,if,while etc

===================================================================================

#### 7)What is Identifiers?Tell me the Rules of Identifiers?

=--identifiers is a name given by the programmer to the elements of the java.



\*\*Rules of identifiers:

--we cant starts with numerical values

ex:

class Demo1//CTS

class 1Demo//CTE

class Demo1Program//CTS

--we cant use special charaters otherthen $,\_

ex:

class Demo-Program//CTE

class Demo\_Program//CTS

class Demo?//CTE

--we cant provide the space in between the identifiers .

ex:

class Demo Program//CTE

class DemoProgram//CTS

--we cant use keyword as a identifiers

ex:

class public//CTE

class Public//CTS

===================================================================================

#### 8)What is Variables ?Syntax to declare an initialize?

=Variable: is a name given by the programmer to the container created.

\*to create variable we need:->

1)datatype

2)identifiers



\#Syntax to create variable:->

datatype identifiers;



\#Syntax to initialize a variable:->

variable Name=value/Expression;



\#Syntax to declare \& initialize a variable:->

datatype identifier=value/Exp;

====================================================================================

#### 9)Tell me the characters of Local variable?

=Local variable: a variable which is create in the local area.



\*\*Characteristics of local variable:->

1)local variable doesn't have the default value.

2)Before using the local variable we must initialize else we get compile time error.

3)local variable can be used within the block where it is declared, if we try to use outside the block we get error.

=====================================================================================

#### 10)Difference between Widening and Narrowing?

i)Widening:

->the process of converting smaller range datatype into larger range datatype is known as Widening.

->During widening there is no-data loss therefore it will happen implicitly hence it is called as Auto-widening.

ex: int a='A';

&nbsp;	System.out.println(a);//65



2)Narrow:

->the process converting larger range datatype into smaller range datatype is known as Narrow.

->there is chance of data loss so we have to do Explicitly, by using an Operator called Type-Cast-operator. 

ex:

int a=10.5;//CTE

System.out.println(a);

=======================================================================================================================

#### 11)what is Source file?

(i)Source file:



=A file inside which we write the instruction in HLL to develop an application is called source file.



=it is created by the programmer.



=ex:.java,.py,.MP3,.png,.txt,.pdf etc.

===============================================================================================================================

#### 12)what are the tokens?Explain each?

Tokens:

--tokens are the smallest elements in a program

--we have the following tokens:

1)keyword

2)identifiers

3)literals

4)seperators

================================================================================================================================

#### 13)what is datatype? Explain its type?

\*\*Datatype:

are used to specifies the size and type of the data that can be stored in a container known as datatype.

\*we have 2 types:->

1)Primitive datatype(Single value data)

2)Non-Primitive datatype(Multi-value data)

=================================================================================================================================

#### 14)what is primitive datatype? list all primitive datatype with default size?

Primitive datatypes:(8)

1)byte

2)short

3)int

4)long

5)float

6)double

7)char

8)Boolean

===============================================================================================================================================

#### 15)Explain type Casting? its types?

\*Typecasting:

=>The process of Converting one datatype into Another datatype known as Typecasting.

=>In java we have 2 types of Typecasting:

1)Primitive Typecasting

2)Non-Primitive typecasting

=================================================================================================================================================

#### 16)int a=10.5

#### i)CTS ii)CTE justify your answer

->CCTE because we cant pass decimal value to the int datatype

========================================================================================================================================================

#### 17)Difference between division and modules operator?

ii)Division Operator(/):

=>it is Binary Operator

=>it is used to get the Quotient value.



iii)Modules(%):

=>it is the Binary Operator

=>it is used to get the reminder value.

=======================================================================================================================================

#### 18)Difference between post and pre increment?

1)Post-increment Operator:

->Syntax: variable++

->first use the value then, increases the value of a variable by one.

ex: int a=15;

System.out.println(a++);//15

System.out.println(a);//16



2)Pre-increment Operator:

->Syntax: ++Variable

->first increases the value of a variable by 1 then,use the value.

ex: int a=15;

System.out.println(++a);//16

System.out.println(a);//16

=========================================================================================================================================

#### 19)Difference between post and pre decrement?

1)Post-decrement Operator:

->Syntax: variable--

->first use the value then, decreases the value of a variable by one.

ex: int a=15;

System.out.println(a--);//15

System.out.println(a);//14



2)Pre-decrement Operator:

->Syntax: --Variable

->first decreases the value of a variable by 1 then,use the value.

ex: int a=15;

System.out.println(--a);//14

System.out.println(a);//14

=========================================================================================================================================

#### 20)when we should use logical and ,logical or opert0r?



1)AND Operator:

->it is binary Operator

->whenever we need to satisfy multiple conditions to perform a task we use \&\& operator

->we can use \&\& Operator between the conditions that is between the Boolean value

->the return type is Boolean

ex: int a=10;

int b=20;

System.out.println(a>b \&\& ++a<b);//false

System.out.println(a);//10

System.out.println(b);//20



2)OR Operator:

->it is binary Operator

->whenever we need to satisfy any one of the condition to perform a task we use OR operator

->we can use or operator between the condition only

->The return-type is Boolean

->ex: int a=10;

int b=20;

System.out.println(a<b || ++a<b);//true

System.out.println(a);//10

System.out.println(b);//20

===============================================================================================================================================

#### 21)what is advantage of compound assignment operator?

->advantage: Narrowing done implicitly

===================================================================================================

#### 22)what are all the datatype we can pass to Switch statements?

->byte,int,short,string,char

====================================================================================================

#### 23)can we Overload main method?Explain

->yes, we can Overload main method

==========================================================================================================================

#### 24)what is the difference between else-if and Switch?

iii)else-if ladder:

->whenever we have more then 2 condition and it needs to execute any one of it, we use else-if ladder.

Syntax:

if(condition)

{

//java statements

}

else if(condition)

{

//java statements

}

else if(condition)

{

//java statements

}

else if(condition)

{

//java statements

}

---

else

{

//java statements

}



iv)Switch:

->when ever we need to take the decision based on the value we use switch statements.

Syntax:

Switch(value/Exp)

{

case(value/Exp):

{

//java Statements

}

case(value/Exp):

{

//java Statements

}

---

default:

{

//java statements

}

}

==========================================================================================================================

#### 25)what is method? Syntax to create a method?

\*Methods:

->is used to stored the behaviour of an object 

->method is a set of instructions or block of code to perform a specific task.

note: method get executed only when it is called

Syntax: \[Modifiers] returntype methodname(\[formal argument])

{

//implementation

}

================================================================================================================

#### 26)what is difference while and do-while loop?

while-loop:

->it is also called as Entry control loop

->0-iteration is minimum  possible



do-while loop:

->it is also called as exist control loop

->1-iteration is possible

=======================================================================================================================

#### 27)what is Overloading? rules to achieve it?

\*Method Overloading:

->in a class having multiple methods with the same name but change in formal Arguments is called as Method Overloading



\*Rules of Method Overloading:

1)no. of formal Argument should be different

2)Datatype should be different

3)Sequence of the datatype should be different



->we can satisfy any 1 rule among 3 rules.

============================================================================================================================

#### 28)Difference between return and return-type?

\*return:

->it is a keyword

->it is also known as control transfer statement

->return will destroy the frame and transfer the control back to calling method

note:return statement should be the last statement in a block else we get compile time error

ex: System.out.println("main begin");

return;//CTE

System.out.println("main end");



\*return-type:

->can a method return a value to its caller:

yes, we call return the following types of data/literals.

1)numericals

2)character

3)string

4)Boolean

->it is the type of value that we returning from the method

=====================================================================================================================================================================

#### 29)what is recursion? how can we stop it?

\*Recursion:

the process of method calling it self is known as Recursion

ex: class p1

{

public static void main(String\[] args)

{

System.out.println("main begin");

test();

System.out.println("main end");

}

public static void test()

{

System.out.println("test begin");

test();

System.out.println("test end");

}

}



\*\*Steps to stop infinite time Execution:

->create base condition,it is condition which is used to stops the execution

->if the condition is satisfied execute the return statement

========================================================================================================================================

#### 30)for( ; ;)

#### {

#### System.out.println("hi");

#### }

#### what is the output for above statement?

->hi

hi

hi

-----infinite times











