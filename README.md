biogeochemthemes readme
================
Jason Venkiteswaran

# `biogeochemthemes` : Biogeochem Lab Themes for `ggplot2`

## Installation

``` r
library(devtools)
devtools::install_github("biogeochem/biogeochemthemes")
```

## Usage

``` r
library(biogeochemthemes)
library(ggplot2)
```

## Jason’s theme

``` r
ggplot(mtcars, aes(y=mpg, x=disp, colour=factor(cyl))) +
  geom_point() +
  labs(x="Fuel effiiency (mpg)", y="Weight (tons)", colour = "Cylinders",
       title="Jason's ggplot2 scatterplot example",
       subtitle="A witty subtitle goes here",
       caption="Brought to you by the phrase 'Who knows?!'") + 
  theme_jason()
```

![](README_files/figure-gfm/jason-example-1.png)<!-- -->

## Kateri’s theme

``` r
ggplot(mtcars, aes(y=mpg, x=disp, colour=factor(cyl))) +
  geom_point() +
  labs(x="Fuel effiiency (mpg)", y="Weight (tons)", color = "Cylinders",
       title="Kateri's ggplot2 scatterplot example",
       subtitle="A witty subtitle goes here",
       caption="Brought to you by the letters 'MSU'") + 
  theme_kateri()
```

![](README_files/figure-gfm/kateri-example-1.png)<!-- -->

## Megan’s theme

``` r
ggplot(mtcars, aes(y=mpg, x=disp, colour=factor(cyl))) +
  geom_point() +
  labs(x="Fuel effiiency (mpg)", y="Weight (tons)", color = "Cylinders",
       title="Megan's ggplot2 scatterplot example",
       subtitle="A witty subtitle goes here",
       caption="Brought to you by extra coffee") + 
  theme_megan()
```

![](README_files/figure-gfm/megan-example-1.png)<!-- -->
