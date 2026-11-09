---
app: Wiki.js
app_slug: wiki-js
app_url: https://github.com/requarks/wiki
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.50.30
  key: AE-170.50.30
  layer: domain
  name: Embedded Comments
  providers:
  - Discourse
  - Disqus
  - Hyvor Talk
  url: /capabilities/social-networks-community/
  via_parent: Social Networks & Community
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - Discord
  - GitHub
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Elastic APM
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Baidu Tongji
  - Contentsquare
  - Fathom Analytics
  - Google Analytics
  - Matomo
  - Microsoft Clarity
  - Plausible
  - StatCounter
  - Umami
  - Yandex Metrica
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Azure Blob Storage
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Microsoft Entra ID
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: notes-knowledge
  name: Notes & Personal Knowledge Management
  url: /applications/notes-knowledge/
counts:
  declared: 0
  observed: 21
credits: []
evidence:
- route: source code
  url: https://github.com/requarks/wiki/tree/scarlett/backend/modules
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id001
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id002
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/storage/azure
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
    agent_band: agent-aware
    agent_readiness: 6.0
    band: emerging
    in_catalog: true
    kin_score: 18.5
    mcp: &id003
      source: https://github.com/baidu-maps/mcp
      status: verified
    slug: baidu
    status: profiled
    tags: &id004
    - Artificial Intelligence
    - Company
    - Machine Learning
    - Technology
    url: /providers/baidu/
  layer: common
  name: Baidu Tongji
  provider: baidu
  says: ships the Baidu Tongji SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/baidu
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
    agent_readiness: 47.6
    band: thin
    in_catalog: true
    kin_score: 34.0
    mcp: &id005
      status: none
    slug: contentsquare
    status: profiled
    tags: &id006
    - Digital Experience Analytics
    - Heatmaps
    - Product Analytics
    - Session Replay
    url: /providers/contentsquare/
  layer: common
  name: Contentsquare
  provider: contentsquare
  says: ships the Contentsquare SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/contentsquare
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
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id007
      status: none
    slug: discord
    status: profiled
    tags: &id008
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/authentication/discord
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.30
    key: AE-170.50.30
    name: Embedded Comments
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: thin
    in_catalog: true
    kin_score: 37.1
    mcp: &id009
      source: https://github.com/discourse/discourse-mcp
      status: verified
    slug: discourse
    status: profiled
    tags: &id010
    - Community
    - Forums
    - Open Source
    url: /providers/discourse/
  layer: domain
  name: Discourse
  provider: discourse
  says: ships the Discourse SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/comments/discourse
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.30
    key: AE-170.50.30
    name: Embedded Comments
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.1
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id011
      status: none
    slug: disqus
    status: profiled
    tags: &id012
    - Comments
    - Community
    - Discussions
    - Publishing
    url: /providers/disqus/
  layer: domain
  name: Disqus
  provider: disqus
  says: ships the Disqus SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/comments/disqus
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
    agent_readiness: 28.6
    band: exemplar
    in_catalog: true
    kin_score: 70.2
    mcp: &id013
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id014
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: common
  name: Elastic APM
  provider: elastic
  says: ships the Elastic APM SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/elasticapm
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
    agent_band: agent-aware
    agent_readiness: 25.4
    band: developing
    in_catalog: true
    kin_score: 49.7
    mcp: &id015
      status: none
    slug: fathom
    status: profiled
    tags: &id016
    - Analytics
    - GDPR
    - Privacy
    - Website Analytics
    url: /providers/fathom/
  layer: common
  name: Fathom Analytics
  provider: fathom
  says: ships the Fathom Analytics SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/fathom
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
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id017
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id018
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/authentication/github
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
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
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
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/google
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
    agent_band: agent-ready
    agent_readiness: 45.3
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id021
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id022
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/storage/gcs
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
    mcp: &id023
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id024
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: domain
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/authentication/google
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.2
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id025
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id026
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/gtm
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.30
    key: AE-170.50.30
    name: Embedded Comments
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 18.3
    mcp: &id027
      status: none
    slug: hyvor-talk
    status: profiled
    tags: &id028
    - Comments
    - Engagement
    - Platform
    - Software-as-a-Service
    url: /providers/hyvor-talk/
  layer: domain
  name: Hyvor Talk
  provider: hyvor-talk
  says: ships the Hyvor Talk SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/comments/hyvortalk
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
    agent_readiness: 37.4
    band: exemplar
    in_catalog: true
    kin_score: 72.2
    mcp: &id029
      source: https://github.com/matomo-org/plugin-McpServer
      status: verified
    slug: matomo
    status: profiled
    tags: &id030
    - Analytics
    - Open Source
    - Privacy
    - Web Analytics
    url: /providers/matomo/
  layer: common
  name: Matomo
  provider: matomo
  says: ships the Matomo SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/matomo
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
    agent_readiness: 30.0
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id031
      source: https://github.com/microsoft/clarity-mcp-server
      status: verified
    slug: microsoft-clarity
    status: profiled
    tags: &id032
    - Analytics
    - Heatmaps
    - Session Recording
    - Web Analytics
    url: /providers/microsoft-clarity/
  layer: common
  name: Microsoft Clarity
  provider: microsoft-clarity
  says: ships the Microsoft Clarity SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/clarity
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id033
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id034
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft Entra ID
  provider: microsoft-entra
  says: ships the Microsoft Entra ID SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/authentication/entra
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
    agent_band: agent-aware
    agent_readiness: 23.1
    band: strong
    in_catalog: true
    kin_score: 63.4
    mcp: &id035
      status: none
    slug: plausible
    status: profiled
    tags: &id036
    - Analytics
    - Cookie-Free
    - Event Tracking
    - GDPR
    url: /providers/plausible/
  layer: common
  name: Plausible
  provider: plausible
  says: ships the Plausible SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/plausible
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
    agent_band: agent-aware
    agent_readiness: 18.7
    band: emerging
    in_catalog: true
    kin_score: 17.3
    mcp: &id037
      source: https://statcounter.com/api/docs/mcp
      status: verified
    slug: statcounter
    status: profiled
    tags: &id038
    - Analytics
    - Company
    - Real-Time
    - Web
    url: /providers/statcounter/
  layer: common
  name: StatCounter
  provider: statcounter
  says: ships the StatCounter SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/statcounter
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
    agent_readiness: 38.4
    band: exemplar
    in_catalog: true
    kin_score: 73.3
    mcp: &id039
      status: none
    slug: umami
    status: profiled
    tags: &id040
    - Cookieless Tracking
    - Open Source
    - Privacy
    - Web Analytics
    url: /providers/umami/
  layer: common
  name: Umami
  provider: umami
  says: ships the Umami SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/umami
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
    band: minimal
    in_catalog: true
    kin_score: 9.6
    mcp: &id041
      status: none
    slug: yandex-metrica
    status: profiled
    tags: &id042
    - Analytics
    - Marketing
    - Web Analytics
    - Yandex
    url: /providers/yandex-metrica/
  layer: common
  name: Yandex Metrica
  provider: yandex-metrica
  says: ships the Yandex Metrica SDK or integration code
  source: https://github.com/requarks/wiki/tree/scarlett/backend/modules/analytics/yandex
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/notes-knowledge/wiki-js/
providers:
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id001
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id002
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-aware
  agent_readiness: 6.0
  band: emerging
  in_catalog: true
  kin_score: 18.5
  mcp: *id003
  name: Baidu Tongji
  slug: baidu
  status: profiled
  tags: *id004
  url: /providers/baidu/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: thin
  in_catalog: true
  kin_score: 34.0
  mcp: *id005
  name: Contentsquare
  slug: contentsquare
  status: profiled
  tags: *id006
  url: /providers/contentsquare/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id007
  name: Discord
  slug: discord
  status: profiled
  tags: *id008
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: thin
  in_catalog: true
  kin_score: 37.1
  mcp: *id009
  name: Discourse
  slug: discourse
  status: profiled
  tags: *id010
  url: /providers/discourse/
