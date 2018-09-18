# Welcome to SmartLamps Lesson 2

# Today we will look at _data types_

#### Let's get started. 

At the terminal (screen on the right), type python3.6

#### :: _What we type_ ::
```
> python3.6
```
and press the return/enter key!
        
Output on the screen will look something like this:

#### :: _What terminal outputs_ ::
```
Python 3.6.5 (default, Mar 29 2018, 03:28:50)
[GCC 5.4.0 20160609] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

They symbol >>> means that python is ready to read, interpret and execute our commands. 

------------------------------------------------------------

#### Python can tell us the data type!

We saw that python classifies values into different data types. To find the data type of a value, we use a command that is called **type**

#### Data Type 1: String

The syntax for using the **type** command is given below. 
Enter the **type** command in the terminal on your right and press enter key to see what the computer outputs!

#### :: _What we type_ ::
```
>>> type("Hello World!")
```
#### :: _What terminal outputs_ ::
```
<class 'str'>
```

* "Hello World!" belongs to a class of data type called **'String'** ('str' for short). 

* It consists of a string of characters containing alphabets, numbers, special characters (like space, * % @ # !) etc. 

* To indicate that a value is a string, it is enclosed within quotes " ". Eg. "Hello World!", "R2D2", "1234", "50-50", "100%", "$25". 

* Even numbers inside quotes " " will be treated as Strings. Try the command below and check it out for yourselves!

#### :: _What we type_ ::
```
>>> type("1234")
```
#### :: _What terminal outputs_ ::
```
<class 'str'>
```

Important: If string datatype is NOT enclosed in quotes. You will get an error message! Eg. if we enter the following command: 

```
>>> type(Hello)
```

As there are no quotes, the computer doesn't know the data type! So it will say there is an error. In this case, the error is called NameError. We will look at more errors (and how to avoid them!) as we go. 

```
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'Hello' is not defined
```
Can you fix this error? (Hint: Always enclose strings within quotes " "!)

------------------------------------------------------------

#### Data Type 2: Integer

* Numbers without a decimal point are called **'Integer' datatype** ('int' for short).  Eg. 1234, 4321, -123

* Important: do not enclose the numbers inside quotes, because remember anything inside a quote is a string!

* Only + and - symbols are allowed before the numbers in Integer type. Try the following:

Enter the **type** command in the terminal on your right and press enter key to see what the computer outputs!
#### :: _What we type_ ::
```
>>> type(1234)
```
#### :: _What terminal outputs_ ::
```
<class 'int'>
```

#### :: _What we type_ ::
```
>>> type(-1234)
```
#### :: _What terminal outputs_ ::
```
<class 'int'>
```

Adding other symbols like 50%, $2 will give us an error called the syntax error! 

Try the following:

#### :: _What we type_ ::
```
>>> type($50)
```
#### :: _What terminal outputs_ ::
```
  File "<stdin>", line 1
    type($50)
         ^
SyntaxError: invalid syntax
```
Can you fix this error? (Hint: Remove any symbols!)

-------------------------------------------------------


#### Data Type 3: Floating point

* Numbers with a decimal point are called **'floating point' datatype** ('float' for short). Eg. 12.34, 123.4, -1.234 

Try the following: 

#### :: _What we type_ ::
```
>>> type(1.234)
```
#### :: _What terminal outputs_ ::
```
<class 'float'>
```
* Important: do not enclose the numbers inside quotes, because remember anything inside a quote is a string! 

* Only + and - symbols are allowed before the numbers in Floating type. Do not add any symbols others like 5.0%, $2.2.

------------------------------------------------------------

#### Can you find out the data type?

Can you name the data type of the following? Use type command in the terminal to see if you got it right!

* 'Hi There!'

* 3.14

* 'pi'

* -1000

------------------------------------------------------------

#### Can you fix the errors in type command?

Enter the following commands in the terminal and see what errors you get. Can you fix the errors?

```
>>> type(YES)

>>> type(20%)

>>> TYPE("ABCD")

>>> type ("EFG)

>>> type "ab12"

>>> typ ("Apple")

>>> type -3.14)
```

__Hints:__ 
1) Check whether command **type** is spelled correctly! It should be all small letters and there should be no capital letters in the command. 
2) Check whether **type** command is followed by open bracket ( and the end of the command has close bracket )
3) Check whether strings are enclosed in quotes " ". There should be open quotes at the beginning of the string and close quotes at the end. 
4) Check whether integer/floating points have only numbers and no special characters. 
