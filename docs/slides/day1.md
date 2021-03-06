class: middle, center

<style>
  img {
    max-width: 100%;
  }

  img[alt="left bad style example"] {
    max-width: 49%;
  }

    img[alt="right bad style example"] {
    max-width: 49%;
  }
</style>

# Pre-Ada Live

In classroom conversation for day 1

Rename yourself in Zoom with
* Preferred Name
* Pronouns

---

# Hello

Introduce yourself!
* Name
* Pronouns
* What you were doing before Ada **OR** something interesting about yourself

---

# About Me - Chris McAnally

## He/Him

.left-column[
  - Pronounced: Kris (rhymes with kiss)
  - I teach at Ada CS Fundamentals and pretty much anything needed
  - Former IT Administrator/Teacher
  - Cyclist & Gamer
  - I lived overseas for about 10 years
  - 大家好！
]

.right-column[
  ![pic of me](day1_images/chrismc.png)
]

---

# About Me - Ariana Bray

## She/Her

.left-column[
  - Pronounced: Ah-Ree-Ah-Nuh (rhymes with nothing)
  - I'm a Developer Programs Engineer at Google
  - Formerly Chris' favorite student
  - I'm learning how to roller skate! 
  - At the moment I type this, I have a 301-day streak on Duolingo
]

.right-column[
  ![picture of Ari](day1_images/aribray.png)
  ]

---

# Learning Goals

## Today we will 

* Get more familiar with Ada, instructors and classmates
* Gain some practice using VS Code
* Work on learning to write more readable code
* Review Ruby data types & assignment statements
* Practice writing & talking about Ruby code

---

# Agenda

1.  Welcomes (already done)
2.  Learning Goals
3.  Review Unit 2 Exercises
4.  Getting Familiar with our editor
5.  Ruby Style Guide
6.  Ruby data types & assignment statements
7.  Debrief

---

# Peer code review: Unit 2 Exercises

Pointers for code review:
* Ruby style guides: snake_case, spaces, comments, indentation

* Are all minimal requirements followed and working?

* Are any additional, optional requirements coded and working?

* User experience
    * Are the prompts useful, educational, and sufficient for the user of the
      program who is unaware of the requirements?
    * What is the user enters information in an incorrect format? (case
      insensitive input, detailed error messages, prompt for re-entry)

---

# Workflow

Goal
* Be comfortable writing and executing programs on your machine

Tools needed
* VS Code, or another text editor
* terminal, or another terminal emulator such as iTerm2
* ruby
    * What version do you have? Run **`ruby --version`** in a terminal
* irb

---

# Turn This

![repl image](day1_images/repl.png)

---

# Into This

![VS Code & Terminal](day1_images/vs-code-and-terminal.png)

---

# Lets Try VS Code & Terminal

On your computer

- Start up Terminal
- Create a folder called `Ada` if you do not already have it with:
  - `$ mkdir Ada`
- Change into that folder with:
  - `$ cd Ada`
- Then create a JSL folder
  - `$ mkdir JSL`
  - `$ cd JSL`
- Then create a day1 folder and move into that folder.
  - `$ mkdir day1`
  - `$ cd day1`
- Create a ruby file and open it in VS Code:
  - `$ touch hello.rb`
  - `$ code .`

---

# Lets Create This File

![hello.rb](day1_images/hello-rb.png)
![Running hello.rb](day1_images/hello-running.png)

---

# Ruby Style

## Goal

- To write Ruby code that is easy to understand and maintain.
- Tools Needed
  - [Ruby Style guide https://github.com/rubocop-hq/ruby-style-guide](https://github.com/rubocop-hq/ruby-style-guide)

- Mention of Rubocop

---

# These Two Programs Do The Same Thing

What would you do to improve'em?

![left bad style example](day1_images/left-bad-style.png) ![right bad style example](day1_images/right-bad-style.png)

---

# A Good Code Style Sample

![Good code sample](day1_images/good-code-example.png)

---

# Ruby Data Types

| Data Type  	| Description 	| Example 	|
|---	|---	|---	|
| String 	| Anything surrounded by single/double <br />quotes 	| "hello", 'hello' 	|
| Integer 	| A number with no decimal 	| 1, 0, -7 	|
| Float 	| A "real" value (decimal) 	| 0.5, -2.75 	|
| Array 	| An ordered list of values 	| ['hey', 3, 7] 	|
| Symbol 	| A named object 	| :apple 	|
| Hash 	| A set of key-value pairs 	| { A: 2, B: 3, C: 27 } 	|
| Range 	| A set of values with a beginning & end 	| (2..6) or (2...7) 	|

**Question** How do you convert from one to another?

Useful tools, irb &  the `.class` method.

---

# Lets **do** something!

Goal:  
- Practice writing a program which uses keyboard input.

Exercise:

- Create a program which calculates the square footage of a room given the user enters the dimensions of the room 
- Use `gets.chomp`

---

# Example Solution

![Example gets.chomp solution](day1_images/sample-gets1.png)

--

![Example gets.chomp solution output](day1_images/example-gets-output.png)

---

# Strings Practice

- Create a program that makes only one variable (a string) and prints it out to the user.
  - The string must span multiple lines when printed
  - It should include a contraction (don’t, can’t, I’m, etc..)
  - It must also include a user-supplied string within it

--

![Example Output](day1_images/cart.png)

---

# Is there another solution?

![Cart before horse example](day1_images/cart-before-horse.png)

---

# Another Solution

![String interpolation](day1_images/interpolation.png)

---

# Assignment - When you give a set a variable to a value

![Variable Assignment](day1_images/assignment.png)

---

# Assignment - When you give a set a variable to a value

```ruby
my_career = "Software Engineer"
your_career = my_career
their_career = your_career + "ing Manager"

your_career.swapcase!

puts my_career
puts your_career
puts their_career
```


---

# Output

```ruby
14:44 $ ruby software.rb 
sOFTWARE eNGINEER
sOFTWARE eNGINEER
Software Engineering Manager
```

## Why???

--

Pass by reference...

---

# Debrief - Breakout Rooms

- What new things did you learn today?
- What topics are you still struggling with?
- What did you especially enjoy about today's class?
- What can be improved for future classes?

---

# Give us feedback

[Give us feedback](https://airtable.com/shraPA0Opxd8fzOmY)