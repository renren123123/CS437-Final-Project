# CS437-Final-Project


This repo includes file to process the ADC data, prerecorded files, notebook that includes our code to pass the npy files.

## Collecting data

First raw ADC data needs to be collected using a mmwave radar using ADCDataCapture.cfg as the config file. To parse the bin data, the parse_bin_data.py file needs to be updated with the file name of the raw bin data needed to be processed. After editing the file name the parse_bin_data.py file can be run and it wil output a .npy file with the timestamp that it was processed.

Make sure to take a reading of baseline data, and another for data that has items

- parse_bin_data.py

### Parsing the data

For our code we use Demo.ipynb to read the parsed bin data and calculate its outcome. 

The first box of Demo.ipynb is where you should put the file names for the base line data and the data you would want to compare the base line data with

The second box of Demo.ipynb is the analysis of the baseline data and the third box is the data of baseline data - real data:

![alt text](https://github.com/renren123123/CS437-Final-Project/blob/main/Smoothed%20Baseline.PNG)


From there you can change the filename for 'rawData' to test and compare with different cabin enviornments.

