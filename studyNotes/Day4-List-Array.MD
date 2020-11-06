## Lists
working with list, or large amount of data. To make list we first give a name that describe what is in side this list.
`[]` used to make list or store a bunch of values inside.
```python
# list is an array as per javascript
friends = ["Night", "Day", 5, False, "Midday"]
print(friends[3]) # Answer False

# If we give negative value it will start to show  from back of the list.
print(friends[-3]) # Answer 5

# To grab elements after 5
print(friends[2:]) # Answer [5, False, 'Midday']
```
```python
# grabs from 1 up to before 4, mean just 1 and 3 but not 4
friends = ["Day", "Midday", "Evening", "Night", "Midnight"]
print(friends[1:4]) #Answer ['Midday', 'Evening', 'Night']

```
To change a value in this list
```python
friends = ["Day", "Midday", "Evening", "Night", "Midnight"]
friends[2] = "Sunday"
print(friends[2])
```