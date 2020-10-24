# matplotlib_challenge
This program takes data from a mouse study for cancer drugs and visualizes the output.
## Data Cleaning
> First we evaluate the number of unique mice in the dataframe. Then we determine
>which of the mice have duplicate datapoints. We discard the mice with duplicates
>and proceed with the rest of the data.

## Summary Statistics
>We calculate the mean, median, variance, standard deviation, and standard error of the mean.
>We generate this in the same way as the previous homework and then create the same table
>using the aggregate function.

## Charting
>We create two plots in two different ways each. We calculate the number of mice in each drug
>regimen and plot a bar chart of this data using pandas and then pyplot. We then calculate
>the number of male and female mice and create a pie chart using pandas and pyplot.

## Box plot
> We evaluate the final average tumor volume for all of the promising drug regimens. We calculate
>each of the interquartile ranges and check each of the average tumor values for a specific
>drug regimen to determine outliers. We find an outlier in the Infubinol regimen and highlight it
>on the boxplot that we generate.

## Line / Scatter plots
>First we select a random mouse from the Capomulin regimen and print its tumor volume over time.
>Next, for all mice in this regimen we create a scatter plot with weight v tumor volume.
>We find that there is a positive trend between increased weight and increased tumor volume.
>We finally determine the correlation coefficient and finally plot the scatter plot data with a trendline.