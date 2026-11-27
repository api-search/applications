---
app: Fleetbase
app_slug: fleetbase
app_url: https://github.com/fleetbase/fleetbase
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-940
  key: AE-940
  layer: domain
  name: Fleet Fuel Cards & Fuel Transaction Data
  providers:
  - PetroApp
  - SASCO
  url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
  via_parent: null
- attribution: Turbo EA
  id: BC-2430.40
  key: fleet-telematics-and-monitoring
  layer: domain
  name: Fleet Telematics and Monitoring
  providers:
  - AFAQY
  - flespi (Gurtam)
  - Geotab
  - Safee
  - Samsara
  url: /capabilities/fleet-telematics-and-monitoring/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: domain
  name: Forward Geocoding
  providers:
  - Google Maps Places
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: Turbo EA
  id: BC-2400
  key: freight-capacity-management
  layer: domain
  name: Freight Capacity Management
  providers:
  - Lalamove
  url: /capabilities/freight-capacity-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
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
  key: push-notifications
  layer: common
  name: Push Notifications
  providers:
  - Apple Push Notification service
  - Firebase Cloud Messaging
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20
  key: sms-messaging-apps
  layer: common
  name: SMS & Messaging Apps
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Microsoft Graph (mail)
  url: /capabilities/email/
  via_parent: Email
category:
  id: fleet-telematics
  name: Fleet Management & Telematics
  url: /applications/fleet-telematics/
counts:
  declared: 0
  observed: 15
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/fleetbase/core-api/blob/main/composer.json
- route: dependency manifest
  url: https://github.com/fleetbase/fleetops/blob/main/composer.json
- route: source code
  url: https://github.com/fleetbase/fleetops/tree/main/server/src/Integrations/Lalamove
- route: source code
  url: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/FuelProviders/Providers
- route: source code
  url: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2430.40
    key: fleet-telematics-and-monitoring
    name: Fleet Telematics and Monitoring
    url: /capabilities/fleet-telematics-and-monitoring/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.5
    mcp: &id001
      status: unchecked
    slug: afaqy
    status: profiled
    tags: &id002
    - AVL
    - Fleet Management
    - IoT
    - Smart Parking
    url: /providers/afaqy/
  layer: domain
  name: AFAQY
  provider: afaqy
  says: ships the AFAQY SDK or integration code
  source: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: push-notifications
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
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
  name: Apple Push Notification service
  provider: apple
  says: ships the Apple Push Notification service SDK or integration code
  source: https://github.com/fleetbase/core-api/blob/main/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: push-notifications
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id005
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id006
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase Cloud Messaging
  provider: firebase
  says: ships the Firebase Cloud Messaging SDK or integration code
  source: https://github.com/fleetbase/core-api/blob/main/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2430.40
    key: fleet-telematics-and-monitoring
    name: Fleet Telematics and Monitoring
    url: /capabilities/fleet-telematics-and-monitoring/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.0
    band: developing
    in_catalog: true
    kin_score: 43.5
    mcp: &id007
      status: unchecked
    slug: flespi
    status: profiled
    tags: &id008
    - Data Ingestion
    - IoT
    - Real-Time Analytics
    - Telematics
    url: /providers/flespi/
  layer: domain
  name: flespi (Gurtam)
  provider: flespi
  says: ships the flespi (Gurtam) SDK or integration code
  source: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2430.40
    key: fleet-telematics-and-monitoring
    name: Fleet Telematics and Monitoring
    url: /capabilities/fleet-telematics-and-monitoring/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.4
    band: thin
    in_catalog: true
    kin_score: 36.9
    mcp: &id009
      source: https://mcp.geotab.com/mygeotab
      status: verified
    slug: geotab
    status: profiled
    tags: &id010
    - ELD Compliance
    - Fleet Management
    - Telematics
    - Vehicle Tracking
    url: /providers/geotab/
  layer: domain
  name: Geotab
  provider: geotab
  says: ships the Geotab SDK or integration code
  source: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id011
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id012
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/fleetbase/core-api/blob/main/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.0
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id013
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id014
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: domain
  name: Google Maps Places
  provider: google-maps
  says: ships the Google Maps Places SDK or integration code
  source: https://github.com/fleetbase/fleetops/blob/main/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2400
    key: freight-capacity-management
    name: Freight Capacity Management
    url: /capabilities/freight-capacity-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.1
    band: developing
    in_catalog: true
    kin_score: 44.0
    mcp: &id015
      status: none
    slug: lalamove
    status: profiled
    tags: &id016
    - Company
    - Delivery
    - Logistics
    - Technology
    url: /providers/lalamove/
  layer: domain
  name: Lalamove
  provider: lalamove
  says: ships the Lalamove SDK or integration code
  source: https://github.com/fleetbase/fleetops/tree/main/server/src/Integrations/Lalamove
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.0
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id017
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-graph
    status: profiled
    tags: &id018
    - Azure AD
    - Collaboration
    - Contacts
    - Microsoft Graph
    url: /providers/microsoft-graph/
  layer: common
  name: Microsoft Graph (mail)
  provider: microsoft-graph
  says: ships the Microsoft Graph (mail) SDK or integration code
  source: https://github.com/fleetbase/core-api/blob/main/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 19.9
    mcp: &id019
      status: unchecked
    slug: petroapp
    status: profiled
    tags: &id020
    - Company
    - Fleet Management
    - Fuel Expenses
    - Software-as-a-Service
    url: /providers/petroapp/
  layer: domain
  name: PetroApp
  provider: petroapp
  says: ships the PetroApp SDK or integration code
  source: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/FuelProviders/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2430.40
    key: fleet-telematics-and-monitoring
    name: Fleet Telematics and Monitoring
    url: /capabilities/fleet-telematics-and-monitoring/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.4
    band: minimal
    in_catalog: true
    kin_score: 8.3
    mcp: &id021
      status: unchecked
    slug: safee
    status: profiled
    tags: &id022
    - Fleet Management
    - GPS Tracking
    - Telematics
    - Vehicle-Analytics
    url: /providers/safee/
  layer: domain
  name: Safee
  provider: safee
  says: ships the Safee SDK or integration code
  source: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-2430.40
    key: fleet-telematics-and-monitoring
    name: Fleet Telematics and Monitoring
    url: /capabilities/fleet-telematics-and-monitoring/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.9
    band: thin
    in_catalog: true
    kin_score: 32.0
    mcp: &id023
      source: https://mcp.samsara.com/mcp
      status: documented
    slug: samsara
    status: profiled
    tags: &id024
    - Asset Tracking
    - Connected Operations
    - ELD
    - Fleet Management
    url: /providers/samsara/
  layer: domain
  name: Samsara
  provider: samsara
  says: ships the Samsara SDK or integration code
  source: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.1
    band: emerging
    in_catalog: true
    kin_score: 18.8
    mcp: &id025
      status: unchecked
    slug: sasco
    status: profiled
    tags: &id026
    - Automotive
    - Public Company
    - Saudi Arabia
    - Services
    url: /providers/sasco/
  layer: domain
  name: SASCO
  provider: sasco
  says: ships the SASCO SDK or integration code
  source: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/FuelProviders/Providers
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
  source: https://github.com/fleetbase/core-api/blob/main/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20
    key: sms-messaging-apps
    name: SMS & Messaging Apps
    url: /capabilities/sms-messaging-apps/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id029
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id030
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://github.com/fleetbase/core-api/blob/main/composer.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/fleet-telematics/fleetbase/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.5
  mcp: *id001
  name: AFAQY
  slug: afaqy
  status: profiled
  tags: *id002
  url: /providers/afaqy/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id003
  name: Apple Push Notification service
  slug: apple
  status: profiled
  tags: *id004
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id005
  name: Firebase Cloud Messaging
  slug: google-firebase
  status: profiled
  tags: *id006
  url: /providers/google-firebase/
