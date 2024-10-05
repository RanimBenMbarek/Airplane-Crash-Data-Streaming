# Airplane Crash Data Streaming Analysis

This repository presents a streaming pipeline for analyzing and visualizing airplane crash data in real-time. Leveraging technologies like Apache Kafka for data ingestion and processing, this project aims to provide insights into airplane crashes as they happen.

## About the Dataset

The **Airplane Crashes and Fatalities Since 1908** dataset provides a historical account of airplane crashes worldwide from 1908 to 2009. It includes vital information such as the year of the crash, the number of people on board, survivors, fatalities, and a summary of the circumstances surrounding the crash. This dataset is crucial for real-time analytics and understanding trends in airplane safety.

## Dataset Link
You can download the dataset from Kaggle:
- [Airplane Crash Data on Kaggle](https://www.kaggle.com/datasets/saurograndi/airplane-crashes-since-1908/data?fbclid=IwY2xjawFuBw5leHRuA2FlbQIxMAABHT-1JuJhduEwm-uBDjrOdXKmRGHEN1m9ny4CNriPmyB_0aXjVbv6cQ6PvQ_aem_4nKJwPKDKvEQoti0J03J-g)

## Project Overview

1. **Data Ingestion**:
   - Utilize Apache Kafka to stream data from the CSV dataset, enabling real-time processing.

2. **Data Processing**:
   - Process incoming data streams to extract meaningful insights and update aggregates in real-time.

3. **Data Storage**:
   - Store processed data in a suitable database (e.g., HBase or NoSQL) for efficient querying and analysis.

4. **Data Analysis**:
   - Analyze crash data in real-time to answer key questions, such as:
     - Current trends in plane crashes.
     - Frequency of accidents by flight type in real-time.
     - Total fatalities by country.

5. **Data Visualization**:
   - Visualize insights through real-time dashboards and graphs, illustrating trends and patterns in airplane crashes.

## Architecture

![image](https://github.com/user-attachments/assets/d262070e-ff51-44fc-8da9-8eb3c816a299)

## Sample Visualizations

Here are some sample visualizations produced from the streaming analysis:

1. **Live Fatalities**:
   ![image](https://github.com/user-attachments/assets/eb021138-0631-46e1-926f-e66e77afe5fb)

