---
app: Traccar
app_slug: traccar
app_url: https://github.com/traccar/traccar
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.50.20
  key: AE-120.50.20
  layer: domain
  name: Device Positioning
  providers:
  - Google Maps Platform
  - OpenCelliD
  - Unwired Labs
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: API Evangelist extension
  id: AE-120.10.20
  key: AE-120.10.20
  layer: domain
  name: Reverse Geocoding
  providers:
  - AutoNavi (Amap)
  - Baidu Maps
  - Base Adresse Nationale (BAN)
  - Bing Maps
  - Factual
  - Geoapify
  - Geocode.Farm
  - Geocode.xyz
  - Gisgraphy
  - Google Maps Platform
  - HERE
  - LocationIQ
  - Mapbox
  - MapmyIndia (Mappls)
  - MapQuest
  - MapTiler
  - Nominatim
  - OpenCage
  - positionstack
  - Tencent Location Service
  - TomTom
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-120.30.20
  key: AE-120.30.20
  layer: domain
  name: Road Attributes & Speed Limits
  providers:
  - OpenStreetMap (Overpass API)
  url: /capabilities/routing-navigation/
  via_parent: Routing & Navigation
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase (Crashlytics / Analytics)
  url: /capabilities/product-usage-analytics/
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
  - Amazon SNS
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - Telegram
  - WhatsApp
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: maps-navigation
  name: Maps, Navigation & GPS
  url: /applications/maps-navigation/
counts:
  declared: 0
  observed: 31
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/org.traccar.client/latest/
- route: source code
  url: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
- route: source code
  url: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geolocation
- route: source code
  url: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/notificators
- route: source code
  url: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/sms
- route: source code
  url: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/speedlimit
