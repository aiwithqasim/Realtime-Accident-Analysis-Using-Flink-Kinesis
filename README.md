# Realtime-Accident-Analysis-Using-Flink-Kinesis

**Business Overview**

Perishable data is information whose value can significantly decline over a period of time. When the operating conditions change to the point that the knowledge is no longer helpful, the information loses a large amount of its value. This information is frequently produced in an IoT computing context. Managing perishable data provides a number of benefits. Real-time data provides you with the information you need almost instantly and in the context which helps make smarter business decisions. The use of data from edge computing devices speeds up reaction time and minimizes time to action. Such data does not need to be kept in data centers for a long time and maybe deleted after usage, saving storage space and money. Systems are usually designed on constant patterns and can’t scale with peaks in the load resulting in latency and server failures.

This Project will simulate real-time accident data and architect a pipeline that will help us analyze and take quick actions using AWS Kinesis, Apache Flink, Grafana, and Amazon SNS.

**Data Pipeline**

A data pipeline is a technique for transferring data from one system to another. The data may or may not be updated, and it may be handled in real-time (or streaming) rather than in batches. The data pipeline encompasses everything from harvesting or acquiring data using various methods to storing raw data, cleaning, validating, and transforming data into a query-worthy format, displaying KPIs, and managing the above process.

**Dataset Description**

This Project uses the US car accidents dataset which includes a few of the following fields:

- Severity
- Start_Time
- End_Time
- Location
- Description
- City
- State

**Tech Stack:**

➔ Languages - SQL, Python3

➔ Services - AWS S3, AWS Glue, AWS Athena, AWS Cloud9, Apache Flink, Amazon Kinesis, Amazon SNS, AWS Lambda, Amazon CloudWatch, Grafana, Apache Zepplin

**Architecture Diagram**

![Architecture Diagram](https://github.com/aiwithqasim/Realtime-Accident-Analysis-Using-Flink-Kinesis/blob/main/README.md)
