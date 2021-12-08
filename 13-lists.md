# Lists

- Used to store any array of objects.
- Index starts with 0


## Initializing the list

```python
countries = ["USA","UK","Canada"]
```

## Reading the value

```python
print(countries[0])
```
## Reading the last value

```python
print(countries[-1])
```


## Updating the value

```python
countries[0]="India"
```

## Deleting the value

```python
del countries[0]
```

## Appending values

```python
countries = ["USA","UK","Canada"]
countries.append("Spain") # Append values at the end
countries.insert(2, "Spain") # Insert value at the 2nd position. Items in the current postion on 2 shift right
```

## Sorting a list

```python
ages = [25,28,6,2]
ages.sort() # Sorts in ascending
```

## Reversing a list

```python
ages = [25,28,6,2]
ages.reverse() # reverses item in the list
```
## Removing items from the list

```python
ages = [25,28,6,2]
ages.pop(2) # remove the item from the 2nd index.
```

# Moving values within the list.

The first item in the list should be the value of the second item, the second item value should be the value of the first item.

```python
countries[0], countries[1] = countries[1], countries[0]
```

# Iterating within a list

Iterating lists

```python
for age in ages:
  print(age)
```
# Slicing

 * list[start:end] is the pattern
 * list[start:end:step] is the pattern

 Note that when slicing a list a new array object is created in memory except when using del when slicing it works on the same memory reference.
 
```python
ages = [25,28,6,2]
print(ages[1:]) # Prints every item equal and after index 1
```


# Element is in list or not can be checked using the following

```
ages = [25,28,6,2]

if 25 in ages

if 25 not in ages
```

# Iterate over values based on index

Iterating lists

```python
ages = [25,28,6,2]
print(ages[2::]) # Prints items in index 0,2
```

```
>>> list1 = [1, 2, 3, 4]
>>> for i, j in enumerate(list1):
...      print(i, j)
... 
0 1
1 2
2 3
3 4

```

## Errors

If there is an error accessing the index, we receive an

```
IndexError: list index out of range
```

