# nhpdata
A repository to hold the `nhpdata` package, a package containing the normalized mRNA expression data used in the Non-human Primate Atlas at the [Allen Institute](http://brain-map.org/).

The original data can be found [here](https://github.com/AllenBrainAtlas/DevRhesusLMD).

This package is intended to be used in conjunction with the `atlasplot` package.

## Install
To install the `nhpdata` package it is recommended to use the
[`devtools`](https://github.com/hadley/devtools) package. This is a well trusted and reputable package from Hadley Wickham intended to streamline package development and installation. This alternate installation method is necessary due to the large size of this package.

**WARNING**: This package is large (>100 Mb); ensure that you have a
steady internet connection.

In the `R` command line perform the following commands
```
# Install devtools package
install.package("devtools")

# Install nhpdata
devtools::install_github("AllenInstitute/nhpdata")
```

## Additional Details
The source version of this package contains the code necessary to format the raw data downloaded from the [Allen Institute](http://www.blueprintnhpatlas.org/static/download) into the hosted `.rda` files. This code is located in `data-raw`.
