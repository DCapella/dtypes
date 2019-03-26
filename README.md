# Python Data Types
This challenge was supposed to be about the different data types, however, it was about learning something new for me. Not about dtypes but about how to read stdin from python. Thankfully, u0b34a0f6ae, had the answer of using fileinput.

# Challenge
1. Declare 3 variables: one of type int, one of type double, and one of type String.
Easy Enough.

```
# Declaring int, float, string.
i = 4
d = 4.0
s = 'HackerRank'
```

2. Read 3 lines of input from stdin (according to the sequence given in the Input Format section below) and initialize your  variables.
This was the tricky part, but got it after some quick research.

```
# Import
import fileinput
...
# Initialize items as fileinput object
items = fileinput.input()

# Declaring input int, float, string.
ii = items[0]
dd = items[1]
ss = items[2]
```

3. Use the + operator to perform the following operations: 
    1. Print the sum of  plus your int variable on a new line.
    2. Print the sum of  plus your double variable to a scale of one decimal place on a new line.
    3. Concatenate  with the string you read as input and print the result on a new line.
<br/>    
Too fun.

```
# Sum of ints
print(i + ii)

# Sum of floats
print(d + dd)

# Concatenation of strings
print(ss + s)
```

# Conclusion
* Learned a new module, `fileinput`.
* Had fun.
* Good practice.


# Acknowledgements
* [u0b34a0f6ae](https://stackoverflow.com/questions/1450393/how-do-you-read-from-stdin)
* [HackerRank](https://www.hackerrank.com/)
