## Python Assignment

What to do:

1. Make a private repository, and add the Jupyter Notebook and data files
2. Fill in the required code to complete the Problem_Statement Jupyter Notebook.
3. Push the notebook to the main branch of your repository.
4. After the deadline, make your repository public (you will be given a reminder)

We also conducted sessions on Python for the computational astronomy bootcamp (in which we covered the first four notebooks), the recordings of which are available on the MS Teams link - https://rb.gy/uge8gk . You will also of course find resources on everything needed for this online as well, so keep googling if you're stuck at any point!

### A description of each project is available [here](https://docs.google.com/document/d/1d8R4Wz6IbfhX28kDoJ9xSoXfNyC2GZAklVd3eUjtPEI/edit)

## Overview of the Solution!

First Question:

Part1:

1.Imported required libraries and then loaded the given CSV file.
2.We renamed the columns of the StarData, deleted the NaN rows and reset the changed indices.
3.We then the stored the data required in their respective arrays with appropiate names.
4.Using the property that operations on arrays are element wise we successfully found out Absolute Magnitude.
5.Plotted the histogram of Absolute Magnitude.

Part2:

1.Then we plotted scatter plot by using scatter function.
2.As the size of the dots was a function of Apparent Magnitude, we form an array of s with relation s=12-Apparent Magnitude as described,
  so that each element will have different size based on the value of s[i], where i is any index.

Second Question:

Part:1:

1.Importing the required library and loading the data.txt file.
2.Again storing the data in corresponding arrays.
3.We then defined a function as 'Best_fit' to return the best fit line or the recession velocity by the slope intercept form relation.
4.Then we used the curve_fit function in the scipy library to get optimized values of slope and intercept.
5.Then we plotted the scatter data and the corresponding regression line.

Part2(Optional):

1.We defined  the function "Remove_Outliers", which deletes the elements where the  condition is satisfied i;e dis-mean>3*std
  and plots the corresponding graphs.
2.Again in the second part we defined the function such that it makes an array of distances of the points from the line and the
  removes the elements which follow the condition distance>5*mean, and then it plots the corresponding graphs.
  
Part:3:

1.Here we just took the value of Slope we calculated earlier and took its inverse to find the Age of the universe.
2.Also the units were appropiately converted to years.

Hence, ends the overview of the solution to the Assignment.









