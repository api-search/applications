---
app: Algolia
app_slug: algolia
app_url: https://www.algolia.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Google BigQuery
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.20
  key: AE-140.10.20
  layer: domain
  name: Headless & Composable Commerce
  providers:
  - BigCommerce
  - commercetools
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: Turbo EA
  id: BC-830
  key: knowledge-management
  layer: domain
  name: Knowledge Management
  providers:
  - Zendesk Knowledge Base
  url: /capabilities/knowledge-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: domain
  name: Managed Operational Databases
  providers:
  - MySQL
  - Supabase
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: domain
  name: Search and Discovery Management
  providers:
  - Elasticsearch
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
category:
  id: search-engine
  name: Site & App Search
  url: /applications/search-engine/
counts:
  declared: 7
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.20
    key: AE-140.10.20
    name: Headless & Composable Commerce
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.5
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id001
      source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
      status: verified
    slug: bigcommerce
    status: profiled
    tags: &id002
    - Catalog
    - E-Commerce
    - Order
    - Retail
    url: /providers/bigcommerce/
  layer: domain
  name: BigCommerce
  provider: bigcommerce
  says: lists BigCommerce as an integration
  source: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.20
    key: AE-140.10.20
    name: Headless & Composable Commerce
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.9
    band: strong
    in_catalog: true
    kin_score: 57.5
    mcp: &id003
      source: https://github.com/commercetools/mcp-essentials
      status: verified
    slug: commercetools
    status: profiled
    tags: &id004
    - Commerce
    - Composable Commerce
    - E-Commerce
    - GraphQL
    url: /providers/commercetools/
  layer: domain
  name: commercetools
  provider: commercetools
  says: lists commercetools as an integration
  source: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
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
    agent_band: agent-ready
    agent_readiness: 28.6
    band: exemplar
    in_catalog: true
    kin_score: 70.2
    mcp: &id005
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id006
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: domain
  name: Elasticsearch
  provider: elastic
  says: lists Elasticsearch as an integration
  source: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
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
    agent_readiness: 31.5
    band: developing
    in_catalog: true
    kin_score: 49.7
    mcp: &id007
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id008
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
  layer: domain
  name: Google BigQuery
  provider: google-bigquery
  says: lists Google BigQuery as an integration
  source: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
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
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 31.8
    mcp: &id009
      status: none
    slug: mysql
    status: profiled
    tags: &id010
    - Database
    - Open Source
    - RDBMS
    - Relational Database
    url: /providers/mysql/
  layer: domain
  name: MySQL
  provider: mysql
  says: lists MySQL as an integration
  source: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
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
    agent_readiness: 48.1
    band: developing
    in_catalog: true
    kin_score: 49.1
    mcp: &id011
      source: https://github.com/supabase/mcp
      status: verified
    slug: supabase
    status: profiled
    tags: &id012
    - Authentication
    - Backend-as-a-Service
    - Open Source
    - PostgreSQL
    url: /providers/supabase/
  layer: domain
  name: Supabase
  provider: supabase
  says: lists Supabase as an integration
  source: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id013
      status: none
    slug: zendesk
    status: profiled
    tags: &id014
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk Knowledge Base
  provider: zendesk
  says: lists Zendesk Knowledge Base as an integration
  source: https://www.algolia.com/doc/guides/sending-and-managing-data/send-and-update-your-data/connectors/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/search-engine/algolia/
providers:
- agent_band: agent-ready
  agent_readiness: 60.5
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id001
  name: BigCommerce
  slug: bigcommerce
  status: profiled
  tags: *id002
  url: /providers/bigcommerce/
- agent_band: agent-ready
  agent_readiness: 36.9
  band: strong
  in_catalog: true
  kin_score: 57.5
  mcp: *id003
  name: commercetools
  slug: commercetools
  status: profiled
  tags: *id004
  url: /providers/commercetools/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id005
  name: Elasticsearch
  slug: elastic
  status: profiled
  tags: *id006
  url: /providers/elastic/
- agent_band: agent-ready
  agent_readiness: 31.5
  band: developing
  in_catalog: true
  kin_score: 49.7
  mcp: *id007
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id008
  url: /providers/google-bigquery/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 31.8
  mcp: *id009
  name: MySQL
  slug: mysql
  status: profiled
  tags: *id010
  url: /providers/mysql/
- agent_band: agent-ready
  agent_readiness: 48.1
  band: developing
  in_catalog: true
  kin_score: 49.1
  mcp: *id011
  name: Supabase
  slug: supabase
  status: profiled
  tags: *id012
  url: /providers/supabase/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id013
  name: Zendesk Knowledge Base
  slug: zendesk
  status: profiled
  tags: *id014
  url: /providers/zendesk/
siblings:
- name: Elasticsearch
  rows: 26
  url: /applications/search-engine/elasticsearch/
- name: Meilisearch
  rows: 4
  url: /applications/search-engine/meilisearch/
- name: OpenSearch
  rows: 23
  url: /applications/search-engine/opensearch/
- name: Quickwit
  rows: 8
  url: /applications/search-engine/quickwit/
- name: SearXNG
  rows: 49
  url: /applications/search-engine/searxng/
- name: Typesense
  rows: 5
  url: /applications/search-engine/typesense/
sitemap: true
title: 'Algolia: Site & App Search reference app'
---
