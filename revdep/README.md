# Setup

## Platform

|setting  |value                        |
|:--------|:----------------------------|
|version  |R version 3.4.0 (2017-04-21) |
|system   |x86_64, linux-gnu            |
|ui       |X11                          |
|language |en                           |
|collate  |en_US.UTF-8                  |
|tz       |America/Los_Angeles          |
|date     |2017-05-25                   |

## Packages

|package  |*  |version |date       |source         |
|:--------|:--|:-------|:----------|:--------------|
|digest   |   |0.6.12  |2017-01-27 |cran (@0.6.12) |
|future   |   |1.4.0   |2017-03-13 |cran (@1.4.0)  |
|globals  |   |0.10.0  |2017-04-17 |cran (@0.10.0) |
|listenv  |   |0.6.0   |2015-12-28 |cran (@0.6.0)  |
|markdown |   |0.8     |2017-04-20 |cran (@0.8)    |
|R.rsp    |   |0.41.0  |2017-04-16 |cran (@0.41.0) |

# Check results

24 packages

|package              |version | errors| warnings| notes|
|:--------------------|:-------|------:|--------:|-----:|
|ACNE                 |0.8.1   |      0|        0|     0|
|aroma.affymetrix     |3.1.0   |      0|        0|     0|
|aroma.cn             |1.6.1   |      0|        0|     0|
|aroma.core           |3.1.0   |      0|        0|     1|
|calmate              |0.12.1  |      0|        0|     0|
|doFuture             |0.5.0   |      0|        0|     0|
|fiery                |0.2.2   |      0|        0|     0|
|future.BatchJobs     |0.14.0  |      0|        0|     0|
|GeneBreak            |1.6.0   |      0|        0|     1|
|googleComputeEngineR |0.1.0   |      0|        0|     0|
|kernelboot           |0.1.0   |      0|        0|     0|
|MPAgenomics          |1.1.2   |      0|        0|     2|
|NSA                  |0.0.32  |      0|        0|     6|
|pbmcapply            |1.2.1   |      0|        0|     0|
|PECA                 |1.12.0  |      0|        0|     1|
|PSCBS                |0.62.0  |      0|        0|     0|
|PureCN               |1.6.2   |      0|        0|     1|
|QDNAseq              |1.12.0  |      0|        1|     0|
|Repitools            |1.22.0  |      0|        0|     3|
|R.filesets           |2.11.0  |      0|        0|     0|
|startR               |0.0.1   |      0|        0|     0|
|TIN                  |1.8.0   |      0|        0|     2|
|vesselr              |0.2.1   |      0|        0|     0|
|warbleR              |1.1.8   |      0|        0|     0|

## ACNE (0.8.1)
Maintainer: Henrik Bengtsson <henrikb@braju.com>  
Bug reports: https://github.com/HenrikBengtsson/ACNE/issues

0 errors | 0 warnings | 0 notes

## aroma.affymetrix (3.1.0)
Maintainer: Henrik Bengtsson <henrikb@braju.com>  
Bug reports: https://github.com/HenrikBengtsson/aroma.affymetrix/issues

0 errors | 0 warnings | 0 notes

## aroma.cn (1.6.1)
Maintainer: Henrik Bengtsson <henrikb@braju.com>  
Bug reports: https://github.com/HenrikBengtsson/aroma.cn/issues

0 errors | 0 warnings | 0 notes

## aroma.core (3.1.0)
Maintainer: Henrik Bengtsson <henrikb@braju.com>  
Bug reports: https://github.com/HenrikBengtsson/aroma.core/issues

0 errors | 0 warnings | 1 note 

```
checking package dependencies ... NOTE
Packages suggested but not available for checking:
  ‘expectile’ ‘HaarSeg’ ‘mpcbs’
```

## calmate (0.12.1)
Maintainer: Henrik Bengtsson <henrikb@braju.com>  
Bug reports: https://github.com/HenrikBengtsson/calmate/issues

0 errors | 0 warnings | 0 notes

## doFuture (0.5.0)
Maintainer: Henrik Bengtsson <henrikb@braju.com>  
Bug reports: https://github.com/HenrikBengtsson/doFuture/issues

0 errors | 0 warnings | 0 notes

## fiery (0.2.2)
Maintainer: Thomas Lin Pedersen <thomasp85@gmail.com>  
Bug reports: https://github.com/thomasp85/fiery/issues

0 errors | 0 warnings | 0 notes

## future.BatchJobs (0.14.0)
Maintainer: Henrik Bengtsson <henrikb@braju.com>  
Bug reports: https://github.com/HenrikBengtsson/future.BatchJobs/issues

