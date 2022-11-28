# Cloud Migration Reference 

## Hadoop Migration 

 | % | Source  | Target | Target Platform |
 |  ----------- | -----------  | -----------  | -----------  | 
 | 1 | [- HBase](https://hbase.apache.org) 		| [- HBase on S3/EMRFS](https://d1.awsstatic.com/whitepapers/Migrating_to_Apache_Hbase_on_Amazon_S3_on_Amazon_EMR.pdf) | AWS |
 | 2 | [- HBase](https://hbase.apache.org) 		| [- HBase on HDInsight](https://docs.microsoft.com/en-us/azure/data-factory/connector-hbase?tabs=data-factory) | Azure |
 | 3 | [- HBase](https://hbase.apache.org) 		| [- CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db/sql/migrate-hbase-to-cosmos-db) | Azure |
 | 4 | [- HBase](https://hbase.apache.org) 		| [- Bigtable](https://cloud.google.com/architecture/hadoop/hadoop-gcp-migration-data-hbase-to-bigtable) | GCP |
 | 5 | [- Hadoop ORC](https://orc.apache.org) 	| [- Delta on Azure](https://docs.microsoft.com/en-us/azure/data-factory/format-delta) | Azure |
 | 6 | [- Hadoop ORC](https://orc.apache.org) 	| [- Delta on Dataproc](https://medium.com/analytics-vidhya/using-google-dataproc-to-create-delta-tables-c6dffa263fee) | GCP |
 
 ## ETL Migration
 
  | % | Source  | AWS | Databricks | Azure | GCP |
 |  ----------- | -----------  | -----------  | -----------  | -----------  | -----------  | 
 | 1 | [- Abinitio](https://www.abinitio.com) </br> [- Components](http://abinitio-components.blogspot.com) </br> [- Graph Design](http://abinitio-graph.blogspot.com)| [- Glue ETL](https://aws.amazon.com/glue/features/) </br> [- Glue Brew vs Glue](https://cloudacademy.com/course/management-saa-c03/aws-glue-databrew-vs-glue-studio/) </br> |  |  |
 
 ## EDW Migration
 
  | % | Source  | AWS | Databricks | Azure | GCP |
 |  ----------- | -----------  | -----------  | -----------  | -----------  | -----------  | 
 | 1 |  | [] | [] | [- Azure Data Loading Strategy](https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/design-elt-data-loading) </br> [- Data migration using ADF and Synapse Pipeline](https://learn.microsoft.com/en-us/azure/data-factory/load-azure-sql-data-warehouse?toc=%2Fazure%2Fsynapse-analytics%2Fsql-data-warehouse%2Ftoc.json&tabs=data-factory) |
 
