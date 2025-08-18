# Before we begin:

i would like to clarify that all the operations and everything explained here was done in the terminal by running "Python".


# Comments 1.1

So comments in python start with the hash character or better known as #. for example:

```
# This is a comment
>>> azanegay = 0 # This is also a comment
```

As you can see comments can be placed at the start of the line or even after the part of the code as visualised above.

But if the comment is inside of a quote it isnt a comment, just a regular text. An example:

```
>>> huza = "This is not a comment."
```

# Numbers 1.2

The interpreter acts like a simple calculator, you can type any calculation and it will run. You can use the operators `+`,`-`,`*` and `/`. They can used to perform calculations. and `()` can be used for grouping. For example:

```
>>> 2-2
0
>>> 50 + 3*3
59
>>> (15 - 5*2) / 5
1
>>> 8 / 5 # Divisions always return a floating point number.
1.6

```

The integer numbers (e.g. 2,9,10.) have type int. meanwhile fractional part (e.g. 1.69,5.420) have type float.

Divisions (`/`) always return a float. in the examle you can use `/` for varios things.

```
>>> 17 / 3 # Simple division that returns a float.
5.666666666666667

>>> 17 // 3 # floor division, this discards the fractional part.
5 

>>> 17 % 3 # the `%` operator returns the remainder of the division.
2 
>>> 5 * 6 + 2 # extra calculation.
32
```

Oh yeah, in python its possible to use the operator `**`to calculate powers. as shown below 

```
>>> 2 ** 2 #Square root of 2. simple ay? 
4
>>> 4 ** 3 # 4 to the power of 3. Fairly simple ez xd.
64

```
OHH YEHAHH thats what i was forgetting you can use the equal sign to assign a value to a varible. 

```
>>> base = 4 
>>> height = 5
>>> area = base * height # calculating the area of a rectangle. pretty nerdy xd.
>>> area
20
```

# Text 1.3

So yeah folks welcome to texts. Sooo to start we can know that python can manipulate text or well "strings" as well as numbers. This includes everying, even text and sentences. they can be enclosed in single quotes or doube quotes. Result doesnt change.

```
>>> "Azan e' gay."
"Azan e' gay."
>>> 'Bread'
'Bread'
>>> '1969'
'1969'
```

okayy so i can go and explain more but instead ill make a list you can read and at the bottom there will be exals:

- to quote a quote, we kinda gotta escape it, i think you can do this by preceding it with a  `\` or we can use other types of quotation.
- also a very useful thing is if you wanna go down a life to type more text you  can \n btw you can also use print() fr a more readble output.. 
- oh yeah also if you dont want characters to be prefaced by `\` just put an `r`.

```
>>> 'doesn\'t'
"doesn't"
>>> "doesn't"
"doesn't"
>>> phuc = 'first person \nSecond person '
>>> print(phuc)
first person
Second person
>>> print(r"\home\nerds")
\home\nerds

```
