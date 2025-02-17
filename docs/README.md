
<p align="center">
<img src="https://user-images.githubusercontent.com/987057/167296405-e7798ac8-03e7-444e-acaf-d99fc42d1c9e.png" align="right" alt="" width="125" />
</p>

<br>

<!-- badges: start -->

[![DOI](http://joss.theoj.org/papers/10.21105/joss.00848/status.svg)](https://doi.org/10.21105/joss.00848)
<a href = "https://vincentarelbundock.github.io/countrycode" target = "_blank"><img src="https://img.shields.io/static/v1?label=Website&message=Visit&color=blue"></a>
[![R build
status](https://github.com/vincentarelbundock/countrycode/workflows/R-CMD-check/badge.svg)](https://github.com/vincentarelbundock/countrycode/actions)
![CRAN
downloads](http://cranlogs.r-pkg.org/badges/grand-total/countrycode.png)
<!-- badges: end -->

`countrycode` standardizes country names, converts them into ~40
different coding schemes, and assigns region descriptors. Scroll down
for more details or visit the [countrycode CRAN
page](http://cran.r-project.org/web/packages/countrycode/index.html)

If you use `countrycode` in your research, we would be very grateful if
you could cite our paper:

> Arel-Bundock, Vincent, Nils Enevoldsen, and CJ Yetman, (2018).
> countrycode: An R package to convert country names and country codes.
> Journal of Open Source Software, 3(28), 848,
> https://doi.org/10.21105/joss.00848

## Why `countrycode`?

### The Problem

Different data sources use different coding schemes to represent
countries (e.g. CoW or ISO). This poses two main problems: (1) some of
these coding schemes are less than intuitive, and (2) merging these data
requires converting from one coding scheme to another, or from long
country names to a coding scheme.

### The Solution

The `countrycode` function can convert to and from 40+ different country
coding schemes, and to 600+ variants of country names in different
languages and formats. It uses regular expressions to convert long
country names (e.g. Sri Lanka) into any of those coding schemes or
country names. It can create new variables with various regional
groupings.

## Installation

From the R console, type:

``` r
install.packages("countrycode")
```

To install the latest development version, you can use the `remotes`
package:

``` r
library(remotes)
install_github('vincentarelbundock/countrycode')
```

## Supported codes

To get an up-to-date list of supported country codes, install the
package and type `?codelist`. These include:

-   600+ variants of country names in different languages and formats.
-   AR5
-   Continent and region identifiers.
-   Correlates of War (numeric and character)
-   European Central Bank
-   [EUROCONTROL](https://www.eurocontrol.int) - The European
    Organisation for the Safety of Air Navigation
-   Eurostat
-   Federal Information Processing Standard (FIPS)
-   Food and Agriculture Organization of the United Nations
-   Global Administrative Unit Layers (GAUL)
-   Geopolitical Entities, Names and Codes (GENC)
-   Gleditsch & Ward (numeric and character)
-   International Civil Aviation Organization
-   International Monetary Fund
-   International Olympic Committee
-   ISO (2/3-character and numeric)
-   Polity IV
-   United Nations
-   United Nations Procurement Division
-   Varieties of Democracy
-   World Bank
-   World Values Survey
-   Unicode symbols (flags)
