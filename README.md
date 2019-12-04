# Climate-Data-Analysis
* This repository contains nine Jupyter Notebooks:

Visualisation Notebooks:
    1. US-Climate-1.ipynb
    2. US-Climate-2.ipynb
    
Machine Learning for Rain and Weather prediction:
    1. Classification
    2. Classification-Abalations0
    3. Classification-Abalations1
    4. Classification-Abalations2
    5. Classification-Abalations3
    6. Classification-All Features
    7. Decision Tree-ver2


* Both notebooks have different kinds of visualisations and interactive tools to play with. User interacts with the Spark Dataframes by selecting data to be filtered and consequently, maps and plots are shown.

* Dataset: The dataset is a BigQuery Data and can be found at https://bigquery.cloud.google.com/dataset/bigquery-public-data:noaa_gsod.
For analysis, data from 2009 to 2019 was retrieved using BigQuery Client API. The size of data is approx 6 GB. The paths of the dataset should be changed in the notebook dependingon where the data resides in your machine.

* These notebooks were created in Google Colab, therefore, pip installs were done for the required packages at the start of the notebook. Feel free to skip those cells while running if you already have the required packages. The list of required packages used in this analysis are:

  1. Spark - The climate data is huge, spark was used to for parallel processing of the data.
  2. Visualisation libraries - 
      Folium - Interactive plots were created using folium and vincent.
      Matplotlib
      Seaborn
      Basemap
 
Screenshot of few plots have been attached for reference as they are not rendering on github.
