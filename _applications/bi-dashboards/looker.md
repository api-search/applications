---
app: Looker
app_slug: looker
app_url: https://cloud.google.com/looker
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Actian (Avalanche / Vector)
  - Amazon Athena
  - Amazon Redshift
  - Apache Druid
  - Apache Hive
  - Apache Impala
  - Apache Spark SQL
  - Azure Synapse Analytics
  - ClickHouse
  - Databricks
  - Dremio
  - Exasol
  - Google BigQuery
  - Greenplum
  - IBM Netezza
  - Presto (PrestoDB)
  - SAP HANA
  - SingleStore
  - Snowflake
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
  - Data Virtuality
  - Denodo
  url: /capabilities/data-virtualization-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - AlloyDB for PostgreSQL
  - Amazon Aurora
  - Google Cloud Spanner
  - Google Cloud SQL
  - MariaDB
  - Microsoft SQL Server
  - MongoDB
  - MySQL
  - Oracle Database
  - PostgreSQL
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: bi-dashboards
  name: BI & Dashboards
  url: /applications/bi-dashboards/
counts:
  declared: 34
  observed: 0
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.8
    band: strong
    in_catalog: true
    kin_score: 60.7
    mcp: &id001
      source: https://docs.actian.com/mcp-server/
      status: verified
    slug: actian
    status: profiled
    tags: &id002
    - Analytics
    - Company
    - Data
    - Integration
    url: /providers/actian/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id003
      status: unchecked
    slug: google-alloydb
    status: queued for profiling
    tags: &id004 []
    url: null
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
  facts:
    agent_band: agent-native
    agent_readiness: 44.8
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-athena
    status: profiled
    tags: &id006
    - Amazon Athena
    - Analytics
    - SQL
    - Serverless
    url: /providers/amazon-athena/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id007
      source: https://github.com/awslabs/mcp
      status: documented
    slug: amazon-aurora
    status: profiled
    tags: &id008
    - Amazon Aurora
    - MySQL
    - PostgreSQL
    - Relational Database
    url: /providers/amazon-aurora/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 38.7
    mcp: &id011
      status: none
    slug: apache-druid
    status: profiled
    tags: &id012
    - Analytics
    - Apache
    - Database
    - Kafka
    url: /providers/apache-druid/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.8
    band: thin
    in_catalog: true
    kin_score: 32.9
    mcp: &id013
      status: none
    slug: apache-hive
    status: profiled
    tags: &id014
    - Apache
    - Big Data
    - Data Warehouse
    - ETL
    url: /providers/apache-hive/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 13.8
    mcp: &id015
      status: unchecked
    slug: apache-impala
    status: profiled
    tags: &id016
    - Analytics
    - Company
    - Hadoop
    - Open Source
    url: /providers/apache-impala/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 38.3
    mcp: &id017
      status: none
    slug: apache-spark
    status: profiled
    tags: &id018
    - Analytics
    - Big Data
    - Distributed Computing
    - Machine Learning
    url: /providers/apache-spark/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.8
    band: strong
    in_catalog: true
    kin_score: 62.9
    mcp: &id019
      status: none
    slug: microsoft-azure-synapse-analytics
    status: profiled
    tags: &id020
    - Analytics
    - Apache Spark
    - Big Data
    - Data Integration
    url: /providers/microsoft-azure-synapse-analytics/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 77.1
    mcp: &id021
      source: https://github.com/ClickHouse/mcp-clickhouse
      status: verified
    slug: clickhouse
    status: profiled
    tags: &id022
    - Analytics
    - ClickHouse
    - Cloud Database
    - Column-Oriented
    url: /providers/clickhouse/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id023
      status: unchecked
    slug: data-virtuality
    status: queued for profiling
    tags: &id024 []
    url: null
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
  facts:
    agent_band: agent-native
    agent_readiness: 65.5
    band: strong
    in_catalog: true
    kin_score: 58.7
    mcp: &id025
      source: https://docs.databricks.com/aws/en/generative-ai/mcp/
      status: verified
    slug: databricks
    status: profiled
    tags: &id026
    - Analytics
    - Artificial Intelligence
    - Cleanroom
    - Databricks
    url: /providers/databricks/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.5
    band: thin
    in_catalog: true
    kin_score: 34.7
    mcp: &id027
      source: https://community.denodo.com/docs/html/document/denodoconnects/9.1/en/Denodo%20MCP%20Server%20-%20User%20Manual
      status: verified
    slug: denodo
    status: profiled
    tags: &id028
    - Data Catalog
    - Data Fabric
    - Data Mesh
    - Data Virtualization
    url: /providers/denodo/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 5.8
    band: developing
    in_catalog: true
    kin_score: 51.5
    mcp: &id029
      source: https://github.com/dremio/dremio-mcp
      status: verified
    slug: dremio
    status: profiled
    tags: &id030
    - Analytics
    - Company
    - Data Lakehouse
    - SQL Query Engine
    url: /providers/dremio/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 15.5
    band: emerging
    in_catalog: true
    kin_score: 22.6
    mcp: &id031
      status: unchecked
    slug: exasol
    status: profiled
    tags: &id032
    - Analytics
    - Artificial Intelligence
    - Company
    - Database
    url: /providers/exasol/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id033
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id034
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id035
      source: https://github.com/googleapis/mcp-toolbox
      status: verified
    slug: google-cloud-spanner
    status: profiled
    tags: &id036
    - Database
    - Distributed
    - Google Cloud
    - Relational
    url: /providers/google-cloud-spanner/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.9
    band: strong
    in_catalog: true
    kin_score: 65.9
    mcp: &id037
      source: https://sqladmin.googleapis.com/mcp
      status: verified
    slug: google-cloud-sql
    status: profiled
    tags: &id038
    - Database
    - Google Cloud
    - MySQL
    - PostgreSQL
    url: /providers/google-cloud-sql/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id039
      status: unchecked
    slug: greenplum
    status: queued for profiling
    tags: &id040 []
    url: null
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.6
    mcp: &id041
      status: none
    slug: netezza
    status: profiled
    tags: &id042
    - Analytics
    - Company
    - Data Warehouse
    - Database
    url: /providers/netezza/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.8
    band: developing
    in_catalog: true
    kin_score: 41.2
    mcp: &id043
      status: unchecked
    slug: mariadb
    status: profiled
    tags: &id044
    - Cloud
    - Database
    - Enterprise
    - Open Source
    url: /providers/mariadb/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: exemplar
    in_catalog: true
    kin_score: 67.0
    mcp: &id045
      source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
      status: verified
    slug: microsoft-sql-server
    status: profiled
    tags: &id046
    - Cloud
    - Data Management
    - Database
    - Enterprise
    url: /providers/microsoft-sql-server/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 59.1
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id047
      source: https://github.com/mongodb-js/mongodb-mcp-server
      status: verified
    slug: mongodb
    status: profiled
    tags: &id048
    - Cloud Database
    - Database
    - Document Database
    - NoSQL
    url: /providers/mongodb/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id049
      status: none
    slug: mysql
    status: profiled
    tags: &id050
    - Database
    - Open Source
    - RDBMS
    - Relational Database
    url: /providers/mysql/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 59.8
    band: exemplar
    in_catalog: true
    kin_score: 70.4
    mcp: &id051
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id052
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id053
      status: none
    slug: postgresql
    status: profiled
    tags: &id054
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.2
    band: thin
    in_catalog: true
    kin_score: 34.3
    mcp: &id055
      status: none
    slug: presto-foundation
    status: profiled
    tags: &id056
    - Analytics
    - Big Data
    - Distributed SQL
    - Linux Foundation
    url: /providers/presto-foundation/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: developing
    in_catalog: true
    kin_score: 44.8
    mcp: &id057
      status: none
    slug: sap-hana
    status: profiled
    tags: &id058
    - Analytics
    - Cloud
    - Database
    - Enterprise
    url: /providers/sap-hana/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.6
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id059
      source: https://github.com/singlestore-labs/mcp-server-singlestore
      status: verified
    slug: singlestore
    status: profiled
    tags: &id060
    - Analytics
    - Cloud
    - Database
    - SQL
    url: /providers/singlestore/
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
  facts:
    agent_band: agent-native
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 82.3
    mcp: &id061
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id062
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 52.8
    mcp: &id063
      source: https://github.com/Teradata/teradata-mcp-server
      status: verified
    slug: teradata
    status: profiled
    tags: &id064
    - Analytics
    - Cloud
    - Data Management
    - Data Warehousing
    url: /providers/teradata/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.3
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id065
      status: none
    slug: trino
    status: profiled
    tags: &id066
    - Analytics
    - Big Data
    - Distributed SQL
    - MySQL
    url: /providers/trino/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: emerging
    in_catalog: true
    kin_score: 22.9
    mcp: &id067
      status: none
    slug: vertica
    status: profiled
    tags: &id068
    - Analytics Database
    - Data Lakehouse
    - Data Warehouse
    - Database
    url: /providers/vertica/
  layer: domain
  name: Vertica
  provider: vertica
  says: lists Vertica as an integration
  source: https://cloud.google.com/looker/docs/dialects
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/bi-dashboards/looker/
providers:
- agent_band: agent-ready
  agent_readiness: 43.8
  band: strong
  in_catalog: true
  kin_score: 60.7
  mcp: *id001
  name: Actian (Avalanche / Vector)
  slug: actian
  status: profiled
  tags: *id002
  url: /providers/actian/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: AlloyDB for PostgreSQL
  slug: google-alloydb
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: agent-native
  agent_readiness: 44.8
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id005
  name: Amazon Athena
  slug: amazon-athena
  status: profiled
  tags: *id006
  url: /providers/amazon-athena/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id007
  name: Amazon Aurora
  slug: amazon-aurora
  status: profiled
  tags: *id008
  url: /providers/amazon-aurora/
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
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 38.7
  mcp: *id011
  name: Apache Druid
  slug: apache-druid
  status: profiled
  tags: *id012
  url: /providers/apache-druid/
