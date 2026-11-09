---
app: Home Assistant
app_slug: home-assistant
app_url: https://github.com/home-assistant/core
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-200.70
  key: AE-200.70
  layer: domain
  name: 3D Printing & Printer Control
  providers:
  - OctoPrint
  url: /capabilities/3d-printing-printer-control/
  via_parent: null
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
  id: AE-200.60
  key: AE-200.60
  layer: domain
  name: Home Network & DNS Filtering
  providers:
  - NETGEAR
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
  - Blink (Amazon cameras)
  - EZVIZ
  - Reolink
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
  - Amazon Alexa
  - Apple HomeKit
  - August Home
  - Belkin WeMo
  - Daikin
  - ecobee
  - Google Assistant / Google Home
  - Google Nest (Smart Device Management)
  - Govee
  - LIFX
  - Mill (heaters)
  - Nanoleaf
  - Netatmo
  - Nuki
  - Rachio
  - Resideo (Honeywell Home)
  - Roborock
  - Samsung SmartThings
  - Shelly
  - Signify (Philips Hue, WiZ)
  - Somfy (TaHoma / Overkiz)
  - Sonos
  - SwitchBot
  - tado
  - TP-Link (Kasa / Tapo)
  - Tuya
  - Xiaomi (Mi Home)
  - Yale Home (smart locks)
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
  id: AE-130.20
  key: AE-130.20
  layer: domain
  name: Wearable & Health Data Sync
  providers:
  - Withings
  url: /capabilities/wearable-health-data-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.10
  key: AE-230.10
  layer: domain
  name: Weather & Environment
  providers:
  - MET Norway (api.met.no)
  - OpenWeatherMap
  url: /capabilities/weather-environment/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Firebase Cloud Messaging
  - Pushover
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - Telegram Bot API
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - IFTTT
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - Google Gemini
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.10.40
  key: AE-110.10.40
  layer: agent
  name: On-Device & Edge Inference
  providers:
  - Ollama
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.30.20
  key: AE-110.30.20
  layer: agent
  name: Text-to-Speech
  providers:
  - Amazon Polly
  - Google Translate TTS
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
category:
  id: smart-home-iot
  name: Smart Home & Home Automation
  url: /applications/smart-home-iot/
counts:
  declared: 0
  observed: 55
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/io.homeassistant.companion.android/latest/
- route: dependency manifest
  url: https://github.com/home-assistant/android/blob/main/gradle/libs.versions.toml
