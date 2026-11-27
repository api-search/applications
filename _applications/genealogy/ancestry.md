---
app: Ancestry
app_slug: ancestry
app_url: https://www.ancestry.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Salesforce Marketing Cloud
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Branch
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Google CrashLytics
  - New Relic
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook sign-in
  - Google sign-in
  - Sign in with Apple
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: genealogy
  name: Genealogy & Family History
  url: /applications/genealogy/
counts:
  declared: 3
  observed: 5
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
- route: documentation
  url: https://www.ancestry.com/c/legal/privacystatement
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id002
      status: none
    slug: branch-io
    status: profiled
    tags: &id003
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id006
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id007
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google CrashLytics
  provider: firebase
  says: ships the Google CrashLytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id010
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id011
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: ships the New Relic SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id012
      status: none
    slug: salesforce-marketing-cloud
    status: profiled
    tags: &id013
    - Automation
    - Content Management
    - Customer Journey
    - Digital Marketing
    url: /providers/salesforce-marketing-cloud/
  layer: common
  name: Salesforce Marketing Cloud
  provider: salesforce-marketing-cloud
  says: ships the Salesforce Marketing Cloud SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ancestry.android.apps.ancestry/latest/
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id004
      status: none
    slug: facebook
    status: profiled
    tags: &id005
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook sign-in
  provider: facebook
  says: lists Facebook sign-in as an integration
  source: https://www.ancestry.com/c/legal/privacystatement
  tier: declared
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
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id008
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id009
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: lists Google sign-in as an integration
  source: https://www.ancestry.com/c/legal/privacystatement
  tier: declared
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
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id014
      status: none
    slug: apple
    status: profiled
    tags: &id015
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Sign in with Apple
  provider: apple
  says: lists Sign in with Apple as an integration
  source: https://www.ancestry.com/c/legal/privacystatement
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/genealogy/ancestry/
providers:
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id002
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id003
  url: /providers/branch-io/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id004
  name: Facebook sign-in
  slug: facebook
  status: profiled
  tags: *id005
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id006
  name: Google CrashLytics
  slug: google-firebase
  status: profiled
  tags: *id007
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id008
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id009
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id010
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id011
  url: /providers/new-relic/
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id012
  name: Salesforce Marketing Cloud
  slug: salesforce-marketing-cloud
  status: profiled
  tags: *id013
  url: /providers/salesforce-marketing-cloud/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id014
  name: Sign in with Apple
  slug: apple
  status: profiled
  tags: *id015
  url: /providers/apple/
siblings:
- name: Family Tree Maker
  rows: 2
  url: /applications/genealogy/family-tree-maker/
- name: FamilySearch
  rows: 3
  url: /applications/genealogy/familysearch/
- name: Gramps Web
  rows: 11
  url: /applications/genealogy/gramps-web/
- name: RootsMagic
  rows: 4
  url: /applications/genealogy/rootsmagic/
- name: webtrees
  rows: 13
  url: /applications/genealogy/webtrees/
sitemap: true
title: 'Ancestry: Genealogy & Family History reference app'
---
