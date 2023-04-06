# Pymaceuticals
### Instructions
- This assignment is broken down into the following tasks:
- Prepare the data.
- Generate summary statistics.
- Create bar charts and pie charts.
- Calculate quartiles, find outliers, and create a box plot.
- Create a line plot and a scatter plot.
- Calculate correlation and regression.

#### Prepare the Data
1. Run the provided package dependency and data imports, and then merge the mouse_metadata and study_results DataFrames into a single DataFrame.
2. Display the number of unique mice IDs in the data, and then check for any mouse ID with duplicate time points. Display the data associated with that mouse ID, and then create a new DataFrame where this data is removed. Use this cleaned DataFrame for the remaining steps.
3. Display the updated number of unique mice IDs.

![image](https://user-images.githubusercontent.com/62813833/226750787-ed6193e9-feb2-4b0c-996c-9836c1a442c8.png)


#### Generate Summary Statistics
Create a DataFrame of summary statistics. Remember, there is more than one method to produce the results you're after, so the method you use is less important than the result.
Your summary statistics should include:
- A row for each drug regimen. These regimen names should be contained in the index column.
- A column for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume.

![image](https://user-images.githubusercontent.com/62813833/226750646-11524ca5-58a7-4e1a-b77c-7887113051e7.png)


#### Create Bar Charts and Pie Charts
1. Generate two bar charts. Both charts should be identical and show the total number of time points for all mice tested for each drug regimen throughout the study.
Create the first bar chart with the Pandas DataFrame.plot() method.
Create the second bar chart with Matplotlib's pyplot methods.
2. Generate two pie charts. Both charts should be identical and show the distribution of female versus male mice in the study.
Create the first pie chart with the Pandas DataFrame.plot() method.
Create the second pie chart with Matplotlib's pyplot methods.

![image](https://user-images.githubusercontent.com/62813833/226750508-bf278aeb-1e90-45da-979c-dd53fa32e20d.png)


#### Calculate Quartiles, Find Outliers, and Create a Box Plot
1. Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, calculate the quartiles and IQR, and determine if there are any potential outliers across all four treatment regimens.
2. Using Matplotlib, generate a box plot that shows the distribution of the final tumor volume for all the mice in each treatment group. Highlight any potential outliers in the plot by changing their color and style.

<img width="460" alt="image" src="https://user-images.githubusercontent.com/62813833/230239589-6e1fa4b4-f440-4004-9eb6-6ba3546ea5ad.png">


#### Create a Line Plot and a Scatter Plot
1. Select a mouse that was treated with Capomulin, and generate a line plot of tumor volume versus time point for that mouse.
2. Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

<img width="460" alt="image" src="https://user-images.githubusercontent.com/62813833/230239497-5a5da891-307c-4170-b0ed-159005abdfd9.png">

<img width="460" alt="image" src="https://user-images.githubusercontent.com/62813833/230239444-bdcd24a2-147d-47a8-9805-3f90d412ecd8.png">


#### Calculate Correlation and Regression
1. Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment.
2. Plot the linear regression model on top of the previous scatter plot.
<img width="607" alt="image" src="https://user-images.githubusercontent.com/62813833/230239257-4f7fb1ba-9a3d-4a06-bf98-933473e1874a.png">

