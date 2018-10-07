# Clean Code Workshop Script

## The Programmer's Oath

[Page Link](https://blog.cleancoder.com/uncle-bob/2015/11/18/TheProgrammersOath.html)

In order to defend and preserve the honor of the profession of computer programmers,
I Promise that, to the best of my ability and judgement:

1. I will not produce harmful code.
2. The code that I produce will always be my best work. I will not knowingly allow code that is defective either in behavior or structure to accumulate.
3. I will produce, with each release, a quick, sure, and repeatable proof that every element of the code works as it should.
4. I will make frequent, small, releases so that I do not impede the progress of others.
5. I will fearlessly and relentlessly improve my creations at every opportunity. I will never degrade them.
6. I will do all that I can to keep the productivity of myself, and others, as high as possible. I will do nothing that decreases that productivity.
7. I will continuously ensure that others can cover for me, and that I can cover for them.
8. I will produce estimates that are honest both in magnitude and precision. I will not make promises without certainty.
9. I will never stop learning and improving my craft.

## Awesome Clean Code

[Github Repo](https://github.com/kkisiele/awesome-clean-code)

## Clean Code Notes

* Stefano has summarized the video explanations from Uncle Bob's Clean Code videos on his [Page](https://cianciustyles.github.io/2017/10/16/Notes-From-Uncle-Bob-s-Clean-Code-Videos/) here.

* Juan Carlos Ruiz González maintains notes for Clean Code book at [Github Repo](https://github.com/JuanCrg90/Clean-Code-Notes)

## Functions

* first tear of organization
* first place where we write code
* how to do them well
* classes hiding in your code
* classes tend to hide in large functions
* function should do one thing, do it well and do it only

### First rule of functions

* They should be small

### Second rule of functions

* They should be smalled than that

### How big should be function

* 90s * screenfull
* about 20 lines
* now screens 120 chars and 100 lines * does not apply now
* four lines, maybe five, six ok, 10 way too big
* how will the bodies of if, while, try blocks look like in 4 line fun
* they will need to be function calls themselves right

### What do all functions have in common

* they have names
* well chosen names
* well descriptive intent revealing
* function in small scope should have long descriptive names
* functions in large scope should have small names
* extract predicates of if and while into nicely named boolean functions

### Clean Code Kata TestableHtml

[Link](https://github.com/cleancode-katas/cleancode-kata-testablehtml)

### What so small functions

* so many functions
* so many classes
* we will get lost in the forest of functions and classes
* what about the function call overhead?
* With current power of computers this is very less overhead
* We will not be lost
* We will be naming our functions and classes with intention
* They act as flag posts in the forest
* We will not be lost

### Why comfortable long code is not right

* Not right for the team member
* Does not promote new members
* Creates bottlenecks and silos
* Living alone your room can be dirty but comfortable for you
* Sharing with others needs management and modularization

### What is a large function

* It is a scope which shares common variables
* It shares blocks of logic using those variables
* Actually this is a class hiding there

### Clean Code Kata - PrimePrinter

[Link](https://github.com/cleancode-katas/cleancode-kata-primeprinter)

### What should a function do

* One thing
* One abstract thing, do it well and do it only
* in both katas we seperated functions
* into different level of abstractions

### How to make function do one thing

* Extract till you drop
* the consequence is our functions will all be 4 to 5 lines long

### Clean Code Kata - VideoStore

[Link](https://github.com/cleancode-katas/cleancode-kata-videostore)

### Summary

* First Rule of functions they are small
* second rule they are smaller than that
* lots of well named functions will save lots of time
* they act as sign posts navigate through code
* most of us do not have to worry about efficiency of call stack
* making functions small will save us and all
* classes hide in long functions
* keep functions small to properly partition
* functions do one thing
* to make sure extract till you drop

## Original source

[Clean Coders Episode 3](https://cleancoders.com/episode/clean-code-episode-3/show)
has the detailed explanation of how to refactor the classes in this project
into clean code.