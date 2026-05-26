# Academic Theme in addition to ggplot2

Academic Theme in addition to ggplot2

## Usage

``` r
theme_academic(base_size = 12)
```

## Arguments

- base_size:

  A positive integer value

## Value

plot with theme added when passed with ggplot2 (centralized plot title,
grid lines removed)

## Examples

``` r
library(ggplot2)
p <- ggplot(data = mtcars) + geom_point(aes(x = mpg, y = hp)) + labs(title = "plot_title")
p + theme_academic()
```
