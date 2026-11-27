---
app: Wallet by BudgetBakers
app_slug: wallet-by-budgetbakers
app_url: https://budgetbakers.com/en/products/wallet/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-190.50
  key: AE-190.50
  layer: domain
  name: Consumer Data Access
  providers:
  - Salt Edge
  url: /capabilities/consumer-data-access/
  via_parent: null
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: common
  name: Customer Lifecycle Engagement
  providers:
  - MoEngage
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase
  - Mixpanel
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: personal-finance-budgeting
  name: Personal Finance & Budgeting
  url: /applications/personal-finance-budgeting/
counts:
  declared: 1
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.droid4you.application.wallet/latest/
- route: documentation
  url: https://budgetbakers.com/en/legal/saltedge-privacy/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id001
      status: none
    slug: facebook
    status: profiled
    tags: &id002
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.droid4you.application.wallet/latest/
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
    mcp: &id003
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id004
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.droid4you.application.wallet/latest/
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
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id005
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id006
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.droid4you.application.wallet/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-native
    agent_readiness: 65.1
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id007
      status: none
    slug: moengage
    status: profiled
    tags: &id008
    - Customer Data Platform
    - Customer Engagement
    - Marketing Automation
    - Push Notifications
    url: /providers/moengage/
  layer: common
  name: MoEngage
  provider: moengage
  says: ships the MoEngage SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.droid4you.application.wallet/latest/
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
    agent_band: agent-aware
    agent_readiness: 21.9
    band: emerging
    in_catalog: true
    kin_score: 26.1
    mcp: &id009
      status: none
    slug: salt-edge
    status: profiled
    tags: &id010
    - Aggregator
    - Fintech
    - Open Banking
    - PSD2
    url: /providers/salt-edge/
  layer: domain
  name: Salt Edge
  provider: salt-edge
  says: lists Salt Edge as an integration
  source: https://budgetbakers.com/en/legal/saltedge-privacy/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/personal-finance-budgeting/wallet-by-budgetbakers/
providers:
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id001
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id002
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id003
  name: Firebase
  slug: google-firebase
  status: profiled
  tags: *id004
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id005
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id006
  url: /providers/mixpanel/
- agent_band: agent-native
  agent_readiness: 65.1
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id007
  name: MoEngage
  slug: moengage
  status: profiled
  tags: *id008
  url: /providers/moengage/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: emerging
  in_catalog: true
  kin_score: 26.1
  mcp: *id009
  name: Salt Edge
  slug: salt-edge
  status: profiled
  tags: *id010
  url: /providers/salt-edge/
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
- name: YNAB
  rows: 7
  url: /applications/personal-finance-budgeting/ynab/
sitemap: true
title: 'Wallet by BudgetBakers: Personal Finance & Budgeting reference app'
---
