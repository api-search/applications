---
app: dlt (dltHub)
app_slug: dlt-dlthub
app_url: https://github.com/dlt-hub/verified-sources
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Microsoft SharePoint
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4210.10
  key: continuous-integration-management
  layer: domain
  name: Continuous Integration Management
  providers:
  - GitHub
  url: /capabilities/continuous-integration-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Pipedrive
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Freshdesk
  - ServiceNow
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Bing Webmaster Tools
  - Facebook / Meta Ads
  - Google Ads
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - Shopify
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: domain
  name: Human Capital Management
  providers:
  - Personio
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: domain
  name: Integration and API Management
  providers:
  - Amazon Kinesis
  - Apache Kafka
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: domain
  name: Managed Operational Databases
  providers:
  - MongoDB
  - PostgreSQL
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: domain
  name: Product Usage Analytics
  providers:
  - Google Analytics
  - Matomo
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Asana
  - Jira
  - Notion
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: domain
  name: Spreadsheets & No-Code Databases
  providers:
  - Airtable
  - Google Sheets
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-300.10
  key: talent-acquisition-management
  layer: domain
  name: Talent Acquisition Management
  providers:
  - Workable
  url: /capabilities/talent-acquisition-management/
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
category:
  id: data-integration-etl
  name: Data Integration & ETL
  url: /applications/data-integration-etl/
counts:
  declared: 0
  observed: 27
credits: []
evidence:
- route: source code
  url: https://github.com/dlt-hub/verified-sources/tree/master/sources
