![](https://github.com/Kate-Pol/Biodiversity-in-National-Parks/blob/main/png%20files/Biodiversity-in-National-Parks.png)

### Codecademy take home project
---
### Project Overview
---
For this project, you will interpret data from the National Parks Service about endangered species in different parks.

You will perform some data analysis on the conservation statuses of these species and investigate if there are any patterns or themes to the types of species that become endangered. During this project, you will analyze, clean up, and plot data as well as pose questions and seek to answer them in a meaningful way.

After you perform your analysis, you will share your findings about the National Park Service.

Project Objectives:
- Complete a project to add to your portfolio
- Use Jupyter Notebook to communicate findings
- Run an analysis on a set of data
- Become familiar with data analysis workflow

Prerequisites:
- Data Visualization
- Communicating Data Science Findings

### 1. Setting Up The Project
---
We have to download all nessessary files form the website, for farther review and data analysis.
Download files from from biodiversity.zip and make sure our directory is set up for Jupyter notebook.

Double-click on it to “unzip” the folder. It should contain several items:
- Observations.csv
- Species_info.csv
- Biodiversity.ipynb

In the command line, navigate into the your venv folder, and activate Scripts folder. For required libraries you can use ![requirements file](https://github.com/Kate-Pol/Biodiversity-in-National-Parks/blob/main/requirements.txt). 
Then novigate into unzipped file directory.

Type the following into the command line: jupyter notebook This should open a browser tab.

### 2. Setting up your Git Repository
---
Create a new Git repository for this project, and connet it to the project folder on your machine. 

If you need more guidance, review the GitHub Desktop article and additional help on this [Git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf).

Main components that you will want to include:

- Jupyter Notebook
- CSV data file(s)

After work is completed we can create and update README.md file. 

### 3. Project Scoping
---
Properly scoping your project will greatly benefit you; scoping creates structure while requiring you to think through your entire project before you begin. You should start with stating the goals for your project, then gathering the data, and considering the analytical steps required. A proper project scope can be a great road map for your project, but keep in mind that some down-stream tasks may become dead ends which will require adjustment to the scope.

Hint:

Here is [University of Chicago’s Data Science Project Scoping Guide](http://www.datasciencepublicpolicy.org/our-work/tools-guides/data-science-project-scoping-guide/).

### 4. Load the Data
---
You have been given two CSV files:

species_info.csv - contains data about different species and their conservation status
observations.csv - holds recorded sightings of different species at several national parks for the past 7 days.
Hint:

Open observations.csv and species_info.csv with pandas. The datasets provided have the following columns of data:

species_info.csv:
- category - class of animal
- scientific_name - the scientific name of each species
- common_name - the common names of each species
- conservation_status - each species’ current conservation status

observations.csv:
- scientific_name - the scientific name of each species
- park_name - Park where species were found
- observations - the number of times each species was observed at park

Read over the [pandas read_csv documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_csv.html) for a refresher on how to load and look at the dataset.

### 5. Explore and Explain Data
---
Once you have your data, it’s a good idea to get acquainted with it. You should show some summary statistics and visually examine your data. Don’t forget to write out some insights that you have gained along with your analysis.

You can start to build graphs from the data by first importing [Matplotlib](https://matplotlib.org/stable/tutorials/introductory/pyplot.html) or [seaborn](https://seaborn.pydata.org/tutorial/introduction) and then making some plots!

Hint:

Some components that you may want to include (but not limited):

What is the distribution of conservation_status for animals?

Are certain types of species more likely to be endangered?

Are the differences between species and their conservation status significant?

Which species were spotted the most at each park?

More Resources:

The National Institute of Standards and Technology’s (NIST) [EDA Introduction](https://www.itl.nist.gov/div898/handbook/eda/section1/eda11.htm).

### 6. Conclusions
---
Finally we can wrap up the project. You can write a conclusion about your process and findings.

Hint:

Main components that you will want to include:

- What did you learn throughout the process?
- Are the results what you expected?
- What are the key findings and takeaways?

### 7. Create a Slide Deck
---
Once we’ve performed the analysis, we’re ready to create a slide deck. One of the most important parts of data analysis is being able to communicate the findings.

We can create a slide deck using Google Drive, Microsoft Powerpoint, or some other presentation software.

Your presentation should include the following:

- A title slide
- A section describing the data in species_info.csv. Be sure to include some (or all) of what you noticed while working through the notebook.
- A section describing the significance calculations that you did for endangered status between different categories of species.
- A recommendation for conservationists concerned about endangered species, based on your significance calculations
- A section describing the sample size determination that you did for the foot and mouth disease study
- All of the graphs that you created in the notebook

More Resources:
- ![How to use Google Slides](https://support.google.com/docs/answer/2763168?co=GENIE.Platform%3DDesktop&hl=en)
- ![Create a presentation in PowerPoint](https://support.microsoft.com/en-us/office/create-a-presentation-in-powerpoint-422250f8-5721-4cea-92cc-202fa7b89617)

### Practice Tools 🛠
---

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/jupyter/jupyter-original-wordmark.svg" title="Jupyter" alt="Jupyter" width="30" height="30"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="Python" alt="Python" width="30" height="30"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original-wordmark.svg" title="Numpy" alt="Numpy" width="35" height="35"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original-wordmark.svg" title="Pandas" alt="Pandas" width="30" height="30"/>&nbsp;
  
</div>

### Those are some examples of the plotting the data
---

<img src="https://github.com/Kate-Pol/Biodiversity-in-National-Parks/blob/main/png%20files/distribution%20of%20conservation%20status.PNG" width="550" height="300">

<img src="https://github.com/Kate-Pol/Biodiversity-in-National-Parks/blob/main/png%20files/Conservation%20Status%20by%20Species.PNG" width="550" height="300">

<img src="https://github.com/Kate-Pol/Biodiversity-in-National-Parks/blob/main/png%20files/Observations%20of%20Bats%20in%20a%20Week.PNG" width="550" height="300">


