# Tidy Tuesday
Repo for Tidy Tuesday exercise, Week 35 (2022).

[Original post]()

[Source metadata]()

## Notes  


Some highlights:

* Used `slice_min()` and `slice_max()` to pull the min and max values per year in Colorado, then combined them in a new dataframe. Feels like a nice way to build this kind of graphic (instead of trying to do this all within ggplot).
* Build a quick `gt::` table of the data and used two features of `gtExtras::` that are new to me (hulk color scheme and highlighting specific rows).
* Experimented with `camcorder::` and will plan to use this for future projects.
* Used the `glue::` package to build titles and captions, and this feels like a much easier way to create these.


## Future ideas

* [Hex map](https://github.com/KittJonathan/tidytuesday/blob/master/R/2022_08_30_pell_grants.R) 


## Visualization  

![](https://github.com/mrafa3/tidy_tuesday/blob/master/2022/week35/graphics/viz_pell_colorado.png)

![](https://github.com/mrafa3/tidy_tuesday/blob/master/2022/week35/graphics/tbl_pell_by_state_2017.png)
