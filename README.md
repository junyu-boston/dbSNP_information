# Get dbsnp information with script.
## Method 1:
For example: rs191548761: https://www.ncbi.nlm.nih.gov/snp/rs1449699134
get json file with this link: 
https://api.ncbi.nlm.nih.gov/variation/v0/beta/refsnp/1449699134
In R, you can use jsonlite to import with this link directly.
then figure out to parse the required information with script. 
I believe python can do the same thing.

## Method 2:
SNPnexus.org
can output tsv format
but the population data are not very comprehensive.

## method 3:
VEP or annovar, just do the annotation.
This is a really cool approach.

## method 4:
biomaRt?
