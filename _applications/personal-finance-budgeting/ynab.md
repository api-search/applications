---
app: YNAB
app_slug: ynab
app_url: https://www.ynab.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-190.50
  key: AE-190.50
  layer: domain
  name: Consumer Data Access
  providers:
  - Apple (Apple Wallet)
  - MX
  - Plaid
  url: /capabilities/consumer-data-access/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Bugsnag
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amplitude
  - Firebase
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: personal-finance-budgeting
  name: Personal Finance & Budgeting
  url: /applications/personal-finance-budgeting/
counts:
  declared: 4
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.youneedabudget.evergreen.app/latest/
- route: documentation
  url: https://support.ynab.com/en_us/how-direct-import-works-H1IGYLgnxl.md
- route: integrations page
  url: https://api.ynab.com/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 56.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id001
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id002
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: ships the Amplitude SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.youneedabudget.evergreen.app/latest/
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 76.3
    mcp: &id005
      source: https://github.com/SmartBear/smartbear-mcp
      status: verified
    slug: bugsnag
    status: profiled
    tags: &id006
    - Application Performance Monitoring
    - Error Monitoring
    - Monitoring
    - Observability
    url: /providers/bugsnag/
  layer: common
  name: Bugsnag
  provider: bugsnag
  says: ships the Bugsnag SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.youneedabudget.evergreen.app/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id007
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id008
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.youneedabudget.evergreen.app/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-190.50
    key: AE-190.50
    name: Consumer Data Access
    url: /capabilities/consumer-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id003
      status: none
    slug: apple
    status: profiled
    tags: &id004
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple (Apple Wallet)
  provider: apple
  says: lists Apple (Apple Wallet) as an integration
  source: https://support.ynab.com/en_us/how-direct-import-works-H1IGYLgnxl.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-190.50
    key: AE-190.50
    name: Consumer Data Access
    url: /capabilities/consumer-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.6
    band: exemplar
    in_catalog: true
    kin_score: 66.7
    mcp: &id009
      status: none
    slug: mx-technologies
    status: profiled
    tags: &id010
    - Account Aggregation
    - Data Connectivity
    - Financial Data
    - Open Banking
    url: /providers/mx-technologies/
  layer: domain
  name: MX
  provider: mx-technologies
  says: lists MX as an integration
  source: https://support.ynab.com/en_us/how-direct-import-works-H1IGYLgnxl.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-190.50
    key: AE-190.50
    name: Consumer Data Access
    url: /capabilities/consumer-data-access/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 51.1
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id011
      source: https://plaid.com/docs/resources/mcp/
      status: verified
    slug: plaid
    status: profiled
    tags: &id012
    - Bank Accounts
    - Finance
    - Fintech
    - Open Banking
    url: /providers/plaid/
  layer: domain
  name: Plaid
  provider: plaid
  says: lists Plaid as an integration
  source: https://support.ynab.com/en_us/how-direct-import-works-H1IGYLgnxl.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id013
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id014
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://api.ynab.com/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/personal-finance-budgeting/ynab/
providers:
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id001
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id002
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id003
  name: Apple (Apple Wallet)
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 76.3
  mcp: *id005
  name: Bugsnag
  slug: bugsnag
  status: profiled
  tags: *id006
  url: /providers/bugsnag/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id007
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id008
  url: /providers/google-firebase/
- agent_band: agent-aware
  agent_readiness: 26.6
  band: exemplar
  in_catalog: true
  kin_score: 66.7
  mcp: *id009
  name: MX
  slug: mx-technologies
  status: profiled
  tags: *id010
  url: /providers/mx-technologies/
- agent_band: agent-native
  agent_readiness: 51.1
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id011
  name: Plaid
  slug: plaid
  status: profiled
  tags: *id012
  url: /providers/plaid/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id013
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id014
  url: /providers/zapier/
siblings:
- name: Actual Budget
  rows: 5
  url: /applications/personal-finance-budgeting/actual-budget/
- name: Firefly III
  rows: 9
  url: /applications/personal-finance-budgeting/firefly-iii/
- name: Ghostfolio
  rows: 13
  url: /applications/personal-finance-budgeting/ghostfolio/
- name: Maybe
  rows: 10
  url: /applications/personal-finance-budgeting/maybe/
- name: Monarch Money
  rows: 7
  url: /applications/personal-finance-budgeting/monarch-money/
- name: Wallet by BudgetBakers
  rows: 5
  url: /applications/personal-finance-budgeting/wallet-by-budgetbakers/
sitemap: true
title: 'YNAB: Personal Finance & Budgeting reference app'
---