- agent_band: agent-aware
  agent_readiness: 16.8
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id013
  name: Apache Hive
  slug: apache-hive
  status: profiled
  tags: *id014
  url: /providers/apache-hive/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 13.8
  mcp: *id015
  name: Apache Impala
  slug: apache-impala
  status: profiled
  tags: *id016
  url: /providers/apache-impala/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 38.3
  mcp: *id017
  name: Apache Spark SQL
  slug: apache-spark
  status: profiled
  tags: *id018
  url: /providers/apache-spark/
- agent_band: agent-aware
  agent_readiness: 24.8
  band: strong
  in_catalog: true
  kin_score: 62.9
  mcp: *id019
  name: Azure Synapse Analytics
  slug: microsoft-azure-synapse-analytics
  status: profiled
  tags: *id020
  url: /providers/microsoft-azure-synapse-analytics/
- agent_band: agent-ready
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 77.1
  mcp: *id021
  name: ClickHouse
  slug: clickhouse
  status: profiled
  tags: *id022
  url: /providers/clickhouse/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id023
  name: Data Virtuality
  slug: data-virtuality
  status: queued for profiling
  tags: *id024
  url: null
- agent_band: agent-native
  agent_readiness: 65.5
  band: strong
  in_catalog: true
  kin_score: 58.7
  mcp: *id025
  name: Databricks
  slug: databricks
  status: profiled
  tags: *id026
  url: /providers/databricks/
