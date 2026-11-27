---
app: Apache Superset
app_slug: apache-superset
app_url: https://github.com/apache/superset
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Alibaba Cloud (Hologres / MaxCompute)
  - Amazon Athena
  - Amazon Redshift
  - Apache Doris
  - Apache Drill
  - Apache Druid
  - Apache Hive
  - Apache Impala
  - Apache Kylin
  - Apache Pinot
  - Apache Spark SQL
  - Azure Data Explorer (Kusto)
  - ClickHouse
  - Databend
  - Databricks
  - Dremio
  - DuckDB
  - Exasol
  - Firebolt
  - Google BigQuery
  - Greenplum
  - IBM Netezza
  - MonetDB
  - Ocient
  - Presto (PrestoDB)
  - RisingWave
  - SAP HANA
  - SingleStore
  - Snowflake
  - StarRocks
  - Teradata
  - Trino
  - Vertica
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-939
  key: AE-939
  layer: domain
  name: Data Virtualization & Federation
  providers:
  - Denodo
  url: /capabilities/data-virtualization-federation/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: domain
  name: Search and Discovery Management
  providers:
  - Apache Solr
  - Elasticsearch
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Amazon Aurora
  - Amazon DynamoDB
  - Cloudflare D1
  - CockroachDB
  - Couchbase
  - CrateDB
  - Google Cloud Datastore
  - IBM Db2
  - MariaDB
  - Microsoft SQL Server
  - MongoDB
  - MySQL
  - OceanBase
  - Oracle Database
  - PostgreSQL
  - Sybase (SAP ASE)
  - TimescaleDB
  - YDB
  - YugabyteDB
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Apache IoTDB
  - Parseable
  - TDengine
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: common
  name: Spreadsheets & No-Code Databases
  providers:
  - Google Sheets
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: bi-dashboards
  name: BI & Dashboards
  url: /applications/bi-dashboards/
counts:
  declared: 0
  observed: 60
