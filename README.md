# SambaR

SambaR is a R package which allow users to import a SNP dataset into R and to perform quality control and population genetic analyses with a minimum number (i.e. ≤ 10) of commands. Summary statistics and analyses outcomes are automatically exported in ready to publish graphs with coherent layout (i.e. consistent font type, font size and colour coding based on population assignment).

The selection scan 'GWDS' is implemented in SambaR.

To start using SambaR, simply download SambaR from this website using the green 'Clone or download' button (choose 'Download ZIP'), unzip the folder, and follow the instructions in the manual. The main commands to run SambaR are:

source("SAMBAR_v1.00.txt")

setwd("C:/path/to/workingdir/")

getpackages(myrepos='http://cran.us.r-project.org',mylib=NULL)

importdata(inputprefix="SNPdataprefix")

filterdata(indmiss=0.25,snpmiss=0.1)

findstructure(Kmax=6)

calcdistance()

calcdiversity()

selectionanalyses()

backupdata("mySNPdata")

Example datasets are provided in the example datasets directory (which will be included in the download).
