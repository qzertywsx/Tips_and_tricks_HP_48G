# Tips and tricks HP 48G
Tips and tricks for the HP 48G calculator
## Button icon
<kbd>⯅</kbd>
<kbd>⯆</kbd>
<kbd>⯇</kbd>
<kbd>⯈</kbd>
<kbd>↱</kbd>
<kbd>↰</kbd>
<kbd>α</kbd>
<kbd>←</kbd>
↲
∠

## Solve quadratic equation (or n-th order polynomial equation)
### Find roots of a polynomial equation

* Go to `SOLVE`->`Solve poly`
* In `COEFFICIENTS` write all the coefficients of the equation
* When all the coefficients is written, press `ENTER` to return to the solver menu
* With the arrow down key go `ROOTS`
* Press `SOLVE`

Example:<br>
Equation: 2x^2-136x+1920=0<br>
Coefficients: 2 -136 1920<br>
Roots: 20 48

### Find coefficiets of a polynomial equation
You can insert the roots and it can calculate the coefficients of the equation with that roots

* Go to `SOLVE`->`Solve poly`
* In `ROOTS` write all the roots of the equation
* When all the roots is written, press `ENTER` to return to the solver menu
* With the arrow up key go `COEFFICIENTS`
* Press `SOLVE`

## Complex number
### Write complex number
A complex number is written between parentesis (Real, Imm)
Example 5+2i ==> (5, 2)

### Rectangular and polar coordinate
Press <kbd>↱</kbd><kbd>POLAR</kbd> to change between rectangular and polar coordinate.<br>
With <kbd>↱</kbd><kbd>MODES</kbd><kbd>⯆</kbd><kbd>⯆</kbd> you can choose between "Rectangular", "Polar" and "Spherical".

Mode|annunciator
----|----
Rectangular|
Polar|R∠Z
Spherical|R∠∠

### Function for complex number
In <kbd>MTH</kbd><kbd>NXT</kbd>COMPL there is some function for complex number
Function|Description|Example
----|----|----
ABS|Absolute value|(3,4)==>5
ARG|Polar Angle|(1,1)==>45
CONJ|Complex conjugate|(2,3)==>(2,-3)
C→R|Complex to real|(2,3)==>2 3
IM|Immaginary part|(4,-3)==>-3
NEG|Negative|(2,-1)==>(-2,1)
RE|Real part|(4,-3)==>4
R→C|Real to complex|-7 -2==>(-7,-2)
SIGN|Unit vector in the direction of the complex number|(3,4)==>(0.6,0.8)

## Binary arithmetic and number bases
### Select number base
In <kbd>MTH</kbd>BASE choose between HEX, DEC, OCT and BIN.
### Set word size
Enter the number of bit in the stack, then press <kbd>MTH</kbd>BASE<kbd>NXT</kbd>STWS
### Get word size
Press <kbd>MTH</kbd> `BASE` <kbd>NXT</kbd> `RCWS`
### Enter an integer value
To enter a value press #, enter the value, if the selected base is the base you want, press enter, else press "d" for decimal, "h" for hexadecimal, "o" for octal or "b" for binary and press enter.
### Convert between different base
Enter the number in the given base, in <kbd>MTH</kbd> `BASE` select the desired base
### Two's complement
Press <kbd>+/-</kbd> to show the two's complement.
### Convert from real number to integer end viceversa
To convert from real to integer press <kbd>MTH</kbd> `BASE` `R→B`<br>
To convert from integer to real press <kbd>MTH</kbd> `BASE` `B→R`
### Boolean operator
In <kbd>MTH</kbd> `BASE` <kbd>NXT</kbd> `LOGIC` there is the operator AND, OR, XOR and NOT.
### Manipulating bit and byte
In <kbd>MTH</kbd> `BASE` <kbd>NXT</kbd> `BIT` or `BYTE` there are these commands (the bit example assume word size of 4, the byte example assume word size of 24):
Function|Description|Example
----|----|----
RL|Rotate left|# 1001b==># 11b
RR|Rotate right|# 1001b==># 1100b
SL|Shift left|# 1001b==># 10b
SR|Shift right|# 1001b==># 100b
ASR|Arithmetic shift right (preserve MSB - Sign bit)|# 1001b==># 1100b
SLB|Shift left byte|# 123456h==># 345600h
SRB|Shift right byte|# 123456h==># 1234h
RLB|Rotate left byte|# 123456h==># 345612h
RRB|Rotate right byte|# 123456h==># 561234h
