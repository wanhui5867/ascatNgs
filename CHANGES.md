### 2.0.0
* Now species agnostic provided you can generate a panel of SNPs, approx 1 HET per 2kb is required.  Tools are included in the package for guided and unguided SNP generation.  More details can be found in the [wiki](https://github.com/cancerit/ascatNgs/wiki).
* Supports CRAM
* Allele count phase is now threaded.

NOTE: Individual scripts called by `ascat.pl` have been renamed to prevent potential namespace clashes.