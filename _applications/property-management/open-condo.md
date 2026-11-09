---
app: Open Condo
app_slug: open-condo
app_url: https://github.com/open-condo-software/condo
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.10.30
  key: AE-120.10.30
  layer: common
  name: Address Validation & Autocomplete
  providers:
  - DaData
  - Google Places
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Yandex Metrica
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Apple Push / Sign in with Apple
  - Firebase Cloud Messaging
  - Huawei Push Kit (HCM)
  - OneSignal
  - RuStore push
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Instasent
  - SMS.ru
  - SMSC.ru
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Sber ID / SberCloud
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-911
  key: AE-911
  layer: common
  name: Tag Management
  providers:
  - Google Tag Manager
  url: /capabilities/product-telemetry-instrumentation/
  via_parent: Product Telemetry Instrumentation
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - Telegram
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Flowise
  - n8n
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: property-management
  name: Property & Rental Management
  url: /applications/property-management/
counts:
  declared: 0
  observed: 18
credits: []
evidence:
- route: source code
  url: https://github.com/open-condo-software/condo/tree/main/apps/address-service/domains/common/utils/services
- route: source code
  url: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/ai/adapters
- route: source code
  url: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/common/components/containers
- route: source code
  url: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/notification/adapters
- route: source code
  url: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/user/integration
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/open-condo-software/condo/blob/main/apps/condo/domains/common/utils/awsFileAdapter.spec.js
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
  layer: common
  name: Apple Push / Sign in with Apple
  provider: apple
  says: ships the Apple Push / Sign in with Apple SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/notification/adapters/appleAdapter.js
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.30
    key: AE-120.10.30
    name: Address Validation & Autocomplete
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.5
    band: thin
    in_catalog: true
    kin_score: 28.6
    mcp: &id005
      source: https://dadata.ru/mcp/
      status: verified
    slug: dadata
    status: profiled
    tags: &id006
    - AddressStandardization
    - Data
    - Data Enrichment
    - Russian
    url: /providers/dadata/
  layer: common
  name: DaData
  provider: dadata
  says: ships the DaData SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/address-service/domains/common/utils/services/suggest/providers/DadataSuggestionProvider.js
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
    mcp: &id007
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id008
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase Cloud Messaging
  provider: firebase
  says: ships the Firebase Cloud Messaging SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/notification/adapters/firebaseAdapter.js
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
    agent_band: agent-aware
    agent_readiness: 21.3
    band: thin
    in_catalog: true
    kin_score: 37.1
    mcp: &id009
      status: none
    slug: flowise
    status: profiled
    tags: &id010
    - Agent Workflows
    - Agents
    - Artificial Intelligence
    - LLM
    url: /providers/flowise/
  layer: common
  name: Flowise
  provider: flowise
  says: ships the Flowise SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/ai/adapters/FlowiseAdapter.js
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.30
    key: AE-120.10.30
    name: Address Validation & Autocomplete
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.3
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id011
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-places
    status: profiled
    tags: &id012
    - Geolocation
    - Google
    - Location
    - Restaurant
    url: /providers/google-places/
  layer: common
  name: Google Places
  provider: google-places
  says: ships the Google Places SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/address-service/domains/common/utils/services/suggest/providers/GoogleSuggestionProvider.js
  tier: observed
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
    agent_readiness: 38.2
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id013
      status: none
    slug: google-tag-manager
    status: profiled
    tags: &id014
    - Analytics
    - Conversion Tracking
    - Marketing
    - Tag Management
    url: /providers/google-tag-manager/
  layer: common
  name: Google Tag Manager
  provider: google-tag-manager
  says: ships the Google Tag Manager SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/common/components/containers/GoogleTagManager.tsx
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id015
      status: unchecked
    slug: huawei
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: common
  name: Huawei Push Kit (HCM)
  provider: huawei
  says: ships the Huawei Push Kit (HCM) SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/notification/adapters/hcmAdapter.js
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
    agent_band: agent-ready
    agent_readiness: 47.1
    band: developing
    in_catalog: true
    kin_score: 49.5
    mcp: &id017
      source: https://docs.instasent.com/a2p-messaging-api/http/reference/
      status: documented
    slug: instasent
    status: profiled
    tags: &id018
    - Company
    - Messaging
    - RCS
    - SMS
    url: /providers/instasent/
  layer: common
  name: Instasent
  provider: instasent
  says: ships the Instasent SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/notification/adapters/smsAdapter.js
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
    agent_readiness: 36.4
    band: exemplar
    in_catalog: true
    kin_score: 71.3
    mcp: &id019
      source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
      status: verified
    slug: n8n
    status: profiled
    tags: &id020
    - Agents
    - Artificial Intelligence
    - Integration
    - Workflows
    url: /providers/n8n/
  layer: common
  name: n8n
  provider: n8n
  says: ships the n8n SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/ai/adapters/N8NAdapter.js
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
    agent_band: agent-native
    agent_readiness: 71.3
    band: exemplar
    in_catalog: true
    kin_score: 78.0
    mcp: &id021
      source: https://github.com/OneSignal/onesignal-ai-skills
      status: documented
    slug: onesignal
    status: profiled
    tags: &id022
    - Email
    - Notification
    - Push
    - SMS
    url: /providers/onesignal/
  layer: common
  name: OneSignal
  provider: onesignal
  says: ships the OneSignal SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/notification/adapters/oneSignalAdapter.js
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id023
      status: unchecked
    slug: rustore
    status: queued for profiling
    tags: &id024 []
    url: null
  layer: common
  name: RuStore push
  provider: rustore
  says: ships the RuStore push SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/notification/adapters/redStoreAdapter.js
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.8
    band: thin
    in_catalog: true
    kin_score: 28.0
    mcp: &id025
      status: unknown
    slug: sber
    status: profiled
    tags: &id026
    - Cloud
    - Computing
    - Infrastructure
    - Storage
    url: /providers/sber/
  layer: common
  name: Sber ID / SberCloud
  provider: sber
  says: ships the Sber ID / SberCloud SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/user/integration/sberid
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
    agent_band: agent-aware
    agent_readiness: 22.8
    band: emerging
    in_catalog: true
    kin_score: 17.8
    mcp: &id027
      status: unknown
    slug: sms-ru
    status: profiled
    tags: &id028
    - Company
    - Messaging
    - Russia
    - SMS
    url: /providers/sms-ru/
  layer: common
  name: SMS.ru
  provider: sms-ru
  says: ships the SMS.ru SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/notification/adapters/smsAdapter.js
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
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 5.8
    mcp: &id029
      status: none
    slug: smsc
    status: profiled
    tags: &id030
    - Messaging
    - Russia
    - SMS
    - Telecommunications
    url: /providers/smsc/
  layer: common
  name: SMSC.ru
  provider: smsc
  says: ships the SMSC.ru SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/notification/adapters/smsAdapter.js
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
    mcp: &id031
      status: none
    slug: telegram
    status: profiled
    tags: &id032
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/notification/transports/telegram.js
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
    mcp: &id033
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id034
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/notification/adapters/smsAdapter.js
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.6
    mcp: &id035
      status: none
    slug: yandex-metrica
    status: profiled
    tags: &id036
    - Analytics
    - Marketing
    - Web Analytics
    - Yandex
    url: /providers/yandex-metrica/
  layer: common
  name: Yandex Metrica
  provider: yandex-metrica
  says: ships the Yandex Metrica SDK or integration code
  source: https://github.com/open-condo-software/condo/tree/main/apps/condo/domains/common/components/containers/YandexMetrika.tsx
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/property-management/open-condo/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id003
  name: Apple Push / Sign in with Apple
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: thin
  in_catalog: true
  kin_score: 28.6
  mcp: *id005
  name: DaData
  slug: dadata
  status: profiled
  tags: *id006
  url: /providers/dadata/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id007
  name: Firebase Cloud Messaging
  slug: firebase
  status: profiled
  tags: *id008
  url: /providers/firebase/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: thin
  in_catalog: true
  kin_score: 37.1
  mcp: *id009
  name: Flowise
  slug: flowise
  status: profiled
  tags: *id010
  url: /providers/flowise/
