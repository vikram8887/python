# 18 oct documantion of today class with proper explanation

# using markdown, comments, examples and code

## ascii values

#### here values for each and every character called 'ascii' 
#### that can be in the form of upper function and lower function alphabets

##### like ( a,b,c,d.....),(A,B,C,D..)

### example


```python
ord('a')
```




    97




```python
ord('A')
```




    65



### toung twister

#### > this toung twistes should be denoted with three qoutes


```python
tt ='''Can you can a can as a canner can can a can'''
tt


```




    'Can you can a can as a canner can can a can'



#### > this was the id which this toung twister was located


```python
id(y)
```




    1994764711376




```python
y = 'Can you can a can as a canner can can a can'
xu =xu.upper()
```

 #### strings are immutable the resulting starting from string methods having a new memory location
      in order to use these strings , we need reassing into avarible

## capitalize

#### capitalise 


```python
x= "Can you can a can as a canner can can a can"
x.capitalize()

```




    'Can you can a can as a canner can can a can'



## title()

#### title()  first alfabet of every world in sentance is converted into capital
#### xl.title()



```python
x.title()
```




    'Can You Can A Can As A Canner Can Can A Can'



### swapcase ()

 #### in swapcase it will swap from lower case to upper case


```python
x.swapcase()
```




    'cAN YOU CAN A CAN AS A CANNER CAN CAN A CAN'



### casefold ()

#### casefold is samelike as lowercase


```python
x.casefold()
```




    'can you can a can as a canner can can a can'



### arthematic operations

 ### operations that involve manipulating numerical values to perform calculations. These operations are essential in mathematics and are commonly used in computer programming and everyday life. The basic arithmetic operations include:


```python
addition       (+)

multiplication (*)

subtraction (-)

division (/)

floor division (//)

modules  (%)

exponentiation (**)
```


```python
x = 10
y = 2
print(x+y, x*y, x-y, x/y, x//y, x%y, x**y)
```

    12 20 8 5.0 5 0 100
    

### logical operations

### Logical operations, also known as Boolean operations, are fundamental operations in both mathematics and computer science that deal with logical values (true or false). 


```python
x = True
y = False
print('x and y is ',x and y)
print('x or y is ', x or y)
print('not x is ',not x)
```

    x and y is  False
    x or y is  True
    not x is  False
    


```python
operator                   meaning

&                          bitwise AND

|                          bitwise OR

^                          bitwise exclusive

-                          bitwise complement

<<                         shift left

>>                         shift right
```

### Assignment operator

### An assignment operator is used in programming to assign a value to a variable. It is a fundamental concept in computer programming and is used to store data in memory locations represented by variables.


```python
Assignment Operators:

Assign value:             =
Add and assign:            +=
Subtract and assign:      -=
Multiply and assign:      *=
Divide and assign:        /=
Floor divide and assign:  //=
Modulus and assign:        %=
```

## strings 


###  strings are immutable because it avoids the unnecessary bugs
Some other immutable objects are integer, float, tuple, and bool. More on mutable and immutable objects in Python.

### 1. string methods with example



#####  1.lower int()
##### 2.upper int()


```python
 text = "HELLO, WORLD!" 
text.lower()
```




    'hello, world!'




```python
text = "hello,world"
text . upper()
```




    'HELLO,WORLD'



### these are the methods of strings


```python
x = 'python'
print(x, type(x))
dir(x)
```

    python <class 'str'>
    




    ['__add__',
     '__class__',
     '__contains__',
     '__delattr__',
     '__dir__',
     '__doc__',
     '__eq__',
     '__format__',
     '__ge__',
     '__getattribute__',
     '__getitem__',
     '__getnewargs__',
     '__getstate__',
     '__gt__',
     '__hash__',
     '__init__',
     '__init_subclass__',
     '__iter__',
     '__le__',
     '__len__',
     '__lt__',
     '__mod__',
     '__mul__',
     '__ne__',
     '__new__',
     '__reduce__',
     '__reduce_ex__',
     '__repr__',
     '__rmod__',
     '__rmul__',
     '__setattr__',
     '__sizeof__',
     '__str__',
     '__subclasshook__',
     'capitalize',
     'casefold',
     'center',
     'count',
     'encode',
     'endswith',
     'expandtabs',
     'find',
     'format',
     'format_map',
     'index',
     'isalnum',
     'isalpha',
     'isascii',
     'isdecimal',
     'isdigit',
     'isidentifier',
     'islower',
     'isnumeric',
     'isprintable',
     'isspace',
     'istitle',
     'isupper',
     'join',
     'ljust',
     'lower',
     'lstrip',
     'maketrans',
     'partition',
     'removeprefix',
     'removesuffix',
     'replace',
     'rfind',
     'rindex',
     'rjust',
     'rpartition',
     'rsplit',
     'rstrip',
     'split',
     'splitlines',
     'startswith',
     'strip',
     'swapcase',
     'title',
     'translate',
     'upper',
     'zfill']



## Take a twostrings of your choice,

### 1) reversing one string

### 2) Concatenate these two strings


### 3)Get the alternate chars of the concatenate string in reverse order.

### 1)


 #### it begins with index -1 to -n , where n is length of string

#### negative indexing movies from right to left


```python
x = 'hyderbad'
y= 'charminar'
z = y[::-1]
print(x+z)
```

    hyderbadranimrahc
    

### 2)


### string concatenation is the operation of joining character string end- to -end


```python
str1="Hello"
str2="friends"
print ("string 1:",str1)
print ("string 2 :", str2)
str=str1+str2
print("concatenated two different string:",str)
```

    string 1: Hello
    string 2 : friends
    concatenated two different string: Hellofriends
    

### 3)

## Get the alternate chars of the concatenate string in reverse order.

### Here we take two strings then we add these two strings by using concalination

### after concationation the output will be taken for another function called reverse() function


```python
x='hyderbad'
y='charminer'
z=x+y
print(z)
print(z[::-2])
```

    hyderbadcharminer
    rnmacardh
    


```python

```
