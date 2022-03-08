The Jupyter Notebook World Happiness Data - Data Visualisation.ipynb is the Jupyter Notebook submitted in 2021 
as part of the module CMT218 Data Visualisation (MSc Data Science and Analytics, Cardiff University).

The following libraries were used within the Jupyter Notebook:

Pandas
Plotly
Plotly Express (contained within the Plotly package)
os
Scipy

1. How to install these libraries

Using pip install 

The following commands can be used:

pip install pandas
pip install plotly==4.14.3 or pip install plotly
pip install scipy



Using Anaconda (conda install)

conda install -c plotly plotly=4.14.3
conda install -c anaconda scipy
conda install -c anaconda pandas


The os package is within Python


2. Import the packages 
The first cell of code within the notebook contains all import commands for the packages needed for this Jupyter Notebook.


3. Running the code

Both visualisations use the dataset 'Final Dataset.csv', the excel workbook has been provided for reference.
There has been a code cell included to change the directory. Type the location of the '.csv' file in the 
brackets of the os.chdir() command. 

Statistical Analysis

stats module within the Scipy package.

Visualisation 1 - Plotly Express


Visulisation 2 - Plotly and Plotly Graph Objects (in the Plotly package)

After the code has been run, all scatter points are plotted. The visualisation is viewed by clicking the button of 
any of the plots. The plots can then be examined.