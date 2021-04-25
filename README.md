# Hackthon
# R code

library(readxl)
> ZOOM <- read_excel("~/Desktop/ZOOM.xlsx")
> View(ZOOM)                                                                            
> library(readxl)
> ZOOM <- read_excel("~/Desktop/ZOOM.xlsx")
> View(ZOOM) 

#rename

> colnames(ZOOM)[1]="NAME"
> colnames(ZOOM)[2]="DATE"
> colnames(ZOOM)[3]="TIME"
> colnames(ZOOM)[4]="RESOURCE"
> colnames(ZOOM)[5]="RESDETAIL"
> colnames(ZOOM)[7]="USEDZOOM"
> colnames(ZOOM)[10]="PERSONALITY"
> colnames(ZOOM)[11]="PSCORE"
> colnames(ZOOM)[12]="AFFECTED"
> colnames(ZOOM)[13]="MENTALAFF"
> colnames(ZOOM)[14]="AFFSCORE"
> colnames(ZOOM)[15]="PREFER"
> colnames(ZOOM)[16]="RZZ"
> colnames(ZOOM)[17]="RZI"

