---
app: openIMIS
app_slug: openimis
app_url: https://github.com/openimis
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2900
  key: health-information-management
  layer: domain
  name: Health Information Management
  providers:
  - DHIS2
  url: /capabilities/health-information-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2900.60
  key: healthcare-interoperability-operations
  layer: domain
  name: Healthcare Interoperability Operations
  providers:
  - OpenHIM
  url: /capabilities/healthcare-interoperability-operations/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: common
  name: Integration and API Management
  providers:
  - RabbitMQ
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Microsoft SQL Server
  - Redis
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: common
  name: Search and Discovery Management
  providers:
  - OpenSearch
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
category:
  id: insurance-policy-claims
  name: Insurance Policy & Claims
  url: /applications/insurance-policy-claims/
counts:
  declared: 0
  observed: 6
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/openimis/openimis-be_py/blob/develop/requirements.txt
- route: source code
  url: https://github.com/openimis/openimis-be_py/blob/develop/openimis.json
- route: source code
  url: https://github.com/openimis/openimis_node_openhim_claim_mediator
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2900
    key: health-information-management
    name: Health Information Management
    url: /capabilities/health-information-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.3
    band: developing
    in_catalog: true
    kin_score: 44.3
    mcp: &id001
      status: unchecked
    slug: dhis2
    status: profiled
    tags: &id002
    - Analytics
    - Data Management
    - Health
    - Open Source
    url: /providers/dhis2/
  layer: domain
  name: DHIS2
  provider: dhis2
  says: ships the DHIS2 SDK or integration code
  source: https://github.com/openimis/openimis-be-dhis2_etl_py
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
    mcp: &id003
      source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
      status: verified
    slug: microsoft-sql-server
    status: profiled
    tags: &id004
    - Cloud
    - Data Management
    - Database
    - Enterprise
    url: /providers/microsoft-sql-server/
  layer: common
  name: Microsoft SQL Server
  provider: microsoft-sql-server
  says: ships the Microsoft SQL Server SDK or integration code
  source: https://github.com/openimis/openimis-be_py/blob/develop/requirements.txt
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2900.60
    key: healthcare-interoperability-operations
    name: Healthcare Interoperability Operations
    url: /capabilities/healthcare-interoperability-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.7
    band: emerging
    in_catalog: true
    kin_score: 26.1
    mcp: &id005
      status: unchecked
    slug: openhim
    status: profiled
    tags: &id006
    - Health
    - Integration
    - Middleware
    - Open Source
    url: /providers/openhim/
  layer: domain
  name: OpenHIM
  provider: openhim
  says: ships the OpenHIM SDK or integration code
  source: https://github.com/openimis/openimis_node_openhim_claim_mediator
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
    agent_readiness: 26.3
    band: thin
    in_catalog: true
    kin_score: 37.3
    mcp: &id007
      source: https://github.com/opensearch-project/opensearch-mcp-server-py
      status: verified
    slug: opensearch
    status: profiled
    tags: &id008
    - Analytics
    - Observability
    - OpenSearch
    - Search
    url: /providers/opensearch/
  layer: common
  name: OpenSearch
  provider: opensearch
  says: ships the OpenSearch SDK or integration code
  source: https://github.com/openimis/openimis-be_py/blob/develop/requirements.txt
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
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id009
      status: none
    slug: rabbitmq
    status: profiled
    tags: &id010
    - AMQP
    - Distributed Systems
    - Queues
    - RabbitMQ
    url: /providers/rabbitmq/
  layer: common
  name: RabbitMQ
  provider: rabbitmq
  says: ships the RabbitMQ SDK or integration code
  source: https://github.com/openimis/openimis-be_py/blob/develop/requirements.txt
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
    agent_readiness: 41.5
    band: developing
    in_catalog: true
    kin_score: 46.5
    mcp: &id011
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id012
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: common
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://github.com/openimis/openimis-be_py/blob/develop/requirements.txt
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/insurance-policy-claims/openimis/
providers:
- agent_band: agent-aware
  agent_readiness: 18.3
  band: developing
  in_catalog: true
  kin_score: 44.3
  mcp: *id001
  name: DHIS2
  slug: dhis2
  status: profiled
  tags: *id002
  url: /providers/dhis2/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 67.0
  mcp: *id003
  name: Microsoft SQL Server
  slug: microsoft-sql-server
  status: profiled
  tags: *id004
  url: /providers/microsoft-sql-server/
- agent_band: agent-aware
  agent_readiness: 21.7
  band: emerging
  in_catalog: true
  kin_score: 26.1
  mcp: *id005
  name: OpenHIM
  slug: openhim
  status: profiled
  tags: *id006
  url: /providers/openhim/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: thin
  in_catalog: true
  kin_score: 37.3
  mcp: *id007
  name: OpenSearch
  slug: opensearch
  status: profiled
  tags: *id008
  url: /providers/opensearch/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id009
  name: RabbitMQ
  slug: rabbitmq
  status: profiled
  tags: *id010
  url: /providers/rabbitmq/
- agent_band: agent-ready
  agent_readiness: 41.5
  band: developing
  in_catalog: true
  kin_score: 46.5
  mcp: *id011
  name: Redis
  slug: redis
  status: profiled
  tags: *id012
  url: /providers/redis/
siblings:
- name: Duck Creek
  rows: 11
  url: /applications/insurance-policy-claims/duck-creek/
- name: EZLynx
  rows: 13
  url: /applications/insurance-policy-claims/ezlynx/
- name: HawkSoft
  rows: 12
  url: /applications/insurance-policy-claims/hawksoft/
- name: Lemonade
  rows: 0
  url: /applications/insurance-policy-claims/lemonade/
- name: Socotra
  rows: 12
  url: /applications/insurance-policy-claims/socotra/
sitemap: true
title: 'openIMIS: Insurance Policy & Claims reference app'
---
