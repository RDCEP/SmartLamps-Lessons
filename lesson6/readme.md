## SmartLamps lesson 5

## Variable operations
We saw how to defile variables in a previous lesson. Variables are like containers that can hold any value. The value can be of any type (such as integer, floating point or string). Today we will look at some of the things we can do with variables

Let's start by opening python
##### :: _What we type_ ::

```
> python3.6
```

##### :: _What terminal outputs_ ::

```
Python 3.6.5 (default, Aug 29 2018, 03:28:50)
[GCC 5.4.0 20160609] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

#### There are a few rules to defining names of variables
First let's look at rules for defining variables. 

1. Variable names are case sensitive. For eg., CAT & cat are considered two different variables. They can hold two different values. 

##### :: _What we type_ ::

```
>>> CAT = 5
>>> cat = 1000
```

##### :: _What terminal outputs_ ::

```
>>>
```

Now try printing the two values using print statement & you will see the difference

##### :: _What we type_ ::

```
>>> print (CAT)
```

##### :: _What terminal outputs_ ::
```
>>> 5
```

##### :: _What we type_ ::
```
>>> print (cat)
```

##### :: _What terminal outputs_ ::
```
>>> 1000
```
2. Variable names can have letters and numbers but NO special characters except underscore (_). Eg. Hello123, Dog_Cat

3. The first letter of the variable has to be a character from a-z or A-Z or special symbol underscore (_)

4. It is best to use a mnemonic as variable name to indicate what value we store there. For example, if we want to store phone number of Sam & Anna, you can pick variable names like Sam_phone and Anna_phone to know what you store in the variable.

***

#### Mathematical operations with variables (integers and floating points)

Mathematical operations that we saw in the previous lesson can also be used in variables that are integer and floating point types. The operations are

- Addition : **+**
- Subtraction: **-**
- Division: **/**
- Multiplication: __*__
- Exponent: __**__

Let's try the different operations! 
*** 
#### First let's define two variables.

##### :: _What we type_ ::
```
>>> a = 5
>>> b = 2
```

##### :: _What terminal outputs_ ::
```
>>>
```

#### Addition:
##### :: _What we type_ ::
```
>>> a + b
```

Remember **a** stores value 5 & **b** stores value 2. So the terminal outputs the following

##### :: _What terminal outputs_ ::
```
>>> 7
```

#### Subtraction:

##### :: _What we type_ ::
```
>>> a - b
```

##### :: _What terminal outputs_ ::
```
>>> 3
```
#### Multiplication:
Remember the symbol __*__ for multiplication. 
##### :: _What we type_ ::
```
>>> a * b
```

##### :: _What terminal outputs_ ::
```
>>> 10
```
#### Division:
Remember the symbol __/__ for multiplication. 
##### :: _What we type_ ::
```
>>> a / b
```

##### :: _What terminal outputs_ ::
```
>>> 2.5
```

#### Exponent:
Remember the symbol __**__ for exponent. 
##### :: _What we type_ ::
```
>>> a ** b
```

##### :: _What terminal outputs_ ::
```
>>> 25
```

#### Bonus: Modulo
Remember the symbol __%__ for exponent. Modulo gives the reminder, reminder for 5 divided by 2 is 1. 
##### :: _What we type_ ::
```
>>> a % b
```

##### :: _What terminal outputs_ ::
```
>>> 1
```
***

#### String operations with variables (Strings)

We can also use operation with strings but because strings are made up of letters and numbers, there are different operations. 

Let's define two string variables!
##### :: _What we type_ ::
```
>>> x = "apple"
>>> y = "pie"
```
Notice how we have a space after **Hello**.
Feel free to use any name instead of Adam!
##### :: _What terminal outputs_ ::
```
>>> 
```
***

##### Addition
This is also known as string concatenation.
Symbol is **+**

Let's add the two strings. 
##### :: _What we type_ ::
```
>>> x + y
```

##### :: _What terminal outputs_ ::
```
>>> applepie
```
You can save the value of **x + y** in a new variable, say z. This uses the ASSIGNMENT operation that we saw in earlier lessons. Here is how we do it. 

##### :: _What we type_ ::
```
>>> z = x + y
```
##### :: _What terminal outputs_ ::
```
>>> 
```
Remember, once we save the output in a new variable, there will be no display in the terminal. To see what value is stored in variable z, do the following. 

##### :: _What we type_ ::
```
>>> print (z)
```
*print* function displays the value of **z**. As we see below, **z** indeed has the value of x + y!
##### :: _What terminal outputs_ ::
```
>>> applepie
```
***

##### length
This helps find the number of letters in the given string. 

We can use this to find how long the strings are.
##### :: _What we type_ ::
```
>>> len(x)
```

##### :: _What terminal outputs_ ::
```
>>> 5
```

Coding Challenge: Could you find the length of strings **y** and **z**?


##### Convert cases (Upper to Lower case or Lower to Upper case)

This one works a bit differently. So watch how we do it. We know variable **x** stores the value 'apple'. All letters are in lower case. If we want to convert it into upper case, here is how we do it. 

##### :: _What we type_ ::
```
>>> x.upper()
```
Do not forget the period **.** after the variable and the brackets () after typing upper. 
##### :: _What terminal outputs_ ::
```
>>> APPLE
```
Let's save the uppercase APPLE in a new variable **x_caps**.

##### :: _What we type_ ::
```
>>> x_caps = x.upper()
```
Do not forget the period **.** after the variable and the brackets () after typing upper. 
##### :: _What terminal outputs_ ::
```
>>> 
```
Remember, once we save the output in a new variable, there will be no display in the terminal.

To see the value stored in x_caps, use print function. 
##### :: _What we type_ ::
```
>>> print(x_caps)
```

##### :: _What terminal outputs_ ::
```
>>> APPLE
```

Now to convert this back to lower case, we use the following. 

##### :: _What we type_ ::
```
>>> x_caps.lower()
```

##### :: _What terminal outputs_ ::
```
>>> apple
```

**Note:** *.upper()* converts all lower case letters into upper case letters. It ignores letters that are already in upper case and it also ignores special characters/numbers. Similarly *.lower()* converts all upper case letters into lower case and ignores the rest. 
