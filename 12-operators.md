# Operators

* and
* or
* not

# Bitwise Operators

### & - Ampersand

Example

print(15 & 22) = 6

#### Continue dividing by 2
15 - 0b 1111
22 - 0b10110

Comparing two 1's returns 1
Comparing two 0's returns 0
Comparing 1's and 0's returns 0

Result =  0b00110 (6)

---

### | - OR

print(15 | 22) = 31

#### Continue dividing by 2
15 - 0b 1111
22 - 0b10110

ORing 1 or 0 gives 1
ORing 1 or 1 gives 1
ORing 0 or 0 gives 0

Result =  0b11111 (6)

---

### ^ - Exclusive OR

print(15 ^ 22) = 25

#### Continue dividing by 2
15 - 0b 1111
22 - 0b10110

ExORing 1 or 0 gives 1
ExORing 1 or 1 gives 0
ExORing 0 or 0 gives 0

Result =  0b11111 (6)

---

### ~ - Negation operator

#### Continue dividing by 2 and provide 8 bits
22 - 0b00010110

Result =  0b11101001 (-23)

---

The following operators can be used as ternary

&=
|=
^=

same as

bit1 = bit1 & 23 can be represented as bit1&=23

### Bit Shifting

Note: Bitwise shift operators (<<, >>) has higher precedence than Bitwise AND(&) operator

22 - 0b00010110

print(22 >> 1)

1 bit shifted to the right

00010110 become - 0b00001011

prints 11

print(22 << 1)

00010110 become - 00101100

prints 44

| Floor Division | Bitwise | 
| ------------- |:-------------:|
| 22 // 2      | 22 >> 1 |
| 22 // 4      | 22 >> 2     |

| Multiplication | Bitwise | 
| ------------- |:-------------:|
| 22 * 2      | 22 << 1 |
| 22 * 4      | 22 << 2     |