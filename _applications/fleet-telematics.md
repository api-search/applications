---
access: understanding
agent_layer:
- app: Fleetio
  finding: Fleetio help centre lists an "MCP Server" article among its integrations articles (Fleetio exposes its own MCP server)
  source: https://help.fleetio.com/en_US/integrations
  tier: declared
apps:
- anchor: traccar
  counts:
    declared: 0
    observed: 36
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
    layer: domain
    name: Wialon (Gurtam)
    provider: wialon
    says: ships the Wialon (Gurtam) SDK or integration code
    source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/forward
    tier: observed
  kind: self-hosted
  name: Traccar
  page: /applications/fleet-telematics/traccar/
  slug: traccar
  url: https://github.com/traccar/traccar
- anchor: fleetbase
  counts:
    declared: 0
    observed: 15
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
    layer: common
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/fleetbase/core-api/blob/main/composer.json
    tier: observed
  kind: self-hosted
  name: Fleetbase
  page: /applications/fleet-telematics/fleetbase/
  slug: fleetbase
  url: https://github.com/fleetbase/fleetbase
- anchor: samsara
  counts:
    declared: 12
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.samsara.com/marketplace
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2130
      key: insurance-underwriting-management
      name: Insurance Underwriting Management
      url: /capabilities/insurance-underwriting-management/
      via_parent: null
    credit: null
    layer: domain
    name: Acuity Insurance
    provider: acuity-insurance
    says: lists Acuity Insurance as an integration
    source: https://www.samsara.com/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Carrier Transicold (Lynx Fleet)
    provider: carrier-transicold
    says: lists Carrier Transicold (Lynx Fleet) as an integration
    source: https://www.samsara.com/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2130
      key: insurance-underwriting-management
      name: Insurance Underwriting Management
      url: /capabilities/insurance-underwriting-management/
      via_parent: null
    credit: null
    layer: domain
    name: Fenchurch General Insurance
    provider: fenchurch-general-insurance
    says: lists Fenchurch General Insurance as an integration
    source: https://www.samsara.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: domain
    name: FLEETCOR Fuel Card
    provider: corpay
    says: lists FLEETCOR Fuel Card as an integration
    source: https://www.samsara.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20
      key: connected-vehicles
      name: Connected Vehicles
      url: /capabilities/connected-vehicles/
      via_parent: null
    credit: null
    layer: domain
    name: Ford Pro
    provider: fordpass
    says: lists Ford Pro as an integration
    source: https://www.samsara.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20
      key: connected-vehicles
      name: Connected Vehicles
      url: /capabilities/connected-vehicles/
      via_parent: null
    credit: null
    layer: domain
    name: General Motors
    provider: general-motors
    says: lists General Motors as an integration
    source: https://www.samsara.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20
      key: connected-vehicles
      name: Connected Vehicles
      url: /capabilities/connected-vehicles/
      via_parent: null
    credit: null
    layer: domain
    name: Liebherr
    provider: liebherr
    says: lists Liebherr as an integration
    source: https://www.samsara.com/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.10
      key: dispatch-management
      name: Dispatch Management
      url: /capabilities/dispatch-management/
      via_parent: null
    credit: null
    layer: domain
    name: McLeod LoadMaster
    provider: mcleod-software
    says: lists McLeod LoadMaster as an integration
    source: https://www.samsara.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20
      key: connected-vehicles
      name: Connected Vehicles
      url: /capabilities/connected-vehicles/
      via_parent: null
    credit: null
    layer: domain
    name: Navistar
    provider: navistar-international
    says: lists Navistar as an integration
    source: https://www.samsara.com/marketplace
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430.20
      key: fleet-maintenance-management
      name: Fleet Maintenance Management
      url: /capabilities/fleet-maintenance-management/
      via_parent: null
    credit: null
    layer: domain
    name: Penske eDVIR (built by ATI)
    provider: penske
    says: lists Penske eDVIR (built by ATI) as an integration
    source: https://www.samsara.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20
      key: connected-vehicles
      name: Connected Vehicles
      url: /capabilities/connected-vehicles/
      via_parent: null
    credit: null
    layer: domain
    name: Rivian
    provider: rivian-automotive
    says: lists Rivian as an integration
    source: https://www.samsara.com/marketplace
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: domain
    name: WEX Fleet Card
    provider: wex
    says: lists WEX Fleet Card as an integration
    source: https://www.samsara.com/marketplace
    tier: declared
  kind: commercial
  name: Samsara
  page: /applications/fleet-telematics/samsara/
  slug: samsara
  url: https://www.samsara.com/
