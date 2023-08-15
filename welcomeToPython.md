# Welcome To Python!
## By Lapis Pheonix
---

# Table Of Contents
| Name | Contents |
|------|----------|
| What is Python? | We will cover what is Python, and other specific langauge detials. |
| Why use Python? | We will cover the pros and cons of Python compaired to other languages. |
| Setting up our enviroment | Basic enviroment setup, choosing an IDE, and installing Python. |
| Basic Concepts | We will cover variables, strings, ints, bools, conditionals, printing and other smaller basics|


---

# Chapter 1 - What is Python?

What is Python? Seems like a simple question, right. Well it's more convoluted than that. Lets step back, what is a programming language? At its core, a programming language is a just a special set of keywords to tell a computer what to do for a specific task.[[1]](http://home.iitk.ac.in/~krrahul/cs300/6.pdf) There are two main types of programming languages, interpreted languages, and compiled languages. (Dont worry if you dont know what that means, its alright for now.) 

Python is a interpreted language, which means it gets converted to a computer readable format when you run it (called runtime). Python is also a "high-level" and "dynamically typed" programming language. These are terms that you learn later. 

---

# Chapter 2 - Why use Python?

There are many reasons to use Python, one of them being its an easy language to learn and get things done in! Its also used in things like:
1. AI/Machine Learning
2. Data Science
3. Automation
4. Build Websites
5. And More!

Python is a very popular language, and many companies use Python, so its a great language to learn even if its just for a Job. It looks great on an resume! Beyond its popularity, it one of the easiest languages to use to produce something, and there are Thousands of community made packages to use, so its easy to create many things. If you look around you can see Python everywhere!

While this is all true, Python isnt a perfect language, and isnt suitable for all situations. Heres why you might not want to use Python:
1. Its Very Slow. Compaired to languages like Go, Rust, or C++, and isnt suitable for very computational tasks
2. Its a high level language, which means you cant do things that something like C++ can, which is a lower level language (think like interacting directly with computer parts)
3. You cant (easily) compile Python, which means if someone else wants to use your project, they need Python installed

While there are other cons, I believe these are some of the more important ones to take note of.

---

# Chapter 3 -Setting Up The Enviroment

So, you want to use Python? Great! Before we can get coding, we have todo some chores.

