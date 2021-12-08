# Dictionaries

* Are key-value pairs

```python
fruits = {
 "apple" : "red",
 "orange" : "orange
}
```

## Accessing keys

* usernames[key] provides access to the username object
* Trying to access a key which does not exist throws a KeyError



## Iterating a dictionary

```python
for key in usernames.keys():
    print(key + "-" + usernames[key]) 

for value in usernames.values():
    print(value) 

# Converts a dictionary into a tuple
for value in usernames.items():
    print(value) 
```

### Reading a value

```python
print(fruits["apple])
```

### Inserting/Updating a value

```python
fruits.update({"apple" : "green"})
```

### Deleting a value

```python
del fruits["apple"]
```

### Deleting all items from a dictionary

```python
fruits.clear()
```

### Copying a dictionary

```python
fruits1 = fruits.copy()
```