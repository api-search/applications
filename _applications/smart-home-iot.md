---
access: understanding
agent_layer:
- app: Home Assistant
  finding: ships an mcp_server integration exposing the Assist API to MCP clients, plus LLM conversation agents (OpenAI, Anthropic, Gemini, Ollama)
  source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/mcp_server
  tier: observed
- app: Hubitat Elevation
  finding: built-in AI (MCP) Connector Integration app
  source: https://docs2.hubitat.com/en/apps/ai-mcp-connector-integration
  tier: declared
- app: Frigate
  finding: BYO-LLM GenAI plugins describe camera events (OpenAI, Azure OpenAI, Gemini, Ollama, llama.cpp)
  source: https://github.com/blakeblackshear/frigate/tree/dev/frigate/genai/plugins
  tier: observed
apps:
- anchor: home-assistant
  counts:
    declared: 0
    observed: 55
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
    layer: domain
    name: Yale Home (smart locks)
    provider: yale-home
    says: ships the Yale Home (smart locks) SDK or integration code
    source: https://github.com/home-assistant/core/tree/dev/homeassistant/components/yale
    tier: observed
  kind: self-hosted
  name: Home Assistant
  page: /applications/smart-home-iot/home-assistant/
  slug: home-assistant
  url: https://github.com/home-assistant/core
- anchor: openhab
  counts:
    declared: 0
    observed: 39
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
    layer: domain
    name: Xiaomi (Mi Home)
    provider: xiaomi
    says: ships the Xiaomi (Mi Home) SDK or integration code
    source: https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.miio
    tier: observed
  kind: self-hosted
  name: openHAB
  page: /applications/smart-home-iot/openhab/
  slug: openhab
  url: https://github.com/openhab/openhab-addons
- anchor: homebridge
  counts:
    declared: 38
    observed: 0
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
    layer: domain
    name: Tuya
    provider: tuya
    says: lists Tuya as an integration
    source: https://github.com/homebridge/homebridge/wiki/Verified-Plugins
    tier: declared
  kind: self-hosted
  name: Homebridge
  page: /applications/smart-home-iot/homebridge/
  slug: homebridge
  url: https://github.com/homebridge/homebridge
- anchor: frigate
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://github.com/blakeblackshear/frigate/blob/dev/docker/main/requirements-wheels.txt
  - route: source code
    url: https://github.com/blakeblackshear/frigate/tree/dev/frigate/genai/plugins
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Azure OpenAI
    provider: microsoft-azure-openai
    says: ships the Azure OpenAI SDK or integration code
    source: https://github.com/blakeblackshear/frigate/tree/dev/frigate/genai/plugins/azure-openai.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Google Gemini
    provider: google-gemini
    says: ships the Google Gemini SDK or integration code
    source: https://github.com/blakeblackshear/frigate/tree/dev/frigate/genai/plugins/gemini.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Ollama
    provider: ollama
    says: ships the Ollama SDK or integration code
    source: https://github.com/blakeblackshear/frigate/tree/dev/frigate/genai/plugins/ollama.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/blakeblackshear/frigate/tree/dev/frigate/genai/plugins/openai.py
    tier: observed
  kind: self-hosted
  name: Frigate
  page: /applications/smart-home-iot/frigate/
  slug: frigate
  url: https://github.com/blakeblackshear/frigate
- anchor: smartthings
  counts:
    declared: 8
    observed: 0
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
    layer: domain
    name: Yale Home (smart locks)
    provider: yale-home
    says: lists Yale Home (smart locks) as an integration
    source: https://www.smartthings.com/works-with-smartthings
    tier: declared
  kind: commercial
  name: SmartThings
  page: /applications/smart-home-iot/smartthings/
  slug: smartthings
  url: https://www.smartthings.com/
- anchor: hubitat-elevation
  counts:
    declared: 17
    observed: 0
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
    layer: domain
    name: Ubiquiti UniFi
    provider: ubiquiti
    says: lists Ubiquiti UniFi as an integration
    source: https://docs2.hubitat.com/en/apps
    tier: declared
  kind: commercial
  name: Hubitat Elevation
  page: /applications/smart-home-iot/hubitat-elevation/
  slug: hubitat-elevation
  url: https://hubitat.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: smart-home-iot
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Lifestyle
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Utilities
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: House & Home
  store: google-play
  url: https://play.google.com/store/apps/category/HOUSE_AND_HOME
- category: Lifestyle
  store: google-play
  url: https://play.google.com/store/apps/category/LIFESTYLE