0 errors | 0 warnings | 0 notes

## GeneBreak (1.6.0)
Maintainer: Evert van den Broek <vandenbroek.evert@gmail.com>

0 errors | 0 warnings | 1 note 

```
checking R code for possible problems ... NOTE
.glmbreak: no visible global function definition for ‘glm’
.glmbreak: no visible global function definition for ‘predict’
addGeneAnnotation,CopyNumberBreakPoints: no visible global function
  definition for ‘head’
bpStats,CopyNumberBreakPoints: no visible global function definition
  for ‘sd’
bpStats,CopyNumberBreakPoints: no visible global function definition
  for ‘p.adjust’
Undefined global functions or variables:
  glm head p.adjust predict sd
Consider adding
  importFrom("stats", "glm", "p.adjust", "predict", "sd")
  importFrom("utils", "head")
to your NAMESPACE file.
```

## googleComputeEngineR (0.1.0)
Maintainer: Mark Edmondson <r@sunholo.com>  
Bug reports: https://github.com/cloudyr/googleComputeEngineR/issues

0 errors | 0 warnings | 0 notes

## kernelboot (0.1.0)
Maintainer: Tymoteusz Wolodzko <twolodzko+kernelboot@gmail.com>  
Bug reports: https://github.com/twolodzko/kernelboot/issues

0 errors | 0 warnings | 0 notes

## MPAgenomics (1.1.2)
Maintainer: Samuel Blanck <samuel.blanck@inria.fr>

0 errors | 0 warnings | 2 notes

```
checking dependencies in R code ... NOTE
'library' or 'require' calls in package code:
  ‘R.devices’ ‘R.filesets’ ‘R.methodsS3’ ‘R.oo’ ‘aroma.affymetrix’
  ‘aroma.cn’ ‘aroma.core’ ‘aroma.light’ ‘matrixStats’ ‘snowfall’
  Please use :: or requireNamespace() instead.
  See section 'Suggested packages' in the 'Writing R Extensions' manual.
Unexported object imported by a ':::' call: ‘cghseg:::segmeanCO’
  See the note in ?`:::` about the use of this operator.

checking R code for possible problems ... NOTE
.varregtimescount: no visible global function definition for ‘var’
CGHSEGaroma: no visible global function definition for ‘read.csv’
CGHSEGaroma : <anonymous>: no visible global function definition for
  ‘points’
CGHSEGaroma : <anonymous>: no visible global function definition for
  ‘lines’
CGHSEGaroma : <anonymous>: no visible global function definition for
  ‘write.table’
CGHcall: no visible global function definition for ‘mad’
... 43 lines ...
tumorboostPlot: no visible global function definition for ‘par’
tumorboostPlot: no visible global function definition for ‘axis’
tumorboostPlot: no visible global function definition for ‘points’
Undefined global functions or variables:
  axis head lines lm mad median optim par points read.csv sd var
  write.table
Consider adding
  importFrom("graphics", "axis", "lines", "par", "points")
  importFrom("stats", "lm", "mad", "median", "optim", "sd", "var")
  importFrom("utils", "head", "read.csv", "write.table")
to your NAMESPACE file.
```

## NSA (0.0.32)
Maintainer: Maria Ortiz-Estevez <mortizest@gmail.com>

0 errors | 0 warnings | 6 notes

