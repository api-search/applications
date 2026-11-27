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
  - Google Maps
  - Unwired Labs (incl. OpenCelliD)
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: Turbo EA
  id: BC-2430.40
  key: fleet-telematics-and-monitoring
  layer: domain
  name: Fleet Telematics and Monitoring
  providers:
  - Wialon (Gurtam)
  url: /capabilities/fleet-telematics-and-monitoring/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.10.20
  key: AE-120.10.20
  layer: domain
  name: Reverse Geocoding
  providers:
  - AutoNavi (Amap)
  - Baidu Maps
  - Base Adresse Nationale (adresse.data.gouv.fr)
  - Bing Maps
  - Factual
  - Geoapify
  - Geocode.Farm
  - Geocode.xyz
  - Gisgraphy
  - Google Maps
  - HERE
  - LocationIQ
  - Mapbox
  - MapmyIndia (Mappls)
  - MapQuest
  - MapTiler
  - MyGeocode
  - Nominatim
  - OpenCage
  - positionstack
  - Tencent Maps
  - TomTom
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: API Evangelist extension
  id: AE-120.30.20
  key: AE-120.30.20
  layer: domain
  name: Road Attributes & Speed Limits
  providers:
  - Overpass API
  url: /capabilities/routing-navigation/
  via_parent: Routing & Navigation
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: common
  name: Integration and API Management
  providers:
  - Apache Kafka
  - MQTT
  - RabbitMQ (AMQP)
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase Analytics / Crashlytics
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: push-notifications
  layer: common
  name: Push Notifications
  providers:
  - Firebase Cloud Messaging
  - Pushover
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20
  key: sms-messaging-apps
  layer: common
  name: SMS & Messaging Apps
  providers:
  - Amazon SNS
  url: /capabilities/sms-messaging-apps/
  via_parent: null
- attribution: Turbo EA
  id: BC-4270.80
  key: webhook-event-subscription-management
  layer: common
  name: Webhook & Event Subscription Management
  providers:
  - Redis
  url: /capabilities/webhook-event-subscription-management/
  via_parent: null
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
  id: fleet-telematics
  name: Fleet Management & Telematics
  url: /applications/fleet-telematics/
