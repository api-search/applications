---
app: Shlink
app_slug: shlink
app_url: https://github.com/shlinkio/shlink
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: domain
  name: IP Geolocation
  providers:
  - MaxMind GeoLite2
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: API Evangelist extension
  id: AE-913
  key: AE-913
  layer: domain
  name: Link Shortening & Link-in-Bio
  providers:
  - Bitly
  - Kutt
  - YOURLS
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: domain
  name: Product Usage Analytics
  providers:
  - Matomo
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: common
  name: Integration and API Management
  providers:
  - RabbitMQ
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
category:
  id: url-shortener-links
  name: Link Management & URL Shorteners
  url: /applications/url-shortener-links/
counts:
  declared: 0
  observed: 6
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/shlinkio/shlink/blob/develop/composer.json
- route: source code
  url: https://github.com/shlinkio/shlink-importer/tree/main/src/Sources
- route: source code
  url: https://github.com/shlinkio/shlink/tree/develop/config/autoload
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.4
    band: exemplar
    in_catalog: true
    kin_score: 73.7
    mcp: &id001
      source: https://dev.bitly.com/bitly-mcp/
      status: verified
    slug: bitly
    status: profiled
    tags: &id002
    - Analytics
    - Links
    - QR Codes
    - URL Shorteners
    url: /providers/bitly/
  layer: domain
  name: Bitly
  provider: bitly
  says: ships the Bitly SDK or integration code
  source: https://github.com/shlinkio/shlink-importer/tree/main/src/Sources
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.3
    mcp: &id003
      status: none
    slug: kutt
    status: profiled
    tags: &id004
    - Public APIs
    - URL Shorteners
    url: /providers/kutt/
  layer: domain
  name: Kutt
  provider: kutt
  says: ships the Kutt SDK or integration code
  source: https://github.com/shlinkio/shlink-importer/tree/main/src/Sources
  tier: observed
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
    agent_readiness: 37.4
    band: exemplar
    in_catalog: true
    kin_score: 72.2
    mcp: &id005
      source: https://github.com/matomo-org/plugin-McpServer
      status: verified
    slug: matomo
    status: profiled
    tags: &id006
    - Analytics
    - Open Source
    - Privacy
    - Web Analytics
    url: /providers/matomo/
  layer: domain
  name: Matomo
  provider: matomo
  says: ships the Matomo SDK or integration code
  source: https://github.com/shlinkio/shlink/blob/develop/composer.json
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
    agent_band: agent-aware
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id007
      status: none
    slug: maxmind
    status: profiled
    tags: &id008
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: domain
  name: MaxMind GeoLite2
  provider: maxmind
  says: ships the MaxMind GeoLite2 SDK or integration code
  source: https://github.com/shlinkio/shlink/tree/develop/config/autoload/geolite2.global.php
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.0
    band: thin
    in_catalog: true
    kin_score: 29.8
    mcp: &id009
      status: none
    slug: rabbitmq
    status: profiled
    tags: &id010
    - AMQP
    - Distributed Systems
    - Queues
    - RabbitMQ
    url: /providers/rabbitmq/
  layer: common
  name: RabbitMQ
  provider: rabbitmq
  says: ships the RabbitMQ SDK or integration code
  source: https://github.com/shlinkio/shlink/tree/develop/config/autoload/rabbit.global.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 14.8
    mcp: &id011
      status: none
    slug: yourls
    status: profiled
    tags: &id012
    - Company
    - Open Source
    - PHP
    - URL Shorteners
    url: /providers/yourls/
  layer: domain
  name: YOURLS
  provider: yourls
  says: ships the YOURLS SDK or integration code
  source: https://github.com/shlinkio/shlink-importer/tree/main/src/Sources
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/url-shortener-links/shlink/
providers:
- agent_band: agent-ready
  agent_readiness: 59.4
  band: exemplar
  in_catalog: true
  kin_score: 73.7
  mcp: *id001
  name: Bitly
  slug: bitly
  status: profiled
  tags: *id002
  url: /providers/bitly/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.3
  mcp: *id003
  name: Kutt
  slug: kutt
  status: profiled
  tags: *id004
  url: /providers/kutt/
- agent_band: agent-ready
  agent_readiness: 37.4
  band: exemplar
  in_catalog: true
  kin_score: 72.2
  mcp: *id005
  name: Matomo
  slug: matomo
  status: profiled
  tags: *id006
  url: /providers/matomo/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id007
  name: MaxMind GeoLite2
  slug: maxmind
  status: profiled
  tags: *id008
  url: /providers/maxmind/
- agent_band: agent-aware
  agent_readiness: 20.0
  band: thin
  in_catalog: true
  kin_score: 29.8
  mcp: *id009
  name: RabbitMQ
  slug: rabbitmq
  status: profiled
  tags: *id010
  url: /providers/rabbitmq/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 14.8
  mcp: *id011
  name: YOURLS
  slug: yourls
  status: profiled
  tags: *id012
  url: /providers/yourls/
siblings:
- name: Bitly
  rows: 55
  url: /applications/url-shortener-links/bitly/
- name: Dub
  rows: 25
  url: /applications/url-shortener-links/dub/
- name: Kutt
  rows: 1
  url: /applications/url-shortener-links/kutt/
- name: Short.io
  rows: 8
  url: /applications/url-shortener-links/short-io/
- name: Sink
  rows: 5
  url: /applications/url-shortener-links/sink/
- name: YOURLS
  rows: 2
  url: /applications/url-shortener-links/yourls/
sitemap: true
title: 'Shlink: Link Management & URL Shorteners reference app'
---
