# Tidy Tuesday
Repo for Tidy Tuesday exercise, Week 39 (2020).

[Original post](https://www.alexcookson.com/post/analyzing-himalayan-peaks-first-ascents/)

[Source metadata](https://www.himalayandatabase.com/)

## Notes  

Some highlights:

*  Using `geom_curve()` to highlight Mount Everest as an outlier. 
*  Experimented with `ggtext::` for `element_textbox()` on y-axis titles.  

Further development:  

*  Could do a ternary diagram (from `ggtern::`) of height, difficulty, and number of ascents  
*  Could experiment with `Rayshader::` to do a 3D map of peaks
*  Could scrape Colorado 14ers and do a ridgeplot (from `ggridges::`) comparing the heights  
*  Could use `geom_violin()` and color the peaks by ascent or difficulty

## Visualization  

![](https://github.com/mrafa3/tidy_tuesday/blob/master/2020/week39/graphics/peak_hist_viz.png)

![](https://github.com/mrafa3/tidy_tuesday/blob/master/2020/week39/graphics/paving_everest_viz.png)

## Examples that I like  

*  [This article](https://www.r-bloggers.com/2020/09/handle-class-imbalance-in-tidytuesday-climbing-expedition-data-with-tidymodels/) addresses the class imbalance in the data and uses the `tidymodels::` package.  