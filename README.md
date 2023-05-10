# SambaR

SambaR is a R package which allows users to import a biallelic SNP dataset into R and to perform quality control and population genetic analyses with a minimum number (i.e. ≤ 10) of R commands. Summary statistics and analyses outcomes are automatically exported in ready to publish graphs with coherent layout (i.e. consistent font type, font size and colour coding based on population assignment).

The selection scan 'GWDS' is implemented in SambaR.

The easiest way to start using SambaR is to load the script directly from this Github page into R, by typing on the R command line:
source("https://github.com/mennodejong1986/SambaR/raw/master/SAMBAR_v1.xx.txt")   # replace xx with the correct version

However, you will need the manual for further instructions. Therefore, if you are a first-time user, download SambaR from this website using the green 'Code' button (choose 'Download ZIP'), unzip the folder, and follow the instructions in the SambaR manual (which will be included in the download). Note: do NOT use the git clone command, because this will not work. We intend to make this option available at a later point in time. An example dataset is provided in the example dataset directory, which will also be included in the download. Users must agree with the terms of the LICENSE.


UPDATE 22-04-2021

By default, the calcdiversity() function of SambaR does no longer generate SFS-vectors. Users can still enable this utility, but are adviced to generate SFS vectors using more established methods (e.g., ANGSD, EasySFS or Popgen Pipeline Platform).     


## How to cite SambaR

If you use SambaR for scientific publications, please cite:

Menno J. de Jong, Joost F. de Jong, A. Rus Hoelzel, Axel Janke, 2021, SambaR: an R package for fast, easy and reproducible population‐genetic analyses of biallelic SNP datasets, Molecular Ecology Resources, doi/10.1111/1755-0998.13339

If you make use of the selection scan GWDS for scientific publications, please cite in addition:

Menno de Jong, Fiona Lovatt, A. Rus Hoelzel, 2021, Detecting genetic signals of selection in heavily bottlenecked reindeer populations by comparing parallel founder events, Molecular Ecology, doi/10.1111/mec.15837

Do not forgot to also cite all applicable references of other R packages which SambaR uses to generate the output. A file with a list of references will be available in the SambaR output directories.







