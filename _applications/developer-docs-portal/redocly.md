---
app: Redocly
app_slug: redocly
app_url: https://redocly.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - Azure DevOps
  - Bitbucket Cloud
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - RudderStack
  - Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Adobe Analytics
  - Amplitude
  - Fullstory
  - Google Analytics
  - Heap
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
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Auth0
  - Google Workspace
  - Microsoft Entra ID
  - Okta
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: developer-docs-portal
  name: Developer Docs & API Portals
  url: /applications/developer-docs-portal/
counts:
  declared: 16
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://redocly.com/llms.txt
integrations:
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
  layer: common
  name: Adobe Analytics
  provider: adobe-analytics
  says: lists Adobe Analytics as an integration
  source: https://redocly.com/docs/platform/config/analytics/adobe.md
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
    agent_readiness: 56.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id003
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id004
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: lists Amplitude as an integration
  source: https://redocly.com/docs/platform/config/analytics/amplitude.md
  tier: declared
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
    agent_readiness: 39.5
    band: exemplar
    in_catalog: true
    kin_score: 71.8
    mcp: &id005
      source: https://auth0.com/docs/get-started/auth0-mcp-server
      status: verified
    slug: auth0
    status: profiled
    tags: &id006
    - AI Agents
    - Auth0
    - Authentication
    - Authorization
    url: /providers/auth0/
  layer: common
  name: Auth0
  provider: auth0
  says: lists Auth0 as an integration
  source: https://redocly.com/docs/platform/organization/sso/configure-auth0.md
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
    agent_readiness: 37.7
    band: exemplar
    in_catalog: true
    kin_score: 81.9
    mcp: &id007
      source: https://github.com/microsoft/azure-devops-mcp
      status: verified
    slug: microsoft-azure-devops
    status: profiled
    tags: &id008
    - Agile
    - CI/CD
    - DevOps
    - Developer Tools
    url: /providers/microsoft-azure-devops/
  layer: domain
  name: Azure DevOps
  provider: microsoft-azure-devops
  says: lists Azure DevOps as an integration
  source: https://redocly.com/docs/platform/project/connect-git/azure-devops.md
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
    mcp: &id009
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: bitbucket
    status: profiled
    tags: &id010
    - Atlassian
    - CI/CD
    - Code Collaboration
    - Code Review
    url: /providers/bitbucket/
  layer: domain
  name: Bitbucket Cloud
  provider: bitbucket
  says: lists Bitbucket Cloud as an integration
  source: https://redocly.com/docs/platform/project/connect-git/bitbucket-cloud.md
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
    agent_readiness: 30.0
    band: thin
    in_catalog: true
    kin_score: 37.4
    mcp: &id011
      source: https://developer.fullstory.com/mcp/introduction/
      status: documented
    slug: fullstory
    status: profiled
    tags: &id012
    - Behavioral Analytics
    - Digital Experience
    - Product Analytics
    - Session Replay
    url: /providers/fullstory/
  layer: common
  name: Fullstory
  provider: fullstory
  says: lists Fullstory as an integration
  source: https://redocly.com/docs/platform/config/analytics/fullstory.md
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
    mcp: &id013
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id014
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://redocly.com/docs/platform/project/connect-git/github.md
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
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id015
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id016
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: lists GitLab as an integration
  source: https://redocly.com/docs/platform/project/connect-git/gitlab.md
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
    mcp: &id017
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id018
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://redocly.com/docs/platform/config/analytics/google.md
  tier: declared
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
    mcp: &id019
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id020
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: lists Google Tag Manager as an integration
  source: https://redocly.com/docs/platform/config/analytics/gtm.md
  tier: declared
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
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id021
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id022
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: common
  name: Google Workspace
  provider: google-workspace
  says: lists Google Workspace as an integration
  source: https://redocly.com/docs/platform/organization/sso/configure-google-sso.md
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
    agent_readiness: 26.3
    band: developing
    in_catalog: true
    kin_score: 40.6
    mcp: &id023
      status: unknown
    slug: heap
    status: profiled
    tags: &id024
    - Analytics
    - Autocapture
    - Digital Analytics
    - Product Analytics
    url: /providers/heap/
  layer: common
  name: Heap
  provider: heap
  says: lists Heap as an integration
  source: https://redocly.com/docs/platform/config/analytics/heap.md
  tier: declared
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
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id025
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id026
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft Entra ID
  provider: microsoft-entra
  says: lists Microsoft Entra ID as an integration
  source: https://redocly.com/docs/platform/organization/sso/configure-azure-ad.md
  tier: declared
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
    agent_readiness: 47.1
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id027
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id028
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://redocly.com/docs/platform/organization/sso/configure-okta.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.9
    band: exemplar
    in_catalog: true
    kin_score: 79.1
    mcp: &id029
      source: https://github.com/rudderlabs/rudderstack-mcp
      status: verified
    slug: rudderstack
    status: profiled
    tags: &id030
    - CDP
    - Customer Data Platform
    - Data Pipeline
    - Open Source
    url: /providers/rudderstack/
  layer: common
  name: RudderStack
  provider: rudderstack
  says: lists RudderStack as an integration
  source: https://redocly.com/docs/platform/config/analytics/rudderstack.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.7
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id031
      status: none
    slug: segment
    status: profiled
    tags: &id032
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: lists Segment as an integration
  source: https://redocly.com/docs/platform/config/analytics/segment.md
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/developer-docs-portal/redocly/
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
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id003
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id004
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 39.5
  band: exemplar
  in_catalog: true
  kin_score: 71.8
  mcp: *id005
  name: Auth0
  slug: auth0
  status: profiled
  tags: *id006
  url: /providers/auth0/
