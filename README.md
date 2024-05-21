# Bloom-Study

The included notebooks were used to better understand which species of plants have been blooming earlier and earlier every year.
The herb_flower_bloom notebook contains bloom data for multiple sites, while the Mohonk_bloom_data contains such data for one site, Mohonk.

Please view the colab notebook to utilize the interactive charts:
Aggregated stats: https://colab.research.google.com/drive/1bfvz8D7NZeWr19M7X30qbGETI-NvGBB2#scrollTo=Ax1Z259QsR8A

Aggregated analysis: https://colab.research.google.com/drive/1bfvz8D7NZeWr19M7X30qbGETI-NvGBB2#scrollTo=aZHW_Y5lAFGs

TASK
1) Perform a linear regression on the day of first bloom vs. the year of the bloom. 
2) Compute the Kendall's tau, the R^2 of the regression, the slope of the regression line, and the p-values for the observed regressions. 
3) Restrict results to instances that showed a p-value of <.1 and split these instances based on positive and negative slopes.

The following is an example for Genus = Crocus, Species = spp., Site_Name = Home, State = ME
DOY stands for 'Day Of Year'
As you can see, there appears to be some correlation between how early the plant is blooming and the passage of years. These are the instances we are interested in to see if there is a statistical significance to this relationship.


![image](https://github.com/MillerAJ/Bloom-Study/assets/9644656/bcf1034b-5925-45d3-92bf-6a8041056bf4)