credits: []
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
  facts:
    agent_band: human-only
    agent_readiness: 3.4
    band: emerging
    in_catalog: true
    kin_score: 17.9
    mcp: &id001
      source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
      status: verified
    slug: alibaba
    status: profiled
    tags: &id002
    - Cloud
    - Cloud Computing
    - Commerce
    - E-Commerce
    url: /providers/alibaba/
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
  facts:
    agent_band: agent-native
    agent_readiness: 44.8
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-athena
    status: profiled
    tags: &id004
    - Amazon Athena
    - Analytics
    - SQL
    - Serverless
    url: /providers/amazon-athena/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: documented
    slug: amazon-aurora
    status: profiled
    tags: &id006
    - Amazon Aurora
    - MySQL
    - PostgreSQL
    - Relational Database
    url: /providers/amazon-aurora/
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
  facts:
    agent_band: agent-native
    agent_readiness: 41.0
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id007
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-dynamodb
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Database
    - Document Store
    - Key-Value Store
    url: /providers/amazon-dynamodb/
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
  facts:
    agent_band: agent-native
    agent_readiness: 44.5
    band: exemplar
    in_catalog: true
    kin_score: 75.1
    mcp: &id009
      source: https://github.com/awslabs/mcp/tree/main/src/redshift-mcp-server
      status: verified
    slug: amazon-redshift
    status: profiled
    tags: &id010
    - Analytics
    - Big Data
    - Cloud
    - Data Lake
    url: /providers/amazon-redshift/
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
  facts:
    agent_band: human-only
    agent_readiness: 1.8
    band: developing
    in_catalog: true
    kin_score: 39.3
    mcp: &id011
      source: https://github.com/apache/doris-mcp-server
      status: verified
    slug: apache-doris
    status: profiled
    tags: &id012
    - Analytics
    - Apache
    - Database
    - Lakehouse
    url: /providers/apache-doris/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 12.4
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id013
      status: unchecked
    slug: apache-drill
    status: profiled
    tags: &id014
    - Data Analytics
    - Distributed Query
    - Hadoop
    - SQL Engine
    url: /providers/apache-drill/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 38.7
    mcp: &id015
      status: none
    slug: apache-druid
    status: profiled
    tags: &id016
    - Analytics
    - Apache
    - Database
    - Kafka
    url: /providers/apache-druid/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.8
    band: thin
    in_catalog: true
    kin_score: 32.9
    mcp: &id017
      status: none
    slug: apache-hive
    status: profiled
    tags: &id018
    - Apache
    - Big Data
    - Data Warehouse
    - ETL
    url: /providers/apache-hive/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 13.8
    mcp: &id019
      status: unchecked
    slug: apache-impala
    status: profiled
    tags: &id020
    - Analytics
    - Company
    - Hadoop
    - Open Source
    url: /providers/apache-impala/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.3
    band: thin
    in_catalog: true
    kin_score: 28.5
    mcp: &id021
      status: unchecked
    slug: apache-iotdb
    status: profiled
    tags: &id022
    - Company
    - Database
    - IoT
    - Time Series
    url: /providers/apache-iotdb/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.9
    band: thin
    in_catalog: true
    kin_score: 37.2
    mcp: &id023
      status: none
    slug: apache-kylin
    status: profiled
    tags: &id024
    - Analytics
    - Big Data
    - OLAP
    - cube
    url: /providers/apache-kylin/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: emerging
    in_catalog: true
    kin_score: 20.5
    mcp: &id025
      status: none
    slug: apache-pinot
    status: profiled
    tags: &id026
    - Analytics
    - Database
    - Low Latency
    - OLAP
    url: /providers/apache-pinot/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: developing
    in_catalog: true
    kin_score: 40.6
    mcp: &id027
      source: https://github.com/apache/solr-mcp
      status: verified
    slug: apache-solr
    status: profiled
    tags: &id028
    - Enterprise Search
    - Full-Text Search
    - Lucene
    - Search
    url: /providers/apache-solr/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 38.3
    mcp: &id029
      status: none
    slug: apache-spark
    status: profiled
    tags: &id030
    - Analytics
    - Big Data
    - Distributed Computing
    - Machine Learning
    url: /providers/apache-spark/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id031
      status: unchecked
    slug: azure-data-explorer
    status: queued for profiling
    tags: &id032 []
    url: null
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 77.1
    mcp: &id033
      source: https://github.com/ClickHouse/mcp-clickhouse
      status: verified
    slug: clickhouse
    status: profiled
    tags: &id034
    - Analytics
    - ClickHouse
    - Cloud Database
    - Column-Oriented
    url: /providers/clickhouse/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.3
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id035
      source: https://github.com/cloudflare/mcp-server-cloudflare
      status: verified
    slug: cloudflare-d1
    status: profiled
    tags: &id036
    - Database
    - Edge Computing
    - SQLite
    - Serverless
    url: /providers/cloudflare-d1/
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
  facts:
    agent_band: agent-native
    agent_readiness: 49.9
    band: exemplar
    in_catalog: true
    kin_score: 79.2
    mcp: &id037
      source: https://github.com/cockroachdb/cockroachdb-mcp-server
      status: verified
    slug: cockroach-labs
    status: profiled
    tags: &id038
    - Cloud
    - Cluster Management
    - Database
    - Distributed SQL
    url: /providers/cockroach-labs/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.4
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id039
      source: https://github.com/couchbase/mcp-server-couchbase
      status: verified
    slug: couchbase
    status: profiled
    tags: &id040
    - Analytics
    - App Services
    - Backup
    - Capella
    url: /providers/couchbase/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 8.7
    band: developing
    in_catalog: true
    kin_score: 47.8
    mcp: &id041
      source: https://github.com/crate/cratedb-mcp
      status: verified
    slug: crate-io
    status: profiled
    tags: &id042
    - Company
    - Database
    - Distributed Database
    - SQL
    url: /providers/crate-io/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.2
    band: developing
    in_catalog: true
    kin_score: 42.4
    mcp: &id043
      status: unchecked
    slug: databend
    status: profiled
    tags: &id044
    - Cloud
    - Company
    - Data Warehouse
    - Open Source
    url: /providers/databend/
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
  facts:
    agent_band: agent-native
    agent_readiness: 65.5
    band: strong
    in_catalog: true
    kin_score: 58.7
    mcp: &id045
      source: https://docs.databricks.com/aws/en/generative-ai/mcp/
      status: verified
    slug: databricks
    status: profiled
    tags: &id046
    - Analytics
    - Artificial Intelligence
    - Cleanroom
    - Databricks
    url: /providers/databricks/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.5
    band: thin
    in_catalog: true
    kin_score: 34.7
    mcp: &id047
      source: https://community.denodo.com/docs/html/document/denodoconnects/9.1/en/Denodo%20MCP%20Server%20-%20User%20Manual
      status: verified
    slug: denodo
    status: profiled
    tags: &id048
    - Data Catalog
    - Data Fabric
    - Data Mesh
    - Data Virtualization
    url: /providers/denodo/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 5.8
    band: developing
    in_catalog: true
    kin_score: 51.5
    mcp: &id049
      source: https://github.com/dremio/dremio-mcp
      status: verified
    slug: dremio
    status: profiled
    tags: &id050
    - Analytics
    - Company
    - Data Lakehouse
    - SQL Query Engine
    url: /providers/dremio/
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
  facts:
    agent_band: human-only
    agent_readiness: 1.3
    band: thin
    in_catalog: true
    kin_score: 27.8
    mcp: &id051
      status: none
    slug: duckdb
    status: profiled
    tags: &id052
    - Analytics
    - Database
    - Embedded
    - OLAP
    url: /providers/duckdb/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.5
    band: exemplar
    in_catalog: true
    kin_score: 78.4
    mcp: &id053
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id054
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 15.5
    band: emerging
    in_catalog: true
    kin_score: 22.6
    mcp: &id055
      status: unchecked
    slug: exasol
    status: profiled
    tags: &id056
    - Analytics
    - Artificial Intelligence
    - Company
    - Database
    url: /providers/exasol/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.4
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id057
      source: https://github.com/firebolt-db/mcp-server
      status: verified
    slug: firebolt
    status: profiled
    tags: &id058
    - Analytics
    - Cloud
    - Data Warehouse
    - SQL
    url: /providers/firebolt/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id059
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id060
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.6
    band: strong
    in_catalog: true
    kin_score: 64.1
    mcp: &id061
      status: none
    slug: google-cloud-datastore
    status: profiled
    tags: &id062
    - Database
    - Document Database
    - Google Cloud
    - NoSQL
    url: /providers/google-cloud-datastore/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id063
      status: none
    slug: google-sheets
    status: profiled
    tags: &id064
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id065
      status: unchecked
    slug: greenplum
    status: queued for profiling
    tags: &id066 []
    url: null
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.0
    mcp: &id067
      status: none
    slug: ibm-db2
    status: profiled
    tags: &id068
    - Cloud Database
    - Database
    - Relational Database
    - SQL
    url: /providers/ibm-db2/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.6
    mcp: &id069
      status: none
    slug: netezza
    status: profiled
    tags: &id070
    - Analytics
    - Company
    - Data Warehouse
    - Database
    url: /providers/netezza/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.8
    band: developing
    in_catalog: true
    kin_score: 41.2
    mcp: &id071
      status: unchecked
    slug: mariadb
    status: profiled
    tags: &id072
    - Cloud
    - Database
    - Enterprise
    - Open Source
    url: /providers/mariadb/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: exemplar
    in_catalog: true
    kin_score: 67.0
    mcp: &id073
      source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
      status: verified
    slug: microsoft-sql-server
    status: profiled
    tags: &id074
    - Cloud
    - Data Management
    - Database
    - Enterprise
    url: /providers/microsoft-sql-server/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 9.8
    mcp: &id075
      status: unchecked
    slug: monetdb
    status: profiled
    tags: &id076
    - Analytics
    - Database
    - Open Source
    - SQL
    url: /providers/monetdb/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 59.1
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id077
      source: https://github.com/mongodb-js/mongodb-mcp-server
      status: verified
    slug: mongodb
    status: profiled
    tags: &id078
    - Cloud Database
    - Database
    - Document Database
    - NoSQL
    url: /providers/mongodb/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id079
      status: none
    slug: mysql
    status: profiled
    tags: &id080
    - Database
    - Open Source
    - RDBMS
    - Relational Database
    url: /providers/mysql/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 12.7
    band: emerging
    in_catalog: true
    kin_score: 24.7
    mcp: &id081
      status: unchecked
    slug: oceanbase
    status: profiled
    tags: &id082
    - AI Native Search
    - Cloud Database
    - Distributed Database
    - Open Source Database
    url: /providers/oceanbase/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 32.8
    band: strong
    in_catalog: true
    kin_score: 58.0
    mcp: &id083
      source: https://docs.ocient.com/ocient-mcp-server
      status: verified
    slug: ocient
    status: profiled
    tags: &id084
    - Analytics
    - Company
    - Data
    - Data Warehouse
    url: /providers/ocient/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 59.8
    band: exemplar
    in_catalog: true
    kin_score: 70.4
    mcp: &id085
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id086
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: developing
    in_catalog: true
    kin_score: 44.5
    mcp: &id087
      status: unchecked
    slug: parseable
    status: profiled
    tags: &id088
    - Cloud
    - Observability
    - OpenTelemetry
    - Rust
    url: /providers/parseable/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id089
      status: none
    slug: postgresql
    status: profiled
    tags: &id090
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.2
    band: thin
    in_catalog: true
    kin_score: 34.3
    mcp: &id091
      status: none
    slug: presto-foundation
    status: profiled
    tags: &id092
    - Analytics
    - Big Data
    - Distributed SQL
    - Linux Foundation
    url: /providers/presto-foundation/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 30.4
    mcp: &id093
      source: https://github.com/risingwavelabs/risingwave-mcp
      status: verified
    slug: risingwave
    status: profiled
    tags: &id094
    - Database
    - Real-Time
    - SQL
    - Streaming
    url: /providers/risingwave/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: developing
    in_catalog: true
    kin_score: 44.8
    mcp: &id095
      status: none
    slug: sap-hana
    status: profiled
    tags: &id096
    - Analytics
    - Cloud
    - Database
    - Enterprise
    url: /providers/sap-hana/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.6
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id097
      source: https://github.com/singlestore-labs/mcp-server-singlestore
      status: verified
    slug: singlestore
    status: profiled
    tags: &id098
    - Analytics
    - Cloud
    - Database
    - SQL
    url: /providers/singlestore/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id099
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id100
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
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
  facts:
    agent_band: agent-native
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 82.3
    mcp: &id101
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id102
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.1
    band: thin
    in_catalog: true
    kin_score: 29.1
    mcp: &id103
      source: https://github.com/StarRocks/mcp-server-starrocks
      status: verified
    slug: starrocks
    status: profiled
    tags: &id104
    - Lakehouse
    - OLAP
    - Open Source
    - SQL
    url: /providers/starrocks/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.7
    band: developing
    in_catalog: true
    kin_score: 41.3
    mcp: &id105
      status: unknown
    slug: sybase
    status: profiled
    tags: &id106
    - Database
    - Enterprise
    - SAP
    - SQL
    url: /providers/sybase/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 15.7
    band: thin
    in_catalog: true
    kin_score: 28.0
    mcp: &id107
      status: unchecked
    slug: tdengine
    status: profiled
    tags: &id108
    - AI Platform
    - Company
    - Industrial IoT
    - Time Series Database
    url: /providers/tdengine/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 52.8
    mcp: &id109
      source: https://github.com/Teradata/teradata-mcp-server
      status: verified
    slug: teradata
    status: profiled
    tags: &id110
    - Analytics
    - Cloud
    - Data Management
    - Data Warehousing
    url: /providers/teradata/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.3
    band: exemplar
    in_catalog: true
    kin_score: 70.6
    mcp: &id111
      source: https://www.tigerdata.com/docs/reference/tiger-cloud/tiger-mcp
      status: verified
    slug: timescale
    status: profiled
    tags: &id112
    - Company
    - Database
    - PostgreSQL
    - Time Series
    url: /providers/timescale/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.3
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id113
      status: none
    slug: trino
    status: profiled
    tags: &id114
    - Analytics
    - Big Data
    - Distributed SQL
    - MySQL
    url: /providers/trino/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: emerging
    in_catalog: true
    kin_score: 22.9
    mcp: &id115
      status: none
    slug: vertica
    status: profiled
    tags: &id116
    - Analytics Database
    - Data Lakehouse
    - Data Warehouse
    - Database
    url: /providers/vertica/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 12.7
    band: emerging
    in_catalog: true
    kin_score: 22.5
    mcp: &id117
      status: unchecked
    slug: ydb
    status: profiled
    tags: &id118
    - Database
    - Distributed
    - Open Source
    - SQL
    url: /providers/ydb/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.8
    band: exemplar
    in_catalog: true
    kin_score: 67.3
    mcp: &id119
      source: https://github.com/yugabyte/yugabytedb-mcp-server
      status: verified
    slug: yugabyte
    status: profiled
    tags: &id120
    - Company
    - Database
    - Distributed SQL
    - PostgreSQL
    url: /providers/yugabyte/
  layer: common
  name: YugabyteDB
  provider: yugabyte
  says: ships the YugabyteDB SDK or integration code
  source: https://github.com/apache/superset/tree/master/superset/db_engine_specs
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/bi-dashboards/apache-superset/
providers:
- agent_band: human-only
  agent_readiness: 3.4
  band: emerging
  in_catalog: true
  kin_score: 17.9
  mcp: *id001
  name: Alibaba Cloud (Hologres / MaxCompute)
  slug: alibaba
  status: profiled
  tags: *id002
  url: /providers/alibaba/
