---
app: Metabase
app_slug: metabase
app_url: https://github.com/metabase/metabase
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Amazon Athena
  - Amazon Redshift
  - Apache Druid
  - Apache Hive
  - Apache Spark SQL
  - ClickHouse
  - Databricks
  - Google BigQuery
  - MotherDuck
  - Presto (PrestoDB)
  - Snowflake
  - Starburst
  - Vertica
  url: /capabilities/analytics-bi-management/
  via_parent: null
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
  declared: 0
  observed: 19
credits: []
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
  facts:
    agent_band: agent-native
    agent_readiness: 44.5
    band: exemplar
    in_catalog: true
    kin_score: 75.1
    mcp: &id003
      source: https://github.com/awslabs/mcp/tree/main/src/redshift-mcp-server
      status: verified
    slug: amazon-redshift
    status: profiled
    tags: &id004
    - Analytics
    - Big Data
    - Cloud
    - Data Lake
    url: /providers/amazon-redshift/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 38.7
    mcp: &id005
      status: none
    slug: apache-druid
    status: profiled
    tags: &id006
    - Analytics
    - Apache
    - Database
    - Kafka
    url: /providers/apache-druid/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.8
    band: thin
    in_catalog: true
    kin_score: 32.9
    mcp: &id007
      status: none
    slug: apache-hive
    status: profiled
    tags: &id008
    - Apache
    - Big Data
    - Data Warehouse
    - ETL
    url: /providers/apache-hive/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 38.3
    mcp: &id009
      status: none
    slug: apache-spark
    status: profiled
    tags: &id010
    - Analytics
    - Big Data
    - Distributed Computing
    - Machine Learning
    url: /providers/apache-spark/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 77.1
    mcp: &id011
      source: https://github.com/ClickHouse/mcp-clickhouse
      status: verified
    slug: clickhouse
    status: profiled
    tags: &id012
    - Analytics
    - ClickHouse
    - Cloud Database
    - Column-Oriented
    url: /providers/clickhouse/
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
  facts:
    agent_band: agent-native
    agent_readiness: 65.5
    band: strong
    in_catalog: true
    kin_score: 58.7
    mcp: &id013
      source: https://docs.databricks.com/aws/en/generative-ai/mcp/
      status: verified
    slug: databricks
    status: profiled
    tags: &id014
    - Analytics
    - Artificial Intelligence
    - Cleanroom
    - Databricks
    url: /providers/databricks/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id015
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id016
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: exemplar
    in_catalog: true
    kin_score: 67.0
    mcp: &id017
      source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
      status: verified
    slug: microsoft-sql-server
    status: profiled
    tags: &id018
    - Cloud
    - Data Management
    - Database
    - Enterprise
    url: /providers/microsoft-sql-server/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 59.1
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id019
      source: https://github.com/mongodb-js/mongodb-mcp-server
      status: verified
    slug: mongodb
    status: profiled
    tags: &id020
    - Cloud Database
    - Database
    - Document Database
    - NoSQL
    url: /providers/mongodb/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 32.1
    band: emerging
    in_catalog: true
    kin_score: 18.6
    mcp: &id021
      source: https://github.com/motherduckdb/mcp-server-motherduck
      status: verified
    slug: motherduck
    status: profiled
    tags: &id022
    - Data Warehouse
    - DuckDB
    - SQL
    - Serverless
    url: /providers/motherduck/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id023
      status: none
    slug: mysql
    status: profiled
    tags: &id024
    - Database
    - Open Source
    - RDBMS
    - Relational Database
    url: /providers/mysql/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 59.8
    band: exemplar
    in_catalog: true
    kin_score: 70.4
    mcp: &id025
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id026
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id027
      status: none
    slug: postgresql
    status: profiled
    tags: &id028
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.2
    band: thin
    in_catalog: true
    kin_score: 34.3
    mcp: &id029
      status: none
    slug: presto-foundation
    status: profiled
    tags: &id030
    - Analytics
    - Big Data
    - Distributed SQL
    - Linux Foundation
    url: /providers/presto-foundation/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id031
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id032
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
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
  facts:
    agent_band: agent-native
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 82.3
    mcp: &id033
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id034
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id035
      source: https://docs.starburst.io/starburst-galaxy/starburst-ai/mcp-server.html
      status: verified
    slug: starburst
    status: profiled
    tags: &id036
    - Company
    - Data Analytics
    - Data Lakehouse
    - SQL Query Engine
    url: /providers/starburst/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: emerging
    in_catalog: true
    kin_score: 22.9
    mcp: &id037
      status: none
    slug: vertica
    status: profiled
    tags: &id038
    - Analytics Database
    - Data Lakehouse
    - Data Warehouse
    - Database
    url: /providers/vertica/
  layer: domain
  name: Vertica
  provider: vertica
  says: ships the Vertica SDK or integration code
  source: https://github.com/metabase/metabase/tree/master/modules/drivers
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/bi-dashboards/metabase/
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
  agent_readiness: 44.5
  band: exemplar
  in_catalog: true
  kin_score: 75.1
  mcp: *id003
  name: Amazon Redshift
  slug: amazon-redshift
  status: profiled
  tags: *id004
  url: /providers/amazon-redshift/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 38.7
  mcp: *id005
  name: Apache Druid
  slug: apache-druid
  status: profiled
  tags: *id006
  url: /providers/apache-druid/
