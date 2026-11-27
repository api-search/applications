---
app: Umami
app_slug: umami
app_url: https://github.com/umami-software/umami
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - WordPress
  url: /capabilities/content-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: domain
  name: IP Geolocation
  providers:
  - MaxMind GeoIP2
  - Cloudflare
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: domain
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
category:
  id: web-analytics
  name: Web & Product Analytics
  url: /applications/web-analytics/
counts:
  declared: 3
  observed: 1
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/umami-software/umami/master/package.json
- route: documentation
  url: https://umami.is/docs/enable-cloudflare-headers
- route: documentation
  url: https://umami.is/docs/google-tag-manager
- route: documentation
  url: https://umami.is/docs/integrations
- route: documentation
  url: https://umami.is/docs/mcp
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 31.5
    mcp: &id005
      status: none
    slug: maxmind
    status: profiled
    tags: &id006
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: domain
  name: MaxMind GeoIP2
  provider: maxmind
  says: ships the MaxMind GeoIP2 SDK or integration code
  source: https://raw.githubusercontent.com/umami-software/umami/master/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 69.4
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id001
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id002
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: common
  name: Cloudflare
  provider: cloudflare
  says: lists Cloudflare as an integration
  source: https://umami.is/docs/enable-cloudflare-headers
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
    mcp: &id003
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id004
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: domain
  name: Google Tag Manager
  provider: google-tag-manager
  says: lists Google Tag Manager as an integration
  source: https://umami.is/docs/google-tag-manager
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id007
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id008
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: domain
  name: WordPress
  provider: wordpress
  says: lists WordPress as an integration
  source: https://umami.is/docs/integrations
  tier: declared
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/web-analytics/umami/
providers:
- agent_band: agent-native
  agent_readiness: 69.4
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id001
  name: Cloudflare
  slug: cloudflare
  status: profiled
  tags: *id002
  url: /providers/cloudflare/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 65.8
  mcp: *id003
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id004
  url: /providers/google-tag-manager/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id005
  name: MaxMind GeoIP2
  slug: maxmind
  status: profiled
  tags: *id006
  url: /providers/maxmind/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id007
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id008
  url: /providers/wordpress/
siblings:
- name: Amplitude
  rows: 50
  url: /applications/web-analytics/amplitude/
- name: Google Analytics
  rows: 4
  url: /applications/web-analytics/google-analytics/
- name: Matomo
  rows: 18
  url: /applications/web-analytics/matomo/
- name: Mixpanel
  rows: 12
  url: /applications/web-analytics/mixpanel/
- name: Plausible
  rows: 16
  url: /applications/web-analytics/plausible/
- name: PostHog
  rows: 42
  url: /applications/web-analytics/posthog/
sitemap: true
title: 'Umami: Web & Product Analytics reference app'
---
