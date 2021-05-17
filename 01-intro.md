# Introduction
This is my take on the most streamlined way to learn the fundamentals of coding. Will this be enough to get you hired? Maybe, maybe not. Theres a lot that goes into the Software Developer hiring process that isn't straight coding (believe it or not). But I think its a good start.

I try to make the sections as interactive as possible because at the end of the day, there is no substitute for repetition and trying things out yourself. **Its very important to experiment** and go off the rails when you learn programming. 

## Shitty cooking analogy
Programming is less like baking, in which you measure out the exact amount of ingredients and bake at a specific time and temp to arrive at the perfect result, and more like cooking, where you have a general idea of what you're trying to make and how you get there is up to your personal skill, preference, and limitations. 

Maybe you've never diced an onion before, or you do not have a dutch oven, or are missing half the spices the recipe calls for. But you still gotta eat so you're just gonna move forward with making that dish anyways. Its not going to be perfect, but thats okay because next time you'll know what worked and didn't work and you'll be slightly better at adapting and have a better understanding of why certain rules and guidelines exist.

Theres a ton of tricks and techniques that chefs (and programmers) will accumulate over their lifetimes and all of it happens because they tried out weird stuff that will never see the light of day. Experiment enough times and eventually you'll get the hang of it.

**tldr**: Just try things out even if its not perfect in the hopes that next time you'll be a bit better

## Python
We'll be working primarily with Python because its fairly straightforward and easy to setup and still really popular and widely used. I will try my best to note certain aspects which are Python specific versus applicable to all languages, but at the end of the day the general concepts translate to all languages.

### How to Run Your Code
Theres a few ways you can run the code you write during this tutorial. In the long term, using PyCharm or the macOS terminal is better since that more closely mimics the development environment you would use at a job, but since this is just a tutorial, I think using an online Python interpreter like [programiz](https://www.programiz.com/python-programming/online-compiler/) should be fine.

I'll detail some info about PyCharm and the Terminal below.

#### Terminal
Most of my example output will be shown from me running the scripts from my terminal as its my preferred method of developing. 

**Note**:, *You need to have some experience with Unix commands as well as familiarity with a text editor. Unix is an altogether different skill set that I will not be diving too deep into. If you are completely new to it, then go with the online option or PyCharm*

If you are working on macOS, Python should be installed by default.

*Run this command to check. Should get something like this on the terminal if python is installed already*
```
jeff-mbp:~$ python3

Python 3.7.4 (v3.7.4:e09359112e, Jul  8 2019, 14:54:52)
[Clang 6.0 (clang-600.0.57)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>>
```
Type `exit()` to quit.

#### PyCharm
PyCharm is an IDE (integrated development environment). Meaning its a program that runs on your computer that gives you a place to write Python on and takes care of some of the background setup. It comes with useful features like syntax checking and autocomplete and it has a free version.

### Python 2 vs 3
The most common version of Python used to be 2.7 (Python2), but then the maintainers of the language decided to release Python3 and stop supporting Python2. Theres slight differences, but enough that it will make your life annoying to constantly switch back and forth. Therefore, make sure you are using Python3 (any version should be fine)

## Before We Get Started

### Learning Notes
I will also try to add notes on how feel the best way to approach learning a topic ie: "memorize this" or "this isn't too important for now" but obviously your mileage will vary. Again, just my interpretation of the best way to learn. Programming is one of those skills where there are rules, exceptions to those rules, exceptions to the exceptions, etc, etc.

### Error Handling
If you ever encounter an error thrown by Python, then read it and if you don't understand it, Google it. Thats how 100% of programmers deal with their errors. Its a normal part of coding and understanding what errors are trying to tell you is an important learned skill. That being said, I'll try to showcase common errors that occur as we go along.
