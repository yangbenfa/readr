# Setup

## Platform

|setting  |value                        |
|:--------|:----------------------------|
|version  |R version 3.3.0 (2016-05-03) |
|system   |x86_64, darwin13.4.0         |
|ui       |RStudio (0.99.1261)          |
|language |(EN)                         |
|collate  |en_US.UTF-8                  |
|tz       |America/Chicago              |
|date     |2016-07-19                   |

## Packages

|package   |*  |version    |date       |source                           |
|:---------|:--|:----------|:----------|:--------------------------------|
|BH        |   |1.60.0-2   |2016-05-07 |CRAN (R 3.3.0)                   |
|covr      |   |2.1.0      |2016-06-21 |cran (@2.1.0)                    |
|curl      |   |0.9.7      |2016-04-10 |CRAN (R 3.3.0)                   |
|hms       |   |0.2-1      |2016-07-19 |Github (rstats-db/hms@98d14cf)   |
|knitr     |   |1.13       |2016-05-09 |CRAN (R 3.3.0)                   |
|Rcpp      |   |0.12.5     |2016-05-14 |CRAN (R 3.3.0)                   |
|readr     |   |0.2.2.9000 |2016-07-19 |local (hadley/readr@6e7b437)     |
|rmarkdown |   |1.0        |2016-07-08 |cran (@1.0)                      |
|stringi   |   |1.1.1      |2016-05-27 |cran (@1.1.1)                    |
|testthat  |*  |1.0.2.9000 |2016-07-19 |Github (hadley/testthat@46d15da) |
|tibble    |   |1.1        |2016-07-19 |Github (hadley/tibble@725e61a)   |

# Check results
38 packages

## abbyyR (0.5.0)
Maintainer: Gaurav Sood <gsood07@gmail.com>  
Bug reports: http://github.com/soodoku/abbyyR/issues

0 errors | 0 warnings | 1 note 

```
checking installed package size ... NOTE
  installed size is  7.2Mb
  sub-directories of 1Mb or more:
    doc       2.0Mb
    extdata   5.0Mb
```

## biomartr (0.0.3)
Maintainer: Hajk-Georg Drost <hgd23@cam.ac.uk>  
Bug reports: https://github.com/HajkD/biomartr/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Packages required but not available: ‘biomaRt’ ‘Biostrings’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## dataonderivatives (0.2.1)
Maintainer: Imanuel Costigan <i.costigan@me.com>  
Bug reports: https://github.com/imanuelcostigan/dataonderivatives/issues

0 errors | 0 warnings | 0 notes

## dataRetrieval (2.5.5)
Maintainer: Laura DeCicco <ldecicco@usgs.gov>  
Bug reports: https://github.com/USGS-R/dataRetrieval/issues

0 errors | 0 warnings | 0 notes

