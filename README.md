# Backend-Data-Engineer-Internship
This repository contains all the necessory .py &amp; .ipynb files that are required for Backend Data Internship
Following are the instructions which must be followed to clone this repository:
1. Install Anaconda
2. Install all necessarry libraries on your local machine ehich include- pandas,xlrd, matplotlib,scipy
3. Keep both the data files named 'data.xlsx' and 'data_1.xlsx' inside the same folder where you will be running the python scripts 

# Following are the sequence in which you must run the scripts
1.Task1-creation of 3 different .csv files - After running this script you will get 3 files named, 
  1. 'detail.csv',
  2. 'detailVol.csv' and
  3. 'detailTemp.csv'.
These files are the output that is being generated once the python scripts are run sucessfully.
All three output files will be stored inside your root folder where all these scripts are executed. 

2.Task2-down-sampling- This script takes 3 files as inputs named, 'detail.csv','detailVol.csv' & 'detailTemp.csv'. These files are output which is received after sucessfully executing the 1st script. Here we are applying down-sampling method to reduce the sampling rate to 1 sample/minute from 1 sample/second. This operation is performed in all 3 input files and following 3 output files are being generated:
  1. 'detailDownsampled.csv'
  2. 'detailVolDownsampled.csv' and
  3. 'detailTempDownsampled.csv'

3.Task3-low-pass-filter- Applying low pass filter technique for noise removal on the data set for 'detailVolDownsampled.csv' and showing the distribution of the dataset through visualization

