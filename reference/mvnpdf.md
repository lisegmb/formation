# mvnpdf this function calculate the (log)normal distribution for a matrix

mvnpdf this function calculate the (log)normal distribution for a matrix

## Usage

``` r
mvnpdf(x, mean = rep(0, nrow(x)), varcovM = diag(nrow(x)), Log = TRUE)
```

## Arguments

- x:

  the matrix of the observations

- mean:

  a vector, the mean for each variable

- varcovM:

  the matrix of variance, covariance

- Log:

  logical, default equal TRUE if TRUE calculate the log normal
  distribution

## Value

the observation and the prediction with the (log)normal distribution

## Examples

``` r
mvnpdf(x=matrix(1.96), Log=FALSE)
#> $x
#>      [,1]
#> [1,] 1.96
#> 
#> $y
#> [1] 0.05844094
#> 
#> attr(,"class")
#> [1] "mvnpdf"
```
