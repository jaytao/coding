# Introduction
This is my take on the most streamlined way to learn the fundamentals of coding. Will this be enough to get you hired? Maybe, maybe not. Theres a lot that goes into the Software Developer hiring process that isn't straight coding (believe it or not). But I think its a good start.

I try to make the sections as interactive as possible because at the end of the day, there is no substitute for repetition and trying things out yourself. **Its very important to experiment** and go off the rails when you learn programming. 

## Why Programming Is Like Cooking Analogy
Programming is less like baking, in which you measure out the exact amount of ingredients and bake at a specific time and temp to arrive at the perfect result, and more like cooking, where you have a general idea of what you're trying to make and how you get there is up to your personal skill, preference, and limitations. 

Maybe you've never diced an onion before, or you do not have a dutch oven, or are missing half the spices the recipe calls for. But you still gotta eat so you're just gonna move forward with making that dish anyways. Its not going to be perfect, but thats okay because next time you'll know what worked and didn't work and you'll be slightly better at adapting and have a better understanding of why certain rules and guidelines exist.

Theres a ton of tricks and techniques that chefs (and programmers) will accumulate over their lifetimes and all of it happens because they tried out weird stuff that will never see the light of day. Experiment enough times and eventually you'll get the hang of it.

**tldr**: Just try things out even if its not perfect in the hopes that next time you'll be a bit better

## Python
We'll be working primarily with Python because its fairly straightforward and easy to setup and still really popular and widely used. I will try my best to note certain aspects which are Python specific versus applicable to all languages, but at the end of the day the general concepts translate to all languages.

### How to Run Your Code
Theres a few ways you can run the code you write during this tutorial. In the long term, using PyCharm or the macOS terminal is better since that more closely mimics the development environment you would use at a job, but since this is just a tutorial that covers the basics, ***using an online Python interpreter*** should be fine.

There are a few free ones, but I think [programiz](https://www.programiz.com/python-programming/online-compiler/) would work fine.

#### Terminal Output
Most of my example output will be shown from my terminal as its my preferred method of developing. Its a bit easier to show the output this way instead of grabbing screenshots from Programiz.

*For example:*
```
jeff-mbp:~$ python helloworld.py
hello world
```
This is me running the `helloworld.py` program and getting the `hello world` output on the next line.

The equivalent for Programiz would be typing the contents of `helloworld.py` file (shown in the next chapter) and hitting the `Run` button. You should see the output on the right side panel

## Before We Get Started

### Learning Notes
I will also try to add notes on how I feel the best way to approach learning a topic ie: "memorize this" or "this isn't too important for now". Sometimes things will come up prematurely but its not important in the moment, and I will try to make it clear to avoid unnecessary confusion.

Programming is one of those skills where there are rules, exceptions to those rules, exceptions to the exceptions, etc, etc.

Just don't panic and take it one step at a time. Its better to understand what you are doing and how it all comes together.

### Error Handling
If you ever encounter an error thrown by Python, then read it and if you don't understand it, Google it. Thats how 100% of programmers deal with their errors. Its a normal part of coding and understanding what errors are trying to tell you is an important learned skill. That being said, I'll try to showcase common errors that occur as we go along.
