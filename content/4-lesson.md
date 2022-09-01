---
title: Pseudocode
nav: Four
---

#### Pseudocode

When breaking problems down, pasting sticky notes on a wall, or creating a structure diagram on a whiteboard can help visualise the necessary steps. 

**Pseudocode** is another useful tool which can be used regardless of what programming language you will eventually use to automate your work. Pseudocode is a way of documenting each step of a process so that when you begin to code, you have already arranged your steps in a logical order. It also provides a sense check if you want to run your idea past people who may not be programmers. 

Suppose we loved the book *Little Women*, but we wonder now whether Jo got a disproportionate share of the novel's action. We could read the book again to check, or we could run a short piece of code to count the number of times each girl's name is mentioned throughout the story. We could document those steps in pseudocode before writing any code to be sure we have covered all the things we will need to do. 

{% include figure.html img="pseudocode.png" alt="Pseudocode steps" caption="Pseudocode steps" width="65%" %}

- The text only version of *Little Women* is the file the code will process.   
- The four names, Amy, Beth, Jo and Meg, are the list variables the program will look for and count.  

---------

The code that will be used to do this job is an example of a **loop**. Loops allow us to execute the same command over and over again until a certain condition is met. 

In the example above, the program will search all the way through the text of *Little Women* adding up all the appearances of the first name in the list (Amy). Then it will go through the text again to do the count for Beth. The same thing will then be done for Jo and Meg respectively, and then the program will report its findings for each name and stop because the list of four names has been exhausted, i.e. the condition has been met. 

{% include figure.html img="loop-diagram.png" alt="How loops work" caption="Loops in programming" width="65%" %}

---------

### Practice

Imagine you are designing a something. Create some pseudocode to illustrate the steps.
