# Bloom-Study

The included notebooks were used to better understand which species of plants have been blooming earlier and earlier every year.
The herb_flower_bloom notebook contains bloom data for multiple sites, while the Mohonk_bloom_data contains such data for one site, Mohonk.

TASK
1) Perform a linear regression on the day of first bloom vs. the year of the bloom. 
2) Compute the Kendall's tau, the R^2 of the regression, the slope of the regression line, and the p-values for the observed regressions. 
3) Restrict results to instances that showed a p-value of <.1 and split these instances based on positive and negative slopes.

The following is an example for Genus = Acer, Species = saccharum, Site_Name = Home
DOY stands for 'Day Of Year'
As you can see, there appears to be a correlation between how early the plant is blooming and the passage of years. These are the instances we are interested in to see if there is a statistical significance to this relationship.
![image](https://github.com/MillerAJ/Bloom-Study/assets/9644656/2174cb19-0822-4f01-b193-13e331ba7213)

