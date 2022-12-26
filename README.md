# Anomaly Detection IoT23
## Research Paper
This project is part of the research under   
*Machine Learning and Deep Learning Methods for Better Anomaly Detection in IoT-23 Dataset Cybersecurity*.  
  
* The goal of the research was to find the best solution based on time efficiency and accuracy.  
* This paper proposed an anomaly detection system model for IoT security with the implementation of ML/DL methods, including Naïve Bayes, SVM, Decision Trees, and CNN.  
* The proposed method reached better accuracy compared to other paper.  
* The research was performed on the IoT-23 dataset.  
  
## Data Preprocessing
This file is the data preprocessing for IoT-23 dataset. It loads 23 datasets seprately into Pandas dataframe, then skip the first 10 rows (headers) and load the 100,000 rows after. When finished, it combines 23 dataframes into a new dataset:  
iot23_combined.csv  
Note: The lighter version (8.8GB) of IoT-23 dataset was used in this research.
  
## Models
There are total of 4 models are implemented in this project:  
* CNN
* SVM
* Decision Trees
* Navie Bayes
  
## Environment Settings
Anaconda Jupyter Notebook  
Python 3.8  
Tensorflow 2.4  
  
## IoT-23 Dataset  
Stratosphere Laboratory. A labeled dataset with malicious and benign IoT network traffic. January 22th. Agustin Parmisano, Sebastian Garcia, Maria Jose Erquiaga.  
https://www.stratosphereips.org/datasets-iot23