```
checking package dependencies ... NOTE
Depends: includes the non-default packages:
  ‘R.methodsS3’ ‘MASS’ ‘matrixStats’ ‘R.oo’ ‘R.utils’ ‘aroma.core’
  ‘aroma.affymetrix’ ‘DNAcopy’
Adding so many packages to the search path is excessive and importing
selectively is preferable.

checking top-level files ... NOTE
Non-standard file/directory found at top level:
  ‘incl’

checking dependencies in R code ... NOTE
Packages in Depends field not imported from:
  ‘DNAcopy’ ‘MASS’ ‘R.methodsS3’ ‘R.oo’ ‘aroma.affymetrix’ ‘aroma.core’
  ‘matrixStats’
  These packages need to be imported from (in the NAMESPACE file)
  for when this namespace is loaded but not attached.

checking S3 generic/method consistency ... NOTE
Found the following apparent S3 methods exported but not registered:
  NSAByTotalAndFracB.matrix allocateOutputDataSets.NSANormalization
  allocateOutputDataSets.SNPsNormalization
  allocateOutputDataSets.SampleNormalization
  as.character.NSANormalization as.character.SNPsNormalization
  as.character.SampleNormalization findArraysTodo.NSANormalization
  findArraysTodo.SampleNormalization findUnitsTodo.SNPsNormalization
  fitNSA.matrix fitNSAcnPs.matrix getDataSets.NSANormalization
  getDataSets.SNPsNormalization getDataSets.SampleNormalization
  getName.NSANormalization getName.SNPsNormalization
  getName.SampleNormalization getOutputDataSets.NSANormalization
  getOutputDataSets.SNPsNormalization
  getOutputDataSets.SampleNormalization getPath.NSANormalization
  getPath.SNPsNormalization getPath.SampleNormalization
  getRootPath.NSANormalization getRootPath.SNPsNormalization
  getRootPath.SampleNormalization process.NSANormalization
  process.SNPsNormalization process.SampleNormalization
  sampleNByTotalAndFracB.numeric snpsNByTotalAndFracB.matrix
See section ‘Registering S3 methods’ in the ‘Writing R Extensions’
manual.

checking R code for possible problems ... NOTE
NB: .First.lib is obsolete and will not be used in R >= 3.0.0

.First.lib: no visible global function definition for
  ‘packageDescription’
NSAByTotalAndFracB.matrix: no visible global function definition for
  ‘throw’
NSAByTotalAndFracB.matrix: no visible global function definition for
  ‘str’
NSANormalization: no visible global function definition for ‘throw’
... 279 lines ...
  extractMatrix findUnitsTodo getAsteriskTags getChipType getFile
  getFullName getFullNames getGenomeInformation getName getNames
  getPath getPathname getPathnames getPositions getRam getRootPath
  getTags getUnitsOnChromosome hist median nbrOfFiles newInstance
  packageDescription rowAlls rowMedians segment setTags str throw trim
  verbose
Consider adding
  importFrom("graphics", "hist")
  importFrom("stats", "approxfun", "median")
  importFrom("utils", "packageDescription", "str")
to your NAMESPACE file.

checking Rd line widths ... NOTE
Rd file 'NSANormalization.Rd':
  \examples lines wider than 100 characters:
     by <- 50e3; # 50kb bins; you may want to try with other amounts of smoothing xOut <- seq(from=xRange[1], to=xRange[2], by=by);
     plot(getSignals(cnCNPS), getSignals(cnSNPS), xlim=Clim, ylim=Clim); abline(a=0, b=1, col="red", lwd=2);

These lines will be truncated in the PDF manual.
```

## pbmcapply (1.2.1)
Maintainer: Kevin kuang <kvn.kuang@mail.utoronto.ca>  
Bug reports: https://github.com/kvnkuang/pbmcapply/issues

0 errors | 0 warnings | 0 notes

## PECA (1.12.0)
Maintainer: Tomi Suomi <tomi.suomi@utu.fi>

0 errors | 0 warnings | 1 note 

```
checking Rd line widths ... NOTE
Rd file 'PECA.Rd':
  \usage lines wider than 90 characters:
     PECA_AffyBatch(affy=NULL, normalize=FALSE, test="t", type="median", paired=FALSE, progress=FALSE)

These lines will be truncated in the PDF manual.
```

## PSCBS (0.62.0)
Maintainer: Henrik Bengtsson <henrikb@braju.com>  
Bug reports: https://github.com/HenrikBengtsson/PSCBS/issues

0 errors | 0 warnings | 0 notes

## PureCN (1.6.2)
Maintainer: Markus Riester <markus.riester@novartis.com>

0 errors | 0 warnings | 1 note 

```
checking installed package size ... NOTE
  installed size is  5.3Mb
  sub-directories of 1Mb or more:
    doc       1.6Mb
    extdata   2.4Mb
```

## QDNAseq (1.12.0)
Maintainer: Daoud Sie <d.sie@vumc.nl>  
Bug reports: https://github.com/ccagc/QDNAseq/issues

0 errors | 1 warning  | 0 notes

```
checking for missing documentation entries ... WARNING
Undocumented code objects:
  ‘exportVCF’
All user-level objects in a package should have documentation entries.
See chapter ‘Writing R documentation files’ in the ‘Writing R
Extensions’ manual.
```

## Repitools (1.22.0)
Maintainer: Mark Robinson <mark.robinson@imls.uzh.ch>

0 errors | 0 warnings | 3 notes