- agent_band: agent-native
  agent_readiness: 44.8
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id003
  name: Amazon Athena
  slug: amazon-athena
  status: profiled
  tags: *id004
  url: /providers/amazon-athena/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id005
  name: Amazon Aurora
  slug: amazon-aurora
  status: profiled
  tags: *id006
  url: /providers/amazon-aurora/
- agent_band: agent-native
  agent_readiness: 41.0
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id007
  name: Amazon DynamoDB
  slug: amazon-dynamodb
  status: profiled
  tags: *id008
  url: /providers/amazon-dynamodb/
- agent_band: agent-native
  agent_readiness: 44.5
  band: exemplar
  in_catalog: true
  kin_score: 75.1
  mcp: *id009
  name: Amazon Redshift
  slug: amazon-redshift
  status: profiled
  tags: *id010
  url: /providers/amazon-redshift/
- agent_band: human-only
  agent_readiness: 1.8
  band: developing
  in_catalog: true
  kin_score: 39.3
  mcp: *id011
  name: Apache Doris
  slug: apache-doris
  status: profiled
  tags: *id012
  url: /providers/apache-doris/
- agent_band: agent-aware
  agent_readiness: 12.4
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id013
  name: Apache Drill
  slug: apache-drill
  status: profiled
  tags: *id014
  url: /providers/apache-drill/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 38.7
  mcp: *id015
  name: Apache Druid
  slug: apache-druid
  status: profiled
  tags: *id016
  url: /providers/apache-druid/
