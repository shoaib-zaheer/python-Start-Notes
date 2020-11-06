## Using functions with list in python.
**extend()**, **insert(a, b)**, **remove()**, **clear()**, **pop()**, **index()**, **count()**, **sort()**, **reverse()**, **copy()**

```python
# append one list in other one as one of the its value.
lucky_num = [4, 6, 8, 10, 12, 14, 16]
time = ["Day", "Afternoon", "Midday", "Evening", "Night"]
time.append(lucky_num)
print(time)

# we can append new value also with this
time.append("Midnight")

# To insure in a specific location
time.insert(1, "Midnight")

# to remove the element from the list
time.remove("Day")

# To clear all the elements from the list
time.clear()

# to remove the last element from the list
time.pop()

# checking the value existence and position in list.
print(time.index("Afternoon"))

# to count how many time a value existed in the list.

print(time.count("Afternoon"))

# writing your list in alphabetical order

luck_num.sort()

# to write your list in reverse order

lucky_num.reverse()

# create a new list by copying the old list

time2 = time.copy()
```