- route: source code
  url: https://github.com/home-assistant/core/tree/dev/homeassistant/components
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
  says: ships the Amazon Alexa SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/alexa
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.20
    key: AE-110.30.20
    name: Text-to-Speech
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.0
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id003
      status: none
    slug: amazon-polly
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Artificial Intelligence
    - Machine Learning
    - Speech Synthesis
    url: /providers/amazon-polly/
  layer: agent
  name: Amazon Polly
  provider: amazon-polly
  says: ships the Amazon Polly SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/amazon_polly
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 87.5
    mcp: &id005
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id006
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/anthropic
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
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id007
      status: none
    slug: apple
    status: profiled
    tags: &id008
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple HomeKit
  provider: apple
  says: ships the Apple HomeKit SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/homekit
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
    agent_readiness: 13.8
    band: emerging
    in_catalog: true
    kin_score: 16.9
    mcp: &id009
      status: unknown
    slug: august
    status: profiled
    tags: &id010
    - Company
    - Consumer
    - Smart Home
    - Smart Lock
    url: /providers/august/
  layer: domain
  name: August Home
  provider: august
  says: ships the August Home SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/august
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
    kin_score: 7.6
    mcp: &id011
      status: unknown
    slug: belkin
    status: profiled
    tags: &id012
    - Cables
    - Chargers
    - Phone Cases
    - Power Banks
    url: /providers/belkin/
  layer: domain
  name: Belkin WeMo
  provider: belkin
  says: ships the Belkin WeMo SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/wemo
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id013
      status: unchecked
    slug: blink-home
    status: queued for profiling
    tags: &id014 []
    url: null
  layer: domain
  name: Blink (Amazon cameras)
  provider: blink-home
  says: ships the Blink (Amazon cameras) SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/blink
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
    kin_score: 3.1
    mcp: &id015
      status: unknown
    slug: daikin
    status: profiled
    tags: &id016
    - Air Conditioning
    - Company
    - HVAC
    - Refrigeration
    url: /providers/daikin/
  layer: domain
  name: Daikin
  provider: daikin
  says: ships the Daikin SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/daikin
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
    agent_readiness: 21.3
    band: thin
    in_catalog: true
    kin_score: 28.2
    mcp: &id017
      status: none
    slug: ecobee
    status: profiled
    tags: &id018
    - HVAC
    - IoT
    - Smart Home
    - Thermostat
    url: /providers/ecobee/
  layer: domain
  name: ecobee
  provider: ecobee
  says: ships the ecobee SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/ecobee
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
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 11.6
    mcp: &id019
      status: unknown
    slug: ezviz
    status: profiled
    tags: &id020
    - Security Cameras
    - Smart Entry
    - Smart Home
    - Smart Home Appliance
    url: /providers/ezviz/
  layer: domain
  name: EZVIZ
  provider: ezviz
  says: ships the EZVIZ SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/ezviz
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
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id021
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id022
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase Cloud Messaging
  provider: firebase
  says: ships the Firebase Cloud Messaging SDK or integration code
  source: https://github.com/home-assistant/android/blob/main/gradle/libs.versions.toml
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
    agent_readiness: 17.2
    band: thin
    in_catalog: true
    kin_score: 28.7
    mcp: &id023
      status: unknown
    slug: google-assistant
    status: profiled
    tags: &id024
    - Actions on Google
    - Conversational AI
    - Google Assistant
    - Natural-Language
    url: /providers/google-assistant/
  layer: domain
  name: Google Assistant / Google Home
  provider: google-assistant
  says: ships the Google Assistant / Google Home SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/google_assistant
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: strong
    in_catalog: true
    kin_score: 55.1
    mcp: &id025
      status: none
    slug: google-gemini
    status: profiled
    tags: &id026
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/google_generative_ai_conversation
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
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 41.4
    mcp: &id027
      status: none
    slug: google-nest
    status: profiled
    tags: &id028
    - Camera
    - Device Management
    - Doorbell
    - Google Nest
    url: /providers/google-nest/
  layer: domain
  name: Google Nest (Smart Device Management)
  provider: google-nest
  says: ships the Google Nest (Smart Device Management) SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/nest
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.20
    key: AE-110.30.20
    name: Text-to-Speech
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.9
    band: developing
    in_catalog: true
    kin_score: 51.6
    mcp: &id029
      status: none
    slug: google-translate
    status: profiled
    tags: &id030
    - Google Cloud
    - Internationalization
    - Language Detection
    - Localization
    url: /providers/google-translate/
  layer: agent
  name: Google Translate TTS
  provider: google-translate
  says: ships the Google Translate TTS SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/google_translate
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
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id031
      status: unknown
    slug: govee
    status: profiled
    tags: &id032
    - IoT
    - LED
    - Smart Home
    - Smart Lighting
    url: /providers/govee/
  layer: domain
  name: Govee
  provider: govee
  says: ships the Govee SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/govee_light_local
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.3
    band: emerging
    in_catalog: true
    kin_score: 25.0
    mcp: &id033
      source: https://github.com/IFTTT/ifttt-plugins
      status: verified
    slug: ifttt
    status: profiled
    tags: &id034
    - Automation
    - No-Code
    - Webhook
    - iPaaS
    url: /providers/ifttt/
  layer: common
  name: IFTTT
  provider: ifttt
  says: ships the IFTTT SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/ifttt
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
    agent_readiness: 31.3
    band: thin
    in_catalog: true
    kin_score: 37.5
    mcp: &id035
      status: none
    slug: lifx
    status: profiled
    tags: &id036
    - Home Automation
    - Lighting Fixtures
    - Smart Lighting
    - Wi‑Fi Bulbs
    url: /providers/lifx/
  layer: domain
  name: LIFX
  provider: lifx
  says: ships the LIFX SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/lifx
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id037
      status: unchecked
    slug: met-no
    status: queued for profiling
    tags: &id038 []
    url: null
  layer: domain
  name: MET Norway (api.met.no)
  provider: met-no
  says: ships the MET Norway (api.met.no) SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/met
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
    agent_readiness: 14.4
    band: emerging
    in_catalog: true
    kin_score: 12.7
    mcp: &id039
      status: unknown
    slug: mill-heat
    status: profiled
    tags: &id040
    - Company
    - Heating
    - IoT
    - ScandinavianDesign
    url: /providers/mill-heat/
  layer: domain
  name: Mill (heaters)
  provider: mill-heat
  says: ships the Mill (heaters) SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/mill
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
    agent_readiness: 4.5
    band: emerging
    in_catalog: true
    kin_score: 11.1
    mcp: &id041
      source: https://nanoleaf.me
      status: documented
    slug: nanoleaf
    status: profiled
    tags: &id042
    - Company
    - Home Automation
    - IoT
    - Smart Lighting
    url: /providers/nanoleaf/
  layer: domain
  name: Nanoleaf
  provider: nanoleaf
  says: ships the Nanoleaf SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/nanoleaf
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
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 9.4
    mcp: &id043
      status: none
    slug: netatmo
    status: profiled
    tags: &id044
    - Company
    - Devices
    - IoT
    - Smart Home
    url: /providers/netatmo/
  layer: domain
  name: Netatmo
  provider: netatmo
  says: ships the Netatmo SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/netatmo
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
    agent_band: agent-aware
    agent_readiness: 18.7
    band: emerging
    in_catalog: true
    kin_score: 14.2
    mcp: &id045
      status: none
    slug: netgear
    status: profiled
    tags: &id046
    - Company
    - Consumer
    - Hardware
    - Networking
    url: /providers/netgear/
  layer: domain
  name: NETGEAR
  provider: netgear
  says: ships the NETGEAR SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/netgear
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
    agent_readiness: 25.4
    band: emerging
    in_catalog: true
    kin_score: 19.6
    mcp: &id047
      status: none
    slug: nuki
    status: profiled
    tags: &id048
    - Company
    - Home Automation
    - IoT
    - Smart Lock
    url: /providers/nuki/
  layer: domain
  name: Nuki
  provider: nuki
  says: ships the Nuki SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/nuki
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-200.70
    key: AE-200.70
    name: 3D Printing & Printer Control
    url: /capabilities/3d-printing-printer-control/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.8
    band: emerging
    in_catalog: true
    kin_score: 24.5
    mcp: &id049
      status: none
    slug: octoprint
    status: profiled
    tags: &id050
    - 3D Printing
    - Company
    - IoT
    - Open Source
    url: /providers/octoprint/
  layer: domain
  name: OctoPrint
  provider: octoprint
  says: ships the OctoPrint SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/octoprint
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.40
    key: AE-110.10.40
    name: On-Device & Edge Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id051
      status: none
    slug: ollama
    status: profiled
    tags: &id052
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
  layer: agent
  name: Ollama
  provider: ollama
  says: ships the Ollama SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/ollama
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id053
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id054
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/openai_conversation
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
    agent_band: agent-aware
    agent_readiness: 22.5
    band: strong
    in_catalog: true
    kin_score: 60.4
    mcp: &id055
      source: https://mcp.openweathermap.org/
      status: verified
    slug: openweathermap
    status: profiled
    tags: &id056
    - Air Pollution
    - Climate
    - Forecast
    - Weather
    url: /providers/openweathermap/
  layer: domain
  name: OpenWeatherMap
  provider: openweathermap
  says: ships the OpenWeatherMap SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/openweathermap
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
    agent_readiness: 59.6
    band: strong
    in_catalog: true
    kin_score: 55.9
    mcp: &id057
      status: none
    slug: plex
    status: profiled
    tags: &id058
    - Company
    - Media
    - Streaming
    - Video
    url: /providers/plex/
  layer: domain
  name: Plex
  provider: plex
  says: ships the Plex SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/plex
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
    mcp: &id059
      status: none
    slug: pushover
    status: profiled
    tags: &id060
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: common
  name: Pushover
  provider: pushover
  says: ships the Pushover SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/pushover
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
    agent_readiness: 30.8
    band: strong
    in_catalog: true
    kin_score: 56.7
    mcp: &id061
      status: unknown
    slug: rachio
    status: profiled
    tags: &id062
    - Company
    - IoT
    - Irrigation
    - Smart Home
    url: /providers/rachio/
  layer: domain
  name: Rachio
  provider: rachio
  says: ships the Rachio SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/rachio
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
    agent_band: agent-aware
    agent_readiness: 20.9
    band: thin
    in_catalog: true
    kin_score: 32.0
    mcp: &id063
      status: none
    slug: reolink
    status: profiled
    tags: &id064
    - IoT
    - Security Cameras
    - Smart Home
    - Surveillance
    url: /providers/reolink/
  layer: domain
  name: Reolink
  provider: reolink
  says: ships the Reolink SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/reolink
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
    kin_score: 1.1
    mcp: &id065
      status: unknown
    slug: resideo-technologies
    status: profiled
    tags: &id066 []
    url: /providers/resideo-technologies/
  layer: domain
  name: Resideo (Honeywell Home)
  provider: resideo-technologies
  says: ships the Resideo (Honeywell Home) SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/lyric
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
    agent_readiness: 34.1
    band: developing
    in_catalog: true
    kin_score: 43.9
    mcp: &id067
      status: none
    slug: ring
    status: profiled
    tags: &id068
    - Company
    - Home Security
    - IoT
    - Smart Home
    url: /providers/ring/
  layer: domain
  name: Ring
  provider: ring
  says: ships the Ring SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/ring
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
    kin_score: 14.1
    mcp: &id069
      status: unknown
    slug: roborock
    status: profiled
    tags: &id070
    - Company
    - Consumer IoT
    - Robot Vacuum
    - Robotics
    url: /providers/roborock/
  layer: domain
  name: Roborock
  provider: roborock
  says: ships the Roborock SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/roborock
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
    agent_readiness: 21.0
    band: thin
    in_catalog: true
    kin_score: 29.2
    mcp: &id071
      status: none
    slug: smartthings
    status: profiled
    tags: &id072
    - Devices
    - Home Automation
    - IoT
    - Smart Home
    url: /providers/smartthings/
  layer: domain
  name: Samsung SmartThings
  provider: smartthings
  says: ships the Samsung SmartThings SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/smartthings
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
    kin_score: 80.6
    mcp: &id073
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id074
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/home-assistant/android/blob/main/gradle/libs.versions.toml
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
    agent_readiness: 4.5
    band: minimal
    in_catalog: true
    kin_score: 9.7
    mcp: &id075
      source: https://shelly-api-docs.shelly.cloud/mcp
      status: verified
    slug: shelly
    status: profiled
    tags: &id076
    - Company
    - Devices
    - IoT
    - Smart Home
    url: /providers/shelly/
  layer: domain
  name: Shelly
  provider: shelly
  says: ships the Shelly SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/shelly
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
    kin_score: 10.4
    mcp: &id077
      status: unknown
    slug: signify
    status: profiled
    tags: &id078
    - Company
    - IoT
    - Lighting
    - Smart Home
    url: /providers/signify/
  layer: domain
  name: Signify (Philips Hue, WiZ)
  provider: signify
  says: ships the Signify (Philips Hue, WiZ) SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/hue
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 16.4
    mcp: &id079
      status: none
    slug: simplisafe
    status: profiled
    tags: &id080
    - Alarms
    - Home Security
    - Security Systems
    - Wireless
    url: /providers/simplisafe/
  layer: domain
  name: SimpliSafe
  provider: simplisafe
  says: ships the SimpliSafe SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/simplisafe
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
    kin_score: 4.4
    mcp: &id081
      status: unknown
    slug: somfy
    status: profiled
    tags: &id082
    - Company
    - Home Automation
    - IoT
    - Smart Home
    url: /providers/somfy/
  layer: domain
  name: Somfy (TaHoma / Overkiz)
  provider: somfy
  says: ships the Somfy (TaHoma / Overkiz) SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/overkiz
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
    kin_score: 34.2
    mcp: &id083
      status: none
    slug: sonos
    status: profiled
    tags: &id084
    - Audio
    - Company
    - Consumer
    - Music
    url: /providers/sonos/
  layer: domain
  name: Sonos
  provider: sonos
  says: ships the Sonos SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/sonos
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
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 49.8
    mcp: &id085
      status: none
    slug: spotify
    status: profiled
    tags: &id086
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
  layer: domain
  name: Spotify
  provider: spotify
  says: ships the Spotify SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/spotify
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
    agent_readiness: 7.9
    band: minimal
    in_catalog: true
    kin_score: 8.7
    mcp: &id087
      status: unknown
    slug: switchbot
    status: profiled
    tags: &id088
    - Automation
    - IoT
    - Robotics
    - Smart Home
    url: /providers/switchbot/
  layer: domain
  name: SwitchBot
  provider: switchbot
  says: ships the SwitchBot SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/switchbot
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
    agent_readiness: 24.1
    band: emerging
    in_catalog: true
    kin_score: 24.8
    mcp: &id089
      status: unknown
    slug: tado
    status: profiled
    tags: &id090
    - Company
    - EnergySaving
    - Heating
    - Smart Home
    url: /providers/tado/
  layer: domain
  name: tado
  provider: tado
  says: ships the tado SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/tado
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
    agent_readiness: 25.4
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id091
      status: none
    slug: telegram
    status: profiled
    tags: &id092
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram Bot API
  provider: telegram
  says: ships the Telegram Bot API SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/telegram_bot
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
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id093
      status: none
    slug: tesla
    status: profiled
    tags: &id094
    - Automobiles
    - Cars
    - Electric Vehicles
    - Vehicles
    url: /providers/tesla/
  layer: domain
  name: Tesla (Fleet API)
  provider: tesla
  says: ships the Tesla (Fleet API) SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/tesla_fleet
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
    agent_readiness: 26.1
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id095
      status: none
    slug: tibber
    status: profiled
    tags: &id096
    - ElectricityPricing
    - Energy
    - Smart Home
    - Smart Meter
    url: /providers/tibber/
  layer: domain
  name: Tibber
  provider: tibber
  says: ships the Tibber SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/tibber
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
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 6.9
    mcp: &id097
      status: unknown
    slug: tp-link
    status: profiled
    tags: &id098
    - Cloud
    - Company
    - Hardware
    - Networking
    url: /providers/tp-link/
  layer: domain
  name: TP-Link (Kasa / Tapo)
  provider: tp-link
  says: ships the TP-Link (Kasa / Tapo) SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/tplink
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
    agent_readiness: 25.8
    band: thin
    in_catalog: true
    kin_score: 31.9
    mcp: &id099
      source: https://github.com/tuya/tuya-mcp-sdk
      status: verified
    slug: tuya
    status: profiled
    tags: &id100
    - Cloud Platform
    - Devices
    - IoT
    - Smart Home
    url: /providers/tuya/
  layer: domain
  name: Tuya
  provider: tuya
  says: ships the Tuya SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/tuya
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 90.3
    mcp: &id101
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id102
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/twilio
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
    agent_band: agent-aware
    agent_readiness: 23.9
    band: developing
    in_catalog: true
    kin_score: 46.3
    mcp: &id103
      status: none
    slug: ubiquiti
    status: profiled
    tags: &id104
    - Networking
    - Routing
    - Switching
    - Wi-Fi
    url: /providers/ubiquiti/
  layer: domain
  name: Ubiquiti UniFi
  provider: ubiquiti
  says: ships the Ubiquiti UniFi SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/unifiprotect
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id105
      status: none
    slug: withings
    status: profiled
    tags: &id106
    - Body Composition
    - Connected Devices
    - Health
    - Wearables
    url: /providers/withings/
  layer: domain
  name: Withings
  provider: withings
  says: ships the Withings SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/withings
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
    agent_readiness: 25.4
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id107
      status: none
    slug: xiaomi
    status: profiled
    tags: &id108
    - Consumer Electronics
    - IoT
    - Mobile
    - Smart Home
    url: /providers/xiaomi/
  layer: domain
  name: Xiaomi (Mi Home)
  provider: xiaomi
  says: ships the Xiaomi (Mi Home) SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/xiaomi_miio
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
    agent_readiness: 4.5
    band: minimal
    in_catalog: true
    kin_score: 8.6
    mcp: &id109
      status: unknown
    slug: yale-home
    status: profiled
    tags: &id110
    - Company
    - Home Security
    - IoT
    - smart-locks
    url: /providers/yale-home/
  layer: domain
  name: Yale Home (smart locks)
  provider: yale-home
  says: ships the Yale Home (smart locks) SDK or integration code
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/yale
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/smart-home-iot/home-assistant/
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
  agent_readiness: 32.0
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id003
  name: Amazon Polly
  slug: amazon-polly
  status: profiled
  tags: *id004
  url: /providers/amazon-polly/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id005
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id006
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id007
  name: Apple HomeKit
  slug: apple
  status: profiled
  tags: *id008
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 13.8
  band: emerging
  in_catalog: true
  kin_score: 16.9
  mcp: *id009
  name: August Home
  slug: august
  status: profiled
  tags: *id010
  url: /providers/august/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.6
  mcp: *id011
  name: Belkin WeMo
  slug: belkin
  status: profiled
  tags: *id012
  url: /providers/belkin/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id013
  name: Blink (Amazon cameras)
  slug: blink-home
  status: queued for profiling
  tags: *id014
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.1
  mcp: *id015
  name: Daikin
  slug: daikin
  status: profiled
  tags: *id016
  url: /providers/daikin/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: thin
  in_catalog: true
  kin_score: 28.2
  mcp: *id017
  name: ecobee
  slug: ecobee
  status: profiled
  tags: *id018
  url: /providers/ecobee/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 11.6
  mcp: *id019
  name: EZVIZ
  slug: ezviz
  status: profiled
  tags: *id020
  url: /providers/ezviz/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id021
  name: Firebase Cloud Messaging
  slug: firebase
  status: profiled
  tags: *id022
  url: /providers/firebase/
