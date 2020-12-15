# DataScienceProject2020
This is a data science project for an electricity company in New York to find appropriate participants to one of their energy efficient upgrade program.
The project intends to use several machine learning models to find out features for missed opportunities in joining the energy upgrade. There are two available datasets: 
  1. users' monthly electricity usage and personal information from 2014 to 2020; 
  2. users' annual electricity usage and personal information from 2014 to 2020.

In order to not include same customer's monthly information for too many times in the model, the monthly usage dataset is shrinked by grouping the data based on user ID, and then changed by using pivot table to aggregate their each year's average electricity usage. After the change, this dataset is merged with the other dataset to include all the personal information to a one big dataset.
