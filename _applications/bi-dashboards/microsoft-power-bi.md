---
app: Microsoft Power BI
app_slug: microsoft-power-bi
app_url: https://www.microsoft.com/power-platform/products/power-bi
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
  - Apache Impala
  - Azure Data Explorer (Kusto)
  - ClickHouse
  - Databricks
  - Dremio
  - Exasol
  - Funnel
  - Google BigQuery
  - IBM Netezza
  - Palantir Foundry
  - SAP HANA
  - SingleStore
  - Snowflake
  - Starburst
  - Supermetrics
  - Teradata
  - Vertica
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1150
  key: construction-management
  layer: domain
  name: Construction Management
  providers:
  - Autodesk Construction Cloud
  url: /capabilities/construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - Attio
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Zendesk
  url: /capabilities/customer-service-management/
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
  id: BC-600.50.50
  key: BC-600.50.50
  layer: domain
  name: End-User Computing Management
  providers:
  - Jamf Pro
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-2430
  key: fleet-mobile-asset-management
  layer: domain
  name: Fleet & Mobile Asset Management
  providers:
  - Samsara
  url: /capabilities/fleet-mobile-asset-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: domain
  name: Human Capital Management
  providers:
  - ADP Analytics
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-913
  key: AE-913
  layer: domain
  name: Link Shortening & Link-in-Bio
  providers:
  - Bitly
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-230.20
  key: AE-230.20
  layer: domain
  name: Market & Financial Data
  providers:
  - Bloomberg Data and Analytics
  - FactSet
  url: /capabilities/market-financial-data/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.50
  key: marketing-operations-management
  layer: domain
  name: Marketing Operations Management
  providers:
  - Marketo
  url: /capabilities/marketing-operations-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: domain
  name: Online Forms & Survey Collection
  providers:
  - SurveyMonkey
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: domain
  name: Product Usage Analytics
  providers:
  - Adobe Analytics
  - Google Analytics 4
  - Mixpanel
  - Siteimprove
  - Webtrends Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Asana
  - Wrike
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
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - Bitbucket
  - GitHub
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - SparkPost
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - IBM Db2
  - MariaDB
  - MarkLogic
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
  - Visual Studio App Center Crashes
  - Dynatrace Grail
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: common
  name: Spreadsheets & No-Code Databases
  providers:
  - Google Sheets
  - Quickbase
  - Smartsheet
  - Zoho Creator
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: bi-dashboards
  name: BI & Dashboards
  url: /applications/bi-dashboards/
