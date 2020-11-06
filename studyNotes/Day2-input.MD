#### input ()
Making small app for user to input something then we use that input to do something
```python
# What ever name the user put in input we use it to say hello back!
name = input ("Enter your name here!")
print("Hello " + name + "!" )

# we can use multiple input 
name = input ("Enter your name here!")
age = input ("Enter your age here!")

print("Hello " + name + "! Your are " + age + " years old." )
```
## Building a Basic Calculator
##### int(), float()
```python
# int () convert sting to number but whole number.
num1 = input("Enter a number: ")
num2 = input("Enter another number: ")
result = int(num1) + int(num2)
print(result)

# float() convert string to a number and also not going to ignore the dismals while doing any calculation.
result = float(num1) + float(num2)
print(result)
```