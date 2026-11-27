---
app: Flagsmith
app_slug: flagsmith
app_url: https://github.com/Flagsmith/flagsmith
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4210.50
  key: feature-flag-management
  layer: domain
  name: Feature Flag Management
  providers:
  - LaunchDarkly
  url: /capabilities/feature-flag-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280
  key: product-telemetry-experimentation-management
  layer: domain
  name: Product Telemetry & Experimentation Management
  providers:
  - Amplitude
  - Heap
  - Mixpanel
  url: /capabilities/product-telemetry-experimentation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
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
  - Twilio Segment
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Pylon (usepylon.com)
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
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
  - Dynatrace
  - Grafana
  - New Relic
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: feature-flags-experimentation
  name: Feature Flags & Experimentation
  url: /applications/feature-flags-experimentation/
counts:
  declared: 0
  observed: 16
credits: []
evidence:
- route: source code
  url: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
- route: source code
  url: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations/lead_tracking
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: null
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
  layer: domain
  name: Amplitude
  provider: amplitude
  says: ships the Amplitude SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
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
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 80.0
    mcp: &id003
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id004
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: ships the Datadog SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
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
    agent_readiness: 43.8
    band: exemplar
    in_catalog: true
    kin_score: 85.6
    mcp: &id005
      source: https://github.com/dynatrace-oss/dynatrace-mcp
      status: verified
    slug: dynatrace
    status: profiled
    tags: &id006
    - AI Operations
    - APM
    - Analytics
    - Application Performance Monitoring
    url: /providers/dynatrace/
  layer: common
  name: Dynatrace
  provider: dynatrace
  says: ships the Dynatrace SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
  tier: observed
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
  says: ships the GitHub SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
  tier: observed
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
  says: ships the GitLab SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
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
    agent_band: agent-aware
    agent_readiness: 27.6
    band: strong
    in_catalog: true
    kin_score: 66.0
    mcp: &id011
      source: https://github.com/grafana/mcp-grafana
      status: verified
    slug: grafana-com
    status: profiled
    tags: &id012
    - Dashboards
    - Logs
    - Monitoring
    - Observability
    url: /providers/grafana-com/
  layer: common
  name: Grafana
  provider: grafana-com
  says: ships the Grafana SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.3
    band: developing
    in_catalog: true
    kin_score: 40.6
    mcp: &id013
      status: unknown
    slug: heap
    status: profiled
    tags: &id014
    - Analytics
    - Autocapture
    - Digital Analytics
    - Product Analytics
    url: /providers/heap/
  layer: domain
  name: Heap
  provider: heap
  says: ships the Heap SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id015
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id016
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: ships the HubSpot SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations/lead_tracking
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.7
    band: exemplar
    in_catalog: true
    kin_score: 84.5
    mcp: &id017
      source: https://launchdarkly.com/docs/home/getting-started/mcp
      status: verified
    slug: launchdarkly
    status: profiled
    tags: &id018
    - Experimentation
    - Feature Flags
    - Feature Management
    - Observability
    url: /providers/launchdarkly/
  layer: domain
  name: LaunchDarkly
  provider: launchdarkly
  says: ships the LaunchDarkly SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id019
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id020
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: domain
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
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
    mcp: &id021
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id022
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: ships the New Relic SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 32.3
    mcp: &id023
      status: unknown
    slug: pylon
    status: profiled
    tags: &id024
    - Customer Operations
    - Customer Service
    - Knowledge Base
    - Ticketing
    url: /providers/pylon/
  layer: common
  name: Pylon (usepylon.com)
  provider: pylon
  says: ships the Pylon (usepylon.com) SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
  tier: observed
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
    mcp: &id025
      source: https://github.com/rudderlabs/rudderstack-mcp
      status: verified
    slug: rudderstack
    status: profiled
    tags: &id026
    - CDP
    - Customer Data Platform
    - Data Pipeline
    - Open Source
    url: /providers/rudderstack/
  layer: common
  name: RudderStack
  provider: rudderstack
  says: ships the RudderStack SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
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
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id027
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id028
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
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
  says: ships the Slack SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
  tier: observed
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
  name: Twilio Segment
  provider: segment
  says: ships the Twilio Segment SDK or integration code
  source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/feature-flags-experimentation/flagsmith/
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
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id003
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id004
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 43.8
  band: exemplar
  in_catalog: true
  kin_score: 85.6
  mcp: *id005
  name: Dynatrace
  slug: dynatrace
  status: profiled
  tags: *id006
  url: /providers/dynatrace/
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
- agent_band: agent-aware
  agent_readiness: 27.6
  band: strong
  in_catalog: true
  kin_score: 66.0
  mcp: *id011
  name: Grafana
  slug: grafana-com
  status: profiled
  tags: *id012
  url: /providers/grafana-com/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: developing
  in_catalog: true
  kin_score: 40.6
  mcp: *id013
  name: Heap
  slug: heap
  status: profiled
  tags: *id014
  url: /providers/heap/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id015
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id016
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 59.7
  band: exemplar
  in_catalog: true
  kin_score: 84.5
  mcp: *id017
  name: LaunchDarkly
  slug: launchdarkly
  status: profiled
  tags: *id018
  url: /providers/launchdarkly/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id019
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id020
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id021
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id022
  url: /providers/new-relic/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id023
  name: Pylon (usepylon.com)
  slug: pylon
  status: profiled
  tags: *id024
  url: /providers/pylon/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: exemplar
  in_catalog: true
  kin_score: 79.1
  mcp: *id025
  name: RudderStack
  slug: rudderstack
  status: profiled
  tags: *id026
  url: /providers/rudderstack/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id027
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id028
  url: /providers/sentry-system/
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
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id031
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id032
  url: /providers/segment/
siblings:
- name: ConfigCat
  rows: 18
  url: /applications/feature-flags-experimentation/configcat/
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
- name: Unleash
  rows: 4
  url: /applications/feature-flags-experimentation/unleash/
sitemap: true
title: 'Flagsmith: Feature Flags & Experimentation reference app'
---