counts:
  declared: 57
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id107
      status: unchecked
    slug: microsoft-app-center
    status: queued for profiling
    tags: &id108 []
    url: null
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
  facts:
    agent_band: agent-native
    agent_readiness: 60.3
    band: strong
    in_catalog: true
    kin_score: 65.0
    mcp: &id001
      status: none
    slug: adobe-analytics
    status: profiled
    tags: &id002
    - Adobe
    - Analytics
    - Business Intelligence
    - Customer Intelligence
    url: /providers/adobe-analytics/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 39.8
    band: developing
    in_catalog: true
    kin_score: 45.6
    mcp: &id003
      status: none
    slug: adp
    status: profiled
    tags: &id004
    - Benefits
    - HCM
    - Human Resources
    - Payroll
    url: /providers/adp/
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
  facts:
    agent_band: agent-native
    agent_readiness: 43.6
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id007
      source: https://docs.aws.amazon.com/opensearch-service/latest/developerguide/aws-mcp-server.html
      status: verified
    slug: amazon-opensearch
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Analytics
    - Elasticsearch
    - Search
    url: /providers/amazon-opensearch/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 13.8
    mcp: &id011
      status: unchecked
    slug: apache-impala
    status: profiled
    tags: &id012
    - Analytics
    - Company
    - Hadoop
    - Open Source
    url: /providers/apache-impala/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 55.3
    band: exemplar
    in_catalog: true
    kin_score: 72.5
    mcp: &id013
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id014
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: emerging
    in_catalog: true
    kin_score: 20.0
    mcp: &id015
      source: https://docs.attio.com/mcp/overview
      status: verified
    slug: attio
    status: profiled
    tags: &id016
    - CRM
    - Companies
    - Contacts
    - Sales
    url: /providers/attio/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 69.0
    mcp: &id017
      source: https://github.com/autodesk-platform-services/aps-mcp-server-nodejs
      status: verified
    slug: autodesk-construction-cloud
    status: profiled
    tags: &id018
    - AEC
    - BIM
    - Construction
    - Project Management
    url: /providers/autodesk-construction-cloud/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id019
      status: unchecked
    slug: azure-data-explorer
    status: queued for profiling
    tags: &id020 []
    url: null
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: exemplar
    in_catalog: true
    kin_score: 71.9
    mcp: &id021
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: bitbucket
    status: profiled
    tags: &id022
    - Atlassian
    - CI/CD
    - Code Collaboration
    - Code Review
    url: /providers/bitbucket/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.2
    band: exemplar
    in_catalog: true
    kin_score: 73.0
    mcp: &id023
      source: https://dev.bitly.com/bitly-mcp/
      status: verified
    slug: bitly
    status: profiled
    tags: &id024
    - Analytics
    - Links
    - QR Codes
    - URL Shorteners
    url: /providers/bitly/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.3
    band: strong
    in_catalog: true
    kin_score: 55.4
    mcp: &id025
      status: unknown
    slug: bloomberg
    status: profiled
    tags: &id026
    - Analytics
    - Business Intelligence
    - Data License
    - Enterprise
    url: /providers/bloomberg/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 77.1
    mcp: &id027
      source: https://github.com/ClickHouse/mcp-clickhouse
      status: verified
    slug: clickhouse
    status: profiled
    tags: &id028
    - Analytics
    - ClickHouse
    - Cloud Database
    - Column-Oriented
    url: /providers/clickhouse/
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
  facts:
    agent_band: agent-native
    agent_readiness: 65.5
    band: strong
    in_catalog: true
    kin_score: 58.7
    mcp: &id029
      source: https://docs.databricks.com/aws/en/generative-ai/mcp/
      status: verified
    slug: databricks
    status: profiled
    tags: &id030
    - Analytics
    - Artificial Intelligence
    - Cleanroom
    - Databricks
    url: /providers/databricks/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.5
    band: thin
    in_catalog: true
    kin_score: 34.7
    mcp: &id031
      source: https://community.denodo.com/docs/html/document/denodoconnects/9.1/en/Denodo%20MCP%20Server%20-%20User%20Manual
      status: verified
    slug: denodo
    status: profiled
    tags: &id032
    - Data Catalog
    - Data Fabric
    - Data Mesh
    - Data Virtualization
    url: /providers/denodo/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 5.8
    band: developing
    in_catalog: true
    kin_score: 51.5
    mcp: &id033
      source: https://github.com/dremio/dremio-mcp
      status: verified
    slug: dremio
    status: profiled
    tags: &id034
    - Analytics
    - Company
    - Data Lakehouse
    - SQL Query Engine
    url: /providers/dremio/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.8
    band: exemplar
    in_catalog: true
    kin_score: 85.6
    mcp: &id035
      source: https://github.com/dynatrace-oss/dynatrace-mcp
      status: verified
    slug: dynatrace
    status: profiled
    tags: &id036
    - AI Operations
    - APM
    - Analytics
    - Application Performance Monitoring
    url: /providers/dynatrace/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.5
    band: exemplar
    in_catalog: true
    kin_score: 78.4
    mcp: &id037
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id038
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 15.5
    band: emerging
    in_catalog: true
    kin_score: 22.6
    mcp: &id039
      status: unchecked
    slug: exasol
    status: profiled
    tags: &id040
    - Analytics
    - Artificial Intelligence
    - Company
    - Database
    url: /providers/exasol/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 49.0
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id041
      source: https://mcp.factset.com/.well-known/oauth-protected-resource
      status: verified
    slug: factset
    status: profiled
    tags: &id042
    - Finance
    - Financial Data
    - Investment Analytics
    - Market Data
    url: /providers/factset/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 58.7
    mcp: &id043
      source: https://github.com/funnel-io/funnel-mcp
      status: verified
    slug: funnel
    status: profiled
    tags: &id044
    - Company
    - Marketing
    - Marketing Data
    - Marketing Intelligence
    url: /providers/funnel/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id045
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id046
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id047
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id048
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id049
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id050
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id051
      status: none
    slug: google-sheets
    status: profiled
    tags: &id052
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.0
    mcp: &id053
      status: none
    slug: ibm-db2
    status: profiled
    tags: &id054
    - Cloud Database
    - Database
    - Relational Database
    - SQL
    url: /providers/ibm-db2/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.6
    mcp: &id055
      status: none
    slug: netezza
    status: profiled
    tags: &id056
    - Analytics
    - Company
    - Data Warehouse
    - Database
    url: /providers/netezza/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.3
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id057
      status: none
    slug: jamf
    status: profiled
    tags: &id058
    - Apple Device Management
    - Company
    - Endpoint Security
    - MDM
    url: /providers/jamf/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.8
    band: developing
    in_catalog: true
    kin_score: 41.2
    mcp: &id059
      status: unchecked
    slug: mariadb
    status: profiled
    tags: &id060
    - Cloud
    - Database
    - Enterprise
    - Open Source
    url: /providers/mariadb/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.4
    band: strong
    in_catalog: true
    kin_score: 57.2
    mcp: &id061
      status: none
    slug: marketo
    status: profiled
    tags: &id062
    - Adobe
    - Automation
    - Marketing
    - Marketing Automation
    url: /providers/marketo/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id063
      status: unchecked
    slug: marklogic
    status: queued for profiling
    tags: &id064 []
    url: null
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: exemplar
    in_catalog: true
    kin_score: 67.0
    mcp: &id065
      source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
      status: verified
    slug: microsoft-sql-server
    status: profiled
    tags: &id066
    - Cloud
    - Data Management
    - Database
    - Enterprise
    url: /providers/microsoft-sql-server/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id067
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id068
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 59.1
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id069
      source: https://github.com/mongodb-js/mongodb-mcp-server
      status: verified
    slug: mongodb
    status: profiled
    tags: &id070
    - Cloud Database
    - Database
    - Document Database
    - NoSQL
    url: /providers/mongodb/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id071
      status: none
    slug: mysql
    status: profiled
    tags: &id072
    - Database
    - Open Source
    - RDBMS
    - Relational Database
    url: /providers/mysql/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 59.8
    band: exemplar
    in_catalog: true
    kin_score: 70.4
    mcp: &id073
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id074
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 17.5
    band: emerging
    in_catalog: true
    kin_score: 24.9
    mcp: &id075
      source: https://github.com/palantir/palantir-mcp
      status: verified
    slug: palantir
    status: profiled
    tags: &id076
    - AI Platform
    - Data Analytics
    - Enterprise
    - Government
    url: /providers/palantir/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id077
      status: none
    slug: postgresql
    status: profiled
    tags: &id078
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 49.5
    band: exemplar
    in_catalog: true
    kin_score: 80.5
    mcp: &id079
      status: unknown
    slug: quickbase
    status: profiled
    tags: &id080
    - Application Development
    - Company
    - Low-Code
    - No-Code
    url: /providers/quickbase/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id081
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id082
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.9
    band: thin
    in_catalog: true
    kin_score: 32.0
    mcp: &id083
      source: https://mcp.samsara.com/mcp
      status: documented
    slug: samsara
    status: profiled
    tags: &id084
    - Asset Tracking
    - Connected Operations
    - ELD
    - Fleet Management
    url: /providers/samsara/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: developing
    in_catalog: true
    kin_score: 44.8
    mcp: &id085
      status: none
    slug: sap-hana
    status: profiled
    tags: &id086
    - Analytics
    - Cloud
    - Database
    - Enterprise
    url: /providers/sap-hana/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.6
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id087
      source: https://github.com/singlestore-labs/mcp-server-singlestore
      status: verified
    slug: singlestore
    status: profiled
    tags: &id088
    - Analytics
    - Cloud
    - Database
    - SQL
    url: /providers/singlestore/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.9
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id089
      status: unchecked
    slug: siteimprove
    status: profiled
    tags: &id090
    - Accessibility
    - Analytics
    - Company
    - SEO
    url: /providers/siteimprove/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 41.4
    mcp: &id091
      source: https://github.com/smartsheet-platform/smar-mcp
      status: verified
    slug: smartsheet
    status: profiled
    tags: &id092
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/smartsheet/
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
  facts:
    agent_band: agent-native
    agent_readiness: 44.9
    band: exemplar
    in_catalog: true
    kin_score: 82.3
    mcp: &id093
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id094
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.6
    band: thin
    in_catalog: true
    kin_score: 37.1
    mcp: &id095
      status: none
    slug: sparkpost
    status: profiled
    tags: &id096
    - Email
    - Email Delivery
    - Marketing Email
    - Transactional Email
    url: /providers/sparkpost/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id097
      source: https://docs.starburst.io/starburst-galaxy/starburst-ai/mcp-server.html
      status: verified
    slug: starburst
    status: profiled
    tags: &id098
    - Company
    - Data Analytics
    - Data Lakehouse
    - SQL Query Engine
    url: /providers/starburst/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.4
    band: strong
    in_catalog: true
    kin_score: 58.2
    mcp: &id099
      source: https://mcp.supermetrics.com/mcp
      status: verified
    slug: supermetrics
    status: profiled
    tags: &id100
    - Advertising
    - Analytics
    - Company
    - Marketing
    url: /providers/supermetrics/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: thin
    in_catalog: true
    kin_score: 34.9
    mcp: &id101
      source: https://www.surveymonkey.com/apps/
      status: documented
    slug: surveymonkey
    status: profiled
    tags: &id102
    - Feedback
    - Market Research
    - NPS
    - Surveys
    url: /providers/surveymonkey/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 52.8
    mcp: &id103
      source: https://github.com/Teradata/teradata-mcp-server
      status: verified
    slug: teradata
    status: profiled
    tags: &id104
    - Analytics
    - Cloud
    - Data Management
    - Data Warehousing
    url: /providers/teradata/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: emerging
    in_catalog: true
    kin_score: 22.9
    mcp: &id105
      status: none
    slug: vertica
    status: profiled
    tags: &id106
    - Analytics Database
    - Data Lakehouse
    - Data Warehouse
    - Database
    url: /providers/vertica/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.1
    mcp: &id109
      status: unchecked
    slug: webtrends
    status: profiled
    tags: &id110
    - Analytics
    - Digital Analytics
    - Microsoft 365
    - SharePoint
    url: /providers/webtrends/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id111
      source: https://github.com/wrike/datahub-mcp
      status: verified
    slug: wrike
    status: profiled
    tags: &id112
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/wrike/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id113
      status: none
    slug: zendesk
    status: profiled
    tags: &id114
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.6
    band: thin
    in_catalog: true
    kin_score: 33.6
    mcp: &id115
      source: https://help.zoho.com/portal/en/kb/creator/developer-guide/agents/articles/zoho-creator-mcp
      status: verified
    slug: zoho-creator
    status: profiled
    tags: &id116
    - Application Development
    - Forms
    - Low-Code
    - No-Code
    url: /providers/zoho-creator/
  layer: common
  name: Zoho Creator
  provider: zoho-creator
  says: lists Zoho Creator as an integration
  source: https://learn.microsoft.com/en-us/power-query/connectors/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/bi-dashboards/microsoft-power-bi/
