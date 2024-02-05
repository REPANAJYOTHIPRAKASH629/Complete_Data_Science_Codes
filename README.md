# Complete_Data_Science_Codes

<u><b> NumPy Functions</b></u>


NumPy provides a wide range of functions for efficient numerical operations on arrays in Python. 

1. np.array(x): Creates a NumPy array from a Python object x.
2. type(x): Returns the type of the object x.
3. np.zeros(()): Creates an empty NumPy array with all elements set to zero.
4. np.ones(()): Creates an empty NumPy array with all elements set to one.
5. np.random.rand(): Generates a random float between 0 and 1.
6. np.random.rand??: Generates a random array of shape (?,?) with values between 0 and 1.
7. np.random.randint??: Generates random integers between low and high (inclusive) with shape (?,?).
8. np.random.choice([]): Selects k elements randomly from an empty array without replacement.
9. np.full((3,4),10): Creates a full array of shape (3,4) with value 10.
10. np.eye(): Creates an identity matrix of size n (default: 1).
11. np.arange(): Generates an array of integers from start to stop (exclusive) with step size step.
12. np.linspace(): Generates an array of num evenly spaced values between start and stop (inclusive).
13. x.ndim(): Returns the number of dimensions of the array x.
14. x.shape(): Returns a tuple containing the dimensions of the array x.
15. x.reshape(): Reshapes the array x into a new shape.
16. x.size(): Returns the number of elements in the array x.
17. np.transpose(): Transposes the array x.
18. np.vstack(()): Stacks arrays vertically.
19. np.hstack(()): Stacks arrays horizontally.
20. np.concatenate(()): Concatenates arrays along an existing axis.
21. np.sin(x): Calculates the sine of the elements in x.
22. np.cos(x): Calculates the cosine of the elements in x.
23. np.sqrt(x): Calculates the square root of the elements in x.
24. np.mean(x): Calculates the mean of the elements in x.
25. np.median(x): Calculates the median of the elements in x.
26. np.std(x): Calculates the standard deviation of the elements in x.
27. np.min(): Returns the minimum value in the array.
28. np.max(): Returns the maximum value in the array.
29. np.sort(x, kind = 'mergesort'): Sorts the elements in x in ascending order using the specified sorting algorithm.
30. np.dot(x,y): Calculates the dot product of x and y.
31. np.full(): Creates a new array with all elements set to a given value.
32. np.diag([]): Creates a diagonal matrix with the given elements on the diagonal.
33. x.dtype(): Returns the data type of the elements in x.
34. x.flatten(): Flattens the multi-dimensional array x into a one-dimensional array.
35. np.datetime64(): Creates a datetime64 object with the given time value.
36. np.linalg.lstsq(): Solves a system of linear equations using least squares.
37. np.add(): Adds two arrays element-wise.
38. np.sum(x): Calculates the sum of the elements in x.

<u><b> Pandas Functions</b></u>

1.	Creating DataFrames:
•	pd.DataFrame(): Create an empty DataFrame.
•	pd.read_csv(): Read data from a CSV file into a DataFrame.
•	pd.read_excel(): Read data from an Excel file into a DataFrame.
•	pd.read_sql(): Read data from a SQL database into a DataFrame.
2.	Data Exploration:
•	df.head(): Display the first few rows of a DataFrame.
•	df.tail(): Display the last few rows of a DataFrame.
•	df.sample(): Randomly sample rows from a DataFrame.
•	df.info(): Display a concise summary of a DataFrame.
•	df.describe(): Generate descriptive statistics of a DataFrame.
•	df.shape: Get the number of rows and columns in a DataFrame.
•	df.columns: Get the column names of a DataFrame.
3.	Data Manipulation:
•	df.drop(): Drop specified labels from rows or columns.
•	df.fillna(): Fill missing values in a DataFrame.
•	df.replace(): Replace specified values in a DataFrame.
•	df.rename(): Rename columns in a DataFrame.
•	df.sort_values(): Sort a DataFrame by specified columns.
•	df.groupby(): Group data in a DataFrame based on specified criteria.
•	df.pivot_table(): Create a pivot table in a DataFrame.
4.	Merging and Concatenating:
•	pd.concat(): Concatenate DataFrames along a particular axis.
•	pd.merge(): Merge two DataFrames based on specified keys.
5.	Indexing and Selection:
•	df[] or df.loc[] or df.iloc[]: Select columns or rows from a DataFrame.
•	df.at[] or df.iat[]: Access a single value in a DataFrame.
6.	Aggregation and Statistics:
•	df.mean(), df.median(), df.sum(): Calculate mean, median, and sum.
•	df.min(), df.max(): Find minimum and maximum values.
•	df.std(), df.var(): Calculate standard deviation and variance.
7.	Handling Time Series Data:
•	pd.to_datetime(): Convert a column to datetime format.
•	df.resample(): Resample time series data.
8.	Miscellaneous:
•	df.apply(): Apply a function along the axis of a DataFrame.
•	df.isnull(), df.notnull(): Check for missing or non-missing values.



<b>Matplotlib</b>
1.	Basic Plotting:
•	plt.plot(): Create line plots.
•	plt.scatter(): Create scatter plots.
•	plt.bar(): Create bar plots.
•	plt.hist(): Create histograms.
•	plt.pie(): Create pie charts.
•	plt.boxplot(): Create boxplots.
•	plt.errorbar(): Add error bars to a plot.
2.	Axes and Labels:
•	plt.xlabel(), plt.ylabel(): Set the labels for the x and y axes.
•	plt.title(): Set the title of the plot.
•	plt.legend(): Add a legend to the plot.
•	plt.grid(): Add a grid to the plot.
•	plt.xlim(), plt.ylim(): Set the limits of the x and y axes.
3.	Annotation and Text:
•	plt.text(): Add text to the plot.
•	plt.annotate(): Annotate a specific point in the plot.
4.	Figure and Subplots:
•	plt.figure(): Create a new figure.
•	plt.subplot(): Create subplots within a figure.
•	plt.subplots(): Create multiple subplots in a single call.
5.	Color and Style:
•	plt.color(): Set the color of the plot elements.
•	plt.linestyle(), plt.marker(): Set the line style and marker style.
•	plt.plot(..., label='label'): Specify labels for the legend.
6.	Saving and Displaying Plots:
•	plt.show(): Display the plot.
•	plt.savefig(): Save the plot to a file (e.g., PNG, PDF).
7.	Customizing Ticks and Tick Labels:
•	plt.xticks(), plt.yticks(): Customize the tick locations.
•	plt.tick_params(): Customize various aspects of ticks and tick labels.
8.	3D Plots (with mplot3d toolkit):
•	from mpl_toolkits.mplot3d import Axes3D: Import the 3D plotting toolkit.
•	ax = plt.axes(projection='3d'): Create a 3D subplot.
9.	Colormaps and Colorbars:
•	plt.cm: Access predefined colormaps.
•	plt.colorbar(): Add a colorbar to the plot.
10.	Miscellaneous:
•	plt.style.use(): Set the style of the plot.
•	plt.close(): Close a figure.
•	plt.tight_layout(): Adjust subplot parameters for better layout.

