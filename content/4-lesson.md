---
title: Pseudocode
nav: Four
---

#### Pseudocode

When breaking problems down, pasting sticky notes on a wall, or creating a structure diagram on a whiteboard can help visualise the necessary steps. 

**Pseudocode** is another useful tool which can be used regardless of what programming language you will eventually use. Pseudocode is a way of documenting each step of a process so that when you begin to code, you have arranged your steps in a logical order. It also proides a sense check if you want to run your idea past people who may not be programmers as no complex coding syntax gets in the way of understanding.

Suppose we loved the book *Little Women*, but we wonder now whether Jo got a disproportionate share of the novel's action. We could read the book again to check, or we could run a short piece of code to count the number of times each girl's name is mentioned throughout the story. We could document those steps in pseudocode before writing any code. 

| **Step** | &nbsp; |  **Notes** |
| :--- | :---: | :--- | 
| Identify the text to be used as the source for the code | &nbsp; | This will be a text only version of *Little Women*. |  
| Create a list of the four names whose frequency you want to count | &nbsp; | These will be the variables that the program will need to look for. | 
| For each instance of each name found, increment the counter for that list member by one | &nbsp; | The code will work through the file sequentially |
| Output the final counts of each variable | &nbsp; | Output could be printed to the screen or to a file |

The code that will be used to do this job is an example of a loop. Loops allow us to execute the same command over and over again until a certain condition is met. In the example above, the program will go all the way through the text of *Little Women* adding up all the appearances of the first name in the list (Amy). Then it will go through the text again to do the count for Beth. The same thing will then be done for Jo and Meg respectively, and then the program will report its findings for each name and stop because the list of four names has been exhausted, i.e. the condition has been met). 

{% include figure.html img="loop.png" alt="How loops work" caption="Loops in programming" width="85%" %}

---------

### Practice

Imagine you are designing a something. Create some pseudocode to illustrate the steps.
