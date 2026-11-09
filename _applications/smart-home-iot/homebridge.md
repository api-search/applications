---
app: Homebridge
app_slug: homebridge
app_url: https://github.com/homebridge/homebridge
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.30.10
  key: AE-200.30.10
  layer: domain
  name: Dynamic Electricity Tariffs
  providers:
  - Tibber
  url: /capabilities/home-energy/
  via_parent: Home Energy
- attribution: API Evangelist extension
  id: AE-200.30
  key: AE-200.30
  layer: domain
  name: Home Energy
  providers:
  - Enphase Envoy
  url: /capabilities/home-energy/
  via_parent: null
- attribution: Turbo EA
  id: BC-2340.50
  key: physical-security-surveillance-management
  layer: domain
  name: Physical Security & Surveillance Management
  providers:
  - Blink (Amazon cameras)
  - eufy (Anker)
  - EZVIZ
  - Ring
  - SimpliSafe
  url: /capabilities/physical-security-surveillance-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.90
  key: AE-170.90
  layer: domain
  name: Self-Hosted Media Servers & Library Automation
  providers:
  - Plex
  url: /capabilities/self-hosted-media-servers-library-automation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.10
  key: AE-200.10
  layer: domain
  name: Smart Home
  providers:
  - Airthings
  - August Home
  - Bond (fan / shade bridge)
  - Chamberlain myQ
  - Daikin
  - ECOVACS
  - eWeLink (ITEAD / Sonoff)
  - Google Nest (Smart Device Management)
  - Govee
  - Home Connect (BSH appliances)
  - iRobot
  - LG ThinQ
  - LIFX
  - Lutron (Caseta)
  - Meross
  - Miele
  - Nuki
  - Rachio
  - Rain Bird
  - Resideo (Honeywell Home)
  - Samsung SmartThings
  - Sensibo
  - Shelly
  - Signify (Philips Hue, WiZ)
  - Sonos
  - SwitchBot
  - tado
  - TP-Link (Kasa / Tapo)
  - Tuya
  url: /capabilities/smart-home/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.20.10
  key: AE-200.20.10
  layer: domain
  name: Vehicle Data Access
  providers:
  - Tesla (Fleet API)
  url: /capabilities/connected-vehicles/
  via_parent: Connected Vehicles
category:
  id: smart-home-iot
  name: Smart Home & Home Automation
  url: /applications/smart-home-iot/
