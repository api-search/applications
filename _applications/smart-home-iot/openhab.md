---
app: openHAB
app_slug: openhab
app_url: https://github.com/openhab/openhab-addons
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
  - evcc
  - Tesla Energy (Powerwall)
  url: /capabilities/home-energy/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-200.60
  key: AE-200.60
  layer: domain
  name: Home Network & DNS Filtering
  providers:
  - Ubiquiti UniFi
  url: /capabilities/home-network-dns-filtering/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.20.10
  key: AE-170.20.10
  layer: domain
  name: Music Streaming & Catalog
  providers:
  - Spotify
  url: /capabilities/audio-music/
  via_parent: Audio & Music
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
  - Amazon Alexa
  - Belkin WeMo
  - Daikin
  - ecobee
  - ECOVACS
  - Google Cast (Chromecast)
  - Google Nest (Smart Device Management)
  - Govee
  - Home Connect (BSH appliances)
  - LIFX
  - Miele
  - Mill (heaters)
  - Nanoleaf
  - Netatmo
  - Nuki
  - Roborock
  - Samsung SmartThings
  - Sensibo
  - Shelly
  - Signify (Philips Hue, WiZ)
  - Somfy (TaHoma / Overkiz)
  - Sonos
  - tado
  - TP-Link (Kasa / Tapo)
  - Tuya
  - Warmup (underfloor heating)
  - Xiaomi (Mi Home)
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
- attribution: API Evangelist extension
  id: AE-230.10
  key: AE-230.10
  layer: domain
  name: Weather & Environment
  providers:
  - OpenWeatherMap
  url: /capabilities/weather-environment/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - ntfy
  - Pushover
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - Telegram Bot API
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: smart-home-iot
  name: Smart Home & Home Automation
  url: /applications/smart-home-iot/
counts:
  declared: 0
  observed: 39
