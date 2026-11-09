---
app: Actual Budget
app_slug: actual-budget
app_url: https://github.com/actualbudget/actual
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-190.50
  key: AE-190.50
  layer: domain
  name: Consumer Data Access
  providers:
  - Akahu
  - Enable Banking
  - GoCardless Bank Account Data
  - Pluggy
  - SimpleFIN Bridge
  url: /capabilities/consumer-data-access/
  via_parent: null
category:
  id: personal-finance-budgeting
  name: Personal Finance & Budgeting
  url: /applications/personal-finance-budgeting/
counts:
  declared: 0
  observed: 5
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/actualbudget/actual/master/packages/sync-server/package.json
- route: documentation
  url: https://actualbudget.org/docs/advanced/bank-sync/
- route: source code
  url: https://github.com/actualbudget/actual/tree/master/packages/sync-server/src
integrations:
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
    agent_readiness: 33.8
    band: developing
    in_catalog: true
    kin_score: 47.6
    mcp: &id001
      status: none
    slug: akahu
    status: profiled
    tags: &id002
    - Company
    - Finance
    - New Zealand
    - Open Banking
    url: /providers/akahu/
  layer: domain
  name: Akahu
  provider: akahu
  says: ships the Akahu SDK or integration code
  source: https://github.com/actualbudget/actual/tree/master/packages/sync-server/src
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
    agent_readiness: 26.5
    band: developing
    in_catalog: true
    kin_score: 39.9
    mcp: &id003
      status: none
    slug: enable-banking
    status: profiled
    tags: &id004
    - AISP
    - Open Banking
    - PISP
    - PSD2
    url: /providers/enable-banking/
  layer: domain
  name: Enable Banking
  provider: enable-banking
  says: ships the Enable Banking SDK or integration code
  source: https://github.com/actualbudget/actual/tree/master/packages/sync-server/src
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.1
    mcp: &id005
      source: https://github.com/gocardless/gc-mcp
      status: verified
    slug: nordigen
    status: profiled
    tags: &id006
    - Finance
    - Public APIs
    url: /providers/nordigen/
  layer: domain
  name: GoCardless Bank Account Data
  provider: nordigen
  says: ships the GoCardless Bank Account Data SDK or integration code
  source: https://github.com/actualbudget/actual/tree/master/packages/sync-server/src
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
    agent_readiness: 59.4
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id007
      source: https://github.com/pluggyai/pluggy-mcp
      status: verified
    slug: pluggy
    status: profiled
    tags: &id008
    - Banking
    - Company
    - Financial Data
    - Open Finance
    url: /providers/pluggy/
  layer: domain
  name: Pluggy
  provider: pluggy
  says: ships the Pluggy SDK or integration code
  source: https://raw.githubusercontent.com/actualbudget/actual/master/packages/sync-server/package.json
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
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 9.9
    mcp: &id009
      status: none
    slug: simplefin
    status: profiled
    tags: &id010
    - Company
    - Data
    - Finance
    - Open Source
    url: /providers/simplefin/
  layer: domain
  name: SimpleFIN Bridge
  provider: simplefin
  says: ships the SimpleFIN Bridge SDK or integration code
  source: https://github.com/actualbudget/actual/tree/master/packages/sync-server/src
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/personal-finance-budgeting/actual-budget/
providers:
- agent_band: agent-ready
  agent_readiness: 33.8
  band: developing
  in_catalog: true
  kin_score: 47.6
  mcp: *id001
  name: Akahu
  slug: akahu
  status: profiled
  tags: *id002
  url: /providers/akahu/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: developing
  in_catalog: true
  kin_score: 39.9
  mcp: *id003
  name: Enable Banking
  slug: enable-banking
  status: profiled
  tags: *id004
  url: /providers/enable-banking/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.1
  mcp: *id005
  name: GoCardless Bank Account Data
  slug: nordigen
  status: profiled
  tags: *id006
  url: /providers/nordigen/
- agent_band: agent-ready
  agent_readiness: 59.4
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id007
  name: Pluggy
  slug: pluggy
  status: profiled
  tags: *id008
  url: /providers/pluggy/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 9.9
  mcp: *id009
  name: SimpleFIN Bridge
  slug: simplefin
  status: profiled
  tags: *id010
  url: /providers/simplefin/
siblings:
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
- name: YNAB
  rows: 7
  url: /applications/personal-finance-budgeting/ynab/
sitemap: true
title: 'Actual Budget: Personal Finance & Budgeting reference app'
---
