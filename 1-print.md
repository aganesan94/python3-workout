# print()

## Usages

### General

```
print("Hello World")
Hello World
```

### Array of Strings

```
print("Hello","Arun","How","Are","You")
```

### Ending Strings

```
>>> print("Hello",end="!"); \
... print("how")
Hello!how
```

### Separating Strings

```
>>> print("Hello","how","are","you",sep="!"); \
... print("Fine")
Hello!how!are!you
Fine
```

### Using Separate and End together

```
>>> print(1, 2, 3, 4, sep='#', end='&')
1#2#3#4&>
```

### Using a new line

```
>>> print("Fine \n how are you?")
Fine 
 how are you?
```

### Printing

```
>>> print("Hello" + " " "future" + " " "python!")
Hello future python!
```

### TypeErrors during printing

```
>>> print('My age is ' + 25)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: can only concatenate str (not "int") to str
```

### Escaping characters during printing

```
>>> print("Hello \"Python\" world")
Hello "Python" world
```