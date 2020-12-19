< [GMIT Data Analytics](https://web.archive.org/web/20201029063153/https://www.gmit.ie/computer-science-and-applied-physics/higher-diploma-science-computing-data-analytics-ict) | [Table of Contents](https://github.com/E6985) | [README](https://github.com/E6985/pda-numpy-random-simulation/blob/main/README.md) >

![GMIT](https://github.com/E6985/pda-numpy-random/blob/main/img/gmit.png?raw=true)

## Programming for Data Analysis - Project 2020
## Due (Extended): last commit on or before January 3rd, 2020

Undergraduate of Computing (Data Analytics) at Galway-Mayo Institute of Technology. This repository contains the project instructions for the ``Programming for Data Analysis`` module in 2020. The assessment is worth 50% of the marks for the module. Completed in a single [Jupyter Notebook](https://nbviewer.jupyter.org/github/E6985/pda-numpy-random-simulation/blob/main/Programming-for-Data-Analysis-Project-2020.ipynb).

## Project

Since the Second World War many events have changed the world in extraordinary ways. The Cold War brought about the Space Race, the creation of the World Wide Web, the 2001 September 11th terrorist attacks in New York city and today Ireland and the rest of the world are tackling the SARS-CoV-2 (Covid-19) Pandemic which has resulted in the deaths of over 1.5 million people as of 3rd December 2020 [[...] Worldometer, "COVID-19 Coronavirus Pandemic," [worldometers.info](https://web.archive.org/web/20201203190732/https://www.worldometers.info/coronavirus/), December 2020.].

This project forms part of the ``Programming for Data Analysis`` module of the Higher Diploma in Data Analytics presented by Galway Mayo Institute of Technology. It involves creating a dataset by simulating a real-world phenomenon. The chosen real-world phenomenon is the Covid-19 Pandemic from day zero of the Irish epidemic on February 28th, 2020 to the lowest 14-day incidence rate recorded on July 3th, 2020 when the national 14-day incidence rate was 2.98 cases per 100,000 population [[...] Department of Health, "Statement from the National Public Health Emergency Team - Thursday 22 October," [gov.ie](https://web.archive.org/web/20201122235048/https://www.gov.ie/en/press-release/6eb15-statement-from-the-national-public-health-emergency-team-thursday-22-october), October 2020.] 

Rather than collecting data related to the Covid-19 Pandemic, instead modelling and synthesising data in Python using the ``numpy.random`` package. Simulating/synthesising data based on this phenomenon.

Project specification indicates choosing a real-world phenomenon that can be measured with at least 100 data points across at least four variables. Investigating the types of variables involved, likely distributions and their relationships with each other. This is not about just creating a random dataset but rather to pick a phenomenon, research it, and figuring out what sort of variables could be collected that relate to the phenomenon. Determining reasonable values for each of the variables and how the variables depend (relate) to each other.

Synthesising/simulating a dataset closely matching the properties as possible. Determining what the variables should look like and how they relate to each other, creating the dataset based on the rules or properties discovered in the research. 

Detailing research findings, investigations completed, variables involved and the relationships to each other, the simulation is to be implemented in a Jupiter notebook.

While the main task in this project is to create a synthesised dataset, actual data generated is not of interest. Instead the research investigations completed in creating the dataset is of must interest because presumably, there will be some random element in the generation of the data, following some sort of distribution. Rerunning the Jupyter notebook on a different system will produce a different randomly generated dataset with the same properties.

The project is about simulation. The synthesised dataset will be based on Irish Government daily Press Releases relating to the National Public Health Emergency - Covid-19. Providing insight on how the data is modelled based on literature where available from the Irish Epidemiological Modelling Advisory Group, chaired by Professor Philip Nolan. The dataset can be found [here](https://github.com/E6985/covid-19-ireland/blob/master/src/dataset/covid-19-ireland.csv) and is updated daily.

#### Variables (Covid-19 ralated):

- cumulative daily number of infections - ``cases`` 
- cumulative daily number of admissions to hospital - ``hospital`` 
- cumulative daily number of admissions to intensive care units - ``icu`` 
- cumulative daily number of deaths - ``deaths``

#### Marking Scheme
1. ``25%`` - Research - Investigation of the package as demonstrated by references, background information, and approach.

2. ``25%`` - Development - Clear, well-written, and efficient code with appropriate comments.

3. ``25%`` - Consistency - Good planning and pragmatic attitude to work as evidenced by commit history.

4. ``25%`` - Documentation - Concise descriptions and plots of theoretical and practical aspects of problems.

#### Getting Started
- Keeping in mind the impression given to someone who is looking at this repository, this submission is to provide direct evidence of each of the items listed in each category - ``Research`` - ``Development`` - ``Consistency`` - ``Documentation`` - refer ``Marking Scheme`` above.

1. Research:

	- ***Investigation of the package as demonstrated by references, background information, and approach***: References will be in the format:

		- [task-number.number] authorNames, referenceTitle, locationWebsiteBookVideo, dateMonthYear.

	- Demonstrating work completed in the submission with good references and not just for the problem but for level of understanding of the problem.

	- Code comments will include details of package, module, function, object, method, attribute if applicable to demonstrate understanding of software documentation and libraries used.

2. Development:

	- ***Clear, well-written, and efficient code with appropriate comments***: Using Jupyter Notebook markdown cells to summarise concise workings. 

	- Individual code statements will have single Jupyter Notebook code cell unless user-defined functions are created. 

	- As much as possible use ``Style Guide for Python Code`` [Guido van Rossum](https://web.archive.org/web/20201029095211/https://www.python.org/dev/peps/pep-0008/). User-defined coding conventions to be given separate section - refer ``Coding Conventions`` - within README as and when presented (note good commits do not change many different files - when a user-defined coding convention is represented within a Jupyter Notebook then the commit completed will include an update to this README file - this will be the only time this will happen given that to update README every time is wasteful):- 

3. Consistency:

	- ***Good planning and pragmatic attitude to work as evidenced by commit history***: This README will form the template for this and all future tasks/projects. Git commit to include within the blurb the number of days outstanding before deadline.

	- Endeavour to submit work every day worthy of a git commit. At best 4/5 times per week. Later presentation of topics/sections will require more commits to ensure equal proof of work for all before the deadline.

	- Correctly use git history by putting in a little blurb - 2/3 lines. 

	- Commits to highlight changes made since the last commit so that reviews of the git history can demonstrate compartmentation of work into the different sections.   

4. Documentation - 

	- ***Concise descriptions and plots of theoretical and practical aspects of problems***: Comments to be very concise for ease of readability. 

	- Descriptions of code requiring further explanation will be presented in Jupyter Notebook markdown cells prior to code execution.   

#### Considerations

- The four listed categories - ``Research`` - ``Development`` - ``Consistency`` - ``Documentation`` - are each worth 25%. 

- Designed not only to be about programming but also about looking at information - data - manipulating the data and coming up with techniques. 

- Sometimes the most complex algorithms are counter-intuitive but do work and have been proven to work. Sometimes only a few lines of code is required to complete a topic/section but to obtain full marks it is not good enough to submit the lines of code. Must explain how the algorithm was developed and the reasoning behind why/how the code works.

- Jupyter Notebook text formatting/presentation to be tidied up closer to the deadline.

#### Coding Conventions

- variable/name/functions - start with letters as follows

| Example       | Signify 		          |
| ------------- |:-----------------------:|
|	f        	|	user-defined function |

| Example       | Signify 		          |
| ------------- |:-----------------------:|
|	n        	|	name - no variables   |

#### Prerequisites

- Require Python to be loaded on your local machine. Recommend downloading and installing Anaconda.

https://www.anaconda.com/download/

#### Execute Jupyter Notebook

- The software must be downloaded and run on a machine as follows:

	- Clone the repository with the following command:

	``git clone https://github.com/E6985/pda-numpy-random-simulation.git``

    - Run Jupyter Notebooks from the repository with the following command:

	``jupyter notebook``

    - Open notebook - Programming-for-Data-Analysis-Project-2020.ipynb

    - Once running within the Jupyter environment can navigate with ease - links are plentiful.

	- Notebook links will not work on github given that github renders as static HTML.

- If not running Jupyter notebook code cells - alternative to downloading and running on a machine: 

	- Render Jupyter notebook [here](https://nbviewer.jupyter.org/github/E6985/pda-numpy-random-simulation/blob/main/Programming-for-Data-Analysis-Project-2020.ipynb)