- agent_band: agent-aware
  agent_readiness: 16.8
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id017
  name: Apache Hive
  slug: apache-hive
  status: profiled
  tags: *id018
  url: /providers/apache-hive/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 13.8
  mcp: *id019
  name: Apache Impala
  slug: apache-impala
  status: profiled
  tags: *id020
  url: /providers/apache-impala/
- agent_band: agent-aware
  agent_readiness: 19.3
  band: thin
  in_catalog: true
  kin_score: 28.5
  mcp: *id021
  name: Apache IoTDB
  slug: apache-iotdb
  status: profiled
  tags: *id022
  url: /providers/apache-iotdb/
- agent_band: agent-aware
  agent_readiness: 24.9
  band: thin
  in_catalog: true
  kin_score: 37.2
  mcp: *id023
  name: Apache Kylin
  slug: apache-kylin
  status: profiled
  tags: *id024
  url: /providers/apache-kylin/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: emerging
  in_catalog: true
  kin_score: 20.5
  mcp: *id025
  name: Apache Pinot
  slug: apache-pinot
  status: profiled
  tags: *id026
  url: /providers/apache-pinot/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: developing
  in_catalog: true
  kin_score: 40.6
  mcp: *id027
  name: Apache Solr
  slug: apache-solr
  status: profiled
  tags: *id028
  url: /providers/apache-solr/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 38.3
  mcp: *id029
  name: Apache Spark SQL
  slug: apache-spark
  status: profiled
  tags: *id030
  url: /providers/apache-spark/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id031
  name: Azure Data Explorer (Kusto)
  slug: azure-data-explorer
  status: queued for profiling
  tags: *id032
  url: null
