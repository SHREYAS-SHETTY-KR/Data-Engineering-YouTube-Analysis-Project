# Data-Engineering-YouTube-Analysis-Project

## Project Overview

Our project aims to securely manage, streamline, and analyze structured and semi-structured YouTube video data from three countries: the USA, Great Britain, and Canada. The primary focus is on video categories and trending metrics.

## Key Research Questions
Our project addresses three main research questions:

1. **Country Comparison**

   Which of the three countries (USA, Great Britain, or Canada) had the highest number of views across all videos?

3. **Category Analysis**
  
   Which video categories garnered the most views overall?

3. **Regional Differences**

   How do views vary across video categories in each of the three regions (USA, Great Britain, Canada)?
   
By answering these questions, our project provides valuable insights into viewership trends across different countries and video categories on YouTube. This analysis helps us understand the popularity and preferences of viewers in these regions.

## Project Goals

1. **Data Ingestion:** Develop a robust mechanism to ingest data from various sources.

2. **ETL System:** Implement an ETL (Extract, Transform, Load) system to process raw data into the required format.

3. **Data Lake:** Create a centralized repository (data lake) to store data from multiple sources efficiently.

4. **Scalability:** Ensure the system is scalable to handle increasing data volumes effectively.

5. **Cloud Integration:** Utilize cloud services, specifically AWS (Amazon Web Services), to process and manage large datasets.

6. **Reporting:** Design and build a user-friendly dashboard to extract meaningful insights and answers to predefined questions from the processed data.

These project goals collectively aim to establish a data pipeline that can efficiently handle, process, and analyze large datasets from diverse sources while ensuring scalability and ease of reporting through cloud-based infrastructure.


## Services Used

1. **Amazon S3 (Simple Storage Service):** Amazon S3 is an object storage service known for its manufacturing scalability, data availability, security, and performance.

2. **AWS IAM (Identity and Access Management):** AWS IAM is a critical component for managing access to AWS services and resources securely, ensuring proper authentication and authorization.

3. **Amazon QuickSight:** Amazon QuickSight is a scalable, serverless, machine learning-powered business intelligence (BI) service designed for the cloud. It facilitates data visualization and reporting.

4. **AWS Glue:** AWS Glue is a serverless data integration service that simplifies the process of discovering, preparing, and combining data for various purposes, including analytics, machine learning, and application development.

5. **AWS Lambda:** AWS Lambda is a serverless computing service that enables developers to run code without the need to manage servers. It's used for executing code in response to specific events.

6. **AWS Athena:** AWS Athena is an interactive query service designed for data stored in Amazon S3. It allows users to query data without the need to load it into a separate database; the data remains in S3, making it an efficient choice for querying large datasets.

These services are integral to our project and will collectively support our data processing, storage, analysis, and reporting needs in an efficient and scalable manner.

## Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture Diagram
![Image Alt Text](architecture.jpeg)

