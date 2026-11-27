---
app: Redash
app_slug: redash
app_url: https://github.com/getredash/redash
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Amazon Athena
  - Apache Drill
  - Apache Druid
  - Apache Hive
  - Apache Impala
  - Apache Kylin
  - Apache Phoenix
  - Apache Pinot
  - Azure Data Explorer (Kusto)
  - ClickHouse
  - Databend
  - Databricks
  - DuckDB
  - e6data
  - Exasol
  - Google BigQuery
  - IBM Netezza
  - Presto (PrestoDB)
  - RisingWave
  - SingleStore
  - Snowflake
  - Tinybird
  - Treasure Data
  - Trino
  - Vertica
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: domain
  name: Product Usage Analytics
  providers:
  - Google Analytics 4
  - Google Search Console
  - Yandex Metrica
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Asana
  - Jira (JQL)
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: domain
  name: Search and Discovery Management
  providers:
  - Amazon OpenSearch Service
  - Elasticsearch
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Yandex Disk
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: common
  name: Incident Response Management
  providers:
  - PagerDuty
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Chatwork
  - Discord
  - Google Chat
  - Mattermost
  - Microsoft Teams
  - Slack
  - Webex
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Apache Cassandra
  - Apache Ignite
  - ArangoDB
  - Cloudflare D1
  - Couchbase
  - Dgraph
  - Google Cloud Spanner
  - IBM Db2
  - Microsoft SQL Server
  - MongoDB
  - MySQL
  - Oracle Database
  - PostgreSQL
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Amazon CloudWatch
  - Datadog
  - Graphite
  - InfluxDB
  - Prometheus
  - Uptycs
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
  observed: 62
