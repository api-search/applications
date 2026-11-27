---
app: IHateMoney
app_slug: ihatemoney
app_url: https://github.com/spiral-project/ihatemoney
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.20.10
  key: AE-230.20.10
  layer: domain
  name: Exchange Rates
  providers:
  - exchangerate.host
  url: /capabilities/market-financial-data/
  via_parent: Market & Financial Data
category:
  id: expense-management
  name: Expense & Spend Management
  url: /applications/expense-management/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/spiral-project/ihatemoney/master/pyproject.toml
- route: source code
  url: https://raw.githubusercontent.com/spiral-project/ihatemoney/master/ihatemoney/currency_convertor.py
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-230.20.10
    key: AE-230.20.10
    name: Exchange Rates
    url: /capabilities/market-financial-data/
    via_parent: Market & Financial Data
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.0
    mcp: &id001
      status: none
    slug: exchangerate-host
    status: profiled
    tags: &id002
    - Exchange Rates
    - Foreign Exchange
    - Public APIs
    url: /providers/exchangerate-host/
  layer: domain
  name: exchangerate.host
  provider: exchangerate-host
  says: ships the exchangerate.host SDK or integration code
  source: https://raw.githubusercontent.com/spiral-project/ihatemoney/master/ihatemoney/currency_convertor.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/expense-management/ihatemoney/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.0
  mcp: *id001
  name: exchangerate.host
  slug: exchangerate-host
  status: profiled
  tags: *id002
  url: /providers/exchangerate-host/
siblings:
- name: Brex
  rows: 82
  url: /applications/expense-management/brex/
- name: Expensify
  rows: 82
  url: /applications/expense-management/expensify/
- name: Ramp
  rows: 62
  url: /applications/expense-management/ramp/
- name: SAP Concur
  rows: 3
  url: /applications/expense-management/sap-concur/
- name: Spliit
  rows: 4
  url: /applications/expense-management/spliit/
- name: Splitwise
  rows: 2
  url: /applications/expense-management/splitwise/
sitemap: true
title: 'IHateMoney: Expense & Spend Management reference app'
---