- agent_band: agent-aware
  agent_readiness: 17.2
  band: thin
  in_catalog: true
  kin_score: 28.7
  mcp: *id023
  name: Google Assistant / Google Home
  slug: google-assistant
  status: profiled
  tags: *id024
  url: /providers/google-assistant/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id025
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id026
  url: /providers/google-gemini/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 41.4
  mcp: *id027
  name: Google Nest (Smart Device Management)
  slug: google-nest
  status: profiled
  tags: *id028
  url: /providers/google-nest/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: developing
  in_catalog: true
  kin_score: 51.6
  mcp: *id029
  name: Google Translate TTS
  slug: google-translate
  status: profiled
  tags: *id030
  url: /providers/google-translate/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id031
  name: Govee
  slug: govee
  status: profiled
  tags: *id032
  url: /providers/govee/
- agent_band: agent-ready
  agent_readiness: 43.3
  band: emerging
  in_catalog: true
  kin_score: 25.0
  mcp: *id033
  name: IFTTT
  slug: ifttt
  status: profiled
  tags: *id034
  url: /providers/ifttt/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 37.5
  mcp: *id035
  name: LIFX
  slug: lifx
  status: profiled
  tags: *id036
  url: /providers/lifx/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id037
  name: MET Norway (api.met.no)
  slug: met-no
  status: queued for profiling
  tags: *id038
  url: null