integrations:
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
    agent_readiness: 29.4
    band: strong
    in_catalog: true
    kin_score: 55.5
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sns
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Email
    - Messaging
    - Notification
    url: /providers/amazon-sns/
  layer: common
  name: Amazon SNS
  provider: amazon-sns
  says: ships the Amazon SNS SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/sms
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id005
      status: unchecked
    slug: autonavi
    status: queued for profiling
    tags: &id006 []
    url: null
  layer: domain
  name: AutoNavi (Amap)
  provider: autonavi
  says: ships the AutoNavi (Amap) SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    agent_readiness: 6.0
    band: emerging
    in_catalog: true
    kin_score: 18.5
    mcp: &id007
      source: https://github.com/baidu-maps/mcp
      status: verified
    slug: baidu
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Company
    - Machine Learning
    - Technology
    url: /providers/baidu/
  layer: domain
  name: Baidu Maps
  provider: baidu
  says: ships the Baidu Maps SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unchecked
    slug: base-adresse-nationale
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: domain
  name: Base Adresse Nationale (BAN)
  provider: base-adresse-nationale
  says: ships the Base Adresse Nationale (BAN) SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    agent_readiness: 5.8
    band: thin
    in_catalog: true
    kin_score: 29.7
    mcp: &id011
      status: none
    slug: bing-maps
    status: profiled
    tags: &id012
    - Geocoding
    - Geospatial
    - Maps
    - Routing
    url: /providers/bing-maps/
  layer: domain
  name: Bing Maps
  provider: bing-maps
  says: ships the Bing Maps SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    kin_score: 5.2
    mcp: &id013
      status: none
    slug: factual
    status: profiled
    tags: &id014
    - Company
    - Geolocation
    - Location
    - Places
    url: /providers/factual/
  layer: domain
  name: Factual
  provider: factual
  says: ships the Factual SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id015
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id016
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase (Crashlytics / Analytics)
  provider: firebase
  says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/org.traccar.client/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: Firebase Cloud Messaging
  provider: firebase
  says: ships the Firebase Cloud Messaging SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/notificators
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
    agent_readiness: 44.3
    band: strong
    in_catalog: true
    kin_score: 60.3
    mcp: &id017
      status: none
    slug: geoapify
    status: profiled
    tags: &id018
    - Geocoding
    - Geospatial
    - Location
    - Maps
    url: /providers/geoapify/
  layer: domain
  name: Geoapify
  provider: geoapify
  says: ships the Geoapify SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    agent_readiness: 28.9
    band: thin
    in_catalog: true
    kin_score: 36.2
    mcp: &id019
      status: unknown
    slug: geocode-farm
    status: profiled
    tags: &id020
    - Data
    - Geocoding
    - Location
    - Services
    url: /providers/geocode-farm/
  layer: domain
  name: Geocode.Farm
  provider: geocode-farm
  says: ships the Geocode.Farm SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    kin_score: 5.6
    mcp: &id021
      status: unknown
    slug: geocode-xyz
    status: profiled
    tags: &id022
    - Geocoding
    - Public APIs
    url: /providers/geocode-xyz/
  layer: domain
  name: Geocode.xyz
  provider: geocode-xyz
  says: ships the Geocode.xyz SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 27.8
    mcp: &id023
      status: none
    slug: gisgraphy
    status: profiled
    tags: &id024
    - Company
    - Geocoding
    - Geolocation
    - Open Source
    url: /providers/gisgraphy/
  layer: domain
  name: Gisgraphy
  provider: gisgraphy
  says: ships the Gisgraphy SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  credit: null
  facts: &id002
    agent_band: agent-ready
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id025
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id026
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: domain
  name: Google Maps Platform
  provider: google-maps
  says: ships the Google Maps Platform SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.20
    key: AE-120.50.20
    name: Device Positioning
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts: *id002
  layer: domain
  name: Google Maps Platform
  provider: google-maps
  says: ships the Google Maps Platform SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geolocation
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
    agent_band: agent-native
    agent_readiness: 55.5
    band: exemplar
    in_catalog: true
    kin_score: 77.6
    mcp: &id027
      status: none
    slug: here
    status: profiled
    tags: &id028
    - Location
    - Mapping
    - Maps
    - Spatial
    url: /providers/here/
  layer: domain
  name: HERE
  provider: here
  says: ships the HERE SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    kin_score: 5.6
    mcp: &id029
      status: none
    slug: locationiq
    status: profiled
    tags: &id030
    - Geocoding
    - Geospatial
    - Public APIs
    url: /providers/locationiq/
  layer: domain
  name: LocationIQ
  provider: locationiq
  says: ships the LocationIQ SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 49.3
    mcp: &id031
      source: https://github.com/mapbox/mcp-server
      status: verified
    slug: mapbox
    status: profiled
    tags: &id032
    - Geospatial
    - Location
    - Mapping
    - Maps
    url: /providers/mapbox/
  layer: domain
  name: Mapbox
  provider: mapbox
  says: ships the Mapbox SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 7.2
    mcp: &id033
      status: none
    slug: mappls
    status: profiled
    tags: &id034
    - Company
    - Location
    - Mapping
    - Navigation
    url: /providers/mappls/
  layer: domain
  name: MapmyIndia (Mappls)
  provider: mappls
  says: ships the MapmyIndia (Mappls) SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    agent_readiness: 15.1
    band: thin
    in_catalog: true
    kin_score: 34.0
    mcp: &id035
      status: none
    slug: mapquest
    status: profiled
    tags: &id036
    - Geocoding
    - Mapping
    - Maps
    - Navigation
    url: /providers/mapquest/
  layer: domain
  name: MapQuest
  provider: mapquest
  says: ships the MapQuest SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    agent_readiness: 26.5
    band: developing
    in_catalog: true
    kin_score: 40.3
    mcp: &id037
      status: none
    slug: maptiler
    status: profiled
    tags: &id038
    - Geospatial
    - Maps
    - Tiles
    - Vector Tiles
    url: /providers/maptiler/
  layer: domain
  name: MapTiler
  provider: maptiler
  says: ships the MapTiler SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    agent_readiness: 19.9
    band: developing
    in_catalog: true
    kin_score: 42.4
    mcp: &id039
      status: none
    slug: nominatim
    status: profiled
    tags: &id040
    - Geocoding
    - Location Services
    - Maps
    - OpenStreetMap
    url: /providers/nominatim/
  layer: domain
  name: Nominatim
  provider: nominatim
  says: ships the Nominatim SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    kin_score: 7.9
    mcp: &id041
      source: https://github.com/OpenCageData/opencage-geocoding-mcp
      status: verified
    slug: opencage
    status: profiled
    tags: &id042
    - Geocoding
    - Geospatial
    - Public APIs
    url: /providers/opencage/
  layer: domain
  name: OpenCage
  provider: opencage
  says: ships the OpenCage SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.20
    key: AE-120.50.20
    name: Device Positioning
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id043
      status: unchecked
    slug: opencellid
    status: queued for profiling
    tags: &id044 []
    url: null
  layer: domain
  name: OpenCelliD
  provider: opencellid
  says: ships the OpenCelliD SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geolocation
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.30.20
    key: AE-120.30.20
    name: Road Attributes & Speed Limits
    url: /capabilities/routing-navigation/
    via_parent: Routing & Navigation
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.8
    band: developing
    in_catalog: true
    kin_score: 44.4
    mcp: &id045
      status: none
    slug: openstreetmap
    status: profiled
    tags: &id046
    - Geocoding
    - Geospatial
    - Mapping
    - Open Data
    url: /providers/openstreetmap/
  layer: domain
  name: OpenStreetMap (Overpass API)
  provider: openstreetmap
  says: ships the OpenStreetMap (Overpass API) SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/speedlimit
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
    agent_readiness: 29.5
    band: strong
    in_catalog: true
    kin_score: 60.4
    mcp: &id047
      status: none
    slug: positionstack
    status: profiled
    tags: &id048
    - Geocoding
    - Location
    - Maps
    - Reverse Geocoding
    url: /providers/positionstack/
  layer: domain
  name: positionstack
  provider: positionstack
  says: ships the positionstack SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    mcp: &id049
      status: none
    slug: pushover
    status: profiled
    tags: &id050
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: common
  name: Pushover
  provider: pushover
  says: ships the Pushover SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/notificators
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
    mcp: &id051
      status: none
    slug: telegram
    status: profiled
    tags: &id052
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/notificators
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id053
      status: unchecked
    slug: tencent-maps
    status: queued for profiling
    tags: &id054 []
    url: null
  layer: domain
  name: Tencent Location Service
  provider: tencent-maps
  says: ships the Tencent Location Service SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
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
    agent_readiness: 36.1
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id055
      source: https://github.com/tomtom-international/tomtom-mcp
      status: verified
    slug: tomtom
    status: profiled
    tags: &id056
    - Maps
    - Navigation
    - Traffic
    - Transportation
    url: /providers/tomtom/
  layer: domain
  name: TomTom
  provider: tomtom
  says: ships the TomTom SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.20
    key: AE-120.50.20
    name: Device Positioning
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.2
    band: developing
    in_catalog: true
    kin_score: 39.6
    mcp: &id057
      status: none
    slug: unwired-labs
    status: profiled
    tags: &id058
    - Company
    - Geolocation
    - Location API
    - Mapping
    url: /providers/unwired-labs/
  layer: domain
  name: Unwired Labs
  provider: unwired-labs
  says: ships the Unwired Labs SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geolocation
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
    agent_band: agent-ready
    agent_readiness: 48.0
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id059
      status: none
    slug: whatsapp
    status: profiled
    tags: &id060
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: common
  name: WhatsApp
  provider: whatsapp
  says: ships the WhatsApp SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/notificators
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/maps-navigation/traccar/
providers:
- agent_band: agent-ready
  agent_readiness: 29.4
  band: strong
  in_catalog: true
  kin_score: 55.5
  mcp: *id003
  name: Amazon SNS
  slug: amazon-sns
  status: profiled
  tags: *id004
  url: /providers/amazon-sns/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id005
  name: AutoNavi (Amap)
  slug: autonavi
  status: queued for profiling
  tags: *id006
  url: null
