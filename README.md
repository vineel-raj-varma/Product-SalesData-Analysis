# Product Sales Analysis Using Python Pandas and Python Matplotlib


Here I took the advantage of Python Pandas & Python Matplotlib to analyze and answer real world business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

Let me explain how I took this data and performed some real world data analysis to this particular sales data.

Firstly I imported all the libraries that are necessary to perform tasks.

After importing the necessary libraries I read the data and it has 12 months of data so I merged them into one single data set and performed all the operations accordingly.

I started by cleaning data. Tasks that were included during that particular section:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

Once I have cleaned up our data a bit, I moveed to data exploration section. In this section I explore 6 high level business questions that were related to our data:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?
- What product sold the most in each month?

To answer these questions I went through many different pandas & matplotlib methods. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Performed some statistical operation by using .mean()
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs
