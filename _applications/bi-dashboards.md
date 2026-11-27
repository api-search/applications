---
access: understanding
agent_layer: []
apps:
- anchor: metabase
  counts:
    declared: 0
    observed: 19
  evidence:
  - route: source code
    url: https://github.com/metabase/metabase/tree/master/modules/drivers
  - route: source code
    url: https://github.com/metabase/metabase/tree/master/src/metabase/channel/impl
  - route: source code
    url: https://github.com/metabase/metabase/tree/master/src/metabase/driver
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Athena
    provider: amazon-athena
    says: ships the Amazon Athena SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Redshift
    provider: amazon-redshift
    says: ships the Amazon Redshift SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Druid
    provider: apache-druid
    says: ships the Apache Druid SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Hive
    provider: apache-hive
    says: ships the Apache Hive SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Spark SQL
    provider: apache-spark
    says: ships the Apache Spark SQL SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickHouse
    provider: clickhouse
    says: ships the ClickHouse SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Databricks
    provider: databricks
    says: ships the Databricks SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google BigQuery
    provider: google-bigquery
    says: ships the Google BigQuery SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft SQL Server
    provider: microsoft-sql-server
    says: ships the Microsoft SQL Server SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MongoDB
    provider: mongodb
    says: ships the MongoDB SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: MotherDuck
    provider: motherduck
    says: ships the MotherDuck SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MySQL
    provider: mysql
    says: ships the MySQL SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/src/metabase/driver
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Oracle Database
    provider: oracle
    says: ships the Oracle Database SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: PostgreSQL
    provider: postgresql
    says: ships the PostgreSQL SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/src/metabase/driver
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Presto (PrestoDB)
    provider: presto-foundation
    says: ships the Presto (PrestoDB) SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/src/metabase/channel/impl
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snowflake
    provider: snowflake
    says: ships the Snowflake SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Starburst
    provider: starburst
    says: ships the Starburst SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Vertica
    provider: vertica
    says: ships the Vertica SDK or integration code
    source: https://github.com/metabase/metabase/tree/master/modules/drivers
    tier: observed
  kind: self-hosted
  name: Metabase
  page: /applications/bi-dashboards/metabase/
  slug: metabase
  url: https://github.com/metabase/metabase
- anchor: apache-superset
  counts:
    declared: 0
    observed: 60
  evidence:
  - route: source code
    url: https://github.com/apache/superset/tree/master/superset/db_engine_specs
  - route: source code
    url: https://github.com/apache/superset/tree/master/superset/reports/notifications
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Alibaba Cloud (Hologres / MaxCompute)
    provider: alibaba
    says: ships the Alibaba Cloud (Hologres / MaxCompute) SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Athena
    provider: amazon-athena
    says: ships the Amazon Athena SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon Aurora
    provider: amazon-aurora
    says: ships the Amazon Aurora SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon DynamoDB
    provider: amazon-dynamodb
    says: ships the Amazon DynamoDB SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Redshift
    provider: amazon-redshift
    says: ships the Amazon Redshift SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Doris
    provider: apache-doris
    says: ships the Apache Doris SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Drill
    provider: apache-drill
    says: ships the Apache Drill SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Druid
    provider: apache-druid
    says: ships the Apache Druid SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Hive
    provider: apache-hive
    says: ships the Apache Hive SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Impala
    provider: apache-impala
    says: ships the Apache Impala SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Apache IoTDB
    provider: apache-iotdb
    says: ships the Apache IoTDB SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Kylin
    provider: apache-kylin
    says: ships the Apache Kylin SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Pinot
    provider: apache-pinot
    says: ships the Apache Pinot SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Apache Solr
    provider: apache-solr
    says: ships the Apache Solr SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Spark SQL
    provider: apache-spark
    says: ships the Apache Spark SQL SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure Data Explorer (Kusto)
    provider: azure-data-explorer
    says: ships the Azure Data Explorer (Kusto) SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickHouse
    provider: clickhouse
    says: ships the ClickHouse SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Cloudflare D1
    provider: cloudflare-d1
    says: ships the Cloudflare D1 SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: CockroachDB
    provider: cockroach-labs
    says: ships the CockroachDB SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Couchbase
    provider: couchbase
    says: ships the Couchbase SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: CrateDB
    provider: crate-io
    says: ships the CrateDB SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Databend
    provider: databend
    says: ships the Databend SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Databricks
    provider: databricks
    says: ships the Databricks SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-939
      key: AE-939
      name: Data Virtualization & Federation
      url: /capabilities/data-virtualization-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Denodo
    provider: denodo
    says: ships the Denodo SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Dremio
    provider: dremio
    says: ships the Dremio SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: DuckDB
    provider: duckdb
    says: ships the DuckDB SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Elasticsearch
    provider: elastic
    says: ships the Elasticsearch SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Exasol
    provider: exasol
    says: ships the Exasol SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Firebolt
    provider: firebolt
    says: ships the Firebolt SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google BigQuery
    provider: google-bigquery
    says: ships the Google BigQuery SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Cloud Datastore
    provider: google-cloud-datastore
    says: ships the Google Cloud Datastore SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Sheets
    provider: google-sheets
    says: ships the Google Sheets SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Greenplum
    provider: greenplum
    says: ships the Greenplum SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: IBM Db2
    provider: ibm-db2
    says: ships the IBM Db2 SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: IBM Netezza
    provider: netezza
    says: ships the IBM Netezza SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MariaDB
    provider: mariadb
    says: ships the MariaDB SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft SQL Server
    provider: microsoft-sql-server
    says: ships the Microsoft SQL Server SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: MonetDB
    provider: monetdb
    says: ships the MonetDB SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MongoDB
    provider: mongodb
    says: ships the MongoDB SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MySQL
    provider: mysql
    says: ships the MySQL SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: OceanBase
    provider: oceanbase
    says: ships the OceanBase SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ocient
    provider: ocient
    says: ships the Ocient SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Oracle Database
    provider: oracle
    says: ships the Oracle Database SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Parseable
    provider: parseable
    says: ships the Parseable SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: PostgreSQL
    provider: postgresql
    says: ships the PostgreSQL SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Presto (PrestoDB)
    provider: presto-foundation
    says: ships the Presto (PrestoDB) SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: RisingWave
    provider: risingwave
    says: ships the RisingWave SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: SAP HANA
    provider: sap-hana
    says: ships the SAP HANA SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: SingleStore
    provider: singlestore
    says: ships the SingleStore SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/reports/notifications
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snowflake
    provider: snowflake
    says: ships the Snowflake SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: StarRocks
    provider: starrocks
    says: ships the StarRocks SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Sybase (SAP ASE)
    provider: sybase
    says: ships the Sybase (SAP ASE) SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: TDengine
    provider: tdengine
    says: ships the TDengine SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Teradata
    provider: teradata
    says: ships the Teradata SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: TimescaleDB
    provider: timescale
    says: ships the TimescaleDB SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Trino
    provider: trino
    says: ships the Trino SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Vertica
    provider: vertica
    says: ships the Vertica SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: YDB
    provider: ydb
    says: ships the YDB SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: YugabyteDB
    provider: yugabyte
    says: ships the YugabyteDB SDK or integration code
    source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
    tier: observed
  kind: self-hosted
  name: Apache Superset
  page: /applications/bi-dashboards/apache-superset/
  slug: apache-superset
  url: https://github.com/apache/superset
