# VoIP Call Analysis with PySpark on Google Colab

This project analyzes VoIP call data using PySpark on Google Colab. The analysis includes selecting MSISDN, filtering specific date-time ranges, identifying and calculating various metrics for each VoIP call, and distinguishing between audio and video calls based on bitrate.

## Prerequisites

1. You must be signed into your Google account.
2. Basic knowledge of PySpark.
3. ipdr.csv file to be uploaded in colab

## Getting Started

### Setup Google Colab

1. Open open `Dobby_VoIP_Call_Analysis.ipynb` file in this repo
2. Then click on `Open in Colab` as seen below <br>
   <img width="956" alt="Opening_Colab" src="https://github.com/user-attachments/assets/57afedbc-fc0b-4d13-b303-1b2ec3ee8e5a">


### Uploading csv file
* In your Colab notebook, click on the folder icon on the left sidebar to open the file explorer.<br>
* Click on the upload icon (a file with an upward arrow) and select the ipdr.csv file from your computer. This will upload the file to the Colab environment.


### Install and Configure PySpark

Run the following commands in a Colab cell to install PySpark:

```
!pip install pyspark
```
Then run all the subsequent cells
