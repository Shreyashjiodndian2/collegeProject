# pythonsp500-robo-advisor-edition

Repo with all files and data needed for Python for Financial Analyses, Robo Advisor edition.

# Summary

This repo contains the Jupyter notebook and Python script with the full code for my "Python for Finance:  Robo Advisor Edition" post, as well as the excel file initially read in as the sample portfolio, using pandas, and the csv files generated from the Jupyter notebook.  Using a virtual environment, Python 3.6, and the libraries listed in the requirements.txt file, you can run a Plotly Dash dashboard locally based on the csv files generated from the Jupyter notebook.

To recreate the entire analysis, I recommend setting up a virtual environment (described below), loading the requirements.txt file into the virtual environment (also described below), and ` `pip install`  ` or `  `conda install` ` any additional packages -- the explanations for how to accomplish all of this should either be described below or provided in the virtual environment link below. 

---

## Relevant posts where you can find the tutorial

1. Medium: https://towardsdatascience.com/python-for-finance-robo-advisor-edition-36571e0fd48e
2. Personal blog:  https://kdboller.github.io/2019/04/06/python-for-finance-robo-advisor-edition.html

## Getting set up

1. Clone this repository:  ``https://github.com/Shreyashjiodndian2/collegeProject``; or 
2. Hit 'Clone or download' on the main repo page in order to grab the Jupyter notebook, python script and the sample excel file.

## Note on Anaconda distribution and Python Notebook

I highly recommend that you download the [Anaconda distribution](https://www.anaconda.com/download/).  You can also run the notebook without Anaconda using ` `pip` ` to install the required packages, however Anaconda is the industry standard for data science.

## Python Version and Virtual Environments  

It is recommended that you have Python 3.6 or greater so that you can run the Plotly Dashboard locally with the provided csv files.  

I strongly recommend setting up a virtual environment. I manage all of my virtual environments with Anaconda.  

[Here](https://medium.freecodecamp.org/why-you-need-python-environments-and-how-to-manage-them-with-conda-85f155f4353c) is a very thorough explanation on how to set up virtual environments within Anaconda.

## Requirements

For any packages not distributed under Anaconda, e.g., the Yahoo Finance package fix, you can do the following in your virtual environment:  ``pip install [name of package]``.

## How to use the notebook

* Run the notebook by opening the Jupyter notebook in your favorite editor.
* import ``Insomnia_2022-06-05.json`` into insomnia.
* Run the server using ``python3 -m flask run``.
* Let the server run for a few minutes and let it show ``server is running``.
* Edit the Insomnia url to point to the server.
