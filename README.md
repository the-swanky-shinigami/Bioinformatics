# Bioinformatics
Some codes for general purpose bioinformatics 

Split VCF File by Column Value

Overview

This script processes a VCF (Variant Call Format) file, ensures all rows have the same number of columns, and then splits the file into multiple parts based on the values in the 20th column. Each split dataset is saved as a separate .vcf file.

Features

* Reads a large VCF file without skipping any data.

* Ensures irregular rows with extra/missing columns are properly handled.

* Identifies unique values in the 20th column.

* Splits the data into multiple DataFrames based on those values.

* Saves each subset as a new VCF file in a separate folder.

Requirements

* Python 3.7+

* Pandas
