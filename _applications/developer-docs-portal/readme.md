---
app: ReadMe
app_slug: readme
app_url: https://readme.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-909
  key: AE-909
  layer: domain
  name: API Gateways
  providers:
  - Amazon API Gateway
  url: /capabilities/api-consumption-governance/
  via_parent: API Consumption Governance
- attribution: API Evangelist extension
  id: AE-908
  key: AE-908
  layer: domain
  name: API Testing & Mocking
  providers:
  - Postman
  url: /capabilities/public-api-lifecycle-management/
  via_parent: Public API Lifecycle Management
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - Bitbucket
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Google reCAPTCHA
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Intercom
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Google Site Verification
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Microsoft Teams
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Okta
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.70.20
  key: AE-170.70.20
  layer: common
  name: Translation Management & Localization
  providers:
  - Localize
  - Transifex
  url: /capabilities/content-management/
  via_parent: Content Management
- attribution: API Evangelist extension
  id: AE-170.80.10
  key: AE-170.80.10
  layer: common
  name: Web Fonts & Typography
  providers:
  - Adobe Fonts (Typekit)
  url: /capabilities/design-creative-editing/
  via_parent: Design & Creative Editing
category:
  id: developer-docs-portal
  name: Developer Docs & API Portals
  url: /applications/developer-docs-portal/
counts:
  declared: 17
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://docs.readme.com/llms.txt
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.80.10
    key: AE-170.80.10
    name: Web Fonts & Typography
    url: /capabilities/design-creative-editing/
    via_parent: Design & Creative Editing
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.9
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id001
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe
    status: profiled
    tags: &id002
    - Adobe
    - Analytics
    - E-Signature
    - Fortune 1000
    url: /providers/adobe/
  layer: common
  name: Adobe Fonts (Typekit)
  provider: adobe
  says: lists Adobe Fonts (Typekit) as an integration
  source: https://docs.readme.com/main/docs/typekit-key.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-909
    key: AE-909
    name: API Gateways
    url: /capabilities/api-consumption-governance/
    via_parent: API Consumption Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.0
    band: exemplar
    in_catalog: true
    kin_score: 77.4
    mcp: &id003
      status: none
    slug: aws-api-gateway
    status: profiled
    tags: &id004
    - API Gateway
    - Amazon Web Services
    - Cloud
    - REST
    url: /providers/aws-api-gateway/
  layer: domain
  name: Amazon API Gateway
  provider: aws-api-gateway
  says: lists Amazon API Gateway as an integration
  source: https://docs.readme.com/main/docs/aws.md
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
    mcp: &id005
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: bitbucket
    status: profiled
    tags: &id006
    - Atlassian
    - CI/CD
    - Code Collaboration
    - Code Review
    url: /providers/bitbucket/
  layer: domain
  name: Bitbucket
  provider: bitbucket
  says: lists Bitbucket as an integration
  source: https://docs.readme.com/main/docs/sync-with-bitbucket.md
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
    mcp: &id007
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id008
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://docs.readme.com/main/docs/sync-with-github.md
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
    mcp: &id009
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id010
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: lists GitLab as an integration
  source: https://docs.readme.com/main/docs/sync-with-gitlab.md
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
    mcp: &id011
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id012
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://docs.readme.com/main/docs/google-analytics.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id013
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id014
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: lists Google reCAPTCHA as an integration
  source: https://docs.readme.com/main/docs/recaptcha.md
  tier: declared
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
    agent_readiness: 30.7
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id015
      status: none
    slug: google-search-console
    status: profiled
    tags: &id016
    - Analytics
    - Google
    - Indexing
    - Search
    url: /providers/google-search-console/
  layer: common
  name: Google Site Verification
  provider: google-search-console
  says: lists Google Site Verification as an integration
  source: https://docs.readme.com/main/docs/google-site-verification.md
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
    agent_readiness: 32.5
    band: developing
    in_catalog: true
    kin_score: 51.0
    mcp: &id017
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: common
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://docs.readme.com/main/docs/searching-readme-within-the-intercom-widget-changing-so-404-results-rb.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.20
    key: AE-170.70.20
    name: Translation Management & Localization
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id019
      status: unchecked
    slug: localize
    status: queued for profiling
    tags: &id020 []
    url: null
  layer: common
  name: Localize
  provider: localize
  says: lists Localize as an integration
  source: https://docs.readme.com/main/docs/localize.md
  tier: declared
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id021
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id022
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://docs.readme.com/main/docs/microsoft-teams.md
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
    mcp: &id023
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id024
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://docs.readme.com/main/enterprise/setting-up-okta.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-908
    key: AE-908
    name: API Testing & Mocking
    url: /capabilities/public-api-lifecycle-management/
    via_parent: Public API Lifecycle Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id025
      source: https://github.com/postmanlabs/postman-mcp-server
      status: verified
    slug: postman
    status: profiled
    tags: &id026
    - Environment
    - Flow
    - Specification
    - Workspace
    url: /providers/postman/
  layer: domain
  name: Postman
  provider: postman
  says: lists Postman as an integration
  source: https://docs.readme.com/main/docs/postman-1.md
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
    mcp: &id027
      status: none
    slug: segment
    status: profiled
    tags: &id028
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: lists Segment as an integration
  source: https://docs.readme.com/main/docs/segment.md
  tier: declared
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
    mcp: &id029
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id030
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://docs.readme.com/main/docs/slack.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.20
    key: AE-170.70.20
    name: Translation Management & Localization
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.3
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id031
      source: https://help.transifex.com/en/articles/15970082-transifex-mcp-server
      status: documented
    slug: transifex
    status: profiled
    tags: &id032
    - L10n
    - Localization
    - Translation
    - i18n
    url: /providers/transifex/
  layer: common
  name: Transifex
  provider: transifex
  says: lists Transifex as an integration
  source: https://docs.readme.com/main/docs/transifex.md
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
    mcp: &id033
      status: none
    slug: zendesk
    status: profiled
    tags: &id034
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: common
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://docs.readme.com/main/docs/zendesk.md
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/developer-docs-portal/readme/
providers:
- agent_band: agent-ready
  agent_readiness: 62.9
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id001
  name: Adobe Fonts (Typekit)
  slug: adobe
  status: profiled
  tags: *id002
  url: /providers/adobe/