## ddpcr (1.4)
Maintainer: Dean Attali <daattali@gmail.com>  
Bug reports: https://github.com/daattali/ddpcr/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  > 
  > test_check("ddpcr")
  1. Failure: get_filled_drops works (@test-pnpp_experiment-filled.R#22) ---------
  get_filled_drops(plate, "A05") not identical to readr::read_csv(file.path(dir, "A05_filled.csv")).
  Objects equal but not identical
  
  
  testthat results ================================================================
  OK: 261 SKIPPED: 0 FAILED: 1
  1. Failure: get_filled_drops works (@test-pnpp_experiment-filled.R#22) 
  
  Error: testthat unit tests failed
  Execution halted
```

## eechidna (0.1)
Maintainer: Ben Marwick <benmarwick@gmail.com>

0 errors | 0 warnings | 0 notes

## eemR (0.1.3)
Maintainer: Philippe Massicotte <pm@bios.au.dk>  
Bug reports: https://github.com/PMassicotte/eemR/issues

0 errors | 0 warnings | 0 notes

## efreadr (0.1.1)
Maintainer: Marco Bascietto <marco.bascietto@crea.gov.it>

0 errors | 0 warnings | 0 notes

## elpatron (0.0.2)
Maintainer: Jordan Mackie <jmackie@protonmail.com>

1 error  | 1 warning  | 0 notes

```
checking examples ... ERROR
Running examples in ‘elpatron-Ex.R’ failed
The error most likely occurred in:

> base::assign(".ptime", proc.time(), pos = "CheckExEnv")
> ### Name: clean_bikedata
> ### Title: Clean raw cycling device data.
> ### Aliases: clean_bikedata
> 
> ### ** Examples
> 
> ride_file <- system.file("extdata/lufbra.fit", package = "elpatron")
> 
> parsed_ride <- import_ride(ride_file, make_laps = TRUE)
Error: Length of logical index vector must be 1 or 18, got: 17
Execution halted

checking Rd cross-references ... WARNING
Missing link or links in documentation object 'pipe.Rd':
  ‘[dplyr]{chain}’

See section 'Cross-references' in the 'Writing R Extensions' manual.

```

## estatapi (0.2)
Maintainer: Hiroaki Yutani <yutani.ini@gmail.com>

0 errors | 0 warnings | 0 notes

## eyelinker (0.1)
Maintainer: Simon Barthelme <simon.barthelme@gipsa-lab.fr>

0 errors | 0 warnings | 0 notes

## fuzzyjoin (0.1.1)
Maintainer: David Robinson <drobinson@stackoverflow.com>

0 errors | 0 warnings | 0 notes

## geojsonio (0.2.0)
Maintainer: Scott Chamberlain <myrmecocystus@gmail.com>  
Bug reports: http://www.github.com/ropensci/geojsonio/issues

0 errors | 0 warnings | 0 notes

## googlesheets (0.2.1)
Maintainer: Jennifer Bryan <jenny@stat.ubc.ca>  
Bug reports: https://github.com/jennybc/googlesheets/issues

0 errors | 0 warnings | 0 notes

## GSODR (0.1.9)
Maintainer: Adam Sparks <adamhsparks@gmail.com>  
Bug reports: https://github.com/adamhsparks/GSODR/issues

0 errors | 0 warnings | 0 notes

## gunsales (0.1.1)
Maintainer: Dirk Eddelbuettel <edd@debian.org>

0 errors | 0 warnings | 0 notes

## gutenbergr (0.1.2)
Maintainer: David Robinson <admiral.david@gmail.com>  
Bug reports: http://github.com/ropenscilabs/gutenbergr/issues

0 errors | 0 warnings | 0 notes

## httr (1.2.1)
Maintainer: Hadley Wickham <hadley@rstudio.com>

0 errors | 0 warnings | 0 notes

## IalsaSynthesis (0.1.6)
Maintainer: Will Beasley <wibeasley@hotmail.com>  
Bug reports: https://github.com/IALSA/IalsaSynthesis/issues

0 errors | 0 warnings | 0 notes

## macleish (0.3.0)
Maintainer: Ben Baumer <ben.baumer@gmail.com>

0 errors | 0 warnings | 0 notes

## mosaic (0.14)
Maintainer: Randall Pruim <rpruim@calvin.edu>  
Bug reports: https://github.com/ProjectMOSAIC/mosaic/issues

0 errors | 0 warnings | 1 note 

```
checking installed package size ... NOTE
  installed size is  9.2Mb
  sub-directories of 1Mb or more:
    R     1.8Mb
    doc   6.8Mb
```

## myTAI (0.4.0)
Maintainer: Hajk-Georg Drost <hgd23@cam.ac.uk>  
Bug reports: https://github.com/HajkD/myTAI/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘edgeR’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## ncappc (0.2.1.1)
Maintainer: Chayan Acharya <chayan.acharya@farmbio.uu.se>

0 errors | 0 warnings | 0 notes

## neuroim (0.0.6)
Maintainer: Bradley Buchsbaum <brad.buchsbaum@gmail.com>

0 errors | 0 warnings | 0 notes

## photobiologyInOut (0.4.6)
Maintainer: Pedro J. Aphalo <pedro.aphalo@helsinki.fi>  
Bug reports: https://bitbucket.org/aphalo/photobiologyinout/

0 errors | 0 warnings | 0 notes

## readODS (1.6.2)
Maintainer: Chung-hong Chan <chainsawtiney@gmail.com>

0 errors | 0 warnings | 0 notes

## rgho (0.1.0)
Maintainer: Antoine Filipovic-Pierucci <pierucci@gmail.com>  
Bug reports: https://github.com/pierucci/rgho/issues

0 errors | 0 warnings | 0 notes

## riem (0.1.0)
Maintainer: Maëlle Salmon <maelle.salmon@yahoo.se>  
Bug reports: http://github.com/ropenscilabs/riem/issues

0 errors | 0 warnings | 1 note 

```
checking DESCRIPTION meta-information ... NOTE
Authors@R field gives persons with no valid roles:
  Brooke Anderson [rev] (Brooke Anderson reviewed the package for rOpenSci, see https://github.com/ropensci/onboarding/issues/39.)
```

## rio (0.4.8)
Maintainer: Thomas J. Leeper <thosjleeper@gmail.com>

0 errors | 0 warnings | 0 notes

## rmapshaper (0.1.0)
Maintainer: Andy Teucher <andy.teucher@gmail.com>  
Bug reports: http://www.github.com/ateucher/rmapshaper/issues

0 errors | 0 warnings | 0 notes

## rpdo (0.2.0)
Maintainer: Joe Thorley <joe@poissonconsulting.ca>

0 errors | 0 warnings | 0 notes

## rrefine (1.0)
Maintainer: VP Nagraj <vpnagraj@virginia.edu>

0 errors | 0 warnings | 0 notes

## RSocrata (1.7.0-14)
Maintainer: "Tom Schenk Jr." <developers@cityofchicago.org>  
Bug reports: https://github.com/Chicago/RSocrata/issues

0 errors | 0 warnings | 0 notes

## stationaRy (0.4.1)
Maintainer: Richard Iannone <riannone@me.com>  
Bug reports: https://github.com/rich-iannone/stationaRy/issues

0 errors | 0 warnings | 1 note 

```
checking installed package size ... NOTE
  installed size is  8.1Mb
```

## stplanr (0.1.2)
Maintainer: Robin Lovelace <rob00x@gmail.com>  
Bug reports: https://github.com/ropensci/stplanr/issues

0 errors | 0 warnings | 0 notes

## tidytext (0.1.1)
Maintainer: Julia Silge <julia.silge@gmail.com>  
Bug reports: http://github.com/juliasilge/tidytext/issues

0 errors | 0 warnings | 0 notes

## traits (0.2.0)
Maintainer: Scott Chamberlain <myrmecocystus@gmail.com>  
Bug reports: http://www.github.com/ropensci/traits/issues

0 errors | 0 warnings | 0 notes

## webreadr (0.4.0)
Maintainer: Oliver Keyes <ironholds@gmail.com>  
Bug reports: https://github.com/Ironholds/webreadr/issues

0 errors | 0 warnings | 0 notes

