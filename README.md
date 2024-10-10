# Columns_Metabolomics
# Supplementary Material
The code provided by this repository is part of the supplementary material for the scientific article "Comparison of reversed‑phase, hydrophilic
interaction, and porous graphitic carbon chromatography columns for an untargeted toxicometabolomics study in pooled human liver microsomes, rat
urine, and rat plasma" by Selina Hemmer et al., Metabolomics, 2024 (<DOI:10.1007/s11306-024-02115-0>). See the following sections for detailed information
about it. Corresponding files can be found at MetaboLights using the study identifier MTBLS5082.

# Source Code

## Dependencies

The code deployed by this repository requires the following packages:

-   tidyverse (CRAN)
-   ggrepel (CRAN)
-   gplots (CRAN)
-   MASS (CRAN)
-   caret (CRAN)
-   XCMS (Bioconductor)
-   CAMERA (Bioconductor)

If not installed you can use the following lines to install them:

     `install.packages(c("tidyverse", "ggrepel", "gplots", "MASS", "caret")
     source("https://bioconductor.org/biocLite.R")
     biocLite(c("xcms", "CAMERA"))`

Additionally, evaluation script require functions provided by the metaboLib.R library. The corresponding library can be found [here](https://github.com/saskema/metaboLib).

## Usage

To use the scripts as deployed in this repository, place the matching script in the same folder were the files are grouped in folders corresponding to their study group (e.g. "Blank", "PCYP", "QC") and run it.

## Result

You will obtain the following files:

-   evaluateResults/samoleStatistic.pdf
-   evaluateResults/Chromatogram.pdf
-   evaluateResults/peaklistCAMERA.csv
-   evaluateResults/significant_results.csv
