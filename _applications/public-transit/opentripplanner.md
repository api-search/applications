---
app: OpenTripPlanner
app_slug: opentripplanner
app_url: https://github.com/opentripplanner/OpenTripPlanner
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-210.30.30
  key: AE-210.30.30
  layer: domain
  name: Parking
  providers:
  - Bikeep
  - Bikely
  - Liipi
  - ParkAPI
  url: /capabilities/ground-transport/
  via_parent: Ground Transport
- attribution: API Evangelist extension
  id: AE-210.30.10
  key: AE-210.30.10
  layer: domain
  name: Ride Hailing
  providers:
  - Uber
  url: /capabilities/ground-transport/
  via_parent: Ground Transport
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Google Cloud Storage
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: common
  name: Integration and API Management
  providers:
  - Azure Service Bus
  - Google Cloud Pub/Sub
  - HiveMQ MQTT client
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
category:
  id: public-transit
  name: Public Transit
  url: /applications/public-transit/
counts:
  declared: 0
  observed: 9
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/opentripplanner/OpenTripPlanner/blob/dev-2.x/application/pom.xml
- route: source code
  url: https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/application/src/ext/java/org/opentripplanner/ext/ridehailing/service
- route: source code
  url: https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/application/src/ext/java/org/opentripplanner/ext/vehicleparking
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 77.2
    mcp: &id001
      source: https://raw.githubusercontent.com/microsoft/mcp/main/servers/Azure.Mcp.Server/README.md
      status: verified
    slug: azure-service-bus
    status: profiled
    tags: &id002
    - Cloud
    - Enterprise
    - Message Broker
    - Microsoft Azure
    url: /providers/azure-service-bus/
  layer: common
  name: Azure Service Bus
  provider: azure-service-bus
  says: ships the Azure Service Bus SDK or integration code
  source: https://github.com/opentripplanner/OpenTripPlanner/blob/dev-2.x/application/pom.xml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.30
    key: AE-210.30.30
    name: Parking
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.4
    band: thin
    in_catalog: true
    kin_score: 35.6
    mcp: &id003
      status: unchecked
    slug: bikeep
    status: profiled
    tags: &id004
    - Company
    - IoT
    - Mobility
    - Smart Parking
    url: /providers/bikeep/
  layer: domain
  name: Bikeep
  provider: bikeep
  says: ships the Bikeep SDK or integration code
  source: https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/application/src/ext/java/org/opentripplanner/ext/vehicleparking
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.30
    key: AE-210.30.30
    name: Parking
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.6
    mcp: &id005
      status: unchecked
    slug: bikely
    status: profiled
    tags: &id006
    - Bike Parking
    - Municipalities
    - Smart Infrastructure
    - Transit Hubs
    url: /providers/bikely/
  layer: domain
  name: Bikely
  provider: bikely
  says: ships the Bikely SDK or integration code
  source: https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/application/src/ext/java/org/opentripplanner/ext/vehicleparking
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
    agent_band: agent-ready
    agent_readiness: 38.0
    band: strong
    in_catalog: true
    kin_score: 64.1
    mcp: &id007
      source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
      status: verified
    slug: google-cloud-pubsub
    status: profiled
    tags: &id008
    - Event-Driven
    - Google Cloud
    - Messaging
    - Pub/Sub
    url: /providers/google-cloud-pubsub/
  layer: common
  name: Google Cloud Pub/Sub
  provider: google-cloud-pubsub
  says: ships the Google Cloud Pub/Sub SDK or integration code
  source: https://github.com/opentripplanner/OpenTripPlanner/blob/dev-2.x/application/pom.xml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id009
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id010
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/opentripplanner/OpenTripPlanner/blob/dev-2.x/application/pom.xml
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
    agent_readiness: 21.3
    band: strong
    in_catalog: true
    kin_score: 58.3
    mcp: &id011
      status: none
    slug: hivemq
    status: profiled
    tags: &id012
    - IoT
    - MQTT
    - Message Broker
    - Messaging
    url: /providers/hivemq/
  layer: common
  name: HiveMQ MQTT client
  provider: hivemq
  says: ships the HiveMQ MQTT client SDK or integration code
  source: https://github.com/opentripplanner/OpenTripPlanner/blob/dev-2.x/application/pom.xml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.30
    key: AE-210.30.30
    name: Parking
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id013
      status: unchecked
    slug: liipi
    status: queued for profiling
    tags: &id014 []
    url: null
  layer: domain
  name: Liipi
  provider: liipi
  says: ships the Liipi SDK or integration code
  source: https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/application/src/ext/java/org/opentripplanner/ext/vehicleparking
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.30
    key: AE-210.30.30
    name: Parking
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 4.5
    mcp: &id015
      status: unchecked
    slug: parkapi
    status: profiled
    tags: &id016
    - Europe
    - Mobile
    - Parking
    - Real-Time
    url: /providers/parkapi/
  layer: domain
  name: ParkAPI
  provider: parkapi
  says: ships the ParkAPI SDK or integration code
  source: https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/application/src/ext/java/org/opentripplanner/ext/vehicleparking
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.10
    key: AE-210.30.10
    name: Ride Hailing
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: developing
    in_catalog: true
    kin_score: 49.0
    mcp: &id017
      status: none
    slug: uber
    status: profiled
    tags: &id018
    - Food Delivery
    - Ride Hailing
    - Taxis
    - Transportation
    url: /providers/uber/
  layer: domain
  name: Uber
  provider: uber
  says: ships the Uber SDK or integration code
  source: https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/application/src/ext/java/org/opentripplanner/ext/ridehailing/service
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/public-transit/opentripplanner/
providers:
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 77.2
  mcp: *id001
  name: Azure Service Bus
  slug: azure-service-bus
  status: profiled
  tags: *id002
  url: /providers/azure-service-bus/
