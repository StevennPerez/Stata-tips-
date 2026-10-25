# Stata-tips-
Habilidades en Stata para manejo de datos y análisis económico

1.How to create a codebook
User-written commands: none 

*Load training data 
sysuse nlsw88 

*Codebook 
codebook

*Log the codebook 
log using codebook.txt, replace text 
codebook, all problems detail 