credits: []
evidence:
- route: source code
  url: https://github.com/openhab/openhab-addons/tree/main/bundles
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
    agent_band: agent-native
    agent_readiness: 53.6
    band: strong
    in_catalog: true
    kin_score: 58.4
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
  says: ships the Amazon Alexa SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.amazonechocontrol
  tier: observed
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
    kin_score: 11.2
    mcp: &id003
      status: unknown
    slug: belkin
    status: profiled
    tags: &id004
    - Cables
    - Chargers
    - Phone Cases
    - Power Banks
    url: /providers/belkin/
  layer: domain
  name: Belkin WeMo
  provider: belkin
  says: ships the Belkin WeMo SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.wemo
  tier: observed
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
    kin_score: 2.2
    mcp: &id005
      status: unknown
    slug: daikin
    status: profiled
    tags: &id006
    - Air Conditioning
    - Company
    - HVAC
    - Refrigeration
    url: /providers/daikin/
  layer: domain
  name: Daikin
  provider: daikin
  says: ships the Daikin SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.daikin
  tier: observed
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
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 27.5
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
  says: ships the ecobee SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.ecobee
  tier: observed
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
    kin_score: 11.8
    mcp: &id009
      source: https://github.com/ecovacs-ai/ecovacs-mcp
      status: verified
    slug: ecovacs-robotics
    status: profiled
    tags: &id010
    - Company
    - Consumer Technology
    - Home Automation
    - Robotics
    url: /providers/ecovacs-robotics/
  layer: domain
  name: ECOVACS
  provider: ecovacs-robotics
  says: ships the ECOVACS SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.ecovacs
  tier: observed
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
    agent_readiness: 32.6
    band: developing
    in_catalog: true
    kin_score: 45.0
    mcp: &id011
      source: https://docs.evcc.io/en/integrations/mcp.md
      status: verified
    slug: evcc
    status: profiled
    tags: &id012
    - Company
    - Electric Vehicles
    - Open Source
    - Smart Charging
    url: /providers/evcc/
  layer: domain
  name: evcc
  provider: evcc
  says: ships the evcc SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.evcc
  tier: observed
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
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id013
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id014
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Google Cast (Chromecast)
  provider: google
  says: ships the Google Cast (Chromecast) SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.chromecast
  tier: observed
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
    agent_readiness: 35.8
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id015
      status: none
    slug: google-nest
    status: profiled
    tags: &id016
    - Camera
    - Device Management
    - Doorbell
    - Google Nest
    url: /providers/google-nest/
  layer: domain
  name: Google Nest (Smart Device Management)
  provider: google-nest
  says: ships the Google Nest (Smart Device Management) SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.nest
  tier: observed
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
    agent_readiness: 23.9
    band: thin
    in_catalog: true
    kin_score: 28.0
    mcp: &id017
      status: unknown
    slug: govee
    status: profiled
    tags: &id018
    - IoT
    - LED
    - Smart Home
    - Smart Lighting
    url: /providers/govee/
  layer: domain
  name: Govee
  provider: govee
  says: ships the Govee SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.govee
  tier: observed
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
    agent_readiness: 28.0
    band: thin
    in_catalog: true
    kin_score: 30.4
    mcp: &id019
      status: unknown
    slug: home-connect
    status: profiled
    tags: &id020
    - Appliances
    - Connected Devices
    - Smart Home
    url: /providers/home-connect/
  layer: domain
  name: Home Connect (BSH appliances)
  provider: home-connect
  says: ships the Home Connect (BSH appliances) SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.homeconnect
  tier: observed
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
    agent_readiness: 30.7
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id021
      status: none
    slug: lifx
    status: profiled
    tags: &id022
    - Home Automation
    - Lighting Fixtures
    - Smart Lighting
    - Wi‑Fi Bulbs
    url: /providers/lifx/
  layer: domain
  name: LIFX
  provider: lifx
  says: ships the LIFX SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.lifx
  tier: observed
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
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 31.2
    mcp: &id023
      status: unknown
    slug: miele
    status: profiled
    tags: &id024
    - Appliances
    - Company
    - Homes
    - Technology
    url: /providers/miele/
  layer: domain
  name: Miele
  provider: miele
  says: ships the Miele SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.mielecloud
  tier: observed
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
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 17.9
    mcp: &id025
      status: unknown
    slug: mill-heat
    status: profiled
    tags: &id026
    - Company
    - Heating
    - IoT
    - ScandinavianDesign
    url: /providers/mill-heat/
  layer: domain
  name: Mill (heaters)
  provider: mill-heat
  says: ships the Mill (heaters) SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.millheat
  tier: observed
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
    agent_readiness: 4.4
    band: emerging
    in_catalog: true
    kin_score: 17.3
    mcp: &id027
      source: https://nanoleaf.me
      status: documented
    slug: nanoleaf
    status: profiled
    tags: &id028
    - Company
    - Home Automation
    - IoT
    - Smart Lighting
    url: /providers/nanoleaf/
  layer: domain
  name: Nanoleaf
  provider: nanoleaf
  says: ships the Nanoleaf SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.nanoleaf
  tier: observed
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
    kin_score: 12.3
    mcp: &id029
      status: none
    slug: netatmo
    status: profiled
    tags: &id030
    - Company
    - Devices
    - IoT
    - Smart Home
    url: /providers/netatmo/
  layer: domain
  name: Netatmo
  provider: netatmo
  says: ships the Netatmo SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.netatmo
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id031
      status: none
    slug: ntfy
    status: profiled
    tags: &id032
    - Notification
    - Open Source
    - Pub/Sub
    - Self-Hosted
    url: /providers/ntfy/
  layer: common
  name: ntfy
  provider: ntfy
  says: ships the ntfy SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.ntfy
  tier: observed
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
    agent_readiness: 24.8
    band: thin
    in_catalog: true
    kin_score: 30.2
    mcp: &id033
      status: none
    slug: nuki
    status: profiled
    tags: &id034
    - Company
    - Home Automation
    - IoT
    - Smart Lock
    url: /providers/nuki/
  layer: domain
  name: Nuki
  provider: nuki
  says: ships the Nuki SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.nuki
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.0
    band: strong
    in_catalog: true
    kin_score: 59.1
    mcp: &id035
      source: https://mcp.openweathermap.org/
      status: verified
    slug: openweathermap
    status: profiled
    tags: &id036
    - Air Pollution
    - Climate
    - Forecast
    - Weather
    url: /providers/openweathermap/
  layer: domain
  name: OpenWeatherMap
  provider: openweathermap
  says: ships the OpenWeatherMap SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.openweathermap
  tier: observed
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
    agent_readiness: 63.2
    band: strong
    in_catalog: true
    kin_score: 56.7
    mcp: &id037
      status: none
    slug: plex
    status: profiled
    tags: &id038
    - Company
    - Media
    - Streaming
    - Video
    url: /providers/plex/
  layer: domain
  name: Plex
  provider: plex
  says: ships the Plex SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.plex
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
    agent_readiness: 21.6
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id039
      status: none
    slug: pushover
    status: profiled
    tags: &id040
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: common
  name: Pushover
  provider: pushover
  says: ships the Pushover SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.pushover
  tier: observed
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
    agent_readiness: 33.4
    band: developing
    in_catalog: true
    kin_score: 45.1
    mcp: &id041
      status: none
    slug: ring
    status: profiled
    tags: &id042
    - Company
    - Home Security
    - IoT
    - Smart Home
    url: /providers/ring/
  layer: domain
  name: Ring
  provider: ring
  says: ships the Ring SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.ring
  tier: observed
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
    kin_score: 15.2
    mcp: &id043
      status: unknown
    slug: roborock
    status: profiled
    tags: &id044
    - Company
    - Consumer IoT
    - Robot Vacuum
    - Robotics
    url: /providers/roborock/
  layer: domain
  name: Roborock
  provider: roborock
  says: ships the Roborock SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.roborock
  tier: observed
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
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 29.0
    mcp: &id045
      status: none
    slug: smartthings
    status: profiled
    tags: &id046
    - Devices
    - Home Automation
    - IoT
    - Smart Home
    url: /providers/smartthings/
  layer: domain
  name: Samsung SmartThings
  provider: smartthings
  says: ships the Samsung SmartThings SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.smartthings
  tier: observed
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
    agent_readiness: 29.6
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id047
      status: none
    slug: sensibo
    status: profiled
    tags: &id048
    - Air Conditioning
    - HVAC
    - IoT
    - Smart Home
    url: /providers/sensibo/
  layer: domain
  name: Sensibo
  provider: sensibo
  says: ships the Sensibo SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.sensibo
  tier: observed
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
    agent_readiness: 4.4
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id049
      source: https://shelly-api-docs.shelly.cloud/mcp
      status: verified
    slug: shelly
    status: profiled
    tags: &id050
    - Company
    - Devices
    - IoT
    - Smart Home
    url: /providers/shelly/
  layer: domain
  name: Shelly
  provider: shelly
  says: ships the Shelly SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.shelly
  tier: observed
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
    kin_score: 18.3
    mcp: &id051
      status: unknown
    slug: signify
    status: profiled
    tags: &id052
    - Company
    - IoT
    - Lighting
    - Smart Home
    url: /providers/signify/
  layer: domain
  name: Signify (Philips Hue, WiZ)
  provider: signify
  says: ships the Signify (Philips Hue, WiZ) SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.hue
  tier: observed
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
    kin_score: 5.4
    mcp: &id053
      status: unknown
    slug: somfy
    status: profiled
    tags: &id054
    - Company
    - Home Automation
    - IoT
    - Smart Home
    url: /providers/somfy/
  layer: domain
  name: Somfy (TaHoma / Overkiz)
  provider: somfy
  says: ships the Somfy (TaHoma / Overkiz) SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.somfytahoma
  tier: observed
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
    agent_readiness: 23.1
    band: thin
    in_catalog: true
    kin_score: 33.0
    mcp: &id055
      status: none
    slug: sonos
    status: profiled
    tags: &id056
    - Audio
    - Company
    - Consumer
    - Music
    url: /providers/sonos/
  layer: domain
  name: Sonos
  provider: sonos
  says: ships the Sonos SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.sonos
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.7
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id057
      status: none
    slug: spotify
    status: profiled
    tags: &id058
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
  layer: domain
  name: Spotify
  provider: spotify
  says: ships the Spotify SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.spotify
  tier: observed
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
    kin_score: 36.0
    mcp: &id059
      status: unknown
    slug: tado
    status: profiled
    tags: &id060
    - Company
    - EnergySaving
    - Heating
    - Smart Home
    url: /providers/tado/
  layer: domain
  name: tado
  provider: tado
  says: ships the tado SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.tado
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id061
      status: none
    slug: telegram
    status: profiled
    tags: &id062
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram Bot API
  provider: telegram
  says: ships the Telegram Bot API SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.telegram
  tier: observed
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
    agent_readiness: 22.3
    band: thin
    in_catalog: true
    kin_score: 34.8
    mcp: &id063
      status: none
    slug: tesla
    status: profiled
    tags: &id064
    - Automobiles
    - Cars
    - Electric Vehicles
    - Vehicles
    url: /providers/tesla/
  layer: domain
  name: Tesla (Fleet API)
  provider: tesla
  says: ships the Tesla (Fleet API) SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.tesla
  tier: observed
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
    agent_readiness: 31.2
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id065
      status: unknown
    slug: tesla-energy
    status: profiled
    tags: &id066
    - Battery Storage
    - Clean Energy
    - Energy
    - Solar
    url: /providers/tesla-energy/
  layer: domain
  name: Tesla Energy (Powerwall)
  provider: tesla-energy
  says: ships the Tesla Energy (Powerwall) SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.teslapowerwall
  tier: observed
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
    agent_readiness: 25.6
    band: developing
    in_catalog: true
    kin_score: 49.5
    mcp: &id067
      status: none
    slug: tibber
    status: profiled
    tags: &id068
    - ElectricityPricing
    - Energy
    - Smart Home
    - Smart Meter
    url: /providers/tibber/
  layer: domain
  name: Tibber
  provider: tibber
  says: ships the Tibber SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.tibber
  tier: observed
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
    kin_score: 9.4
    mcp: &id069
      status: unknown
    slug: tp-link
    status: profiled
    tags: &id070
    - Cloud
    - Company
    - Hardware
    - Networking
    url: /providers/tp-link/
  layer: domain
  name: TP-Link (Kasa / Tapo)
  provider: tp-link
  says: ships the TP-Link (Kasa / Tapo) SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.tplinksmarthome
  tier: observed
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
    agent_readiness: 25.3
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id071
      source: https://github.com/tuya/tuya-mcp-sdk
      status: verified
    slug: tuya
    status: profiled
    tags: &id072
    - Cloud Platform
    - Devices
    - IoT
    - Smart Home
    url: /providers/tuya/
  layer: domain
  name: Tuya
  provider: tuya
  says: ships the Tuya SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.tuya
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.60
    key: AE-200.60
    name: Home Network & DNS Filtering
    url: /capabilities/home-network-dns-filtering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id073
      status: none
    slug: ubiquiti
    status: profiled
    tags: &id074
    - Networking
    - Routing
    - Switching
    - Wi-Fi
    url: /providers/ubiquiti/
  layer: domain
  name: Ubiquiti UniFi
  provider: ubiquiti
  says: ships the Ubiquiti UniFi SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.unifi
  tier: observed
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
    kin_score: 11.7
    mcp: &id075
      status: unknown
    slug: warmup
    status: profiled
    tags: &id076
    - Company
    - Home Improvement
    - Underfloor Heating
    - United Kingdom
    url: /providers/warmup/
  layer: domain
  name: Warmup (underfloor heating)
  provider: warmup
  says: ships the Warmup (underfloor heating) SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.warmup
  tier: observed
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
    agent_readiness: 24.9
    band: thin
    in_catalog: true
    kin_score: 35.6
    mcp: &id077
      status: none
    slug: xiaomi
    status: profiled
    tags: &id078
    - Consumer Electronics
    - IoT
    - Mobile
    - Smart Home
    url: /providers/xiaomi/
  layer: domain
  name: Xiaomi (Mi Home)
  provider: xiaomi
  says: ships the Xiaomi (Mi Home) SDK or integration code
  source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.miio
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/smart-home-iot/openhab/
providers:
- agent_band: agent-native
  agent_readiness: 53.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id001
  name: Amazon Alexa
  slug: amazon
  status: profiled
  tags: *id002
  url: /providers/amazon/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.2
  mcp: *id003
  name: Belkin WeMo
  slug: belkin
  status: profiled
  tags: *id004
  url: /providers/belkin/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id005
  name: Daikin
  slug: daikin
  status: profiled
  tags: *id006
  url: /providers/daikin/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 27.5
  mcp: *id007
  name: ecobee
  slug: ecobee
  status: profiled
  tags: *id008
  url: /providers/ecobee/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.8
  mcp: *id009
  name: ECOVACS
  slug: ecovacs-robotics
  status: profiled
  tags: *id010
  url: /providers/ecovacs-robotics/
