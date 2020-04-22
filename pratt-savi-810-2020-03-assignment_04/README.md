
# Assignment 04

# Project Proposal

![http://www.pratt.edu/tiny_mce/plugins/imagemanager/files/Light_brown_blue22.jpg](http://www.pratt.edu/tiny_mce/plugins/imagemanager/files/Light_brown_blue22.jpg)

The **purpose of this project** is to have some **well-written** and **well-documented code** in a GitHub repository that illustrates you can write some Python code. This project is for **your** Portfolio, so pick something you are **interested in** or that's **useful** (either in some professional work or automating some task). [Learn how the project is evaluated (rubric)](https://github.com/pratt-savi-810/pratt-savi-810-2020-03-project).


#### Project Routes

There's a couple of routes you can go;

1. **Creating a Tool to Automate a Task** - usually for some task automation, less an analysis, more data engineering. 
2. **Performing Data Analysis to Answer a Research Question** - this type of project requires plots and data insights. 

Since writing the code is the challenging part. Do not think about this in scope of a normal project. **Keep your scope focused!** Keep it limited in functionality and if you finish early, you can add more features. I've seen students go down some pretty deep rabbit holes and emerge with some very disorganized projects. You could have only 30 lines of code or so, and still have a great project so long as the code is well written and the doc's are informative and it has some functionality that's useful in some capacity. Most likely someone such as a hiring manager will only glance at your Repository, so you want it to be organized and clean and very clear as to its purpose. 

## Assignment 04 Submission
You will **Fork** and **Clone this Repo** and **edit this README.md Markdown file**. This is your submission, just the link to your forked Repo and edited README.md file. This project should be the edited version of this README.md (**Markdown**) file. 

#### Learn more about [Markdown](https://www.markdownguide.org/). 

Most code editors allow editing of Markdown files, some recommended editors are;

* [Atom](https://atom.io/)
* [MacDown](https://macdown.uranusjr.com/)
* [Visual Studio Code (VS Code)](https://code.visualstudio.com/)
* [StackEdit (edit in-browser)](https://stackedit.io/)
* [Dillinger (edit in-browser)](https://dillinger.io/)
* You can even edit inside of [GitHub](https://github.com/). 

Your Assignment 04 Deliverables are listed below:

# Deliverables

You should edit the following items in-line and substitute any of the provided text with your response below for your README.md Assignment 04 submission. 


---

## Executive Summary

A _brief description_ of your final project idea. 

- **Why** are you doing this project? 
- **How** do you imagine you'll accomplish this project? 
- Is this a project **Creating a Tool to Automate a Task** or **Performing Data Analysis to Answer a Research Questio**? 

This should be a paragraph or so and provide a _high-level overview_ of your project. Again this is a summary, so think of this as the "Elevator Pitch". 

Roger interpolation, start:

(I'd earlier said that I'd do a project based on the election map, but have changed my mind.  I'm still going to see if I can turn that polling center data into a map of zones of influence, but that's something I probably won't ever have to do again, so I don't want to devote my project to it).  
- **Project objective**: To improve my skills in the area of prepping, transfering and linking data. 
- **Project goals**: 
-- To devolop an interactive web based map and graph that draw on a third party database.  -- To automate the refresh process from that database.  
-- To arrange a degree of user interactivity in specing out the map and graph.  

Roger's interpolation end

## Background

A more **detailed background** of your project, please include any information that would be useful for understanding the context of the project. This can be as long or short as you'd like. 

Roger interpolation start:
My project would focus on the kind of 'Violent incident' graphing and mapping that I'd showed you earlier.  It was that data that you were helping me assign date formatting to.  

An NGO named ACLED (Armed Conflict Location & Event Data Project) has a crew of people who scan news stories for 'violent events', which they enter into a database.  Afghanistan is one of the countries they cover.  They log over 10,000 events a year, and do a respectable job of normalizing them, even to the extent of geocoding them with coordinates and standardized place names.  They refresh their public facing database once a week.  You can feed dates, country names and event types to a 'data tool' of theirs and get back a .CSV of the results.

I want to download their data, process it into a database of my own, and link that database to a graph and a map.  Online users would be able to specify the geography and time period  that interested them and get back a graph and map.


## Resources
List any possible articles, resources or analysis or anything useful and include links and perhaps annotate a sentence as to the key findings of this resource. Or if you cannot find any resources please mention. 



#### Resources List



**Mapping Software** 
??
I have an Arcgis Online account, but would like to explore alternatives.
 
## Input Data 

#### Data Sources List 

**ACLED**
The ACLED data tool:
https://acleddata.com/data-export-tool/
Screen shot of data tool:
C:\Users\Roger Helms\Documents\ArcGIS\Projects\ACLED\ACLED_export_tool.PNG
Some documentation on the database:
ACLED codebook:  https://acleddata.com/acleddatanew/wp-content/uploads/dlm_uploads/2019/04/ACLED_Codebook_2019FINAL_pbl.pdf
Other ACLED resources:
https://acleddata.com/resources/general-guides/

**Boundary files**:
I'm pretty well set for boundary files.  I will document their provenance in the project.  A key one will be the 421 district / 34 provice version admin boundary set of 2018:
https://mapsynch.maps.arcgis.com/home/item.html?id=50ef8d9c306d43c187b70de0d629c6b5

#### Data Wish List
List and describe any type of data you'd like to include but had difficulty tracking down. 

* Data Wish List Item A - description
* Data Wish List Item B - description

## Technical Requirements

#### Python Libraries

Pandas / Geopandas - to manage the ACLED data
Matplotlib - for the graph

#### Library Wish List
[None]

## Measuring Success: 

- How will you measure your project's sucess?
	- Is there some metric you'd hope to generate from your project.  	
    Hits on the site would be my measure of success.  The key bit of information...
	- Is there some plot or visualization that will be generated? 
    An interactive web map and bar chart.

	- Is some manual task now fully automated? 

## Project Execution Plan Outline
Please include a short outline describing the steps you'd imagine going through. 

Could be as simple as;

```
- Background Research 
	- Spend some time researching the topic

- Data Collection
	- Spend time collecting and looking for additional data
	 
- Exploratory Data Analysis
 	- Summarize the input data, plot and examine any columns that may be useful. 

- Data Processing
	- A couple of steps that may be needed to Process your data. 

- Results and Conclusion 
	- Key findings
	- Was your Project Successful. 
	- Generate Assumptions and Limitations. 
```
