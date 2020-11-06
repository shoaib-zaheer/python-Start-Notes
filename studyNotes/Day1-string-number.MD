#Python
## To draw shape in the screen.
```python
print("Hello World")
print("   /|")
print("  / |")
print(" /  |")
print("/___|")
```
## Variables & Data Types
strings, decimal number or whole numbers, true or false values "Boolean "

```python
character_name = "BAD"
character_age = "50"
print("There once was a man named " + character_name + ",")
print("He was " + character_age + "years old.")
character_name = "NICE"
print("He really like the name " + character_name + ",")
print("but didn't like being 70.")
```
## working with strings
strings are basically just plain text.

```python
# \n printing new line.
print("Hello\nWorld")

# writing string as variable
variable = "Hello world"
print(variable)

# concatenation "is a process to appending to strings"
variable = "Hello world"
print(variable + " writing for the first time")
```
#### lower (), upper(), islower(), isupper(), len(), 
```python
# convert string to lowercase
variable = "Hello World"
print(variable.lower())

# convert string to uppercase
print(variable.upper())
 
# to check if string is upper or is lower case
print(variable.upper().isupper()) 

#islower()
# answer is by False and True
print(variable.upper().isupper()) 

# to check how many characters in the string
print(len(variable))
```
##### stringName[], 

```python
# to grab the character from string.
variable = "Hello World"
print(variable[6])
```
##### index(), replace()
```python

# tell us where specific character or string is located
variable = "Hello World, I'm here!"
print(variable.index("W"))# write parameter to look.

# to check word in string start from
print(variable.index("I'm"))

# If character is not available, it throw error
print(variable.index("Z"))

# to replace, two parameters 1 the on to replace, 2 with one to replace.
print(variable.replace("World", "Earth"))
```
## Working With Numbers
```python

print (2 + 2.323)
print (5.3 - 2)
print (2 * 4 + 4)
print (3 * (10 / 5)) # now this will follow the mathematic rule
print (10 / 3)
print (10 % 3) # 10 mod 3 give the remaining value not the answer
```
##### str() `string`, abs() `absolute value`, pow(), nax(), round(),  
```python
# convert number to string
my_num = 5
print(str(my_num) + " My lucky number")

# To find out the absolute value for number.
my_num = -5
print(abs(my_num))

# pow () takes to pieces of information 1 number second the power it might take.

my_num = 5
print(pow(my_num, 5)) # Answer 3125

# max() return the larger number of two number we pass
print(max(6, 2)) # Answer 6

# min () return the lower number of two number we pass
print(min(6, 2)) # Answer 2

# round() to round a number
print(round(4.8)) # Answer 5

```
#### Using import to bring some more math function.
##### floor(), ceil(), sqrt(),
```python
# floor() It will grab the lowest number
from math import *
print(floor(3.7)) # Answer 3, it will remove the decimal point.

# ceil () opposite of floor()
print(ceil(3.7))# Answer 4, 

# sqrt() It return the square root of a number
print(sqrt(36))
```