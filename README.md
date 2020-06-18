# Get dbsnp information with script.
## Method 1:
For example: rs191548761: https://www.ncbi.nlm.nih.gov/snp/rs1449699134
get json file with this link: 
https://api.ncbi.nlm.nih.gov/variation/v0/beta/refsnp/1449699134
In R, you can use jsonlite to import with this link directly.
then figure out to parse the required information with script. 
I believe python can do the same thing.

The code is here:
https://github.com/ncbi/dbsnp/blob/master/tutorials/hadoop_json_placement.py

NCBI dbSNP json API:
https://ncbiinsights.ncbi.nlm.nih.gov/2018/06/15/dbsnp-updates-json-refsnp-report-api/

## Method 2:
SNPnexus.org
can output tsv format
but the population data are not very comprehensive.

## method 3:
VEP or annovar, just do the annotation.
This is a really cool approach.

## method 4:
biomaRt?

## method 5:
https://thelaziestprogrammer.com/bioinformatics/warehousing-DbSNP-Part-I-download-and-create-db#parsing-the-json-data
Will adapt this.
