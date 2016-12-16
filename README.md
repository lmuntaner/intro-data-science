# Introduction to Data Science Setup Instructions

This is a repo from an exercise at the Cambridge Coding Academy - Intro to Data Science bootcamp.

### Primer on Pandas

Throughout the bootcamp we will be working with a python library called `pandas` that is very useful for data handling. To get the most from the course, it is worth to have a look at [this primer](https://github.com/cambridgecoding/intro-to-datascience/blob/master/pandas_primer.ipynb) that covers all the functionality that we will be using.

### Install Python

Install Anaconda (**Python 2.7**) from:  [https://www.continuum.io/downloads](https://www.continuum.io/downloads)
This includes python 2.7.9 and the necessary libraries we will be using: "numpy", "scipy" and "scikit-learn"

### Install Packages with pip

Open your terminal and check whether you have the "pip" function installed by typing pip (and enter).
If you do not have pip installed, check the link: [https://pip.pypa.io/en/latest/installing/](https://pip.pypa.io/en/latest/installing/). (If installing via the terminal/command line, ensure you are in the directory where you have downloaded the file "get-pip" or if using chrome right-click on the link to download, save to desktop, and simply double click on the executable).

You may need to use `sudo pip install` (for OSX, *nix, etc) or run your command shell as Administrator (for Windows) to be able to perform the installation of the following individual packages:

    (sudo) pip install seaborn
    (sudo) pip install Plotly

If you already have any of the previously-mentioned libraries installed, you can update them to a newer version using the syntax:

    pip install <package> --upgrade

where `<package>` can be any of the libraries mentioned above.


### Install git and sign up on GitHub (optional)

**This step is only required if you are using git clone and not download in the next step**

Install git if you don't have it: [http://git-scm.com/](http://git-scm.com/)

Sign up for a GitHub account or sign in if you have one: [github.com](https://github.com)


### Clone or download the code from the CCA GitHub repository

You can create a copy of the provided code on your local machine by using the "git clone" command on your console:

    git clone git@gitlab.cambridgespark.com:pub/intro-to-datascience.git

Alternatively, click on the Download button above and select "Download ZIP".


### Finalise the setup

Open and run the "[load_libraries.ipynb](http://gitlab.cambridgespark.com/pub/intro-to-datascience/blob/master/load_libraries.ipynb)" file, and check whether the libraries have been successfully loaded.

To execute the notebook, in your terminal run:

    ipython notebook load_libraries.ipynb

* You can run the notebook document step-by-step (one cell a time) by pressing **shift + enter**.
* You can run the whole notebook in a single step by clicking on the menu Cell -> Run All.
* To restart the kernel (i.e. the computational engine), click on the menu Kernel -> Restart. This can be useful to start over a computation from scratch (e.g. variables are deleted, open files are closed, etc...).
* Click on the menu Help -> User Interface Tour for an overview of the Jupyter Notebook App user interface.
