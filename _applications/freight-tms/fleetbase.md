---
app: Fleetbase
app_slug: fleetbase
app_url: https://github.com/fleetbase/fleetbase
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-2430.40
  key: fleet-telematics-and-monitoring
  layer: domain
  name: Fleet Telematics and Monitoring
  providers:
  - Afaqy
  - flespi
  - Geotab
  - Safee
  - Samsara
  url: /capabilities/fleet-telematics-and-monitoring/
  via_parent: null
- attribution: Turbo EA
  id: BC-2400
  key: freight-capacity-management
  layer: domain
  name: Freight Capacity Management
  providers:
  - Lalamove
  url: /capabilities/freight-capacity-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1050.20.20
  key: BC-1050.20.20
  layer: domain
  name: Route Optimisation
  providers:
  - VROOM (Vehicle Routing Open-source Optimization Machine)
  url: /capabilities/service-dispatch-management/
  via_parent: Service Dispatch Management
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: common
  name: Forward Geocoding
  providers:
  - Google Maps Platform
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.70
  key: AE-150.70
  layer: common
  name: Realtime Messaging
  providers:
  - Pusher
  url: /capabilities/realtime-messaging/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Mailgun
  - Postmark
  - Resend
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-120.30.10
  key: AE-120.30.10
  layer: common
  name: Turn-by-Turn Directions
  providers:
  - Valhalla
  url: /capabilities/routing-navigation/
  via_parent: Routing & Navigation
category:
  id: freight-tms
  name: Freight & Transportation Management
  url: /applications/freight-tms/
counts:
  declared: 0
  observed: 16
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
- route: dependency manifest
  url: https://raw.githubusercontent.com/fleetbase/fleetops/main/composer.json
- route: source code
  url: https://github.com/fleetbase/fleetops/tree/main/server/src/Integrations
- route: source code
  url: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
