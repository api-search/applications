---
app: Hubitat Elevation
app_slug: hubitat-elevation
app_url: https://hubitat.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.60
  key: AE-200.60
  layer: domain
  name: Home Network & DNS Filtering
  providers:
  - Ubiquiti UniFi
  url: /capabilities/home-network-dns-filtering/
  via_parent: null
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
  - Amazon Alexa
  - Apple HomeKit
  - Bond (fan / shade bridge)
  - ecobee
  - Google Assistant / Google Home
  - Govee
  - LIFX
  - Lutron (Caseta)
  - Rachio
  - SharpTools
  - Shelly
  - Signify (Philips Hue, WiZ)
  - Sonos
  - TP-Link (Kasa / Tapo)
  - Tuya
  url: /capabilities/smart-home/
  via_parent: null
category:
  id: smart-home-iot
  name: Smart Home & Home Automation
  url: /applications/smart-home-iot/
counts:
  declared: 17
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://docs2.hubitat.com/en/apps
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
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 46.7
    mcp: &id001
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id002
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: domain
  name: Amazon Alexa
  provider: amazon
  says: lists Amazon Alexa as an integration
  source: https://docs2.hubitat.com/en/apps
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
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
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
  name: Apple HomeKit
  provider: apple
  says: lists Apple HomeKit as an integration
  source: https://docs2.hubitat.com/en/apps
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
    agent_readiness: 12.9
    band: emerging
    in_catalog: true
    kin_score: 25.2
    mcp: &id005
      status: none
    slug: bond-home
    status: profiled
    tags: &id006
    - Company
    - Home Automation
    - IoT
    - Smart Home
    url: /providers/bond-home/
  layer: domain
  name: Bond (fan / shade bridge)
  provider: bond-home
  says: lists Bond (fan / shade bridge) as an integration
  source: https://docs2.hubitat.com/en/apps
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
    agent_readiness: 21.3
    band: thin
    in_catalog: true
    kin_score: 28.2
    mcp: &id007
      status: none
    slug: ecobee
    status: profiled
    tags: &id008
    - HVAC
    - IoT
    - Smart Home
    - Thermostat
    url: /providers/ecobee/
  layer: domain
  name: ecobee
  provider: ecobee
  says: lists ecobee as an integration
  source: https://docs2.hubitat.com/en/apps
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
    agent_readiness: 17.2
    band: thin
    in_catalog: true
    kin_score: 28.7
    mcp: &id009
      status: unknown
    slug: google-assistant
    status: profiled
    tags: &id010
    - Actions on Google
    - Conversational AI
    - Google Assistant
    - Natural-Language
    url: /providers/google-assistant/
  layer: domain
  name: Google Assistant / Google Home
  provider: google-assistant
  says: lists Google Assistant / Google Home as an integration
  source: https://docs2.hubitat.com/en/apps
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
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id011
      status: unknown
    slug: govee
    status: profiled
    tags: &id012
    - IoT
    - LED
    - Smart Home
    - Smart Lighting
    url: /providers/govee/
  layer: domain
  name: Govee
  provider: govee
  says: lists Govee as an integration
  source: https://docs2.hubitat.com/en/apps
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
    agent_band: agent-ready
    agent_readiness: 31.3
    band: thin
    in_catalog: true
    kin_score: 37.5
    mcp: &id013
      status: none
    slug: lifx
    status: profiled
    tags: &id014
    - Home Automation
    - Lighting Fixtures
    - Smart Lighting
    - Wi‑Fi Bulbs
    url: /providers/lifx/
  layer: domain
  name: LIFX
  provider: lifx
  says: lists LIFX as an integration
  source: https://docs2.hubitat.com/en/apps
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
    kin_score: 3.2
    mcp: &id015
      status: unknown
    slug: lutron
    status: profiled
    tags: &id016
    - Company
    - Home Automation
    - Lighting
    - Smart Home
    url: /providers/lutron/
  layer: domain
  name: Lutron (Caseta)
  provider: lutron
  says: lists Lutron (Caseta) as an integration
  source: https://docs2.hubitat.com/en/apps
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
    agent_band: agent-ready
    agent_readiness: 30.8
    band: strong
    in_catalog: true
    kin_score: 56.7
    mcp: &id017
      status: unknown
    slug: rachio
    status: profiled
    tags: &id018
    - Company
    - IoT
    - Irrigation
    - Smart Home
    url: /providers/rachio/
  layer: domain
  name: Rachio
  provider: rachio
  says: lists Rachio as an integration
  source: https://docs2.hubitat.com/en/apps
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
    mcp: &id019
      status: none
    slug: ring
    status: profiled
    tags: &id020
    - Company
    - Home Security
    - IoT
    - Smart Home
    url: /providers/ring/
  layer: domain
  name: Ring
  provider: ring
  says: lists Ring as an integration
  source: https://docs2.hubitat.com/en/apps
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
    agent_readiness: 20.1
    band: thin
    in_catalog: true
    kin_score: 26.9
    mcp: &id021
      status: none
    slug: sharptools
    status: profiled
    tags: &id022
    - Automation
    - Dashboards
    - Rule Engine
    - Smart Home
    url: /providers/sharptools/
  layer: domain
  name: SharpTools
  provider: sharptools
  says: lists SharpTools as an integration
  source: https://docs2.hubitat.com/en/apps
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
    kin_score: 9.7
    mcp: &id023
      source: https://shelly-api-docs.shelly.cloud/mcp
      status: verified
    slug: shelly
    status: profiled
    tags: &id024
    - Company
    - Devices
    - IoT
    - Smart Home
    url: /providers/shelly/
  layer: domain
  name: Shelly
  provider: shelly
  says: lists Shelly as an integration
  source: https://docs2.hubitat.com/en/apps
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
    mcp: &id025
      status: unknown
    slug: signify
    status: profiled
    tags: &id026
    - Company
    - IoT
    - Lighting
    - Smart Home
    url: /providers/signify/
  layer: domain
  name: Signify (Philips Hue, WiZ)
  provider: signify
  says: lists Signify (Philips Hue, WiZ) as an integration
  source: https://docs2.hubitat.com/en/apps
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
    agent_readiness: 23.6
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id027
      status: none
    slug: sonos
    status: profiled
    tags: &id028
    - Audio
    - Company
    - Consumer
    - Music
    url: /providers/sonos/
  layer: domain
  name: Sonos
  provider: sonos
  says: lists Sonos as an integration
  source: https://docs2.hubitat.com/en/apps
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
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 6.9
    mcp: &id029
      status: unknown
    slug: tp-link
    status: profiled
    tags: &id030
    - Cloud
    - Company
    - Hardware
    - Networking
    url: /providers/tp-link/
  layer: domain
  name: TP-Link (Kasa / Tapo)
  provider: tp-link
  says: lists TP-Link (Kasa / Tapo) as an integration
  source: https://docs2.hubitat.com/en/apps
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
    agent_readiness: 25.8
    band: thin
    in_catalog: true
    kin_score: 31.9
    mcp: &id031
      source: https://github.com/tuya/tuya-mcp-sdk
      status: verified
    slug: tuya
    status: profiled
    tags: &id032
    - Cloud Platform
    - Devices
    - IoT
    - Smart Home
    url: /providers/tuya/
  layer: domain
  name: Tuya
  provider: tuya
  says: lists Tuya as an integration
  source: https://docs2.hubitat.com/en/apps
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.60
    key: AE-200.60
    name: Home Network & DNS Filtering
    url: /capabilities/home-network-dns-filtering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.9
    band: developing
    in_catalog: true
    kin_score: 46.3
    mcp: &id033
      status: none
    slug: ubiquiti
    status: profiled
    tags: &id034
    - Networking
    - Routing
    - Switching
    - Wi-Fi
    url: /providers/ubiquiti/
  layer: domain
  name: Ubiquiti UniFi
  provider: ubiquiti
  says: lists Ubiquiti UniFi as an integration
  source: https://docs2.hubitat.com/en/apps
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/smart-home-iot/hubitat-elevation/
providers:
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id001
  name: Amazon Alexa
  slug: amazon
  status: profiled
  tags: *id002
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id003
  name: Apple HomeKit
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 12.9
  band: emerging
  in_catalog: true
  kin_score: 25.2
  mcp: *id005
  name: Bond (fan / shade bridge)
  slug: bond-home
  status: profiled
  tags: *id006
  url: /providers/bond-home/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: thin
  in_catalog: true
  kin_score: 28.2
  mcp: *id007
  name: ecobee
  slug: ecobee
  status: profiled
  tags: *id008
  url: /providers/ecobee/
