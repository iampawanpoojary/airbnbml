
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This project utilizes default packages within the Anaconda distribution of Python for the majority of the analysis. 

However, you will need to install plotly if you haven't already done so before. See [Getting Started with Plotly for Python](https://plot.ly/python/getting-started/).

In addition, if you would like to display the plotly visualizations within the jupyter notebook, then you will need to install the orca commandline utility and the psutil and requests Python libraries. See [Static Image Export in Python](https://plot.ly/python/static-image-export/).

The code should run with no issues using Python versions 3.*.


## Project Motivation<a name="motivation"></a>

I used the Seattle Airbnb data to understand the following:

1. How listing cost is impacted by property type around a neighborhood ?
2. In regards of property type, how varied are the neighborhoods?
3. To what accuracy level can we predict listing price?


## File Descriptions <a name="files"></a>

There is one notebook available here to address the questions above.

Please note that the notebook utilizes Plotly for a majority of the visualizations. Dependencies for doing so on your own local machine are mentioned above in the Installations section. 

The Plotly visualizations' output will not appear when viewing in Github, so please go to NBViewer at the following address:

https://nbviewer.jupyter.org/github/iampawanpoojary/airbnbml/airbnb_ml.ipynb

The data is in the listings.csv file, which was downloaded from [Kaggle](https://www.kaggle.com/airbnb/seattle).

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Credit to Airbnb for providing the data. Licensing information can be found at the [Kaggle page](https://www.kaggle.com/airbnb/seattle) and the original source from [Airbnb Inside](http://insideairbnb.com/get-the-data.html).