- agent_band: agent-ready
  agent_readiness: 42.0
  band: exemplar
  in_catalog: true
  kin_score: 77.4
  mcp: *id003
  name: Amazon API Gateway
  slug: aws-api-gateway
  status: profiled
  tags: *id004
  url: /providers/aws-api-gateway/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: exemplar
  in_catalog: true
  kin_score: 71.9
  mcp: *id005
  name: Bitbucket
  slug: bitbucket
  status: profiled
  tags: *id006
  url: /providers/bitbucket/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id007
  name: GitHub
  slug: github
  status: profiled
  tags: *id008
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id009
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id010
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id011
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id012
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id013
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id014
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 30.7
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id015
  name: Google Site Verification
  slug: google-search-console
  status: profiled
  tags: *id016
  url: /providers/google-search-console/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id017
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id018
  url: /providers/intercom/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id019
  name: Localize
  slug: localize
  status: queued for profiling
  tags: *id020
  url: null
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id021
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id022
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id023
  name: Okta
  slug: okta
  status: profiled
  tags: *id024
  url: /providers/okta/
- agent_band: agent-ready
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id025
  name: Postman
  slug: postman
  status: profiled
  tags: *id026
  url: /providers/postman/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id027
  name: Segment
  slug: segment
  status: profiled
  tags: *id028
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id029
  name: Slack
  slug: slack
  status: profiled
  tags: *id030
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 28.3
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id031
  name: Transifex
  slug: transifex
  status: profiled
  tags: *id032
  url: /providers/transifex/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id033
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id034
  url: /providers/zendesk/
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
- name: Redocly
  rows: 16
  url: /applications/developer-docs-portal/redocly/
- name: Zudoku
  rows: 10
  url: /applications/developer-docs-portal/zudoku/
sitemap: true
title: 'ReadMe: Developer Docs & API Portals reference app'
---
