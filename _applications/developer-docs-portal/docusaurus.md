---
app: Docusaurus
app_slug: docusaurus
app_url: https://github.com/facebook/docusaurus
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: domain
  name: Search and Discovery Management
  providers:
  - Algolia DocSearch
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics (gtag)
  - Vercel Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
- attribution: API Evangelist extension
  id: AE-926
  key: AE-926
  layer: common
  name: Web Hosting & Control Panels
  providers:
  - GitHub Pages
  - Netlify
  - Vercel
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: developer-docs-portal
  name: Developer Docs & API Portals
  url: /applications/developer-docs-portal/
counts:
  declared: 3
  observed: 4
credits: []
evidence:
- route: documentation
  url: https://github.com/facebook/docusaurus/tree/main/website/docs/deployment
- route: source code
  url: https://github.com/facebook/docusaurus/tree/main/packages
integrations:
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
    agent_readiness: 61.9
    band: exemplar
    in_catalog: true
    kin_score: 81.1
    mcp: &id002
      status: none
    slug: algolia
    status: profiled
    tags: &id003
    - Discovery
    - Personalization
    - Recommendations
    - Search
    url: /providers/algolia/
  layer: domain
  name: Algolia DocSearch
  provider: algolia
  says: ships the Algolia DocSearch SDK or integration code
  source: https://github.com/facebook/docusaurus/tree/main/packages
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
    mcp: &id006
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id007
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics (gtag)
  provider: google-analytics
  says: ships the Google Analytics (gtag) SDK or integration code
  source: https://github.com/facebook/docusaurus/tree/main/packages
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
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 65.8
    mcp: &id008
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id009
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://github.com/facebook/docusaurus/tree/main/packages
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 50.0
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id012
      source: https://vercel.com/docs/mcp/vercel-mcp
      status: verified
    slug: vercel
    status: profiled
    tags: &id013
    - AI Gateway
    - Gateways
    - Observability
    - Webhook
    url: /providers/vercel/
  layer: common
  name: Vercel Analytics
  provider: vercel
  says: ships the Vercel Analytics SDK or integration code
  source: https://github.com/facebook/docusaurus/tree/main/packages
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-926
    key: AE-926
    name: Web Hosting & Control Panels
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id004
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id005
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub Pages
  provider: github
  says: lists GitHub Pages as an integration
  source: https://github.com/facebook/docusaurus/tree/main/website/docs/deployment/github-pages.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-926
    key: AE-926
    name: Web Hosting & Control Panels
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 58.9
    band: exemplar
    in_catalog: true
    kin_score: 72.2
    mcp: &id010
      source: https://github.com/netlify/netlify-mcp
      status: verified
    slug: netlify
    status: profiled
    tags: &id011
    - CDN
    - Cloud
    - Continuous Deployment
    - Developer Tools
    url: /providers/netlify/
  layer: common
  name: Netlify
  provider: netlify
  says: lists Netlify as an integration
  source: https://github.com/facebook/docusaurus/tree/main/website/docs/deployment/netlify.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-926
    key: AE-926
    name: Web Hosting & Control Panels
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts: *id001
  layer: common
  name: Vercel
  provider: vercel
  says: lists Vercel as an integration
  source: https://github.com/facebook/docusaurus/tree/main/website/docs/deployment/vercel.mdx
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/developer-docs-portal/docusaurus/
providers:
- agent_band: agent-ready
  agent_readiness: 61.9
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id002
  name: Algolia DocSearch
  slug: algolia
  status: profiled
  tags: *id003
  url: /providers/algolia/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id004
  name: GitHub Pages
  slug: github
  status: profiled
  tags: *id005
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id006
  name: Google Analytics (gtag)
  slug: google-analytics
  status: profiled
  tags: *id007
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id008
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id009
  url: /providers/google-tag-manager/
- agent_band: agent-ready
  agent_readiness: 58.9
  band: exemplar
  in_catalog: true
  kin_score: 72.2
  mcp: *id010
  name: Netlify
  slug: netlify
  status: profiled
  tags: *id011
  url: /providers/netlify/
- agent_band: agent-ready
  agent_readiness: 50.0
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id012
  name: Vercel Analytics
  slug: vercel
  status: profiled
  tags: *id013
  url: /providers/vercel/
siblings:
- name: Backstage
  rows: 37
  url: /applications/developer-docs-portal/backstage/
- name: GitBook
  rows: 56
  url: /applications/developer-docs-portal/gitbook/
- name: Mintlify
  rows: 49
  url: /applications/developer-docs-portal/mintlify/
- name: ReadMe
  rows: 17
  url: /applications/developer-docs-portal/readme/
- name: Redocly
  rows: 16
  url: /applications/developer-docs-portal/redocly/
- name: Zudoku
  rows: 10
  url: /applications/developer-docs-portal/zudoku/
sitemap: true
title: 'Docusaurus: Developer Docs & API Portals reference app'
---