- agent_band: agent-aware
  agent_readiness: 21.1
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id011
  name: Disqus
  slug: disqus
  status: profiled
  tags: *id012
  url: /providers/disqus/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id013
  name: Elastic APM
  slug: elastic
  status: profiled
  tags: *id014
  url: /providers/elastic/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: developing
  in_catalog: true
  kin_score: 49.7
  mcp: *id015
  name: Fathom Analytics
  slug: fathom
  status: profiled
  tags: *id016
  url: /providers/fathom/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id017
  name: GitHub
  slug: github
  status: profiled
  tags: *id018
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id019
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id020
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id021
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id022
  url: /providers/gcp-cloud-storage/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id023
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id024
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 38.2
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id025
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id026
  url: /providers/google-tag-manager/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 18.3
  mcp: *id027
  name: Hyvor Talk
  slug: hyvor-talk
  status: profiled
  tags: *id028
  url: /providers/hyvor-talk/
- agent_band: agent-ready
  agent_readiness: 37.4
  band: exemplar
  in_catalog: true
  kin_score: 72.2
  mcp: *id029
  name: Matomo
  slug: matomo
  status: profiled
  tags: *id030
  url: /providers/matomo/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id031
  name: Microsoft Clarity
  slug: microsoft-clarity
  status: profiled
  tags: *id032
  url: /providers/microsoft-clarity/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id033
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id034
  url: /providers/microsoft-entra/
- agent_band: agent-aware
  agent_readiness: 23.1
  band: strong
  in_catalog: true
  kin_score: 63.4
  mcp: *id035
  name: Plausible
  slug: plausible
  status: profiled
  tags: *id036
  url: /providers/plausible/
- agent_band: agent-aware
  agent_readiness: 18.7
  band: emerging
  in_catalog: true
  kin_score: 17.3
  mcp: *id037
  name: StatCounter
  slug: statcounter
  status: profiled
  tags: *id038
  url: /providers/statcounter/
- agent_band: agent-ready
  agent_readiness: 38.4
  band: exemplar
  in_catalog: true
  kin_score: 73.3
  mcp: *id039
  name: Umami
  slug: umami
  status: profiled
  tags: *id040
  url: /providers/umami/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.6
  mcp: *id041
  name: Yandex Metrica
  slug: yandex-metrica
  status: profiled
  tags: *id042
  url: /providers/yandex-metrica/
siblings:
- name: AFFiNE
  rows: 16
  url: /applications/notes-knowledge/affine/
- name: BookStack
  rows: 11
  url: /applications/notes-knowledge/bookstack/
- name: Joplin
  rows: 5
  url: /applications/notes-knowledge/joplin/
- name: Logseq
  rows: 3
  url: /applications/notes-knowledge/logseq/
- name: Notion
  rows: 12
  url: /applications/notes-knowledge/notion/
- name: Obsidian
  rows: 0
  url: /applications/notes-knowledge/obsidian/
- name: Outline
  rows: 18
  url: /applications/notes-knowledge/outline/
sitemap: true
title: 'Wiki.js: Notes & Personal Knowledge Management reference app'
---
