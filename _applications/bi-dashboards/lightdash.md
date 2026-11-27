---
app: Lightdash
app_slug: lightdash
app_url: https://github.com/lightdash/lightdash
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
  - ClickHouse
  - Databricks
  - DuckDB
  - Google BigQuery
  - MotherDuck
  - Snowflake
  - Trino
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-938
  key: AE-938
  layer: domain
  name: Semantic & Metrics Layer
  providers:
  - dbt
  url: /capabilities/analytics-bi-management/
  via_parent: Analytics & BI Management
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - PostgreSQL
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: bi-dashboards
  name: BI & Dashboards
  url: /applications/bi-dashboards/
counts:
  declared: 1
  observed: 10
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 77.1
    mcp: &id005
      source: https://github.com/ClickHouse/mcp-clickhouse
      status: verified
    slug: clickhouse
    status: profiled
    tags: &id006
    - Analytics
    - ClickHouse
    - Cloud Database
    - Column-Oriented
    url: /providers/clickhouse/
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
  facts:
    agent_band: agent-native
    agent_readiness: 65.5
    band: strong
    in_catalog: true
    kin_score: 58.7
    mcp: &id007
      source: https://docs.databricks.com/aws/en/generative-ai/mcp/
      status: verified
    slug: databricks
    status: profiled
    tags: &id008
    - Analytics
    - Artificial Intelligence
    - Cleanroom
    - Databricks
    url: /providers/databricks/
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
  facts:
    agent_band: human-only
    agent_readiness: 1.3
    band: thin
    in_catalog: true
    kin_score: 27.8
    mcp: &id011
      status: none
    slug: duckdb
    status: profiled
    tags: &id012
    - Analytics
    - Database
    - Embedded
    - OLAP
    url: /providers/duckdb/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id013
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id014
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 32.1
    band: emerging
    in_catalog: true
    kin_score: 18.6
    mcp: &id015
      source: https://github.com/motherduckdb/mcp-server-motherduck
      status: verified
    slug: motherduck
    status: profiled
    tags: &id016
    - Data Warehouse
    - DuckDB
    - SQL
    - Serverless
    url: /providers/motherduck/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id017
      status: none
    slug: postgresql
    status: profiled
    tags: &id018
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
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
  facts:
    agent_band: agent-native
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 82.3
    mcp: &id019
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id020
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.3
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id021
      status: none
    slug: trino
    status: profiled
    tags: &id022
    - Analytics
    - Big Data
    - Distributed SQL
    - MySQL
    url: /providers/trino/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.8
    band: developing
    in_catalog: true
    kin_score: 51.5
    mcp: &id009
      source: https://github.com/dbt-labs/dbt-mcp
      status: verified
    slug: dbt
    status: profiled
    tags: &id010
    - Analytics Engineering
    - Data
    - ELT
    - Metrics
    url: /providers/dbt/
  layer: domain
  name: dbt
  provider: dbt
  says: lists dbt as an integration
  source: https://github.com/lightdash/lightdash/blob/main/README.md
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/bi-dashboards/lightdash/
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
- agent_band: agent-ready
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 77.1
  mcp: *id005
  name: ClickHouse
  slug: clickhouse
  status: profiled
  tags: *id006
  url: /providers/clickhouse/
- agent_band: agent-native
  agent_readiness: 65.5
  band: strong
  in_catalog: true
  kin_score: 58.7
  mcp: *id007
  name: Databricks
  slug: databricks
  status: profiled
  tags: *id008
  url: /providers/databricks/
- agent_band: agent-aware
  agent_readiness: 19.8
  band: developing
  in_catalog: true
  kin_score: 51.5
  mcp: *id009
  name: dbt
  slug: dbt
  status: profiled
  tags: *id010
  url: /providers/dbt/
- agent_band: human-only
  agent_readiness: 1.3
  band: thin
  in_catalog: true
  kin_score: 27.8
  mcp: *id011
  name: DuckDB
  slug: duckdb
  status: profiled
  tags: *id012
  url: /providers/duckdb/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id013
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id014
  url: /providers/google-bigquery/
- agent_band: agent-ready
  agent_readiness: 32.1
  band: emerging
  in_catalog: true
  kin_score: 18.6
  mcp: *id015
  name: MotherDuck
  slug: motherduck
  status: profiled
  tags: *id016
  url: /providers/motherduck/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id017
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id018
  url: /providers/postgresql/
- agent_band: agent-native
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 82.3
  mcp: *id019
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id020
  url: /providers/snowflake/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id021
  name: Trino
  slug: trino
  status: profiled
  tags: *id022
  url: /providers/trino/
siblings:
- name: Apache Superset
  rows: 60
  url: /applications/bi-dashboards/apache-superset/
- name: Grafana
  rows: 32
  url: /applications/bi-dashboards/grafana/
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
title: 'Lightdash: BI & Dashboards reference app'
---
