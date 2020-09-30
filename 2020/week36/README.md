# Tidy Tuesday
Repo for Tidy Tuesday exercise, Week 36 (2020).

[Original post](https://ourworldindata.org/crop-yields))

[Source metadata](https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-09-01/readme.md)

## Notes  

Some highlights:

*  Using `janitor::clean_names()` to help with initial management of the dataset. This helps with quick tidying. 
*  Using the `%%` operator to quickly calculate the `decade` variable.  
*  Using `countrycode::` to join to `continent` to provide another dimension to the analysis.  
*  Using `gt::` to produce a table of maize yield in the Southern African Development Community.  

Further development:  

*  Using `tidymodels::` on the dataset (tutorial [here](https://www.r-bloggers.com/2020/09/train-and-analyze-many-models-for-tidytuesday-crop-yields/)).
*  Using `gt::` on the dataset (tutorial [here](https://themockup.blog/posts/2020-09-04-10-table-rules-in-r/)).  

## Visualization  

![](https://github.com/mrafa3/tidy_tuesday/blob/master/2020/week36/graphics/yield_gt.png/yield_gt.png)

![](https://github.com/mrafa3/tidy_tuesday/blob/master/2020/week36/graphics/yield_gt.png/fertilizer_gt.png)
