# Turbofan Predictive Maintenance
Exploring NASA's Turbofan dataset to predict Remaining Useful Life (RUL) on the turbofan datasets.
## About Dataset
Prognostics and health management is an important topic in industry for predicting state of assets to avoid downtime and failures. This data set is the Kaggle version of the very well known public data set for asset degradation modeling from NASA. It includes Run-to-Failure simulated data from turbo fan jet engines.
Engine degradation simulation was carried out using C-MAPSS. Four different were sets simulated under different combinations of operational conditions and fault modes. Records several sensor channels to characterize fault evolution. The data set was provided by the Prognostics CoE at NASA Ames.
- [**Dataset**](https://data.nasa.gov/Aerospace/CMAPSS-Jet-Engine-Simulated-Data/ff5v-kuh6)

The notebooks are used to explore the dataset and try various modeling techniques (both Machine Learning and Neural Networks). The data are provided as a zip-compressed text file with 26 columns of numbers, separated by spaces. Each row is a snapshot of data taken during a single operational cycle, each column is a different variable. The columns correspond to:

| Dataset | Operating conditions | Fault modes | Train size (nr. of engines) | Test size (nr. of engines) | notebook |
| --- | --- | --- | --- | --- | --- |
| FD001 | 1 (Sea Level) | 1 (HPC Degradation) | 100 | 100 | [**01_FD001**](https://github.com/DennisxB/turbofan-predictive-maintenance/blob/main/01_FD001.ipynb) :white_check_mark: |
| FD002 | 6 | 1 (HPC Degradation) | 260 | 259 | [**03_FD002**](#) |
| FD003 | 1 (Sea Level) | 2 (HPC Degradation, Fan Degradation) | 100 | 100 | [**02_FD003**](https://github.com/DennisxB/turbofan-predictive-maintenance/blob/main/02_FD003.ipynb) :white_check_mark: |
| FD004 | 6 | 2 (HPC Degradation, Fan Degradation) | 248 | 249 | [**#**](#) |
