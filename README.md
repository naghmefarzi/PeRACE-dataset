# PeRACE-dataset
Persian automatic translation of RACE dataset (multiple-choice machine reading comprehension dataset) using GNMT


PeRACE is an automatic Persian translation of the RACE dataset, which consists of RACE-M and RACE-H, using Google Neural Machine Translation. According to the errors of machine translation, we consider PeRACE as the noisy data. PeRACE consists of PeRACE-M and PeRACE-H, respectively; the statistics are listed below.



|     Dataset   | |PeRACE-M |  |   |PeRACE-H |   |
| ------------- | :---:|:---:|:---: | :---:|:---:|:---: |
|   |  train|   dev  | test   |   train  | dev | test  |
| #questions    | 25,421 | 1,436  | 1,436  |  62,445 | 3,451 | 3,498  |

PeRACE.zip file contains PeRACE-H and PeRACE-M, including train, dev, and test files. The data.csv files in each of them contain seven columns of information, including text, options [from 0 to 3], queries, and answers [A, B, C, or D].


