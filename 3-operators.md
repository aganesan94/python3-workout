# Operators

* \+  Addition
* \-  Subtraction
* \*  Multiplication
* \/  Division
* \** Exponent
* % Modulo
* \// Floor Division

## Special case

* Exponents/Multiplication/addition/subtraction
  * When one value is a decimal, the result is a decimal

* Division
  * Always returns a float

* Floor Division
  * Returns a float only if one of them is float.
  * Returns the least value in case of negative integer.

Difference between division and floor division

```
6. / 4 = 1.5
6. / -4 = -1.5

6. // 4 = 1.0
6. // -4 = -2.0
```

* \- operator - is both binary and unary  operator

## Operators - Priority

\+ \-

\**

\* / // %

\+ \- (Binary operators)

## Short cut operators

```
a = a + 2 
```
is the same as 

```
a+=2
```

```
print(arun*2)
arunarun
```