- agent_band: agent-aware
  agent_readiness: 17.2
  band: thin
  in_catalog: true
  kin_score: 28.7
  mcp: *id009
  name: Google Assistant / Google Home
  slug: google-assistant
  status: profiled
  tags: *id010
  url: /providers/google-assistant/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id011
  name: Govee
  slug: govee
  status: profiled
  tags: *id012
  url: /providers/govee/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 37.5
  mcp: *id013
  name: LIFX
  slug: lifx
  status: profiled
  tags: *id014
  url: /providers/lifx/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.2
  mcp: *id015
  name: Lutron (Caseta)
  slug: lutron
  status: profiled
  tags: *id016
  url: /providers/lutron/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: strong
  in_catalog: true
  kin_score: 56.7
  mcp: *id017
  name: Rachio
  slug: rachio
  status: profiled
  tags: *id018
  url: /providers/rachio/
- agent_band: agent-ready
  agent_readiness: 34.1
  band: developing
  in_catalog: true
  kin_score: 43.9
  mcp: *id019
  name: Ring
  slug: ring
  status: profiled
  tags: *id020
  url: /providers/ring/
- agent_band: agent-aware
  agent_readiness: 20.1
  band: thin
  in_catalog: true
  kin_score: 26.9
  mcp: *id021
  name: SharpTools
  slug: sharptools
  status: profiled
  tags: *id022
  url: /providers/sharptools/
- agent_band: human-only
  agent_readiness: 4.5
  band: minimal
  in_catalog: true
  kin_score: 9.7
  mcp: *id023
  name: Shelly
  slug: shelly
  status: profiled
  tags: *id024
  url: /providers/shelly/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.4
  mcp: *id025
  name: Signify (Philips Hue, WiZ)
  slug: signify
  status: profiled
  tags: *id026
  url: /providers/signify/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id027
  name: Sonos
  slug: sonos
  status: profiled
  tags: *id028
  url: /providers/sonos/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 6.9
  mcp: *id029
  name: TP-Link (Kasa / Tapo)
  slug: tp-link
  status: profiled
  tags: *id030
  url: /providers/tp-link/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 31.9
  mcp: *id031
  name: Tuya
  slug: tuya
  status: profiled
  tags: *id032
  url: /providers/tuya/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: developing
  in_catalog: true
  kin_score: 46.3
  mcp: *id033
  name: Ubiquiti UniFi
  slug: ubiquiti
  status: profiled
  tags: *id034
  url: /providers/ubiquiti/
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
- name: openHAB
  rows: 39
  url: /applications/smart-home-iot/openhab/
- name: SmartThings
  rows: 8
  url: /applications/smart-home-iot/smartthings/
sitemap: true
title: 'Hubitat Elevation: Smart Home & Home Automation reference app'
---