providers:
- agent_band: agent-native
  agent_readiness: 60.3
  band: strong
  in_catalog: true
  kin_score: 65.0
  mcp: *id001
  name: Adobe Analytics
  slug: adobe-analytics
  status: profiled
  tags: *id002
  url: /providers/adobe-analytics/
- agent_band: agent-ready
  agent_readiness: 39.8
  band: developing
  in_catalog: true
  kin_score: 45.6
  mcp: *id003
  name: ADP Analytics
  slug: adp
  status: profiled
  tags: *id004
  url: /providers/adp/
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
- agent_band: agent-native
  agent_readiness: 43.6
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id007
  name: Amazon OpenSearch Service
  slug: amazon-opensearch
  status: profiled
  tags: *id008
  url: /providers/amazon-opensearch/
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
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 13.8
  mcp: *id011
  name: Apache Impala
  slug: apache-impala
  status: profiled
  tags: *id012
  url: /providers/apache-impala/
- agent_band: agent-ready
  agent_readiness: 55.3
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id013
  name: Asana
  slug: asana
  status: profiled
  tags: *id014
  url: /providers/asana/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: emerging
  in_catalog: true
  kin_score: 20.0
  mcp: *id015
  name: Attio
  slug: attio
  status: profiled
  tags: *id016
  url: /providers/attio/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 69.0
  mcp: *id017
  name: Autodesk Construction Cloud
  slug: autodesk-construction-cloud
  status: profiled
  tags: *id018
  url: /providers/autodesk-construction-cloud/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id019
  name: Azure Data Explorer (Kusto)
  slug: azure-data-explorer
  status: queued for profiling
  tags: *id020
  url: null
