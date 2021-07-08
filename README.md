# Microarray-Expression

Access the ArrayExpress Microarray Database at EBI and build Bioconductor data structures: ExpressionSet, AffyBatch, NChannelSet

* Installation Details see in(http://www.bioconductor.org/packages/release/bioc/html/ArrayExpress.html) 

To install this package, start R (version "4.1") and enter:
Author: Audrey Kauffmann, Ibrahim Emam, Michael Schubert

* Maintainer: Suhaib Mohammed <suhaib at ebi.ac.uk>

* Citation (from within R, enter citation("ArrayExpress")):

Kauffmann A, Rayner TF, Parkinson H, Kapushesky M, Lukk M, Brazma A, Huber W (2009). “Importing ArrayExpress datasets into R/Bioconductor.” Bioinformatics, 25(16), 2092–4.
  
```bash
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("ArrayExpress")
```

  To view documentation for the version of this package installed in your system, start R and enter:
  
  ```
  browseVignettes("ArrayExpress")
  ```
