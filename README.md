## Datasets Available in R

### Motivation & Objective

Often my main objective is to find an R datasets of a particular class (e.g. `tbl_df`, `data.frame`, `ts`) which I would like to use for: 

* teaching
* presentations 
* to prepare reproducible example code for sharing (see `reprex` package)

There *are* many useful datasets available in Base R and others that are loaded with packages. To see a list of those that are available to you (including for loaded packages) type `data()` in the R console. There are packages dedicated to sharing data (e.g. see `gapminder`, `FiveThirtyEight` packages) which are not covered in this document.

This program creates a `tibble` call `all_ds` that makes it easier to search for datasets based on the keywords and/or classes. 