- agent_band: agent-aware
  agent_readiness: 23.0
  band: developing
  in_catalog: true
  kin_score: 43.5
  mcp: *id007
  name: flespi (Gurtam)
  slug: flespi
  status: profiled
  tags: *id008
  url: /providers/flespi/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: thin
  in_catalog: true
  kin_score: 36.9
  mcp: *id009
  name: Geotab
  slug: geotab
  status: profiled
  tags: *id010
  url: /providers/geotab/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id011
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id012
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id013
  name: Google Maps Places
  slug: google-maps
  status: profiled
  tags: *id014
  url: /providers/google-maps/
- agent_band: agent-aware
  agent_readiness: 23.1
  band: developing
  in_catalog: true
  kin_score: 44.0
  mcp: *id015
  name: Lalamove
  slug: lalamove
  status: profiled
  tags: *id016
  url: /providers/lalamove/
- agent_band: agent-ready
  agent_readiness: 39.0
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id017
  name: Microsoft Graph (mail)
  slug: microsoft-graph
  status: profiled
  tags: *id018
  url: /providers/microsoft-graph/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 19.9
  mcp: *id019
  name: PetroApp
  slug: petroapp
  status: profiled
  tags: *id020
  url: /providers/petroapp/
- agent_band: agent-aware
  agent_readiness: 21.4
  band: minimal
  in_catalog: true
  kin_score: 8.3
  mcp: *id021
  name: Safee
  slug: safee
  status: profiled
  tags: *id022
  url: /providers/safee/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: thin
  in_catalog: true
  kin_score: 32.0
  mcp: *id023
  name: Samsara
  slug: samsara
  status: profiled
  tags: *id024
  url: /providers/samsara/
- agent_band: agent-aware
  agent_readiness: 17.1
  band: emerging
  in_catalog: true
  kin_score: 18.8
  mcp: *id025
  name: SASCO
  slug: sasco
  status: profiled
  tags: *id026
  url: /providers/sasco/
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
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id029
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id030
  url: /providers/twilio/
siblings:
- name: Fleetio
  rows: 11
  url: /applications/fleet-telematics/fleetio/
- name: Geotab
  rows: 5
  url: /applications/fleet-telematics/geotab/
- name: Motive
  rows: 14
  url: /applications/fleet-telematics/motive/
- name: Samsara
  rows: 12
  url: /applications/fleet-telematics/samsara/
- name: Traccar
  rows: 36
  url: /applications/fleet-telematics/traccar/
sitemap: true
title: 'Fleetbase: Fleet Management & Telematics reference app'
---
