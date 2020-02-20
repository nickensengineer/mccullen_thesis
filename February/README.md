# Notes


## here are the 5 files that we need to clean and why.

|  VARIABLE  |FILENAME                  |NOTES                                                         |
|------------|--------------------------|--------------------------------------------------------------|
|est_vet_pop | proportion1.csv          |                                                   |
|moe_prop    | std_err_prop.csv         | the moe_prop var is calc'd based on the std_err_prop.csv file|
|est_ratio   | est_ratio5.csv           |                                                              |
|moe_ratio   | std_err_prop.csv         | moe_ratio = std_ratio * 1.65, std_ratio = std_err_prop.csv   |
|population  | ACS_Full_Table_Copy1.csv |                                                              |


the exclude block is not preventing us from divide by zero warnings and errors, thus sticking the code in an uncaught exception, so it is not finishing. we need to download and clean these 5 files and then reupload them and the code should complete. 