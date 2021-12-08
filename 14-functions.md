# Functions

* Function use def keyword and are use to modularize code and reuse code.
* Variables declared inside function are declared inside the function.
* Variables with global scope and local scope are placed differently in memory.
* Arguments are passed by reference.

```python
def printme():
```

Function needs to be defined before invocation.

## Passing named parameters

```python
def input_number(num1, num2):
  input1 = input_number(num2 = 100, num1 = 50)
```

## Return statement - returns the value last evaluate

* Returns not just return value
* returns can also return None

```python
def print_sum(num1, num2)
  sum = num1 + num2
  return
```  

```python
def is_even(num1, num2)
  if(num % 2 == 0 ):
    return True
```  

```python
def is_true(a): 
  return bool(a) 

result = is_true(6<3) 
print("The result is", result)
```

## Passing a list as argument