- anchor: redash
  counts:
    declared: 0
    observed: 62
  evidence:
  - route: source code
    url: https://github.com/getredash/redash/tree/master/redash/destinations
  - route: source code
    url: https://github.com/getredash/redash/tree/master/redash/query_runner
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Athena
    provider: amazon-athena
    says: ships the Amazon Athena SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon CloudWatch
    provider: amazon-cloudwatch
    says: ships the Amazon CloudWatch SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Amazon OpenSearch Service
    provider: amazon-opensearch
    says: ships the Amazon OpenSearch Service SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Apache Cassandra
    provider: cassandra
    says: ships the Apache Cassandra SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Drill
    provider: apache-drill
    says: ships the Apache Drill SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Druid
    provider: apache-druid
    says: ships the Apache Druid SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Hive
    provider: apache-hive
    says: ships the Apache Hive SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Apache Ignite
    provider: apache-ignite
    says: ships the Apache Ignite SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Impala
    provider: apache-impala
    says: ships the Apache Impala SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Kylin
    provider: apache-kylin
    says: ships the Apache Kylin SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Phoenix
    provider: apache-phoenix
    says: ships the Apache Phoenix SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Pinot
    provider: apache-pinot
    says: ships the Apache Pinot SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: ArangoDB
    provider: arangodb
    says: ships the ArangoDB SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: ships the Asana SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/destinations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure Data Explorer (Kusto)
    provider: azure-data-explorer
    says: ships the Azure Data Explorer (Kusto) SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Chatwork
    provider: chatwork
    says: ships the Chatwork SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/destinations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickHouse
    provider: clickhouse
    says: ships the ClickHouse SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Cloudflare D1
    provider: cloudflare-d1
    says: ships the Cloudflare D1 SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Couchbase
    provider: couchbase
    says: ships the Couchbase SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Databend
    provider: databend
    says: ships the Databend SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Databricks
    provider: databricks
    says: ships the Databricks SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Datadog
    provider: datadog
    says: ships the Datadog SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/destinations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Dgraph
    provider: dgraph
    says: ships the Dgraph SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/destinations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: DuckDB
    provider: duckdb
    says: ships the DuckDB SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: e6data
    provider: e6data
    says: ships the e6data SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Elasticsearch
    provider: elastic
    says: ships the Elasticsearch SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Exasol
    provider: exasol
    says: ships the Exasol SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Google Analytics 4
    provider: google-analytics
    says: ships the Google Analytics 4 SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google BigQuery
    provider: google-bigquery
    says: ships the Google BigQuery SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Chat
    provider: google-chat
    says: ships the Google Chat SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/destinations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Cloud Spanner
    provider: google-cloud-spanner
    says: ships the Google Cloud Spanner SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Google Search Console
    provider: google-search-console
    says: ships the Google Search Console SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Sheets
    provider: google-sheets
    says: ships the Google Sheets SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Graphite
    provider: graphite-com
    says: ships the Graphite SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: IBM Db2
    provider: ibm-db2
    says: ships the IBM Db2 SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: IBM Netezza
    provider: netezza
    says: ships the IBM Netezza SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: InfluxDB
    provider: influxdb
    says: ships the InfluxDB SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira (JQL)
    provider: jira
    says: ships the Jira (JQL) SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Mattermost
    provider: mattermost
    says: ships the Mattermost SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/destinations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft SQL Server
    provider: microsoft-sql-server
    says: ships the Microsoft SQL Server SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: ships the Microsoft Teams SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/destinations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MongoDB
    provider: mongodb
    says: ships the MongoDB SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MySQL
    provider: mysql
    says: ships the MySQL SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Oracle Database
    provider: oracle
    says: ships the Oracle Database SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: common
    name: PagerDuty
    provider: pagerduty
    says: ships the PagerDuty SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/destinations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: PostgreSQL
    provider: postgresql
    says: ships the PostgreSQL SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Presto (PrestoDB)
    provider: presto-foundation
    says: ships the Presto (PrestoDB) SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Prometheus
    provider: prometheus-io
    says: ships the Prometheus SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: RisingWave
    provider: risingwave
    says: ships the RisingWave SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: ships the Salesforce SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: SingleStore
    provider: singlestore
    says: ships the SingleStore SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/destinations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snowflake
    provider: snowflake
    says: ships the Snowflake SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Tinybird
    provider: tinybird
    says: ships the Tinybird SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Treasure Data
    provider: treasure-data
    says: ships the Treasure Data SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Trino
    provider: trino
    says: ships the Trino SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Uptycs
    provider: uptycs
    says: ships the Uptycs SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Vertica
    provider: vertica
    says: ships the Vertica SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Webex
    provider: webex
    says: ships the Webex SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/destinations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Yandex Disk
    provider: yandex-disk
    says: ships the Yandex Disk SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Yandex Metrica
    provider: yandex-metrica
    says: ships the Yandex Metrica SDK or integration code
    source: https://github.com/getredash/redash/tree/master/redash/query_runner
    tier: observed
  kind: self-hosted
  name: Redash
  page: /applications/bi-dashboards/redash/
  slug: redash
  url: https://github.com/getredash/redash
- anchor: grafana
  counts:
    declared: 0
    observed: 32
  evidence:
  - route: documentation
    url: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
  - route: source code
    url: https://github.com/grafana/alerting/tree/main/receivers
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Amazon CloudWatch
    provider: amazon-cloudwatch
    says: ships the Amazon CloudWatch SDK or integration code
    source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Amazon SNS
    provider: amazon-sns
    says: ships the Amazon SNS SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: Apache Kafka
    provider: apache-kafka
    says: ships the Apache Kafka SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Azure Monitor
    provider: azure-monitor
    says: ships the Azure Monitor SDK or integration code
    source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: DingTalk
    provider: dingtalk
    says: ships the DingTalk SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Elasticsearch
    provider: elastic
    says: ships the Elasticsearch SDK or integration code
    source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Chat
    provider: google-chat
    says: ships the Google Chat SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Cloud Monitoring
    provider: google-cloud-monitoring
    says: ships the Google Cloud Monitoring SDK or integration code
    source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Graphite
    provider: graphite-com
    says: ships the Graphite SDK or integration code
    source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: InfluxDB
    provider: influxdb
    says: ships the InfluxDB SDK or integration code
    source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Jaeger
    provider: jaeger
    says: ships the Jaeger SDK or integration code
    source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira (JQL)
    provider: jira
    says: ships the Jira (JQL) SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: LINE
    provider: line
    says: ships the LINE SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft SQL Server
    provider: microsoft-sql-server
    says: ships the Microsoft SQL Server SDK or integration code
    source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: ships the Microsoft Teams SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MySQL
    provider: mysql
    says: ships the MySQL SDK or integration code
    source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: OpenTSDB
    provider: opentsdb
    says: ships the OpenTSDB SDK or integration code
    source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: common
    name: Opsgenie
    provider: opsgenie
    says: ships the Opsgenie SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: common
    name: PagerDuty
    provider: pagerduty
    says: ships the PagerDuty SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Parca
    provider: parca
    says: ships the Parca SDK or integration code
    source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: PostgreSQL
    provider: postgresql
    says: ships the PostgreSQL SDK or integration code
    source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Prometheus
    provider: prometheus-io
    says: ships the Prometheus SDK or integration code
    source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Pushover
    provider: pushover
    says: ships the Pushover SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Sensu
    provider: sensu
    says: ships the Sensu SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: common
    name: Splunk On-Call (VictorOps)
    provider: victorops
    says: ships the Splunk On-Call (VictorOps) SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Threema
    provider: threema
    says: ships the Threema SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Webex
    provider: webex
    says: ships the Webex SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: WeCom
    provider: wecom
    says: ships the WeCom SDK or integration code
    source: https://github.com/grafana/alerting/tree/main/receivers
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Zipkin
    provider: zipkin
    says: ships the Zipkin SDK or integration code
    source: https://github.com/grafana/grafana/tree/main/docs/sources/datasources
    tier: observed
  kind: self-hosted
  name: Grafana
  page: /applications/bi-dashboards/grafana/
  slug: grafana
  url: https://github.com/grafana/grafana
- anchor: lightdash
  counts:
    declared: 1
    observed: 10
  evidence:
  - route: documentation
    url: https://github.com/lightdash/lightdash/blob/main/README.md
  - route: source code
    url: https://github.com/lightdash/lightdash/tree/main/packages/warehouses/src/warehouseClients
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Athena
    provider: amazon-athena
    says: ships the Amazon Athena SDK or integration code
    source: https://github.com/lightdash/lightdash/tree/main/packages/warehouses/src/warehouseClients
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Redshift
    provider: amazon-redshift
    says: ships the Amazon Redshift SDK or integration code
    source: https://github.com/lightdash/lightdash/tree/main/packages/warehouses/src/warehouseClients
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickHouse
    provider: clickhouse
    says: ships the ClickHouse SDK or integration code
    source: https://github.com/lightdash/lightdash/tree/main/packages/warehouses/src/warehouseClients
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Databricks
    provider: databricks
    says: ships the Databricks SDK or integration code
    source: https://github.com/lightdash/lightdash/tree/main/packages/warehouses/src/warehouseClients
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: DuckDB
    provider: duckdb
    says: ships the DuckDB SDK or integration code
    source: https://github.com/lightdash/lightdash/tree/main/packages/warehouses/src/warehouseClients
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google BigQuery
    provider: google-bigquery
    says: ships the Google BigQuery SDK or integration code
    source: https://github.com/lightdash/lightdash/tree/main/packages/warehouses/src/warehouseClients
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: MotherDuck
    provider: motherduck
    says: ships the MotherDuck SDK or integration code
    source: https://github.com/lightdash/lightdash/tree/main/packages/warehouses/src/warehouseClients
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: PostgreSQL
    provider: postgresql
    says: ships the PostgreSQL SDK or integration code
    source: https://github.com/lightdash/lightdash/tree/main/packages/warehouses/src/warehouseClients
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snowflake
    provider: snowflake
    says: ships the Snowflake SDK or integration code
    source: https://github.com/lightdash/lightdash/tree/main/packages/warehouses/src/warehouseClients
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Trino
    provider: trino
    says: ships the Trino SDK or integration code
    source: https://github.com/lightdash/lightdash/tree/main/packages/warehouses/src/warehouseClients
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-938
      key: AE-938
      name: Semantic & Metrics Layer
      url: /capabilities/analytics-bi-management/
      via_parent: Analytics & BI Management
    credit: null
    layer: domain
    name: dbt
    provider: dbt
    says: lists dbt as an integration
    source: https://github.com/lightdash/lightdash/blob/main/README.md
    tier: declared
  kind: self-hosted
  name: Lightdash
  page: /applications/bi-dashboards/lightdash/
  slug: lightdash
  url: https://github.com/lightdash/lightdash
