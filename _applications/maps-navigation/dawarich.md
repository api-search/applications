---
app: Dawarich
app_slug: dawarich
app_url: https://github.com/Freika/dawarich
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.50.20
  key: AE-120.50.20
  layer: domain
  name: Device Positioning
  providers:
  - Overland
  - OwnTracks
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: API Evangelist extension
  id: AE-120.50.30
  key: AE-120.50.30
  layer: domain
  name: Location History & Timeline
  providers:
  - Google Maps Timeline / Takeout
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: domain
  name: Photo & Image Libraries
  providers:
  - Immich
  - PhotoPrism
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10.20
  key: AE-120.10.20
  layer: domain
  name: Reverse Geocoding
  providers:
  - Geoapify
  - LocationIQ
  - Nominatim
  - Photon (komoot)
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-130.10.30
  key: AE-130.10.30
  layer: domain
  name: Running & Cycling Tracking
  providers:
  - Strava
  url: /capabilities/activity-fitness-tracking/
  via_parent: Activity & Fitness Tracking
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
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - GitHub
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: maps-navigation
  name: Maps, Navigation & GPS
  url: /applications/maps-navigation/
counts:
  declared: 6
  observed: 8
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/app.dawarich.Dawarich/latest/
- route: dependency manifest
  url: https://github.com/Freika/dawarich/blob/master/Gemfile
- route: documentation
  url: https://github.com/Freika/dawarich/blob/master/README.md
- route: source code
  url: https://github.com/Freika/dawarich/blob/master/config/initializers/geocoder.rb
integrations:
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
  source: https://github.com/Freika/dawarich/blob/master/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 62.6
    mcp: &id003
      status: none
    slug: geoapify
    status: profiled
    tags: &id004
    - Geocoding
    - Geospatial
    - Location
    - Maps
    url: /providers/geoapify/
  layer: domain
  name: Geoapify
  provider: geoapify
  says: ships the Geoapify SDK or integration code
  source: https://github.com/Freika/dawarich/blob/master/config/initializers/geocoder.rb
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
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id005
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id006
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/Freika/dawarich/blob/master/Gemfile
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
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id009
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id010
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/Freika/dawarich/blob/master/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.8
    mcp: &id013
      status: none
    slug: locationiq
    status: profiled
    tags: &id014
    - Geocoding
    - Geospatial
    - Public APIs
    url: /providers/locationiq/
  layer: domain
  name: LocationIQ
  provider: locationiq
  says: ships the LocationIQ SDK or integration code
  source: https://github.com/Freika/dawarich/blob/master/config/initializers/geocoder.rb
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.7
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id015
      status: none
    slug: nominatim
    status: profiled
    tags: &id016
    - Geocoding
    - Location Services
    - Maps
    - OpenStreetMap
    url: /providers/nominatim/
  layer: domain
  name: Nominatim
  provider: nominatim
  says: ships the Nominatim SDK or integration code
  source: https://github.com/Freika/dawarich/blob/master/config/initializers/geocoder.rb
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 11.3
    mcp: &id021
      status: none
    slug: komoot-photon
    status: profiled
    tags: &id022
    - Geocoding
    - OpenStreetMap
    - Search
    - Typeahead
    url: /providers/komoot-photon/
  layer: domain
  name: Photon (komoot)
  provider: komoot-photon
  says: ships the Photon (komoot) SDK or integration code
  source: https://github.com/Freika/dawarich/blob/master/config/initializers/geocoder.rb
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
    mcp: &id025
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id026
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/Freika/dawarich/blob/master/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.30
    key: AE-120.50.30
    name: Location History & Timeline
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id007
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id008
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Google Maps Timeline / Takeout
  provider: google
  says: lists Google Maps Timeline / Takeout as an integration
  source: https://github.com/Freika/dawarich/blob/master/README.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 25.5
    mcp: &id011
      status: none
    slug: immich
    status: profiled
    tags: &id012
    - Photo Management
    - Privacy
    - Self-Hosted
    - Video Management
    url: /providers/immich/
  layer: domain
  name: Immich
  provider: immich
  says: lists Immich as an integration
  source: https://github.com/Freika/dawarich/blob/master/README.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.20
    key: AE-120.50.20
    name: Device Positioning
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.2
    band: emerging
    in_catalog: true
    kin_score: 11.5
    mcp: &id017
      status: unknown
    slug: overland
    status: profiled
    tags: &id018
    - GPS
    - Location Tracking
    - Open Source
    - iOS
    url: /providers/overland/
  layer: domain
  name: Overland
  provider: overland
  says: lists Overland as an integration
  source: https://github.com/Freika/dawarich/blob/master/README.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.20
    key: AE-120.50.20
    name: Device Positioning
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.7
    mcp: &id019
      status: none
    slug: owntracks
    status: profiled
    tags: &id020
    - Company
    - Location Tracking
    - Open Source
    - Privacy
    url: /providers/owntracks/
  layer: domain
  name: OwnTracks
  provider: owntracks
  says: lists OwnTracks as an integration
  source: https://github.com/Freika/dawarich/blob/master/README.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.3
    band: developing
    in_catalog: true
    kin_score: 52.5
    mcp: &id023
      source: https://docs.photoprism.app/developer-guide/api/mcp/
      status: verified
    slug: photoprism
    status: profiled
    tags: &id024
    - Artificial Intelligence
    - Company
    - Photo Management
    - Self-Hosted
    url: /providers/photoprism/
  layer: domain
  name: PhotoPrism
  provider: photoprism
  says: lists PhotoPrism as an integration
  source: https://github.com/Freika/dawarich/blob/master/README.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.30
    key: AE-130.10.30
    name: Running & Cycling Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.3
    band: developing
    in_catalog: true
    kin_score: 52.0
    mcp: &id027
      status: none
    slug: strava
    status: profiled
    tags: &id028
    - Cycling
    - Fitness
    - Fitness Tracking
    - Running
    url: /providers/strava/
  layer: domain
  name: Strava
  provider: strava
  says: lists Strava as an integration
  source: https://github.com/Freika/dawarich/blob/master/README.md
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/maps-navigation/dawarich/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id003
  name: Geoapify
  slug: geoapify
  status: profiled
  tags: *id004
  url: /providers/geoapify/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id005
  name: GitHub
  slug: github
  status: profiled
  tags: *id006
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id007
  name: Google Maps Timeline / Takeout
  slug: google
  status: profiled
  tags: *id008
  url: /providers/google/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id009
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id010
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 25.5
  mcp: *id011
  name: Immich
  slug: immich
  status: profiled
  tags: *id012
  url: /providers/immich/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.8
  mcp: *id013
  name: LocationIQ
  slug: locationiq
  status: profiled
  tags: *id014
  url: /providers/locationiq/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id015
  name: Nominatim
  slug: nominatim
  status: profiled
  tags: *id016
  url: /providers/nominatim/