credits: []
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
  facts:
    agent_band: agent-native
    agent_readiness: 44.8
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-athena
    status: profiled
    tags: &id002
    - Amazon Athena
    - Analytics
    - SQL
    - Serverless
    url: /providers/amazon-athena/
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
  facts:
    agent_band: agent-native
    agent_readiness: 43.4
    band: exemplar
    in_catalog: true
    kin_score: 77.4
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-cloudwatch
    status: profiled
    tags: &id004
    - Amazon Web Services
    - CloudWatch
    - Monitoring
    - Observability
    url: /providers/amazon-cloudwatch/
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
  facts:
    agent_band: agent-native
    agent_readiness: 43.6
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id005
      source: https://docs.aws.amazon.com/opensearch-service/latest/developerguide/aws-mcp-server.html
      status: verified
    slug: amazon-opensearch
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Analytics
    - Elasticsearch
    - Search
    url: /providers/amazon-opensearch/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 37.7
    mcp: &id007
      status: none
    slug: cassandra
    status: profiled
    tags: &id008
    - Apache
    - Big Data
    - Database
    - Distributed
    url: /providers/cassandra/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 12.4
    band: thin
    in_catalog: true
    kin_score: 28.3
    mcp: &id009
      status: unchecked
    slug: apache-drill
    status: profiled
    tags: &id010
    - Data Analytics
    - Distributed Query
    - Hadoop
    - SQL Engine
    url: /providers/apache-drill/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.2
    band: developing
    in_catalog: true
    kin_score: 40.0
    mcp: &id015
      status: none
    slug: apache-ignite
    status: profiled
    tags: &id016
    - Caching
    - Compute Grid
    - Distributed Database
    - In-Memory
    url: /providers/apache-ignite/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 13.8
    mcp: &id017
      status: unchecked
    slug: apache-impala
    status: profiled
    tags: &id018
    - Analytics
    - Company
    - Hadoop
    - Open Source
    url: /providers/apache-impala/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.9
    band: thin
    in_catalog: true
    kin_score: 37.2
    mcp: &id019
      status: none
    slug: apache-kylin
    status: profiled
    tags: &id020
    - Analytics
    - Big Data
    - OLAP
    - cube
    url: /providers/apache-kylin/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 12.4
    band: thin
    in_catalog: true
    kin_score: 29.7
    mcp: &id021
      status: unchecked
    slug: apache-phoenix
    status: profiled
    tags: &id022
    - Company
    - Database
    - Open Source
    - SQL
    url: /providers/apache-phoenix/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: emerging
    in_catalog: true
    kin_score: 20.5
    mcp: &id023
      status: none
    slug: apache-pinot
    status: profiled
    tags: &id024
    - Analytics
    - Database
    - Low Latency
    - OLAP
    url: /providers/apache-pinot/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.8
    band: developing
    in_catalog: true
    kin_score: 52.3
    mcp: &id025
      status: none
    slug: arangodb
    status: profiled
    tags: &id026
    - Company
    - Database
    - Graph Database
    - Multi-Model Database
    url: /providers/arangodb/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 55.3
    band: exemplar
    in_catalog: true
    kin_score: 72.5
    mcp: &id027
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id028
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id029
      status: unchecked
    slug: azure-data-explorer
    status: queued for profiling
    tags: &id030 []
    url: null
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.9
    band: thin
    in_catalog: true
    kin_score: 30.1
    mcp: &id031
      source: https://github.com/chatwork/chatwork-mcp-server
      status: verified
    slug: chatwork
    status: profiled
    tags: &id032
    - Chat
    - Collaboration
    - Messaging
    - Productivity
    url: /providers/chatwork/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.4
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id037
      source: https://github.com/couchbase/mcp-server-couchbase
      status: verified
    slug: couchbase
    status: profiled
    tags: &id038
    - Analytics
    - App Services
    - Backup
    - Capella
    url: /providers/couchbase/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.2
    band: developing
    in_catalog: true
    kin_score: 42.4
    mcp: &id039
      status: unchecked
    slug: databend
    status: profiled
    tags: &id040
    - Cloud
    - Company
    - Data Warehouse
    - Open Source
    url: /providers/databend/
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
  facts:
    agent_band: agent-native
    agent_readiness: 65.5
    band: strong
    in_catalog: true
    kin_score: 58.7
    mcp: &id041
      source: https://docs.databricks.com/aws/en/generative-ai/mcp/
      status: verified
    slug: databricks
    status: profiled
    tags: &id042
    - Analytics
    - Artificial Intelligence
    - Cleanroom
    - Databricks
    url: /providers/databricks/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 80.0
    mcp: &id043
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id044
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 16.1
    mcp: &id045
      source: https://github.com/dgraph-io/dgraph/tree/main/dgraph/cmd/mcp
      status: verified
    slug: dgraph
    status: profiled
    tags: &id046
    - Distributed Database
    - Graph Database
    - GraphQL
    - Real-Time
    url: /providers/dgraph/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id047
      status: none
    slug: discord
    status: profiled
    tags: &id048
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
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
  facts:
    agent_band: human-only
    agent_readiness: 1.3
    band: thin
    in_catalog: true
    kin_score: 27.8
    mcp: &id049
      status: none
    slug: duckdb
    status: profiled
    tags: &id050
    - Analytics
    - Database
    - Embedded
    - OLAP
    url: /providers/duckdb/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 5.3
    band: thin
    in_catalog: true
    kin_score: 33.7
    mcp: &id051
      status: unknown
    slug: e6data
    status: profiled
    tags: &id052
    - Analytics
    - B2B
    - Company
    - Data
    url: /providers/e6data/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id057
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id058
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.0
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id061
      source: https://github.com/google/mcp
      status: verified
    slug: google-chat
    status: profiled
    tags: &id062
    - Chat
    - Collaboration
    - Google
    - Google Workspace
    url: /providers/google-chat/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id063
      source: https://github.com/googleapis/mcp-toolbox
      status: verified
    slug: google-cloud-spanner
    status: profiled
    tags: &id064
    - Database
    - Distributed
    - Google Cloud
    - Relational
    url: /providers/google-cloud-spanner/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.7
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id065
      status: none
    slug: google-search-console
    status: profiled
    tags: &id066
    - Analytics
    - Google
    - Indexing
    - Search
    url: /providers/google-search-console/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id067
      status: none
    slug: google-sheets
    status: profiled
    tags: &id068
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.1
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id069
      source: https://graphite.dev/docs/gt-mcp
      status: verified
    slug: graphite-com
    status: profiled
    tags: &id070
    - AI Code Review
    - Code Review
    - Stacked PRs
    - merge-queue
    url: /providers/graphite-com/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.0
    mcp: &id071
      status: none
    slug: ibm-db2
    status: profiled
    tags: &id072
    - Cloud Database
    - Database
    - Relational Database
    - SQL
    url: /providers/ibm-db2/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.6
    mcp: &id073
      status: none
    slug: netezza
    status: profiled
    tags: &id074
    - Analytics
    - Company
    - Data Warehouse
    - Database
    url: /providers/netezza/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.6
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id075
      source: https://github.com/influxdata/influxdb3_mcp_server
      status: verified
    slug: influxdb
    status: profiled
    tags: &id076
    - Analytics
    - Database
    - Real-Time
    - Time Series
    url: /providers/influxdb/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id077
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id078
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: thin
    in_catalog: true
    kin_score: 37.0
    mcp: &id079
      source: https://github.com/mattermost/mmctl-mcp
      status: verified
    slug: mattermost
    status: profiled
    tags: &id080
    - Collaboration
    - Messaging
    - Open Source
    - Team Chat
    url: /providers/mattermost/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: exemplar
    in_catalog: true
    kin_score: 67.0
    mcp: &id081
      source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
      status: verified
    slug: microsoft-sql-server
    status: profiled
    tags: &id082
    - Cloud
    - Data Management
    - Database
    - Enterprise
    url: /providers/microsoft-sql-server/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id083
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id084
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 59.1
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id085
      source: https://github.com/mongodb-js/mongodb-mcp-server
      status: verified
    slug: mongodb
    status: profiled
    tags: &id086
    - Cloud Database
    - Database
    - Document Database
    - NoSQL
    url: /providers/mongodb/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id087
      status: none
    slug: mysql
    status: profiled
    tags: &id088
    - Database
    - Open Source
    - RDBMS
    - Relational Database
    url: /providers/mysql/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 59.8
    band: exemplar
    in_catalog: true
    kin_score: 70.4
    mcp: &id089
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id090
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 54.4
    band: developing
    in_catalog: true
    kin_score: 52.1
    mcp: &id091
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id092
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id093
      status: none
    slug: postgresql
    status: profiled
    tags: &id094
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.2
    band: thin
    in_catalog: true
    kin_score: 34.3
    mcp: &id095
      status: none
    slug: presto-foundation
    status: profiled
    tags: &id096
    - Analytics
    - Big Data
    - Distributed SQL
    - Linux Foundation
    url: /providers/presto-foundation/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id097
      source: https://github.com/prometheus/prometheus-mcp
      status: verified
    slug: prometheus-io
    status: profiled
    tags: &id098
    - Metrics
    - Monitoring
    - Observability
    - Prometheus
    url: /providers/prometheus-io/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 30.4
    mcp: &id099
      source: https://github.com/risingwavelabs/risingwave-mcp
      status: verified
    slug: risingwave
    status: profiled
    tags: &id100
    - Database
    - Real-Time
    - SQL
    - Streaming
    url: /providers/risingwave/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id101
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id102
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.6
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id103
      source: https://github.com/singlestore-labs/mcp-server-singlestore
      status: verified
    slug: singlestore
    status: profiled
    tags: &id104
    - Analytics
    - Cloud
    - Database
    - SQL
    url: /providers/singlestore/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id105
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id106
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
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
  facts:
    agent_band: agent-native
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 82.3
    mcp: &id107
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id108
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: developing
    in_catalog: true
    kin_score: 46.4
    mcp: &id109
      source: https://www.tinybird.co/docs/forward/analytics-agents/mcp
      status: verified
    slug: tinybird
    status: profiled
    tags: &id110
    - Analytics
    - Data
    - Real-Time
    - SQL
    url: /providers/tinybird/
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
  facts:
    agent_band: agent-native
    agent_readiness: 49.9
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id111
      source: https://github.com/treasure-data/td-mcp-server
      status: verified
    slug: treasure-data
    status: profiled
    tags: &id112
    - Big Data
    - CDP
    - Customer Data Platform
    - Data Warehouse
    url: /providers/treasure-data/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 30.8
    mcp: &id115
      source: https://github.com/uptycslabs/juno-mcp-server
      status: verified
    slug: uptycs
    status: profiled
    tags: &id116
    - CNAPP
    - Cybersecurity
    - Security
    - XDR
    url: /providers/uptycs/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: emerging
    in_catalog: true
    kin_score: 22.9
    mcp: &id117
      status: none
    slug: vertica
    status: profiled
    tags: &id118
    - Analytics Database
    - Data Lakehouse
    - Data Warehouse
    - Database
    url: /providers/vertica/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 61.8
    band: strong
    in_catalog: true
    kin_score: 66.1
    mcp: &id119
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id120
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 11.9
    mcp: &id121
      status: unchecked
    slug: yandex-disk
    status: profiled
    tags: &id122
    - AI Features
    - Backup
    - Cloud Storage
    - File Sync
    url: /providers/yandex-disk/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.8
    mcp: &id123
      status: none
    slug: yandex-metrica
    status: profiled
    tags: &id124
    - Analytics
    - Marketing
    - Web Analytics
    - Yandex
    url: /providers/yandex-metrica/
  layer: domain
  name: Yandex Metrica
  provider: yandex-metrica
  says: ships the Yandex Metrica SDK or integration code
  source: https://github.com/getredash/redash/tree/master/redash/query_runner
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/bi-dashboards/redash/
providers:
- agent_band: agent-native
  agent_readiness: 44.8
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id001
  name: Amazon Athena
  slug: amazon-athena
  status: profiled
  tags: *id002
  url: /providers/amazon-athena/