- agent_band: agent-ready
  agent_readiness: 32.6
  band: developing
  in_catalog: true
  kin_score: 45.0
  mcp: *id011
  name: evcc
  slug: evcc
  status: profiled
  tags: *id012
  url: /providers/evcc/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id013
  name: Google Cast (Chromecast)
  slug: google
  status: profiled
  tags: *id014
  url: /providers/google/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id015
  name: Google Nest (Smart Device Management)
  slug: google-nest
  status: profiled
  tags: *id016
  url: /providers/google-nest/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: thin
  in_catalog: true
  kin_score: 28.0
  mcp: *id017
  name: Govee
  slug: govee
  status: profiled
  tags: *id018
  url: /providers/govee/
- agent_band: agent-aware
  agent_readiness: 28.0
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id019
  name: Home Connect (BSH appliances)
  slug: home-connect
  status: profiled
  tags: *id020
  url: /providers/home-connect/
- agent_band: agent-ready
  agent_readiness: 30.7
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id021
  name: LIFX
  slug: lifx
  status: profiled
  tags: *id022
  url: /providers/lifx/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 31.2
  mcp: *id023
  name: Miele
  slug: miele
  status: profiled
  tags: *id024
  url: /providers/miele/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 17.9
  mcp: *id025
  name: Mill (heaters)
  slug: mill-heat
  status: profiled
  tags: *id026
  url: /providers/mill-heat/
