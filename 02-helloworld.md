# Hello World
Its become tradition that the first program anybody writes is to print out "Hello World".

We will use this as an opportunity to run our first program and make sure everything is setup correctly if you're using the terminal. If you're using PyCharm, then follow their tutorials on their site  (sorry to point you to somewhere else, but no sense in me rewriting their tutorials). If you're using an online code editor, then it should be straightforward to just hit the `Run` button or something.

**Note**: *`#` is the symbol for a comment. Python will ignore everything after it on that line. This is specific to Python, as other languages will use things like `//` to denote comments*

So lets write this bad boy.
```
# helloworld.py
print("hello world")
```

In this case, I'm telling you in the comments that the name of the file is `helloworld.py` so that when I run this later its not confusing.

`print()` is a "command" in python that just prints something back to the user. Its helpful for debugging and overall understanding. Most languages have a feature that does something similar since its such an important feature for programmers to have when writing their code.

**Note**: *the technical term for `print()` is that it is a "function". But we'll get to that later.*

So if we save the contents of the program to `helloworld.py` using whichever text editor you are familiar with and run it, it should look like this.
```
jeff-mbp:~$ python helloworld.py
hello world
```

# Experimentation
Congrats, we ran the program and it printed back our message. Feel free to try replacing the text to print something else.

`print("World Hello")`

`print(123)`

See if you can put something inside the parenthesis that breaks the program
