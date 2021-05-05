< [GMIT Data Analytics](https://web.archive.org/web/20201029063153/https://www.gmit.ie/computer-science-and-applied-physics/higher-diploma-science-computing-data-analytics-ict) | [Table of Contents](https://github.com/SeanOhAileasa) | [README](https://github.com/SeanOhAileasa/pda-numpy-random-simulation/blob/main/README.md) >

![GMIT](https://github.com/SeanOhAileasa/pda-numpy-random/blob/main/img/gmit.png?raw=true)

## Programming for Data Analysis - Project 2020
## Due: last commit on or before January 6th, 2021

Undergraduate of Computing (Data Analytics) at Galway-Mayo Institute of Technology. This repository contains the project instructions for the ``Programming for Data Analysis`` module in 2020. The assessment is worth 50% of the marks for the module. Completed in a single [Jupyter Notebook](https://nbviewer.jupyter.org/github/SeanOhAileasa/pda-numpy-random-simulation/blob/main/Programming-for-Data-Analysis-Project-2020.ipynb).

## Project

Since the Second World War many events have changed the world in extraordinary ways. The Cold War brought about the Space Race, the creation of the World Wide Web, the 2001 September 11th terrorist attacks in New York city and today Ireland and the rest of the world are tackling the SARS-CoV-2 (Covid-19) Pandemic which has resulted in the deaths of over 1.5 million people as of 3rd December 2020.

This project forms part of the ``Programming for Data Analysis`` module of the Higher Diploma in Data Analytics presented by Galway Mayo Institute of Technology. It involves creating a dataset by simulating a real-world phenomenon. The chosen real-world phenomenon is the Covid-19 Pandemic from day zero of the Irish epidemic on February 28th, 2020 to the lowest 14-day incidence rate recorded on July 3th, 2020 when the national 14-day incidence rate was 2.98 cases per 100,000 population. 

Rather than collecting data related to the Covid-19 Pandemic, instead modelling and synthesising data in Python using the ``numpy.random`` package. Simulating/synthesising data based on this phenomenon.

Project specification indicates choosing a real-world phenomenon that can be measured with at least 100 data points across at least four variables. Investigating the types of variables involved, likely distributions and their relationships with each other. This is not about just creating a random dataset but rather to pick a phenomenon, research it, and figuring out what sort of variables could be collected that relate to the phenomenon. Determining reasonable values for each of the variables and how the variables depend (relate) to each other.

Synthesising/simulating a dataset closely matching the properties as possible. Determining what the variables should look like and how they relate to each other, creating the dataset based on the rules or properties discovered in the research. 

Detailing research findings, investigations completed, variables involved and the relationships to each other, the simulation is to be implemented in a Jupiter notebook.

While the main task in this project is to create a synthesised dataset, actual data generated is not of interest. Instead the research investigations completed in creating the dataset is of must interest because presumably, there will be some random element in the generation of the data, following some sort of distribution. Rerunning the Jupyter notebook on a different system will produce a different randomly generated dataset with the same properties.

The project is about simulation. The synthesised dataset will be based on Irish Government daily Press Releases relating to the National Public Health Emergency - Covid-19. Providing insight on how the data is modelled based on literature where available from the Irish Epidemiological Modelling Advisory Group, chaired by Professor Philip Nolan. The dataset can be found [here](https://github.com/SeanOhAileasa/covid-19-ireland/blob/master/src/dataset/covid-19-ireland.csv) and is updated daily.

#### Variables (Covid-19 ralated):

- cumulative daily number of infections - ``cases`` 
- cumulative daily number of admissions to hospital - ``hospital`` 
- cumulative daily number of admissions to intensive care units - ``icu`` 
- cumulative daily number of deaths - ``deaths``

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

	``git clone https://github.com/SeanOhAileasa/pda-numpy-random-simulation.git``

    - Run Jupyter Notebooks from the repository with the following command:

	``jupyter notebook``

    - Open notebook - Programming-for-Data-Analysis-Project-2020.ipynb

    - Once running within the Jupyter environment can navigate with ease - links are plentiful.

	- Notebook links will not work on github given that github renders as static HTML.

- If not running Jupyter notebook code cells - alternative to downloading and running on a machine: 

	- Render Jupyter notebook [here](https://nbviewer.jupyter.org/github/SeanOhAileasa/pda-numpy-random-simulation/blob/main/Programming-for-Data-Analysis-Project-2020.ipynb)