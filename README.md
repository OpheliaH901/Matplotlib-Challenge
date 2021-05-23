# Matplotlib-Challenge
Matplotlib homework, week 4

    After importing and merging the two data files, we were able to locate the duplicate Mouse ID, by focusing on the duplicate values in the Timepoint column. Once we found the mouse that was mistakenly reported in the data, we filtered it from our dataframe, and set it as a new variable so that we could visualize the data through graphs, charts, and plots. There was actually a total of 248 mice identified with SCC tumor growth being treated through various types of drug regimens.

    In order to generate the summary statistics table, the data needed to be grouped by the Drug regimens in order to calculate the mean, median, variance, standard deviation, and SEM of the tumor volume for each. Bar graphs and pie graphs were developed to show the types of mice used in the tests and the amount used for each drug regimen. Dataframes were created break down the info needed in order to produce the visual.

Quartiles, Outliers and Boxplots

    A new data frame was created to group the Mouse IDs in order to get the maximum timepoint value for each mouse. Once created, index values needed to be reset because it needed to be merged with the filtered dataframe from the beginning of the analysis. Variables were created with the .loc function to locate the four drug regimens in our data frame. For loops helped identify the quartiles and the outliers of this sub-set. Infubinol contained the only outlier within this dataset, which indicates bad data in our set, and Capomulin is negatively skewed based on the median's position in the box plot. 

Line and Scatter Plots

    Our newly created data frame was filtered to only include one Female mouse that was treated with Capomulin. Based on the line plot, there was a downward trend in the tumor volume over the course of 45 days (red line, constant). A downward trend in the tumor volume (blue line) shows a positive impact the regimen has on skin cancer, but because the data is negatively skewed based on Capomulin's box plot, the data may be misleading and a deeper analysis will be necessary.
