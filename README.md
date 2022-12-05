# PeRACE-dataset
Persian automatic translation of RACE dataset (multiple-choice machine reading comprehension dataset) using GNMT


PeRACE is an automatic Persian translation of the RACE dataset, which consists of RACE-M and RACE-H, using Google Neural Machine Translation. According to the errors of machine translation, we consider PeRACE as the noisy data. PeRACE consists of PeRACE-M and PeRACE-H, respectively; the statistics are listed below.



|     Dataset   | |PeRACE-M |  |   |PeRACE-H |   |
| ------------- | :---:|:---:|:---: | :---:|:---:|:---: |
|   |  train|   dev  | test   |   train  | dev | test  |
| #questions    | 25,421 | 1,436  | 1,436  |  62,445 | 3,451 | 3,498  |

PeRACE.zip file contains PeRACE-H and PeRACE-M, including train, dev, and test files. The data.csv files in each of them contain seven columns of information, including text, options [from 0 to 3], queries, and answers [A, B, C, or D].

.table-scrollable
{
    width: 100%;
    border-collapse: collapse;
    border-spacing: 0;
}

.table-scrollable thead,
.table-scrollable tbody,
.table-scrollable tr,
.table-scrollable td,
.table-scrollable th
{
    display: block;
}

.table-scrollable tr:after
{
    content: ' ';
    display: block;
    visibility: hidden;
    clear: both;
}

.table-scrollable thead th
{
    height: 32px;
    line-height: 32px;
}

.table-scrollable tbody
{
    height: 200px;
    overflow-y: scroll;
}

.table-scrollable thead
{
    width: 97%;
    width: calc(100% - 17px);
}

.table-scrollable tbody td,
.table-scrollable thead th
{
    width: 20%;
    float: left;
}

.table-scrollable tbody td:last-child,
.table-scrollable thead th:last-child
{
    border-right: none;
}

.table-scrollable > tbody > tr > td
{
    padding: 13px 9px;
}