- agent_band: agent-native
  agent_readiness: 43.4
  band: exemplar
  in_catalog: true
  kin_score: 77.4
  mcp: *id003
  name: Amazon CloudWatch
  slug: amazon-cloudwatch
  status: profiled
  tags: *id004
  url: /providers/amazon-cloudwatch/
- agent_band: agent-native
  agent_readiness: 43.6
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id005
  name: Amazon OpenSearch Service
  slug: amazon-opensearch
  status: profiled
  tags: *id006
  url: /providers/amazon-opensearch/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id007
  name: Apache Cassandra
  slug: cassandra
  status: profiled
  tags: *id008
  url: /providers/cassandra/
- agent_band: agent-aware
  agent_readiness: 12.4
  band: thin
  in_catalog: true
  kin_score: 28.3
  mcp: *id009
  name: Apache Drill
  slug: apache-drill
  status: profiled
  tags: *id010
  url: /providers/apache-drill/
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
- agent_band: agent-ready
  agent_readiness: 30.2
  band: developing
  in_catalog: true
  kin_score: 40.0
  mcp: *id015
  name: Apache Ignite
  slug: apache-ignite
  status: profiled
  tags: *id016
  url: /providers/apache-ignite/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 13.8
  mcp: *id017
  name: Apache Impala
  slug: apache-impala
  status: profiled
  tags: *id018
  url: /providers/apache-impala/
