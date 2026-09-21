# Markedly divergent performance of variant annotation methods for gene-level association testing

This is the code release for "[Markedly divergent performance of variant annotation methods for gene-level association testing](https://doi.org/10.1186/s12864-026-13379-2)" (Irudayanathan and Aguirre, _et. al._, _BMC Genomics_ 2026). We provide analysis code in this repository as-is under an MIT license to support the reproducibility of our work. 

The data release, which comprises variant scores and association test summary statitics, can be found on [Figshare](https://doi.org/10.6084/m9.figshare.32248455).

## Contents

This repository contains four analysis notebooks that contain all of the code necessary to replicate our findings and recreate figures from our manuscript. They operate directly on the files made available in the data release. The notebooks respectively correspond to:
 - Primary analysis of rare variant association tests in the UK Biobank (`main.ipynb`)
 - Replication study in the All of Us cohort (`aou.ipynb`)
 - Sensitivity analysis of minor allele frequency thresholding for burden tests (`maf.ipynb`)
 - Analysis of signal aggregation across annotation methods with [ACAT](https://pubmed.ncbi.nlm.nih.gov/30849328/) (`acat.ipynb`) 

We also provide the commands we used to run association tests with [REGENIE](https://rgcgithub.github.io/regenie/). These can be found in the `scripts` subdirectory. 

## Contact

Please direct questions related to this repository to the corresponding authors of the manuscript. 

## License

Copyright 2026, Genentech, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
