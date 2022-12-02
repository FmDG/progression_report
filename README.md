# Progression Report

The above code compiles the Progression Report required for completion of the 1st year of my PhD per the QMUL requirements. The structure of the document is outlined below. This code should contain all of the files required to typeset the progression report. The Progression_Report.pdf file contains the fully compiled and typeset file complete as of 30th November 2022.

## Structure

The report.tex file is the file that needs to be typeset to generate a full report. The report.tex file contains a series of commands that are commented out describing more complicated functions that are not being used for this particular project (think indices, tables of figures, and interim cover pages). The report file includes a series of files from the FrontBackMatter folder which layout the wider structure and the three chapters outlined in the Chapters folder.

### FrontBackMatter

The folder contains four files. Their uses are outlined below:
- Environments
This is basically empty but would describe any potential unique environments built bespoke for this project. The only command is here is to direct all the figures requests towards the relevant folder.
- Macros
This contains all of the bespoke macros created for this project. There are no bespoke macros created for this project.
- Packages
This contains a list of all of the LATEX packages that have been requested for this project. The project has aimed to use as few packages as possible for this and so the packages commands are as limited as possible.
- Titlepage
This describes the title page and how it should be structured. There are a series of commands herein which are not used in this project, such as graphics for the Queen Mary University of London Crest which was thought to be a bit garish for this particular project.

### Chapters

This folder is where most of the actual content is stoed. There are four files stores herein.

- Introduction
The introduction sets out the context (background) and rationale (knowledge gaps, significance, and potential benefits) of the research; the research aims/hypotheses; and an outline structure for the rest of the report.
- Literature Review
This is the part where I demonstrate understanding of key concepts in the research area, providing detail on the research gaps highlighted in the Introduction and (if appropriate) support for any hypotheses proposed in the Introduction.
- Project Structure
This part details sampling/experimental design, methods (data sets/collection/processing/analysis) and a research timetable. The timetable should demonstrate that the thesis can be completed within three years and can be presented in the form of a Gantt Chart.
- Appendix
This is where the GANTT Chart and the supplementary figures are stored.
