# <h1> Weather-condition </h1>


<img align="center" alt="coding" width="400" src="https://mir-s3-cdn-cf.behance.net/project_modules/disp/ebc4db2235034.560a96356930d.gif">
<img align="center" alt="coding" width="400" src="https://bestanimations.com/Nature/Storms/lightning-storm-animated-gif-10.gif">
<img align="center" alt="coding" width="400" src="https://mir-s3-cdn-cf.behance.net/project_modules/disp/01d9bc30971807.563b2b13c384b.gif"><br>

* In this project we will learn how to work on a real project of Data Analysis with Python. Questions are given in the project and then solved with the help of Python. It is a project of Data Analysis with Python or you can say, Data Science with Python.
<br>
<h2>Description :-</h2><br>

* Here The Weather Dataset is a time series data set with per-hour information about the weather conditions at a particular location. it records Temperature. Dew point Temperature, Realtive Humidity, Wind Speed, visibility, Pressure conditions.

<h2>Dataset :- <br></h2>
* Download the dataset for custom trainig <br>
https://drive.google.com/file/d/1JvD4Ss2yS3d9X36YkWqmqZXLamNWLSFJ/view?usp=sharing<br>
* The data is available as a CSV file. we are going to analyze this data set using the pandas DataFrame

<br>

<h2>Requirements :-</h2><br>
* Python 3.9.13<br>
* pandas<br>
<br>Windows<br>

<h2>The commands that we used in this project :- </h2><br>
* head() - it show the first N rows in the data (by default, N=5).<br>
* shape - it shows the total no. of rows and no. of columns of the dataframe.<br>
* index - This attribute provides the index of the dataframe.<br>
* columns - it shows the name of each column.<br>
* dtypes - it shows the data-type of each column.<be>
* unique() - in a column, it shows all the unique values. it can be applied on a single column only, not on the whole dataframe.<br>
* nunique() - it shows the total no. of unique values in each column. it can be applied on a single column as well as on the whole dataframe.<br>
* count - it shows the total no. of non-null values in each column. It can be applied on a single column as well as on the whole dataframe.<br>
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.<br>
* info() - Provides basic information about the dataframe.<br>



  <br>
  <br>
  
  
  Q. 1)  Find all the unique 'Wind Speed' values in the data.<br>
Q. 2) Find the number of times when the 'Weather is exactly Clear'.<br>
Q. 3) Find the number of times when the 'Wind Speed was exactly 4 km/h'.<br>
Q. 4) Find out all the Null Values in the data.<br>
Q. 5) Rename the column name 'Weather' of the dataframe to 'Weather Condition'.<br>
Q. 6) What is the mean 'Visibility' ?<br>
Q. 7) What is the Standard Deviation of 'Pressure'  in this data?<br>
Q. 8) What is the Variance of 'Relative Humidity' in this data ?<br>
Q. 9) Find all instances when 'Snow' was recorded.<br>
Q. 10) Find all instances when 'Wind Speed is above 24' and 'Visibility is 25'.<br>
Q. 11) What is the Mean value of each column against each 'Weather Condition ?<br>
Q. 12) What is the Minimum & Maximum value of each column against each 'Weather Condition ?<br>
Q. 13) Show all the Records where Weather Condition is Fog.<br>
Q. 14) Find all instances when 'Weather is Clear' or 'Visibility is above 40'.<br>
Q. 15) Find all instances when :<br>
A. 'Weather is Clear' and 'Relative Humidity is greater than 50'<br>
or<br>
B. 'Visibility is above 40'<br>