counts:
  declared: 0
  observed: 36
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/org.traccar.client/latest/
- route: source code
  url: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/forward
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
    id: AE-150.20
    key: sms-messaging-apps
    name: SMS & Messaging Apps
    url: /capabilities/sms-messaging-apps/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.7
    band: strong
    in_catalog: true
    kin_score: 64.4
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
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.8
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id005
      status: none
    slug: apache-kafka
    status: profiled
    tags: &id006
    - Apache Kafka
    - Distributed Systems
    - Event Streaming
    - Messaging
    url: /providers/apache-kafka/
  layer: common
  name: Apache Kafka
  provider: apache-kafka
  says: ships the Apache Kafka SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/forward
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
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 19.0
    mcp: &id007
      status: unchecked
    slug: autonavi
    status: profiled
    tags: &id008
    - China
    - Company
    - Location Services
    - Mapping
    url: /providers/autonavi/
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
    agent_readiness: 5.8
    band: emerging
    in_catalog: true
    kin_score: 17.4
    mcp: &id009
      source: https://github.com/baidu-maps/mcp
      status: verified
    slug: baidu
    status: profiled
    tags: &id010
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.8
    mcp: &id011
      status: none
    slug: adresse-data-gouv-fr
    status: profiled
    tags: &id012
    - Geocoding
    - Public APIs
    url: /providers/adresse-data-gouv-fr/
  layer: domain
  name: Base Adresse Nationale (adresse.data.gouv.fr)
  provider: adresse-data-gouv-fr
  says: ships the Base Adresse Nationale (adresse.data.gouv.fr) SDK or integration code
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
    agent_readiness: 3.5
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id013
      status: none
    slug: bing-maps
    status: profiled
    tags: &id014
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
    kin_score: 4.6
    mcp: &id015
      status: none
    slug: factual
    status: profiled
    tags: &id016
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
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id017
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id018
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase Analytics / Crashlytics
  provider: firebase
  says: ships the Firebase Analytics / Crashlytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/org.traccar.client/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: push-notifications
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
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 62.6
    mcp: &id019
      status: none
    slug: geoapify
    status: profiled
    tags: &id020
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
    agent_band: agent-aware
    agent_readiness: 26.1
    band: developing
    in_catalog: true
    kin_score: 45.3
    mcp: &id021
      status: unknown
    slug: geocode-farm
    status: profiled
    tags: &id022
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
    kin_score: 4.8
    mcp: &id023
      status: unknown
    slug: geocode-xyz
    status: profiled
    tags: &id024
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
    agent_readiness: 15.1
    band: thin
    in_catalog: true
    kin_score: 32.5
    mcp: &id025
      status: none
    slug: gisgraphy
    status: profiled
    tags: &id026
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
    agent_readiness: 33.0
    band: exemplar
    in_catalog: true
    kin_score: 73.6
    mcp: &id027
      source: https://developers.google.com/maps/ai/grounding-lite
      status: verified
    slug: google-maps
    status: profiled
    tags: &id028
    - Environment
    - Geocoding
    - Geolocation
    - Maps
    url: /providers/google-maps/
  layer: domain
  name: Google Maps
  provider: google-maps
  says: ships the Google Maps SDK or integration code
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
  name: Google Maps
  provider: google-maps
  says: ships the Google Maps SDK or integration code
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
    agent_readiness: 54.4
    band: exemplar
    in_catalog: true
    kin_score: 79.0
    mcp: &id029
      status: none
    slug: here
    status: profiled
    tags: &id030
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
    kin_score: 4.8
    mcp: &id031
      status: none
    slug: locationiq
    status: profiled
    tags: &id032
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
    agent_readiness: 45.2
    band: developing
    in_catalog: true
    kin_score: 50.7
    mcp: &id033
      source: https://github.com/mapbox/mcp-server
      status: verified
    slug: mapbox
    status: profiled
    tags: &id034
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
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.7
    mcp: &id035
      status: none
    slug: mappls
    status: profiled
    tags: &id036
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
    agent_readiness: 14.7
    band: thin
    in_catalog: true
    kin_score: 35.2
    mcp: &id037
      status: none
    slug: mapquest
    status: profiled
    tags: &id038
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
    agent_band: agent-ready
    agent_readiness: 32.5
    band: developing
    in_catalog: true
    kin_score: 41.0
    mcp: &id039
      status: none
    slug: maptiler
    status: profiled
    tags: &id040
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
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.5
    band: emerging
    in_catalog: true
    kin_score: 15.4
    mcp: &id041
      status: none
    slug: mqtt
    status: profiled
    tags: &id042
    - IoT
    - MQTT
    - Messaging
    - Publish Subscribe
    url: /providers/mqtt/
  layer: common
  name: MQTT
  provider: mqtt
  says: ships the MQTT SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/forward
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
    agent_readiness: 21.0
    band: developing
    in_catalog: true
    kin_score: 40.6
    mcp: &id043
      status: unchecked
    slug: mygeocode
    status: profiled
    tags: &id044
    - Elevation
    - Geocoding
    - IP Lookup
    - Timezone
    url: /providers/mygeocode/
  layer: domain
  name: MyGeocode
  provider: mygeocode
  says: ships the MyGeocode SDK or integration code
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
    agent_readiness: 25.7
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id045
      status: none
    slug: nominatim
    status: profiled
    tags: &id046
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
    agent_readiness: 1.7
    band: minimal
    in_catalog: true
    kin_score: 8.5
    mcp: &id047
      source: https://github.com/OpenCageData/opencage-geocoding-mcp
      status: verified
    slug: opencage
    status: profiled
    tags: &id048
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
    id: AE-120.30.20
    key: AE-120.30.20
    name: Road Attributes & Speed Limits
    url: /capabilities/routing-navigation/
    via_parent: Routing & Navigation
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 15.1
    mcp: &id049
      status: unknown
    slug: overpass-api
    status: profiled
    tags: &id050
    - GIS
    - Geographic
    - OpenStreetMap
    - Spatial
    url: /providers/overpass-api/
  layer: domain
  name: Overpass API
  provider: overpass-api
  says: ships the Overpass API SDK or integration code
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
    agent_readiness: 35.1
    band: strong
    in_catalog: true
    kin_score: 57.6
    mcp: &id051
      status: none
    slug: positionstack
    status: profiled
    tags: &id052
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
    key: push-notifications
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
    mcp: &id053
      status: none
    slug: pushover
    status: profiled
    tags: &id054
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
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id055
      status: none
    slug: rabbitmq
    status: profiled
    tags: &id056
    - AMQP
    - Distributed Systems
    - Queues
    - RabbitMQ
    url: /providers/rabbitmq/
  layer: common
  name: RabbitMQ (AMQP)
  provider: rabbitmq
  says: ships the RabbitMQ (AMQP) SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/forward
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4270.80
    key: webhook-event-subscription-management
    name: Webhook & Event Subscription Management
    url: /capabilities/webhook-event-subscription-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.5
    band: developing
    in_catalog: true
    kin_score: 46.5
    mcp: &id057
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id058
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: common
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/forward
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
    mcp: &id059
      status: none
    slug: telegram
    status: profiled
    tags: &id060
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.4
    mcp: &id061
      source: https://github.com/Tencent/cos-mcp
      status: verified
    slug: tencent-com
    status: profiled
    tags: &id062
    - Company
    url: /providers/tencent-com/
  layer: domain
  name: Tencent Maps
  provider: tencent-com
  says: ships the Tencent Maps SDK or integration code
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
    agent_readiness: 40.9
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id063
      source: https://github.com/tomtom-international/tomtom-mcp
      status: verified
    slug: tomtom
    status: profiled
    tags: &id064
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
    agent_readiness: 21.8
    band: developing
    in_catalog: true
    kin_score: 46.0
    mcp: &id065
      status: none
    slug: unwired-labs
    status: profiled
    tags: &id066
    - Company
    - Geolocation
    - Location API
    - Mapping
    url: /providers/unwired-labs/
  layer: domain
  name: Unwired Labs (incl. OpenCelliD)
  provider: unwired-labs
  says: ships the Unwired Labs (incl. OpenCelliD) SDK or integration code
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
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id067
      status: none
    slug: whatsapp
    status: profiled
    tags: &id068
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
    band: emerging
    in_catalog: true
    kin_score: 17.0
    mcp: &id069
      status: unknown
    slug: wialon
    status: profiled
    tags: &id070
    - Company
    - Fleet Management
    - GPS Tracking
    - Telematics
    url: /providers/wialon/
  layer: domain
  name: Wialon (Gurtam)
  provider: wialon
  says: ships the Wialon (Gurtam) SDK or integration code
  source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/forward
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/fleet-telematics/traccar/
providers:
- agent_band: agent-ready
  agent_readiness: 41.7
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id003
  name: Amazon SNS
  slug: amazon-sns
  status: profiled
  tags: *id004
  url: /providers/amazon-sns/