- agent_band: agent-ready
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 77.1
  mcp: *id033
  name: ClickHouse
  slug: clickhouse
  status: profiled
  tags: *id034
  url: /providers/clickhouse/
- agent_band: agent-ready
  agent_readiness: 30.3
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id035
  name: Cloudflare D1
  slug: cloudflare-d1
  status: profiled
  tags: *id036
  url: /providers/cloudflare-d1/
- agent_band: agent-native
  agent_readiness: 49.9
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id037
  name: CockroachDB
  slug: cockroach-labs
  status: profiled
  tags: *id038
  url: /providers/cockroach-labs/
- agent_band: agent-aware
  agent_readiness: 28.4
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id039
  name: Couchbase
  slug: couchbase
  status: profiled
  tags: *id040
  url: /providers/couchbase/
- agent_band: agent-aware
  agent_readiness: 8.7
  band: developing
  in_catalog: true
  kin_score: 47.8
  mcp: *id041
  name: CrateDB
  slug: crate-io
  status: profiled
  tags: *id042
  url: /providers/crate-io/
- agent_band: agent-aware
  agent_readiness: 23.2
  band: developing
  in_catalog: true
  kin_score: 42.4
  mcp: *id043
  name: Databend
  slug: databend
  status: profiled
  tags: *id044
  url: /providers/databend/