integrations:
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
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id001
      source: https://github.com/Airtable/airtable-mcp-cli
      status: verified
    slug: airtable
    status: profiled
    tags: &id002
    - Application
    - Collaboration
    - Data
    - Database
    url: /providers/airtable/
  layer: domain
  name: Airtable
  provider: airtable
  says: ships the Airtable SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/airtable
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.6
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id003
      status: none
    slug: kinesis
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Analytics
    - Apache Flink
    - Big Data
    url: /providers/kinesis/
  layer: domain
  name: Amazon Kinesis
  provider: kinesis
  says: ships the Amazon Kinesis SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/kinesis
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.8
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id005
      status: none
    slug: apache-kafka
    status: profiled
    tags: &id006
    - Apache Kafka
    - Distributed Systems
    - Event Streaming
    - Messaging
    url: /providers/apache-kafka/
  layer: domain
  name: Apache Kafka
  provider: apache-kafka
  says: ships the Apache Kafka SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/kafka
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
    mcp: &id007
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id008
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
  layer: domain
  name: Asana
  provider: asana
  says: ships the Asana SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/asana_dlt
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.2
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id009
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft
    status: profiled
    tags: &id010
    - Cloud
    - Fortune 100
    - Microsoft
    - Software
    url: /providers/microsoft/
  layer: domain
  name: Bing Webmaster Tools
  provider: microsoft-bing
  says: ships the Bing Webmaster Tools SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/bing_webmaster
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id011
      status: none
    slug: facebook
    status: profiled
    tags: &id012
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook / Meta Ads
  provider: facebook
  says: ships the Facebook / Meta Ads SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/facebook_ads
  tier: observed
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
    agent_readiness: 35.0
    band: thin
    in_catalog: true
    kin_score: 29.7
    mcp: &id013
      status: none
    slug: freshdesk
    status: profiled
    tags: &id014
    - Application
    - Automation
    - Customer Service
    - Help Desk
    url: /providers/freshdesk/
  layer: domain
  name: Freshdesk
  provider: freshdesk
  says: ships the Freshdesk SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/freshdesk
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.10
    key: continuous-integration-management
    name: Continuous Integration Management
    url: /capabilities/continuous-integration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id015
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id016
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/github
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 73.4
    mcp: &id017
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id018
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
  layer: domain
  name: Google Ads
  provider: google-ads
  says: ships the Google Ads SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/google_ads
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
    mcp: &id019
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id020
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: domain
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/google_analytics
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
    mcp: &id021
      status: none
    slug: google-sheets
    status: profiled
    tags: &id022
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: domain
  name: Google Sheets
  provider: google-sheets
  says: ships the Google Sheets SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/google_sheets
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id023
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id024
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: ships the HubSpot SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/hubspot
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
    mcp: &id025
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id026
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Jira
  provider: jira
  says: ships the Jira SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/jira
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
    agent_readiness: 41.3
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id027
      source: https://github.com/matomo-org/plugin-McpServer
      status: verified
    slug: matomo
    status: profiled
    tags: &id028
    - Analytics
    - Open Source
    - Privacy
    - Web Analytics
    url: /providers/matomo/
  layer: domain
  name: Matomo
  provider: matomo
  says: ships the Matomo SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/matomo
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
    agent_band: agent-ready
    agent_readiness: 32.3
    band: strong
    in_catalog: true
    kin_score: 60.9
    mcp: &id029
      source: https://github.com/microsoft/mcp
      status: verified
    slug: sharepoint
    status: profiled
    tags: &id030
    - Collaboration
    - Document Management
    - Enterprise Content Management
    - Intranet
    url: /providers/sharepoint/
  layer: domain
  name: Microsoft SharePoint
  provider: sharepoint
  says: ships the Microsoft SharePoint SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/sharepoint
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
    mcp: &id031
      source: https://github.com/mongodb-js/mongodb-mcp-server
      status: verified
    slug: mongodb
    status: profiled
    tags: &id032
    - Cloud Database
    - Database
    - Document Database
    - NoSQL
    url: /providers/mongodb/
  layer: domain
  name: MongoDB
  provider: mongodb
  says: ships the MongoDB SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/mongodb
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
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id033
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id034
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
  layer: domain
  name: Notion
  provider: notion
  says: ships the Notion SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/notion
  tier: observed
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
    agent_readiness: 41.0
    band: thin
    in_catalog: true
    kin_score: 29.8
    mcp: &id035
      status: none
    slug: personio
    status: profiled
    tags: &id036
    - Applicant Tracking
    - HRIS
    - Human Resources
    - Recruiting
    url: /providers/personio/
  layer: domain
  name: Personio
  provider: personio
  says: ships the Personio SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/personio
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
    agent_readiness: 28.7
    band: strong
    in_catalog: true
    kin_score: 55.3
    mcp: &id037
      status: none
    slug: pipedrive
    status: profiled
    tags: &id038
    - CRM
    - Pipeline Management
    - Sales
    - Software-as-a-Service
    url: /providers/pipedrive/
  layer: domain
  name: Pipedrive
  provider: pipedrive
  says: ships the Pipedrive SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/pipedrive
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
    mcp: &id039
      status: none
    slug: postgresql
    status: profiled
    tags: &id040
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
  layer: domain
  name: PostgreSQL
  provider: postgresql
  says: ships the PostgreSQL SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/pg_replication
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
    mcp: &id041
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id042
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: ships the Salesforce SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/salesforce
  tier: observed
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
    agent_readiness: 42.3
    band: strong
    in_catalog: true
    kin_score: 61.9
    mcp: &id043
      status: none
    slug: servicenow
    status: profiled
    tags: &id044
    - Automation
    - Cloud Services
    - Digital Workflows
    - ServiceNow
    url: /providers/servicenow/
  layer: domain
  name: ServiceNow
  provider: servicenow
  says: ships the ServiceNow SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/servicenow
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.8
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id045
      source: https://shopify.dev/docs/apps/build/devmcp
      status: verified
    slug: shopify
    status: profiled
    tags: &id046
    - Commerce
    - E-Commerce
    - Payments
    - Retail
    url: /providers/shopify/
  layer: domain
  name: Shopify
  provider: shopify
  says: ships the Shopify SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/shopify_dlt
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
    mcp: &id047
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id048
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/slack
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id049
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id050
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/stripe_analytics
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-300.10
    key: talent-acquisition-management
    name: Talent Acquisition Management
    url: /capabilities/talent-acquisition-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.3
    band: thin
    in_catalog: true
    kin_score: 38.1
    mcp: &id051
      source: https://mcp.workable.com/mcp
      status: verified
    slug: workable
    status: profiled
    tags: &id052
    - Applicant Tracking
    - Human Resources
    - Recruiting
    - Sourcing
    url: /providers/workable/
  layer: domain
  name: Workable
  provider: workable
  says: ships the Workable SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/workable
  tier: observed
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
    mcp: &id053
      status: none
    slug: zendesk
    status: profiled
    tags: &id054
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk
  provider: zendesk
  says: ships the Zendesk SDK or integration code
  source: https://github.com/dlt-hub/verified-sources/tree/master/sources/zendesk
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/data-integration-etl/dlt-dlthub/
providers:
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id001
  name: Airtable
  slug: airtable
  status: profiled
  tags: *id002
  url: /providers/airtable/