- agent_band: agent-aware
  agent_readiness: 24.9
  band: thin
  in_catalog: true
  kin_score: 37.2
  mcp: *id019
  name: Apache Kylin
  slug: apache-kylin
  status: profiled
  tags: *id020
  url: /providers/apache-kylin/
- agent_band: agent-aware
  agent_readiness: 12.4
  band: thin
  in_catalog: true
  kin_score: 29.7
  mcp: *id021
  name: Apache Phoenix
  slug: apache-phoenix
  status: profiled
  tags: *id022
  url: /providers/apache-phoenix/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: emerging
  in_catalog: true
  kin_score: 20.5
  mcp: *id023
  name: Apache Pinot
  slug: apache-pinot
  status: profiled
  tags: *id024
  url: /providers/apache-pinot/
- agent_band: agent-aware
  agent_readiness: 27.8
  band: developing
  in_catalog: true
  kin_score: 52.3
  mcp: *id025
  name: ArangoDB
  slug: arangodb
  status: profiled
  tags: *id026
  url: /providers/arangodb/
- agent_band: agent-ready
  agent_readiness: 55.3
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id027
  name: Asana
  slug: asana
  status: profiled
  tags: *id028
  url: /providers/asana/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id029
  name: Azure Data Explorer (Kusto)
  slug: azure-data-explorer
  status: queued for profiling
  tags: *id030
  url: null
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 30.1
  mcp: *id031
  name: Chatwork
  slug: chatwork
  status: profiled
  tags: *id032
  url: /providers/chatwork/
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
- agent_band: agent-aware
  agent_readiness: 28.4
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id037
  name: Couchbase
  slug: couchbase
  status: profiled
  tags: *id038
  url: /providers/couchbase/