- agent_band: agent-native
  agent_readiness: 65.5
  band: strong
  in_catalog: true
  kin_score: 58.7
  mcp: *id045
  name: Databricks
  slug: databricks
  status: profiled
  tags: *id046
  url: /providers/databricks/
- agent_band: agent-aware
  agent_readiness: 16.5
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id047
  name: Denodo
  slug: denodo
  status: profiled
  tags: *id048
  url: /providers/denodo/
- agent_band: agent-aware
  agent_readiness: 5.8
  band: developing
  in_catalog: true
  kin_score: 51.5
  mcp: *id049
  name: Dremio
  slug: dremio
  status: profiled
  tags: *id050
  url: /providers/dremio/
- agent_band: human-only
  agent_readiness: 1.3
  band: thin
  in_catalog: true
  kin_score: 27.8
  mcp: *id051
  name: DuckDB
  slug: duckdb
  status: profiled
  tags: *id052
  url: /providers/duckdb/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id053
  name: Elasticsearch
  slug: elastic
  status: profiled
  tags: *id054
  url: /providers/elastic/
- agent_band: agent-aware
  agent_readiness: 15.5
  band: emerging
  in_catalog: true
  kin_score: 22.6
  mcp: *id055
  name: Exasol
  slug: exasol
  status: profiled
  tags: *id056
  url: /providers/exasol/
- agent_band: agent-ready
  agent_readiness: 29.4
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id057
  name: Firebolt
  slug: firebolt
  status: profiled
  tags: *id058
  url: /providers/firebolt/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id059
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id060
  url: /providers/google-bigquery/
- agent_band: agent-ready
  agent_readiness: 36.6
  band: strong
  in_catalog: true
  kin_score: 64.1
  mcp: *id061
  name: Google Cloud Datastore
  slug: google-cloud-datastore
  status: profiled
  tags: *id062
  url: /providers/google-cloud-datastore/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id063
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id064
  url: /providers/google-sheets/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id065
  name: Greenplum
  slug: greenplum
  status: queued for profiling
  tags: *id066
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.0
  mcp: *id067
  name: IBM Db2
  slug: ibm-db2
  status: profiled
  tags: *id068
  url: /providers/ibm-db2/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.6
  mcp: *id069
  name: IBM Netezza
  slug: netezza
  status: profiled
  tags: *id070
  url: /providers/netezza/
- agent_band: agent-aware
  agent_readiness: 24.8
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id071
  name: MariaDB
  slug: mariadb
  status: profiled
  tags: *id072
  url: /providers/mariadb/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 67.0
  mcp: *id073
  name: Microsoft SQL Server
  slug: microsoft-sql-server
  status: profiled
  tags: *id074
  url: /providers/microsoft-sql-server/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 9.8
  mcp: *id075
  name: MonetDB
  slug: monetdb
  status: profiled
  tags: *id076
  url: /providers/monetdb/
- agent_band: agent-ready
  agent_readiness: 59.1
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id077
  name: MongoDB
  slug: mongodb
  status: profiled
  tags: *id078
  url: /providers/mongodb/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id079
  name: MySQL
  slug: mysql
  status: profiled
  tags: *id080
  url: /providers/mysql/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: emerging
  in_catalog: true
  kin_score: 24.7
  mcp: *id081
  name: OceanBase
  slug: oceanbase
  status: profiled
  tags: *id082
  url: /providers/oceanbase/
