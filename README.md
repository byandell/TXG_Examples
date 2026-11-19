# Tribal Exchange Examples

This repo has a collection of shortexamples inspired by monthly sessions of the
[Tribal Exchange Network Group](https://www.tribalexchangenetwork.org/),
which meets mid-day on the 3rd Thursday of the month.
They have a collection of
[technical training videos](https://www.tribalexchangenetwork.org/technical-training-videos).

While some people shared data with me, the examples here use R datasets or
generated data simulated to match the questions asked.
Visitors may also be interesed in other examples and resources at my
GitHub repo
[byandell/esiil-stars](https://github.com/byandell/esiil-stars),
which is associated with the
[ESIIL Stars Program](https://esiil.org/esiil-stars).

* [Intros and Useful Sites](#intros-and-useful-sites)
* [Examples](#examples)
* [Dates and Times](#dates-and-times)
* [General R and Coding Resources](#general-r-and-coding-resources)

---

## Intros and Useful sites

* [Intro to R (Karl Broman)](https://kbroman.org/datacarpentry_R_2016-08-23/01-intro-to-R.html)
* [Document Tools](https://byandell.github.io/DocumentTools/)
* [For Loops (Mark Nepf)](https://marknepf.github.io/code/r_vignettes/nepf_for_loops.html)

## Examples

* [rplot.Rmd](rplot.html) ([PDF](rplot.pdf))
  * Basic R plots and ggplot with x-y data
* [ggplot_time.Rmd](ggplot_time.html) ([PDF](ggplot_time.pdf))
  * ggplot with datetime axis
* [process_data.Rmd](process_data.html) ([PDF](process_data.pdf))
  * aggregate data over time using base R

## Dates and Times

There are several ways to handle dates and times in R, notably with
[base function
[`as.Date()`,
base classes `POSIXct` and `POSIXlt`](https://www.neonscience.org/resources/learning-hub/tutorials/dc-convert-date-time-posix-r),
and `tidyverse` package
[`lubridate`](https://lubridate.tidyverse.org/).
Here are some resources that may be helpful.

* [R for Data Science (Hadley Wickham et al.): Dates and times](https://r4ds.hadley.nz/datetimes.html)
* [R Programming for Data Science (Roger Peng): Dates and Times](https://bookdown.org/rdpeng/rprogdatascience/dates-and-times.html)
* [Dates and Times in R (UC Berkeley Stats)](https://www.stat.berkeley.edu/~s133/dates.html)
* [R Graphics Cookbook (Winston Chang): Using Dates on an Axis](https://r-graphics.org/RECIPE-AXES-AXIS-DATE.html)

## General R and Coding Resources

* [byandell/esiil-stars](https://github.com/byandell/esiil-stars)
* [Document Digital Tools: R Language (Brian Yandell)](https://byandell.github.io/Documentation/R/)
* [R for Data Science (Hadley Wickham et al)](https://r4ds.hadley.nz/)
* [R Programming for Data Science (Roger Peng)](https://bookdown.org/rdpeng/rprogdatascience/)
* [R Graphics Book (Winston Chang)](https://r-graphics.org/)
