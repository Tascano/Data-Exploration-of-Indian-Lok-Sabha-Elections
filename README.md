# Data-Exploration-of-Indian-Lok-Sabha-Elections691_ds_dataexploration
 Assignment 1 for UMBC's Fall 2020 course CMSC 691 - Data Science under Prof. Tim Oates.

Dataset used: Indian Candidates for General Election 2019 @(https://www.kaggle.com/prakrutchauhan/indian-candidates-for-general-election-2019)
 
In a step-by-step format I have explored the dataset in-depth starting with explaining what the columns are and understanding each column.

I performed cleaning: understanding why data may be incorrect or missing and applying corrective actions.

I then proceeded to create visualisations and using them provided analysis of relationship between various variable/columns.

Lastly, I picked one variable to be a dependent variable, and two others to be predictor variables and generated a 2-D plot to show whether the predictor variables provide information (and what information) about the the dependent variable. And then explained why I think they do or do not.

Assignment:

Choose any dataset from the Open Baltimore collection except for variations of the Victim Based Crime Data that I explored in my DataExploration notebook. Choose a dataset that allows you to perform the following tasks:

Load the data into a Jupyter notebook. Explain briefly (using markdown) what the Open Baltimore website says about the dataset. Do a head(50) and tail(50) on the data frame after loading the data. Explain any observations you can make about the dataset and its quality from just that output.
Explore the data to understand what's in each of the columns. If the dataset has a very large number of columns (more than 10) you can choose a smaller subset of columns with which to work, but justify why you selected those columns. For each of the columns, but no more than 5 total columns:
Describe what the column contains (e.g., the time at which a crime was committed, or the last sale price of a house) in prose
Determine whether the column contains missing data, make a decision about how to handle them, and implement that decision
Do the same for outliers or other unusual values. Determine if they exist and, if so, implement an approach to dealing with them
Explain anything else interesting or unusual about the data in the column that you observed Note that your code for both discovering missing values and outliers, as well as dealing with them, must be included in the notebook. Add explanatory markdown as needed.
Create scatter plots of pairs of variables that you think might be related, and for two such plots do the following:
Explain why you think the two variables might be related
Show the scatter plot
Explain what the plot says, if anything, about the relationship between the variables. The explanation should be semantic. That is, don't say "x gets bigger when y gets bigger", say, for example, "it looks like crime increases later in the week, presumably because people are out later in the week and on the weekends".
Note that you do not need to plot all pairs of variables. In fact, you can do just two pairs as long as they show interesting relationships.
Pick one variable to be a dependent variable, and two others to be predictor variables. These choices should be based on your exploration above. Generate a 2-D or 3-D plot that shows whether the predictor variables actually convey information about the value of the dependent variable. Explain clearly why you think they do or do not by referring to the plot.
