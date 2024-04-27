# Data Analytic: Week 1
What is Data?
Data refers to specific information collected and interpreted for a particular purpose. If data is not presented in a particular format, it is not useful for either computers or humans.
Data refers to specific information collected and interpreted for a particular purpose. The basic structures used in data analysis include rows and columns.

## Data Basic
### Type of Data Variable
#### 1) Category
A data type that can be stored and identified based on the name or label given to the data.
##### - Nominal
With this data, it's impossible to establish a specific order or determine superiority, as the data doesn't allow for any calculative comparisons.
Example: 
country column is nominal data because we cannot determine which one can be put in the first/last order and which one is better.

![Screenshot (839)](https://github.com/Rnovranza/Python_Week_3/assets/134476980/e3b7b36b-b6fd-4dad-9f2e-6d1b5b83e4a5)

##### - Ordinal
Ordinal data measures data that is non-numeric and the interval value is unknown.
Example: 
Rating column is ordinal data because this data uses a certain order to rank and is effective for data that requires order when evaluating. 
for example, PG (Parental Guidance) where movies with this rating can be watched by children with parental supervision. and other ratings

![Screenshot (841)](https://github.com/Rnovranza/Python_Week_3/assets/134476980/f623819a-9eaa-4685-a271-6e6fb0e05de6)

#### 2) Numeric
Data used a constant variable, to store a value in the form of a number.
##### - Discrete
A discrete value is taken from a particular data set, a data set that has a finite number of values. Can take on possible values hat can be listed out.

##### note: 
because in the netflix.csv dataset, i didn't find any example of continues data, so I replaced it with airbnb.csv
Example:
Bedrooms column is an integer, where integers are included in discrete data and can take on possible values hat can be listed out.

![Screenshot (843)](https://github.com/Rnovranza/Python_Week_3/assets/134476980/614bc832-e2d9-4212-8d96-656596e20456)


##### - Continues
A data that can be retrieved but has an unlimited number of values and of course the value is not fixed. Can possible values cannot be counted and only be described using interval on the real number line.
Example:
guest_satisfaction_overall column is a measurements, possible values cannot be counted and can only be described using intervals

![Screenshot (845)](https://github.com/Rnovranza/Python_Week_3/assets/134476980/689d5873-61e4-46a3-aca1-17ceb81e9539)


#### 3) Boolean
This data type is usually used to represent true and false values in data
Example: The boolean data is room_shared column, room_private column, host_is_superhost column

### Type of Data Categories
#### 1) Data Structures
##### - Structures data
Structured data example are name, dates, stock information, person capacity, bedrooms, etc

![Screenshot (847)](https://github.com/Rnovranza/Python_Week_3/assets/134476980/78851578-46d6-4371-a41e-fc4a4c5881c7)


##### - Unstructures data
Unstructured data example are audio, image, video, natural language, document

![Screenshot (848)](https://github.com/Rnovranza/Python_Week_3/assets/134476980/6d284146-da2c-4d93-b293-409f72208019)

#### 2) Data Categories
##### - Quatitantive
Quantitative data are collected using instruments such as rulers, scales, beakers, and thermometers.
The example below using df.describe() is a quantitative calculation because there is mean, min, max, etc.

![Screenshot (835)](https://github.com/Rnovranza/Python_Week_3/assets/134476980/05e62f98-fd70-4c7f-8269-6ddc287bb1f7)

##### - Qualitative
Qualitative data involve using your senses to observe and interpret the results.
An example is room_type, where there are several options.

#### 3) Meta Data
Metadata in data analytics refers to the descriptive or structural information about a dataset. It provides context about the data, helping analysts understand and interpret the data better. 
Example:

![Screenshot (837)](https://github.com/Rnovranza/Python_Week_3/assets/134476980/820fefa8-9a29-4151-89d1-13cfccc7f8a5)


#### 4) Big Data
Big data refers to extremely large datasets that are too complex and massive to be processed using traditional data processing applications. These datasets typically consist of structured, semi-structured, and unstructured data from various sources, including social media, sensors, online transactions, and more.

Example: https://www.kaggle.com/datasets/gabrielramos87/an-online-shop-business

## Data Cleansing
Data cleansing, also known as data cleaning, is the process of fixing inconsistencies and errors within a dataset to prepare it for analysis. 
Jupyter Notebook is a popular interactive environment for working with Python that's well-suited for data cleaning tasks due to its ability to combine code, visualizations, and text explanations.

### Imputation and Distribution
Imputation refers to the technique of filling in missing values within a dataset. Missing data can arise from various reasons, like sensor malfunctions, human error during data entry, or surveys with non-responses. Unaddressed missing values can lead to inaccurate analysis and biased results.
Distribution, on the other hand, refers to the way data points are spread out for a particular variable. Understanding the distribution helps you identify potential issues and choose appropriate imputation methods.

Example :

![Imputation and Distribution](https://github.com/Rnovranza/Python_Week_3/assets/101807673/ff74d6f3-0a80-41f5-a14b-f1023af6c040)

### Missing Value
Missing values, also known as null values, are a common challenge in data cleansing. They occur when data points are absent from a dataset, leaving blank cells or entries represented by special characters like NaN (Not a Number) in Python.

Example :

![Missing Value](https://github.com/Rnovranza/Python_Week_3/assets/101807673/c634d9a4-1188-4566-a905-bb95512763ee)

### Imputation by mode
Imputation with mode is usually carried out when finding missing values ​​with categorical values

Example :

![Screen Shot 2024-04-27 at 08 06 15](https://github.com/Rnovranza/Python_Week_3/assets/121234567/6694a92b-74bb-43c2-8630-fb7ac52853e5)

![Screen Shot 2024-04-27 at 08 06 25](https://github.com/Rnovranza/Python_Week_3/assets/121234567/5fbeb7b6-e01e-426d-8494-1b74c3226664)

### Perform data manipulation
It is not intended to change the value of data but to make the data easier to read by machines

Example :

![Screen Shot 2024-04-27 at 08 09 50](https://github.com/Rnovranza/Python_Week_3/assets/121234567/3aeb9ee8-0a28-4beb-82c3-39eb20edf8aa)

![Screen Shot 2024-04-27 at 08 10 01](https://github.com/Rnovranza/Python_Week_3/assets/121234567/cb7f841c-5426-443c-8785-74a288444234)

### Relationships between columns
Example : relationship between the room_type column and person_capacity

![Screen Shot 2024-04-27 at 08 12 56](https://github.com/Rnovranza/Python_Week_3/assets/121234567/e8546804-4f1a-48d6-897f-48502e6ad77f)

![Screen Shot 2024-04-27 at 08 13 02](https://github.com/Rnovranza/Python_Week_3/assets/121234567/81e732cb-e1e0-426e-a2d5-0da0faa80930)

## Data Manipulation 

### Aggregate data 
In the world of pandas DataFrames, data aggregation involves summarizing and combining data points to create a more concise and informative representation.

#### 1. Pivoting
Pivoting involves restructuring data from a format where each observation has multiple rows (long format) to a format where summary statistics for different categories are displayed in columns (wide format). This transformation makes it possible to condense large data sets and highlight important insights more effectively.

Example :

![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/a108192c-60b3-463a-9769-f379dcee7a09)

#### 2. Grouping
Grouping is a fundamental operation in pandas that allows organizing and analyzing data based on shared characteristics. This involves segmenting the DataFrame rows into different groups based on the values in one or more columns.

Example :

![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/6035a3a5-a73b-422e-ac00-5e37c5de3516)


#### 3. Crosstab
Crosstab is a data aggregation technique that summarizes data from a long format (multiple rows per observation) into a more concise and informative wide format (summary statistics displayed in rows and columns). It is a valuable tool for data exploration and analysis, particularly when dealing with categorical data.

Example :

![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/e28b8ef3-3b3e-4f07-adf3-9dae00b46faf)


#### 4. Concatenation
Concatenation (Concat) combines DataFrames along a specific axis (0 for rows, 1 for columns). It stacks DataFrames on top of each other (axis 0) or side-by-side (axis 1) to create a larger DataFrame.

Example :

![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/7b340acb-202c-4346-bfcd-01c043458aa1)


#### 5. Merging
Merging combines data from two separate DataFrames based on a common column or index. It allows to create a new DataFrame that includes columns from both original DataFrames while establishing a specific relationship between the corresponding rows.

Example :

![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/1257a0c0-ed4f-4847-bb0e-0b304c3ecace)


### Organize data
Data organization refers to the process of structuring and arranging data within pandas DataFrames to facilitate analysis and interpretation.

#### 1. Sorting
In the context of organized data, particularly within pandas DataFrames, Sorting refers to the process of rearranging rows based on the values in one or more columns. The goal is to create a specific order that facilitates data exploration, analysis, and interpretation.

Example :

![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/2fa8afd2-6d08-43cf-948c-c1687873a371)


#### 2. Get dummies
The get_dummies function from the pandas library performs one-hot encoding on categorical data. It takes a DataFrame with categorical columns and returns a new DataFrame with new binary columns representing each unique category.

Example :

![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/b4364b7e-ad8d-4f90-94d3-b0bc4a5ed796)


#### 3. Renaming
Renaming columns or rows in a pandas DataFrame is considered a data organization technique. It falls under the category of data wrangling, which involves cleaning, transforming, and preparing data for analysis. Renaming helps you create more meaningful and descriptive column and row names, making it easier to understand and interpret your data.

Example :

![image](https://github.com/Rnovranza/Python_Week_3/assets/165742717/f7f97bfa-07d7-424a-80dd-2d5e72360915)
