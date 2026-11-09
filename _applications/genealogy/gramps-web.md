---
app: Gramps Web
app_slug: gramps-web
app_url: https://github.com/gramps-project/gramps-web
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230
  key: AE-230
  layer: domain
  name: Data & Reference Information Services
  providers:
  - Wikidata SPARQL buildings layer (query.wikidata.org)
  url: /capabilities/data-reference-information-services/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.110
  key: AE-230.110
  layer: domain
  name: Genealogy Records & Family Trees
  providers:
  - CompGen DES / domus.genealogy.net historical building map
  url: /capabilities/genealogy-records-family-trees/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.20.10
  key: AE-120.20.10
  layer: common
  name: Base Map Tiles
  providers:
  - OpenFreeMap vector styles (tiles.openfreemap.org)
  - OpenHistoricalMap time-aware basemap style
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: common
  name: Forward Geocoding
  providers:
  - Nominatim place search (nominatim.openstreetmap.org)
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Redis as Celery broker (celery[redis])
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry error monitoring (sentry-sdk[flask])
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google OIDC sign-in (accounts.google.com)
  - Microsoft OIDC sign-in (login.microsoftonline.com)
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - S3 media storage (boto3, api/s3.py)
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - OpenAI-compatible LLM via pydantic-ai[openai] (LLM_BASE_URL)
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: genealogy
  name: Genealogy & Family History
  url: /applications/genealogy/
counts:
  declared: 0
  observed: 11
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/gramps-project/gramps-web-api/blob/master/pyproject.toml
- route: dependency manifest
  url: https://github.com/gramps-project/gramps-web/blob/main/package.json
- route: source code
  url: https://github.com/gramps-project/gramps-web-api/blob/master/gramps_webapi/auth/oidc.py
- route: source code
  url: https://github.com/gramps-project/gramps-web-api/blob/master/gramps_webapi/config.py
- route: source code
  url: https://github.com/gramps-project/gramps-web-api/blob/master/gramps_webapi/const.py
- route: source code
  url: https://github.com/gramps-project/gramps-web/blob/main/src/components/GrampsjsMap.js
- route: source code
  url: https://github.com/gramps-project/gramps-web/blob/main/src/components/GrampsjsMapSearchbox.js