- agent_band: agent-ready
  agent_readiness: 35.3
  band: exemplar
  in_catalog: true
  kin_score: 71.9
  mcp: *id021
  name: Bitbucket
  slug: bitbucket
  status: profiled
  tags: *id022
  url: /providers/bitbucket/
- agent_band: agent-ready
  agent_readiness: 58.2
  band: exemplar
  in_catalog: true
  kin_score: 73.0
  mcp: *id023
  name: Bitly
  slug: bitly
  status: profiled
  tags: *id024
  url: /providers/bitly/
- agent_band: agent-aware
  agent_readiness: 28.3
  band: strong
  in_catalog: true
  kin_score: 55.4
  mcp: *id025
  name: Bloomberg Data and Analytics
  slug: bloomberg
  status: profiled
  tags: *id026
  url: /providers/bloomberg/
- agent_band: agent-ready
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 77.1
  mcp: *id027
  name: ClickHouse
  slug: clickhouse
  status: profiled
  tags: *id028
  url: /providers/clickhouse/
- agent_band: agent-native
  agent_readiness: 65.5
  band: strong
  in_catalog: true
  kin_score: 58.7
  mcp: *id029
  name: Databricks
  slug: databricks
  status: profiled
  tags: *id030
  url: /providers/databricks/
- agent_band: agent-aware
  agent_readiness: 16.5
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id031
  name: Denodo
  slug: denodo
  status: profiled
  tags: *id032
  url: /providers/denodo/
