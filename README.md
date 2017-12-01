# OpenChapters

## Purpose
This repository contains a series of LaTeX files and associated figures for chapters that are part of the OpenChapters project.  This project collects individual open source chapters on a variety of topical areas; via the web site http://OpenChapters.web.cmu.edu the user can then select a number of chapters and automatically type set them into a nice book format.  This could be useful once we reach a critical mass of chapters; instructors could them compose their own custom course notes based on the available chapters.  The open source (Creative Commons) license model allow for individual authors to contribute their chapters, which will be edited by either Tony Rollett or Marc De Graef at CMU to put them in the correct format for this project.

## Generating the PDF file
You can generate the main.pdf document if you have a fully functional LaTeX installation.  First, clone the repo to some location on your hard drive using

*git clone ssh://github.com/OpenChapters/OpenChapters*

Then typeset the main.tex file using the standard pdflatex command. The main.tex has instructions for the arara typesetting engine to perform all the individual LaTeX/makeindex/biber runs needed to get the whole thing done.
 
## Funding Acknowledgement
This document is created as part of the research activities carried out with financial support from a Vannevar Bush Faculty Fellowship program (ONR # N00014-16-1-2821).