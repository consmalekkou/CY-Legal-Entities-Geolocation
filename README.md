# CY-Legal-Entities-Geolocation
Project by Constantia Malekkou for Big Data Management and Processing (COMP548)

### Objectives

As the course title suggests, the project objectives are the exploration of the V dimensions of Big Data. In this project we are dealing with the Variety dimension as we are transforming address text to geolocation. The task was to identify if the visualization of customer address data on a map, would provide enough insights to a company to the optimal physical store locations.

### Description
For the purposes of this specific project, we have considered as sample population the legal entities registered in Cyprus. Data has been gathered through the 
CY Open Data portal for all legal entities registered in Cyprus and their registered office addresses. The office addresses have been translated to geolocations through the Geocoding API in Google Cloud Platform.

Code was developed to run through JupyterLab Notebook with PySpark kernel on the Google Cloud Platform. The additional components needed for this project to run on the Google Cloud Platform are Dataproc with Compute Engine Virtual Machines and Storage Bucket. The code makes use of the PySpark Dataframe RDD data structure for fast and effective data processing. Persisting the entire legal entity population with geolocations RDD to disk storage was not pursued, as the dataset was quite large for the resources available. The results will be presented through a sample of 20k legal entities with geolocations, with the potential to grow to the full population given additional resources.

### Attachments / Deliverables
- Geolocation Project CM.ipynb - PySpark Notebook with the code to translate the text address data to geolocations and merge with the registered legal entities.
- Registered Legal Entities Dataset 
- Registered Offices Dataset
- Sample dataset with results

- Video project description and results presentation can be found by clicking here.


Developed by: Constantia Malekkou
Contact email: constantia.malekkou@gmail.com