- agent_band: agent-ready
  agent_readiness: 42.4
  band: thin
  in_catalog: true
  kin_score: 35.6
  mcp: *id003
  name: Bikeep
  slug: bikeep
  status: profiled
  tags: *id004
  url: /providers/bikeep/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.6
  mcp: *id005
  name: Bikely
  slug: bikely
  status: profiled
  tags: *id006
  url: /providers/bikely/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: strong
  in_catalog: true
  kin_score: 64.1
  mcp: *id007
  name: Google Cloud Pub/Sub
  slug: google-cloud-pubsub
  status: profiled
  tags: *id008
  url: /providers/google-cloud-pubsub/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id009
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id010
  url: /providers/gcp-cloud-storage/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: strong
  in_catalog: true
  kin_score: 58.3
  mcp: *id011
  name: HiveMQ MQTT client
  slug: hivemq
  status: profiled
  tags: *id012
  url: /providers/hivemq/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id013
  name: Liipi
  slug: liipi
  status: queued for profiling
  tags: *id014
  url: null
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 4.5
  mcp: *id015
  name: ParkAPI
  slug: parkapi
  status: profiled
  tags: *id016
  url: /providers/parkapi/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: developing
  in_catalog: true
  kin_score: 49.0
  mcp: *id017
  name: Uber
  slug: uber
  status: profiled
  tags: *id018
  url: /providers/uber/
siblings:
- name: Citymapper
  rows: 23
  url: /applications/public-transit/citymapper/
- name: Moovit
  rows: 17
  url: /applications/public-transit/moovit/
- name: MOTIS (Transitous)
  rows: 7
  url: /applications/public-transit/motis-transitous/
- name: OneBusAway Android
  rows: 8
  url: /applications/public-transit/onebusaway-android/
- name: Transit
  rows: 9
  url: /applications/public-transit/transit/
sitemap: true
title: 'OpenTripPlanner: Public Transit reference app'
---
