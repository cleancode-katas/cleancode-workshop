# Clean Code Workshop Session 02

## Functions

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

## Form

* Comments should be rare, and supposed to take our whole attention, and readers should be glad it’s there.
* It should be a prerogative of a developer to write code that expresses itself. In this light, comments can be seen as failures.
* Over time, comments degenerate into lies because usually the code changes but the comment does not.
* Worthwhile comment are:
  * legal comments
  * informative comments (e.g., the format a regular expression is trying to match)
  * TODO comments
  * public API comments
  * expression of intent comments
* Bad comments include:
  * mumbling
  * redundant explanations
  * mandated redundancy
  * journal comments
  * big banner comments
  * closing brace comments
  * attribution comments
  * HTML in comments
  * non-local comments

## Clean Code Kata - Comments

[Link](https://github.com/cleancode-katas/cleancode-kata-comments)
