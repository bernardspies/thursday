R Markdown Rocks
================
Bernard Spies
16 February 2017

R Markdown
----------

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

``` r
#summary(cars)
x <- rnorm(1000) + 10
head(x)
```

    ## [1] 10.354398 10.384739  9.793327 10.128426 11.047334 10.804240

Including Plots
---------------

You can also embed plots, for example:

![](rmarkdown-rocks_files/figure-markdown_github/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
