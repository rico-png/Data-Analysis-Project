# PROJECT REVIEW




# Analysing Supermarket Data Across the Country- Company XYZ

Company XYZ owns a supermarket chain across the country. Each major branch located in 3 cities across the country recorded sales information for 3 months, to help the company understand sales trends and determine its growth, as the rise of supermarkets competition is seen to increase.The data folder contains datasets from three different branches; Lagos, Abuja and Port Harcourt. Each data file from the branches contains the same attribute information.

To-Do - Write a short project description here.

 # Project Steps.

Step 1: 
Loaded 3 different csv dataset or files. Each of the dataset are made up 3 Branches namely Branch A = Lagos branch, B = Abuja branch, C = Portharcourt. The .csv files was passed in List using .glob. The 3 files was joined together as one dataset using pd.concat and the dataset was read using pd.read_csv format.

Step 2:
Pandas was imported to convert dataset to Dataframe while numpy was also used to Numerical computation. seaborn and matplotlib was also use for plots. i used the .head() to preview the dataset, the isnull to check for missing values. i also used the .info() to see the summary of the dataframe. The data contains 1000 rows and 17 columns. 

key things i noted was that the highest rating is 10 and lowest is 4.0. while the maximum gross income is 17874. we also noticed that the highest unit price as 35985 and minimum as 3661.

Step 3: 
Here i dealth wih DateTimee features. I convert Date to date and time into the date format using pd.to_datetime. i also extracted extracted the hour, Day,Month and Year from our Date and Time Column

Step 4: 
I was able to get Unique Value in Column iteration and i got a categorical column. i now used .unique().tolist() function to get the unique value from each categorical column.

Step 5: 
Here firstly i did a groupby object with City column using and aggregate function was used to get the sum and mean. Also determined the gross income across all cities and it was gotten that Portharcourt has the highest. Did a Unit price and Quantity analysis, Here Lagos has the Quantity and Unit Price across all Cities.

Step 6: 
Data Visualization. I used charts and plots to create visualization to answer some questions like Cites with the highest Sles, Most used payment methods across cities and branches  then many more.


# Insights

Here i outlined and explained the insights i got from analysing the dataset

1) The dataset is made up of 3 unique branches, in 3 different states, 2 gender, 6 product line and 3 payment method
2) Portharcourt has the highest gross profit
3) Lagos has the highest Unit price and Quantity, Rating and gross margin percentage across all Branches
4) Fashion accessories was rated higher than any other product line followed by Food beverages.
5) Food beverages has the highest gross income compared to other Product line

# Future Work

1) More columns can be added to get more clearer and concised analysis to know which product customers prefer like colour column
2) Product line can still go more granular to for better analysis.

# Standout Section

1) Analyzed the Product line to get the one with the highest rating
2) I compared the Product line with regards to Ta to get the one that pays more tax
3) i did the agregation of sum and mean together.

# Executive Summary.

To-Do - Include your Executive Summary document in your repository.