- category: Internet of Things (IoT)
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#internet-of-things-iot
- category: Video Surveillance
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#video-surveillance
name: Smart Home & Home Automation
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-200.10
    key: AE-200.10
    name: Smart Home
    url: /capabilities/smart-home/
    via_parent: null
  fit: exact
  layer: domain
  why: device clouds and local device APIs (lights, locks, climate, appliances, voice ecosystems) are the category
- capability:
    attribution: Turbo EA
    id: BC-2340.50
    key: physical-security-surveillance-management
    name: Physical Security & Surveillance Management
    url: /capabilities/physical-security-surveillance-management/
    via_parent: null
  fit: exact
  layer: domain
  why: cameras, doorbells and alarm systems
- capability:
    attribution: API Evangelist extension
    id: AE-200.30
    key: AE-200.30
    name: Home Energy
    url: /capabilities/home-energy/
    via_parent: null
  fit: exact
  layer: domain
  why: solar, battery and EV-charger energy data
- capability:
    attribution: API Evangelist extension
    id: AE-200.30.10
    key: AE-200.30.10
    name: Dynamic Electricity Tariffs
    url: /capabilities/home-energy/
    via_parent: Home Energy
  fit: exact
  layer: domain
  why: spot-price tariffs drive automations
- capability:
    attribution: API Evangelist extension
    id: AE-200.20.10
    key: AE-200.20.10
    name: Vehicle Data Access
    url: /capabilities/connected-vehicles/
    via_parent: Connected Vehicles
  fit: exact
  layer: domain
  why: the car as a home device (Tesla)
- capability:
    attribution: API Evangelist extension
    id: AE-200.60
    key: AE-200.60
    name: Home Network & DNS Filtering
    url: /capabilities/home-network-dns-filtering/
    via_parent: null
  fit: exact
  layer: domain
  why: router and network presence detection
- capability:
    attribution: API Evangelist extension
    id: AE-200.70
    key: AE-200.70
    name: 3D Printing & Printer Control
    url: /capabilities/3d-printing-printer-control/
    via_parent: null
  fit: exact
  layer: domain
  why: 3D printer status
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  fit: exact
  layer: domain
  why: weather for automations and dashboards
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  fit: exact
  layer: domain
  why: music playback