counts:
  declared: 38
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    agent_readiness: 36.7
    band: developing
    in_catalog: true
    kin_score: 47.1
    mcp: &id001
      status: none
    slug: airthings
    status: profiled
    tags: &id002
    - Air Quality
    - Company
    - Radon
    - Sensors
    url: /providers/airthings/
  layer: domain
  name: Airthings
  provider: airthings
  says: lists Airthings as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    agent_readiness: 13.8
    band: emerging
    in_catalog: true
    kin_score: 16.9
    mcp: &id003
      status: unknown
    slug: august
    status: profiled
    tags: &id004
    - Company
    - Consumer
    - Smart Home
    - Smart Lock
    url: /providers/august/
  layer: domain
  name: August Home
  provider: august
  says: lists August Home as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id005
      status: unchecked
    slug: blink-home
    status: queued for profiling
    tags: &id006 []
    url: null
  layer: domain
  name: Blink (Amazon cameras)
  provider: blink-home
  says: lists Blink (Amazon cameras) as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    mcp: &id007
      status: none
    slug: bond-home
    status: profiled
    tags: &id008
    - Company
    - Home Automation
    - IoT
    - Smart Home
    url: /providers/bond-home/
  layer: domain
  name: Bond (fan / shade bridge)
  provider: bond-home
  says: lists Bond (fan / shade bridge) as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    kin_score: 3.1
    mcp: &id009
      status: unknown
    slug: chamberlain
    status: profiled
    tags: &id010
    - Company
    - Garage Door
    - IoT
    - Smart Home
    url: /providers/chamberlain/
  layer: domain
  name: Chamberlain myQ
  provider: chamberlain
  says: lists Chamberlain myQ as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    kin_score: 3.1
    mcp: &id011
      status: unknown
    slug: daikin
    status: profiled
    tags: &id012
    - Air Conditioning
    - Company
    - HVAC
    - Refrigeration
    url: /providers/daikin/
  layer: domain
  name: Daikin
  provider: daikin
  says: lists Daikin as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    band: emerging
    in_catalog: true
    kin_score: 11.0
    mcp: &id013
      source: https://github.com/ecovacs-ai/ecovacs-mcp
      status: verified
    slug: ecovacs-robotics
    status: profiled
    tags: &id014
    - Company
    - Consumer Technology
    - Home Automation
    - Robotics
    url: /providers/ecovacs-robotics/
  layer: domain
  name: ECOVACS
  provider: ecovacs-robotics
  says: lists ECOVACS as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: AE-200.30
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.9
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id015
      status: none
    slug: enphase
    status: profiled
    tags: &id016
    - DER
    - Energy
    - Solar
    - United States
    url: /providers/enphase/
  layer: domain
  name: Enphase Envoy
  provider: enphase
  says: lists Enphase Envoy as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.1
    mcp: &id017
      status: unknown
    slug: anker-innovations
    status: profiled
    tags: &id018
    - Company
    - Consumer Electronics
    - Consumer Technology
    - Smart Home
    url: /providers/anker-innovations/
  layer: domain
  name: eufy (Anker)
  provider: anker-innovations
  says: lists eufy (Anker) as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    kin_score: 9.8
    mcp: &id019
      status: none
    slug: ewelink
    status: profiled
    tags: &id020
    - Automation
    - Cloud Platform
    - IoT
    - Smart Home
    url: /providers/ewelink/
  layer: domain
  name: eWeLink (ITEAD / Sonoff)
  provider: ewelink
  says: lists eWeLink (ITEAD / Sonoff) as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id021
      status: unknown
    slug: ezviz
    status: profiled
    tags: &id022
    - Security Cameras
    - Smart Entry
    - Smart Home
    - Smart Home Appliance
    url: /providers/ezviz/
  layer: domain
  name: EZVIZ
  provider: ezviz
  says: lists EZVIZ as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    mcp: &id023
      status: none
    slug: google-nest
    status: profiled
    tags: &id024
    - Camera
    - Device Management
    - Doorbell
    - Google Nest
    url: /providers/google-nest/
  layer: domain
  name: Google Nest (Smart Device Management)
  provider: google-nest
  says: lists Google Nest (Smart Device Management) as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    mcp: &id025
      status: unknown
    slug: govee
    status: profiled
    tags: &id026
    - IoT
    - LED
    - Smart Home
    - Smart Lighting
    url: /providers/govee/
  layer: domain
  name: Govee
  provider: govee
  says: lists Govee as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    agent_readiness: 23.8
    band: thin
    in_catalog: true
    kin_score: 28.6
    mcp: &id027
      status: unknown
    slug: home-connect
    status: profiled
    tags: &id028
    - Appliances
    - Connected Devices
    - Smart Home
    url: /providers/home-connect/
  layer: domain
  name: Home Connect (BSH appliances)
  provider: home-connect
  says: lists Home Connect (BSH appliances) as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    kin_score: 5.6
    mcp: &id029
      status: unknown
    slug: irobot
    status: profiled
    tags: &id030
    - Consumer Robotics
    - Home Robotics
    - Robot Vacuums
    - Robotics
    url: /providers/irobot/
  layer: domain
  name: iRobot
  provider: irobot
  says: lists iRobot as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    kin_score: 4.6
    mcp: &id031
      status: unknown
    slug: lg-electronics
    status: profiled
    tags: &id032
    - Company
    - Consumer Electronics
    - IoT
    - Smart Home
    url: /providers/lg-electronics/
  layer: domain
  name: LG ThinQ
  provider: lg-electronics
  says: lists LG ThinQ as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    mcp: &id033
      status: none
    slug: lifx
    status: profiled
    tags: &id034
    - Home Automation
    - Lighting Fixtures
    - Smart Lighting
    - Wi‑Fi Bulbs
    url: /providers/lifx/
  layer: domain
  name: LIFX
  provider: lifx
  says: lists LIFX as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    mcp: &id035
      status: unknown
    slug: lutron
    status: profiled
    tags: &id036
    - Company
    - Home Automation
    - Lighting
    - Smart Home
    url: /providers/lutron/
  layer: domain
  name: Lutron (Caseta)
  provider: lutron
  says: lists Lutron (Caseta) as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    band: emerging
    in_catalog: true
    kin_score: 11.9
    mcp: &id037
      status: unknown
    slug: meross
    status: profiled
    tags: &id038
    - Automation
    - Consumer
    - IoT
    - Smart Home
    url: /providers/meross/
  layer: domain
  name: Meross
  provider: meross
  says: lists Meross as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    agent_readiness: 21.8
    band: emerging
    in_catalog: true
    kin_score: 24.9
    mcp: &id039
      status: unknown
    slug: miele
    status: profiled
    tags: &id040
    - Appliances
    - Company
    - Homes
    - Technology
    url: /providers/miele/
  layer: domain
  name: Miele
  provider: miele
  says: lists Miele as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    agent_readiness: 25.4
    band: emerging
    in_catalog: true
    kin_score: 19.6
    mcp: &id041
      status: none
    slug: nuki
    status: profiled
    tags: &id042
    - Company
    - Home Automation
    - IoT
    - Smart Lock
    url: /providers/nuki/
  layer: domain
  name: Nuki
  provider: nuki
  says: lists Nuki as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.6
    band: strong
    in_catalog: true
    kin_score: 55.9
    mcp: &id043
      status: none
    slug: plex
    status: profiled
    tags: &id044
    - Company
    - Media
    - Streaming
    - Video
    url: /providers/plex/
  layer: domain
  name: Plex
  provider: plex
  says: lists Plex as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    mcp: &id045
      status: unknown
    slug: rachio
    status: profiled
    tags: &id046
    - Company
    - IoT
    - Irrigation
    - Smart Home
    url: /providers/rachio/
  layer: domain
  name: Rachio
  provider: rachio
  says: lists Rachio as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    band: emerging
    in_catalog: true
    kin_score: 15.2
    mcp: &id047
      status: unknown
    slug: rainbird
    status: profiled
    tags: &id048
    - Agriculture
    - Company
    - Irrigation
    - Water Management
    url: /providers/rainbird/
  layer: domain
  name: Rain Bird
  provider: rainbird
  says: lists Rain Bird as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    mcp: &id049
      status: unknown
    slug: resideo-technologies
    status: profiled
    tags: &id050 []
    url: /providers/resideo-technologies/
  layer: domain
  name: Resideo (Honeywell Home)
  provider: resideo-technologies
  says: lists Resideo (Honeywell Home) as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    mcp: &id051
      status: none
    slug: ring
    status: profiled
    tags: &id052
    - Company
    - Home Security
    - IoT
    - Smart Home
    url: /providers/ring/
  layer: domain
  name: Ring
  provider: ring
  says: lists Ring as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    agent_readiness: 21.0
    band: thin
    in_catalog: true
    kin_score: 29.2
    mcp: &id053
      status: none
    slug: smartthings
    status: profiled
    tags: &id054
    - Devices
    - Home Automation
    - IoT
    - Smart Home
    url: /providers/smartthings/
  layer: domain
  name: Samsung SmartThings
  provider: smartthings
  says: lists Samsung SmartThings as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 29.1
    mcp: &id055
      status: none
    slug: sensibo
    status: profiled
    tags: &id056
    - Air Conditioning
    - HVAC
    - IoT
    - Smart Home
    url: /providers/sensibo/
  layer: domain
  name: Sensibo
  provider: sensibo
  says: lists Sensibo as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    mcp: &id057
      source: https://shelly-api-docs.shelly.cloud/mcp
      status: verified
    slug: shelly
    status: profiled
    tags: &id058
    - Company
    - Devices
    - IoT
    - Smart Home
    url: /providers/shelly/
  layer: domain
  name: Shelly
  provider: shelly
  says: lists Shelly as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    mcp: &id059
      status: unknown
    slug: signify
    status: profiled
    tags: &id060
    - Company
    - IoT
    - Lighting
    - Smart Home
    url: /providers/signify/
  layer: domain
  name: Signify (Philips Hue, WiZ)
  provider: signify
  says: lists Signify (Philips Hue, WiZ) as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 16.4
    mcp: &id061
      status: none
    slug: simplisafe
    status: profiled
    tags: &id062
    - Alarms
    - Home Security
    - Security Systems
    - Wireless
    url: /providers/simplisafe/
  layer: domain
  name: SimpliSafe
  provider: simplisafe
  says: lists SimpliSafe as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    mcp: &id063
      status: none
    slug: sonos
    status: profiled
    tags: &id064
    - Audio
    - Company
    - Consumer
    - Music
    url: /providers/sonos/
  layer: domain
  name: Sonos
  provider: sonos
  says: lists Sonos as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    agent_readiness: 7.9
    band: minimal
    in_catalog: true
    kin_score: 8.7
    mcp: &id065
      status: unknown
    slug: switchbot
    status: profiled
    tags: &id066
    - Automation
    - IoT
    - Robotics
    - Smart Home
    url: /providers/switchbot/
  layer: domain
  name: SwitchBot
  provider: switchbot
  says: lists SwitchBot as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    agent_readiness: 24.1
    band: emerging
    in_catalog: true
    kin_score: 24.8
    mcp: &id067
      status: unknown
    slug: tado
    status: profiled
    tags: &id068
    - Company
    - EnergySaving
    - Heating
    - Smart Home
    url: /providers/tado/
  layer: domain
  name: tado
  provider: tado
  says: lists tado as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id069
      status: none
    slug: tesla
    status: profiled
    tags: &id070
    - Automobiles
    - Cars
    - Electric Vehicles
    - Vehicles
    url: /providers/tesla/
  layer: domain
  name: Tesla (Fleet API)
  provider: tesla
  says: lists Tesla (Fleet API) as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-200.30.10
    key: AE-200.30.10
    name: Dynamic Electricity Tariffs
    url: /capabilities/home-energy/
    via_parent: Home Energy
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.1
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id071
      status: none
    slug: tibber
    status: profiled
    tags: &id072
    - ElectricityPricing
    - Energy
    - Smart Home
    - Smart Meter
    url: /providers/tibber/
  layer: domain
  name: Tibber
  provider: tibber
  says: lists Tibber as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    mcp: &id073
      status: unknown
    slug: tp-link
    status: profiled
    tags: &id074
    - Cloud
    - Company
    - Hardware
    - Networking
    url: /providers/tp-link/
  layer: domain
  name: TP-Link (Kasa / Tapo)
  provider: tp-link
  says: lists TP-Link (Kasa / Tapo) as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
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
    mcp: &id075
      source: https://github.com/tuya/tuya-mcp-sdk
      status: verified
    slug: tuya
    status: profiled
    tags: &id076
    - Cloud Platform
    - Devices
    - IoT
    - Smart Home
    url: /providers/tuya/
  layer: domain
  name: Tuya
  provider: tuya
  says: lists Tuya as an integration
  source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/smart-home-iot/homebridge/