- agent_band: agent-ready
  agent_readiness: 32.8
  band: strong
  in_catalog: true
  kin_score: 58.0
  mcp: *id083
  name: Ocient
  slug: ocient
  status: profiled
  tags: *id084
  url: /providers/ocient/
- agent_band: agent-ready
  agent_readiness: 59.8
  band: exemplar
  in_catalog: true
  kin_score: 70.4
  mcp: *id085
  name: Oracle Database
  slug: oracle
  status: profiled
  tags: *id086
  url: /providers/oracle/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: developing
  in_catalog: true
  kin_score: 44.5
  mcp: *id087
  name: Parseable
  slug: parseable
  status: profiled
  tags: *id088
  url: /providers/parseable/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id089
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id090
  url: /providers/postgresql/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: thin
  in_catalog: true
  kin_score: 34.3
  mcp: *id091
  name: Presto (PrestoDB)
  slug: presto-foundation
  status: profiled
  tags: *id092
  url: /providers/presto-foundation/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id093
  name: RisingWave
  slug: risingwave
  status: profiled
  tags: *id094
  url: /providers/risingwave/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 44.8
  mcp: *id095
  name: SAP HANA
  slug: sap-hana
  status: profiled
  tags: *id096
  url: /providers/sap-hana/
- agent_band: agent-ready
  agent_readiness: 31.6
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id097
  name: SingleStore
  slug: singlestore
  status: profiled
  tags: *id098
  url: /providers/singlestore/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id099
  name: Slack
  slug: slack
  status: profiled
  tags: *id100
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 82.3
  mcp: *id101
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id102
  url: /providers/snowflake/
- agent_band: human-only
  agent_readiness: 3.1
  band: thin
  in_catalog: true
  kin_score: 29.1
  mcp: *id103
  name: StarRocks
  slug: starrocks
  status: profiled
  tags: *id104
  url: /providers/starrocks/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: developing
  in_catalog: true
  kin_score: 41.3
  mcp: *id105
  name: Sybase (SAP ASE)
  slug: sybase
  status: profiled
  tags: *id106
  url: /providers/sybase/
- agent_band: agent-aware
  agent_readiness: 15.7
  band: thin
  in_catalog: true
  kin_score: 28.0
  mcp: *id107
  name: TDengine
  slug: tdengine
  status: profiled
  tags: *id108
  url: /providers/tdengine/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 52.8
  mcp: *id109
  name: Teradata
  slug: teradata
  status: profiled
  tags: *id110
  url: /providers/teradata/
- agent_band: agent-ready
  agent_readiness: 37.3
  band: exemplar
  in_catalog: true
  kin_score: 70.6
  mcp: *id111
  name: TimescaleDB
  slug: timescale
  status: profiled
  tags: *id112
  url: /providers/timescale/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id113
  name: Trino
  slug: trino
  status: profiled
  tags: *id114
  url: /providers/trino/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: emerging
  in_catalog: true
  kin_score: 22.9
  mcp: *id115
  name: Vertica
  slug: vertica
  status: profiled
  tags: *id116
  url: /providers/vertica/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: emerging
  in_catalog: true
  kin_score: 22.5
  mcp: *id117
  name: YDB
  slug: ydb
  status: profiled
  tags: *id118
  url: /providers/ydb/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: exemplar
  in_catalog: true
  kin_score: 67.3
  mcp: *id119
  name: YugabyteDB
  slug: yugabyte
  status: profiled
  tags: *id120
  url: /providers/yugabyte/
siblings:
- name: Grafana
  rows: 32
  url: /applications/bi-dashboards/grafana/
- name: Lightdash
  rows: 11
  url: /applications/bi-dashboards/lightdash/
- name: Looker
  rows: 34
  url: /applications/bi-dashboards/looker/
- name: Metabase
  rows: 19
  url: /applications/bi-dashboards/metabase/
- name: Microsoft Power BI
  rows: 58
  url: /applications/bi-dashboards/microsoft-power-bi/
- name: Redash
  rows: 62
  url: /applications/bi-dashboards/redash/
sitemap: true
title: 'Apache Superset: BI & Dashboards reference app'
---
