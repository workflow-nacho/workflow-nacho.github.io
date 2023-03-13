# flowfunctions

The `flowfunctions` library enables and empowers development, management and monitoring of complex and extensible data workflows within the native Google BigQuery environment.

## Motivation
Google BigQuery is an amazing foundational technology. The serverless nature, infinite scalability and large but expanding array of features make it a powerful platform for any kind of data work, for any scale or type of organisation or team. 

However due to some fundamental practical and syntactical idiosyncrasies and contraints, it can be difficult to achieve complex tasks in a clear, readable, reusable and therefore scalable manner.

This library aims to provide a clean, unified, functional abstraction based on elements of the core BigQuery language sets ([SQL](https://cloud.google.com/bigquery/docs/reference/standard-sql/introduction), [DDL](https://cloud.google.com/bigquery/docs/reference/standard-sql/data-definition-language), [DML](https://cloud.google.com/bigquery/docs/reference/standard-sql/dml-syntax), [DCL](https://cloud.google.com/bigquery/docs/reference/standard-sql/data-control-language), [Procedural Language](https://cloud.google.com/bigquery/docs/reference/standard-sql/procedural-language), [Debugging](https://cloud.google.com/bigquery/docs/reference/standard-sql/debugging-statements) and [Other Statements](https://cloud.google.com/bigquery/docs/reference/standard-sql/other-statements)) to enable developers to write and reuse powerful, scalable, extensible and maintainable code, to achieve any data objective without requiring integration or usage of external tools.