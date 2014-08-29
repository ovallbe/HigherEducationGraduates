#Workings

This file should keep all my progress and the steps done to achieve the project. 


###Objective

The objective is to merge all the data in a Raw Working file. 

###Tools

My main idea was to do this with some programming language, but at the moment my Python knowledge is quite primitive and I will try to do this in R. 

For this reason I will have to base this in my R and Excel knowledge (because the data use to be stored in excel files). 
Using Macros for the Excel files is also another option. 


###Data

The data is located in the [AQU](http://www.aqu.cat/) web, the 2014 survey edition is located [here](http://www.aqu.cat/estudis/ilaboral_2014.html#.VADcKfl_uYI), where we can read that the survey contains a population of 28.000 graduates, containing the 2010 graduates of the old Degree study (2007 for Medicine), Master's graduates of 2010 and 2011 and Phds from 2009 and 2010.

AQU creates a series of reports analyzing and comparing the data for the different studies. The reports are at different level, from study level to branch or field of study. 
For my interest i will focud on the Study level reports, in which I can downlad a bunch of data for each study. 

The interesting part is that, aparently, if needed I could recreate the source data from the original indicators because I have the real population and the sample used for the survey. 

This is the [link](http://www.aqu.cat/uploads/insercio_laboral/enquesta2014/humanitats.html) in which are listed the different reports by study. The studies separated in five webs ordered by their field of studies (Humanities, Social Sciences, Health, Technical fields and Experimental Sciences). 


###Steps

The main steps, which may include some intermediate tasks and processes. 

####STEP 1: Download
Aparently my first step should be to create a script to download recurrently the whole reports. It is possible to download them in pdf or excel format, the latest is going to be my option to work with. 


####STEP 2: Extract

This could be the more complicated part, to extract the data from the formated excel reports to a raw format. 
The data for each study is in 19 tabs with a format that is not exacly the same in each one. 

My first impression is to use VBA to do this part of the job, however my aim is also to practice with R or Python. We will see.

####STEP 3: Merge

Merge all the data in a raw and consistent format

####STEP 4: Data Analysis

Work with the data








