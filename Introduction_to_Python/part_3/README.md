### Data visualisation for Python
This part of the workshop course is a little different to the others. 

Firstly, the Python section of the data visualisation workshop has been separated into two sections: using matplotlib, and using Seaborn. Matplotlib is the basic plotting module for Python. Seaborn is a module which makes it easier and quicker to create more visually appealing plots. However, since Seaborn is built on top of matplotlib, more complex customisation of Seaborn plots will require knowledge of how matplotlib works.

Secondly, we are introducing the Jupyter notebook (the files with `.ipynb` file extensions). This format combines markdown text with code bundled into cells. You will be able to open the notebooks using the "Jupyter Notebook" application in Anaconda Navigator. You can run the code contained in a cell by selecting the cell and hitting `Ctrl+Enter`. You can also run all cells at once but it is better to go through the cells one-by-one to get a clearer idea of what each block of code is doing. One advantage of using Jupter notebooks is that you can edit the code in the notebook yourself. We encourage you to play with the data, or the arguments given to the plotting functions to get an idea of how they work. E.g. You could change the `color="black"` part of the following code to `color="red"`, and see how it affects the plot: `sns.swarmplot(x="day", y="total_bill", color="black", data=tip_data)`

When you attempt the worksheets, you can do so either in Spyder or by creating your own Jupter Notebook file. It is likely that your solutions are going to look quite a bit different than the sample solutions we will give you, that's OK! With coding, and especially with plotting, there are often many ways of going about the same thing.


P.S. We are also providing the Jupyter Notebook files as markdown (`.md`) in case you have trouble using Jupyter Notebook. In this case, it is probably best to copy/paste the code contained in cells into the Spyder console.
