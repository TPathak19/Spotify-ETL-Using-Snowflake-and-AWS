# Spotify-ETL-Using-Snowflake-and-AWS

## Objective:

The goal was to seamlessly connect with the Spotify API for extracting and analyzing music data. Utilizing Python, Amazon Web Services (AWS), and Snowflake, I constructed a comprehensive end-to-end data pipeline. This pipeline was designed to efficiently process, transform, and visualize Spotify's extensive music data, aiming to derive valuable insights from their vast catalog and automate the entire data handling process.

## Architecture:![Spotify ETL](https://github.com/TPathak19/Spotify-ETL-Using-Snowflake-and-AWS/assets/79747784/c1e14818-7c2c-442c-af8c-7f7d2c3e12e2)

 
## Project Components:

#### Data Extraction: Utilizing Python code, assisted by the Spotipy library, music data was directly fetched from Spotify and subsequently stored in AWS S3.

#### Automated Data Transformation: AWS Lambda functions were designed to efficiently convert JSON data into structured tables, covering songs, albums, and artists.

#### AWS Lambda Functions: These serverless functions automated the entire data processing pipeline whenever new data became available.

#### Amazon S3 & Snowflake Integration: Transformed data was stored in AWS S3 and seamlessly loaded into Snowflake, creating analytics-ready tables.


