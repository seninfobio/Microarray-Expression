# Microarray-Expression

Access the ArrayExpress Microarray Database at EBI and build Bioconductor data structures: ExpressionSet, AffyBatch, NChannelSet

* Installation

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
