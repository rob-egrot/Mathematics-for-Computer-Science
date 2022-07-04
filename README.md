# Mathematics-for-Computer-Science
Notes and other course materials I created for a course for new grad students at Faculty of ICT, Mahidol University.

Materials are written in LaTex (purists be warned, I make no promises about the style or quality of my code). 

There are files for notes and homework (with option to make solutions visible). These should by default be compiled into a master document, 
which will include homework solutions as an appendix. To compile a document without solutions just remove or comment out the appendix.
The .tex file for this document can be found in the 'combined notes' folder. If you change the folder stucture or file names, you'll have to change the references
in the .tex files too.

To compile the homework sheets (with or without solutions) as stand-alone documents you need to uncomment the creation of a \prefix command.
This command is used as a kind of hack in the main document to avoid duplicating labels when files are input twice.
Some exercises reference results in the notes, so these will have to be changed manually to avoid unknown references in a stand-alone file.

There are also files for slides and solutions for selected homework problems (created with Beamer). These can be found in the 'slides' folder.