- anchor: microsoft-power-bi
  counts:
    declared: 57
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.microsoft.powerbim/latest/
  - route: integrations page
    url: https://learn.microsoft.com/en-us/power-query/connectors/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Visual Studio App Center Crashes
    provider: microsoft-app-center
    says: ships the Visual Studio App Center Crashes SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.microsoft.powerbim/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe Analytics
    provider: adobe-analytics
    says: lists Adobe Analytics as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: domain
    name: ADP Analytics
    provider: adp
    says: lists ADP Analytics as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Athena
    provider: amazon-athena
    says: lists Amazon Athena as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Amazon OpenSearch Service
    provider: amazon-opensearch
    says: lists Amazon OpenSearch Service as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Redshift
    provider: amazon-redshift
    says: lists Amazon Redshift as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Impala
    provider: apache-impala
    says: lists Apache Impala as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Attio
    provider: attio
    says: lists Attio as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1150
      key: construction-management
      name: Construction Management
      url: /capabilities/construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Autodesk Construction Cloud
    provider: autodesk-construction-cloud
    says: lists Autodesk Construction Cloud as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure Data Explorer (Kusto)
    provider: azure-data-explorer
    says: lists Azure Data Explorer (Kusto) as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bitbucket
    provider: bitbucket
    says: lists Bitbucket as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Bitly
    provider: bitly
    says: lists Bitly as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20
      key: AE-230.20
      name: Market & Financial Data
      url: /capabilities/market-financial-data/
      via_parent: null
    credit: null
    layer: domain
    name: Bloomberg Data and Analytics
    provider: bloomberg
    says: lists Bloomberg Data and Analytics as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickHouse
    provider: clickhouse
    says: lists ClickHouse as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Databricks
    provider: databricks
    says: lists Databricks as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-939
      key: AE-939
      name: Data Virtualization & Federation
      url: /capabilities/data-virtualization-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Denodo
    provider: denodo
    says: lists Denodo as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Dremio
    provider: dremio
    says: lists Dremio as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Dynatrace Grail
    provider: dynatrace
    says: lists Dynatrace Grail as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: domain
    name: Elasticsearch
    provider: elastic
    says: lists Elasticsearch as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Exasol
    provider: exasol
    says: lists Exasol as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20
      key: AE-230.20
      name: Market & Financial Data
      url: /capabilities/market-financial-data/
      via_parent: null
    credit: null
    layer: domain
    name: FactSet
    provider: factset
    says: lists FactSet as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Funnel
    provider: funnel
    says: lists Funnel as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Google Analytics 4
    provider: google-analytics
    says: lists Google Analytics 4 as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google BigQuery
    provider: google-bigquery
    says: lists Google BigQuery as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Sheets
    provider: google-sheets
    says: lists Google Sheets as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: IBM Db2
    provider: ibm-db2
    says: lists IBM Db2 as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: IBM Netezza
    provider: netezza
    says: lists IBM Netezza as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Jamf Pro
    provider: jamf
    says: lists Jamf Pro as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MariaDB
    provider: mariadb
    says: lists MariaDB as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    credit: null
    layer: domain
    name: Marketo
    provider: marketo
    says: lists Marketo as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MarkLogic
    provider: marklogic
    says: lists MarkLogic as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft SQL Server
    provider: microsoft-sql-server
    says: lists Microsoft SQL Server as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Mixpanel
    provider: mixpanel
    says: lists Mixpanel as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MongoDB
    provider: mongodb
    says: lists MongoDB as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MySQL
    provider: mysql
    says: lists MySQL as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Oracle Database
    provider: oracle
    says: lists Oracle Database as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Palantir Foundry
    provider: palantir
    says: lists Palantir Foundry as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: PostgreSQL
    provider: postgresql
    says: lists PostgreSQL as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Quickbase
    provider: quickbase
    says: lists Quickbase as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430
      key: fleet-mobile-asset-management
      name: Fleet & Mobile Asset Management
      url: /capabilities/fleet-mobile-asset-management/
      via_parent: null
    credit: null
    layer: domain
    name: Samsara
    provider: samsara
    says: lists Samsara as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: SAP HANA
    provider: sap-hana
    says: lists SAP HANA as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: SingleStore
    provider: singlestore
    says: lists SingleStore as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Siteimprove
    provider: siteimprove
    says: lists Siteimprove as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Smartsheet
    provider: smartsheet
    says: lists Smartsheet as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snowflake
    provider: snowflake
    says: lists Snowflake as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: SparkPost
    provider: sparkpost
    says: lists SparkPost as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Starburst
    provider: starburst
    says: lists Starburst as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Supermetrics
    provider: supermetrics
    says: lists Supermetrics as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: domain
    name: SurveyMonkey
    provider: surveymonkey
    says: lists SurveyMonkey as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Teradata
    provider: teradata
    says: lists Teradata as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Vertica
    provider: vertica
    says: lists Vertica as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: domain
    name: Webtrends Analytics
    provider: webtrends
    says: lists Webtrends Analytics as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wrike
    provider: wrike
    says: lists Wrike as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Zoho Creator
    provider: zoho-creator
    says: lists Zoho Creator as an integration
    source: https://learn.microsoft.com/en-us/power-query/connectors/
    tier: declared
  kind: commercial
  name: Microsoft Power BI
  page: /applications/bi-dashboards/microsoft-power-bi/
  slug: microsoft-power-bi
  url: https://www.microsoft.com/power-platform/products/power-bi
- anchor: looker
  counts:
    declared: 34
    observed: 0
  evidence:
  - route: integrations page
    url: https://cloud.google.com/looker/docs/dialects
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Actian (Avalanche / Vector)
    provider: actian
    says: lists Actian (Avalanche / Vector) as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: AlloyDB for PostgreSQL
    provider: google-alloydb
    says: lists AlloyDB for PostgreSQL as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Athena
    provider: amazon-athena
    says: lists Amazon Athena as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon Aurora
    provider: amazon-aurora
    says: lists Amazon Aurora as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Redshift
    provider: amazon-redshift
    says: lists Amazon Redshift as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Druid
    provider: apache-druid
    says: lists Apache Druid as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Hive
    provider: apache-hive
    says: lists Apache Hive as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Impala
    provider: apache-impala
    says: lists Apache Impala as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Apache Spark SQL
    provider: apache-spark
    says: lists Apache Spark SQL as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure Synapse Analytics
    provider: microsoft-azure-synapse-analytics
    says: lists Azure Synapse Analytics as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickHouse
    provider: clickhouse
    says: lists ClickHouse as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-939
      key: AE-939
      name: Data Virtualization & Federation
      url: /capabilities/data-virtualization-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Data Virtuality
    provider: data-virtuality
    says: lists Data Virtuality as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Databricks
    provider: databricks
    says: lists Databricks as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-939
      key: AE-939
      name: Data Virtualization & Federation
      url: /capabilities/data-virtualization-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Denodo
    provider: denodo
    says: lists Denodo as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Dremio
    provider: dremio
    says: lists Dremio as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Exasol
    provider: exasol
    says: lists Exasol as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google BigQuery
    provider: google-bigquery
    says: lists Google BigQuery as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Cloud Spanner
    provider: google-cloud-spanner
    says: lists Google Cloud Spanner as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Cloud SQL
    provider: google-cloud-sql
    says: lists Google Cloud SQL as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Greenplum
    provider: greenplum
    says: lists Greenplum as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: IBM Netezza
    provider: netezza
    says: lists IBM Netezza as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MariaDB
    provider: mariadb
    says: lists MariaDB as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Microsoft SQL Server
    provider: microsoft-sql-server
    says: lists Microsoft SQL Server as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MongoDB
    provider: mongodb
    says: lists MongoDB as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MySQL
    provider: mysql
    says: lists MySQL as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Oracle Database
    provider: oracle
    says: lists Oracle Database as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: PostgreSQL
    provider: postgresql
    says: lists PostgreSQL as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Presto (PrestoDB)
    provider: presto-foundation
    says: lists Presto (PrestoDB) as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: SAP HANA
    provider: sap-hana
    says: lists SAP HANA as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: SingleStore
    provider: singlestore
    says: lists SingleStore as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snowflake
    provider: snowflake
    says: lists Snowflake as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Teradata
    provider: teradata
    says: lists Teradata as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Trino
    provider: trino
    says: lists Trino as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Vertica
    provider: vertica
    says: lists Vertica as an integration
    source: https://cloud.google.com/looker/docs/dialects
    tier: declared
  kind: commercial
  name: Looker
  page: /applications/bi-dashboards/looker/
  slug: looker
  url: https://cloud.google.com/looker
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: bi-dashboards
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Analytics
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#analytics
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Analytics
  store: microsoft-appsource
  url: https://appsource.microsoft.com/marketplace/apps?product=power-bi
- category: Analytics
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Business Intelligence & Advanced Analytics
  store: aws-marketplace
  url: https://aws.amazon.com/marketplace/search/results?category=Business%20Intelligence%20%26%20Advanced%20Analytics
name: BI & Dashboards
needs:
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: domain
  why: warehouses, OLAP engines and query engines every BI tool connects to; the category is defined by its connector list
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: operational relational/NoSQL databases queried directly as dashboard sources
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: alert and report delivery to team chat
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: spreadsheets and no-code databases as data sources
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: metrics, logs and traces stores that power operational dashboards (Grafana) and monitoring sources
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: domain
  why: web/product analytics APIs pulled into dashboards
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: domain
  why: work-management data as a source or alert destination
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: CRM objects/reports as a data source
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: declared/observed source or destination in the reference apps
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  fit: exact
  layer: common
  why: alert routing to on-call/incident tools
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: declared/observed source or destination in the reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: declared/observed source or destination in the reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: declared/observed source or destination in the reference apps
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  fit: exact
  layer: domain
  why: declared/observed source or destination in the reference apps
- capability:
    attribution: Turbo EA
    id: BC-1150
    key: construction-management
    name: Construction Management
    url: /capabilities/construction-management/
    via_parent: null
  fit: exact
  layer: domain
  why: declared/observed source or destination in the reference apps
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: exact
  layer: domain
  why: declared/observed source or destination in the reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: domain
  why: declared/observed source or destination in the reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-230.20
    key: AE-230.20
    name: Market & Financial Data
    url: /capabilities/market-financial-data/
    via_parent: null
  fit: exact
  layer: domain
  why: declared/observed source or destination in the reference apps
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: declared/observed source or destination in the reference apps
- capability:
    attribution: Turbo EA
    id: BC-400.50
    key: marketing-operations-management
    name: Marketing Operations Management
    url: /capabilities/marketing-operations-management/
    via_parent: null
  fit: exact
  layer: domain
  why: declared/observed source or destination in the reference apps
