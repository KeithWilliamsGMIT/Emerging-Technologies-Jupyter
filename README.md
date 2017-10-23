# Emerging-Technologies-Jupyter
This repository contains the solutions to the third problem sheet on Jupyter, numpy, and pyplot given as part of my fourth year emerging technologies module in college. The problems below use the iris data set. All solutions are contained in a single Jupyter notebook file. Note that the solutions to these problems were written in Python 3.5.

# Problems to solve

## 1. Get and load the data
Search online for Fisher’s iris data set, find a copy of the data, download it and save it to your repository. If it is not in CSV format, use whatever means (Excel, notepad++, visual studio code, python) to convert it to CSV and save the CSV version to your repository also. Open your Jupyter notebook for this problem sheet, creating a new one if needed, and load the CSV file into a numpy array.

**Solution:** Downloaded the iris data set from [here](https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data) to a file called `iris.csv` in the data folder.

## 2 Write a note about the data set
In a markdown cell at the start of your notebook, write a short description of the iris data set, complete with references.

**Solution:** A description of the iris data set can be found [here](https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.names).

## 3. Create a simple plot
The dataset contains five variables: sepal length, sepal width, petal length, petal width, and species. Use pyplot to create a scatter plot of sepal length on the x-axis versus sepal width on the y-axis. Add axis labels and a title to the plot.

## 4. Create a more complex plot
Re-create the above plot, but this time plot the setosa data points in red, the versicolor data point in green, and the virginica data points in blue. Setosa, versicolor, and virginica are the three possible values of the species variable. Add a legend to the plot showing which species is in which colour.

## 5. Use seaborn
Use the [seaborn](http://seaborn.pydata.org/examples/scatterplot_matrix.html) library to create a scatterplot matrix of all five variables.

## 6. Fit a line
Fit a straight line to the variables petal length and petal width for the whole data set. Plot the data points in a scatter plot with the best fit line shown.