- agent_band: agent-aware
  agent_readiness: 27.8
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id005
  name: Apache Kafka
  slug: apache-kafka
  status: profiled
  tags: *id006
  url: /providers/apache-kafka/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 19.0
  mcp: *id007
  name: AutoNavi (Amap)
  slug: autonavi
  status: profiled
  tags: *id008
  url: /providers/autonavi/
- agent_band: agent-aware
  agent_readiness: 5.8
  band: emerging
  in_catalog: true
  kin_score: 17.4
  mcp: *id009
  name: Baidu Maps
  slug: baidu
  status: profiled
  tags: *id010
  url: /providers/baidu/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.8
  mcp: *id011
  name: Base Adresse Nationale (adresse.data.gouv.fr)
  slug: adresse-data-gouv-fr
  status: profiled
  tags: *id012
  url: /providers/adresse-data-gouv-fr/
- agent_band: human-only
  agent_readiness: 3.5
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id013
  name: Bing Maps
  slug: bing-maps
  status: profiled
  tags: *id014
  url: /providers/bing-maps/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.6
  mcp: *id015
  name: Factual
  slug: factual
  status: profiled
  tags: *id016
  url: /providers/factual/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id017
  name: Firebase Analytics / Crashlytics
  slug: google-firebase
  status: profiled
  tags: *id018
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id019
  name: Geoapify
  slug: geoapify
  status: profiled
  tags: *id020
  url: /providers/geoapify/
- agent_band: agent-aware
  agent_readiness: 26.1
  band: developing
  in_catalog: true
  kin_score: 45.3
  mcp: *id021
  name: Geocode.Farm
  slug: geocode-farm
  status: profiled
  tags: *id022
  url: /providers/geocode-farm/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.8
  mcp: *id023
  name: Geocode.xyz
  slug: geocode-xyz
  status: profiled
  tags: *id024
  url: /providers/geocode-xyz/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: thin
  in_catalog: true
  kin_score: 32.5
  mcp: *id025
  name: Gisgraphy
  slug: gisgraphy
  status: profiled
  tags: *id026
  url: /providers/gisgraphy/