- agent_band: agent-aware
  agent_readiness: 6.0
  band: emerging
  in_catalog: true
  kin_score: 18.5
  mcp: *id007
  name: Baidu Maps
  slug: baidu
  status: profiled
  tags: *id008
  url: /providers/baidu/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: Base Adresse Nationale (BAN)
  slug: base-adresse-nationale
  status: queued for profiling
  tags: *id010
  url: null
- agent_band: agent-aware
  agent_readiness: 5.8
  band: thin
  in_catalog: true
  kin_score: 29.7
  mcp: *id011
  name: Bing Maps
  slug: bing-maps
  status: profiled
  tags: *id012
  url: /providers/bing-maps/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.2
  mcp: *id013
  name: Factual
  slug: factual
  status: profiled
  tags: *id014
  url: /providers/factual/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id015
  name: Firebase (Crashlytics / Analytics)
  slug: firebase
  status: profiled
  tags: *id016
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: strong
  in_catalog: true
  kin_score: 60.3
  mcp: *id017
  name: Geoapify
  slug: geoapify
  status: profiled
  tags: *id018
  url: /providers/geoapify/
- agent_band: agent-ready
  agent_readiness: 28.9
  band: thin
  in_catalog: true
  kin_score: 36.2
  mcp: *id019
  name: Geocode.Farm
  slug: geocode-farm
  status: profiled
  tags: *id020
  url: /providers/geocode-farm/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id021
  name: Geocode.xyz
  slug: geocode-xyz
  status: profiled
  tags: *id022
  url: /providers/geocode-xyz/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 27.8
  mcp: *id023
  name: Gisgraphy
  slug: gisgraphy
  status: profiled
  tags: *id024
  url: /providers/gisgraphy/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id025
  name: Google Maps Platform
  slug: google-maps
  status: profiled
  tags: *id026
  url: /providers/google-maps/