- capability:
    attribution: Turbo EA
    id: BC-2430
    key: fleet-mobile-asset-management
    name: Fleet & Mobile Asset Management
    url: /capabilities/fleet-mobile-asset-management/
    via_parent: null
  fit: exact
  layer: domain
  why: declared/observed source or destination in the reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: declared/observed source or destination in the reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: domain
  why: declared/observed source or destination in the reference apps
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: declared/observed source or destination in the reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-939
    key: AE-939
    name: Data Virtualization & Federation
    url: /capabilities/data-virtualization-federation/
    via_parent: null
  fit: exact
  layer: domain
  why: Denodo, Data Virtuality (Data Virtualization & Federation)
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  fit: exact
  layer: domain
  why: Elasticsearch, Apache Solr, Amazon OpenSearch Service (Search and Discovery Management)
- capability:
    attribution: API Evangelist extension
    id: AE-938
    key: AE-938
    name: Semantic & Metrics Layer
    url: /capabilities/analytics-bi-management/
    via_parent: Analytics & BI Management
  fit: exact
  layer: domain
  why: dbt (Semantic & Metrics Layer)
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 44.9
      apps:
      - Apache Superset
      - Lightdash
      - Looker
      - Metabase
      - Microsoft Power BI
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 82.3
      mcp:
        source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
        status: verified
      name: Snowflake
      slug: snowflake
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Data
      - Data Lakehouse
      - Data Warehouse
      - Snowflake
      tier: observed
      url: /providers/snowflake/
    - agent_band: agent-ready
      agent_readiness: 58.5
      apps:
      - Apache Superset
      - Lightdash
      - Looker
      - Metabase
      - Microsoft Power BI
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 77.1
      mcp:
        source: https://github.com/ClickHouse/mcp-clickhouse
        status: verified
      name: ClickHouse
      slug: clickhouse
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - ClickHouse
      - Cloud Database
      - Column-Oriented
      tier: observed
      url: /providers/clickhouse/
    - agent_band: agent-native
      agent_readiness: 44.8
      apps:
      - Apache Superset
      - Lightdash
      - Looker
      - Metabase
      - Microsoft Power BI
      - Redash
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Athena
      slug: amazon-athena
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Amazon Athena
      - Analytics
      - SQL
      - Serverless
      tier: observed
      url: /providers/amazon-athena/
    - agent_band: agent-native
      agent_readiness: 65.5
      apps:
      - Apache Superset
      - Lightdash
      - Looker
      - Metabase
      - Microsoft Power BI
      - Redash
      band: strong
      in_catalog: true
      kin_score: 58.7
      mcp:
        source: https://docs.databricks.com/aws/en/generative-ai/mcp/
        status: verified
      name: Databricks
      slug: databricks
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cleanroom
      - Databricks
      tier: observed
      url: /providers/databricks/
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Apache Superset
      - Lightdash
      - Looker
      - Metabase
      - Microsoft Power BI
      - Redash
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
        status: verified
      name: Google BigQuery
      slug: google-bigquery
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Cloud
      - Data Warehouse
      tier: observed
      url: /providers/google-bigquery/
    - agent_band: agent-native
      agent_readiness: 44.5
      apps:
      - Apache Superset
      - Lightdash
      - Looker
      - Metabase
      - Microsoft Power BI
      band: exemplar
      in_catalog: true
      kin_score: 75.1
      mcp:
        source: https://github.com/awslabs/mcp/tree/main/src/redshift-mcp-server
        status: verified
      name: Amazon Redshift
      slug: amazon-redshift
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/lightdash/lightdash/tree/main/packages/warehouses/src/warehouseClients
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Cloud
      - Data Lake
      tier: observed
      url: /providers/amazon-redshift/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Apache Superset
      - Looker
      - Metabase
      - Microsoft Power BI
      - Redash
      band: emerging
      in_catalog: true
      kin_score: 22.9
      mcp:
        status: none
      name: Vertica
      slug: vertica
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics Database
      - Data Lakehouse
      - Data Warehouse
      - Database
      tier: observed
      url: /providers/vertica/
    - agent_band: agent-ready
      agent_readiness: 31.6
      apps:
      - Apache Superset
      - Looker
      - Microsoft Power BI
      - Redash
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        source: https://github.com/singlestore-labs/mcp-server-singlestore
        status: verified
      name: SingleStore
      slug: singlestore
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - Cloud
      - Database
      - SQL
      tier: observed
      url: /providers/singlestore/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Apache Superset
      - Looker
      - Metabase
      - Redash
      band: thin
      in_catalog: true
      kin_score: 38.7
      mcp:
        status: none
      name: Apache Druid
      slug: apache-druid
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - Apache
      - Database
      - Kafka
      tier: observed
      url: /providers/apache-druid/
    - agent_band: agent-aware
      agent_readiness: 27.2
      apps:
      - Apache Superset
      - Looker
      - Metabase
      - Redash
      band: thin
      in_catalog: true
      kin_score: 34.3
      mcp:
        status: none
      name: Presto (PrestoDB)
      slug: presto-foundation
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Distributed SQL
      - Linux Foundation
      tier: observed
      url: /providers/presto-foundation/
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Apache Superset
      - Lightdash
      - Looker
      - Redash
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: none
      name: Trino
      slug: trino
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Distributed SQL
      - MySQL
      tier: observed
      url: /providers/trino/
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - Apache Superset
      - Looker
      - Metabase
      - Redash
      band: thin
      in_catalog: true
      kin_score: 32.9
      mcp:
        status: none
      name: Apache Hive
      slug: apache-hive
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Apache
      - Big Data
      - Data Warehouse
      - ETL
      tier: observed
      url: /providers/apache-hive/
    - agent_band: agent-aware
      agent_readiness: 15.5
      apps:
      - Apache Superset
      - Looker
      - Microsoft Power BI
      - Redash
      band: emerging
      in_catalog: true
      kin_score: 22.6
      mcp:
        status: unchecked
      name: Exasol
      slug: exasol
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Company
      - Database
      tier: observed
      url: /providers/exasol/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Apache Superset
      - Looker
      - Microsoft Power BI
      - Redash
      band: emerging
      in_catalog: true
      kin_score: 22.6
      mcp:
        status: none
      name: IBM Netezza
      slug: netezza
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - Company
      - Data Warehouse
      - Database
      tier: observed
      url: /providers/netezza/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Apache Superset
      - Looker
      - Microsoft Power BI
      - Redash
      band: emerging
      in_catalog: true
      kin_score: 13.8
      mcp:
        status: unchecked
      name: Apache Impala
      slug: apache-impala
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - Company
      - Hadoop
      - Open Source
      tier: observed
      url: /providers/apache-impala/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Apache Superset
      - Looker
      - Microsoft Power BI
      band: developing
      in_catalog: true
      kin_score: 52.8
      mcp:
        source: https://github.com/Teradata/teradata-mcp-server
        status: verified
      name: Teradata
      slug: teradata
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Analytics
      - Cloud
      - Data Management
      - Data Warehousing
      tier: observed
      url: /providers/teradata/
    - agent_band: agent-aware
      agent_readiness: 5.8
      apps:
      - Apache Superset
      - Looker
      - Microsoft Power BI
      band: developing
      in_catalog: true
      kin_score: 51.5
      mcp:
        source: https://github.com/dremio/dremio-mcp
        status: verified
      name: Dremio
      slug: dremio
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Analytics
      - Company
      - Data Lakehouse
      - SQL Query Engine
      tier: observed
      url: /providers/dremio/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Apache Superset
      - Looker
      - Microsoft Power BI
      band: developing
      in_catalog: true
      kin_score: 44.8
      mcp:
        status: none
      name: SAP HANA
      slug: sap-hana
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Analytics
      - Cloud
      - Database
      - Enterprise
      tier: observed
      url: /providers/sap-hana/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Apache Superset
      - Looker
      - Metabase
      band: thin
      in_catalog: true
      kin_score: 38.3
      mcp:
        status: none
      name: Apache Spark SQL
      slug: apache-spark
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/metabase/metabase/tree/master/modules/drivers
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Distributed Computing
      - Machine Learning
      tier: observed
      url: /providers/apache-spark/
    - agent_band: human-only
      agent_readiness: 1.3
      apps:
      - Apache Superset
      - Lightdash
      - Redash
      band: thin
      in_catalog: true
      kin_score: 27.8
      mcp:
        status: none
      name: DuckDB
      slug: duckdb
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      - https://github.com/lightdash/lightdash/tree/main/packages/warehouses/src/warehouseClients
      status: profiled
      tags:
      - Analytics
      - Database
      - Embedded
      - OLAP
      tier: observed
      url: /providers/duckdb/
    - agent_band: null
      agent_readiness: null
      apps:
      - Apache Superset
      - Microsoft Power BI
      - Redash
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Azure Data Explorer (Kusto)
      slug: azure-data-explorer
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-aware
      agent_readiness: 23.2
      apps:
      - Apache Superset
      - Redash
      band: developing
      in_catalog: true
      kin_score: 42.4
      mcp:
        status: unchecked
      name: Databend
      slug: databend
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Cloud
      - Company
      - Data Warehouse
      - Open Source
      tier: observed
      url: /providers/databend/
    - agent_band: agent-aware
      agent_readiness: 24.9
      apps:
      - Apache Superset
      - Redash
      band: thin
      in_catalog: true
      kin_score: 37.2
      mcp:
        status: none
      name: Apache Kylin
      slug: apache-kylin
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - Big Data
      - OLAP
      - cube
      tier: observed
      url: /providers/apache-kylin/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Metabase
      - Microsoft Power BI
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        source: https://docs.starburst.io/starburst-galaxy/starburst-ai/mcp-server.html
        status: verified
      name: Starburst
      slug: starburst
      sources:
      - https://github.com/metabase/metabase/tree/master/modules/drivers
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Company
      - Data Analytics
      - Data Lakehouse
      - SQL Query Engine
      tier: observed
      url: /providers/starburst/
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Apache Superset
      - Redash
      band: thin
      in_catalog: true
      kin_score: 30.4
      mcp:
        source: https://github.com/risingwavelabs/risingwave-mcp
        status: verified
      name: RisingWave
      slug: risingwave
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Database
      - Real-Time
      - SQL
      - Streaming
      tier: observed
      url: /providers/risingwave/
    - agent_band: agent-aware
      agent_readiness: 12.4
      apps:
      - Apache Superset
      - Redash
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        status: unchecked
      name: Apache Drill
      slug: apache-drill
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Data Analytics
      - Distributed Query
      - Hadoop
      - SQL Engine
      tier: observed
      url: /providers/apache-drill/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Apache Superset
      - Redash
      band: emerging
      in_catalog: true
      kin_score: 20.5
      mcp:
        status: none
      name: Apache Pinot
      slug: apache-pinot
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - Database
      - Low Latency
      - OLAP
      tier: observed
      url: /providers/apache-pinot/
    - agent_band: agent-ready
      agent_readiness: 32.1
      apps:
      - Lightdash
      - Metabase
      band: emerging
      in_catalog: true
      kin_score: 18.6
      mcp:
        source: https://github.com/motherduckdb/mcp-server-motherduck
        status: verified
      name: MotherDuck
      slug: motherduck
      sources:
      - https://github.com/lightdash/lightdash/tree/main/packages/warehouses/src/warehouseClients
      - https://github.com/metabase/metabase/tree/master/modules/drivers
      status: profiled
      tags:
      - Data Warehouse
      - DuckDB
      - SQL
      - Serverless
      tier: observed
      url: /providers/motherduck/
    - agent_band: null
      agent_readiness: null
      apps:
      - Apache Superset
      - Looker
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Greenplum
      slug: greenplum
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-native
      agent_readiness: 49.9
      apps:
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        source: https://github.com/treasure-data/td-mcp-server
        status: verified
      name: Treasure Data
      slug: treasure-data
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Big Data
      - CDP
      - Customer Data Platform
      - Data Warehouse
      tier: observed
      url: /providers/treasure-data/
    - agent_band: agent-ready
      agent_readiness: 32.8
      apps:
      - Apache Superset
      band: strong
      in_catalog: true
      kin_score: 58.0
      mcp:
        source: https://docs.ocient.com/ocient-mcp-server
        status: verified
      name: Ocient
      slug: ocient
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Analytics
      - Company
      - Data
      - Data Warehouse
      tier: observed
      url: /providers/ocient/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Redash
      band: developing
      in_catalog: true
      kin_score: 46.4
      mcp:
        source: https://www.tinybird.co/docs/forward/analytics-agents/mcp
        status: verified
      name: Tinybird
      slug: tinybird
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - Data
      - Real-Time
      - SQL
      tier: observed
      url: /providers/tinybird/
    - agent_band: human-only
      agent_readiness: 1.8
      apps:
      - Apache Superset
      band: developing
      in_catalog: true
      kin_score: 39.3
      mcp:
        source: https://github.com/apache/doris-mcp-server
        status: verified
      name: Apache Doris
      slug: apache-doris
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Analytics
      - Apache
      - Database
      - Lakehouse
      tier: observed
      url: /providers/apache-doris/
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - Apache Superset
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp:
        source: https://github.com/firebolt-db/mcp-server
        status: verified
      name: Firebolt
      slug: firebolt
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Analytics
      - Cloud
      - Data Warehouse
      - SQL
      tier: observed
      url: /providers/firebolt/
    - agent_band: agent-aware
      agent_readiness: 5.3
      apps:
      - Redash
      band: thin
      in_catalog: true
      kin_score: 33.7
      mcp:
        status: unknown
      name: e6data
      slug: e6data
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - B2B
      - Company
      - Data
      tier: observed
      url: /providers/e6data/
    - agent_band: agent-aware
      agent_readiness: 12.4
      apps:
      - Redash
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        status: unchecked
      name: Apache Phoenix
      slug: apache-phoenix
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Company
      - Database
      - Open Source
      - SQL
      tier: observed
      url: /providers/apache-phoenix/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Apache Superset
      band: thin
      in_catalog: true
      kin_score: 29.1
      mcp:
        source: https://github.com/StarRocks/mcp-server-starrocks
        status: verified
      name: StarRocks
      slug: starrocks
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Lakehouse
      - OLAP
      - Open Source
      - SQL
      tier: observed
      url: /providers/starrocks/
    - agent_band: human-only
      agent_readiness: 3.4
      apps:
      - Apache Superset
      band: emerging
      in_catalog: true
      kin_score: 17.9
      mcp:
        source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
        status: verified
      name: Alibaba Cloud (Hologres / MaxCompute)
      slug: alibaba
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Cloud
      - Cloud Computing
      - Commerce
      - E-Commerce
      tier: observed
      url: /providers/alibaba/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Apache Superset
      band: minimal
      in_catalog: true
      kin_score: 9.8
      mcp:
        status: unchecked
      name: MonetDB
      slug: monetdb
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Analytics
      - Database
      - Open Source
      - SQL
      tier: observed
      url: /providers/monetdb/
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - Looker
      band: strong
      in_catalog: true
      kin_score: 62.9
      mcp:
        status: none
      name: Azure Synapse Analytics
      slug: microsoft-azure-synapse-analytics
      sources:
      - https://cloud.google.com/looker/docs/dialects
      status: profiled
      tags:
      - Analytics
      - Apache Spark
      - Big Data
      - Data Integration
      tier: declared
      url: /providers/microsoft-azure-synapse-analytics/
    - agent_band: agent-ready
      agent_readiness: 43.8
      apps:
      - Looker
      band: strong
      in_catalog: true
      kin_score: 60.7
      mcp:
        source: https://docs.actian.com/mcp-server/
        status: verified
      name: Actian (Avalanche / Vector)
      slug: actian
      sources:
      - https://cloud.google.com/looker/docs/dialects
      status: profiled
      tags:
      - Analytics
      - Company
      - Data
      - Integration
      tier: declared
      url: /providers/actian/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Microsoft Power BI
      band: strong
      in_catalog: true
      kin_score: 58.7
      mcp:
        source: https://github.com/funnel-io/funnel-mcp
        status: verified
      name: Funnel
      slug: funnel
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Company
      - Marketing
      - Marketing Data
      - Marketing Intelligence
      tier: declared
      url: /providers/funnel/
    - agent_band: agent-ready
      agent_readiness: 33.4
      apps:
      - Microsoft Power BI
      band: strong
      in_catalog: true
      kin_score: 58.2
      mcp:
        source: https://mcp.supermetrics.com/mcp
        status: verified
      name: Supermetrics
      slug: supermetrics
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Advertising
      - Analytics
      - Company
      - Marketing
      tier: declared
      url: /providers/supermetrics/
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - Microsoft Power BI
      band: emerging
      in_catalog: true
      kin_score: 24.9
      mcp:
        source: https://github.com/palantir/palantir-mcp
        status: verified
      name: Palantir Foundry
      slug: palantir
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - AI Platform
      - Data Analytics
      - Enterprise
      - Government
      tier: declared
      url: /providers/palantir/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Microsoft Power BI
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics 4
      slug: google-analytics
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        status: none
      name: Google Search Console
      slug: google-search-console
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - Google
      - Indexing
      - Search
      tier: observed
      url: /providers/google-search-console/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Redash
      band: emerging
      in_catalog: true
      kin_score: 14.8
      mcp:
        status: none
      name: Yandex Metrica
      slug: yandex-metrica
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - Marketing
      - Web Analytics
      - Yandex
      tier: observed
      url: /providers/yandex-metrica/
    - agent_band: agent-native
      agent_readiness: 60.3
      apps:
      - Microsoft Power BI
      band: strong
      in_catalog: true
      kin_score: 65.0
      mcp:
        status: none
      name: Adobe Analytics
      slug: adobe-analytics
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Adobe
      - Analytics
      - Business Intelligence
      - Customer Intelligence
      tier: declared
      url: /providers/adobe-analytics/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Microsoft Power BI
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: declared
      url: /providers/mixpanel/
    - agent_band: agent-aware
      agent_readiness: 24.9
      apps:
      - Microsoft Power BI
      band: thin
      in_catalog: true
      kin_score: 35.4
      mcp:
        status: unchecked
      name: Siteimprove
      slug: siteimprove
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Accessibility
      - Analytics
      - Company
      - SEO
      tier: declared
      url: /providers/siteimprove/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Microsoft Power BI
      band: emerging
      in_catalog: true
      kin_score: 14.1
      mcp:
        status: unchecked
      name: Webtrends Analytics
      slug: webtrends
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Analytics
      - Digital Analytics
      - Microsoft 365
      - SharePoint
      tier: declared
      url: /providers/webtrends/
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Apache Superset
      - Grafana
      - Microsoft Power BI
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp:
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elasticsearch
      slug: elastic
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      - https://github.com/grafana/grafana/tree/main/docs/sources/datasources
      status: profiled
      tags:
      - Analytics
      - Observability
      - Search
      - Security
      tier: observed
      url: /providers/elastic/
    - agent_band: agent-native
      agent_readiness: 43.6
      apps:
      - Microsoft Power BI
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://docs.aws.amazon.com/opensearch-service/latest/developerguide/aws-mcp-server.html
        status: verified
      name: Amazon OpenSearch Service
      slug: amazon-opensearch
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Amazon Web Services
      - Analytics
      - Elasticsearch
      - Search
      tier: observed
      url: /providers/amazon-opensearch/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Apache Superset
      band: developing
      in_catalog: true
      kin_score: 40.6
      mcp:
        source: https://github.com/apache/solr-mcp
        status: verified
      name: Apache Solr
      slug: apache-solr
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Enterprise Search
      - Full-Text Search
      - Lucene
      - Search
      tier: observed
      url: /providers/apache-solr/
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 64.4
      apps:
      - Grafana
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira (JQL)
      slug: jira
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: observed
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Microsoft Power BI
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://github.com/getredash/redash/tree/master/redash/destinations
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: observed
      url: /providers/asana/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Microsoft Power BI
      band: developing
      in_catalog: true
      kin_score: 50.0
      mcp:
        source: https://github.com/wrike/datahub-mcp
        status: verified
      name: Wrike
      slug: wrike
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: declared
      url: /providers/wrike/
  - capability:
      attribution: API Evangelist extension
      id: AE-939
      key: AE-939
      name: Data Virtualization & Federation
      url: /capabilities/data-virtualization-federation/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 16.5
      apps:
      - Apache Superset
      - Looker
      - Microsoft Power BI
      band: thin
      in_catalog: true
      kin_score: 34.7
      mcp:
        source: https://community.denodo.com/docs/html/document/denodoconnects/9.1/en/Denodo%20MCP%20Server%20-%20User%20Manual
        status: verified
      name: Denodo
      slug: denodo
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Data Catalog
      - Data Fabric
      - Data Mesh
      - Data Virtualization
      tier: observed
      url: /providers/denodo/
    - agent_band: null
      agent_readiness: null
      apps:
      - Looker
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Data Virtuality
      slug: data-virtuality
      sources:
      - https://cloud.google.com/looker/docs/dialects
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Microsoft Power BI
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: observed
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Microsoft Power BI
      band: emerging
      in_catalog: true
      kin_score: 20.0
      mcp:
        source: https://docs.attio.com/mcp/overview
        status: verified
      name: Attio
      slug: attio
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - CRM
      - Companies
      - Contacts
      - Sales
      tier: declared
      url: /providers/attio/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.20
      key: AE-230.20
      name: Market & Financial Data
      url: /capabilities/market-financial-data/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 49.0
      apps:
      - Microsoft Power BI
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        source: https://mcp.factset.com/.well-known/oauth-protected-resource
        status: verified
      name: FactSet
      slug: factset
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Finance
      - Financial Data
      - Investment Analytics
      - Market Data
      tier: declared
      url: /providers/factset/
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - Microsoft Power BI
      band: strong
      in_catalog: true
      kin_score: 55.4
      mcp:
        status: unknown
      name: Bloomberg Data and Analytics
      slug: bloomberg
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Analytics
      - Business Intelligence
      - Data License
      - Enterprise
      tier: declared
      url: /providers/bloomberg/
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Microsoft Power BI
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: declared
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Microsoft Power BI
      band: exemplar
      in_catalog: true
      kin_score: 71.9
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Bitbucket
      slug: bitbucket
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Atlassian
      - CI/CD
      - Code Collaboration
      - Code Review
      tier: declared
      url: /providers/bitbucket/
  - capability:
      attribution: Turbo EA
      id: BC-1150
      key: construction-management
      name: Construction Management
      url: /capabilities/construction-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Microsoft Power BI
      band: exemplar
      in_catalog: true
      kin_score: 69.0
      mcp:
        source: https://github.com/autodesk-platform-services/aps-mcp-server-nodejs
        status: verified
      name: Autodesk Construction Cloud
      slug: autodesk-construction-cloud
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - AEC
      - BIM
      - Construction
      - Project Management
      tier: declared
      url: /providers/autodesk-construction-cloud/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Microsoft Power BI
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Microsoft Power BI
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        status: none
      name: Jamf Pro
      slug: jamf
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Apple Device Management
      - Company
      - Endpoint Security
      - MDM
      tier: declared
      url: /providers/jamf/
  - capability:
      attribution: Turbo EA
      id: BC-2430
      key: fleet-mobile-asset-management
      name: Fleet & Mobile Asset Management
      url: /capabilities/fleet-mobile-asset-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - Microsoft Power BI
      band: thin
      in_catalog: true
      kin_score: 32.0
      mcp:
        source: https://mcp.samsara.com/mcp
        status: documented
      name: Samsara
      slug: samsara
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Asset Tracking
      - Connected Operations
      - ELD
      - Fleet Management
      tier: declared
      url: /providers/samsara/
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.8
      apps:
      - Microsoft Power BI
      band: developing
      in_catalog: true
      kin_score: 45.6
      mcp:
        status: none
      name: ADP Analytics
      slug: adp
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Benefits
      - HCM
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/adp/
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 58.2
      apps:
      - Microsoft Power BI
      band: exemplar
      in_catalog: true
      kin_score: 73.0
      mcp:
        source: https://dev.bitly.com/bitly-mcp/
        status: verified
      name: Bitly
      slug: bitly
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Analytics
      - Links
      - QR Codes
      - URL Shorteners
      tier: declared
      url: /providers/bitly/
  - capability:
      attribution: Turbo EA
      id: BC-400.50
      key: marketing-operations-management
      name: Marketing Operations Management
      url: /capabilities/marketing-operations-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Microsoft Power BI
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        status: none
      name: Marketo
      slug: marketo
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Adobe
      - Automation
      - Marketing
      - Marketing Automation
      tier: declared
      url: /providers/marketo/
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Microsoft Power BI
      band: thin
      in_catalog: true
      kin_score: 34.9
      mcp:
        source: https://www.surveymonkey.com/apps/
        status: documented
      name: SurveyMonkey
      slug: surveymonkey
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Feedback
      - Market Research
      - NPS
      - Surveys
      tier: declared
      url: /providers/surveymonkey/
  - capability:
      attribution: API Evangelist extension
      id: AE-938
      key: AE-938
      name: Semantic & Metrics Layer
      url: /capabilities/analytics-bi-management/
      via_parent: Analytics & BI Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.8
      apps:
      - Lightdash
      band: developing
      in_catalog: true
      kin_score: 51.5
      mcp:
        source: https://github.com/dbt-labs/dbt-mcp
        status: verified
      name: dbt
      slug: dbt
      sources:
      - https://github.com/lightdash/lightdash/blob/main/README.md
      status: profiled
      tags:
      - Analytics Engineering
      - Data
      - ELT
      - Metrics
      tier: declared
      url: /providers/dbt/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Apache Superset
      - Grafana
      - Lightdash
      - Looker
      - Metabase
      - Microsoft Power BI
      - Redash
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: none
      name: PostgreSQL
      slug: postgresql
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Database
      - Open Source
      - Relational Database
      - SQL
      tier: observed
      url: /providers/postgresql/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Apache Superset
      - Grafana
      - Looker
      - Metabase
      - Microsoft Power BI
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 67.0
      mcp:
        source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
        status: verified
      name: Microsoft SQL Server
      slug: microsoft-sql-server
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Cloud
      - Data Management
      - Database
      - Enterprise
      tier: observed
      url: /providers/microsoft-sql-server/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Apache Superset
      - Grafana
      - Looker
      - Metabase
      - Microsoft Power BI
      - Redash
      band: thin
      in_catalog: true
      kin_score: 30.5
      mcp:
        status: none
      name: MySQL
      slug: mysql
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Database
      - Open Source
      - RDBMS
      - Relational Database
      tier: observed
      url: /providers/mysql/
    - agent_band: agent-ready
      agent_readiness: 59.1
      apps:
      - Apache Superset
      - Looker
      - Metabase
      - Microsoft Power BI
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 79.9
      mcp:
        source: https://github.com/mongodb-js/mongodb-mcp-server
        status: verified
      name: MongoDB
      slug: mongodb
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Cloud Database
      - Database
      - Document Database
      - NoSQL
      tier: observed
      url: /providers/mongodb/
    - agent_band: agent-ready
      agent_readiness: 59.8
      apps:
      - Apache Superset
      - Looker
      - Metabase
      - Microsoft Power BI
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 70.4
      mcp:
        source: https://github.com/oracle/mcp
        status: verified
      name: Oracle Database
      slug: oracle
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Cloud
      - Database
      - Enterprise
      - Oracle
      tier: observed
      url: /providers/oracle/
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - Apache Superset
      - Looker
      - Microsoft Power BI
      band: developing
      in_catalog: true
      kin_score: 41.2
      mcp:
        status: unchecked
      name: MariaDB
      slug: mariadb
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Cloud
      - Database
      - Enterprise
      - Open Source
      tier: observed
      url: /providers/mariadb/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Apache Superset
      - Microsoft Power BI
      - Redash
      band: emerging
      in_catalog: true
      kin_score: 14.0
      mcp:
        status: none
      name: IBM Db2
      slug: ibm-db2
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Cloud Database
      - Database
      - Relational Database
      - SQL
      tier: observed
      url: /providers/ibm-db2/
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Apache Superset
      - Looker
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        source: https://github.com/awslabs/mcp
        status: documented
      name: Amazon Aurora
      slug: amazon-aurora
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Amazon Aurora
      - MySQL
      - PostgreSQL
      - Relational Database
      tier: observed
      url: /providers/amazon-aurora/
    - agent_band: agent-aware
      agent_readiness: 28.4
      apps:
      - Apache Superset
      - Redash
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        source: https://github.com/couchbase/mcp-server-couchbase
        status: verified
      name: Couchbase
      slug: couchbase
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Analytics
      - App Services
      - Backup
      - Capella
      tier: observed
      url: /providers/couchbase/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - Looker
      - Redash
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/googleapis/mcp-toolbox
        status: verified
      name: Google Cloud Spanner
      slug: google-cloud-spanner
      sources:
      - https://cloud.google.com/looker/docs/dialects
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Database
      - Distributed
      - Google Cloud
      - Relational
      tier: observed
      url: /providers/google-cloud-spanner/
    - agent_band: agent-ready
      agent_readiness: 30.3
      apps:
      - Apache Superset
      - Redash
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        source: https://github.com/cloudflare/mcp-server-cloudflare
        status: verified
      name: Cloudflare D1
      slug: cloudflare-d1
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Database
      - Edge Computing
      - SQLite
      - Serverless
      tier: observed
      url: /providers/cloudflare-d1/
    - agent_band: agent-native
      agent_readiness: 41.0
      apps:
      - Apache Superset
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon DynamoDB
      slug: amazon-dynamodb
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Amazon Web Services
      - Database
      - Document Store
      - Key-Value Store
      tier: observed
      url: /providers/amazon-dynamodb/
    - agent_band: agent-native
      agent_readiness: 49.9
      apps:
      - Apache Superset
      band: exemplar
      in_catalog: true
      kin_score: 79.2
      mcp:
        source: https://github.com/cockroachdb/cockroachdb-mcp-server
        status: verified
      name: CockroachDB
      slug: cockroach-labs
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Cloud
      - Cluster Management
      - Database
      - Distributed SQL
      tier: observed
      url: /providers/cockroach-labs/
    - agent_band: agent-ready
      agent_readiness: 37.3
      apps:
      - Apache Superset
      band: exemplar
      in_catalog: true
      kin_score: 70.6
      mcp:
        source: https://www.tigerdata.com/docs/reference/tiger-cloud/tiger-mcp
        status: verified
      name: TimescaleDB
      slug: timescale
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Company
      - Database
      - PostgreSQL
      - Time Series
      tier: observed
      url: /providers/timescale/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Apache Superset
      band: exemplar
      in_catalog: true
      kin_score: 67.3
      mcp:
        source: https://github.com/yugabyte/yugabytedb-mcp-server
        status: verified
      name: YugabyteDB
      slug: yugabyte
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Company
      - Database
      - Distributed SQL
      - PostgreSQL
      tier: observed
      url: /providers/yugabyte/
    - agent_band: agent-ready
      agent_readiness: 36.6
      apps:
      - Apache Superset
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp:
        status: none
      name: Google Cloud Datastore
      slug: google-cloud-datastore
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Database
      - Document Database
      - Google Cloud
      - NoSQL
      tier: observed
      url: /providers/google-cloud-datastore/
    - agent_band: agent-aware
      agent_readiness: 27.8
      apps:
      - Redash
      band: developing
      in_catalog: true
      kin_score: 52.3
      mcp:
        status: none
      name: ArangoDB
      slug: arangodb
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Company
      - Database
      - Graph Database
      - Multi-Model Database
      tier: observed
      url: /providers/arangodb/
    - agent_band: agent-aware
      agent_readiness: 8.7
      apps:
      - Apache Superset
      band: developing
      in_catalog: true
      kin_score: 47.8
      mcp:
        source: https://github.com/crate/cratedb-mcp
        status: verified
      name: CrateDB
      slug: crate-io
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Company
      - Database
      - Distributed Database
      - SQL
      tier: observed
      url: /providers/crate-io/
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Apache Superset
      band: developing
      in_catalog: true
      kin_score: 41.3
      mcp:
        status: unknown
      name: Sybase (SAP ASE)
      slug: sybase
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Database
      - Enterprise
      - SAP
      - SQL
      tier: observed
      url: /providers/sybase/
    - agent_band: agent-ready
      agent_readiness: 30.2
      apps:
      - Redash
      band: developing
      in_catalog: true
      kin_score: 40.0
      mcp:
        status: none
      name: Apache Ignite
      slug: apache-ignite
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Caching
      - Compute Grid
      - Distributed Database
      - In-Memory
      tier: observed
      url: /providers/apache-ignite/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Redash
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp:
        status: none
      name: Apache Cassandra
      slug: cassandra
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Apache
      - Big Data
      - Database
      - Distributed
      tier: observed
      url: /providers/cassandra/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Apache Superset
      band: emerging
      in_catalog: true
      kin_score: 24.7
      mcp:
        status: unchecked
      name: OceanBase
      slug: oceanbase
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - AI Native Search
      - Cloud Database
      - Distributed Database
      - Open Source Database
      tier: observed
      url: /providers/oceanbase/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Apache Superset
      band: emerging
      in_catalog: true
      kin_score: 22.5
      mcp:
        status: unchecked
      name: YDB
      slug: ydb
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Database
      - Distributed
      - Open Source
      - SQL
      tier: observed
      url: /providers/ydb/
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - Redash
      band: emerging
      in_catalog: true
      kin_score: 16.1
      mcp:
        source: https://github.com/dgraph-io/dgraph/tree/main/dgraph/cmd/mcp
        status: verified
      name: Dgraph
      slug: dgraph
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - Distributed Database
      - Graph Database
      - GraphQL
      - Real-Time
      tier: observed
      url: /providers/dgraph/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Looker
      band: strong
      in_catalog: true
      kin_score: 65.9
      mcp:
        source: https://sqladmin.googleapis.com/mcp
        status: verified
      name: Google Cloud SQL
      slug: google-cloud-sql
      sources:
      - https://cloud.google.com/looker/docs/dialects
      status: profiled
      tags:
      - Database
      - Google Cloud
      - MySQL
      - PostgreSQL
      tier: declared
      url: /providers/google-cloud-sql/
    - agent_band: null
      agent_readiness: null
      apps:
      - Looker
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: AlloyDB for PostgreSQL
      slug: google-alloydb
      sources:
      - https://cloud.google.com/looker/docs/dialects
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Microsoft Power BI
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: MarkLogic
      slug: marklogic
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 43.4
      apps:
      - Grafana
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 77.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon CloudWatch
      slug: amazon-cloudwatch
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      - https://github.com/grafana/grafana/tree/main/docs/sources/datasources
      status: profiled
      tags:
      - Amazon Web Services
      - CloudWatch
      - Monitoring
      - Observability
      tier: observed
      url: /providers/amazon-cloudwatch/
    - agent_band: agent-ready
      agent_readiness: 29.1
      apps:
      - Grafana
      - Redash
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        source: https://graphite.dev/docs/gt-mcp
        status: verified
      name: Graphite
      slug: graphite-com
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      - https://github.com/grafana/grafana/tree/main/docs/sources/datasources
      status: profiled
      tags:
      - AI Code Review
      - Code Review
      - Stacked PRs
      - merge-queue
      tier: observed
      url: /providers/graphite-com/
    - agent_band: agent-ready
      agent_readiness: 33.6
      apps:
      - Grafana
      - Redash
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        source: https://github.com/influxdata/influxdb3_mcp_server
        status: verified
      name: InfluxDB
      slug: influxdb
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      - https://github.com/grafana/grafana/tree/main/docs/sources/datasources
      status: profiled
      tags:
      - Analytics
      - Database
      - Real-Time
      - Time Series
      tier: observed
      url: /providers/influxdb/
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Grafana
      - Redash
      band: thin
      in_catalog: true
      kin_score: 35.9
      mcp:
        source: https://github.com/prometheus/prometheus-mcp
        status: verified
      name: Prometheus
      slug: prometheus-io
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      - https://github.com/grafana/grafana/tree/main/docs/sources/datasources
      status: profiled
      tags:
      - Metrics
      - Monitoring
      - Observability
      - Prometheus
      tier: observed
      url: /providers/prometheus-io/
    - agent_band: agent-ready
      agent_readiness: 48.6
      apps:
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 80.0
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://github.com/getredash/redash/tree/master/redash/destinations
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: observed
      url: /providers/datadog/
    - agent_band: agent-ready
      agent_readiness: 37.2
      apps:
      - Grafana
      band: strong
      in_catalog: true
      kin_score: 66.4
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Monitoring
      slug: google-cloud-monitoring
      sources:
      - https://github.com/grafana/grafana/tree/main/docs/sources/datasources
      status: profiled
      tags:
      - Alerting
      - Dashboards
      - Google Cloud
      - Metrics
      tier: observed
      url: /providers/google-cloud-monitoring/
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - Apache Superset
      band: developing
      in_catalog: true
      kin_score: 44.5
      mcp:
        status: unchecked
      name: Parseable
      slug: parseable
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Cloud
      - Observability
      - OpenTelemetry
      - Rust
      tier: observed
      url: /providers/parseable/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Grafana
      band: thin
      in_catalog: true
      kin_score: 38.2
      mcp:
        status: none
      name: Zipkin
      slug: zipkin
      sources:
      - https://github.com/grafana/grafana/tree/main/docs/sources/datasources
      status: profiled
      tags:
      - Distributed Tracing
      - Microservices
      - Observability
      - Open Source
      tier: observed
      url: /providers/zipkin/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Grafana
      band: thin
      in_catalog: true
      kin_score: 36.3
      mcp:
        source: https://github.com/jaegertracing/jaeger
        status: verified
      name: Jaeger
      slug: jaeger
      sources:
      - https://github.com/grafana/grafana/tree/main/docs/sources/datasources
      status: profiled
      tags:
      - Distributed Tracing
      - Microservices
      - Monitoring
      - Observability
      tier: observed
      url: /providers/jaeger/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Grafana
      band: thin
      in_catalog: true
      kin_score: 34.0
      mcp:
        status: none
      name: Sensu
      slug: sensu
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Company
      - Infrastructure
      - Monitoring
      - Observability
      tier: observed
      url: /providers/sensu/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Redash
      band: thin
      in_catalog: true
      kin_score: 30.8
      mcp:
        source: https://github.com/uptycslabs/juno-mcp-server
        status: verified
      name: Uptycs
      slug: uptycs
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - CNAPP
      - Cybersecurity
      - Security
      - XDR
      tier: observed
      url: /providers/uptycs/
    - agent_band: agent-aware
      agent_readiness: 19.3
      apps:
      - Apache Superset
      band: thin
      in_catalog: true
      kin_score: 28.5
      mcp:
        status: unchecked
      name: Apache IoTDB
      slug: apache-iotdb
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - Company
      - Database
      - IoT
      - Time Series
      tier: observed
      url: /providers/apache-iotdb/
    - agent_band: agent-aware
      agent_readiness: 15.7
      apps:
      - Apache Superset
      band: thin
      in_catalog: true
      kin_score: 28.0
      mcp:
        status: unchecked
      name: TDengine
      slug: tdengine
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      status: profiled
      tags:
      - AI Platform
      - Company
      - Industrial IoT
      - Time Series Database
      tier: observed
      url: /providers/tdengine/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Grafana
      band: emerging
      in_catalog: true
      kin_score: 20.1
      mcp:
        status: unchecked
      name: OpenTSDB
      slug: opentsdb
      sources:
      - https://github.com/grafana/grafana/tree/main/docs/sources/datasources
      status: profiled
      tags:
      - Company
      - Monitoring
      - Open Source
      - Time Series
      tier: observed
      url: /providers/opentsdb/
    - agent_band: agent-aware
      agent_readiness: 14.5
      apps:
      - Grafana
      band: emerging
      in_catalog: true
      kin_score: 19.7
      mcp:
        status: unchecked
      name: Parca
      slug: parca
      sources:
      - https://github.com/grafana/grafana/tree/main/docs/sources/datasources
      status: profiled
      tags:
      - Cloud-Native
      - Open Source
      - Profiling
      - eBPF
      tier: observed
      url: /providers/parca/
    - agent_band: null
      agent_readiness: null
      apps:
      - Grafana
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Azure Monitor
      slug: azure-monitor
      sources:
      - https://github.com/grafana/grafana/tree/main/docs/sources/datasources
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Microsoft Power BI
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Visual Studio App Center Crashes
      slug: microsoft-app-center
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.microsoft.powerbim/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 43.8
      apps:
      - Microsoft Power BI
      band: exemplar
      in_catalog: true
      kin_score: 85.6
      mcp:
        source: https://github.com/dynatrace-oss/dynatrace-mcp
        status: verified
      name: Dynatrace Grail
      slug: dynatrace
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - AI Operations
      - APM
      - Analytics
      - Application Performance Monitoring
      tier: declared
      url: /providers/dynatrace/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Apache Superset
      - Grafana
      - Metabase
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://github.com/apache/superset/tree/master/superset/reports/notifications
      - https://github.com/getredash/redash/tree/master/redash/destinations
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 41.0
      apps:
      - Grafana
      - Redash
      band: exemplar
      in_catalog: true
      kin_score: 67.1
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Chat
      slug: google-chat
      sources:
      - https://github.com/getredash/redash/tree/master/redash/destinations
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Google
      - Google Workspace
      tier: observed
      url: /providers/google-chat/
    - agent_band: agent-ready
      agent_readiness: 61.8
      apps:
      - Grafana
      - Redash
      band: strong
      in_catalog: true
      kin_score: 66.1
      mcp:
        source: https://github.com/WebexSamples/webex-messaging-mcp-server
        status: verified
      name: Webex
      slug: webex
      sources:
      - https://github.com/getredash/redash/tree/master/redash/destinations
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Calling
      - Collaboration
      - Communications
      - Enterprise
      tier: observed
      url: /providers/webex/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Grafana
      - Redash
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://github.com/getredash/redash/tree/master/redash/destinations
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: observed
      url: /providers/microsoft-teams/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Grafana
      - Redash
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/getredash/redash/tree/master/redash/destinations
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Redash
      band: thin
      in_catalog: true
      kin_score: 37.0
      mcp:
        source: https://github.com/mattermost/mmctl-mcp
        status: verified
      name: Mattermost
      slug: mattermost
      sources:
      - https://github.com/getredash/redash/tree/master/redash/destinations
      status: profiled
      tags:
      - Collaboration
      - Messaging
      - Open Source
      - Team Chat
      tier: observed
      url: /providers/mattermost/
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Redash
      band: thin
      in_catalog: true
      kin_score: 30.1
      mcp:
        source: https://github.com/chatwork/chatwork-mcp-server
        status: verified
      name: Chatwork
      slug: chatwork
      sources:
      - https://github.com/getredash/redash/tree/master/redash/destinations
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Messaging
      - Productivity
      tier: observed
      url: /providers/chatwork/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Grafana
      band: minimal
      in_catalog: true
      kin_score: 7.1
      mcp:
        source: https://github.com/open-dingtalk/dingtalk-mcp
        status: verified
      name: DingTalk
      slug: dingtalk
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Collaboration
      - Communications
      - Company
      - Enterprise
      tier: observed
      url: /providers/dingtalk/
    - agent_band: null
      agent_readiness: null
      apps:
      - Grafana
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: WeCom
      slug: wecom
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Apache Superset
      - Microsoft Power BI
      - Redash
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://github.com/apache/superset/tree/master/superset/db_engine_specs
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: observed
      url: /providers/google-sheets/
    - agent_band: agent-ready
      agent_readiness: 49.5
      apps:
      - Microsoft Power BI
      band: exemplar
      in_catalog: true
      kin_score: 80.5
      mcp:
        status: unknown
      name: Quickbase
      slug: quickbase
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Application Development
      - Company
      - Low-Code
      - No-Code
      tier: declared
      url: /providers/quickbase/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Microsoft Power BI
      band: developing
      in_catalog: true
      kin_score: 41.4
      mcp:
        source: https://github.com/smartsheet-platform/smar-mcp
        status: verified
      name: Smartsheet
      slug: smartsheet
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: declared
      url: /providers/smartsheet/
    - agent_band: agent-aware
      agent_readiness: 26.6
      apps:
      - Microsoft Power BI
      band: thin
      in_catalog: true
      kin_score: 33.6
      mcp:
        source: https://help.zoho.com/portal/en/kb/creator/developer-guide/agents/articles/zoho-creator-mcp
        status: verified
      name: Zoho Creator
      slug: zoho-creator
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Application Development
      - Forms
      - Low-Code
      - No-Code
      tier: declared
      url: /providers/zoho-creator/
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Grafana
      - Redash
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        source: https://github.com/PagerDuty/pagerduty-mcp-server
        status: verified
      name: PagerDuty
      slug: pagerduty
      sources:
      - https://github.com/getredash/redash/tree/master/redash/destinations
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Alerting
      - DevOps
      - Incident Management
      - On-Call Management
      tier: observed
      url: /providers/pagerduty/
    - agent_band: agent-aware
      agent_readiness: 26.5
      apps:
      - Grafana
      band: developing
      in_catalog: true
      kin_score: 48.6
      mcp:
        status: none
      name: Opsgenie
      slug: opsgenie
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Alerts
      - Incident Management
      - Monitoring
      - On-Call
      tier: observed
      url: /providers/opsgenie/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Grafana
      band: emerging
      in_catalog: true
      kin_score: 18.1
      mcp:
        status: none
      name: Splunk On-Call (VictorOps)
      slug: victorops
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Alerting
      - DevOps
      - Incident Management
      - On-Call
      tier: observed
      url: /providers/victorops/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 47.0
      apps:
      - Grafana
      band: exemplar
      in_catalog: true
      kin_score: 71.3
      mcp:
        source: https://github.com/line/line-bot-mcp-server
        status: verified
      name: LINE
      slug: line
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Chatbots
      - Messaging
      - Mini Apps
      - Social Login
      tier: observed
      url: /providers/line/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Grafana
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
    - agent_band: human-only
      agent_readiness: 2.8
      apps:
      - Grafana
      band: thin
      in_catalog: true
      kin_score: 30.7
      mcp:
        status: none
      name: Threema
      slug: threema
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Company
      - Messaging
      - Privacy
      - Security
      tier: observed
      url: /providers/threema/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.7
      apps:
      - Grafana
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SNS
      slug: amazon-sns
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Messaging
      - Notification
      tier: observed
      url: /providers/amazon-sns/
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Grafana
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        status: none
      name: Pushover
      slug: pushover
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Alerts
      - Messaging
      - Notification
      - Push Notifications
      tier: observed
      url: /providers/pushover/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Redash
      band: emerging
      in_catalog: true
      kin_score: 11.9
      mcp:
        status: unchecked
      name: Yandex Disk
      slug: yandex-disk
      sources:
      - https://github.com/getredash/redash/tree/master/redash/query_runner
      status: profiled
      tags:
      - AI Features
      - Backup
      - Cloud Storage
      - File Sync
      tier: observed
      url: /providers/yandex-disk/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - Microsoft Power BI
      band: thin
      in_catalog: true
      kin_score: 37.1
      mcp:
        status: none
      name: SparkPost
      slug: sparkpost
      sources:
      - https://learn.microsoft.com/en-us/power-query/connectors/
      status: profiled
      tags:
      - Email
      - Email Delivery
      - Marketing Email
      - Transactional Email
      tier: declared
      url: /providers/sparkpost/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.8
      apps:
      - Grafana
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        status: none
      name: Apache Kafka
      slug: apache-kafka
      sources:
      - https://github.com/grafana/alerting/tree/main/receivers
      status: profiled
      tags:
      - Apache Kafka
      - Distributed Systems
      - Event Streaming
      - Messaging
      tier: observed
      url: /providers/apache-kafka/
  layer: common
summary:
  coverage_pct: 94.4
  declared_only: 33
  distinct_providers: 143
  in_catalog: 135
  mcp:
    documented: 3
    none: 38
    unchecked: 25
    verified: 73
  mcp_verified: 73
  mean_kin_score: 47.9
  observed: 110
  queued: 8
  reference_apps: 7
title: 'BI & Dashboards: application blueprint'
---
