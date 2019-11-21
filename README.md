# BioCircosGenomicVisualization
Web app to display gene mutations with known links to cancer development. 

#new pakage#
  
install.packages('BioCircos')

if (!require('devtools')){install.packages('devtools')}

devtools::install_github('lvulliard/BioCircos.R', build_vignettes = TRUE)



#get circle#
  
library(BioCircos)

BioCircos()
