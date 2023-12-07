# Youtube-Data-Analysis-Project-AWS-
The objective of this initiative is to securely oversee, optimize, and conduct analyses on both structured and semi-structured data from YouTube videos. This involves categorizing videos and assessing trending metrics for enhanced insights.

# Project Objectives

* Data Acquisition — Develop a system for gathering information from diverse origins
* Transformation Pipeline — Given raw data, our focus is on converting it into the correct structure
* Centralized Repository — With data streaming in from various places, establishing a central storage is imperative
* Expansion Capability — With the growing data volume, it's vital for our system to seamlessly expand
* Cloud Computing — Due to the impracticality of handling extensive data locally, opting for cloud solutions is crucial; in this instance, AWS is our choice
* Analytical Outputs — Construct a visual interface for obtaining responses to our earlier inquiries

# The array of services employed:

* Amazon S3: This service offers scalable object storage, ensuring manufacturing scalability, data availability, security, and optimal performance.
* AWS IAM: A system solely dedicated to identity and access management, empowering secure access control over AWS services and resources.
* QuickSight: Amazon QuickSight stands as a scalable, serverless, machine learning-infused business intelligence (BI) service tailored for cloud environments.
* AWS Glue: As a serverless data integration service, AWS Glue simplifies data discovery, preparation, and fusion for analytics, machine learning, and app development purposes.
* AWS Lambda: Lambda represents a computing service enabling code execution sans server management, ideal for programmers.
* AWS Athena: Athena stands out as an interactive S3 query service, eliminating the necessity to load data separately as it resides within S3.

# Utilized Dataset

The dataset sourced from Kaggle encompasses daily statistics (in CSV format) for popular YouTube videos spanning several months. Daily, there are records for up to 200 trending videos across various locations, with dedicated files for each region. The dataset captures information such as video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count. Additionally, the JSON file linked to each region incorporates a category_id field, which varies based on the area.

Link to the dataset: https://www.kaggle.com/datasets/datasnaek/youtube-new

# Architecture Diagram 

![architecture](https://github.com/snehalsmalladi/Youtube-Data-Analysis-Project-AWS-/assets/75508260/e410e889-2e3b-44a9-bd78-b287564346ae)