- agent_band: agent-aware
  agent_readiness: 5.8
  band: developing
  in_catalog: true
  kin_score: 51.5
  mcp: *id033
  name: Dremio
  slug: dremio
  status: profiled
  tags: *id034
  url: /providers/dremio/
- agent_band: agent-ready
  agent_readiness: 43.8
  band: exemplar
  in_catalog: true
  kin_score: 85.6
  mcp: *id035
  name: Dynatrace Grail
  slug: dynatrace
  status: profiled
  tags: *id036
  url: /providers/dynatrace/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id037
  name: Elasticsearch
  slug: elastic
  status: profiled
  tags: *id038
  url: /providers/elastic/
- agent_band: agent-aware
  agent_readiness: 15.5
  band: emerging
  in_catalog: true
  kin_score: 22.6
  mcp: *id039
  name: Exasol
  slug: exasol
  status: profiled
  tags: *id040
  url: /providers/exasol/
- agent_band: agent-ready
  agent_readiness: 49.0
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id041
  name: FactSet
  slug: factset
  status: profiled
  tags: *id042
  url: /providers/factset/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 58.7
  mcp: *id043
  name: Funnel
  slug: funnel
  status: profiled
  tags: *id044
  url: /providers/funnel/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id045
  name: GitHub
  slug: github
  status: profiled
  tags: *id046
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id047
  name: Google Analytics 4
  slug: google-analytics
  status: profiled
  tags: *id048
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id049
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id050
  url: /providers/google-bigquery/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id051
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id052
  url: /providers/google-sheets/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.0
  mcp: *id053
  name: IBM Db2
  slug: ibm-db2
  status: profiled
  tags: *id054
  url: /providers/ibm-db2/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.6
  mcp: *id055
  name: IBM Netezza
  slug: netezza
  status: profiled
  tags: *id056
  url: /providers/netezza/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id057
  name: Jamf Pro
  slug: jamf
  status: profiled
  tags: *id058
  url: /providers/jamf/
- agent_band: agent-aware
  agent_readiness: 24.8
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id059
  name: MariaDB
  slug: mariadb
  status: profiled
  tags: *id060
  url: /providers/mariadb/
