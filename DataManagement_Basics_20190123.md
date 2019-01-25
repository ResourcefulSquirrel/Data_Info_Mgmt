---
title: Data & information management in Clancy lab
author: Katie Lee
date: 2019-01-23
---

## Basics
- Dates
    + YES: yyyy-mm-dd
    + YES: yyyymmdd (usually just as part of filenames)
    + NO: mm-dd-yyyy, mm/dd/yyyy
    + it gets confusing because Polish/European hand-written dates are usually dd-mm-yyyy, while U.S. hand-written dates are usually mm-dd-yyy
- README documents
    + a text document (.txt) that contains relevant information for the project.
    + Should include funding sources, acknowledgements, equipment used for data collection, staff, rough inventory of sample types, etc.
- Spreadsheets
    + Should include PII in the filename if it has personally identifiable information in it
    + Should have a README tab in the .xlsx version, where you list the variables, units, etc.
    + Should *not* have calculations or analyses in the data-storage/data-entry sheet -- make a copy, save it with a different name in another directory (computer folder) where you are working on your project
    + Should have the date it was last saved or updated in the filename
    + Should export it to a .csv version (with date in file name) for analysis
    + **BEWARE** Excel likes to "help" reformat stuff for you, especially dates and anything that Excel thinks might be a date. This makes problems in the data set, and can be avoided (ask Katie for more info about that later)

## Our major projects
Our naming convention for ongoing projects: **YYYYc-###** aka year[character]-(numbers)

### Polish/Polish American project (incl Sto Lat Health & Hormones)
- 2014P-0xx Pilot data collected in Poland in field season of 2014 for Kate's endometrial health project. Includes physical activity data, physical activity data, hormones for a menstrual cycle, endometrial thickness, blood sample, anthropometry, blood spots
- 2014P-1xx week-long version of study for Mary's preliminary dissertation work. 
- 2015P-2xx Data collection for Kate's endometrial health project
- 2015P-3xx week-long version of study
- 2016A-4xx Polish-American portion of study, no endometrial health. Some interview data. Some bone density
- 2016A-5xx Polish-American week long study version
- 2017P-6xx Data collection for Katie's dissertation. includes bone density. No endometrial thickness, no blood spots.

### GAMES (Girls Advancing in Math, Engineering, and Science)
- 2013-# (before we started the naming conventions)
- 2014G-0xx, 2015G-1xx, 2016G-2xx, 2017G-3xx, 2018G-4xx...

### Women in Science
- 2017W-0xx
- ?

## Where are our data & information?

1. [Box](box.illinois.edu)  Need to clean this out some, including moving PII/PHI into [Box Health Data Folders](https://hipaa.uillinois.edu/protecting-phi-with-box-health-data-folders/). Notice that almost all spreadsheets and working documents (vs scanned pdfs, for example) have a date in the title
2. [REDCap](http://redcap.healthinstitute.illinois.edu) currently transitioning for the Polish/Polish-American project; plan to move GAMES there soon
3. [Slack](clancylab.slack.com) Communication, posting information (*not research data*), asking questions, etc.
	- Add yourself to channels
	- When you have a question/comment for a specific person, DM them
	- When responding to a post, make a Thread
	- You can tag specific people using @[their username] vs. @channel or @everyone
	- The goal is to share information fairly quickly, without accidentally spamming everyone
	- You can adjust your notifications, and you should expect others have done so as well
4. [Trello](trello.com) More task-specific detailed lists of work to do.


## Readings about data:
-  Wickham. 2014. [Tidy Data (preprint)](http://vita.had.co.nz/papers/tidy-data.pdf), journal version available [here](https://www.jstatsoft.org/article/view/v059i10)
-  Broman & Woo. 2017. [Data Organization in Spreadsheets (preprint)](https://peerj.com/preprints/3183/), journal version available [here](https://www.tandfonline.com/doi/full/10.1080/00031305.2017.1375989)
-  Kross, et al. 2017. [The democratization of data science education (preprint)](https://peerj.com/preprints/3195/)
-  Bryan. 2017. [Excuse me, do you have a moment to talk about version control? (preprint)](https://peerj.com/preprints/3159/), journal version [here](https://www.tandfonline.com/doi/full/10.1080/00031305.2017.1399928)
-  Parker. 2017. [Opinionated analysis development (preprint)](https://peerj.com/preprints/3210/)
-  Ellis & Leek. 2017. [How to share data for collaboration (preprint)](https://peerj.com/preprints/3139/), journal version [here](https://doi.org/10.1080/00031305.2017.1375987)
-  McNamara & Horton. 2017. [Wrangling Categorical Data in R (preprint)](https://peerj.com/preprints/3163/), journal version [here](https://doi.org/10.1080/00031305.2017.1356375)
-  Verde Arregoitia, et al. 2018. [Good practices for sharing analysis-ready data in mammalogy and biodiversity research](http://www.italian-journal-of-mammalogy.it/Good-practices-for-sharing-analysis-ready-data-in-mammalogy-and-biodiversity-research,101564,0,2.html)
-  PeerJ collection: [Practical Data Sciences for Stats](https://peerj.com/collections/50-practicaldatascistats/)

## Resources on Campus
- [Research Data Service](https://www.library.illinois.edu/rds/)
- [Scholarly Commons](https://www.library.illinois.edu/sc/)
- [Data Carpentry](https://datacarpentry.org/lessons/)
- [Software Carpentry](https://software-carpentry.org/lessons/)
- [UIUC iSchool](https://ischool.illinois.edu/degrees-programs/courses)

