# Climate-Data-Analysis
* This repository contains ten Jupyter Notebooks:

Visualisation Notebooks:

    1. Climate_US_1.ipynb
    2. Climate_US_2.ipynb
    
    * Both notebooks have different kinds of visualisations and interactive tools to play with. User interacts with the Spark Dataframes by selecting data to be filtered and consequently, maps and plots are shown.
    * These notebooks were created in Google Colab, therefore, pip installs were done for the required packages at the start of the notebook. 
    Feel free to skip those cells while running if you already have the required packages. The list of required packages used in this analysis are:

  1. Spark - The climate data is huge, spark was used to for parallel processing of the data.
  2. Visualisation libraries - 
       a. Folium - Interactive plots were created using folium and vincent.
       b. Matplotlib
       c. Seaborn
       d. Basemap
 
Note : Screenshot of few plots have been attached for reference as they are not rendering on github. Also, ipywidgets are not redering on github. The notebook will be published soon to get all visualisations as they are not visible on github.


* Dataset: The dataset is a BigQuery Data and can be found at https://bigquery.cloud.google.com/dataset/bigquery-public-data:noaa_gsod.
For analysis, data from 2009 to 2019 was retrieved using BigQuery Client API. The size of data is approx 6 GB. The paths of the dataset should be changed in the notebook dependingon where the data resides in your machine.


