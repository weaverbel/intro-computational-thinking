---
title: Pseudocode
nav: Four
---

When breaking coding problems down, **pseudocode** is a useful tool to use, regardless of what programming language will be chosen to automate your process. Pseudocode documents each step of a process so that when you begin to code, you will already have your steps arranged in a logical order. Pseudocode also provides a sense check if you want to first run your plans past people who may not be programmers. 

#### Example

Suppose we are fans of the *Lord of the Rings* novels, but we wonder how much the female character of Galadriel featured in the story compared to the male characters Frodo, Gandalf, Aragorn, Legolas and Boromir. We could flick through, say, *The Fellowship of the Ring* to check (which would be painfully slow), or we could run a short piece of code to count the number of times each character's name is mentioned throughout the story. We could document those steps in pseudocode before writing any code to be sure we have covered all the things we will need to do. 

{% include figure.html img="pseudo-example.png" alt="Pseudocode steps" caption="Pseudocode steps" width="65%" %}

*Notes*

- The [text only version](https://www.kaggle.com/datasets/ashishsinhaiitr/lord-of-the-rings-text) of *The Fellowship of the Ring* is the file the code will process.   
- The characters' names, Galadriel, Frodo, Gandalf, Aragorn, Legolas and Boromir are the values the program will look for and count.
- A `.txt` file is important for this kind of activity, as all the "smart" formatting (i.e. curly quote marks, hyphens converted to `em` and `en` dashes) that appear within a `.doc` file is stripped out when saving a `.doc` file as a `.txt` file.

------

*Spoiler alert* - Galadriel gets only **35** mentions by name compared to Frodo's **944**.
  
---------

The code that will be used to do this job is an example of a **loop**. Loops allow us to execute the same command over and over again until a certain pre-set condition has been met. In this case, the condition is to have counted all the appearances of each name in a list.

In the example above, the program will search all the way through the text of [*The Fellowship of the Ring*](https://www.kaggle.com/datasets/ashishsinhaiitr/lord-of-the-rings-text) adding up all the appearances of the first value in the list (`Galadriel`). Then it will go through the text again to do the count for the second value (`Frodo`). The same process will then be done for all the other characters respectively, and then the program will report its findings for each value. It will then stop running because the list of names has been exhausted, i.e. the condition has been met. 

The name values can also be called *variables*, because the value will vary each time the loop runs through the text. Variables are an important part of `abstraction`.

The same piece of code could be re-used for any word counting exercise by changing the list variables and the input source. That would be another example of `abstraction`.

{% include figure.html img="loop-diagram.png" alt="How loops work" caption="Loops in programming" width="65%" %}

---------

#### Practice 1. Creating backup copies of files

In a folder, we have 250 image files for which we want to create backup copies before we process the images for archiving. Manually creating 250 copies of files seems like a very boring thing to do, so we are going to automate the workflow to create the backup copies. 

Write some pseudocode of how you might automate this process.

#### Practice 2a. Tidying up

We have a large folder of files left over from a project that is now finished. The files are all sitting in the one folder which makes it hard to navigate. We want to archive the project and its files, but in the process, we want to create folders by file type, e.g., `.pdf`, `.jpg`, `.doc`, so that anyone wanting to access those particular file types can do so easily. We also want to delete files that have no file extensions. New folders will need to be created and the different files moved into them by file type. 

Write some pseudocode of how you might automate this process.

#### Practice 2b. Tidying up more carefully

In the process of doing the above, we actually made a few blunders. We accidentally deleted some files we didn't want to remove because they were mislabelled or were missing a file extension. Because this automation is a complex operation that cannot be undone, we want to make sure we don't make those kinds of mistakes again. 

One way to do that is to check we have coded the job correctly *before* we finally execute the automation. Therefore we need to first run a step that mimics what would happen if we executed the script on the files, perhaps by substituting printing the filenames to be moved or deleted to the screen or to a file rather than *actually* deleting or moving them at this stage. That way we can check we are working on the correct files and only run the final automation workflow once we are sure we have everything right.

Write some pseudocode for that step of the process.

#### Practice 3. Managing incoming data

Suppose you have a number of acoustic listening devices set up in the bush. Every day, you receive an email from each device with a data file recording that day's activity. In order to analyse the data from the devices, all the separate daily data files need to be combined weekly into a single file. It is important that each device ID is listed within a column in the combined data file to identify the different locations. 

In order to analyse the data over time, you need to append the weekly file digest to the existing, now very large, main data file. Before adding anything new, and in order to safeguard the integrity of the data, you need to create a backup of that main data file and send a copy of that backup file to your cloud storage account for safekeeping. Once the new data has been appended, you need to rename the new main data file with today's date as part of the file name, and run software against the file to ensure the integrity of the data, e.g., to check that no data is missing (which might indicate a malfunctioning device).

Write some pseudocode of how you might automate this process.

-------------------

#### Learning to program

This lesson should help you prepare to learn to code by understanding the process that coders use to break complex problems down into programmable parts. 

Links to sites that teach coding and other resources on computational thinking are listed in the following section. 

--------------

#### First, do no harm 

The automation of bureaucratic and administrative operations is speeding up data capture and service provision, "enabling more-than-human speeds of sorting and analysis. The potential drawback is that machines have no understanding of what they are doing – and sometimes humans do not either," says Professor Mark Andrejevic FAHA in this article, [Robodebt and the Dangers of Datafication: Fast Machines and Fallible Humans](https://mailchi.mp/humanities.org.au/5-minute-friday-read-mark-andrejevics-robodebt-and-the-dangers-of-datafication), which warns of the dangers of too much autonomous automation. While automation brings many benefits, it can also render decisions and analysis opaque and overly rigid. The famous phrase *'Computer says no'* from the TV show *Little Britain* is a perfect example of this kind of intransigent alibi.

Use automation, but use it wisely, and ethically, and with lashings of human oversight. 

---------

### For later

Suppose you write that file movement script and it works a treat. 

Why not get it to run every month to tidy up folders that invariably become messy over time, e.g., your computer's `Downloads` folder? 

Or, suppose you use a file naming convention that starts with `YYYY-MM-DD`. Why not run a script annually to sort and organise your documents by year? 
