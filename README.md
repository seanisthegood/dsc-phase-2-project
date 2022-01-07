The King County housing dataset contains 21,597 entries of home sale data from 2014 to 2015. The data was paired with information on zip codes from a US database to obtain city names for the dataset.

## Methods

In this project I used descriptive anaylsis and tried to follow the  Obtain Scrub Explore Model iNterpret workflow. I used Pandas to clean the data, make choices on the null values and create the Linear Regression Models using Scikit-Learn and StatsModels. 

## Results

After standardizing the house features of the dataset, Square Footage of the Living Space had the largest coefficient. I also one-hot encoded the cities after joining with the zip codes. I then one-hot encoded the cities and found Seattle added the most value.

## Error Terms and Residual Problems

The model showed an R-Squared around 69, meaing the model accounted for 69% of the varrience in the data. I had problems with Heteroskadisctiy, and had to drop outliers in the dataset to try to reduce problems with residuals.

##Conclusions

*Understand a better way to model location, maybe utilize the latitude and longtitude information .
*Understand interactions regarding square footage of living space and location.

## Next Steps
*Collect data in a post-pandemic setting
*Apply advanced modeling techniques to the dataset