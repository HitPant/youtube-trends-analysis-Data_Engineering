# youtube-trends-analysis-Data_Engineering

## Aim
The focus is on extracting trends and insights from YouTube data. 
By leveraging Amazon Web Services, it aims to uncover patterns in viewer behavior, content performance, and channel growth.


## Key Components & Services
### Data Ingestion
- Collected data from different sources ingested into an S3 bucket.
### ETL System
- Transformed raw (JSON and CSV) data into a usable format using AWS Glue.
### Data Lake
- Stored large volumes of data in a centralized repository using Amazon S3.
### Cloud Infrastructure
- Efficiently managed and processed data using AWS services such as AWS Lambda, S3, AWS Glue, and Athena.
### Access Management and Data Security
- Utilized AWS Identity and Access Management (IAM) and data encryption to ensure data/service security.
### Reporting
- Provided insights through an interactive dashboard using Amazon QuickSight.

## Dashboard
QuickSight: https://us-east-1.quicksight.aws.amazon.com/sn/dashboards/f5005cbd-83d2-4757-bcdb-980deaa5d0b8/views/bac4b0a9-cea6-4fd8-8da8-05fa53e854fb?directory_alias=yt-analytics-dashboard
![alt-text](https://github.com/HitPant/youtube-trends-analysis-Data_Engineering/blob/main/images/Screenshot%202024-05-29%20235848.png)

## Architecture Diagram
![alt-text](https://github.com/HitPant/youtube-trends-analysis-Data_Engineering/blob/main/images/architecture_diagram-yt_analytics.jpg)
