# Model-Asset-eXchange-and-the-Data-Asset-Exchange
Model Asset eXchange and the Data Asset Exchange

In this lab, we will explore the Model Asset Exchange (MAX) and the Data Asset Exchange (DAX), which are two open-source Data Science resources on IBM Developer.

# Objective of Exercise 1:
- Find open data sets on IBM Developer.
- Explore the data sets.

# Objective of Exercise 2:
- Find ready-to-use deep learning models on the Model Asset Exchange.
- Explore the deep learning model trained to detect objects in an image.

  

# Exercise 1: Explore deep learning datasets
The Data Asset Exchange is a curated collection of open datasets from IBM Research and third-parties that you can use to train models.

1. Open [This](https://developer.ibm.com/exchanges/data/) in your web browser.The IBM Data Asset eXchange (DAX) home page is displayed. This is an online hub for developers and data scientists to find free and open data sets under open data licenses. These datasets can be used to train models to perform document layout analysis, natural language processing (NLP), time series analysis, and more.

![image](https://github.com/user-attachments/assets/92f0e21d-26a8-4b5f-bb51-708901845f6f)

2. In this activity, you will explore NOAA Weather Data dataset.

3. Open the NOAA Weather Data dataset [here](https://developer.ibm.com/exchanges/data/all/jfk-weather-data/), which contains data from a weather station at the John F. Kennedy Airport in New York spanning eight years.
The dataset was published under the data science friendly CDLA-Sharing license [here](https://cdla.io/).
The dataset contains time-series data and can be used to predict weather trends.
This dataset was used to train the weather forecaster model on MAX [here](https://developer.ibm.com/exchanges/models/all/max-weather-forecaster/).

![image](https://github.com/user-attachments/assets/97870cca-6f08-476f-9068-002db5ccdc3c)



3. Inspect the dataset's metadata.
This dataset is stored as tabular data and formatted as a comma separated value (CSV) file, which is a very popular basic data exchange format.

4. We can download the dataset using the Get this dataset link. Datasets are stored as compressed archives, which you can extract using any utility that supports the targz format. If you are not familiar with this file format, take a look at this short open source tutorial https://opensource.com/article/17/7/how-unzip-targz-file.

5. Most datasets are complemented by Python notebooks that you can use to explore, pre-process, and analyze the data. The notebooks are hosted on Watson Studio, IBM's Data Science platform. Later in this course, you'll learn more about Watson Studio notebooks, how to sign up and how to run notebooks on them.

6. For now, you can preview the dataset and the notebook (or notebooks) by clicking the Preview the data and notebooks as shown in the screenshot below.
NOAA Weather Data dataset with Preview data and notebooks highlighted


![image](https://github.com/user-attachments/assets/6a8fcb51-9185-429a-8981-b20663415943)
This will display dataset metadata, sample records and glossary as shown in the screenshot below.


![image](https://github.com/user-attachments/assets/8da3bebd-1ae5-4302-bbf4-b04a612e63d4)

Now here, you click on the Notebook Preview option on top to view the notebook hosted with this dataset. Explore the steps followed in this notebook to clean data before performing data analysis on this dataset.

![image](https://github.com/user-attachments/assets/f96bb6dd-4779-4bb0-9c12-157175e1ce6b)


This concludes Exercise 1 of this lab, which introduced the Data Asset Exchange




