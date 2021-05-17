# Hello World
Its become tradition that the first program anybody writes is to print out "Hello World".

So lets write this bad boy. Copy the following into Programiz and hit `Run`  
```
# helloworld.py
# i'm a comment, just like the line above me
print("hello world")
```
It should print `hello world` for you.

Lets break down what these 3 lines do.

## Comments
Programmers use comments in code to write notes to themselves and other teammates to better understand the code, or to help keep the code readable. Comments are ignored by the program so no need to stress over the formatting or syntax, as long as its readable by other humans.

`#` is the symbol for a comment in Python. Everything after on the line will be ignored. `#`  is specific to Python; other languages like Java use  `//` to denote comments instead.

In this program, lines 1 and 2 are comments since they begin with `#`.

**Note:** *You can put `#` in the middle of a line as well. Everything to the left will be read as code, and everything to the right will be read as a comment* 

Line 1 is a comment telling you that the name of the file is `helloworld.py` so that when I run this later its not confusing.

Line 2 is a comment just to reinforce what a comment is =]. Otherwise it serves no real purpose

## print()
`print()` is a "command" in python that just prints something back to the user. Its helpful for debugging and returning values back to the user. Most languages have a feature that does something similar since its such an important feature for programmers to have when writing their code.

It will attempt to print whatever goes in between the `()`. So in this case, on Line 3, we gave it `"hello world"` so it attempted to print that back to us. I will explain in a later section why it did not print the quotes.

**Note**: *the technical term for `print()` is that it is a "function". But we'll get to that later.*

# Experimentation
Congrats, we ran the program and it printed back our message. Feel free to try replacing the text to print something else.

**For example**:
`print("World Hello")`
or
`print(123)`

See if you can put something inside the parenthesis that breaks the program
