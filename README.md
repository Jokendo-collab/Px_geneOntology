## Px_geneOntology
This workflow is used to analyse the proteomics data using the clusterprofiler package.

# load Libraries (install if necessary) 

```packages = c("BiocManager","tidyverse","clusterProfiler","org.Hs.eg.db")

package.check <- lapply(packages, FUN = function(x) {
    if (!require(x, character.only = TRUE)) {
        install.packages(x, dependencies = TRUE)
        library(x, character.only = TRUE)
    }
})```