- agent_band: agent-ready
  agent_readiness: 33.0
  band: exemplar
  in_catalog: true
  kin_score: 73.6
  mcp: *id027
  name: Google Maps
  slug: google-maps
  status: profiled
  tags: *id028
  url: /providers/google-maps/
- agent_band: agent-native
  agent_readiness: 54.4
  band: exemplar
  in_catalog: true
  kin_score: 79.0
  mcp: *id029
  name: HERE
  slug: here
  status: profiled
  tags: *id030
  url: /providers/here/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.8
  mcp: *id031
  name: LocationIQ
  slug: locationiq
  status: profiled
  tags: *id032
  url: /providers/locationiq/
- agent_band: agent-ready
  agent_readiness: 45.2
  band: developing
  in_catalog: true
  kin_score: 50.7
  mcp: *id033
  name: Mapbox
  slug: mapbox
  status: profiled
  tags: *id034
  url: /providers/mapbox/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.7
  mcp: *id035
  name: MapmyIndia (Mappls)
  slug: mappls
  status: profiled
  tags: *id036
  url: /providers/mappls/
- agent_band: agent-aware
  agent_readiness: 14.7
  band: thin
  in_catalog: true
  kin_score: 35.2
  mcp: *id037
  name: MapQuest
  slug: mapquest
  status: profiled
  tags: *id038
  url: /providers/mapquest/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 41.0
  mcp: *id039
  name: MapTiler
  slug: maptiler
  status: profiled
  tags: *id040
  url: /providers/maptiler/
- agent_band: agent-aware
  agent_readiness: 16.5
  band: emerging
  in_catalog: true
  kin_score: 15.4
  mcp: *id041
  name: MQTT
  slug: mqtt
  status: profiled
  tags: *id042
  url: /providers/mqtt/
- agent_band: agent-aware
  agent_readiness: 21.0
  band: developing
  in_catalog: true
  kin_score: 40.6
  mcp: *id043
  name: MyGeocode
  slug: mygeocode
  status: profiled
  tags: *id044
  url: /providers/mygeocode/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id045
  name: Nominatim
  slug: nominatim
  status: profiled
  tags: *id046
  url: /providers/nominatim/
- agent_band: human-only
  agent_readiness: 1.7
  band: minimal
  in_catalog: true
  kin_score: 8.5
  mcp: *id047
  name: OpenCage
  slug: opencage
  status: profiled
  tags: *id048
  url: /providers/opencage/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 15.1
  mcp: *id049
  name: Overpass API
  slug: overpass-api
  status: profiled
  tags: *id050
  url: /providers/overpass-api/
- agent_band: agent-ready
  agent_readiness: 35.1
  band: strong
  in_catalog: true
  kin_score: 57.6
  mcp: *id051
  name: positionstack
  slug: positionstack
  status: profiled
  tags: *id052
  url: /providers/positionstack/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id053
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id054
  url: /providers/pushover/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id055
  name: RabbitMQ (AMQP)
  slug: rabbitmq
  status: profiled
  tags: *id056
  url: /providers/rabbitmq/
- agent_band: agent-ready
  agent_readiness: 41.5
  band: developing
  in_catalog: true
  kin_score: 46.5
  mcp: *id057
  name: Redis
  slug: redis
  status: profiled
  tags: *id058
  url: /providers/redis/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id059
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id060
  url: /providers/telegram/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.4
  mcp: *id061
  name: Tencent Maps
  slug: tencent-com
  status: profiled
  tags: *id062
  url: /providers/tencent-com/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id063
  name: TomTom
  slug: tomtom
  status: profiled
  tags: *id064
  url: /providers/tomtom/
- agent_band: agent-aware
  agent_readiness: 21.8
  band: developing
  in_catalog: true
  kin_score: 46.0
  mcp: *id065
  name: Unwired Labs (incl. OpenCelliD)
  slug: unwired-labs
  status: profiled
  tags: *id066
  url: /providers/unwired-labs/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id067
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id068
  url: /providers/whatsapp/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 17.0
  mcp: *id069
  name: Wialon (Gurtam)
  slug: wialon
  status: profiled
  tags: *id070
  url: /providers/wialon/
siblings:
- name: Fleetbase
  rows: 15
  url: /applications/fleet-telematics/fleetbase/
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
sitemap: true
title: 'Traccar: Fleet Management & Telematics reference app'
---