- anchor: motive
  counts:
    declared: 14
    observed: 0
  evidence:
  - route: integrations page
    url: https://marketplace.gomotive.com/
  - route: integrations page
    url: https://marketplace.gomotive.com/t/categories/tms
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: common
    name: ADP
    provider: adp
    says: lists ADP as an integration
    source: https://marketplace.gomotive.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Airtable
    provider: airtable
    says: lists Airtable as an integration
    source: https://marketplace.gomotive.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.10
      key: dispatch-management
      name: Dispatch Management
      url: /capabilities/dispatch-management/
      via_parent: null
    credit: null
    layer: domain
    name: Alvys
    provider: alvys
    says: lists Alvys as an integration
    source: https://marketplace.gomotive.com/t/categories/tms
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2400
      key: freight-capacity-management
      name: Freight Capacity Management
      url: /capabilities/freight-capacity-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Relay
    provider: amazon-relay
    says: lists Amazon Relay as an integration
    source: https://marketplace.gomotive.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430.20
      key: fleet-maintenance-management
      name: Fleet Maintenance Management
      url: /capabilities/fleet-maintenance-management/
      via_parent: null
    credit: null
    layer: domain
    name: AMCS Fleet Maintenance
    provider: amcs-group
    says: lists AMCS Fleet Maintenance as an integration
    source: https://marketplace.gomotive.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1050.20
      key: service-dispatch-management
      name: Service Dispatch Management
      url: /capabilities/service-dispatch-management/
      via_parent: null
    credit: null
    layer: domain
    name: Arrivy
    provider: arrivy
    says: lists Arrivy as an integration
    source: https://marketplace.gomotive.com/t/categories/tms
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.10
      key: dispatch-management
      name: Dispatch Management
      url: /capabilities/dispatch-management/
      via_parent: null
    credit: null
    layer: domain
    name: AscendTMS
    provider: ascendtms
    says: lists AscendTMS as an integration
    source: https://marketplace.gomotive.com/t/categories/tms
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: domain
    name: AtoB
    provider: atob
    says: lists AtoB as an integration
    source: https://marketplace.gomotive.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    credit: null
    layer: common
    name: Auth0 Single Sign-On
    provider: auth0
    says: lists Auth0 Single Sign-On as an integration
    source: https://marketplace.gomotive.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430.20
      key: fleet-maintenance-management
      name: Fleet Maintenance Management
      url: /capabilities/fleet-maintenance-management/
      via_parent: null
    credit: null
    layer: domain
    name: AUTOsist
    provider: autosist
    says: lists AUTOsist as an integration
    source: https://marketplace.gomotive.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2420.10
      key: dispatch-management
      name: Dispatch Management
      url: /capabilities/dispatch-management/
      via_parent: null
    credit: null
    layer: domain
    name: HCSS
    provider: hcss
    says: lists HCSS as an integration
    source: https://marketplace.gomotive.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20
      key: connected-vehicles
      name: Connected Vehicles
      url: /capabilities/connected-vehicles/
      via_parent: null
    credit: null
    layer: domain
    name: John Deere JDLink
    provider: john-deere
    says: lists John Deere JDLink as an integration
    source: https://marketplace.gomotive.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20
      key: connected-vehicles
      name: Connected Vehicles
      url: /capabilities/connected-vehicles/
      via_parent: null
    credit: null
    layer: domain
    name: Komatsu Komtrax
    provider: komatsu
    says: lists Komatsu Komtrax as an integration
    source: https://marketplace.gomotive.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20
      key: connected-vehicles
      name: Connected Vehicles
      url: /capabilities/connected-vehicles/
      via_parent: null
    credit: null
    layer: domain
    name: Stellantis
    provider: stellantis
    says: lists Stellantis as an integration
    source: https://marketplace.gomotive.com/
    tier: declared
  kind: commercial
  name: Motive
  page: /applications/fleet-telematics/motive/
  slug: motive
  url: https://gomotive.com/
- anchor: geotab
  counts:
    declared: 5
    observed: 0
  evidence:
  - route: integrations page
    url: https://marketplace.geotab.com/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2430
      key: fleet-mobile-asset-management
      name: Fleet & Mobile Asset Management
      url: /capabilities/fleet-mobile-asset-management/
      via_parent: null
    credit: null
    layer: domain
    name: Link Labs (AirFinder)
    provider: link-labs
    says: lists Link Labs (AirFinder) as an integration
    source: https://marketplace.geotab.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Lytx (Surfsight)
    provider: lytx
    says: lists Lytx (Surfsight) as an integration
    source: https://marketplace.geotab.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430
      key: fleet-mobile-asset-management
      name: Fleet & Mobile Asset Management
      url: /capabilities/fleet-mobile-asset-management/
      via_parent: null
    credit: null
    layer: domain
    name: ORBCOMM (VIACHAIN)
    provider: orbcomm
    says: lists ORBCOMM (VIACHAIN) as an integration
    source: https://marketplace.geotab.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    credit: null
    layer: domain
    name: Xirgo
    provider: xirgo
    says: lists Xirgo as an integration
    source: https://marketplace.geotab.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2160
      key: insurance-claims-management
      name: Insurance Claims Management
      url: /capabilities/insurance-claims-management/
      via_parent: null
    credit: null
    layer: domain
    name: Xtract360
    provider: xtract360
    says: lists Xtract360 as an integration
    source: https://marketplace.geotab.com/
    tier: declared
  kind: commercial
  name: Geotab
  page: /applications/fleet-telematics/geotab/
  slug: geotab
  url: https://www.geotab.com/
- anchor: fleetio
  counts:
    declared: 11
    observed: 0
  evidence:
  - route: integrations page
    url: https://help.fleetio.com/en_US/integrations/fuel-integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: domain
    name: AtoB
    provider: atob
    says: lists AtoB as an integration
    source: https://help.fleetio.com/en_US/integrations/fuel-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: domain
    name: CarIQ
    provider: cariq
    says: lists CarIQ as an integration
    source: https://help.fleetio.com/en_US/integrations/fuel-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: domain
    name: Coast
    provider: coast
    says: lists Coast as an integration
    source: https://help.fleetio.com/en_US/integrations/fuel-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: domain
    name: Comdata
    provider: comdata
    says: lists Comdata as an integration
    source: https://help.fleetio.com/en_US/integrations/fuel-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: domain
    name: Corpay / FLEETCOR
    provider: corpay
    says: lists Corpay / FLEETCOR as an integration
    source: https://help.fleetio.com/en_US/integrations/fuel-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: domain
    name: EFS
    provider: efs
    says: lists EFS as an integration
    source: https://help.fleetio.com/en_US/integrations/fuel-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: domain
    name: Fill-Rite FMS
    provider: fill-rite
    says: lists Fill-Rite FMS as an integration
    source: https://help.fleetio.com/en_US/integrations/fuel-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: domain
    name: FuelCloud
    provider: fuelcloud
    says: lists FuelCloud as an integration
    source: https://help.fleetio.com/en_US/integrations/fuel-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: domain
    name: FuelMaster
    provider: fuelmaster
    says: lists FuelMaster as an integration
    source: https://help.fleetio.com/en_US/integrations/fuel-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: domain
    name: Intevacon
    provider: intevacon
    says: lists Intevacon as an integration
    source: https://help.fleetio.com/en_US/integrations/fuel-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    credit: null
    layer: domain
    name: WEX
    provider: wex
    says: lists WEX as an integration
    source: https://help.fleetio.com/en_US/integrations/fuel-integrations
    tier: declared
  kind: commercial
  name: Fleetio
  page: /applications/fleet-telematics/fleetio/
  slug: fleetio
  url: https://www.fleetio.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: fleet-telematics
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Fuel Card
  store: samsara-app-marketplace
  url: https://www.samsara.com/marketplace