- agent_band: agent-ready
  agent_readiness: 30.4
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id061
  name: Marketo
  slug: marketo
  status: profiled
  tags: *id062
  url: /providers/marketo/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id063
  name: MarkLogic
  slug: marklogic
  status: queued for profiling
  tags: *id064
  url: null
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 67.0
  mcp: *id065
  name: Microsoft SQL Server
  slug: microsoft-sql-server
  status: profiled
  tags: *id066
  url: /providers/microsoft-sql-server/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id067
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id068
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 59.1
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id069
  name: MongoDB
  slug: mongodb
  status: profiled
  tags: *id070
  url: /providers/mongodb/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id071
  name: MySQL
  slug: mysql
  status: profiled
  tags: *id072
  url: /providers/mysql/
- agent_band: agent-ready
  agent_readiness: 59.8
  band: exemplar
  in_catalog: true
  kin_score: 70.4
  mcp: *id073
  name: Oracle Database
  slug: oracle
  status: profiled
  tags: *id074
  url: /providers/oracle/
- agent_band: agent-aware
  agent_readiness: 17.5
  band: emerging
  in_catalog: true
  kin_score: 24.9
  mcp: *id075
  name: Palantir Foundry
  slug: palantir
  status: profiled
  tags: *id076
  url: /providers/palantir/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id077
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id078
  url: /providers/postgresql/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 80.5
  mcp: *id079
  name: Quickbase
  slug: quickbase
  status: profiled
  tags: *id080
  url: /providers/quickbase/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id081
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id082
  url: /providers/salesforce/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: thin
  in_catalog: true
  kin_score: 32.0
  mcp: *id083
  name: Samsara
  slug: samsara
  status: profiled
  tags: *id084
  url: /providers/samsara/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 44.8
  mcp: *id085
  name: SAP HANA
  slug: sap-hana
  status: profiled
  tags: *id086
  url: /providers/sap-hana/
- agent_band: agent-ready
  agent_readiness: 31.6
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id087
  name: SingleStore
  slug: singlestore
  status: profiled
  tags: *id088
  url: /providers/singlestore/
- agent_band: agent-aware
  agent_readiness: 24.9
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id089
  name: Siteimprove
  slug: siteimprove
  status: profiled
  tags: *id090
  url: /providers/siteimprove/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 41.4
  mcp: *id091
  name: Smartsheet
  slug: smartsheet
  status: profiled
  tags: *id092
  url: /providers/smartsheet/
- agent_band: agent-native
  agent_readiness: 44.9
  band: exemplar
  in_catalog: true
  kin_score: 82.3
  mcp: *id093
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id094
  url: /providers/snowflake/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: thin
  in_catalog: true
  kin_score: 37.1
  mcp: *id095
  name: SparkPost
  slug: sparkpost
  status: profiled
  tags: *id096
  url: /providers/sparkpost/
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id097
  name: Starburst
  slug: starburst
  status: profiled
  tags: *id098
  url: /providers/starburst/
- agent_band: agent-ready
  agent_readiness: 33.4
  band: strong
  in_catalog: true
  kin_score: 58.2
  mcp: *id099
  name: Supermetrics
  slug: supermetrics
  status: profiled
  tags: *id100
  url: /providers/supermetrics/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: thin
  in_catalog: true
  kin_score: 34.9
  mcp: *id101
  name: SurveyMonkey
  slug: surveymonkey
  status: profiled
  tags: *id102
  url: /providers/surveymonkey/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 52.8
  mcp: *id103
  name: Teradata
  slug: teradata
  status: profiled
  tags: *id104
  url: /providers/teradata/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: emerging
  in_catalog: true
  kin_score: 22.9
  mcp: *id105
  name: Vertica
  slug: vertica
  status: profiled
  tags: *id106
  url: /providers/vertica/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id107
  name: Visual Studio App Center Crashes
  slug: microsoft-app-center
  status: queued for profiling
  tags: *id108
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.1
  mcp: *id109
  name: Webtrends Analytics
  slug: webtrends
  status: profiled
  tags: *id110
  url: /providers/webtrends/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id111
  name: Wrike
  slug: wrike
  status: profiled
  tags: *id112
  url: /providers/wrike/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id113
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id114
  url: /providers/zendesk/
- agent_band: agent-aware
  agent_readiness: 26.6
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id115
  name: Zoho Creator
  slug: zoho-creator
  status: profiled
  tags: *id116
  url: /providers/zoho-creator/
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
- name: Redash
  rows: 62
  url: /applications/bi-dashboards/redash/
sitemap: true
title: 'Microsoft Power BI: BI & Dashboards reference app'
---