- agent_band: agent-ready
  agent_readiness: 32.3
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id011
  name: Google Places
  slug: google-places
  status: profiled
  tags: *id012
  url: /providers/google-places/
- agent_band: agent-ready
  agent_readiness: 38.2
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id013
  name: Google Tag Manager
  slug: google-tag-manager
  status: profiled
  tags: *id014
  url: /providers/google-tag-manager/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: Huawei Push Kit (HCM)
  slug: huawei
  status: queued for profiling
  tags: *id016
  url: null
- agent_band: agent-ready
  agent_readiness: 47.1
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id017
  name: Instasent
  slug: instasent
  status: profiled
  tags: *id018
  url: /providers/instasent/
- agent_band: agent-ready
  agent_readiness: 36.4
  band: exemplar
  in_catalog: true
  kin_score: 71.3
  mcp: *id019
  name: n8n
  slug: n8n
  status: profiled
  tags: *id020
  url: /providers/n8n/
- agent_band: agent-native
  agent_readiness: 71.3
  band: exemplar
  in_catalog: true
  kin_score: 78.0
  mcp: *id021
  name: OneSignal
  slug: onesignal
  status: profiled
  tags: *id022
  url: /providers/onesignal/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id023
  name: RuStore push
  slug: rustore
  status: queued for profiling
  tags: *id024
  url: null
- agent_band: agent-aware
  agent_readiness: 22.8
  band: thin
  in_catalog: true
  kin_score: 28.0
  mcp: *id025
  name: Sber ID / SberCloud
  slug: sber
  status: profiled
  tags: *id026
  url: /providers/sber/
- agent_band: agent-aware
  agent_readiness: 22.8
  band: emerging
  in_catalog: true
  kin_score: 17.8
  mcp: *id027
  name: SMS.ru
  slug: sms-ru
  status: profiled
  tags: *id028
  url: /providers/sms-ru/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 5.8
  mcp: *id029
  name: SMSC.ru
  slug: smsc
  status: profiled
  tags: *id030
  url: /providers/smsc/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id031
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id032
  url: /providers/telegram/
- agent_band: agent-native
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 90.3
  mcp: *id033
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id034
  url: /providers/twilio/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.6
  mcp: *id035
  name: Yandex Metrica
  slug: yandex-metrica
  status: profiled
  tags: *id036
  url: /providers/yandex-metrica/
siblings:
- name: AppFolio
  rows: 6
  url: /applications/property-management/appfolio/
- name: Buildium
  rows: 15
  url: /applications/property-management/buildium/
- name: DoorLoop
  rows: 15
  url: /applications/property-management/doorloop/
- name: Guesty
  rows: 12
  url: /applications/property-management/guesty/
- name: Hostaway
  rows: 17
  url: /applications/property-management/hostaway/
sitemap: true
title: 'Open Condo: Property & Rental Management reference app'
---