Firstly, in order to use python, we need to download Python (duh)! You can click [here](https://www.python.org/downloads/) for a download link. When you're downloading python, make sure to click this button:<br>
![screenshot](https://cdn.discordapp.com/attachments/1134759865093464125/1140879586893234216/image.png)

Secondly, we need to pick our code editor (often called an IDE). There are several out there, but I always reccommend two. [Vscodium](https://vscodium.com/) and [Pycharm](https://www.jetbrains.com/pycharm/) Both are free (for Pycharm pick community option), and open source (meaning you can read the code). Here are some pros and cons of each:

## Vscodium
### Pros:
- Lightweight
- Supports VScode extensions/plugins
- More user friendly for beginners

### Cons:
- Less features than Pycharm

## Pycharm
### Pros:
- Very powerful, lots of features
- Lots of programming tools
- Plugin Support

### Cons:
- Not lightweight, a resource hog
- No juypter notebook support (for community version)
- Not all VScode extensions are supported on Pycharm


For most people, I think Vscodium will better for beginners, but you can choose either one. If you have used jetbrain products before, than I reccommend Pycharm, if not then Vscodium.


### For Windows, Vscodium Users
If youre using Vscodium, Id reccommend doing one last thing, using Python's package manager (pip) we should install `virtualenv`, this will help use keep our computer enviroment clean. You can do this by enter the following command inside the command prompt. (Access the command prompt pressing `WIN+R` and typing `cmd` and pressing `ENTER`)
```bash
pip install virtualenv
```

This should install the package we need.


Lastly, you can watch these videos on how to use your IDEs:
### [Pycharm](https://www.youtube.com/watch?v=3VmNuqfavF4)
### Vscodium:
1. [Video 1](https://www.youtube.com/watch?v=197JAS1gNKo)
2. [Video 2](https://www.youtube.com/watch?v=GZbeL5AcTgw)

If youre watching the Vscodium tutorials, please watch both videos (theyre short, I promise)


---

# Chapter 4 - Basic Concepts
Congrats, youve made it through probably the most boring part of this whole thing! Now we can get to the fun part, CODING!

In almost any language you see, whether it be a modern langauge or an ancient language, they all have basic concepts. I will cover these basic concepts in order of what I think you should learn in order.

# Variables
Variables are like containers. They hold data, anything from ints, strings,     bools, (which we cover all those shortly) or anything else. You will use variables for lots of things. How do you make a variable (also called delcaring)? Well its simple. Write the name of the variable, then an "=" then what you want to store. For example, we can hold an age, with a variable called age.
```python
age = 28
```

In this example, we declared a variable with the name `age` and gave it the value `28`. What we stored inside the variable is called an int.

Variables have simple rules:
1. A variable cannot have a symbol
2. A variable cannot start with a number
3. A variable cannot have spaces or dashes ( - ) in the name, but it can have underscores ( _ )

<br>

# Ints
Ints are short for integer, they are whole numbers. All natural numbers can be represented by ints. This also include negative numbers. You can make a int by just saying the number like:
```python
my_lucky_number = 7
```

You can add them, subtract them, anything you can normally do with math.

# Strings
A string is basically a sentence. You can contain emojis, normal words, anything (normal) inside a string. You can make a string by just saying like this:
```python
my_name = "John Doe"
```
A string can with single quotes ( ' ) or double quotes ( " ), but whatever you choose, you can to also close with that same character. You cant mix them. You can also create mutli-line strings, by instead using 3 quotes instead. Like this:
```python
random_words = '''Doge
Boris
Yanky
🍕
'''
```
You can also use either single or double quotes with multi-line strings too.

Now **you** try it! Create different strings, see what you can make!

# Bools & If Statements
A bool, or boolean is a like a yes or no question, but instead of saying yes or no we say `True` or `False`. This is used in conditionals, like if `xyz` then do `abc`. Booleans are used in `if-statments`. If statements are used to check if a condition is true. Here is one in action:

```python
is_16 = False

if is_16 == True:
    print("You can drive!")
```

Inside the code sample, we use an `if-statement`, variable, and boolean. You may have noticed I used `==` to check if it was True. The symbol `==` means "is equal to", there are also several other comparisons you can do, and you can chain conditionals, but that is for a later time.

Here is a list of all conditional symbols you can use, and their meaning:

1. `==` : Is equal to
2. `>=` : Is greater than or equal to
3. `>`  : Is greater than
4. `<=` : Is less than or equal to
5. `<`  : Is less than
6. `!=` : Is not equal to

Man, thats alot isnt it. Go ahead in try it! Create a couple of variables and use those symbols, see what happens! Dont worry if you get an error, try googling it, see what comes up and fix it! Feel free to come back to this and use this to help you. When youre ready, move on!


# Printing
Well, we have all of our code now, but it isnt doing much. So lets get some action! Lets get some text printing onto the screen! Printing is just displaying a message, whether that be a string, number, whatever.

To print something on the screen its rather simple, we just use the `print()` function. (We will conver functions in the future.) Here is our first program! Try running this:
```python
print("Hello, World!")
```

Woah! You just made text print to the screen! Congrats 🎉🎉! This your first step to a great programming carrer, hobby, or whatever. For this next part, follow along. Lets expand on this, lets create a variable called name.

```python
name = "Lapis"
```

With `print()` we can print out the value of variables, easily. Lets just start simple, lets just print the name `Lapis` (or whatever you put.)

```python
name = "Lapis"

print(name)
```
Output:
```
Lapis
```

Now that we've figured out how to print a name, go make a few more variables, print those out. For those who like a challenge, try this: Create a variable with a name, use an if statement to check if the name is equal to a different name, if it is then print something, else print something else. Feel free to use google, but really try your best. Remember its alright if you cant do it, just like any other skill, youll learn the more you practice.

## Concatenation
Right now we are just printing a name, and thats kinda boring, isnt it. Well, how about we turn that boring name into a welcome message! In Python, you can concatenate strings with variables, in several ways, but there are 3 main ways. I will show you all 3.

### 1. Using + Symbol
Using the + symbol on a string will allow us to addon to a string, here is an example.
```python
name = "Lapis"

print("Welcome to Python " + name + "!")
```

### 2. Using , Symbol
You can also use the `,` symbol, the difference between the `+` symbol and the `,` symbol is that the + symbol will not add a space around the variable youre adding, the `,` symbol does.
```python
name = "Lapis"

print("Welcome to Python", name, "!")
```

### 3. F-Strings
The most modern way of doing it, using an F-String. You can make an F string by putting either a lowercase or uppercase F before the quotations. Then add `{}` around the variable inside the string you want to add it in. (Tip: F strings also work with mutli-line strings.)
```python
name = "Lapis"

print(f"Welcome to Python {name}!")
```

All 3 ways will produce (almost) the same affect, but its reccommended you use F-Strings. Now that you have all this knowledge, try using all 3 methods of concating things. If you did the challenge ealier, try now adding concatenation to your strings. If you didnt, just make some new print statements and use all 3 methods.


### Finally, Comments
Man, that was alot huh. Well we are going to finish off last with an easy one. Comments. Comments are like notes you can leave to yourself, or whoever is reading your code. You create a command by putting an `#` symbol follow with whatever text you want. Here is several comments in action.
```python
# Calculate two variables
a = 20
b = 20

# Multiply
c = a * b

# Now print the result
print(f"{a} * {b} = {c}")
```

---

# Congratulations!
Youve just learned some of the basics of Python! I know that was probably alot of information to intake, so feel free to re-read parts of the tutorial, and make sure to practice. ***Practice is key!*** Also remember, asking for help is okay, googling is okay, infact I encourage it. Go make some new programs, try fixing them, and if you cant, move on. 

Good luck, fellow programmer.