- agent_band: agent-aware
  agent_readiness: 16.5
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id027
  name: Denodo
  slug: denodo
  status: profiled
  tags: *id028
  url: /providers/denodo/
- agent_band: agent-aware
  agent_readiness: 5.8
  band: developing
  in_catalog: true
  kin_score: 51.5
  mcp: *id029
  name: Dremio
  slug: dremio
  status: profiled
  tags: *id030
  url: /providers/dremio/
- agent_band: agent-aware
  agent_readiness: 15.5
  band: emerging
  in_catalog: true
  kin_score: 22.6
  mcp: *id031
  name: Exasol
  slug: exasol
  status: profiled
  tags: *id032
  url: /providers/exasol/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id033
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id034
  url: /providers/google-bigquery/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id035
  name: Google Cloud Spanner
  slug: google-cloud-spanner
  status: profiled
  tags: *id036
  url: /providers/google-cloud-spanner/
- agent_band: agent-ready
  agent_readiness: 36.9
  band: strong
  in_catalog: true
  kin_score: 65.9
  mcp: *id037
  name: Google Cloud SQL
  slug: google-cloud-sql
  status: profiled
  tags: *id038
  url: /providers/google-cloud-sql/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id039
  name: Greenplum
  slug: greenplum
  status: queued for profiling
  tags: *id040
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.6
  mcp: *id041
  name: IBM Netezza
  slug: netezza
  status: profiled
  tags: *id042
  url: /providers/netezza/
