# glossary
Glossary of key terms

#####Boolean
A boolean is like a light switch. It can only have two values. Just like a light switch can only be on or off, a boolean can only be True or False.

#####Boolean operators 
These compare statements and result in boolean values. There are three boolean operators:

* ```and```, which checks if both the statements are True;
* ```or```, which checks if at least one of the statements is True;
* ```not```, which gives the opposite of the statement.

Order of operations:
```not``` is evaluated first;
```and``` is evaluated next;
```or``` is evaluated last. Brackets () ensure your expressions are evaluated in the order you want. 

#####Comments
The # sign is for comments. A comment is a line of text that Python won't try to run as code. It's just for humans to read.

#####Comparators 
Comparators check if a value is (or is not) equal to, greater than (or equal to), or less than (or equal to) another value. Comparisons result in either True or False, which are booleans.

There are six comparison operators:

* Equal to ```==```
* Not equal to ```!=```
* Less than ```<```
* Greater than ```>```
* Less than or equal to ```<=```
* Greater than or equal to ```>=```


Note that ```==``` compares whether two things are equal, and ```=``` assigns a value to a variable.

#####Control flow 
This gives us this ability to choose among outcomes based off what else is happening in the programme.



#####Exponentiation
Exponentiation is a maths operator that raises a number to a power of another number e.g. if you want to square a number, i.e. raise 4 to the power of 2 you would type it like this:
```
4**2
```

#####If and else statements
```if``` is a conditional statement that executes some specified code after checking if its expression is True.

```
if 8 < 9:
    print "Eight is less than nine!"
```

In general terms this can be written

```
if some_function():
    # block line one
    # block line two
    # et cetera
```

In the event that some_function() returns True, then the indented block of code after it will be executed. In the event that it returns False, then the indented block will be skipped.

The ```else``` statement complements the ```if``` statement. An if/else pair says: "If this expression is true, run this indented code block; otherwise, run this code after the else statement." Unlike if, else doesn't depend on an expression. For example:

```
if 8 > 9:
    print "I don't printed!"
else:
    print "I get printed!"
```

#####Modulo
Modulo returns the remainder from a division. So, if you type 3 % 2, it will return 1, because 2 goes into 3 evenly once, with 1 left over.


#####Printing
print simply displays your code in the console.


#####Strings
Strings are extremely useful data types, used to contain text. A string can contain letters, numbers, and symbols. Strings need to be within quotes.

Each character in a string is assigned a number. This number is called the index. In Python, we start counting the index from zero instead of one. We can access any character by its index using square brackets E.g. if I wanted to access the 3rd letter of the string "Python" I would type:
```
"Python"[2]
```

Python has a number of ready-made string methods that let you perform specific tasks for strings. e.g. you can find the length of a string by typing 
```
len("Python")
```

The str() method turns non-strings into strings! 

Certain methods can be used on many data types and some are string specific. Those methods that use dot notation, like upper() and lower() only work with strings.

```
"PYTHON".lower()
"python".upper()
```
#####String concatenation 
The + operator between strings will 'add' them together, one after the other. Combining strings together like this is called concatenation. Sometimes you need to combine a string with something that isn't a string. In order to do that, you have to convert the non-string into a string. The str() method converts non-strings into strings. 

#####Variable

A variable stores a piece of data, and gives it a specific name. Think of it like a box that contains a value. 
```
favouriteColor = "lime green"
```

