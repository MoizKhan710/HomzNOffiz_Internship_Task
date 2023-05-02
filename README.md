# HomzNOffiz_Internship_Task

APPROACH TO THE ANALYSIS:

1. I have used Jupyter Notebook as the IDE to solve this problem statement.
2. I have Imported the required Python libraries like pandas, numpy, matplotlib etc.
3. I made dataframe of the data using pandas lib and then checked data type and NULL values for each column.
4. Several columns were having huge amount to null values so i used different appoach to handle null values of each column.
5. For the Price, Bedroom2, Bathroom and Car columns i have grouped the unique values in the rooms column and each of the Price, Bedroom2, Bathroom and Car column then took the mode of each group and filled their null values accordingly.
6. Distance and Postcode had one Null value each but I cannot drop the rows as i would loose a record to instead i will fill these with a '0' value which would indicate it as unknown information.
7. Forward filling the null values in Landsize, BuildingArea, YearBuilt, CouncilArea, Regionname and Propertycount Columns.
8. Filled zero in Lattitude and Longtitude Column as Any values cannot be filled because these are the co-ordinates of a exact location.
9. Using Matplotlib and Seaborn checked for outliers in columns using Boxplot.
10. Got the insights of the different methods of sales using Bar plot.
11. Then plotted Line plot month and year wise which gave us the sales status over months and years.
12. Also plotted Count plot for sellerG and Suburb column these plots tell us about the most active real estate agent and which suburb has most number of properties.
13. Also made a count plot for the type of houses from this plot we determined that house,cottage,villa, semi and terrace are  the most prefferd type of houses by people.
14. TO IMPROVE SALES
The count plot for real estate agent tells us about the most active agents. Using that information we will provide incentives to our agents with respect to their activity. Hence to get high incentives agents will try to improve their Activity which will ultimately improve our sales.
15. Also made a Dashboard of these visualizations on tableau.