providers:
- agent_band: agent-ready
  agent_readiness: 36.7
  band: developing
  in_catalog: true
  kin_score: 47.1
  mcp: *id001
  name: Airthings
  slug: airthings
  status: profiled
  tags: *id002
  url: /providers/airthings/
- agent_band: agent-aware
  agent_readiness: 13.8
  band: emerging
  in_catalog: true
  kin_score: 16.9
  mcp: *id003
  name: August Home
  slug: august
  status: profiled
  tags: *id004
  url: /providers/august/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id005
  name: Blink (Amazon cameras)
  slug: blink-home
  status: queued for profiling
  tags: *id006
  url: null
- agent_band: agent-aware
  agent_readiness: 12.9
  band: emerging
  in_catalog: true
  kin_score: 25.2
  mcp: *id007
  name: Bond (fan / shade bridge)
  slug: bond-home
  status: profiled
  tags: *id008
  url: /providers/bond-home/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.1
  mcp: *id009
  name: Chamberlain myQ
  slug: chamberlain
  status: profiled
  tags: *id010
  url: /providers/chamberlain/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.1
  mcp: *id011
  name: Daikin
  slug: daikin
  status: profiled
  tags: *id012
  url: /providers/daikin/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.0
  mcp: *id013
  name: ECOVACS
  slug: ecovacs-robotics
  status: profiled
  tags: *id014
  url: /providers/ecovacs-robotics/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id015
  name: Enphase Envoy
  slug: enphase
  status: profiled
  tags: *id016
  url: /providers/enphase/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.1
  mcp: *id017
  name: eufy (Anker)
  slug: anker-innovations
  status: profiled
  tags: *id018
  url: /providers/anker-innovations/