- agent_band: agent-aware
  agent_readiness: 23.2
  band: developing
  in_catalog: true
  kin_score: 42.4
  mcp: *id039
  name: Databend
  slug: databend
  status: profiled
  tags: *id040
  url: /providers/databend/
- agent_band: agent-native
  agent_readiness: 65.5
  band: strong
  in_catalog: true
  kin_score: 58.7
  mcp: *id041
  name: Databricks
  slug: databricks
  status: profiled
  tags: *id042
  url: /providers/databricks/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id043
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id044
  url: /providers/datadog/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 16.1
  mcp: *id045
  name: Dgraph
  slug: dgraph
  status: profiled
  tags: *id046
  url: /providers/dgraph/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id047
  name: Discord
  slug: discord
  status: profiled
  tags: *id048
  url: /providers/discord/
- agent_band: human-only
  agent_readiness: 1.3
  band: thin
  in_catalog: true
  kin_score: 27.8
  mcp: *id049
  name: DuckDB
  slug: duckdb
  status: profiled
  tags: *id050
  url: /providers/duckdb/
- agent_band: agent-aware
  agent_readiness: 5.3
  band: thin
  in_catalog: true
  kin_score: 33.7
  mcp: *id051
  name: e6data
  slug: e6data
  status: profiled
  tags: *id052
  url: /providers/e6data/
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
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id057
  name: Google Analytics 4
  slug: google-analytics
  status: profiled
  tags: *id058
  url: /providers/google-analytics/
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
  agent_readiness: 41.0
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id061
  name: Google Chat
  slug: google-chat
  status: profiled
  tags: *id062
  url: /providers/google-chat/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id063
  name: Google Cloud Spanner
  slug: google-cloud-spanner
  status: profiled
  tags: *id064
  url: /providers/google-cloud-spanner/
- agent_band: agent-ready
  agent_readiness: 30.7
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id065
  name: Google Search Console
  slug: google-search-console
  status: profiled
  tags: *id066
  url: /providers/google-search-console/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id067
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id068
  url: /providers/google-sheets/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id069
  name: Graphite
  slug: graphite-com
  status: profiled
  tags: *id070
  url: /providers/graphite-com/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.0
  mcp: *id071
  name: IBM Db2
  slug: ibm-db2
  status: profiled
  tags: *id072
  url: /providers/ibm-db2/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.6
  mcp: *id073
  name: IBM Netezza
  slug: netezza
  status: profiled
  tags: *id074
  url: /providers/netezza/