- agent_band: agent-aware
  agent_readiness: 14.4
  band: emerging
  in_catalog: true
  kin_score: 12.7
  mcp: *id039
  name: Mill (heaters)
  slug: mill-heat
  status: profiled
  tags: *id040
  url: /providers/mill-heat/
- agent_band: human-only
  agent_readiness: 4.5
  band: emerging
  in_catalog: true
  kin_score: 11.1
  mcp: *id041
  name: Nanoleaf
  slug: nanoleaf
  status: profiled
  tags: *id042
  url: /providers/nanoleaf/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 9.4
  mcp: *id043
  name: Netatmo
  slug: netatmo
  status: profiled
  tags: *id044
  url: /providers/netatmo/
- agent_band: agent-aware
  agent_readiness: 18.7
  band: emerging
  in_catalog: true
  kin_score: 14.2
  mcp: *id045
  name: NETGEAR
  slug: netgear
  status: profiled
  tags: *id046
  url: /providers/netgear/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: emerging
  in_catalog: true
  kin_score: 19.6
  mcp: *id047
  name: Nuki
  slug: nuki
  status: profiled
  tags: *id048
  url: /providers/nuki/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: emerging
  in_catalog: true
  kin_score: 24.5
  mcp: *id049
  name: OctoPrint
  slug: octoprint
  status: profiled
  tags: *id050
  url: /providers/octoprint/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id051
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id052
  url: /providers/ollama/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id053
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id054
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: strong
  in_catalog: true
  kin_score: 60.4
  mcp: *id055
  name: OpenWeatherMap
  slug: openweathermap
  status: profiled
  tags: *id056
  url: /providers/openweathermap/
