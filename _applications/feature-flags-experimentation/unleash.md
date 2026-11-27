---
app: Unleash
app_slug: unleash
app_url: https://github.com/Unleash/unleash
author: API Evangelist
capabilities:
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
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Datadog
  - New Relic
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: feature-flags-experimentation
  name: Feature Flags & Experimentation
  url: /applications/feature-flags-experimentation/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/Unleash/unleash/blob/main/package.json
- route: source code
  url: https://github.com/Unleash/unleash/tree/main/src/lib/addons
integrations:
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
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 80.0
    mcp: &id001
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id002
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: ships the Datadog SDK or integration code
  source: https://github.com/Unleash/unleash/tree/main/src/lib/addons
  tier: observed
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
    mcp: &id003
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id004
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: ships the Microsoft Teams SDK or integration code
  source: https://github.com/Unleash/unleash/tree/main/src/lib/addons
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
    agent_readiness: 44.8
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id005
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id006
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: ships the New Relic SDK or integration code
  source: https://github.com/Unleash/unleash/tree/main/src/lib/addons
  tier: observed
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
    mcp: &id007
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id008
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/Unleash/unleash/tree/main/src/lib/addons
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/feature-flags-experimentation/unleash/
providers:
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id001
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id002
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id003
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id004
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id005
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id006
  url: /providers/new-relic/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id007
  name: Slack
  slug: slack
  status: profiled
  tags: *id008
  url: /providers/slack/
siblings:
- name: ConfigCat
  rows: 18
  url: /applications/feature-flags-experimentation/configcat/
- name: Flagsmith
  rows: 16
  url: /applications/feature-flags-experimentation/flagsmith/
- name: Flipt
  rows: 7
  url: /applications/feature-flags-experimentation/flipt/
- name: GrowthBook
  rows: 20
  url: /applications/feature-flags-experimentation/growthbook/
- name: LaunchDarkly
  rows: 91
  url: /applications/feature-flags-experimentation/launchdarkly/
- name: Statsig
  rows: 33
  url: /applications/feature-flags-experimentation/statsig/
sitemap: true
title: 'Unleash: Feature Flags & Experimentation reference app'
---
