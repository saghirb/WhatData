## Datasets Available in R

> *Note:* To search for R datasets please download (or clone) this github repository and open the *WhatData.html* file in your browser.

### Motivation & Objective

I often myself looking for R datasets of a particular class (e.g. `tbl_df`, `data.frame`, `ts`) for: 

* teaching
* presentations 
* preparing reproducible example code (see [`reprex`](https://github.com/tidyverse/reprex) package)

There *are* many useful datasets available in Base R and others that are loaded with packages. To see a list of those that are available to you (including for loaded packages) type `data()` in the R console. There are packages dedicated to sharing data (e.g. see `gapminder`, `FiveThirtyEight` packages) which are not covered in this document.

This program creates a `tibble` call `all_ds` that makes it easier to search for datasets based on the keywords and/or classes. 