- agent_band: human-only
  agent_readiness: 3.2
  band: emerging
  in_catalog: true
  kin_score: 11.5
  mcp: *id017
  name: Overland
  slug: overland
  status: profiled
  tags: *id018
  url: /providers/overland/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.7
  mcp: *id019
  name: OwnTracks
  slug: owntracks
  status: profiled
  tags: *id020
  url: /providers/owntracks/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 11.3
  mcp: *id021
  name: Photon (komoot)
  slug: komoot-photon
  status: profiled
  tags: *id022
  url: /providers/komoot-photon/
- agent_band: agent-ready
  agent_readiness: 37.3
  band: developing
  in_catalog: true
  kin_score: 52.5
  mcp: *id023
  name: PhotoPrism
  slug: photoprism
  status: profiled
  tags: *id024
  url: /providers/photoprism/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id025
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id026
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 51.3
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id027
  name: Strava
  slug: strava
  status: profiled
  tags: *id028
  url: /providers/strava/
siblings:
- name: Google Maps
  rows: 1
  url: /applications/maps-navigation/google-maps/
- name: Headway
  rows: 4
  url: /applications/maps-navigation/headway/
- name: komoot
  rows: 5
  url: /applications/maps-navigation/komoot/
- name: Organic Maps
  rows: 5
  url: /applications/maps-navigation/organic-maps/
- name: OsmAnd
  rows: 4
  url: /applications/maps-navigation/osmand/
- name: Traccar
  rows: 31
  url: /applications/maps-navigation/traccar/
- name: Waze
  rows: 1
  url: /applications/maps-navigation/waze/
sitemap: true
title: 'Dawarich: Maps, Navigation & GPS reference app'
---
