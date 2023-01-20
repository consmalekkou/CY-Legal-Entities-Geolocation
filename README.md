# CY-Legal-Entities-Geolocation
Project by Constantia Malekkou for Big Data Management and Processing (COMP548)

### Objectives

As the course title suggests, the project objectives are the exploration of the V dimensions of Big Data. In this project we are dealing with the Variety dimension as we are transforming address text to geolocation. The task was to identify if the visualization of customer address data on a map, would provide enough insights to a company to the optimal physical store locations.

### Description
For the purposes of this specific project, we have considered as sample population the legal entities registered in Cyprus. Data has been gathered through the 
[CY Open Data portal](https://www.data.gov.cy/dataset/%CE%BC%CE%B7%CF%84%CF%81%CF%8E%CE%BF-%CE%B5%CE%B3%CE%B3%CE%B5%CE%B3%CF%81%CE%B1%CE%BC%CE%BC%CE%AD%CE%BD%CF%89%CE%BD-%CE%B5%CF%84%CE%B1%CE%B9%CF%81%CE%B5%CE%B9%CF%8E%CE%BD-%CE%B5%CE%BC%CF%80%CE%BF%CF%81%CE%B9%CE%BA%CF%8E%CE%BD-%CE%B5%CF%80%CF%89%CE%BD%CF%85%CE%BC%CE%B9%CF%8E%CE%BD-%CE%BA%CE%B1%CE%B9-%CF%83%CF%85%CE%BD%CE%B5%CF%84%CE%B1%CE%B9%CF%81%CE%B9%CF%83%CE%BC%CF%8E%CE%BD-%CF%83%CF%84%CE%B7%CE%BD-%CE%BA%CF%8D%CF%80%CF%81%CE%BF) for all legal entities registered in Cyprus and their registered office addresses. The office addresses have been translated to geolocations through the Geocoding API in Google Cloud Platform.

Code was developed to run through JupyterLab Notebook with PySpark kernel on the Google Cloud Platform. The additional components needed for this project to run on the Google Cloud Platform are Dataproc with Compute Engine Virtual Machines and Storage Bucket. The code makes use of the PySpark Dataframe RDD data structure for fast and effective data processing. Persisting the entire legal entity population with geolocations RDD to disk storage was not pursued, as the dataset was quite large for the resources available. The results will be presented through a sample of 20k legal entities with geolocations, with the potential to grow to the full population given additional resources.

### Attachments
- Geolocation Project CM.ipynb
  PySpark Notebook with the code to translate the text address data to geolocations and merge with the registered legal entities.
- Legal entities datasets.zip
  Datasets for the Registered Legal Entities and the Registered Offices. Datasets have been slightly preprocessed with excel to fix import errors. Following import       they have been further preprocessed through Python
- Map_btch1.csv
  Sample dataset with results from the Pyspark Notebook

### Deliverables
- [Interactive map visualisation of a sample result dataset through Google DataStudio (Looker)](https://datastudio.google.com/reporting/86bf60bc-1025-4140-b94a-aa0002f656be) 

- Video project description and results presentation


Developed by: Constantia Malekkou

Contact email: constantia.malekkou@gmail.com


