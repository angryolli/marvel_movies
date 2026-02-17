# Marvel Movies Data Pipeline

## Overview

**marvel_movies** is a cloud-integrated data pipeline that extracts, enriches, and stores Marvel Cinematic Universe movie data for analytics.

The project demonstrates an end-to-end data engineering workflow:

- Scraping semi-structured HTML data from Wikipedia  
- Cleaning and normalizing complex tables  
- Enriching data using the OMDb REST API  
- Modeling dimensional tables  
- Exporting structured datasets to Amazon S3 in Parquet format  

The pipeline runs locally during development and stores analytics-ready data in AWS S3.