```
checking R code for possible problems ... NOTE
Found an obsolete/platform-specific call in the following function:
  ‘maskOut’
Found the platform-specific device:
  ‘windows’
dev.new() is the preferred way to open a new device, in the unlikely
event one is needed.
.cpgBoxplots: no visible global function definition for ‘pdf’
.cpgBoxplots: no visible global function definition for ‘par’
.cpgBoxplots: no visible global function definition for ‘dev.off’
... 291 lines ...
  rainbow read.table rect str t.test text title verbose
Consider adding
  importFrom("grDevices", "dev.off", "pdf", "rainbow")
  importFrom("graphics", "abline", "axis", "barplot", "bxp", "grid",
             "layout", "legend", "lines", "matlines", "matplot", "mtext",
             "par", "persp", "plot", "plot.new", "plot.window", "points",
             "polygon", "rect", "text", "title")
  importFrom("stats", "dbeta", "embed", "filter", "kmeans", "lm",
             "lowess", "p.adjust", "predict", "pt", "qnorm", "t.test")
  importFrom("utils", "read.table", "str")
to your NAMESPACE file.

checking Rd line widths ... NOTE
Rd file 'ChromaBlocks.Rd':
  \usage lines wider than 90 characters:
     ChromaBlocks(rs.ip, rs.input, organism, chrs, ipWidth=100, inputWidth=500, preset=NULL, blockWidth=NULL, minBlocks=NULL, extend=NULL, c ... [TRUNCATED]

Rd file 'GCbiasPlots.Rd':
  \usage lines wider than 90 characters:
                 cex = 0.2, pch.col = "black", line.col = "red", lty = 1, lwd = 2, verbose = TRUE)

Rd file 'absoluteCN.Rd':
... 57 lines ...

Rd file 'regionStats.Rd':
  \usage lines wider than 90 characters:
     regionStats(x, design = NULL, maxFDR=0.05, n.perm=5, window=600, mean.trim=.1, min.probes=10, max.gap=500, two.sides=TRUE, ndf, return. ... [TRUNCATED]
     regionStats(x, design = NULL, maxFDR=0.05, n.perm=5, window=600, mean.trim=.1, min.probes=10, max.gap=500, two.sides=TRUE, ind=NULL, re ... [TRUNCATED]

Rd file 'writeWig.Rd':
  \usage lines wider than 90 characters:
     writeWig(rs, seq.len = NULL, design=NULL, sample=20, drop.zero=TRUE, normalize=TRUE, verbose=TRUE)

These lines will be truncated in the PDF manual.

checking compiled code ... NOTE
File ‘Repitools/libs/Repitools.so’:
  Found no call to: ‘R_useDynamicSymbols’

It is good practice to register native routines and to disable symbol
search.

See ‘Writing portable packages’ in the ‘Writing R Extensions’ manual.
```

## R.filesets (2.11.0)
Maintainer: Henrik Bengtsson <henrikb@braju.com>  
Bug reports: https://github.com/HenrikBengtsson/R.filesets/issues

0 errors | 0 warnings | 0 notes

## startR (0.0.1)
Maintainer: Nicolau Manubens <nicolau.manubens@bsc.es>  
Bug reports: https://earth.bsc.es/gitlab/es/startR/issues

0 errors | 0 warnings | 0 notes

## TIN (1.8.0)
Maintainer: Bjarne Johannessen <bjajoh@rr-research.no>

0 errors | 0 warnings | 2 notes

```
checking top-level files ... NOTE
Non-standard file/directory found at top level:
  ‘doc’

checking R code for possible problems ... NOTE
aberrantExonUsage: no visible global function definition for ‘quantile’
aberrantExonUsage: no visible global function definition for ‘ave’
clusterPlot: no visible global function definition for ‘dist’
clusterPlot: no visible global function definition for ‘hclust’
clusterPlot: no visible global function definition for
  ‘colorRampPalette’
clusterPlot: no visible global function definition for ‘par’
clusterPlot: no visible global function definition for ‘png’
clusterPlot: no visible global function definition for ‘jpeg’
... 50 lines ...
  importFrom("stats", "ave", "dist", "hclust", "median", "quantile")
  importFrom("utils", "data", "read.table")
to your NAMESPACE file.

Found the following assignments to the global environment:
File ‘TIN/R/aberrantExonUsage.R’:
  assign("quantiles", quantiles, envir = .GlobalEnv)
  assign("aberrantExons", aberrantExons, envir = .GlobalEnv)
File ‘TIN/R/correlationPlot.R’:
  assign("randomGeneSetsDist", B, envir = .GlobalEnv)
  assign("traPermutationsDist", L, envir = .GlobalEnv)
```

## vesselr (0.2.1)
Maintainer: Jordan D. Dworkin <jdwor@mail.med.upenn.edu>

0 errors | 0 warnings | 0 notes

## warbleR (1.1.8)
Maintainer: Marcelo Araya-Salas <araya-salas@cornell.edu>  
Bug reports: https://github.com/maRce10/warbleR/issues

0 errors | 0 warnings | 0 notes

