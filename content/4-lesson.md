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

#### Practice 1. Tidying up

We have a large folder of files left over from a project that is now finished. The files are all sitting in the one folder which makes it hard to navigate. We want to archive the project and its files, but in the process, we want to create folders by file type, so that anyone wanting to access just the documents or the images can do so easily. We also want to delete any temporary files from the folder or files with no file extensions. New folders will need to be created and the files moved into them, although we want to make sure any hidden files are excluded from the move. 

Write some pseudocode of how you might automate this process.

#### Practice 2. Tidying up more carefully

In the process of doing the above, we actually made a few blunders. We accidentally deleted some files we didn't want to remove because they were mislabelled or were missing a file extension. Because this automation is a complex operation that cannot be undone, we want to make sure we don't make those kinds of mistakes again. One way to do that is to check we have coded the job correctly before we finally execute the automation. Therefore we need to include a step that mimics what would happen if we executed the script on the files, e.g., by printing to the screen the filenames to be moved or deleted rather than deleting or moving them. That way we can check we are working on the correct files and only run the actual tasks once we are sure we have things right.

Write some pseudocode for that step of the process.

-------------------------------

#### Operationalising tasks

Suppose you write that script and it works a treat. Why not get it to run every month to tidy up folders that invariably become messy over time, e.g., your Downloads folder? Or, suppose you use a file naming convention that starts with `YYYY-MM-DD`. Why not use the script to run annually to organise your documents by year? 

----------------------

#### Learning to program

This lesson should help you prepare to learn to code by understanding the process that coders use to break complex problems down into programmable parts. 

Links to sites that teach coding and other resources on computational thinking are listed in the following section. 

---------

### Practice

Your organisation is aiming to register attendees for an event. Past attendees will already have a profile on your system, so one step is to check whether a would-be registrant already has a profile, or will need to register for a new one. New users will also need to indicate whether they are over 18. You need to capture and verify the email address of new registrants. Create some pseudocode to list the steps of this process.