- agent_band: human-only
  agent_readiness: 4.5
  band: minimal
  in_catalog: true
  kin_score: 9.8
  mcp: *id019
  name: eWeLink (ITEAD / Sonoff)
  slug: ewelink
  status: profiled
  tags: *id020
  url: /providers/ewelink/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id021
  name: EZVIZ
  slug: ezviz
  status: profiled
  tags: *id022
  url: /providers/ezviz/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 41.4
  mcp: *id023
  name: Google Nest (Smart Device Management)
  slug: google-nest
  status: profiled
  tags: *id024
  url: /providers/google-nest/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id025
  name: Govee
  slug: govee
  status: profiled
  tags: *id026
  url: /providers/govee/
- agent_band: agent-aware
  agent_readiness: 23.8
  band: thin
  in_catalog: true
  kin_score: 28.6
  mcp: *id027
  name: Home Connect (BSH appliances)
  slug: home-connect
  status: profiled
  tags: *id028
  url: /providers/home-connect/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id029
  name: iRobot
  slug: irobot
  status: profiled
  tags: *id030
  url: /providers/irobot/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.6
  mcp: *id031
  name: LG ThinQ
  slug: lg-electronics
  status: profiled
  tags: *id032
  url: /providers/lg-electronics/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 37.5
  mcp: *id033
  name: LIFX
  slug: lifx
  status: profiled
  tags: *id034
  url: /providers/lifx/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.2
  mcp: *id035
  name: Lutron (Caseta)
  slug: lutron
  status: profiled
  tags: *id036
  url: /providers/lutron/