- agent_band: agent-aware
  agent_readiness: 16.8
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id007
  name: Apache Hive
  slug: apache-hive
  status: profiled
  tags: *id008
  url: /providers/apache-hive/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 38.3
  mcp: *id009
  name: Apache Spark SQL
  slug: apache-spark
  status: profiled
  tags: *id010
  url: /providers/apache-spark/
- agent_band: agent-ready
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 77.1
  mcp: *id011
  name: ClickHouse
  slug: clickhouse
  status: profiled
  tags: *id012
  url: /providers/clickhouse/
- agent_band: agent-native
  agent_readiness: 65.5
  band: strong
  in_catalog: true
  kin_score: 58.7
  mcp: *id013
  name: Databricks
  slug: databricks
  status: profiled
  tags: *id014
  url: /providers/databricks/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id015
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id016
  url: /providers/google-bigquery/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 67.0
  mcp: *id017
  name: Microsoft SQL Server
  slug: microsoft-sql-server
  status: profiled
  tags: *id018
  url: /providers/microsoft-sql-server/
- agent_band: agent-ready
  agent_readiness: 59.1
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id019
  name: MongoDB
  slug: mongodb
  status: profiled
  tags: *id020
  url: /providers/mongodb/
- agent_band: agent-ready
  agent_readiness: 32.1
  band: emerging
  in_catalog: true
  kin_score: 18.6
  mcp: *id021
  name: MotherDuck
  slug: motherduck
  status: profiled
  tags: *id022
  url: /providers/motherduck/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id023
  name: MySQL
  slug: mysql
  status: profiled
  tags: *id024
  url: /providers/mysql/
- agent_band: agent-ready
  agent_readiness: 59.8
  band: exemplar
  in_catalog: true
  kin_score: 70.4
  mcp: *id025
  name: Oracle Database
  slug: oracle
  status: profiled
  tags: *id026
  url: /providers/oracle/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id027
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id028
  url: /providers/postgresql/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: thin
  in_catalog: true
  kin_score: 34.3
  mcp: *id029
  name: Presto (PrestoDB)
  slug: presto-foundation
  status: profiled
  tags: *id030
  url: /providers/presto-foundation/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id031
  name: Slack
  slug: slack
  status: profiled
  tags: *id032
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 82.3
  mcp: *id033
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id034
  url: /providers/snowflake/
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id035
  name: Starburst
  slug: starburst
  status: profiled
  tags: *id036
  url: /providers/starburst/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: emerging
  in_catalog: true
  kin_score: 22.9
  mcp: *id037
  name: Vertica
  slug: vertica
  status: profiled
  tags: *id038
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
- name: Looker
  rows: 34
  url: /applications/bi-dashboards/looker/
- name: Microsoft Power BI
  rows: 58
  url: /applications/bi-dashboards/microsoft-power-bi/
- name: Redash
  rows: 62
  url: /applications/bi-dashboards/redash/
sitemap: true
title: 'Metabase: BI & Dashboards reference app'
---