- agent_band: agent-ready
  agent_readiness: 44.6
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id003
  name: Amazon Kinesis
  slug: kinesis
  status: profiled
  tags: *id004
  url: /providers/kinesis/
- agent_band: agent-aware
  agent_readiness: 27.8
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id005
  name: Apache Kafka
  slug: apache-kafka
  status: profiled
  tags: *id006
  url: /providers/apache-kafka/
- agent_band: agent-ready
  agent_readiness: 55.3
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id007
  name: Asana
  slug: asana
  status: profiled
  tags: *id008
  url: /providers/asana/
- agent_band: agent-ready
  agent_readiness: 30.2
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id009
  name: Bing Webmaster Tools
  slug: microsoft
  status: profiled
  tags: *id010
  url: /providers/microsoft/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id011
  name: Facebook / Meta Ads
  slug: facebook
  status: profiled
  tags: *id012
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: thin
  in_catalog: true
  kin_score: 29.7
  mcp: *id013
  name: Freshdesk
  slug: freshdesk
  status: profiled
  tags: *id014
  url: /providers/freshdesk/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id015
  name: GitHub
  slug: github
  status: profiled
  tags: *id016
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 73.4
  mcp: *id017
  name: Google Ads
  slug: google-ads
  status: profiled
  tags: *id018
  url: /providers/google-ads/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id019
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id020
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id021
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id022
  url: /providers/google-sheets/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id023
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id024
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id025
  name: Jira
  slug: jira
  status: profiled
  tags: *id026
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 41.3
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id027
  name: Matomo
  slug: matomo
  status: profiled
  tags: *id028
  url: /providers/matomo/
- agent_band: agent-ready
  agent_readiness: 32.3
  band: strong
  in_catalog: true
  kin_score: 60.9
  mcp: *id029
  name: Microsoft SharePoint
  slug: sharepoint
  status: profiled
  tags: *id030
  url: /providers/sharepoint/
- agent_band: agent-ready
  agent_readiness: 59.1
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id031
  name: MongoDB
  slug: mongodb
  status: profiled
  tags: *id032
  url: /providers/mongodb/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id033
  name: Notion
  slug: notion
  status: profiled
  tags: *id034
  url: /providers/notion/
- agent_band: agent-ready
  agent_readiness: 41.0
  band: thin
  in_catalog: true
  kin_score: 29.8
  mcp: *id035
  name: Personio
  slug: personio
  status: profiled
  tags: *id036
  url: /providers/personio/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: strong
  in_catalog: true
  kin_score: 55.3
  mcp: *id037
  name: Pipedrive
  slug: pipedrive
  status: profiled
  tags: *id038
  url: /providers/pipedrive/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id039
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id040
  url: /providers/postgresql/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id041
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id042
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: strong
  in_catalog: true
  kin_score: 61.9
  mcp: *id043
  name: ServiceNow
  slug: servicenow
  status: profiled
  tags: *id044
  url: /providers/servicenow/
- agent_band: agent-ready
  agent_readiness: 51.8
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id045
  name: Shopify
  slug: shopify
  status: profiled
  tags: *id046
  url: /providers/shopify/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id047
  name: Slack
  slug: slack
  status: profiled
  tags: *id048
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id049
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id050
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 20.3
  band: thin
  in_catalog: true
  kin_score: 38.1
  mcp: *id051
  name: Workable
  slug: workable
  status: profiled
  tags: *id052
  url: /providers/workable/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id053
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id054
  url: /providers/zendesk/
siblings:
- name: Airbyte
  rows: 135
  url: /applications/data-integration-etl/airbyte/
- name: Apache NiFi
  rows: 35
  url: /applications/data-integration-etl/apache-nifi/
- name: Estuary Flow
  rows: 87
  url: /applications/data-integration-etl/estuary-flow/
- name: Fivetran
  rows: 99
  url: /applications/data-integration-etl/fivetran/
- name: Hightouch
  rows: 12
  url: /applications/data-integration-etl/hightouch/
sitemap: true
title: 'dlt (dltHub): Data Integration & ETL reference app'
---
