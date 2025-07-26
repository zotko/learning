| Use case              | On-premises, Databricks                  | AWS                                      | Azure                                    | Google Cloud Platform                    |
|-----------------------|------------------------------------------|------------------------------------------|------------------------------------------|------------------------------------------|
| Workflows             | Airflow, Databricks Workflows            | Glue, MWAA, Step Functions               | Data Factory                             | Cloud Composer                           |
| Streaming ingest      | Apache Kafka                             | Kinesis, MSK                             | Event Hubs                               | Pub/Sub                                  |
| Streaming computation | Flink, Spark Streaming                   | Flink on Kinesis Analytics, Spark on EMR | Stream Analytics, Spark on Databricks    | Dataflow                                 |
| SQL                   | Trino, Hive                              | Athena, Redshift                         | Synapse                                  | BigQuery                                 |
| NoSQL                 | MongoDB, Cassandra                       | DynamoDB                                 | Cosmos DB                                | Bigtable, Firestore                      |
| Filesystem            | MinIO, Delta Lake                        | S3, Lake Formation                       | ADLS Gen2                                | GCS, Dataplex                            |
| Security              | Kerberos, Ranger                         | IAM, Lake Formation                      | RBAC, Purview                            | Cloud IAM, Dataplex                      |
| Batch computation     | Spark                                    | EMR                                      | Databricks, Synapse Spark                | Dataproc                                 