- agent_band: human-only
  agent_readiness: 4.4
  band: emerging
  in_catalog: true
  kin_score: 17.3
  mcp: *id027
  name: Nanoleaf
  slug: nanoleaf
  status: profiled
  tags: *id028
  url: /providers/nanoleaf/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.3
  mcp: *id029
  name: Netatmo
  slug: netatmo
  status: profiled
  tags: *id030
  url: /providers/netatmo/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id031
  name: ntfy
  slug: ntfy
  status: profiled
  tags: *id032
  url: /providers/ntfy/
- agent_band: agent-aware
  agent_readiness: 24.8
  band: thin
  in_catalog: true
  kin_score: 30.2
  mcp: *id033
  name: Nuki
  slug: nuki
  status: profiled
  tags: *id034
  url: /providers/nuki/
- agent_band: agent-ready
  agent_readiness: 30.0
  band: strong
  in_catalog: true
  kin_score: 59.1
  mcp: *id035
  name: OpenWeatherMap
  slug: openweathermap
  status: profiled
  tags: *id036
  url: /providers/openweathermap/
- agent_band: agent-ready
  agent_readiness: 63.2
  band: strong
  in_catalog: true
  kin_score: 56.7
  mcp: *id037
  name: Plex
  slug: plex
  status: profiled
  tags: *id038
  url: /providers/plex/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id039
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id040
  url: /providers/pushover/
