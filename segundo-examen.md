martha johana rozo delgado 1950200
================

## estas son las mediciones de la calidad del aire en nueva york

este trabajo nos va a mostrar las mediciones diarias de la calidad de
aire en nueva york,observando los criterios de**AIRQUALITY**

este dataframe sobre la calidad de aire en nueva york

``` r
data(airquality)
solar <- airquality["Solar.R"]
temp <- airquality["Temp"]
ozono <- airquality["Ozone"]
Refectancia  <- (solar-temp)^2/ozono
```

## Including Code

You can include R code in the document as follows:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](segundo-examen_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