- agent_band: agent-ready
  agent_readiness: 59.6
  band: strong
  in_catalog: true
  kin_score: 55.9
  mcp: *id057
  name: Plex
  slug: plex
  status: profiled
  tags: *id058
  url: /providers/plex/
- agent_band: agent-aware
  agent_readiness: 22.0
  band: thin
  in_catalog: true
  kin_score: 29.2
  mcp: *id059
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id060
  url: /providers/pushover/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: strong
  in_catalog: true
  kin_score: 56.7
  mcp: *id061
  name: Rachio
  slug: rachio
  status: profiled
  tags: *id062
  url: /providers/rachio/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 32.0
  mcp: *id063
  name: Reolink
  slug: reolink
  status: profiled
  tags: *id064
  url: /providers/reolink/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.1
  mcp: *id065
  name: Resideo (Honeywell Home)
  slug: resideo-technologies
  status: profiled
  tags: *id066
  url: /providers/resideo-technologies/
- agent_band: agent-ready
  agent_readiness: 34.1
  band: developing
  in_catalog: true
  kin_score: 43.9
  mcp: *id067
  name: Ring
  slug: ring
  status: profiled
  tags: *id068
  url: /providers/ring/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.1
  mcp: *id069
  name: Roborock
  slug: roborock
  status: profiled
  tags: *id070
  url: /providers/roborock/
