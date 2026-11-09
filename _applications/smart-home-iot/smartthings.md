---
app: SmartThings
app_slug: smartthings
app_url: https://www.smartthings.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2340.50
  key: physical-security-surveillance-management
  layer: domain
  name: Physical Security & Surveillance Management
  providers:
  - Ring
  url: /capabilities/physical-security-surveillance-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.10
  key: AE-200.10
  layer: domain
  name: Smart Home
  providers:
  - Aqara
  - Eve Systems
  - Google Nest (Smart Device Management)
  - Resideo (Honeywell Home)
  - Signify (Philips Hue, WiZ)
  - Somfy (TaHoma / Overkiz)
  - Yale Home (smart locks)
  url: /capabilities/smart-home/
  via_parent: null
category:
  id: smart-home-iot
  name: Smart Home & Home Automation
  url: /applications/smart-home-iot/
counts:
  declared: 8
  observed: 0
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.samsung.android.oneconnect/latest/
- route: integrations page
  url: https://www.smartthings.com/works-with-smartthings
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.8
    band: thin
    in_catalog: true
    kin_score: 35.6
    mcp: &id001
      source: https://github.com/aqara/aqara-mcp-server
      status: verified
    slug: aqara
    status: profiled
    tags: &id002
    - Consumer Electronics
    - Home Automation
    - IoT
    - Smart Home
    url: /providers/aqara/
  layer: domain
  name: Aqara
  provider: aqara
  says: lists Aqara as an integration
  source: https://www.smartthings.com/works-with-smartthings
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.0
    mcp: &id003
      status: none
    slug: eve-systems
    status: profiled
    tags: &id004
    - Company
    - HomeKit
    - IoT
    - Smart Home
    url: /providers/eve-systems/
  layer: domain
  name: Eve Systems
  provider: eve-systems
  says: lists Eve Systems as an integration
  source: https://www.smartthings.com/works-with-smartthings
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 41.4
    mcp: &id005
      status: none
    slug: google-nest
    status: profiled
    tags: &id006
    - Camera
    - Device Management
    - Doorbell
    - Google Nest
    url: /providers/google-nest/
  layer: domain
  name: Google Nest (Smart Device Management)
  provider: google-nest
  says: lists Google Nest (Smart Device Management) as an integration
  source: https://www.smartthings.com/works-with-smartthings
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.1
    mcp: &id007
      status: unknown
    slug: resideo-technologies
    status: profiled
    tags: &id008 []
    url: /providers/resideo-technologies/
  layer: domain
  name: Resideo (Honeywell Home)
  provider: resideo-technologies
  says: lists Resideo (Honeywell Home) as an integration
  source: https://www.smartthings.com/works-with-smartthings
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2340.50
    key: physical-security-surveillance-management
    name: Physical Security & Surveillance Management
    url: /capabilities/physical-security-surveillance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.1
    band: developing
    in_catalog: true
    kin_score: 43.9
    mcp: &id009
      status: none
    slug: ring
    status: profiled
    tags: &id010
    - Company
    - Home Security
    - IoT
    - Smart Home
    url: /providers/ring/
  layer: domain
  name: Ring
  provider: ring
  says: lists Ring as an integration
  source: https://www.smartthings.com/works-with-smartthings
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.4
    mcp: &id011
      status: unknown
    slug: signify
    status: profiled
    tags: &id012
    - Company
    - IoT
    - Lighting
    - Smart Home
    url: /providers/signify/
  layer: domain
  name: Signify (Philips Hue, WiZ)
  provider: signify
  says: lists Signify (Philips Hue, WiZ) as an integration
  source: https://www.smartthings.com/works-with-smartthings
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.4
    mcp: &id013
      status: unknown
    slug: somfy
    status: profiled
    tags: &id014
    - Company
    - Home Automation
    - IoT
    - Smart Home
    url: /providers/somfy/
  layer: domain
  name: Somfy (TaHoma / Overkiz)
  provider: somfy
  says: lists Somfy (TaHoma / Overkiz) as an integration
  source: https://www.smartthings.com/works-with-smartthings
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 4.5
    band: minimal
    in_catalog: true
    kin_score: 8.6
    mcp: &id015
      status: unknown
    slug: yale-home
    status: profiled
    tags: &id016
    - Company
    - Home Security
    - IoT
    - smart-locks
    url: /providers/yale-home/
  layer: domain
  name: Yale Home (smart locks)
  provider: yale-home
  says: lists Yale Home (smart locks) as an integration
  source: https://www.smartthings.com/works-with-smartthings
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/smart-home-iot/smartthings/
providers:
- agent_band: agent-ready
  agent_readiness: 33.8
  band: thin
  in_catalog: true
  kin_score: 35.6
  mcp: *id001
  name: Aqara
  slug: aqara
  status: profiled
  tags: *id002
  url: /providers/aqara/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.0
  mcp: *id003
  name: Eve Systems
  slug: eve-systems
  status: profiled
  tags: *id004
  url: /providers/eve-systems/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 41.4
  mcp: *id005
  name: Google Nest (Smart Device Management)
  slug: google-nest
  status: profiled
  tags: *id006
  url: /providers/google-nest/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.1
  mcp: *id007
  name: Resideo (Honeywell Home)
  slug: resideo-technologies
  status: profiled
  tags: *id008
  url: /providers/resideo-technologies/
- agent_band: agent-ready
  agent_readiness: 34.1
  band: developing
  in_catalog: true
  kin_score: 43.9
  mcp: *id009
  name: Ring
  slug: ring
  status: profiled
  tags: *id010
  url: /providers/ring/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.4
  mcp: *id011
  name: Signify (Philips Hue, WiZ)
  slug: signify
  status: profiled
  tags: *id012
  url: /providers/signify/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.4
  mcp: *id013
  name: Somfy (TaHoma / Overkiz)
  slug: somfy
  status: profiled
  tags: *id014
  url: /providers/somfy/
- agent_band: human-only
  agent_readiness: 4.5
  band: minimal
  in_catalog: true
  kin_score: 8.6
  mcp: *id015
  name: Yale Home (smart locks)
  slug: yale-home
  status: profiled
  tags: *id016
  url: /providers/yale-home/
siblings:
- name: Frigate
  rows: 4
  url: /applications/smart-home-iot/frigate/
- name: Home Assistant
  rows: 55
  url: /applications/smart-home-iot/home-assistant/
- name: Homebridge
  rows: 38
  url: /applications/smart-home-iot/homebridge/
- name: Hubitat Elevation
  rows: 17
  url: /applications/smart-home-iot/hubitat-elevation/
- name: openHAB
  rows: 39
  url: /applications/smart-home-iot/openhab/
sitemap: true
title: 'SmartThings: Smart Home & Home Automation reference app'
---