- category: OEM
  store: samsara-app-marketplace
  url: https://www.samsara.com/marketplace
- category: Maintenance
  store: samsara-app-marketplace
  url: https://www.samsara.com/marketplace
- category: TMS
  store: samsara-app-marketplace
  url: https://www.samsara.com/marketplace
- category: TMS
  store: motive-app-marketplace
  url: https://marketplace.gomotive.com/t/categories/tms
- category: Asset & Trailer Tracking
  store: geotab-marketplace
  url: https://marketplace.geotab.com/
- category: Cameras & ADAS
  store: geotab-marketplace
  url: https://marketplace.geotab.com/
name: Fleet Management & Telematics
needs:
- capability:
    attribution: Turbo EA
    id: BC-2430.40
    key: fleet-telematics-and-monitoring
    name: Fleet Telematics and Monitoring
    url: /capabilities/fleet-telematics-and-monitoring/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Fleetbase, Geotab, Samsara, Traccar
- capability:
    attribution: API Evangelist extension
    id: AE-940
    key: AE-940
    name: Fleet Fuel Cards & Fuel Transaction Data
    url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Fleetbase, Fleetio, Motive, Samsara
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: push-notifications
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: named by Fleetbase, Traccar
- capability:
    attribution: API Evangelist extension
    id: AE-150.20
    key: sms-messaging-apps
    name: SMS & Messaging Apps
    url: /capabilities/sms-messaging-apps/
    via_parent: null
  fit: exact
  layer: common
  why: named by Fleetbase, Traccar
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: nearest
  layer: common
  why: named by Fleetbase, Traccar
- capability:
    attribution: Turbo EA
    id: BC-2400
    key: freight-capacity-management
    name: Freight Capacity Management
    url: /capabilities/freight-capacity-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: named by Fleetbase, Motive
- capability:
    attribution: API Evangelist extension
    id: AE-200.20
    key: connected-vehicles
    name: Connected Vehicles
    url: /capabilities/connected-vehicles/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Motive, Samsara
- capability:
    attribution: Turbo EA
    id: BC-2420.10
    key: dispatch-management
    name: Dispatch Management
    url: /capabilities/dispatch-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: named by Motive, Samsara
- capability:
    attribution: Turbo EA
    id: BC-2430.20
    key: fleet-maintenance-management
    name: Fleet Maintenance Management
    url: /capabilities/fleet-maintenance-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Motive, Samsara
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: domain
  why: named by Traccar
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.20
    key: AE-120.50.20
    name: Device Positioning
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: domain
  why: named by Traccar
- capability:
    attribution: API Evangelist extension
    id: AE-120.30.20
    key: AE-120.30.20
    name: Road Attributes & Speed Limits
    url: /capabilities/routing-navigation/
    via_parent: Routing & Navigation
  fit: exact
  layer: domain
  why: named by Traccar
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: named by Traccar
- capability:
    attribution: Turbo EA
    id: BC-4270.80
    key: webhook-event-subscription-management
    name: Webhook & Event Subscription Management
    url: /capabilities/webhook-event-subscription-management/
    via_parent: null
  fit: gap
  layer: common
  why: named by Traccar
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: named by Fleetbase
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: nearest
  layer: common
  why: named by Fleetbase
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: domain
  why: named by Fleetbase
- capability:
    attribution: Turbo EA
    id: BC-2130
    key: insurance-underwriting-management
    name: Insurance Underwriting Management
    url: /capabilities/insurance-underwriting-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: named by Samsara
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  fit: nearest
  layer: common
  why: named by Motive
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: named by Motive
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: named by Motive
- capability:
    attribution: Turbo EA
    id: BC-1050.20
    key: service-dispatch-management
    name: Service Dispatch Management
    url: /capabilities/service-dispatch-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Motive
- capability:
    attribution: Turbo EA
    id: BC-2430
    key: fleet-mobile-asset-management
    name: Fleet & Mobile Asset Management
    url: /capabilities/fleet-mobile-asset-management/
    via_parent: null
  fit: exact
  layer: domain
  why: named by Geotab
