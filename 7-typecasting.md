# Type casting

Type casting is required to convert one data type to another data type.

int(string) - Converts a string to an integer
float(string) - Converts a string to a float

* Programs not using input is a deaf program.

```
>>> print(int(15.5)-10)
13
```

The following results in an error

```
>>> total_sum = 25
>>> print("sum: " + total_sum)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: can only concatenate str (not "int") to str
>>> 
KeyboardInterrupt
```

The right way to do it is as follows

```
>>> print("sum: " + str(total_sum))
sum: 25
```