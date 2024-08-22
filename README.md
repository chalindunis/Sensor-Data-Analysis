# Sensor-Data-Analysis
Description: This project aims to build a system to collect, process, and analyze
data from IoT sensors in real-time.

Problem: IoT devices generate vast amounts of data that need to be processed
and analyzed in real-time for actionable insights, such as detecting anomalies or
predicting failures.
Possible Architecture:

● Data Ingestion: MQTT / Kafka
● Processing: Spark
● Storage: Hadoop
● Visualization: ELK

Possible Steps:
1. Set up MQTT brokers to collect data from IoT sensors.
2. Use Spark Streaming to process the incoming data and perform real-time
analysis, such as anomaly detection.
3. Store the processed data in Hadoop for long-term storage and batch
processing.
4. Visualize the data in Kibana to monitor sensor data trends and detect
anomalies.