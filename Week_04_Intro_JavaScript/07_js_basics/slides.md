![GeneralAssemb.ly](../../img/icons/FEWD_Logo.png)

#FEWD - JS Basics

###Instructor Name

Instructors current role.

---


##Agenda

*	JS Basics (Syntax)
*	Variables
*	Arithmetic
*	Conditionals

---

##JS Basics Syntax

__Syntax:__ Spelling and grammar rules of a programming language. 


<aside class"notes>
Like with any language, there are formal rules around how to write it. This is the syntax.

</aside>

---

##JS Syntax

*	Semicolon
*	Brackets
*	Parentheses
*	Quotation Marks

---

![GeneralAssemb.ly](../../img/icons/code_along.png)
##JS Basics

---


##Variables

What are variables?

<aside class"notes>


</aside>

---


##Variables

*	We can tell our program to remember values for us to use later on. 

*	The action of saving a value to memory is called assignment

*	The entity we use to store the value is called a variable

---


##Variables

*	The action of getting the value from a variable is called accessing the variable

*	We will use all the above techniques to store values into variables, and generate new values using existing variables

---

##Variables Declaration

Declaration: ```var age;```

---

##Variable Re-Assignment

```var name = "Jo";```
```name = Amir;```

<aside class"notes>

name is now Amir.

</aside>

---

##Variable Conventions

*	Variables start with a lower case letter

		var numberOfStudents = 10;

---

##Variables & Data Types 

What can you store in a variables?


<aside class"notes>

</aside>


##Data Types

The types of different values we support include:
	
*	__String__ numbers
*	__int__, __float__ text
*	__Boolean__ true or false

---


![GeneralAssemb.ly](../../img/icons/code_along.png)
##Score Keeper

---

##Strings

*	Stores textual information

---

##Strings

Double vs single quoted strings:
---

##Strings


---

##Conversion: String To Number

```
var intString = "4";
Why would you need to convert datatypes?


---

##Conversion: Number To String

```
var number = 4;

__OR__

Why would you need to convert datatypes?


---

##Numbers

Represent numerical data

---

##Numbers

Signed

---


##Arithmetic In JavaScript

![](../../img/unit_1/arithmetic.jpg)

---


##Conditionals

![](../../img/unit_1/cfDiagram.png)

---

##Making Decisions

It's either TRUE or FALSE (like booleans)

If you are greater than 18 
you are an adult

	if (age > 18){
		puts "You are an adult"
	}

---



##Comparisons - Equality

Are two things equal?
10 === 10 //true
---


##Logical Operators

![](../../img/unit_1/logical_operators.png)

---

##Conditional Syntax

```
if(condition is true) {   
	//Do cool stuff }
```

---

##Conditional Syntax

```
	if(condition is true) {
		//Do cool stuff
	}else{
		//Do other cool stuff
	}	
```

---

##Conditional Syntax

```
	var topic = "JS";
```

---

##Multiple Conditions

```
if (name == “GA”  && password == “YellowPencil”){
```

---


##The Truth Table

```
if (name == “GA”  && password == “YellowPencil”){
```

---

##The Truth Table

![](../../img/unit_1/and_table.png)

---

##The Truth Table

```
if (day == “Tuesday”  || day == “Thursday”){
```

---

##The Truth Table

![](../../img/unit_1/or_table.png)

---

![GeneralAssemb.ly](../../img/icons/exercise_icon_md.png)
##Temp Converter

---