- agent_band: agent-ready
  agent_readiness: 37.7
  band: exemplar
  in_catalog: true
  kin_score: 81.9
  mcp: *id007
  name: Azure DevOps
  slug: microsoft-azure-devops
  status: profiled
  tags: *id008
  url: /providers/microsoft-azure-devops/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: exemplar
  in_catalog: true
  kin_score: 71.9
  mcp: *id009
  name: Bitbucket Cloud
  slug: bitbucket
  status: profiled
  tags: *id010
  url: /providers/bitbucket/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: thin
  in_catalog: true
  kin_score: 37.4
  mcp: *id011
  name: Fullstory
  slug: fullstory
  status: profiled
  tags: *id012
  url: /providers/fullstory/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id013
  name: GitHub
  slug: github
  status: profiled
  tags: *id014
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id015
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id016
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id017
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id018
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id019
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id020
  url: /providers/google-tag-manager/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id021
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id022
  url: /providers/google-workspace/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: developing
  in_catalog: true
  kin_score: 40.6
  mcp: *id023
  name: Heap
  slug: heap
  status: profiled
  tags: *id024
  url: /providers/heap/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id025
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id026
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id027
  name: Okta
  slug: okta
  status: profiled
  tags: *id028
  url: /providers/okta/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: exemplar
  in_catalog: true
  kin_score: 79.1
  mcp: *id029
  name: RudderStack
  slug: rudderstack
  status: profiled
  tags: *id030
  url: /providers/rudderstack/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id031
  name: Segment
  slug: segment
  status: profiled
  tags: *id032
  url: /providers/segment/
siblings:
- name: Backstage
  rows: 37
  url: /applications/developer-docs-portal/backstage/
- name: Docusaurus
  rows: 7
  url: /applications/developer-docs-portal/docusaurus/
- name: GitBook
  rows: 56
  url: /applications/developer-docs-portal/gitbook/
- name: Mintlify
  rows: 49
  url: /applications/developer-docs-portal/mintlify/
- name: ReadMe
  rows: 17
  url: /applications/developer-docs-portal/readme/
- name: Zudoku
  rows: 10
  url: /applications/developer-docs-portal/zudoku/
sitemap: true
title: 'Redocly: Developer Docs & API Portals reference app'
---