- agent_band: agent-aware
  agent_readiness: 21.0
  band: thin
  in_catalog: true
  kin_score: 29.2
  mcp: *id071
  name: Samsung SmartThings
  slug: smartthings
  status: profiled
  tags: *id072
  url: /providers/smartthings/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id073
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id074
  url: /providers/sentry-system/
- agent_band: human-only
  agent_readiness: 4.5
  band: minimal
  in_catalog: true
  kin_score: 9.7
  mcp: *id075
  name: Shelly
  slug: shelly
  status: profiled
  tags: *id076
  url: /providers/shelly/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.4
  mcp: *id077
  name: Signify (Philips Hue, WiZ)
  slug: signify
  status: profiled
  tags: *id078
  url: /providers/signify/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.4
  mcp: *id079
  name: SimpliSafe
  slug: simplisafe
  status: profiled
  tags: *id080
  url: /providers/simplisafe/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.4
  mcp: *id081
  name: Somfy (TaHoma / Overkiz)
  slug: somfy
  status: profiled
  tags: *id082
  url: /providers/somfy/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id083
  name: Sonos
  slug: sonos
  status: profiled
  tags: *id084
  url: /providers/sonos/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id085
  name: Spotify
  slug: spotify
  status: profiled
  tags: *id086
  url: /providers/spotify/