- route: source code
  url: https://github.com/gramps-project/gramps-web/blob/main/src/wikidata.ts
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-230.110
    key: AE-230.110
    name: Genealogy Records & Family Trees
    url: /capabilities/genealogy-records-family-trees/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 10.9
    mcp: &id001
      status: none
    slug: compgen
    status: profiled
    tags: &id002
    - Data
    - Genealogy
    - History
    - Non-Profit
    url: /providers/compgen/
  layer: domain
  name: CompGen DES / domus.genealogy.net historical building map
  provider: compgen
  says: ships the CompGen DES / domus.genealogy.net historical building map SDK or integration code
  source: https://github.com/gramps-project/gramps-web/blob/main/src/wikidata.ts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id003
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id004
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google OIDC sign-in (accounts.google.com)
  provider: google-identity-platform
  says: ships the Google OIDC sign-in (accounts.google.com) SDK or integration code
  source: https://github.com/gramps-project/gramps-web-api/blob/master/gramps_webapi/auth/oidc.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 57.9
    band: exemplar
    in_catalog: true
    kin_score: 89.0
    mcp: &id005
      source: https://learn.microsoft.com/en-us/graph/mcp-server/overview
      status: verified
    slug: azure-ad
    status: profiled
    tags: &id006
    - Authentication
    - Authorization
    - Identity
    - OAuth
    url: /providers/azure-ad/
  layer: common
  name: Microsoft OIDC sign-in (login.microsoftonline.com)
  provider: azure-ad
  says: ships the Microsoft OIDC sign-in (login.microsoftonline.com) SDK or integration code
  source: https://github.com/gramps-project/gramps-web-api/blob/master/gramps_webapi/auth/oidc.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.9
    band: developing
    in_catalog: true
    kin_score: 42.4
    mcp: &id007
      status: none
    slug: nominatim
    status: profiled
    tags: &id008
    - Geocoding
    - Location Services
    - Maps
    - OpenStreetMap
    url: /providers/nominatim/
  layer: common
  name: Nominatim place search (nominatim.openstreetmap.org)
  provider: nominatim
  says: ships the Nominatim place search (nominatim.openstreetmap.org) SDK or integration code
  source: https://github.com/gramps-project/gramps-web/blob/main/src/components/GrampsjsMapSearchbox.js
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id009
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI-compatible LLM via pydantic-ai[openai] (LLM_BASE_URL)
  provider: openai
  says: ships the OpenAI-compatible LLM via pydantic-ai[openai] (LLM_BASE_URL) SDK or integration code
  source: https://github.com/gramps-project/gramps-web-api/blob/master/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.9
    mcp: &id011
      status: none
    slug: openfreemap
    status: profiled
    tags: &id012
    - Company
    - GIS
    - Mapping
    - Open Source
    url: /providers/openfreemap/
  layer: common
  name: OpenFreeMap vector styles (tiles.openfreemap.org)
  provider: openfreemap
  says: ships the OpenFreeMap vector styles (tiles.openfreemap.org) SDK or integration code
  source: https://github.com/gramps-project/gramps-web/blob/main/src/components/GrampsjsMap.js
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.6
    mcp: &id013
      status: none
    slug: openhistoricalmap
    status: profiled
    tags: &id014
    - Historical
    - Mapping
    - Non-Profit
    - Open Source
    url: /providers/openhistoricalmap/
  layer: domain
  name: OpenHistoricalMap time-aware basemap style
  provider: openhistoricalmap
  says: ships the OpenHistoricalMap time-aware basemap style SDK or integration code
  source: https://github.com/gramps-project/gramps-web/blob/main/src/components/GrampsjsMap.js
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
    agent_readiness: 49.8
    band: developing
    in_catalog: true
    kin_score: 47.4
    mcp: &id015
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id016
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: common
  name: Redis as Celery broker (celery[redis])
  provider: redis
  says: ships the Redis as Celery broker (celery[redis]) SDK or integration code
  source: https://github.com/gramps-project/gramps-web-api/blob/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
    mcp: &id017
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id018
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: S3 media storage (boto3, api/s3.py)
  provider: amazon-s3
  says: ships the S3 media storage (boto3, api/s3.py) SDK or integration code
  source: https://github.com/gramps-project/gramps-web-api/blob/master/pyproject.toml
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
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id019
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id020
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry error monitoring (sentry-sdk[flask])
  provider: sentry-system
  says: ships the Sentry error monitoring (sentry-sdk[flask]) SDK or integration code
  source: https://github.com/gramps-project/gramps-web-api/blob/master/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230
    key: AE-230
    name: Data & Reference Information Services
    url: /capabilities/data-reference-information-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: developing
    in_catalog: true
    kin_score: 52.0
    mcp: &id021
      source: https://www.wikidata.org/wiki/Wikidata:MCP
      status: verified
    slug: wikidata
    status: profiled
    tags: &id022
    - Knowledge Graph
    - Linked Data
    - Open Data
    - Semantic Web
    url: /providers/wikidata/
  layer: domain
  name: Wikidata SPARQL buildings layer (query.wikidata.org)
  provider: wikidata
  says: ships the Wikidata SPARQL buildings layer (query.wikidata.org) SDK or integration code
  source: https://github.com/gramps-project/gramps-web/blob/main/src/wikidata.ts
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/genealogy/gramps-web/
providers:
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 10.9
  mcp: *id001
  name: CompGen DES / domus.genealogy.net historical building map
  slug: compgen
  status: profiled
  tags: *id002
  url: /providers/compgen/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id003
  name: Google OIDC sign-in (accounts.google.com)
  slug: google-identity-platform
  status: profiled
  tags: *id004
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 57.9
  band: exemplar
  in_catalog: true
  kin_score: 89.0
  mcp: *id005
  name: Microsoft OIDC sign-in (login.microsoftonline.com)
  slug: azure-ad
  status: profiled
  tags: *id006
  url: /providers/azure-ad/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: developing
  in_catalog: true
  kin_score: 42.4
  mcp: *id007
  name: Nominatim place search (nominatim.openstreetmap.org)
  slug: nominatim
  status: profiled
  tags: *id008
  url: /providers/nominatim/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id009
  name: OpenAI-compatible LLM via pydantic-ai[openai] (LLM_BASE_URL)
  slug: openai
  status: profiled
  tags: *id010
  url: /providers/openai/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id011
  name: OpenFreeMap vector styles (tiles.openfreemap.org)
  slug: openfreemap
  status: profiled
  tags: *id012
  url: /providers/openfreemap/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.6
  mcp: *id013
  name: OpenHistoricalMap time-aware basemap style
  slug: openhistoricalmap
  status: profiled
  tags: *id014
  url: /providers/openhistoricalmap/
- agent_band: agent-native
  agent_readiness: 49.8
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id015
  name: Redis as Celery broker (celery[redis])
  slug: redis
  status: profiled
  tags: *id016
  url: /providers/redis/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id017
  name: S3 media storage (boto3, api/s3.py)
  slug: amazon-s3
  status: profiled
  tags: *id018
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id019
  name: Sentry error monitoring (sentry-sdk[flask])
  slug: sentry-system
  status: profiled
  tags: *id020
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id021
  name: Wikidata SPARQL buildings layer (query.wikidata.org)
  slug: wikidata
  status: profiled
  tags: *id022
  url: /providers/wikidata/
siblings:
- name: Ancestry
  rows: 8
  url: /applications/genealogy/ancestry/
- name: Family Tree Maker
  rows: 2
  url: /applications/genealogy/family-tree-maker/
- name: FamilySearch
  rows: 3
  url: /applications/genealogy/familysearch/
- name: RootsMagic
  rows: 4
  url: /applications/genealogy/rootsmagic/
- name: webtrees
  rows: 13
  url: /applications/genealogy/webtrees/
sitemap: true
title: 'Gramps Web: Genealogy & Family History reference app'
---
