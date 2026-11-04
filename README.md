This is the original Shoplink Data Platform README.
## Sources
Below is a summary of ShopLink's core data sources and their ingestion methods:
| Source System | Data Type | Ingestion Type | Update Frequency | 
|**PostgresSQL Production DB** | Relational / Transactional | Batch (CDC / Debezium) | Real-time / Daily |
| **Clickstream Service** | Event Logs / User Behavior | Streaming (Kafka / Kinesis) | Continuous |
| **Third-Party Logistics API**| JSON / Supply Chain Metrics| Batch (API Polling) | Hourly |
| **Inventory Sheets** | CSV / Static Reference Data| Batch (File Upload) | Daily |
