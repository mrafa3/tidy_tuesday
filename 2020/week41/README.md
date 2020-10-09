# Tidy Tuesday
Repo for Tidy Tuesday exercise, Week 41 (2020).

[Original post](https://fivethirtyeight.com/features/louisiana-tech-was-the-uconn-of-the-80s/)

[Source metadata](https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-10-06/readme.md)

## Notes  

Some highlights:

* I used a small multiples plot and **borrowed heavily** from [this example](https://github.com/PaulApivat/tidytuesday/blob/master/2020/ncaa/ncaa.png) in order to make a working example of `geom_ribbon()`.  
*  I used `ggtext::` for more use/experimentation with `element_markdown()`.  
*  I used the `dplr::tally()` function, which was a fast way to determine which programs had the most years of data available (although I ultimately ended up just producing a Big 12 visualization).  

## Visualization  

![](https://github.com/mrafa3/tidy_tuesday/blob/master/2020/week41/graphics/big12_viz.png)