- agent_band: human-only
  agent_readiness: 4.5
  band: emerging
  in_catalog: true
  kin_score: 11.9
  mcp: *id037
  name: Meross
  slug: meross
  status: profiled
  tags: *id038
  url: /providers/meross/
- agent_band: agent-aware
  agent_readiness: 21.8
  band: emerging
  in_catalog: true
  kin_score: 24.9
  mcp: *id039
  name: Miele
  slug: miele
  status: profiled
  tags: *id040
  url: /providers/miele/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: emerging
  in_catalog: true
  kin_score: 19.6
  mcp: *id041
  name: Nuki
  slug: nuki
  status: profiled
  tags: *id042
  url: /providers/nuki/
- agent_band: agent-ready
  agent_readiness: 59.6
  band: strong
  in_catalog: true
  kin_score: 55.9
  mcp: *id043
  name: Plex
  slug: plex
  status: profiled
  tags: *id044
  url: /providers/plex/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: strong
  in_catalog: true
  kin_score: 56.7
  mcp: *id045
  name: Rachio
  slug: rachio
  status: profiled
  tags: *id046
  url: /providers/rachio/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 15.2
  mcp: *id047
  name: Rain Bird
  slug: rainbird
  status: profiled
  tags: *id048
  url: /providers/rainbird/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.1
  mcp: *id049
  name: Resideo (Honeywell Home)
  slug: resideo-technologies
  status: profiled
  tags: *id050
  url: /providers/resideo-technologies/
