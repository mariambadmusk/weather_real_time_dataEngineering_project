## Weather Data Pipeline for New Delhi, India

This repository contains the code and configuration for a data pipeline designed to fetch, process, and store weather data for London, United Kingdom. The pipeline prioritises both public safety and efficient API usage.

**Key Features:**

* **Data Source:** Fetches weather data for London through an external API (details to be specified in configuration).
* **Daily Weather Updates:** Sends weather updates to subscribers every three hours for a total of 8 updates in 24 hours. 
* **Safety Weather Updates:** 

* **API Usage:** Operates within a limit of 250 requests per month, ensuring optimal usage while providing timely updates.

**Project Objectives:**

* **Public Safety:** Deliver accurate and timely weather warnings to protect citizens from adverse weather conditions.
* **Emergency Services Coordination:** Provide weather data to enhance emergency response efforts.
* **Public Awareness:** Offer regular weather updates to help the public make informed decisions.
* **Operational Efficiency:** Optimize API request usage to stay within the monthly limit while ensuring comprehensive coverage.
* **Data Quality:** Maintain clean, accurate, and readily available weather data for analysis and dissemination.

**Technology Stack:**
    - Programming Language: Python 3.8+
    - Data Lake: Amazon S3
    - Data Orchestration: AWS Lambda
    - Data Warehouse: Amazon DynamoDB
    - Alerting: Amazon SNS (Simple Notification Service)
    - Monitoring and Logging: Amazon CloudWatch
    - Access and Permissions: IAM (Identity and Access Management)
    - API: WeatherStack API  - weatherstack.com

**Challenges:**
    - API 
        - Using https://weatherstack.com/ free tier provides 250 API requests
        - The free tier option offers only offer real-time weather updates but not historical data and hourly data and forecast data
        - Using the conventional weather updates to every 3 hours aggregates about 240 API requests in a month

        - Option for the full content of news not available in the free tier
    - Data Quality 
        - Request did not limit news sources to certain websites or news sites. It is open ended.

**Getting Started (details to be added later):**

1. Install dependencies (instructions to be added).
2. Configure the pipeline (details on configuration file to be added).
3. Run the pipeline (instructions to be added).

**Further Information:**

* This document will be updated with detailed instructions on setup, configuration, and execution. 
* Specific details about the weather stack API and its limitations will be added.


https://www.statista.com/statistics/275359/largest-cities-in-the-united-kingdom/