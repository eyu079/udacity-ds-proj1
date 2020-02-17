# Udacity Data Science NanoDegree Project 1

This is data science Project 1 readme.
Libraries:
1. numpy
2. pandas
3. matplotlib.pyplot
4. datetime

During the Udacity course the CRISP-DM method was outlined with the following 6 points:

1. Business Understanding
2. Data Understanding
3. Prepare Data
4. Data Modeling
5. Evaluate the Results
6. Deploy

In this project, business understanding is clear - the more rentals through AirBnB the more sucessful the business is.  So, how to understand the neighbourhoods or areas which this is providing most success is important.  Or understanding what makes certain hosts more successful than others?  

Next, for data understanding it was a matter of looking at how different questions can be answered through the 3 different sets of data.  

Preparing the data.  Here the challenge was to remove "NaN" from the data set.  But also, the data type; for example the price for listing was typed as a string and required some work to use the data in numerical form.  Also, the date was also typed as string which made it difficult to use until converted to date/time type.

Evaluate the Results.  Here the data sometimes did not provide a large enough spread to warrent a valid/useful graph.  In this case, a short list or a single answer was used to answer the questions.

# Questions data used to answer:
Which neighbour has the best scores on review ratings?
What day of year in Seattle has most availability? i.e. least busiest time of year in the city?
What is the average price per neighbour to rent in?

Source code used to generate data/plots for the below blog post is 

https://medium.com/@esther.sienkiewicz/neighbourhood-traits-b01d3c5045d5
