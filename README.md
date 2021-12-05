# Personal-Data-Set
Personal Data Set For Data 115

## Significance
I grew up on a dry-land wheat farm, so wheat has always been a part of my life. I chose to further infestigate this data to get a better understanding of how wheat yields vary from state to state and county to county.

## Processing
This data is describing the yield and total number of acres of wheat in the every county in the US. This data was retreived from the USDA (https://quickstats.nass.usda.gov/#DE398F62-AD6A-36D0-BC08-3A71D941943A). The first step of cleaning this data was to remove any columns that were all the same value. This data is not neccessary because it is all the same. Then, rows with blanks were deleted, because if the data did not share the full picture, it was not desired. The final step of cleaning was to remove any rows that did not have values given due to privacy reasons for the farmer. This step was done with both the wheat yield portion of the data and the area of wheat planted. 

## Total Yield from All States
<img src= "https://raw.githubusercontent.com/LeightonDorman/Personal-Data-Set/main/total_wheat_yield_state.jpeg">
*caption:* Bar plot of the total wheat yield from each state. The top three wheat producing states are Kansas, North Dekota, and Washington.

## All State Boxplot
<img src= "https://raw.githubusercontent.com/LeightonDorman/Personal-Data-Set/main/wheat_boxplot_allstate.jpeg">
*caption:* Boxplot of all states seperating the data into quartiles. Outliers are shown in red asterisks.
