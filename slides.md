%title: Python for Beginners!
%author: github.com/VinayManala
%date: 2021-02-24

    / Hello Everyone:                        \
    | Learn Python and build awesome projects|
    \ Python for fun and profit!             /
      --------------------------------------
             \   ^__^ 
              \  (oo)\_______
                 (__)\       )\/\
                     ||----w |
                     ||     ||
    

-------------------------------------------------------------------------------
-> # Background

##  Everybody wants to learn Python:
    <br>        
            * Python is Easy.
            * It is used everywhere: you name it.
    
    <br>
##  Conclusion:
        <br>
        * Why Python?
        * Who are using it?

-------------------------------------------------------------------------------

-> # Objectives

##  Prerequisite:

        <br>
        * Python Version 3 and above

        * Editor

        * Terminal 
        <br>

    * Lets Get Started

-------------------------------------------------------------------------------

-> # Basic DataTypes and Operators

##  Data Types
    <br>
      *  Data - which is stored as an information.

    <br>
      *  Type - which defines what type of data it is.
      *  Variables can store data of different type.

    <br>
      * In Python to check the data type we have syntax:
    <br>
      type(variable)

    <br>
      * Python has following built-in data types:
    <br>
    Text Type: str
    Numeric Types: int, float, complex
    Sequence Types:  list, tuple, range
    Mapping Type: dict

-------------------------------------------------------------------------------

-> # Basic DataTypes and Operators

##  Operators
    <br>
        * Operators are used to perform operations on variables and values.

    <br>
      * Groups
            <br>
            * Arithmetic Operators
            <br>
            * Assignment Operators
            <br>
            * Comparision Operators
            <br>
            * Logical Operators
            <br>
            * Identity Operators

    * Boolean Value
        True
        False

-------------------------------------------------------------------------------

-> # Input Output

##  Output
    <br>

        * displays the message you want to output it to the console.

        print("Hello World")
    /                      \
    | print("Hello World") |
    \                      /
      ------------------------------------------
             \   ^__^
              \  (oo)\_______
                 (__)\       )\/\
                     ||----w |
                     ||     ||

------------------------------------------------------------------------------
     * Others: newline , tab, f-strings

##  Input

    <br>
        * takes input from the console and stores the value in the variable.

    name = input("What is your name?")

    <br>
        *  by default it stores the input as a string.





-------------------------------------------------------------------------------

-> # Conditionals and Loops

##  Conditionals
        * allows to test a condition.
        * if else:
    <br>

    if (condition):
        print("this")
    elif (conditon):
        print("this")
    else:
        print("this")

   <br>
   * Others
        * ternary operator
        * allows to test a condition in a single line.

    print(x) if (condition) else print(y)

    <br>
        * Others: pass statement
            * acts as a null operation.

-------------------------------------------------------------------------------

-> # Conditionals and Loops

##  For Loops
    <br>
        * iterates over the elements or sequencial datatypes.

    mylist = [1,2,3,4]
    for i in range(len(list)):
        print(mylist[i])

    <br>
    * While Loops
    <br>
        * executes a set of statements while condition is true.

    i = 5
    while(i != 0):
        print(i)
        i -= 1

    <br>

    * break, continue
    <br>
        * break - used to break the innermost loop.
        * continue - skips the below instructions.

-------------------------------------------------------------------------------

-> # Working with Lists

##  Lists
    <br>

        * Python Lists are dynamic.
        * Used to store multiple items in a variable.
        * list slicing.

    <br>
    dynamiclist = [1,'apple',[2,3.4],4]

      * Items and Index
        <br>

        * List items allows duplicate entries.
        * List index starts with [[0]],[[1]]....
    <br>
      * methods
        * len()
        * .index()
        * .append()
        * .insert()
        * .remove()
        * .sort()
        * sorted()
        * .reverse()
        * .clear()
        * del
        * pop()

-------------------------------------------------------------------------------

-> # Working with Strings

##  Strings

    <br>
    * Strings are surrounded by single/double quotation marks.
    * multistring can also be formed using three single/double quotation marks.
    <br>
    print("hello!")
    print('hello')

    * String as Arrays
        * we can loop through the strings same as list.
        * get a character using indexing same as list.

    <br>
    a = "string"
    print(a[2])
    OUT : 'r'

    *  Other Features:
        * Slicing can be performed on strings.
        * in , not in operators can be used in string manipulation.

-------------------------------------------------------------------------------

-> # Working with Tuples
    
##  Tuples
    <br>
        * Tuples are used to store multiple items in a single variable.
        * Tuples are same as lists.
        * Drawbacks of Tuples over Lists:
            * Tuples cannot modify items.
    <br>
    mytuple = ("air","fire")
    
    * Other Features:  
        * like lists tuples allow duplicate entries.
        * methods which are used are mostly same as in lists.

-------------------------------------------------------------------------------   

-> # Working with Sets
    
##  Sets
    <br>
        * it also allows to store multiple items in a variable.
        * No duplicate entries are allowed.

    <br> 
    myset = {"air","fire"}
    
    * Others:
        * methods used are mostly same as list,tuples.

-------------------------------------------------------------------------------

-> # Working with dictionaries

##  Dictionaries
    <br>
        * Used to store data values in key:value pairs.
        * No duplicate entries are allowed.

    <br>
    mydict = {"name":"vinay",
              "age": 21,
              "class": "TE"}

    * Manipulation with dict:
        * access elements using 
    <br>
    print(mydict['name'])
    OUT : 'vinay'
    
    * Others:
        * dicitionaries are unordered.
        * new items can be added and modified.
        * methods:
            * .keys()
            * .values()
            * .items()

-------------------------------------------------------------------------------
-> # Parsing Data

## Parsing methods:
    <br>
        * reading the data in various object types.
    <br>
     * Split method:
        * breaks the string into substrings.
        * Uses the defined seperator.
        * returns a list of substrings.
    <br>
    mystr = "String"
    mylist = mystr.split()

        * Strip method:
    <br>
        * removes all trailing and leading whitespaces in a string.
    <br>
    mystr = " String  "
    mystring = mystr.strip()

    mytuple = (1,2,3)
    mylist = list(mytuple)
    OUT: [1,2,3] 

-------------------------------------------------------------------------------

-> # Closing

##  Presentation: 
    *  Connect : *https://github.com/VinayManala/pymulticon21*


    <br>
      __________
    < Questions? >
      ----------
            \   ^__^ 
             \  (oo)\_______
                (__)\       )\/\
                    ||----w |
                    ||     ||


-------------------------------------------------------------------------------
