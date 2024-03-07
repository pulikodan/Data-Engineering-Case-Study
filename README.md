# Data Engineering Framework
This data engineering framework supports various process involved in the data engineering process. It follows microservice architecture and designed keeping scalability and throughput into consideartion.
There are four main services associated with this framework, that are 

  1)Data Ingejction
  
  2)Data preprocessing
  
  3)Data Storage
  
  4)Error handingling and moitoring


![plot](./img/arch.png)

## Data Ingejction

    Implement a scalable data ingestion system capable of collecting and processing ad impressions (JSON), clicks/conversions (CSV), and bid requests (Avro) data.
    Ensure that the ingestion system can handle high data volumes generated in real-time and batch modes.

## Data preprocessing

    Develop data transformation processes to standardize and enrich the data. Handle data validation, filtering, and deduplication.
    Implement logic to correlate ad impressions with clicks and conversions to provide meaningful insights.

## Data Storage

    Select an appropriate data storage solution for storing processed data efficiently, enabling fast querying for campaign performance analysis.
    Optimize the storage system for analytical queries and aggregations of ad campaign data.

## Error handingling and moitoring

    Create an error handling and monitoring system to detect data anomalies, discrepancies, or delays.
    Implement alerting mechanisms to address data quality issues in real-time, ensuring that discrepancies are resolved promptly to maintain ad campaign effectiveness.