- route: source code
  url: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/.env.example
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
  name: Afaqy
  provider: afaqy
  says: ships the Afaqy SDK or integration code
  source: https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
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
    mcp: &id005
      status: unchecked
    slug: flespi
    status: profiled
    tags: &id006
    - Data Ingestion
    - IoT
    - Real-Time Analytics
    - Telematics
    url: /providers/flespi/
  layer: domain
  name: flespi
  provider: flespi
  says: ships the flespi SDK or integration code
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
    mcp: &id007
      source: https://mcp.geotab.com/mygeotab
      status: verified
    slug: geotab
    status: profiled
    tags: &id008
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
    mcp: &id009
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id010
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: common
  name: Google Maps Platform
  provider: google-maps
  says: ships the Google Maps Platform SDK or integration code
  source: https://raw.githubusercontent.com/fleetbase/fleetops/main/composer.json
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
    mcp: &id011
      status: none
    slug: lalamove
    status: profiled
    tags: &id012
    - Company
    - Delivery
    - Logistics
    - Technology
    url: /providers/lalamove/
  layer: domain
  name: Lalamove
  provider: lalamove
  says: ships the Lalamove SDK or integration code
  source: https://github.com/fleetbase/fleetops/tree/main/server/src/Integrations
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
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id013
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id014
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
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
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id015
      source: https://github.com/ActiveCampaign/postmark-mcp
      status: verified
    slug: postmark
    status: profiled
    tags: &id016
    - Deliverability
    - Email
    - Messaging
    - Transactional Email
    url: /providers/postmark/
  layer: common
  name: Postmark
  provider: postmark
  says: ships the Postmark SDK or integration code
  source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.8
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id017
      status: none
    slug: pusher
    status: profiled
    tags: &id018
    - Pub/Sub
    - Push Notifications
    - Real-Time
    - WebSocket
    url: /providers/pusher/
  layer: common
  name: Pusher
  provider: pusher
  says: ships the Pusher SDK or integration code
  source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/.env.example
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
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id019
      source: https://resend.com/docs/mcp-server
      status: verified
    slug: resend
    status: profiled
    tags: &id020
    - Developer Tools
    - Email
    - Marketing Email
    - Transactional Email
    url: /providers/resend/
  layer: common
  name: Resend
  provider: resend
  says: ships the Resend SDK or integration code
  source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
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
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.7
    band: exemplar
    in_catalog: true
    kin_score: 84.0
    mcp: &id025
      status: none
    slug: sendgrid
    status: profiled
    tags: &id026
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id027
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id028
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.30.10
    key: AE-120.30.10
    name: Turn-by-Turn Directions
    url: /capabilities/routing-navigation/
    via_parent: Routing & Navigation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.0
    band: emerging
    in_catalog: true
    kin_score: 24.4
    mcp: &id029
      status: none
    slug: valhalla
    status: profiled
    tags: &id030
    - Mapping
    - Navigation
    - OpenStreetMap
    - Routing
    url: /providers/valhalla/
  layer: common
  name: Valhalla
  provider: valhalla
  says: ships the Valhalla SDK or integration code
  source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1050.20.20
    key: BC-1050.20.20
    name: Route Optimisation
    url: /capabilities/service-dispatch-management/
    via_parent: Service Dispatch Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.1
    mcp: &id031
      status: unchecked
    slug: vroom-project
    status: profiled
    tags: &id032
    - Company
    - Open Source
    - Optimization
    - Routing
    url: /providers/vroom-project/
  layer: domain
  name: VROOM (Vehicle Routing Open-source Optimization Machine)
  provider: vroom-project
  says: ships the VROOM (Vehicle Routing Open-source Optimization Machine) SDK or integration code
  source: https://raw.githubusercontent.com/fleetbase/fleetbase/main/api/composer.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/freight-tms/fleetbase/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.5
  mcp: *id001
  name: Afaqy
  slug: afaqy
  status: profiled
  tags: *id002
  url: /providers/afaqy/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id003
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: agent-aware
  agent_readiness: 23.0
  band: developing
  in_catalog: true
  kin_score: 43.5
  mcp: *id005
  name: flespi
  slug: flespi
  status: profiled
  tags: *id006
  url: /providers/flespi/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: thin
  in_catalog: true
  kin_score: 36.9
  mcp: *id007
  name: Geotab
  slug: geotab
  status: profiled
  tags: *id008
  url: /providers/geotab/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id009
  name: Google Maps Platform
  slug: google-maps
  status: profiled
  tags: *id010
  url: /providers/google-maps/
- agent_band: agent-aware
  agent_readiness: 23.1
  band: developing
  in_catalog: true
  kin_score: 44.0
  mcp: *id011
  name: Lalamove
  slug: lalamove
  status: profiled
  tags: *id012
  url: /providers/lalamove/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id013
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id014
  url: /providers/mailgun/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id015
  name: Postmark
  slug: postmark
  status: profiled
  tags: *id016
  url: /providers/postmark/
- agent_band: agent-aware
  agent_readiness: 25.8
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id017
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id018
  url: /providers/pusher/
- agent_band: agent-ready
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id019
  name: Resend
  slug: resend
  status: profiled
  tags: *id020
  url: /providers/resend/
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
- agent_band: agent-ready
  agent_readiness: 40.7
  band: exemplar
  in_catalog: true
  kin_score: 84.0
  mcp: *id025
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id026
  url: /providers/sendgrid/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id027
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id028
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 29.0
  band: emerging
  in_catalog: true
  kin_score: 24.4
  mcp: *id029
  name: Valhalla
  slug: valhalla
  status: profiled
  tags: *id030
  url: /providers/valhalla/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.1
  mcp: *id031
  name: VROOM (Vehicle Routing Open-source Optimization Machine)
  slug: vroom-project
  status: profiled
  tags: *id032
  url: /providers/vroom-project/
siblings:
- name: 3G TMS
  rows: 4
  url: /applications/freight-tms/3g-tms/
- name: Descartes Aljex
  rows: 19
  url: /applications/freight-tms/descartes-aljex/
- name: Revenova TMS
  rows: 5
  url: /applications/freight-tms/revenova-tms/
- name: Rose Rocket
  rows: 28
  url: /applications/freight-tms/rose-rocket/
sitemap: true
title: 'Fleetbase: Freight & Transportation Management reference app'
---
