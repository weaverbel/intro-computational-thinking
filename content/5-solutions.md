---
title: Practice solutions
nav: Solutions
---

Different people might approach these practice tasks in very different ways so these solutions are suggestions only. They are offered here to provide some guidance for people who might struggle with laying out steps.

#### Practice 1. Creating backup copies of files

In a folder, we have 250 image files for which we want to create backup copies before we process the images for archiving. Manually creating 250 copies of files seems like a very boring thing to do, so we are going to automate the workflow to create the backup copies.

This is a perfect task for a loop, as the task is simple and repetitive.

{% include figure.html img="pseudo-loop.png" alt="Steps in the loop" caption="Steps in the copying loop" width="70%" %}

------------

##### Example code in the Unix shell

`for filename in "*.jpg" "*.tif" "*.png"`     
&nbsp;&nbsp;&nbsp;&nbsp; `do`    
&nbsp;&nbsp;&nbsp;&nbsp; `cp $filename backup-$filename`    
&nbsp;&nbsp;&nbsp;&nbsp; `echo $filename backup-$filename`   
`done`

-------

*Notes*

In the code example above, the loop will run through the folder creating back up copies of all the files with the file extension `.jpg`. As each file is copied, each original filename and the filename of each new file will be printed to the screen. 

Then the loop will restart and repeat the process for all the files with the file extension `.tif`, again printing the original filenames and the filenames of the new files to the screen. 

Then the loop will restart and run through the folder a third time, creating back up copies of all the files with the file extension `.png`, again printing the original filenames and the filenames of the new files to the screen. The loop will then stop.

{% include figure.html img="loop-shell.png" alt="Loop as it would be written in the Unix shell" caption="Coding a loop in the Unix shell" width="90%" %} 

-----------

#### Practice 2a. Tidying up

We have a large folder of files left over from a project that is now finished. The files are all sitting in the one folder which makes it hard to navigate. We want to archive the project and its files, but in the process, we want to create folders by file type, e.g., .pdf, .jpg, .doc, so that anyone wanting to access those particular file types can do so easily. We also want to delete files that have no file extensions. New folders will need to be created and the different files moved into them by file type.


#### Practice 2b. Tidying up more carefully


In the process of doing the above, we actually made a few blunders. We accidentally deleted some files we should have kept either because they were mislabelled or they were missing a file extension. Because this automation is a complex operation that cannot be undone, we want to make sure we don't make those kinds of mistakes again.

One way to do that is to check we have coded the workflow correctly before we finally execute the automation. Therefore we could introduce a step that mimics what would happen if we executed the script on the files, perhaps by printing the filenames we want to move or delete to the screen (or to a file) rather than actually deleting or moving them. That way we can check we are working on the correct files and only execute the final move workflow once we are sure we have everything right.

Write some pseudocode for that step of the process.

#### Practice 3. Managing incoming data
Suppose you have a number of acoustic listening devices set up in the bush. Every day, you receive an email from each device with an attached data file recording that day's activity. In order to analyse the data from the devices, all the separate daily data files need to be combined weekly into a single file. It is important that each device ID is listed within a column in the combined data file to identify all the different locations.

In order to analyse the data over time, you need to append the weekly file digest to the existing, now very large, main data file. Before adding anything new, and in order to safeguard the integrity of the data, you need to create a backup of that main data file and send a copy of that backup file to your cloud storage account for safekeeping. Once the new data has been appended, you need to rename the new main data file with today's date as part of the file name, and run software against the file to ensure the integrity of the data, e.g., to check that no data is missing (which might indicate a malfunctioning device).

Write some pseudocode of how you might automate this process.
