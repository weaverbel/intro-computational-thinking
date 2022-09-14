---
title: Pseudocode
nav: Four
---

When breaking problems down, **pseudocode** is a useful tool which can be used regardless of what programming language you will eventually use to automate your process. Pseudocode documents each step of a process so that when you begin to code, you will already have arranged your steps in a logical order. Pseudocode also provides a sense check if you want to first run your plan past people who may not be programmers. 

#### Example

Suppose we loved the book *Little Women*, but we wonder now whether Jo got a disproportionate share of the novel's action. We could flick through the book again to check (which would be very slow), or we could run a short piece of code to count the number of times each girl's name is mentioned throughout the story. We could document those steps in pseudocode before writing any code to be sure we have covered all the things we will need to do. 

{% include figure.html img="pseudocode.png" alt="Pseudocode steps" caption="Pseudocode steps" width="65%" %}

- The text only version of *Little Women* is the file the code will process.   
- The four girls' names, Amy, Beth, Jo and Meg, are the values the program will look for and count.
  
---------

The code that will be used to do this job is an example of a **loop**. Loops allow us to execute the same command over and over again until a certain condition is met. 

In the example above, the program will search all the way through the text of *Little Women* adding up all the appearances of the first value in the list (Amy). Then it will go through the text again to do the count for the second value (Beth). The same process will then be done for Jo and Meg respectively, and then the program will report its findings for each value. It will then stop because the list of four names has been exhausted, i.e. the condition has been met. 

The name values can also be called *variables*, because the value will vary each time the loop runs through the text.

The same piece of code could be re-used for any counting exercise by changing the list variables and the input source.

{% include figure.html img="loop-diagram.png" alt="How loops work" caption="Loops in programming" width="65%" %}

---------

#### Learning to program

This lesson should help you prepare to learn to code by understanding the process that coders use to break complex problems down into programmable parts. 

Links to sites that teach coding and other resources on computational thinking are listed in the following section. 

---------

### Practice

Your organisation is aiming to register attendees for an event. Past attendees will already have a profile on your system, so one step is to check whether a would-be registrant already has a profile, or will need to register for a new one. New users will also need to indicate whether they are over 18. You need to capture and verify the email address of new registrants. Create some pseudocode to list the steps of this process.
