---
title: Computational thinking in programming
nav: Three
 
---

*Decomposition* is really important in programming. The computer must be told precisely what to do, and in what order, so problems must be broken down into discrete parts and each section coded appropriately.

Suppose we want to find the ten words most commonly used in a text. How would we go about that?

#### Linear code

While there are many different ways to do this task, this is one way, where all the commands are run in a linear sequence, e.g.,

{% include figure.html img="count-words.png" alt="counting words in a text" caption="Counting words in a text" width="60%" %}

First we save the file in `.txt` format to eliminate all the "smart" formatting added in by programs like Word. Then we progressively eliminate everything that is not a word, i.e. punctuation. 

Converting all the words to lower case means we end up with a single version of a word - not two. This is important because, to a computer, `Word` does not equal `word` - it treats them as two separate entities. 

By replacing spaces with new line characters, we end up with each word on its own line, which makes them easy to sort and count.

Each part of the sequence would need to be individually programmed. Fortunately, programmers can adapt code that others have already used to do similar tasks, such as code to identify letter, number or word frequency. This is where the computational thinking skill of *pattern recognition* comes in - identifying similar code that can be used for or adapted to the specific problem you have. 

--------

#### Branching code

Programming rarely works in such a linear fashion. Code generally includes branching so that different pathways can be taken, depending on whether or not certain conditions are met, e.g., different responses to a `Yes/No` decision, as in the example here.

{% include figure.html img="workflow.png" alt="Branching code" caption="Branching code" width="90%" %}


#### Practice

You have been asked to establish a decentralised contact tree for your local walking group. Draw a structure diagram for the steps you would take to achieve that. 