- agent_band: agent-ready
  agent_readiness: 33.4
  band: developing
  in_catalog: true
  kin_score: 45.1
  mcp: *id041
  name: Ring
  slug: ring
  status: profiled
  tags: *id042
  url: /providers/ring/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.2
  mcp: *id043
  name: Roborock
  slug: roborock
  status: profiled
  tags: *id044
  url: /providers/roborock/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 29.0
  mcp: *id045
  name: Samsung SmartThings
  slug: smartthings
  status: profiled
  tags: *id046
  url: /providers/smartthings/
- agent_band: agent-ready
  agent_readiness: 29.6
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id047
  name: Sensibo
  slug: sensibo
  status: profiled
  tags: *id048
  url: /providers/sensibo/
- agent_band: human-only
  agent_readiness: 4.4
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id049
  name: Shelly
  slug: shelly
  status: profiled
  tags: *id050
  url: /providers/shelly/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.3
  mcp: *id051
  name: Signify (Philips Hue, WiZ)
  slug: signify
  status: profiled
  tags: *id052
  url: /providers/signify/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.4
  mcp: *id053
  name: Somfy (TaHoma / Overkiz)
  slug: somfy
  status: profiled
  tags: *id054
  url: /providers/somfy/
- agent_band: agent-aware
  agent_readiness: 23.1
  band: thin
  in_catalog: true
  kin_score: 33.0
  mcp: *id055
  name: Sonos
  slug: sonos
  status: profiled
  tags: *id056
  url: /providers/sonos/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id057
  name: Spotify
  slug: spotify
  status: profiled
  tags: *id058
  url: /providers/spotify/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: thin
  in_catalog: true
  kin_score: 36.0
  mcp: *id059
  name: tado
  slug: tado
  status: profiled
  tags: *id060
  url: /providers/tado/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id061
  name: Telegram Bot API
  slug: telegram
  status: profiled
  tags: *id062
  url: /providers/telegram/