- capability:
    attribution: Turbo EA
    id: BC-2160
    key: insurance-claims-management
    name: Insurance Claims Management
    url: /capabilities/insurance-claims-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: named by Geotab
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: Apache Kafka, RabbitMQ (AMQP), MQTT (Integration and API Management)
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.20
      key: AE-120.10.20
      name: Reverse Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-native
      agent_readiness: 54.4
      apps:
      - Traccar
      band: exemplar
      in_catalog: true
      kin_score: 79.0
      mcp:
        status: none
      name: HERE
      slug: here
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Location
      - Mapping
      - Maps
      - Spatial
      tier: observed
      url: /providers/here/
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Traccar
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp: &id001
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps
      slug: google-maps
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags: &id002
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Traccar
      band: strong
      in_catalog: true
      kin_score: 62.6
      mcp:
        status: none
      name: Geoapify
      slug: geoapify
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Location
      - Maps
      tier: observed
      url: /providers/geoapify/
    - agent_band: agent-ready
      agent_readiness: 35.1
      apps:
      - Traccar
      band: strong
      in_catalog: true
      kin_score: 57.6
      mcp:
        status: none
      name: positionstack
      slug: positionstack
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Geocoding
      - Location
      - Maps
      - Reverse Geocoding
      tier: observed
      url: /providers/positionstack/
    - agent_band: agent-ready
      agent_readiness: 45.2
      apps:
      - Traccar
      band: developing
      in_catalog: true
      kin_score: 50.7
      mcp:
        source: https://github.com/mapbox/mcp-server
        status: verified
      name: Mapbox
      slug: mapbox
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Geospatial
      - Location
      - Mapping
      - Maps
      tier: observed
      url: /providers/mapbox/
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - Traccar
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp:
        source: https://github.com/tomtom-international/tomtom-mcp
        status: verified
      name: TomTom
      slug: tomtom
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Maps
      - Navigation
      - Traffic
      - Transportation
      tier: observed
      url: /providers/tomtom/
    - agent_band: agent-aware
      agent_readiness: 26.1
      apps:
      - Traccar
      band: developing
      in_catalog: true
      kin_score: 45.3
      mcp:
        status: unknown
      name: Geocode.Farm
      slug: geocode-farm
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Data
      - Geocoding
      - Location
      - Services
      tier: observed
      url: /providers/geocode-farm/
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - Traccar
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Nominatim
      slug: nominatim
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Geocoding
      - Location Services
      - Maps
      - OpenStreetMap
      tier: observed
      url: /providers/nominatim/
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Traccar
      band: developing
      in_catalog: true
      kin_score: 41.0
      mcp:
        status: none
      name: MapTiler
      slug: maptiler
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Geospatial
      - Maps
      - Tiles
      - Vector Tiles
      tier: observed
      url: /providers/maptiler/
    - agent_band: agent-aware
      agent_readiness: 21.0
      apps:
      - Traccar
      band: developing
      in_catalog: true
      kin_score: 40.6
      mcp:
        status: unchecked
      name: MyGeocode
      slug: mygeocode
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Elevation
      - Geocoding
      - IP Lookup
      - Timezone
      tier: observed
      url: /providers/mygeocode/
    - agent_band: agent-aware
      agent_readiness: 14.7
      apps:
      - Traccar
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        status: none
      name: MapQuest
      slug: mapquest
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Geocoding
      - Mapping
      - Maps
      - Navigation
      tier: observed
      url: /providers/mapquest/
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - Traccar
      band: thin
      in_catalog: true
      kin_score: 32.5
      mcp:
        status: none
      name: Gisgraphy
      slug: gisgraphy
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Company
      - Geocoding
      - Geolocation
      - Open Source
      tier: observed
      url: /providers/gisgraphy/
    - agent_band: human-only
      agent_readiness: 3.5
      apps:
      - Traccar
      band: thin
      in_catalog: true
      kin_score: 28.9
      mcp:
        status: none
      name: Bing Maps
      slug: bing-maps
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Maps
      - Routing
      tier: observed
      url: /providers/bing-maps/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Traccar
      band: emerging
      in_catalog: true
      kin_score: 19.0
      mcp:
        status: unchecked
      name: AutoNavi (Amap)
      slug: autonavi
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - China
      - Company
      - Location Services
      - Mapping
      tier: observed
      url: /providers/autonavi/
    - agent_band: agent-aware
      agent_readiness: 5.8
      apps:
      - Traccar
      band: emerging
      in_catalog: true
      kin_score: 17.4
      mcp:
        source: https://github.com/baidu-maps/mcp
        status: verified
      name: Baidu Maps
      slug: baidu
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Machine Learning
      - Technology
      tier: observed
      url: /providers/baidu/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Traccar
      band: emerging
      in_catalog: true
      kin_score: 12.8
      mcp:
        status: none
      name: Base Adresse Nationale (adresse.data.gouv.fr)
      slug: adresse-data-gouv-fr
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Geocoding
      - Public APIs
      tier: observed
      url: /providers/adresse-data-gouv-fr/
    - agent_band: human-only
      agent_readiness: 1.7
      apps:
      - Traccar
      band: minimal
      in_catalog: true
      kin_score: 8.5
      mcp:
        source: https://github.com/OpenCageData/opencage-geocoding-mcp
        status: verified
      name: OpenCage
      slug: opencage
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Public APIs
      tier: observed
      url: /providers/opencage/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Traccar
      band: minimal
      in_catalog: true
      kin_score: 7.7
      mcp:
        status: none
      name: MapmyIndia (Mappls)
      slug: mappls
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Company
      - Location
      - Mapping
      - Navigation
      tier: observed
      url: /providers/mappls/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Traccar
      band: minimal
      in_catalog: true
      kin_score: 4.8
      mcp:
        status: unknown
      name: Geocode.xyz
      slug: geocode-xyz
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Geocoding
      - Public APIs
      tier: observed
      url: /providers/geocode-xyz/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Traccar
      band: minimal
      in_catalog: true
      kin_score: 4.8
      mcp:
        status: none
      name: LocationIQ
      slug: locationiq
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Public APIs
      tier: observed
      url: /providers/locationiq/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Traccar
      band: minimal
      in_catalog: true
      kin_score: 4.6
      mcp:
        status: none
      name: Factual
      slug: factual
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Company
      - Geolocation
      - Location
      - Places
      tier: observed
      url: /providers/factual/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Traccar
      band: minimal
      in_catalog: true
      kin_score: 4.4
      mcp:
        source: https://github.com/Tencent/cos-mcp
        status: verified
      name: Tencent Maps
      slug: tencent-com
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/tencent-com/
  - capability:
      attribution: API Evangelist extension
      id: AE-940
      key: AE-940
      name: Fleet Fuel Cards & Fuel Transaction Data
      url: /capabilities/fleet-fuel-cards-fuel-transaction-data/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Fleetio
      - Motive
      band: emerging
      in_catalog: true
      kin_score: 15.2
      mcp:
        status: none
      name: AtoB
      slug: atob
      sources:
      - https://help.fleetio.com/en_US/integrations/fuel-integrations
      - https://marketplace.gomotive.com/
      status: profiled
      tags:
      - Company
      - Fleet Management
      - Fuel Cards
      - Payments
      tier: declared
      url: /providers/atob/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Fleetio
      - Samsara
      band: minimal
      in_catalog: true
      kin_score: 9.7
      mcp:
        status: none
      name: WEX Fleet Card
      slug: wex
      sources:
      - https://help.fleetio.com/en_US/integrations/fuel-integrations
      - https://www.samsara.com/marketplace
      status: profiled
      tags: []
      tier: declared
      url: /providers/wex/
    - agent_band: human-only
      agent_readiness: 2.1
      apps:
      - Fleetio
      - Samsara
      band: minimal
      in_catalog: true
      kin_score: 6.9
      mcp:
        status: unknown
      name: FLEETCOR Fuel Card
      slug: corpay
      sources:
      - https://help.fleetio.com/en_US/integrations/fuel-integrations
      - https://www.samsara.com/marketplace
      status: profiled
      tags:
      - Accounts Payable
      - Corporate Payments
      - Cross-Border Payments
      - Payments
      tier: declared
      url: /providers/corpay/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Fleetbase
      band: emerging
      in_catalog: true
      kin_score: 19.9
      mcp:
        status: unchecked
      name: PetroApp
      slug: petroapp
      sources:
      - https://github.com/fleetbase/fleetops/tree/main/server/src/Support/FuelProviders/Providers
      status: profiled
      tags:
      - Company
      - Fleet Management
      - Fuel Expenses
      - Software-as-a-Service
      tier: observed
      url: /providers/petroapp/
    - agent_band: agent-aware
      agent_readiness: 17.1
      apps:
      - Fleetbase
      band: emerging
      in_catalog: true
      kin_score: 18.8
      mcp:
        status: unchecked
      name: SASCO
      slug: sasco
      sources:
      - https://github.com/fleetbase/fleetops/tree/main/server/src/Support/FuelProviders/Providers
      status: profiled
      tags:
      - Automotive
      - Public Company
      - Saudi Arabia
      - Services
      tier: observed
      url: /providers/sasco/
    - agent_band: agent-ready
      agent_readiness: 37.2
      apps:
      - Fleetio
      band: thin
      in_catalog: true
      kin_score: 32.4
      mcp:
        status: unchecked
      name: FuelCloud
      slug: fuelcloud
      sources:
      - https://help.fleetio.com/en_US/integrations/fuel-integrations
      status: profiled
      tags:
      - Cloud Services
      - Company
      - Fleet Operations
      - Fuel Management
      tier: declared
      url: /providers/fuelcloud/
    - agent_band: agent-aware
      agent_readiness: 21.7
      apps:
      - Fleetio
      band: emerging
      in_catalog: true
      kin_score: 25.0
      mcp:
        status: unchecked
      name: Fill-Rite FMS
      slug: fill-rite
      sources:
      - https://help.fleetio.com/en_US/integrations/fuel-integrations
      status: profiled
      tags:
      - Chemical Transfer
      - Flow Meters
      - Fuel Transfer
      - Oil Transfer
      tier: declared
      url: /providers/fill-rite/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Fleetio
      band: emerging
      in_catalog: true
      kin_score: 16.5
      mcp:
        status: unknown
      name: Coast
      slug: coast
      sources:
      - https://help.fleetio.com/en_US/integrations/fuel-integrations
      status: profiled
      tags:
      - Company
      - Fintech
      - Fleet Management
      - Payments
      tier: declared
      url: /providers/coast/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Fleetio
      band: minimal
      in_catalog: true
      kin_score: 6.0
      mcp:
        status: unchecked
      name: Intevacon
      slug: intevacon
      sources:
      - https://help.fleetio.com/en_US/integrations/fuel-integrations
      status: profiled
      tags:
      - Company
      - Fleet Card
      - Payments
      - Petroleum
      tier: declared
      url: /providers/intevacon/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Fleetio
      band: minimal
      in_catalog: true
      kin_score: 4.0
      mcp:
        status: unchecked
      name: Comdata
      slug: comdata
      sources:
      - https://help.fleetio.com/en_US/integrations/fuel-integrations
      status: profiled
      tags:
      - Company
      - Fleet Management
      - Fuel Services
      - Payments
      tier: declared
      url: /providers/comdata/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Fleetio
      band: minimal
      in_catalog: true
      kin_score: 2.2
      mcp:
        status: unchecked
      name: FuelMaster
      slug: fuelmaster
      sources:
      - https://help.fleetio.com/en_US/integrations/fuel-integrations
      status: profiled
      tags:
      - Automotive
      - Company
      - Environment
      - FuelSaving
      tier: declared
      url: /providers/fuelmaster/
    - agent_band: null
      agent_readiness: null
      apps:
      - Fleetio
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: CarIQ
      slug: cariq
      sources:
      - https://help.fleetio.com/en_US/integrations/fuel-integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Fleetio
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: EFS
      slug: efs
      sources:
      - https://help.fleetio.com/en_US/integrations/fuel-integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-2430.40
      key: fleet-telematics-and-monitoring
      name: Fleet Telematics and Monitoring
      url: /capabilities/fleet-telematics-and-monitoring/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.0
      apps:
      - Fleetbase
      band: developing
      in_catalog: true
      kin_score: 43.5
      mcp:
        status: unchecked
      name: flespi (Gurtam)
      slug: flespi
      sources:
      - https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
      status: profiled
      tags:
      - Data Ingestion
      - IoT
      - Real-Time Analytics
      - Telematics
      tier: observed
      url: /providers/flespi/
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Fleetbase
      band: thin
      in_catalog: true
      kin_score: 36.9
      mcp:
        source: https://mcp.geotab.com/mygeotab
        status: verified
      name: Geotab
      slug: geotab
      sources:
      - https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
      status: profiled
      tags:
      - ELD Compliance
      - Fleet Management
      - Telematics
      - Vehicle Tracking
      tier: observed
      url: /providers/geotab/
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - Fleetbase
      band: thin
      in_catalog: true
      kin_score: 32.0
      mcp:
        source: https://mcp.samsara.com/mcp
        status: documented
      name: Samsara
      slug: samsara
      sources:
      - https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
      status: profiled
      tags:
      - Asset Tracking
      - Connected Operations
      - ELD
      - Fleet Management
      tier: observed
      url: /providers/samsara/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Traccar
      band: emerging
      in_catalog: true
      kin_score: 17.0
      mcp:
        status: unknown
      name: Wialon (Gurtam)
      slug: wialon
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/forward
      status: profiled
      tags:
      - Company
      - Fleet Management
      - GPS Tracking
      - Telematics
      tier: observed
      url: /providers/wialon/
    - agent_band: agent-aware
      agent_readiness: 21.4
      apps:
      - Fleetbase
      band: minimal
      in_catalog: true
      kin_score: 8.3
      mcp:
        status: unchecked
      name: Safee
      slug: safee
      sources:
      - https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
      status: profiled
      tags:
      - Fleet Management
      - GPS Tracking
      - Telematics
      - Vehicle-Analytics
      tier: observed
      url: /providers/safee/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Fleetbase
      band: minimal
      in_catalog: true
      kin_score: 4.5
      mcp:
        status: unchecked
      name: AFAQY
      slug: afaqy
      sources:
      - https://github.com/fleetbase/fleetops/tree/main/server/src/Support/Telematics/Providers
      status: profiled
      tags:
      - AVL
      - Fleet Management
      - IoT
      - Smart Parking
      tier: observed
      url: /providers/afaqy/
    - agent_band: agent-ready
      agent_readiness: 47.2
      apps:
      - Geotab
      band: developing
      in_catalog: true
      kin_score: 40.9
      mcp:
        status: unknown
      name: Lytx (Surfsight)
      slug: lytx
      sources:
      - https://marketplace.geotab.com/
      status: profiled
      tags:
      - Company
      - Fleet Management
      - Vehicle Safety
      - Video Telematics
      tier: declared
      url: /providers/lytx/
    - agent_band: agent-aware
      agent_readiness: 21.4
      apps:
      - Geotab
      band: emerging
      in_catalog: true
      kin_score: 14.7
      mcp:
        status: unchecked
      name: Xirgo
      slug: xirgo
      sources:
      - https://marketplace.geotab.com/
      status: profiled
      tags:
      - Fleet Management
      - IoT
      - Logistics
      - Telematics
      tier: declared
      url: /providers/xirgo/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Samsara
      band: minimal
      in_catalog: true
      kin_score: 2.8
      mcp:
        status: unchecked
      name: Carrier Transicold (Lynx Fleet)
      slug: carrier-transicold
      sources:
      - https://www.samsara.com/marketplace
      status: profiled
      tags:
      - Cold Chain
      - Company
      - IoT
      - Transport Refrigeration
      tier: declared
      url: /providers/carrier-transicold/
  - capability:
      attribution: API Evangelist extension
      id: AE-200.20
      key: connected-vehicles
      name: Connected Vehicles
      url: /capabilities/connected-vehicles/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - Motive
      band: emerging
      in_catalog: true
      kin_score: 22.8
      mcp:
        status: none
      name: Stellantis
      slug: stellantis
      sources:
      - https://marketplace.gomotive.com/
      status: profiled
      tags:
      - Automotive
      - Company
      - Manufacturing
      - Mobility
      tier: declared
      url: /providers/stellantis/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Samsara
      band: emerging
      in_catalog: true
      kin_score: 16.9
      mcp:
        status: none
      name: General Motors
      slug: general-motors
      sources:
      - https://www.samsara.com/marketplace
      status: profiled
      tags:
      - Automobiles
      - Cars
      - Connected Vehicles
      - Vehicles
      tier: declared
      url: /providers/general-motors/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Samsara
      band: emerging
      in_catalog: true
      kin_score: 11.2
      mcp:
        status: none
      name: Rivian
      slug: rivian-automotive
      sources:
      - https://www.samsara.com/marketplace
      status: profiled
      tags:
      - Automotive
      - Connected Vehicles
      - Electric Vehicles
      - Manufacturing
      tier: declared
      url: /providers/rivian-automotive/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Samsara
      band: minimal
      in_catalog: true
      kin_score: 10.8
      mcp:
        source: https://www.ford.com/ford-vehicle-mcp/mcp
        status: documented
      name: Ford Pro
      slug: fordpass
      sources:
      - https://www.samsara.com/marketplace
      status: profiled
      tags:
      - Automotive
      - Connected Vehicles
      - Fleet Management
      - Telematics
      tier: declared
      url: /providers/fordpass/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Motive
      band: minimal
      in_catalog: true
      kin_score: 9.9
      mcp:
        status: none
      name: John Deere JDLink
      slug: john-deere
      sources:
      - https://marketplace.gomotive.com/
      status: profiled
      tags:
      - Agriculture
      - Combines
      - Construction
      - Excavators
      tier: declared
      url: /providers/john-deere/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Motive
      band: minimal
      in_catalog: true
      kin_score: 8.7
      mcp:
        status: unchecked
      name: Komatsu Komtrax
      slug: komatsu
      sources:
      - https://marketplace.gomotive.com/
      status: profiled
      tags:
      - Company
      - Construction
      - Industrial Equipment
      - Mining
      tier: declared
      url: /providers/komatsu/
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - Samsara
      band: minimal
      in_catalog: true
      kin_score: 7.1
      mcp:
        status: unchecked
      name: Liebherr
      slug: liebherr
      sources:
      - https://www.samsara.com/marketplace
      status: profiled
      tags:
      - Company
      - Engineering
      - Heavy Equipment
      - Manufacturing
      tier: declared
      url: /providers/liebherr/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Samsara
      band: minimal
      in_catalog: true
      kin_score: 1.7
      mcp:
        status: unknown
      name: Navistar
      slug: navistar-international
      sources:
      - https://www.samsara.com/marketplace
      status: profiled
      tags:
      - Commercial Vehicles
      - Fortune 500
      - Manufacturing
      - Trucks
      tier: declared
      url: /providers/navistar-international/
  - capability:
      attribution: Turbo EA
      id: BC-2420.10
      key: dispatch-management
      name: Dispatch Management
      url: /capabilities/dispatch-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.2
      apps:
      - Motive
      band: developing
      in_catalog: true
      kin_score: 43.2
      mcp:
        status: unchecked
      name: HCSS
      slug: hcss
      sources:
      - https://marketplace.gomotive.com/
      status: profiled
      tags:
      - Construction
      - Estimating
      - Project Management
      - Software
      tier: declared
      url: /providers/hcss/
    - agent_band: agent-aware
      agent_readiness: 21.4
      apps:
      - Samsara
      band: minimal
      in_catalog: true
      kin_score: 8.3
      mcp:
        status: unchecked
      name: McLeod LoadMaster
      slug: mcleod-software
      sources:
      - https://www.samsara.com/marketplace
      status: profiled
      tags:
      - Logistics
      - Software
      - TMS
      - Transportation
      tier: declared
      url: /providers/mcleod-software/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Motive
      band: minimal
      in_catalog: true
      kin_score: 7.7
      mcp:
        status: unchecked
      name: AscendTMS
      slug: ascendtms
      sources:
      - https://marketplace.gomotive.com/t/categories/tms
      status: profiled
      tags:
      - Company
      - Logistics
      - Software-as-a-Service
      - Transportation
      tier: declared
      url: /providers/ascendtms/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Motive
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        source: https://docs.alvys.com/en/api/guides/mcp
        status: verified
      name: Alvys
      slug: alvys
      sources:
      - https://marketplace.gomotive.com/t/categories/tms
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/alvys/
  - capability:
      attribution: Turbo EA
      id: BC-2430.20
      key: fleet-maintenance-management
      name: Fleet Maintenance Management
      url: /capabilities/fleet-maintenance-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - Motive
      band: developing
      in_catalog: true
      kin_score: 48.3
      mcp:
        status: none
      name: AMCS Fleet Maintenance
      slug: amcs-group
      sources:
      - https://marketplace.gomotive.com/
      status: profiled
      tags:
      - Company
      - Recycling
      - Transport
      - Waste Management
      tier: declared
      url: /providers/amcs-group/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Motive
      band: emerging
      in_catalog: true
      kin_score: 19.4
      mcp:
        status: unchecked
      name: AUTOsist
      slug: autosist
      sources:
      - https://marketplace.gomotive.com/
      status: profiled
      tags:
      - Fleet Management
      - Maintenance
      - Software
      - Software-as-a-Service
      tier: declared
      url: /providers/autosist/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Samsara
      band: minimal
      in_catalog: true
      kin_score: 2.6
      mcp:
        status: unknown
      name: Penske eDVIR (built by ATI)
      slug: penske
      sources:
      - https://www.samsara.com/marketplace
      status: profiled
      tags:
      - Automotive
      - Logistics
      - Transportation
      - Truck Leasing
      tier: declared
      url: /providers/penske/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.20
      key: AE-120.50.20
      name: Device Positioning
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Traccar
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp: *id001
      name: Google Maps
      slug: google-maps
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geolocation
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-maps/
    - agent_band: agent-aware
      agent_readiness: 21.8
      apps:
      - Traccar
      band: developing
      in_catalog: true
      kin_score: 46.0
      mcp:
        status: none
      name: Unwired Labs (incl. OpenCelliD)
      slug: unwired-labs
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geolocation
      status: profiled
      tags:
      - Company
      - Geolocation
      - Location API
      - Mapping
      tier: observed
      url: /providers/unwired-labs/
  - capability:
      attribution: Turbo EA
      id: BC-2430
      key: fleet-mobile-asset-management
      name: Fleet & Mobile Asset Management
      url: /capabilities/fleet-mobile-asset-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Geotab
      band: minimal
      in_catalog: true
      kin_score: 10.1
      mcp:
        status: unchecked
      name: ORBCOMM (VIACHAIN)
      slug: orbcomm
      sources:
      - https://marketplace.geotab.com/
      status: profiled
      tags:
      - Asset Tracking
      - Connectivity
      - Fleet Management
      - IoT
      tier: declared
      url: /providers/orbcomm/
    - agent_band: null
      agent_readiness: null
      apps:
      - Geotab
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Link Labs (AirFinder)
      slug: link-labs
      sources:
      - https://marketplace.geotab.com/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-2400
      key: freight-capacity-management
      name: Freight Capacity Management
      url: /capabilities/freight-capacity-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.1
      apps:
      - Fleetbase
      band: developing
      in_catalog: true
      kin_score: 44.0
      mcp:
        status: none
      name: Lalamove
      slug: lalamove
      sources:
      - https://github.com/fleetbase/fleetops/tree/main/server/src/Integrations/Lalamove
      status: profiled
      tags:
      - Company
      - Delivery
      - Logistics
      - Technology
      tier: observed
      url: /providers/lalamove/
    - agent_band: agent-aware
      agent_readiness: 27.8
      apps:
      - Motive
      band: thin
      in_catalog: true
      kin_score: 27.1
      mcp:
        status: unchecked
      name: Amazon Relay
      slug: amazon-relay
      sources:
      - https://marketplace.gomotive.com/
      status: profiled
      tags:
      - Company
      - Freight
      - Logistics
      - Transportation
      tier: declared
      url: /providers/amazon-relay/
  - capability:
      attribution: Turbo EA
      id: BC-2130
      key: insurance-underwriting-management
      name: Insurance Underwriting Management
      url: /capabilities/insurance-underwriting-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 13.6
      apps:
      - Samsara
      band: emerging
      in_catalog: true
      kin_score: 14.5
      mcp:
        status: unchecked
      name: Acuity Insurance
      slug: acuity-insurance
      sources:
      - https://www.samsara.com/marketplace
      status: profiled
      tags:
      - Company
      - Insurance
      - Mutual
      - Personal Insurance
      tier: declared
      url: /providers/acuity-insurance/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Samsara
      band: minimal
      in_catalog: true
      kin_score: 4.2
      mcp:
        status: unchecked
      name: Fenchurch General Insurance
      slug: fenchurch-general-insurance
      sources:
      - https://www.samsara.com/marketplace
      status: profiled
      tags:
      - Company
      - Finance
      - General Insurance
      - Insurance
      tier: declared
      url: /providers/fenchurch-general-insurance/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - Fleetbase
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp: *id001
      name: Google Maps Places
      slug: google-maps
      sources:
      - https://github.com/fleetbase/fleetops/blob/main/composer.json
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-maps/
  - capability:
      attribution: Turbo EA
      id: BC-2160
      key: insurance-claims-management
      name: Insurance Claims Management
      url: /capabilities/insurance-claims-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Geotab
      band: minimal
      in_catalog: true
      kin_score: 4.8
      mcp:
        status: unchecked
      name: Xtract360
      slug: xtract360
      sources:
      - https://marketplace.geotab.com/
      status: profiled
      tags:
      - Claims
      - Company
      - Fleet Management
      - Insurance
      tier: declared
      url: /providers/xtract360/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.20
      key: AE-120.30.20
      name: Road Attributes & Speed Limits
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Traccar
      band: emerging
      in_catalog: true
      kin_score: 15.1
      mcp:
        status: unknown
      name: Overpass API
      slug: overpass-api
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/speedlimit
      status: profiled
      tags:
      - GIS
      - Geographic
      - OpenStreetMap
      - Spatial
      tier: observed
      url: /providers/overpass-api/
  - capability:
      attribution: Turbo EA
      id: BC-1050.20
      key: service-dispatch-management
      name: Service Dispatch Management
      url: /capabilities/service-dispatch-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - Motive
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        status: unchecked
      name: Arrivy
      slug: arrivy
      sources:
      - https://marketplace.gomotive.com/t/categories/tms
      status: profiled
      tags:
      - Cloud Platform
      - Company
      - Field Service Management
      - Operations Software
      tier: declared
      url: /providers/arrivy/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: push-notifications
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Fleetbase
      - Traccar
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase Cloud Messaging
      slug: google-firebase
      sources:
      - https://github.com/fleetbase/core-api/blob/main/composer.json
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/notificators
      status: profiled
      tags: &id004
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Fleetbase
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Apple Push Notification service
      slug: apple
      sources:
      - https://github.com/fleetbase/core-api/blob/main/composer.json
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Traccar
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        status: none
      name: Pushover
      slug: pushover
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/notificators
      status: profiled
      tags:
      - Alerts
      - Messaging
      - Notification
      - Push Notifications
      tier: observed
      url: /providers/pushover/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.8
      apps:
      - Traccar
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        status: none
      name: Apache Kafka
      slug: apache-kafka
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/forward
      status: profiled
      tags:
      - Apache Kafka
      - Distributed Systems
      - Event Streaming
      - Messaging
      tier: observed
      url: /providers/apache-kafka/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Traccar
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        status: none
      name: RabbitMQ (AMQP)
      slug: rabbitmq
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/forward
      status: profiled
      tags:
      - AMQP
      - Distributed Systems
      - Queues
      - RabbitMQ
      tier: observed
      url: /providers/rabbitmq/
    - agent_band: agent-aware
      agent_readiness: 16.5
      apps:
      - Traccar
      band: emerging
      in_catalog: true
      kin_score: 15.4
      mcp:
        status: none
      name: MQTT
      slug: mqtt
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/forward
      status: profiled
      tags:
      - IoT
      - MQTT
      - Messaging
      - Publish Subscribe
      tier: observed
      url: /providers/mqtt/
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
      - Fleetbase
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/fleetbase/core-api/blob/main/composer.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Traccar
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id003
      name: Firebase Analytics / Crashlytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/org.traccar.client/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20
      key: sms-messaging-apps
      name: SMS & Messaging Apps
      url: /capabilities/sms-messaging-apps/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - Fleetbase
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/fleetbase/core-api/blob/main/composer.json
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-ready
      agent_readiness: 41.7
      apps:
      - Traccar
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SNS
      slug: amazon-sns
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/sms
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Messaging
      - Notification
      tier: observed
      url: /providers/amazon-sns/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Traccar
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp
      slug: whatsapp
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/notificators
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: observed
      url: /providers/whatsapp/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Traccar
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/notificators
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Fleetbase
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/fleetbase/core-api/blob/main/composer.json
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.8
      apps:
      - Motive
      band: developing
      in_catalog: true
      kin_score: 45.6
      mcp:
        status: none
      name: ADP
      slug: adp
      sources:
      - https://marketplace.gomotive.com/
      status: profiled
      tags:
      - Benefits
      - HCM
      - Human Resources
      - Payroll
      tier: declared
      url: /providers/adp/
  - capability:
      attribution: Turbo EA
      id: BC-620.20
      key: identity-access-management
      name: Identity & Access Management
      url: /capabilities/identity-access-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.5
      apps:
      - Motive
      band: exemplar
      in_catalog: true
      kin_score: 71.8
      mcp:
        source: https://auth0.com/docs/get-started/auth0-mcp-server
        status: verified
      name: Auth0 Single Sign-On
      slug: auth0
      sources:
      - https://marketplace.gomotive.com/
      status: profiled
      tags:
      - AI Agents
      - Auth0
      - Authentication
      - Authorization
      tier: declared
      url: /providers/auth0/
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - Motive
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/Airtable/airtable-mcp-cli
        status: verified
      name: Airtable
      slug: airtable
      sources:
      - https://marketplace.gomotive.com/
      status: profiled
      tags:
      - Application
      - Collaboration
      - Data
      - Database
      tier: declared
      url: /providers/airtable/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.0
      apps:
      - Fleetbase
      band: exemplar
      in_catalog: true
      kin_score: 69.7
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph (mail)
      slug: microsoft-graph
      sources:
      - https://github.com/fleetbase/core-api/blob/main/composer.json
      status: profiled
      tags:
      - Azure AD
      - Collaboration
      - Contacts
      - Microsoft Graph
      tier: observed
      url: /providers/microsoft-graph/
  - capability:
      attribution: Turbo EA
      id: BC-4270.80
      key: webhook-event-subscription-management
      name: Webhook & Event Subscription Management
      url: /capabilities/webhook-event-subscription-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.5
      apps:
      - Traccar
      band: developing
      in_catalog: true
      kin_score: 46.5
      mcp:
        source: https://github.com/redis/mcp-redis
        status: verified
      name: Redis
      slug: redis
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/forward
      status: profiled
      tags:
      - Cache
      - Database
      - In-Memory
      - Key-Value Store
      tier: observed
      url: /providers/redis/
  layer: common
summary:
  coverage_pct: 96.5
  declared_only: 39
  distinct_providers: 86
  in_catalog: 83
  mcp:
    documented: 2
    none: 29
    unchecked: 29
    verified: 17
  mcp_verified: 17
  mean_kin_score: 30.0
  observed: 47
  queued: 3
  reference_apps: 6
title: 'Fleet Management & Telematics: application blueprint'
---
