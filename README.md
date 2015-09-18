# AQA CS AS Notes

## 3.5 Fundamentals of data representation

### 3.5.1 Number systems
+ natural numbers

**definition**: those are numbers used for counting.

**examples**: 0,1,2,3,4
``` 

Counting uses natural numbers
A set of natural number can expressed as:
N={0,1,2,3...}

```

+ integer numbers

**Definiton**: Whole numbers.

**Examples**: -5,-1,4,7,9
```

Numbers such as 0.5 or surds are not integers

```


+ rational numbers

**Definiton**: Any number that can be written as a fraction

**Examples**: 1/2,4/5,9/13
```
				   	
Numbers such as √2 or Pi

```

+ irrational numbers

**Defintion**: Numbers that can't be expressed as a fraction or as a terminating decimal
					
**Examples**: Pi, √2
```

Numbers such as 1/2 or 1.4 are not irrational numbers

``` 


+ real numbers

**Definiton**: All numbers than are not imaginary numbers
						 
**Examples** 3,21,1/2, √2
```

An example of an imaginary number would be "i"

```


+ ordinal numbers

**Definiton**: Numbers that are used to indicated position in a list

**Examples**: 1st,2nd,3rd


### 3.5.2 Number bases
+ base 2: those are binary numbers. example: 1010<sub>2</sub>. See [this site](https://bournetocode.com/projects/AQA_AS_Theory/pages/3-5.html) for more infomation
+ base 10: Decimal numbers
+ base 16: Hexidecimal numbers - Easily read by computers
+ conversion between denary, binary and hex

```
Decimal   Binary   Hexidecimal
0		  0000     0
1		  0001     1
2		  0010     2
3		  0011 	   3
4		  0100	   4
5		  0101	   5
6		  0110	   6
7		  0111	   7
8		  1000	   8
9		  1001	   9
10		  1010	   A
11		  1011     B
12		  1100	   C
13		  1101	   D
14		  1110	   E
15		  1111	   F

```


### 3.5.3 Units of information

<img src="http://www.globalspec.com/ImageRepository/LearnMore/20125/bytes_table3ca99aa9c4f24a3fb3bbba3c6de7f828.gif"></img>

### 3.5.4 Binary number system

#### unsigned binary
#### unsigned binary arithmetics
#### signed binary with two's complement
#### fixed point form binary representation of numbers with fractional parts

### 3.5.5 Information encoding system

#### Character form of a decimal digit

```
It is the decimal digit represented as a character
```

#### ASCII

**Definiton**: ASCII (American Standard Code for Information Interchange) is the most common format for text files in computers and on the Internet. In an ASCII file, each alphabetic, numeric, or special character is represented with a 7-bit binary number (a string of seven 0s or 1s). 128 possible characters are defined.

**Examples**: <img src="http://www.asciitable.com/index/asciifull.gif"></img>

```
ASCII was originally 7 bits long so it used to have a 
total of 128 unique combinations. Later, in the mid 80's,
 ASCII was extended to 8 bits, which doubled the amount
  of unique combinations to 256.
```

#### Unicode

**Definiton**: An international encoding standard for use with different languages and scripts

```
Unicode has 3 forms: UTF-8, UTF-16 and UTF-32. 
UTF is essentially the more widely used version of ASCII.
```

#### Error checking and correction

## There are 4 types of error checking:

**Parity**:
```
Parity bit is the simplest technique used to check 
the accuracy of data transimission. In this scheme, 
the MSB(most significant bit) of an 8-bits word is 
used as the parity bit and the remaining 7 bits 
are used as data or message bits. The parity of 
8-bits transmitted word can be either even parity
or odd parity. Between two parties start data 
transmission, they MUST agree on using even or odd
parity. 
```

**Checksum**:
```
Check sum is a mathmatical algorithm that is applied 
to a sequence of data to create a checksum value 
which is transmitted with the data. The same algorithm
is applied to the data at the recieving end. 
If the two checksums match, the data 
transmission has been successful; if not, an error
must have occurred and a re-transmission is requested. 
```

**Majority Vote**:
```
Majority voting is another technique used to detect error.
In this scheme, each bit is transmitted three times 
(redundancy) in the hope that majority of the bits in each 
repetition will be correct. 
```
**Check Digit**:
```
Similar to Checksum, put rather than adding the numbers together and sending the sum, you put the numbers through a formula and send that along with the data
```


### 3.5.6 Representing images, sound and other data

#### Bit patterns, images,  sound  and other  data
#### Analogue and digital
#### Analogue and digital conversion
#### Bitmapped graphics
#### Digital representation of sound
#### Musical Instrument Digital Interface (MIDI)
#### Data compression
#### Encryption