- agent_band: agent-ready
  agent_readiness: 34.1
  band: developing
  in_catalog: true
  kin_score: 43.9
  mcp: *id051
  name: Ring
  slug: ring
  status: profiled
  tags: *id052
  url: /providers/ring/
- agent_band: agent-aware
  agent_readiness: 21.0
  band: thin
  in_catalog: true
  kin_score: 29.2
  mcp: *id053
  name: Samsung SmartThings
  slug: smartthings
  status: profiled
  tags: *id054
  url: /providers/smartthings/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 29.1
  mcp: *id055
  name: Sensibo
  slug: sensibo
  status: profiled
  tags: *id056
  url: /providers/sensibo/
- agent_band: human-only
  agent_readiness: 4.5
  band: minimal
  in_catalog: true
  kin_score: 9.7
  mcp: *id057
  name: Shelly
  slug: shelly
  status: profiled
  tags: *id058
  url: /providers/shelly/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.4
  mcp: *id059
  name: Signify (Philips Hue, WiZ)
  slug: signify
  status: profiled
  tags: *id060
  url: /providers/signify/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.4
  mcp: *id061
  name: SimpliSafe
  slug: simplisafe
  status: profiled
  tags: *id062
  url: /providers/simplisafe/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id063
  name: Sonos
  slug: sonos
  status: profiled
  tags: *id064
  url: /providers/sonos/
- agent_band: agent-aware
  agent_readiness: 7.9
  band: minimal
  in_catalog: true
  kin_score: 8.7
  mcp: *id065
  name: SwitchBot
  slug: switchbot
  status: profiled
  tags: *id066
  url: /providers/switchbot/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: emerging
  in_catalog: true
  kin_score: 24.8
  mcp: *id067
  name: tado
  slug: tado
  status: profiled
  tags: *id068
  url: /providers/tado/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id069
  name: Tesla (Fleet API)
  slug: tesla
  status: profiled
  tags: *id070
  url: /providers/tesla/
- agent_band: agent-aware
  agent_readiness: 26.1
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id071
  name: Tibber
  slug: tibber
  status: profiled
  tags: *id072
  url: /providers/tibber/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 6.9
  mcp: *id073
  name: TP-Link (Kasa / Tapo)
  slug: tp-link
  status: profiled
  tags: *id074
  url: /providers/tp-link/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 31.9
  mcp: *id075
  name: Tuya
  slug: tuya
  status: profiled
  tags: *id076
  url: /providers/tuya/
siblings:
- name: Frigate
  rows: 4
  url: /applications/smart-home-iot/frigate/
- name: Home Assistant
  rows: 55
  url: /applications/smart-home-iot/home-assistant/
- name: Hubitat Elevation
  rows: 17
  url: /applications/smart-home-iot/hubitat-elevation/
- name: openHAB
  rows: 39
  url: /applications/smart-home-iot/openhab/
- name: SmartThings
  rows: 8
  url: /applications/smart-home-iot/smartthings/
sitemap: true
title: 'Homebridge: Smart Home & Home Automation reference app'
---