- capability:
    attribution: API Evangelist extension
    id: AE-170.90
    key: AE-170.90
    name: Self-Hosted Media Servers & Library Automation
    url: /capabilities/self-hosted-media-servers-library-automation/
    via_parent: null
  fit: exact
  layer: domain
  why: media server control
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: connected scales and health devices
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: applet bridges to other services
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: alerts to phones
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: chat-bot alerts and control
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: SMS alerts
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: conversation agents and camera event descriptions
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.40
    key: AE-110.10.40
    name: On-Device & Edge Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: local LLMs
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.20
    key: AE-110.30.20
    name: Text-to-Speech
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  fit: exact
  layer: agent
  why: voice announcements
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: companion-app crash reporting
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-200.10
      key: AE-200.10
      name: Smart Home
      url: /capabilities/smart-home/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Home Assistant
      - Homebridge
      - Hubitat Elevation
      - SmartThings
      - openHAB
      band: minimal
      in_catalog: true
      kin_score: 10.4
      mcp:
        status: unknown
      name: Signify (Philips Hue, WiZ)
      slug: signify
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/hue
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Company
      - IoT
      - Lighting
      - Smart Home
      tier: observed
      url: /providers/signify/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Home Assistant
      - Homebridge
      - SmartThings
      - openHAB
      band: developing
      in_catalog: true
      kin_score: 41.4
      mcp:
        status: none
      name: Google Nest (Smart Device Management)
      slug: google-nest
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/nest
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.nest
      status: profiled
      tags:
      - Camera
      - Device Management
      - Doorbell
      - Google Nest
      tier: observed
      url: /providers/google-nest/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Home Assistant
      - Homebridge
      - Hubitat Elevation
      - openHAB
      band: thin
      in_catalog: true
      kin_score: 37.5
      mcp:
        status: none
      name: LIFX
      slug: lifx
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/lifx
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Home Automation
      - Lighting Fixtures
      - Smart Lighting
      - Wi‑Fi Bulbs
      tier: observed
      url: /providers/lifx/
    - agent_band: agent-aware
      agent_readiness: 23.6
      apps:
      - Home Assistant
      - Homebridge
      - Hubitat Elevation
      - openHAB
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp:
        status: none
      name: Sonos
      slug: sonos
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/sonos
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Audio
      - Company
      - Consumer
      - Music
      tier: observed
      url: /providers/sonos/
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Home Assistant
      - Homebridge
      - Hubitat Elevation
      - openHAB
      band: thin
      in_catalog: true
      kin_score: 31.9
      mcp:
        source: https://github.com/tuya/tuya-mcp-sdk
        status: verified
      name: Tuya
      slug: tuya
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/tuya
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Cloud Platform
      - Devices
      - IoT
      - Smart Home
      tier: observed
      url: /providers/tuya/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Home Assistant
      - Homebridge
      - Hubitat Elevation
      - openHAB
      band: thin
      in_catalog: true
      kin_score: 28.9
      mcp:
        status: unknown
      name: Govee
      slug: govee
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/govee_light_local
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - IoT
      - LED
      - Smart Home
      - Smart Lighting
      tier: observed
      url: /providers/govee/
    - agent_band: human-only
      agent_readiness: 4.5
      apps:
      - Home Assistant
      - Homebridge
      - Hubitat Elevation
      - openHAB
      band: minimal
      in_catalog: true
      kin_score: 9.7
      mcp:
        source: https://shelly-api-docs.shelly.cloud/mcp
        status: verified
      name: Shelly
      slug: shelly
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/shelly
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Company
      - Devices
      - IoT
      - Smart Home
      tier: observed
      url: /providers/shelly/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Home Assistant
      - Homebridge
      - Hubitat Elevation
      - openHAB
      band: minimal
      in_catalog: true
      kin_score: 6.9
      mcp:
        status: unknown
      name: TP-Link (Kasa / Tapo)
      slug: tp-link
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/tplink
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Cloud
      - Company
      - Hardware
      - Networking
      tier: observed
      url: /providers/tp-link/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Home Assistant
      - Homebridge
      - Hubitat Elevation
      band: strong
      in_catalog: true
      kin_score: 56.7
      mcp:
        status: unknown
      name: Rachio
      slug: rachio
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/rachio
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Company
      - IoT
      - Irrigation
      - Smart Home
      tier: observed
      url: /providers/rachio/
    - agent_band: agent-ready
      agent_readiness: 46.8
      apps:
      - Home Assistant
      - Hubitat Elevation
      - openHAB
      band: developing
      in_catalog: true
      kin_score: 46.7
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon Alexa
      slug: amazon
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/alexa
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.amazonechocontrol
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: observed
      url: /providers/amazon/
    - agent_band: agent-aware
      agent_readiness: 21.0
      apps:
      - Home Assistant
      - Homebridge
      - openHAB
      band: thin
      in_catalog: true
      kin_score: 29.2
      mcp:
        status: none
      name: Samsung SmartThings
      slug: smartthings
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/smartthings
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.smartthings
      status: profiled
      tags:
      - Devices
      - Home Automation
      - IoT
      - Smart Home
      tier: observed
      url: /providers/smartthings/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Home Assistant
      - Hubitat Elevation
      - openHAB
      band: thin
      in_catalog: true
      kin_score: 28.2
      mcp:
        status: none
      name: ecobee
      slug: ecobee
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/ecobee
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.ecobee
      status: profiled
      tags:
      - HVAC
      - IoT
      - Smart Home
      - Thermostat
      tier: observed
      url: /providers/ecobee/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - Home Assistant
      - Homebridge
      - openHAB
      band: emerging
      in_catalog: true
      kin_score: 24.8
      mcp:
        status: unknown
      name: tado
      slug: tado
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/tado
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.tado
      status: profiled
      tags:
      - Company
      - EnergySaving
      - Heating
      - Smart Home
      tier: observed
      url: /providers/tado/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Home Assistant
      - Homebridge
      - openHAB
      band: emerging
      in_catalog: true
      kin_score: 19.6
      mcp:
        status: none
      name: Nuki
      slug: nuki
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/nuki
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.nuki
      status: profiled
      tags:
      - Company
      - Home Automation
      - IoT
      - Smart Lock
      tier: observed
      url: /providers/nuki/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Home Assistant
      - SmartThings
      - openHAB
      band: minimal
      in_catalog: true
      kin_score: 4.4
      mcp:
        status: unknown
      name: Somfy (TaHoma / Overkiz)
      slug: somfy
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/overkiz
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.somfytahoma
      - https://www.smartthings.com/works-with-smartthings
      status: profiled
      tags:
      - Company
      - Home Automation
      - IoT
      - Smart Home
      tier: observed
      url: /providers/somfy/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Home Assistant
      - Homebridge
      - openHAB
      band: minimal
      in_catalog: true
      kin_score: 3.1
      mcp:
        status: unknown
      name: Daikin
      slug: daikin
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/daikin
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.daikin
      status: profiled
      tags:
      - Air Conditioning
      - Company
      - HVAC
      - Refrigeration
      tier: observed
      url: /providers/daikin/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Home Assistant
      - Homebridge
      - SmartThings
      band: minimal
      in_catalog: true
      kin_score: 1.1
      mcp:
        status: unknown
      name: Resideo (Honeywell Home)
      slug: resideo-technologies
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/lyric
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      - https://www.smartthings.com/works-with-smartthings
      status: profiled
      tags: []
      tier: observed
      url: /providers/resideo-technologies/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Home Assistant
      - Hubitat Elevation
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Apple HomeKit
      slug: apple
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/homekit
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Home Assistant
      - openHAB
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Xiaomi (Mi Home)
      slug: xiaomi
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/xiaomi_miio
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.miio
      status: profiled
      tags:
      - Consumer Electronics
      - IoT
      - Mobile
      - Smart Home
      tier: observed
      url: /providers/xiaomi/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Homebridge
      - openHAB
      band: thin
      in_catalog: true
      kin_score: 29.1
      mcp:
        status: none
      name: Sensibo
      slug: sensibo
      sources:
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.sensibo
      status: profiled
      tags:
      - Air Conditioning
      - HVAC
      - IoT
      - Smart Home
      tier: observed
      url: /providers/sensibo/
    - agent_band: agent-aware
      agent_readiness: 17.2
      apps:
      - Home Assistant
      - Hubitat Elevation
      band: thin
      in_catalog: true
      kin_score: 28.7
      mcp:
        status: unknown
      name: Google Assistant / Google Home
      slug: google-assistant
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/google_assistant
      status: profiled
      tags:
      - Actions on Google
      - Conversational AI
      - Google Assistant
      - Natural-Language
      tier: observed
      url: /providers/google-assistant/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Homebridge
      - openHAB
      band: thin
      in_catalog: true
      kin_score: 28.6
      mcp:
        status: unknown
      name: Home Connect (BSH appliances)
      slug: home-connect
      sources:
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.homeconnect
      status: profiled
      tags:
      - Appliances
      - Connected Devices
      - Smart Home
      tier: observed
      url: /providers/home-connect/
    - agent_band: agent-aware
      agent_readiness: 21.8
      apps:
      - Homebridge
      - openHAB
      band: emerging
      in_catalog: true
      kin_score: 24.9
      mcp:
        status: unknown
      name: Miele
      slug: miele
      sources:
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.mielecloud
      status: profiled
      tags:
      - Appliances
      - Company
      - Homes
      - Technology
      tier: observed
      url: /providers/miele/
    - agent_band: agent-aware
      agent_readiness: 13.8
      apps:
      - Home Assistant
      - Homebridge
      band: emerging
      in_catalog: true
      kin_score: 16.9
      mcp:
        status: unknown
      name: August Home
      slug: august
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/august
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Company
      - Consumer
      - Smart Home
      - Smart Lock
      tier: observed
      url: /providers/august/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Home Assistant
      - openHAB
      band: emerging
      in_catalog: true
      kin_score: 14.1
      mcp:
        status: unknown
      name: Roborock
      slug: roborock
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/roborock
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.roborock
      status: profiled
      tags:
      - Company
      - Consumer IoT
      - Robot Vacuum
      - Robotics
      tier: observed
      url: /providers/roborock/
    - agent_band: agent-aware
      agent_readiness: 14.4
      apps:
      - Home Assistant
      - openHAB
      band: emerging
      in_catalog: true
      kin_score: 12.7
      mcp:
        status: unknown
      name: Mill (heaters)
      slug: mill-heat
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/mill
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.millheat
      status: profiled
      tags:
      - Company
      - Heating
      - IoT
      - ScandinavianDesign
      tier: observed
      url: /providers/mill-heat/
    - agent_band: human-only
      agent_readiness: 4.5
      apps:
      - Home Assistant
      - openHAB
      band: emerging
      in_catalog: true
      kin_score: 11.1
      mcp:
        source: https://nanoleaf.me
        status: documented
      name: Nanoleaf
      slug: nanoleaf
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/nanoleaf
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.nanoleaf
      status: profiled
      tags:
      - Company
      - Home Automation
      - IoT
      - Smart Lighting
      tier: observed
      url: /providers/nanoleaf/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homebridge
      - openHAB
      band: emerging
      in_catalog: true
      kin_score: 11.0
      mcp:
        source: https://github.com/ecovacs-ai/ecovacs-mcp
        status: verified
      name: ECOVACS
      slug: ecovacs-robotics
      sources:
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.ecovacs
      status: profiled
      tags:
      - Company
      - Consumer Technology
      - Home Automation
      - Robotics
      tier: observed
      url: /providers/ecovacs-robotics/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Home Assistant
      - openHAB
      band: minimal
      in_catalog: true
      kin_score: 9.4
      mcp:
        status: none
      name: Netatmo
      slug: netatmo
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/netatmo
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.netatmo
      status: profiled
      tags:
      - Company
      - Devices
      - IoT
      - Smart Home
      tier: observed
      url: /providers/netatmo/
    - agent_band: agent-aware
      agent_readiness: 7.9
      apps:
      - Home Assistant
      - Homebridge
      band: minimal
      in_catalog: true
      kin_score: 8.7
      mcp:
        status: unknown
      name: SwitchBot
      slug: switchbot
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/switchbot
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Automation
      - IoT
      - Robotics
      - Smart Home
      tier: observed
      url: /providers/switchbot/
    - agent_band: human-only
      agent_readiness: 4.5
      apps:
      - Home Assistant
      - SmartThings
      band: minimal
      in_catalog: true
      kin_score: 8.6
      mcp:
        status: unknown
      name: Yale Home (smart locks)
      slug: yale-home
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/yale
      - https://www.smartthings.com/works-with-smartthings
      status: profiled
      tags:
      - Company
      - Home Security
      - IoT
      - smart-locks
      tier: observed
      url: /providers/yale-home/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Home Assistant
      - openHAB
      band: minimal
      in_catalog: true
      kin_score: 7.6
      mcp:
        status: unknown
      name: Belkin WeMo
      slug: belkin
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/wemo
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.wemo
      status: profiled
      tags:
      - Cables
      - Chargers
      - Phone Cases
      - Power Banks
      tier: observed
      url: /providers/belkin/
    - agent_band: agent-aware
      agent_readiness: 12.9
      apps:
      - Homebridge
      - Hubitat Elevation
      band: emerging
      in_catalog: true
      kin_score: 25.2
      mcp:
        status: none
      name: Bond (fan / shade bridge)
      slug: bond-home
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Company
      - Home Automation
      - IoT
      - Smart Home
      tier: declared
      url: /providers/bond-home/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homebridge
      - Hubitat Elevation
      band: minimal
      in_catalog: true
      kin_score: 3.2
      mcp:
        status: unknown
      name: Lutron (Caseta)
      slug: lutron
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Company
      - Home Automation
      - Lighting
      - Smart Home
      tier: declared
      url: /providers/lutron/
    - agent_band: agent-ready
      agent_readiness: 48.5
      apps:
      - openHAB
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Cast (Chromecast)
      slug: google
      sources:
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.chromecast
      status: profiled
      tags:
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: observed
      url: /providers/google/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - openHAB
      band: minimal
      in_catalog: true
      kin_score: 7.2
      mcp:
        status: unknown
      name: Warmup (underfloor heating)
      slug: warmup
      sources:
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.warmup
      status: profiled
      tags:
      - Company
      - Home Improvement
      - Underfloor Heating
      - United Kingdom
      tier: observed
      url: /providers/warmup/
    - agent_band: agent-ready
      agent_readiness: 36.7
      apps:
      - Homebridge
      band: developing
      in_catalog: true
      kin_score: 47.1
      mcp:
        status: none
      name: Airthings
      slug: airthings
      sources:
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Air Quality
      - Company
      - Radon
      - Sensors
      tier: declared
      url: /providers/airthings/
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - SmartThings
      band: thin
      in_catalog: true
      kin_score: 35.6
      mcp:
        source: https://github.com/aqara/aqara-mcp-server
        status: verified
      name: Aqara
      slug: aqara
      sources:
      - https://www.smartthings.com/works-with-smartthings
      status: profiled
      tags:
      - Consumer Electronics
      - Home Automation
      - IoT
      - Smart Home
      tier: declared
      url: /providers/aqara/
    - agent_band: agent-aware
      agent_readiness: 20.1
      apps:
      - Hubitat Elevation
      band: thin
      in_catalog: true
      kin_score: 26.9
      mcp:
        status: none
      name: SharpTools
      slug: sharptools
      sources:
      - https://docs2.hubitat.com/en/apps
      status: profiled
      tags:
      - Automation
      - Dashboards
      - Rule Engine
      - Smart Home
      tier: declared
      url: /providers/sharptools/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Homebridge
      band: emerging
      in_catalog: true
      kin_score: 15.2
      mcp:
        status: unknown
      name: Rain Bird
      slug: rainbird
      sources:
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Agriculture
      - Company
      - Irrigation
      - Water Management
      tier: declared
      url: /providers/rainbird/
    - agent_band: human-only
      agent_readiness: 4.5
      apps:
      - Homebridge
      band: emerging
      in_catalog: true
      kin_score: 11.9
      mcp:
        status: unknown
      name: Meross
      slug: meross
      sources:
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Automation
      - Consumer
      - IoT
      - Smart Home
      tier: declared
      url: /providers/meross/
    - agent_band: human-only
      agent_readiness: 4.5
      apps:
      - Homebridge
      band: minimal
      in_catalog: true
      kin_score: 9.8
      mcp:
        status: none
      name: eWeLink (ITEAD / Sonoff)
      slug: ewelink
      sources:
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Automation
      - Cloud Platform
      - IoT
      - Smart Home
      tier: declared
      url: /providers/ewelink/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - SmartThings
      band: minimal
      in_catalog: true
      kin_score: 8.0
      mcp:
        status: none
      name: Eve Systems
      slug: eve-systems
      sources:
      - https://www.smartthings.com/works-with-smartthings
      status: profiled
      tags:
      - Company
      - HomeKit
      - IoT
      - Smart Home
      tier: declared
      url: /providers/eve-systems/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homebridge
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: unknown
      name: iRobot
      slug: irobot
      sources:
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Consumer Robotics
      - Home Robotics
      - Robot Vacuums
      - Robotics
      tier: declared
      url: /providers/irobot/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homebridge
      band: minimal
      in_catalog: true
      kin_score: 4.6
      mcp:
        status: unknown
      name: LG ThinQ
      slug: lg-electronics
      sources:
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Company
      - Consumer Electronics
      - IoT
      - Smart Home
      tier: declared
      url: /providers/lg-electronics/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homebridge
      band: minimal
      in_catalog: true
      kin_score: 3.1
      mcp:
        status: unknown
      name: Chamberlain myQ
      slug: chamberlain
      sources:
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Company
      - Garage Door
      - IoT
      - Smart Home
      tier: declared
      url: /providers/chamberlain/
  - capability:
      attribution: Turbo EA
      id: BC-2340.50
      key: physical-security-surveillance-management
      name: Physical Security & Surveillance Management
      url: /capabilities/physical-security-surveillance-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.1
      apps:
      - Home Assistant
      - Homebridge
      - Hubitat Elevation
      - SmartThings
      - openHAB
      band: developing
      in_catalog: true
      kin_score: 43.9
      mcp:
        status: none
      name: Ring
      slug: ring
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/ring
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Company
      - Home Security
      - IoT
      - Smart Home
      tier: observed
      url: /providers/ring/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Home Assistant
      - Homebridge
      band: emerging
      in_catalog: true
      kin_score: 16.4
      mcp:
        status: none
      name: SimpliSafe
      slug: simplisafe
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/simplisafe
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Alarms
      - Home Security
      - Security Systems
      - Wireless
      tier: observed
      url: /providers/simplisafe/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Home Assistant
      - Homebridge
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: unknown
      name: EZVIZ
      slug: ezviz
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/ezviz
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Security Cameras
      - Smart Entry
      - Smart Home
      - Smart Home Appliance
      tier: observed
      url: /providers/ezviz/
    - agent_band: null
      agent_readiness: null
      apps:
      - Home Assistant
      - Homebridge
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Blink (Amazon cameras)
      slug: blink-home
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/blink
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Home Assistant
      band: thin
      in_catalog: true
      kin_score: 32.0
      mcp:
        status: none
      name: Reolink
      slug: reolink
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/reolink
      status: profiled
      tags:
      - IoT
      - Security Cameras
      - Smart Home
      - Surveillance
      tier: observed
      url: /providers/reolink/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Homebridge
      band: emerging
      in_catalog: true
      kin_score: 12.1
      mcp:
        status: unknown
      name: eufy (Anker)
      slug: anker-innovations
      sources:
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - Company
      - Consumer Electronics
      - Consumer Technology
      - Smart Home
      tier: declared
      url: /providers/anker-innovations/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.60
      key: AE-200.60
      name: Home Network & DNS Filtering
      url: /capabilities/home-network-dns-filtering/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Home Assistant
      - Hubitat Elevation
      - openHAB
      band: developing
      in_catalog: true
      kin_score: 46.3
      mcp:
        status: none
      name: Ubiquiti UniFi
      slug: ubiquiti
      sources:
      - https://docs2.hubitat.com/en/apps
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/unifiprotect
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.unifi
      status: profiled
      tags:
      - Networking
      - Routing
      - Switching
      - Wi-Fi
      tier: observed
      url: /providers/ubiquiti/
    - agent_band: agent-aware
      agent_readiness: 18.7
      apps:
      - Home Assistant
      band: emerging
      in_catalog: true
      kin_score: 14.2
      mcp:
        status: none
      name: NETGEAR
      slug: netgear
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/netgear
      status: profiled
      tags:
      - Company
      - Consumer
      - Hardware
      - Networking
      tier: observed
      url: /providers/netgear/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30.10
      key: AE-200.30.10
      name: Dynamic Electricity Tariffs
      url: /capabilities/home-energy/
      via_parent: Home Energy
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.1
      apps:
      - Home Assistant
      - Homebridge
      - openHAB
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        status: none
      name: Tibber
      slug: tibber
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/tibber
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.tibber
      status: profiled
      tags:
      - ElectricityPricing
      - Energy
      - Smart Home
      - Smart Meter
      tier: observed
      url: /providers/tibber/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.30
      key: AE-200.30
      name: Home Energy
      url: /capabilities/home-energy/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.1
      apps:
      - openHAB
      band: developing
      in_catalog: true
      kin_score: 49.0
      mcp:
        status: unknown
      name: Tesla Energy (Powerwall)
      slug: tesla-energy
      sources:
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.teslapowerwall
      status: profiled
      tags:
      - Battery Storage
      - Clean Energy
      - Energy
      - Solar
      tier: observed
      url: /providers/tesla-energy/
    - agent_band: agent-ready
      agent_readiness: 31.2
      apps:
      - openHAB
      band: thin
      in_catalog: true
      kin_score: 38.8
      mcp:
        source: https://docs.evcc.io/en/integrations/mcp.md
        status: verified
      name: evcc
      slug: evcc
      sources:
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.evcc
      status: profiled
      tags:
      - Company
      - Electric Vehicles
      - Open Source
      - Smart Charging
      tier: observed
      url: /providers/evcc/
    - agent_band: agent-ready
      agent_readiness: 35.9
      apps:
      - Homebridge
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        status: none
      name: Enphase Envoy
      slug: enphase
      sources:
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      status: profiled
      tags:
      - DER
      - Energy
      - Solar
      - United States
      tier: declared
      url: /providers/enphase/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.90
      key: AE-170.90
      name: Self-Hosted Media Servers & Library Automation
      url: /capabilities/self-hosted-media-servers-library-automation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.6
      apps:
      - Home Assistant
      - Homebridge
      - openHAB
      band: strong
      in_catalog: true
      kin_score: 55.9
      mcp:
        status: none
      name: Plex
      slug: plex
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/plex
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.plex
      status: profiled
      tags:
      - Company
      - Media
      - Streaming
      - Video
      tier: observed
      url: /providers/plex/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20.10
      key: AE-200.20.10
      name: Vehicle Data Access
      url: /capabilities/connected-vehicles/
      via_parent: Connected Vehicles
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - Home Assistant
      - Homebridge
      - openHAB
      band: thin
      in_catalog: true
      kin_score: 35.5
      mcp:
        status: none
      name: Tesla (Fleet API)
      slug: tesla
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/tesla_fleet
      - https://github.com/homebridge/homebridge/wiki/Verified-Plugins
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.tesla
      status: profiled
      tags:
      - Automobiles
      - Cars
      - Electric Vehicles
      - Vehicles
      tier: observed
      url: /providers/tesla/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.5
      apps:
      - Home Assistant
      - openHAB
      band: strong
      in_catalog: true
      kin_score: 60.4
      mcp:
        source: https://mcp.openweathermap.org/
        status: verified
      name: OpenWeatherMap
      slug: openweathermap
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/openweathermap
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.openweathermap
      status: profiled
      tags:
      - Air Pollution
      - Climate
      - Forecast
      - Weather
      tier: observed
      url: /providers/openweathermap/
    - agent_band: null
      agent_readiness: null
      apps:
      - Home Assistant
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: MET Norway (api.met.no)
      slug: met-no
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/met
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20.10
      key: AE-170.20.10
      name: Music Streaming & Catalog
      url: /capabilities/audio-music/
      via_parent: Audio & Music
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.3
      apps:
      - Home Assistant
      - openHAB
      band: developing
      in_catalog: true
      kin_score: 49.8
      mcp:
        status: none
      name: Spotify
      slug: spotify
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/spotify
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.spotify
      status: profiled
      tags:
      - Audio
      - Music
      - Podcasts
      - Streaming
      tier: observed
      url: /providers/spotify/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.70
      key: AE-200.70
      name: 3D Printing & Printer Control
      url: /capabilities/3d-printing-printer-control/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Home Assistant
      band: emerging
      in_catalog: true
      kin_score: 24.5
      mcp:
        status: none
      name: OctoPrint
      slug: octoprint
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/octoprint
      status: profiled
      tags:
      - 3D Printing
      - Company
      - IoT
      - Open Source
      tier: observed
      url: /providers/octoprint/
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Home Assistant
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Withings
      slug: withings
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/withings
      status: profiled
      tags:
      - Body Composition
      - Connected Devices
      - Health
      - Wearables
      tier: observed
      url: /providers/withings/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.0
      apps:
      - Home Assistant
      - openHAB
      band: thin
      in_catalog: true
      kin_score: 29.2
      mcp:
        status: none
      name: Pushover
      slug: pushover
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/pushover
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.pushover
      status: profiled
      tags:
      - Alerts
      - Messaging
      - Notification
      - Push Notifications
      tier: observed
      url: /providers/pushover/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Home Assistant
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase Cloud Messaging
      slug: firebase
      sources:
      - https://github.com/home-assistant/android/blob/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - openHAB
      band: minimal
      in_catalog: true
      kin_score: 9.9
      mcp:
        status: none
      name: ntfy
      slug: ntfy
      sources:
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.ntfy
      status: profiled
      tags:
      - Notification
      - Open Source
      - Pub/Sub
      - Self-Hosted
      tier: observed
      url: /providers/ntfy/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Home Assistant
      - openHAB
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        status: none
      name: Telegram Bot API
      slug: telegram
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/telegram_bot
      - https://github.com/openhab/openhab-addons/tree/main/bundles/org.openhab.binding.telegram
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Home Assistant
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/home-assistant/android/blob/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 56.4
      apps:
      - Home Assistant
      band: exemplar
      in_catalog: true
      kin_score: 90.3
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/twilio
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.3
      apps:
      - Home Assistant
      band: emerging
      in_catalog: true
      kin_score: 25.0
      mcp:
        source: https://github.com/IFTTT/ifttt-plugins
        status: verified
      name: IFTTT
      slug: ifttt
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/ifttt
      status: profiled
      tags:
      - Automation
      - No-Code
      - Webhook
      - iPaaS
      tier: observed
      url: /providers/ifttt/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - Frigate
      - Home Assistant
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/blakeblackshear/frigate/tree/dev/frigate/genai/plugins/openai.py
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/openai_conversation
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Frigate
      - Home Assistant
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://github.com/blakeblackshear/frigate/tree/dev/frigate/genai/plugins/gemini.py
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/google_generative_ai_conversation
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Home Assistant
      band: exemplar
      in_catalog: true
      kin_score: 87.5
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/anthropic
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - Frigate
      band: developing
      in_catalog: true
      kin_score: 44.6
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure OpenAI
      slug: microsoft-azure-openai
      sources:
      - https://github.com/blakeblackshear/frigate/tree/dev/frigate/genai/plugins/azure-openai.py
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - GPT
      - Generative AI
      tier: observed
      url: /providers/microsoft-azure-openai/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Frigate
      - Home Assistant
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Ollama
      slug: ollama
      sources:
      - https://github.com/blakeblackshear/frigate/tree/dev/frigate/genai/plugins/ollama.py
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/ollama
      status: profiled
      tags:
      - Artificial Intelligence
      - LLM
      - Models
      - Ollama
      tier: observed
      url: /providers/ollama/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.20
      key: AE-110.30.20
      name: Text-to-Speech
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.0
      apps:
      - Home Assistant
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        status: none
      name: Amazon Polly
      slug: amazon-polly
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/amazon_polly
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Machine Learning
      - Speech Synthesis
      tier: observed
      url: /providers/amazon-polly/
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - Home Assistant
      band: developing
      in_catalog: true
      kin_score: 51.6
      mcp:
        status: none
      name: Google Translate TTS
      slug: google-translate
      sources:
      - https://github.com/home-assistant/core/tree/dev/homeassistant/components/google_translate
      status: profiled
      tags:
      - Google Cloud
      - Internationalization
      - Language Detection
      - Localization
      tier: observed
      url: /providers/google-translate/
  layer: agent
summary:
  coverage_pct: 97.5
  declared_only: 14
  distinct_providers: 79
  in_catalog: 77
  mcp:
    documented: 1
    none: 34
    unchecked: 2
    verified: 15
  mcp_verified: 15
  mean_kin_score: 31.3
  observed: 65
  queued: 2
  reference_apps: 6
title: 'Smart Home & Home Automation: application blueprint'
---