- agent_band: agent-aware
  agent_readiness: 24.8
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id043
  name: MariaDB
  slug: mariadb
  status: profiled
  tags: *id044
  url: /providers/mariadb/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 67.0
  mcp: *id045
  name: Microsoft SQL Server
  slug: microsoft-sql-server
  status: profiled
  tags: *id046
  url: /providers/microsoft-sql-server/
- agent_band: agent-ready
  agent_readiness: 59.1
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id047
  name: MongoDB
  slug: mongodb
  status: profiled
  tags: *id048
  url: /providers/mongodb/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id049
  name: MySQL
  slug: mysql
  status: profiled
  tags: *id050
  url: /providers/mysql/
- agent_band: agent-ready
  agent_readiness: 59.8
  band: exemplar
  in_catalog: true
  kin_score: 70.4
  mcp: *id051
  name: Oracle Database
  slug: oracle
  status: profiled
  tags: *id052
  url: /providers/oracle/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id053
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id054
  url: /providers/postgresql/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: thin
  in_catalog: true
  kin_score: 34.3
  mcp: *id055
  name: Presto (PrestoDB)
  slug: presto-foundation
  status: profiled
  tags: *id056
  url: /providers/presto-foundation/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 44.8
  mcp: *id057
  name: SAP HANA
  slug: sap-hana
  status: profiled
  tags: *id058
  url: /providers/sap-hana/
- agent_band: agent-ready
  agent_readiness: 31.6
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id059
  name: SingleStore
  slug: singlestore
  status: profiled
  tags: *id060
  url: /providers/singlestore/
- agent_band: agent-native
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 82.3
  mcp: *id061
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id062
  url: /providers/snowflake/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 52.8
  mcp: *id063
  name: Teradata
  slug: teradata
  status: profiled
  tags: *id064
  url: /providers/teradata/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id065
  name: Trino
  slug: trino
  status: profiled
  tags: *id066
  url: /providers/trino/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: emerging
  in_catalog: true
  kin_score: 22.9
  mcp: *id067
  name: Vertica
  slug: vertica
  status: profiled
  tags: *id068
  url: /providers/vertica/
siblings:
- name: Apache Superset
  rows: 60
  url: /applications/bi-dashboards/apache-superset/
- name: Grafana
  rows: 32
  url: /applications/bi-dashboards/grafana/
- name: Lightdash
  rows: 11
  url: /applications/bi-dashboards/lightdash/
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
title: 'Looker: BI & Dashboards reference app'
---