- agent_band: agent-native
  agent_readiness: 55.5
  band: exemplar
  in_catalog: true
  kin_score: 77.6
  mcp: *id027
  name: HERE
  slug: here
  status: profiled
  tags: *id028
  url: /providers/here/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id029
  name: LocationIQ
  slug: locationiq
  status: profiled
  tags: *id030
  url: /providers/locationiq/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 49.3
  mcp: *id031
  name: Mapbox
  slug: mapbox
  status: profiled
  tags: *id032
  url: /providers/mapbox/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 7.2
  mcp: *id033
  name: MapmyIndia (Mappls)
  slug: mappls
  status: profiled
  tags: *id034
  url: /providers/mappls/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: thin
  in_catalog: true
  kin_score: 34.0
  mcp: *id035
  name: MapQuest
  slug: mapquest
  status: profiled
  tags: *id036
  url: /providers/mapquest/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: developing
  in_catalog: true
  kin_score: 40.3
  mcp: *id037
  name: MapTiler
  slug: maptiler
  status: profiled
  tags: *id038
  url: /providers/maptiler/
- agent_band: agent-aware
  agent_readiness: 19.9
  band: developing
  in_catalog: true
  kin_score: 42.4
  mcp: *id039
  name: Nominatim
  slug: nominatim
  status: profiled
  tags: *id040
  url: /providers/nominatim/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id041
  name: OpenCage
  slug: opencage
  status: profiled
  tags: *id042
  url: /providers/opencage/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id043
  name: OpenCelliD
  slug: opencellid
  status: queued for profiling
  tags: *id044
  url: null
- agent_band: agent-ready
  agent_readiness: 28.8
  band: developing
  in_catalog: true
  kin_score: 44.4
  mcp: *id045
  name: OpenStreetMap (Overpass API)
  slug: openstreetmap
  status: profiled
  tags: *id046
  url: /providers/openstreetmap/
- agent_band: agent-ready
  agent_readiness: 29.5
  band: strong
  in_catalog: true
  kin_score: 60.4
  mcp: *id047
  name: positionstack
  slug: positionstack
  status: profiled
  tags: *id048
  url: /providers/positionstack/
- agent_band: agent-aware
  agent_readiness: 22.0
  band: thin
  in_catalog: true
  kin_score: 29.2
  mcp: *id049
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id050
  url: /providers/pushover/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id051
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id052
  url: /providers/telegram/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id053
  name: Tencent Location Service
  slug: tencent-maps
  status: queued for profiling
  tags: *id054
  url: null
- agent_band: agent-ready
  agent_readiness: 36.1
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id055
  name: TomTom
  slug: tomtom
  status: profiled
  tags: *id056
  url: /providers/tomtom/
- agent_band: agent-aware
  agent_readiness: 22.2
  band: developing
  in_catalog: true
  kin_score: 39.6
  mcp: *id057
  name: Unwired Labs
  slug: unwired-labs
  status: profiled
  tags: *id058
  url: /providers/unwired-labs/
- agent_band: agent-ready
  agent_readiness: 48.0
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id059
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id060
  url: /providers/whatsapp/
siblings:
- name: Dawarich
  rows: 14
  url: /applications/maps-navigation/dawarich/
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
- name: Waze
  rows: 1
  url: /applications/maps-navigation/waze/
sitemap: true
title: 'Traccar: Maps, Navigation & GPS reference app'
---