- agent_band: agent-aware
  agent_readiness: 22.3
  band: thin
  in_catalog: true
  kin_score: 34.8
  mcp: *id063
  name: Tesla (Fleet API)
  slug: tesla
  status: profiled
  tags: *id064
  url: /providers/tesla/
- agent_band: agent-ready
  agent_readiness: 31.2
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id065
  name: Tesla Energy (Powerwall)
  slug: tesla-energy
  status: profiled
  tags: *id066
  url: /providers/tesla-energy/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id067
  name: Tibber
  slug: tibber
  status: profiled
  tags: *id068
  url: /providers/tibber/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.4
  mcp: *id069
  name: TP-Link (Kasa / Tapo)
  slug: tp-link
  status: profiled
  tags: *id070
  url: /providers/tp-link/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id071
  name: Tuya
  slug: tuya
  status: profiled
  tags: *id072
  url: /providers/tuya/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id073
  name: Ubiquiti UniFi
  slug: ubiquiti
  status: profiled
  tags: *id074
  url: /providers/ubiquiti/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.7
  mcp: *id075
  name: Warmup (underfloor heating)
  slug: warmup
  status: profiled
  tags: *id076
  url: /providers/warmup/
- agent_band: agent-aware
  agent_readiness: 24.9
  band: thin
  in_catalog: true
  kin_score: 35.6
  mcp: *id077
  name: Xiaomi (Mi Home)
  slug: xiaomi
  status: profiled
  tags: *id078
  url: /providers/xiaomi/
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
- name: SmartThings
  rows: 8
  url: /applications/smart-home-iot/smartthings/
sitemap: true
title: 'openHAB: Smart Home & Home Automation reference app'
---