- agent_band: agent-aware
  agent_readiness: 7.9
  band: minimal
  in_catalog: true
  kin_score: 8.7
  mcp: *id087
  name: SwitchBot
  slug: switchbot
  status: profiled
  tags: *id088
  url: /providers/switchbot/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: emerging
  in_catalog: true
  kin_score: 24.8
  mcp: *id089
  name: tado
  slug: tado
  status: profiled
  tags: *id090
  url: /providers/tado/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id091
  name: Telegram Bot API
  slug: telegram
  status: profiled
  tags: *id092
  url: /providers/telegram/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id093
  name: Tesla (Fleet API)
  slug: tesla
  status: profiled
  tags: *id094
  url: /providers/tesla/
- agent_band: agent-aware
  agent_readiness: 26.1
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id095
  name: Tibber
  slug: tibber
  status: profiled
  tags: *id096
  url: /providers/tibber/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 6.9
  mcp: *id097
  name: TP-Link (Kasa / Tapo)
  slug: tp-link
  status: profiled
  tags: *id098
  url: /providers/tp-link/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 31.9
  mcp: *id099
  name: Tuya
  slug: tuya
  status: profiled
  tags: *id100
  url: /providers/tuya/
- agent_band: agent-native
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 90.3
  mcp: *id101
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id102
  url: /providers/twilio/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: developing
  in_catalog: true
  kin_score: 46.3
  mcp: *id103
  name: Ubiquiti UniFi
  slug: ubiquiti
  status: profiled
  tags: *id104
  url: /providers/ubiquiti/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id105
  name: Withings
  slug: withings
  status: profiled
  tags: *id106
  url: /providers/withings/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id107
  name: Xiaomi (Mi Home)
  slug: xiaomi
  status: profiled
  tags: *id108
  url: /providers/xiaomi/
- agent_band: human-only
  agent_readiness: 4.5
  band: minimal
  in_catalog: true
  kin_score: 8.6
  mcp: *id109
  name: Yale Home (smart locks)
  slug: yale-home
  status: profiled
  tags: *id110
  url: /providers/yale-home/
siblings:
- name: Frigate
  rows: 4
  url: /applications/smart-home-iot/frigate/
- name: Homebridge
  rows: 38
  url: /applications/smart-home-iot/homebridge/
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
title: 'Home Assistant: Smart Home & Home Automation reference app'
---
