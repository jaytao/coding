# Variables

## Algebra
Do you remember learning algebra and seeing something like this?
```
y = 2x + 3
Solve for y when x = 5
```
And then the answer would be
```
y = 2 * 5 + 3
y = 10 + 3
y = 13
```

Well if you kind of recall this then congrats! You already understand variables and you can skip this entire section!! (jk don't actually do this)

The concept is similar in programming though. You are using "variables" to store values which are masked at the time of writing but then get evaluated later on when the program runs.

Lets try to run the equivalent in python:
```
# variable1.py
x = 5
y = 2 * x + 3
print(y)
```
**Note:** *the arithmetic operators `*` and `+` will be discussed later. But just know they do multiplication and addition, respectively*

Run it and it should print out `13` back to you

You can think of the conversation between the program and Python as follows:
```
Program: Hello Python. Here are the steps I want you to complete.
         I want you to save the value 5 in the variable x
Python: Okay, variable x now has the value 5
Program: I want you to multiply 2 and x together,
         then add 3, then save it to variable y
Python: Okay since I know x is 5, 2 * x would be 2 * 5 which is 10.
        Then I add 3 to 10 and get 13.
        Then I store 13 in the variable y.
        y now has the value 13
Program: I want you to print the value in y
Python: Okay, since I know y has the value 13, I will print 13
Program: Your job is done. Thanks.
```
So as we can see, using `=` assigns a value to the variable on the left side. This is why the program "remembered" that `x` is 5 and why the `print(y)` statement "remembers" that y was 13.
 
If we flip the lines where we define  `y` and `x` though, we will get an error when you run it.

Clear our what we had before and try to run this instead:
```
# variable1-error.py
y = 2 * x + 3
x = 5
print(y)
```
You should get an output like
```
Traceback (most recent call last):
  File "variable1-error.py", line 1, in <module>
    y = 2 * x + 3
NameError: name 'x' is not defined
```
Lets try to explore why this happened

**Note:** *The correct jargon is that a `NameError` was "thrown" by the program. In the world of programming, errors are thrown. Just remember that*

## NameError: name 'x' is not defined
Lets redo the conversation, but using the `variable1-error.py` program instead
```
Program: Hello Python. Here are the steps I want you to complete.
         I want you to multiply 2 and x together,
         then add 3, then save it to variable y
Python: Okay sure, let me retrieve the value of x...
        Wait, I don't know what x is !!
        Abort abort!!!
        x is not defined
        I can't proceed
```

As you can see, if you try to use `x` without first defining it, it will cause this `NameError` since Python is attempting to lookup the variable with name `x`, but it was never defined so it does not know what value it needs to use.

## Other Arithmetic Operators
The other common arithmetic operators are `-` for subtraction, `/` for division.

 `%` is the modulo operator which is fancy for "remainder". So `10 % 3` would be `1` since thats the remainder when you do `10 / 3`. 
 **% shows up pretty often in programming so its definitely worth remembering this one**.

## But....why?

So you might be thinking whats the point of this. If you know you want 
```
y = 2 * 5 + 3
``` 
then why not just type that? Or just assign `y = 13` straightaway. Why go through the trouble of assigning `x = 5` first, and then using it in `y = 2 * x + 3`??

Well, then let sit back and let me introduce this contrived example for you. Imagine we had a program that printed out some mathematical operators for the number `42`.
```
# variable2.py

# Calculate square of 42
square = 42 * 42
print(square)

# Calculate double of 42
double = 42 * 2
print(double)

# Calculate half of 42
half = 42 / 2
print(half)

# Add all of them together
total = square + double + half
print(total)
```

So lets go and run it

```
jeff-mbp:~$ python variable2.py
1764
84
21
1869
```

So it looks like it worked fine to me. Can go check your calculator if you are so inclined. 

But then the voice in your head says, what about if we did that for 100 instead of 42? So are you going to go back and replace every instance of 42 with 100? Thats 4 places you gotta do it (not including the comments). Make sure you don't miss any of them.

```
# variable3.py

# Calculate square of 100
square = 100 * 100
print(square)

# Calculate double of 100
double = 100 * 2
print(double)

# Calculate half of 100
half = 100 / 2
print(half)

# Add all of them together
total = square + double + half
print(total)
```
orrrrrr....hear me out, what if we used a variable instead?
```
# variable4.py

x = 42

# Calculate square of x
square = x * x
print(square)

# Calculate double of x
double = x * 2
print(double)

# Calculate half of x
half = x / 2
print(half)

# Add all of them together
total = square + double + half
print(total)
```

And then when we transition to using 100, we can just replace `x = 42` with `x = 100` and call it a day.

This way we save ourselves some work every time we want to do these operations for a different number, and cut down on the chance we accidentally miss a place.

If you ever find yourself reusing the same number, word, etc etc a lot, its definitely worth defining them in a variable in case you ever need to change it.

## Experimentation

**Things to try (not necessary but might be helpful)**
 1. Try to use all the operators and see if Python respects order of operations (PEMDAS). Hint: Parenthesis do work how you expect it to.
 2. What happens when you do `x = y = 5`? Dont actually do this when you're writing a program for real but its interesting.
 3. What happens when you try to assign a value to a number like: `5 = x`?
 4. What happens when you assign `x = y` but then change the value of `y`? Does `x` change?
