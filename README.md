# Auto-Embedded-Transformer-for-Few-shot-Bearings-Fault-Diagnosis

1.	Source code source https://github.com/OneBugMaker/AET/
2.	the original data source https://github.com/s-whynot/CWRU-dataset code/data 
3.	for the data after the rename the file location (to, and in the original code Processing data consistent naming format) 
4.	AET/main ipynb delete for model training and validation code file
5.	In addition to the Gaussian white noise added to the sample input in the original code (which can also reduce the variance to reasonable data), the noise variance added to the original code is obviously too large, resulting in unstable training.
6.	Code needs to tensorflow - gpu2.5 above and run again
