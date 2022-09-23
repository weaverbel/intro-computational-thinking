---
title: Computational thinking in programming
nav: Three
 
---

*Decomposition* is crucial in any kind of problem breakdown, but especially so in programming. The computer must be told **precisely** what to do, and in what order, so problems must be broken down into discrete parts and each section coded appropriately.

Suppose we want to find the ten words most commonly used in a text. How might we go about that?

#### Linear code

While there are many different ways to do this task, this is one way, where all the commands are run in a linear sequence, e.g.,

{% include figure.html img="count-words.png" alt="counting words in a text" caption="Counting words in a text" width="60%" %}

First we save the file in `.txt` format to eliminate all the "smart" formatting created by programs like Word (as they would otherwise introduce a messy bunch of extraneous characters). Then we progressively eliminate everything from the text that is not a word, i.e. punctuation. 

Converting all the words to lower case means we will end up with a single version of each word - not two. This is important because, to a computer, `Word` (starting with an upper case letter) does not equal `word` (starting with a lower case letter) - it treats them as two separate entities. 

By replacing spaces with `new line` characters, each word will end up on its own line, which makes them easy to sort alphabetically and then count.

Each part of the sequence would need to be individually programmed. Fortunately, programmers can adapt code that others have already used to do similar tasks, such as code to identify letter, number or word frequency. This is where the computational thinking skill of *pattern recognition* comes in - identifying similar code that can be used for or adapted to the specific problem you want to solve. 

--------

#### Branching code

Programming rarely works in such a linear fashion. Code generally includes branching so that different pathways can be taken, depending on whether or not certain conditions are met, e.g., different responses to a `Yes/No` or `True/False` decision, as in the example here.

{% include figure.html img="workflow.png" alt="Branching code" caption="Branching code" width="90%" %}

----------------

#### Practice

Our friends have finally made it out of the bush and back to civilisation. Their experience, while unpleasant, has not put them off bushwalking. Draw a structure diagram of the planning they need to do for next time to avert another disaster.
