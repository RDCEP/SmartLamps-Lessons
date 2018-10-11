## SmartLamps lesson 6

## User Input

Today we will see how to get input from the user. Try the following

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
***

##### :: _What we type_ ::

```
>>> input('What is your name?')
```

##### :: _What terminal outputs_ ::

```
>>> What is your name? 
```
Notice how the computer waits for you to type a name! Enter a name next to the question. Here we type the name **Mia** next to the question. (You can type any name here!)

##### :: _What we type_ ::

```
>>> What is your name? Mia
```
##### :: _What terminal outputs_ ::
```
>>> Mia
```

So the computer asked you a question and got an answer from you! That's called getting user input. 

Now, instead of printing the answer, we can save it in a variable called **name** as follows:

##### :: _What we type_ ::

```
>>> name = input('What is your name?')
```
Now it will save your answer inside the variable **name**. 
##### :: _What terminal outputs_ ::

```
>>> What is your name? 
```
##### :: _What we type_ ::

```
>>> What is your name? Mia
```
 
##### :: _What terminal outputs_ ::
```
>>> 
```
Notice how there is no output because we stored the value in the variable name. 

Now let's ask the computer to tell us the type of the variable **name** and what value it stores. 

##### :: _What we type_ ::

```
>>> print(name)
```
 
##### :: _What terminal outputs_ ::
```
>>> Mia
```
##### :: _What we type_ ::

```
>>> type(name)
```
 
##### :: _What terminal outputs_ ::
```
>>> <class 'str'>
```
This shows that name indeed stored the value we typed and it is of type ***string***.
***

Let's try a few string operations on the variable **name** that we saw in the previous lesson. 
##### 1. Addition or Concatenation

##### :: _What we type_ ::
```
>>> 'Hello ' + name
```
 
##### :: _What terminal outputs_ ::
```
>>> Hello Mia
```
***
##### 2. Finding String length
##### :: _What we type_ ::

```
>>> len(name)
```
 
##### :: _What terminal outputs_ ::
```
>>> 3
```
***
##### 3. Converting to upper and lower case
##### :: _What we type_ ::

```
>>> name
```
 
##### :: _What terminal outputs_ ::
```
>>> Mia
```

When we typed the name, the first letter is in caps and the rest are small. To convert it into all caps, we use the ***.upper()***
##### :: _What we type_ ::

```
>>> name.upper()
```
 
##### :: _What terminal outputs_ ::
```
>>> MIA
```

Similarly if we want to convert it into all small letters:
##### :: _What we type_ ::

```
>>> name.lower()
```
 
##### :: _What terminal outputs_ ::
```
>>> mia
```
***

Let's try another question:
##### :: _What we type_ ::

```
>>> number = input('What is your favorite number?')
```

##### :: _What terminal outputs_ ::

```
>>> What is your favorite number? 
```
Notice how the computer waits for you to type a number! Enter a number next to the question. Here we type the number **42** next to the question. (You can type any number here!)

##### :: _What we type_ ::

```
>>> What is your favorite number? 42
```
##### :: _What terminal outputs_ ::
```
>>> 
```
There is no output because we store the value in a variable called **number**. 

Coding Challenge: 
1) Print the value stored in the variable **number** using *print* function
2) Determine the data type of the variable **number** using *type* function

Hint: do not forget to use brackets () after the function. 

***
#### Data type of user input is always STRING

In the previous example, we asked the user for a number (which is an integer or floating point). However, *by default* computer treats ALL user input as string. 

Hence, in order to do mathematical operations with the user input number, we need to change the data type. 

Here is how we change the data type of the variable **number**. Initially it is ***string*** data type, but we want to change it to ***integer*** data type. 
##### :: _What we type_ ::

```
>>> number
```
 
##### :: _What terminal outputs_ ::
```
>>> '42'
```
Notice the quotes '' around 42, indicating that it is of string data type. 

The function ***int*** converts the value of the given variable to integer. 
##### :: _What we type_ ::

```
>>> int(number)
```
 
##### :: _What terminal outputs_ ::
```
>>> 42
```
Notice, we no longer have the quotes '' around 42, indicating that it is now an integer. 

To do mathematical operations, we need to store the integer value in a new variable. Let's call the new variable **integer**

##### :: _What we type_ ::

```
>>> integer = int(number)
```
 
##### :: _What terminal outputs_ ::
```
>>> 
```
There will be no output because we have stored the value in a variable. 

Now try out some mathematical operations. An example of addition is given below. 

1. Addition: symbol **+**
##### :: _What we type_ ::

```
>>> integer + 20
```
 
##### :: _What terminal outputs_ ::
```
>>> 62
```
2. Subtraction: symbol **-**
3. Multiplication: __*__
4. Division: __/__
5. Exponent: __**__
6. Bonus: Modulo __%__