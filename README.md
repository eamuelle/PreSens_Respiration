PreSens
=======

R script for analysis of PreSens Respiration Data


Known Issues:
1. When using .txt files: The User Comment should be on a single line (line 4) of the document. It this is not the case you will get the following error:
    Error in if (panel$end > panel$start) { : 
    missing value where TRUE/FALSE needed
