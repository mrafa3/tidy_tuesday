# Tidy Tuesday
Repo for Tidy Tuesday exercise, Week 2 (2020).

[Original post](https://www.nytimes.com/interactive/2020/01/02/climate/australia-fires-map.html)

[Source metadata](http://www.bom.gov.au/climate/data/stations/)

## Notes  

Largely replicating the plots done [https://github.com/jkaupp/tidytuesdays/tree/master/2020/week2](here) with some modifications.

Some highlights:

*  Experimenting with `ggrepel::geom_mark_circle()` to help highlight/label points in a plot.  
*  Experimenting with the `jkmisc` package (installed via Github). This package is described as a package of a variety of helper functions, including support for advanced formatting of `ggplot2`. I especially love that this is a way to use color without necessarily needing a legend.  
*  Used `zoo::rollapply()` to calculate and display the 10-year moving average on both plots.  

## Visualization  

![](https://github.com/mrafa3/tidy_tuesday/blob/master/2020/week2/graphics/plot_rain_temp_1900_2019.png)