- agent_band: agent-ready
  agent_readiness: 33.6
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id075
  name: InfluxDB
  slug: influxdb
  status: profiled
  tags: *id076
  url: /providers/influxdb/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id077
  name: Jira (JQL)
  slug: jira
  status: profiled
  tags: *id078
  url: /providers/jira/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id079
  name: Mattermost
  slug: mattermost
  status: profiled
  tags: *id080
  url: /providers/mattermost/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 67.0
  mcp: *id081
  name: Microsoft SQL Server
  slug: microsoft-sql-server
  status: profiled
  tags: *id082
  url: /providers/microsoft-sql-server/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id083
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id084
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 59.1
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id085
  name: MongoDB
  slug: mongodb
  status: profiled
  tags: *id086
  url: /providers/mongodb/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id087
  name: MySQL
  slug: mysql
  status: profiled
  tags: *id088
  url: /providers/mysql/
- agent_band: agent-ready
  agent_readiness: 59.8
  band: exemplar
  in_catalog: true
  kin_score: 70.4
  mcp: *id089
  name: Oracle Database
  slug: oracle
  status: profiled
  tags: *id090
  url: /providers/oracle/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id091
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id092
  url: /providers/pagerduty/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id093
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id094
  url: /providers/postgresql/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: thin
  in_catalog: true
  kin_score: 34.3
  mcp: *id095
  name: Presto (PrestoDB)
  slug: presto-foundation
  status: profiled
  tags: *id096
  url: /providers/presto-foundation/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id097
  name: Prometheus
  slug: prometheus-io
  status: profiled
  tags: *id098
  url: /providers/prometheus-io/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id099
  name: RisingWave
  slug: risingwave
  status: profiled
  tags: *id100
  url: /providers/risingwave/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id101
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id102
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 31.6
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id103
  name: SingleStore
  slug: singlestore
  status: profiled
  tags: *id104
  url: /providers/singlestore/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id105
  name: Slack
  slug: slack
  status: profiled
  tags: *id106
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 82.3
  mcp: *id107
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id108
  url: /providers/snowflake/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: developing
  in_catalog: true
  kin_score: 46.4
  mcp: *id109
  name: Tinybird
  slug: tinybird
  status: profiled
  tags: *id110
  url: /providers/tinybird/
- agent_band: agent-native
  agent_readiness: 49.9
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id111
  name: Treasure Data
  slug: treasure-data
  status: profiled
  tags: *id112
  url: /providers/treasure-data/
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
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 30.8
  mcp: *id115
  name: Uptycs
  slug: uptycs
  status: profiled
  tags: *id116
  url: /providers/uptycs/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: emerging
  in_catalog: true
  kin_score: 22.9
  mcp: *id117
  name: Vertica
  slug: vertica
  status: profiled
  tags: *id118
  url: /providers/vertica/
- agent_band: agent-ready
  agent_readiness: 61.8
  band: strong
  in_catalog: true
  kin_score: 66.1
  mcp: *id119
  name: Webex
  slug: webex
  status: profiled
  tags: *id120
  url: /providers/webex/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 11.9
  mcp: *id121
  name: Yandex Disk
  slug: yandex-disk
  status: profiled
  tags: *id122
  url: /providers/yandex-disk/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.8
  mcp: *id123
  name: Yandex Metrica
  slug: yandex-metrica
  status: profiled
  tags: *id124
  url: /providers/yandex-metrica/
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
- name: Looker
  rows: 34
  url: /applications/bi-dashboards/looker/
- name: Metabase
  rows: 19
  url: /applications/bi-dashboards/metabase/
- name: Microsoft Power BI
  rows: 58
  url: /applications/bi-dashboards/microsoft-power-bi/
sitemap: true
title: 'Redash: BI & Dashboards reference app'
---
