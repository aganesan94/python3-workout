# loops

Loops are classified as

* for 
* while


## While loop

```
secret_number = 3
guess = int(input("Guess a number: "))
while guess != secret_number:
  guess = int(input("Guess a number: " ))
else:
  print("Congratulations, you got it")
```



```
x = 1
while ( x <= 5 ):
  x += 1
print(x)
```

## For loop


### Prints values from 0 to 4

```
i = 0
for i in range(5):
  print(i)
```

### Prints values from 2 to 4

The following ways are demonstrated to print within a specific range


```
for i in range(2, 5):
  print(i)
```

The following sequence of lines below Prints value 0 and 1

```
for i in range(5):
  if(i==2):
    break;
  print(i)
```

The following sequence of lines below skips 2 and prints values from 0 to 4

```
for i in range(5):
  if(i==2):
    continue;

  print("i is: ", i)
```

The following loop iterates over all the characters in a string.
Note: We do not specify a *range* function here.

```
x='arun'
for i in x:
  print(i.upper())
```