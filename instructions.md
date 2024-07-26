
# Name of Assignment

## Objective

> *I can create and name a project folder in Visual Studio Code.*
> 
> *I can add files to my folder in VS Code.*
> 
> *I can edit files I've added to my folder in VS Code.*

## General Specifications

- Add a comment block to your Python script, like so:
```python
# Abraham Lincoln
# 24 MAR 20XX
# Intro to Python Variables
```
- Use short, descriptive filenames and names for your variables
- Write your variable and filenames in lowercase

## Finished With This Activity?

- Submit the URL to your repo on Google Classroom


## PRIMM Activity

> PRIMM stands for (P)redict, (R)un, (I)nvestigate, (M)odify and (M)ake.
>
> PRIMM is a technique developed in the United Kingdom (UK) for teaching students how to read, understand, and write code.


### (P)redict

Study this code snippet and predict what it will do when you execute (run) it.

```
# Part 1
greeting = 'Good morning!'
print(greeting)
```

### (R)un

In the `main.py` file in this repo (repository), click the editing pencil and add the two lines of Python code shown under *(P)redict* to your Python file.

I will show you how to download and run your `main.py` file during another lesson.

### (I)nvestigate

- Is the `print` statement in Part 1 written in uppercase or lowercase?
- What do you think Python would do if you typed `Print` rather than `print`?
- How do you think Python would react if you typed `print(Greeting)` instead of `print(greeting)`?


### (M)odify

Under `Part 1` in your `main.py` file, add a second block of code that looks like this:

```
# Part 2
greeting = 'Good morning ' # Note the space after the g in morning
first_name = 'Abraham'
last_name = 'Lincoln'

full_sentence1 = f'{greeting}, {first_name}!'
full_sentence2 = f'{greeting}, {last_name}!'

print(full_sentence1)
print(full_sentence2)
```

### (Make)

Now add a third code block to the bottom of your script.
- Add a Python comment that says 'Part 3'
- Change the value of the variable `greeting` to a different time of the day
- Assign your first name to the variable `first_name`
- Assign your last name to the variable `last_name`
- Assign the name of your home school to a **NEW** variable called `school`
  -  Use an `f-string` to build and then display on your screen a sentence similar to this one:
 
  > My name is Mike and I attend Bellaire High School.

