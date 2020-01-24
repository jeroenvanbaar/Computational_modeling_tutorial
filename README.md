# Computational modeling tutorial

#### Goal
Provide practical tools to start building trial-level psychological models of behavioral data.

#### Sub-goals / targets (will be updated as we go along)
1. Defining various models for an Ultimatum Game dataset
2. Simulating task data using the different models
3. Determining 'model fit' (the similarity between observed data and a model). This will cover least squares, log likelihood, and choice rules.
4. Fitting a model to task data using gradient descent
5. Model comparison
6. Posterior predictive checks
7. Model/parameter recovery
8. Model types (RL, utility, DDM, etc) – this is more like a bonus. We'll work with models relevant to the group.

#### Getting started
1. Install latest Python 3.x (not 2.x) using an Anaconda distribution at https://www.anaconda.com/distribution/#download-section. If you already have Anaconda on your computer (of any version), you can skip this step.
2. Create a Python 3.7 environment called something like 'comp_model' using the command listed on <a href='https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf'>this conda cheat sheet</a>.
3. Activate your environment, install the package manager PyPI in it using ```conda install pip```, and then use PyPI to install (at least) the following packages: numpy, pandas, matplotlib, seaborn, scipy, jupyter. PyPI works in the following way: ```pip install <package_name> <package_name> <and so on...>```.
4. Create a clean folder for this tutorial, ```cd``` to the folder, and launch a Jupyter Notebook using the command ```jupyter notebook```.
5. Make a new 'sandbox' notebook and get comfortable with behavioral data analysis in Python by attempting to do the following things: 1) generate some random data in two variables of equal length and make a scatter plot using matplotlib; 2) generate some data for a linear relationship between two variables (e.g. age and height of schoolchildren), put them in a Pandas dataframe with 2 named columns, and use Seaborn to create a scatterplot with regression line; 3) create a Pandas dataframe with height data for 5 age groups and use Seaborn to turn this into a barplot with errorbars and an overlaid stripplot or swarmplot. Google is your friend!

#### Not-required reading
Daw, Nathaniel (2009). Trial-by-trial data analysis using computational models. http://www.princeton.edu/~ndaw/d10.pdf

#### Other useful tutorials
Den Ouden, Hanneke & Jill O'Reilly (2015). Models of learning. http://hannekedenouden.ruhosting.nl/RLtutorial/html/dataAnalysisTopPage.html [includes Matlab code]
