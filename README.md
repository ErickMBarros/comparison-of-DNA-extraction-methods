# Scripts for article entitled:"Comparison of two widely used DNA extraction methods"
###### DOI: https://doi.org/10.1016/j.mimet.2019.02.005

This article was published by the Journal of Microbiological Methods at February, 2019

## Contact
Erick Mateus-Barros: erickmbarros@gmail.com
Hugo Sarmento: hsarmento@ufscar.br


## Overview
In this manuscript we compared two of the most commonly used environmental DNA extraction
methods in aquatic microbial ecology (Phenol:Chloroform and PowerSoil DNA isolation Kit) in order
to determine if both methods yield comparative results for community ecology analyses purposes. We
found that despite the small number of OTUs with significant differences, they have a significant
impact on the community and the results from these two extraction methods are not comparable.


## Repo content
This repo conteins all the scripts used to statistical analysis showed in the article, including:

* _[diversity-indexes.R](https://github.com/LMPB/comparison-of-DNA-extraction-methods/blob/master/diversity-indexes)_: Codes used to obtain the diversity indexes;
* _[paired-tests.R](https://github.com/LMPB/comparison-of-DNA-extraction-methods/blob/master/paired-tests)_: Codes used to analyse, pair-to-pair, each OTU obtained with different diversity indexes;
* _[permanova+mNDS](https://github.com/LMPB/comparison-of-DNA-extraction-methods/blob/master/permanova%2BnMDS)_: Codes used to anaylyse and create the figures of distance-based analyses of permutation and components.

## Dataset
The raw data the data is public in the __NCBI database__ under SRA accession number [PRJNA411849](https://www.ncbi.nlm.nih.gov/bioproject/411849).
