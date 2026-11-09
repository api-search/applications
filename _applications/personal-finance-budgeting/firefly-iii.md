---
app: Firefly III
app_slug: firefly-iii
app_url: https://github.com/firefly-iii/firefly-iii
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
  - Lunch Flow
  - SimpleFIN Bridge
  - Sophtron
  url: /capabilities/consumer-data-access/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150
  key: AE-150
  layer: common
  name: Application Communications
  providers:
  - Slack
  url: /capabilities/application-communications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Pushover
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - MailerSend
  url: /capabilities/email/
  via_parent: Email
category:
  id: personal-finance-budgeting
  name: Personal Finance & Budgeting
  url: /applications/personal-finance-budgeting/
counts:
  declared: 0
  observed: 9
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/firefly-iii/firefly-iii/main/composer.json
- route: source code
  url: https://github.com/firefly-iii/data-importer/tree/main/app/Services
- route: source code
  url: https://github.com/firefly-iii/firefly-iii/blob/main/app/Notifications/ReturnsAvailableChannels.php
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
  source: https://github.com/firefly-iii/data-importer/tree/main/app/Services
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
  source: https://github.com/firefly-iii/data-importer/tree/main/app/Services
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
  source: https://github.com/firefly-iii/data-importer/tree/main/app/Services
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
    agent_readiness: 38.4
    band: thin
    in_catalog: true
    kin_score: 33.1
    mcp: &id007
      source: https://www.lunchflow.app/docs/guides/destinations/mcp
      status: verified
    slug: lunch-flow
    status: profiled
    tags: &id008
    - Banking
    - Fintech
    - Integration
    - OpenAPI
    url: /providers/lunch-flow/
  layer: domain
  name: Lunch Flow
  provider: lunch-flow
  says: ships the Lunch Flow SDK or integration code
  source: https://github.com/firefly-iii/data-importer/tree/main/app/Services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.3
    band: strong
    in_catalog: true
    kin_score: 59.5
    mcp: &id009
      source: https://developers.mailersend.com/mcp-server.html
      status: verified
    slug: mailersend
    status: profiled
    tags: &id010
    - Email
    - Marketing
    - SMTP
    - Transactional Email
    url: /providers/mailersend/
  layer: common
  name: MailerSend
  provider: mailersend
  says: ships the MailerSend SDK or integration code
  source: https://raw.githubusercontent.com/firefly-iii/firefly-iii/main/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.0
    band: thin
    in_catalog: true
    kin_score: 29.2
    mcp: &id011
      status: none
    slug: pushover
    status: profiled
    tags: &id012
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: common
  name: Pushover
  provider: pushover
  says: ships the Pushover SDK or integration code
  source: https://raw.githubusercontent.com/firefly-iii/firefly-iii/main/composer.json
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
    mcp: &id013
      status: none
    slug: simplefin
    status: profiled
    tags: &id014
    - Company
    - Data
    - Finance
    - Open Source
    url: /providers/simplefin/
  layer: domain
  name: SimpleFIN Bridge
  provider: simplefin
  says: ships the SimpleFIN Bridge SDK or integration code
  source: https://github.com/firefly-iii/data-importer/tree/main/app/Services
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150
    key: AE-150
    name: Application Communications
    url: /capabilities/application-communications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id015
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id016
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/firefly-iii/firefly-iii/blob/main/app/Notifications/ReturnsAvailableChannels.php
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
    band: emerging
    in_catalog: true
    kin_score: 15.3
    mcp: &id017
      source: https://sophtron.com/mcp-server/
      status: verified
    slug: sophtron
    status: profiled
    tags: &id018
    - Banking
    - Data Aggregation
    - Financial Services
    - Fintech
    url: /providers/sophtron/
  layer: domain
  name: Sophtron
  provider: sophtron
  says: ships the Sophtron SDK or integration code
  source: https://github.com/firefly-iii/data-importer/tree/main/app/Services
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/personal-finance-budgeting/firefly-iii/
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
  agent_readiness: 38.4
  band: thin
  in_catalog: true
  kin_score: 33.1
  mcp: *id007
  name: Lunch Flow
  slug: lunch-flow
  status: profiled
  tags: *id008
  url: /providers/lunch-flow/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: strong
  in_catalog: true
  kin_score: 59.5
  mcp: *id009
  name: MailerSend
  slug: mailersend
  status: profiled
  tags: *id010
  url: /providers/mailersend/
- agent_band: agent-aware
  agent_readiness: 22.0
  band: thin
  in_catalog: true
  kin_score: 29.2
  mcp: *id011
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id012
  url: /providers/pushover/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 9.9
  mcp: *id013
  name: SimpleFIN Bridge
  slug: simplefin
  status: profiled
  tags: *id014
  url: /providers/simplefin/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id015
  name: Slack
  slug: slack
  status: profiled
  tags: *id016
  url: /providers/slack/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.3
  mcp: *id017
  name: Sophtron
  slug: sophtron
  status: profiled
  tags: *id018
  url: /providers/sophtron/
siblings:
- name: Actual Budget
  rows: 5
  url: /applications/personal-finance-budgeting/actual-budget/
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
title: 'Firefly III: Personal Finance & Budgeting reference app'
---
