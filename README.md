# Aviation Safety Analysis


### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [CRISP-DM process](#CRISP-DM)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

No other libraries are needed to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using NTSB accident data to better understand:

1. When is the most dangerous time during each flight phases?
2. Is airplane more safe or less safe during the last few decades?
3. Which airplane model has the highest fatal accident?

## File Descriptions <a name="files"></a>

This [README](./README.md) gives an overview of the libary installation, project motivation, file descriptions, result article, and licensing information.

Data is avaiale in the [csv](./AviationData.csv) file.

Python Jupyter Notebook available [here](./Aviation.ipynb) is the script to answer the above questions. 

## CRISP-DM process implemented in the analysis <a name="CRISP-DM"></a>

1. Business Objectives  
2. Data Understanding  
  2.1 Read NTSB aviation accident data  
  2.2 Check data size  
  2.3 Check field names  
  2.4 Check sample data  
3. Data Preparation  
  3.1 Which fields have missing data?  
  3.2 Handle missing data 
  3.3 Verify data quality  
  3.4 Clean data  
  3.5 Keep relevant data field  
  3.6 Country counts  
  3.7 Numerical fields statistics  
  3.8 Handel categorical variables  
4. Statistic Analysis  
  4.1 When is the most dangerous time during each flight phases?  
  4.2 Is airplane more safe or less safe during the last few decades?  
  4.3 Which airplane has the highest fatal accidents?  
5. Deployment  
6. Conclusion  

## Results<a name="results"></a>

The main findings of the code can be found at the blog article [here](https://medium.com/@qiuxinjie/3-things-you-need-to-know-about-the-of-air-travel-safety-43cddf33cd23).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit goest to NTSB and Kaggle for the data. You can find the Licensing for the data and other descriptive information at the NTSB [here](https://www.ntsb.gov/_layouts/ntsb.aviation/index.aspx) and Kaggle link available [here](https://www.kaggle.com/khsamaha/aviation-accident-database-synopses). Otherwise, feel free to use the code here as you would like! 

