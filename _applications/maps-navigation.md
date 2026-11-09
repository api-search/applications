---
access: understanding
agent_layer: []
apps:
- anchor: traccar
  counts:
    declared: 0
    observed: 31
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
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
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
      id: AE-120.50.20
      key: AE-120.50.20
      name: Device Positioning
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
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
    layer: common
    name: WhatsApp
    provider: whatsapp
    says: ships the WhatsApp SDK or integration code
    source: https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/notificators
    tier: observed
  kind: self-hosted
  name: Traccar
  page: /applications/maps-navigation/traccar/
  slug: traccar
  url: https://github.com/traccar/traccar
- anchor: organic-maps
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/app.organicmaps/latest/
  - route: dependency manifest
    url: https://github.com/organicmaps/organicmaps/blob/master/android/gradle/libs.versions.toml
  - route: documentation
    url: https://github.com/organicmaps/organicmaps/blob/master/docs/CREDENTIALS.md
  - route: source code
    url: https://github.com/organicmaps/organicmaps/blob/master/android/app/src/main/res/layout/place_page_wikipedia_fragment.xml
  - route: source code
    url: https://github.com/organicmaps/organicmaps/blob/master/private.h
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Firebase Crashlytics
    provider: firebase
    says: ships the Firebase Crashlytics SDK or integration code
    source: https://github.com/organicmaps/organicmaps/blob/master/android/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.20
      key: AE-120.50.20
      name: Device Positioning
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    credit: null
    layer: common
    name: Google Play services location
    provider: google
    says: ships the Google Play services location SDK or integration code
    source: https://github.com/organicmaps/organicmaps/blob/master/android/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-210.20.10
      key: AE-210.20.10
      name: Hotel Booking
      url: /capabilities/lodging-stays/
      via_parent: Lodging & Stays
    credit: null
    layer: domain
    name: Kayak
    provider: kayak
    says: ships the Kayak SDK or integration code
    source: https://github.com/organicmaps/organicmaps/blob/master/private.h
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.80
      key: AE-120.80
      name: Map Data Contribution & Editing
      url: /capabilities/map-data-contribution-editing/
      via_parent: null
    credit: null
    layer: domain
    name: OpenStreetMap
    provider: openstreetmap
    says: ships the OpenStreetMap SDK or integration code
    source: https://github.com/organicmaps/organicmaps/blob/master/private.h
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40.20
      key: AE-120.40.20
      name: Place Content & Descriptions
      url: /capabilities/places-points-of-interest/
      via_parent: Places & Points of Interest
    credit: null
    layer: domain
    name: Wikipedia
    provider: wikipedia
    says: ships the Wikipedia SDK or integration code
    source: https://github.com/organicmaps/organicmaps/blob/master/android/app/src/main/res/layout/place_page_wikipedia_fragment.xml
    tier: observed
  kind: open-source-saas
  name: Organic Maps
  page: /applications/maps-navigation/organic-maps/
  slug: organic-maps
  url: https://github.com/organicmaps/organicmaps
- anchor: osmand
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/net.osmand/latest/
  - route: dependency manifest
    url: https://github.com/osmandapp/OsmAnd/blob/master/OsmAnd/build-common.gradle
  - route: source code
    url: https://github.com/osmandapp/OsmAnd/tree/master/OsmAnd/src/net/osmand/plus/plugins
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: common
    name: Google Play Billing
    provider: google-play
    says: ships the Google Play Billing SDK or integration code
    source: https://github.com/osmandapp/OsmAnd/blob/master/OsmAnd/build-common.gradle
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.40
      key: AE-120.20.40
      name: Street-Level Imagery
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: Mapillary
    provider: mapillary
    says: ships the Mapillary SDK or integration code
    source: https://github.com/osmandapp/OsmAnd/tree/master/OsmAnd/src/net/osmand/plus/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.80
      key: AE-120.80
      name: Map Data Contribution & Editing
      url: /capabilities/map-data-contribution-editing/
      via_parent: null
    credit: null
    layer: domain
    name: OpenStreetMap
    provider: openstreetmap
    says: ships the OpenStreetMap SDK or integration code
    source: https://github.com/osmandapp/OsmAnd/tree/master/OsmAnd/src/net/osmand/plus/plugins
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.40
      key: AE-120.20.40
      name: Street-Level Imagery
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: Panoramax
    provider: panoramax
    says: ships the Panoramax SDK or integration code
    source: https://github.com/osmandapp/OsmAnd/tree/master/OsmAnd/src/net/osmand/plus/plugins
    tier: observed
  kind: open-source-saas
  name: OsmAnd
  page: /applications/maps-navigation/osmand/
  slug: osmand
  url: https://github.com/osmandapp/OsmAnd
- anchor: dawarich
  counts:
    declared: 6
    observed: 8
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
    layer: domain
    name: Strava
    provider: strava
    says: lists Strava as an integration
    source: https://github.com/Freika/dawarich/blob/master/README.md
    tier: declared
  kind: self-hosted
  name: Dawarich
  page: /applications/maps-navigation/dawarich/
  slug: dawarich
  url: https://github.com/Freika/dawarich
- anchor: headway
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: documentation
    url: https://github.com/headwaymaps/headway/blob/main/README.md
  - route: source code
    url: https://github.com/headwaymaps/headway/tree/main/services
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: domain
    name: OpenStreetMap
    provider: openstreetmap
    says: ships the OpenStreetMap SDK or integration code
    source: https://github.com/headwaymaps/headway/tree/main/services
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.30
      key: AE-120.30.30
      name: Transit Routing
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    credit: null
    layer: domain
    name: OpenTripPlanner
    provider: opentripplanner
    says: ships the OpenTripPlanner SDK or integration code
    source: https://github.com/headwaymaps/headway/tree/main/services
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
    name: Pelias
    provider: pelias
    says: ships the Pelias SDK or integration code
    source: https://github.com/headwaymaps/headway/tree/main/services
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.10
      key: AE-120.30.10
      name: Turn-by-Turn Directions
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    credit: null
    layer: domain
    name: Valhalla
    provider: valhalla
    says: ships the Valhalla SDK or integration code
    source: https://github.com/headwaymaps/headway/tree/main/services
    tier: observed
  kind: self-hosted
  name: Headway
  page: /applications/maps-navigation/headway/
  slug: headway
  url: https://github.com/headwaymaps/headway
- anchor: komoot
  counts:
    declared: 2
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/de.komoot.android/latest/
  - route: integrations page
    url: https://www.komoot.com/connect
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook Analytics
    provider: facebook
    says: ships the Facebook Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/de.komoot.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook Login / Share
    provider: facebook
    says: ships the Facebook Login / Share SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/de.komoot.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase (Crashlytics / Analytics)
    provider: firebase
    says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/de.komoot.android/latest/
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
    name: Garmin
    provider: garmin
    says: lists Garmin as an integration
    source: https://www.komoot.com/connect
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Wahoo Fitness
    provider: wahoo
    says: lists Wahoo Fitness as an integration
    source: https://www.komoot.com/connect
    tier: declared
  kind: commercial
  name: komoot
  page: /applications/maps-navigation/komoot/
  slug: komoot
  url: https://www.komoot.com/
- anchor: google-maps
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.google.android.apps.maps/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.google.android.apps.maps/latest/
    tier: observed
  kind: commercial
  name: Google Maps
  page: /applications/maps-navigation/google-maps/
  slug: google-maps
  url: https://maps.google.com/
- anchor: waze
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.waze/latest/
  - route: documentation
    url: https://support.google.com/waze/answer/7329233?hl=en
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase (Crashlytics)
    provider: firebase
    says: ships the Firebase (Crashlytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.waze/latest/
    tier: observed
  kind: commercial
  name: Waze
  page: /applications/maps-navigation/waze/
  slug: waze
  url: https://www.waze.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: maps-navigation
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Navigation
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Maps & Navigation
  store: google-play
  url: https://play.google.com/store/apps/category/MAPS_AND_NAVIGATION
- category: Maps and Global Positioning System (GPS)
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#maps-and-global-positioning-system-gps
name: Maps, Navigation & GPS
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: domain
  why: turn GPS fixes and pins into addresses
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: domain
  why: search for addresses and places
- capability:
    attribution: API Evangelist extension
    id: AE-120.30.10
    key: AE-120.30.10
    name: Turn-by-Turn Directions
    url: /capabilities/routing-navigation/
    via_parent: Routing & Navigation
  fit: exact
  layer: domain
  why: routing is the category
- capability:
    attribution: API Evangelist extension
    id: AE-120.30.20
    key: AE-120.30.20
    name: Road Attributes & Speed Limits
    url: /capabilities/routing-navigation/
    via_parent: Routing & Navigation
  fit: exact
  layer: domain
  why: road attributes such as speed limits
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: nearest
  layer: domain
  why: the map itself
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.40
    key: AE-120.20.40
    name: Street-Level Imagery
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: domain
  why: street-level imagery layers (gap)
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.20
    key: AE-120.50.20
    name: Device Positioning
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: domain
  why: fused/cell/Wi-Fi location and tracker clients
- capability:
    attribution: API Evangelist extension
    id: AE-120.40.20
    key: AE-120.40.20
    name: Place Content & Descriptions
    url: /capabilities/places-points-of-interest/
    via_parent: Places & Points of Interest
  fit: exact
  layer: domain
  why: place pages enriched with encyclopedia text
- capability:
    attribution: API Evangelist extension
    id: AE-120.80
    key: AE-120.80
    name: Map Data Contribution & Editing
    url: /capabilities/map-data-contribution-editing/
    via_parent: null
  fit: exact
  layer: domain
  why: map-data editing and location-history import (gap)
- capability:
    attribution: API Evangelist extension
    id: AE-120.30.30
    key: AE-120.30.30
    name: Transit Routing
    url: /capabilities/routing-navigation/
    via_parent: Routing & Navigation
  fit: exact
  layer: domain
  why: transit directions
- capability:
    attribution: API Evangelist extension
    id: AE-210.20.10
    key: AE-210.20.10
    name: Hotel Booking
    url: /capabilities/lodging-stays/
    via_parent: Lodging & Stays
  fit: exact
  layer: domain
  why: affiliate hotel links on places
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.30
    key: AE-130.10.30
    name: Running & Cycling Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  fit: exact
  layer: domain
  why: activity imports for outdoor navigation
- capability:
    attribution: API Evangelist extension
    id: AE-130.20
    key: AE-130.20
    name: Wearable & Health Data Sync
    url: /capabilities/wearable-health-data-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: route sync to GPS devices
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: domain
  why: geotagged photos on the timeline
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: alerts to devices
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: alerts via messaging apps
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
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash and error reporting
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: sign-in
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: stored imports and exports
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: common
  why: paid map features
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: in-app usage analytics SDKs named in Exodus reports
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
    - agent_band: agent-ready
      agent_readiness: 44.3
      apps:
      - Dawarich
      - Traccar
      band: strong
      in_catalog: true
      kin_score: 60.3
      mcp:
        status: none
      name: Geoapify
      slug: geoapify
      sources:
      - https://github.com/Freika/dawarich/blob/master/config/initializers/geocoder.rb
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Location
      - Maps
      tier: observed
      url: /providers/geoapify/
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - Dawarich
      - Traccar
      band: developing
      in_catalog: true
      kin_score: 42.4
      mcp:
        status: none
      name: Nominatim
      slug: nominatim
      sources:
      - https://github.com/Freika/dawarich/blob/master/config/initializers/geocoder.rb
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Geocoding
      - Location Services
      - Maps
      - OpenStreetMap
      tier: observed
      url: /providers/nominatim/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Dawarich
      - Traccar
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: none
      name: LocationIQ
      slug: locationiq
      sources:
      - https://github.com/Freika/dawarich/blob/master/config/initializers/geocoder.rb
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Public APIs
      tier: observed
      url: /providers/locationiq/
    - agent_band: agent-native
      agent_readiness: 55.5
      apps:
      - Traccar
      band: exemplar
      in_catalog: true
      kin_score: 77.6
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
      agent_readiness: 36.0
      apps:
      - Traccar
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp: &id001
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps Platform
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
      agent_readiness: 29.5
      apps:
      - Traccar
      band: strong
      in_catalog: true
      kin_score: 60.4
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
      agent_readiness: 45.8
      apps:
      - Traccar
      band: developing
      in_catalog: true
      kin_score: 49.3
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
      agent_readiness: 36.1
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
      agent_readiness: 26.5
      apps:
      - Traccar
      band: developing
      in_catalog: true
      kin_score: 40.3
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
    - agent_band: agent-ready
      agent_readiness: 28.9
      apps:
      - Traccar
      band: thin
      in_catalog: true
      kin_score: 36.2
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
      agent_readiness: 15.1
      apps:
      - Traccar
      band: thin
      in_catalog: true
      kin_score: 34.0
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
      agent_readiness: 5.8
      apps:
      - Traccar
      band: thin
      in_catalog: true
      kin_score: 29.7
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
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - Traccar
      band: thin
      in_catalog: true
      kin_score: 27.8
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
    - agent_band: agent-aware
      agent_readiness: 6.0
      apps:
      - Traccar
      band: emerging
      in_catalog: true
      kin_score: 18.5
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
      agent_readiness: 2.5
      apps:
      - Dawarich
      band: minimal
      in_catalog: true
      kin_score: 9.0
      mcp:
        status: none
      name: Photon (komoot)
      slug: komoot-photon
      sources:
      - https://github.com/Freika/dawarich/blob/master/config/initializers/geocoder.rb
      status: profiled
      tags:
      - Geocoding
      - OpenStreetMap
      - Search
      - Typeahead
      tier: observed
      url: /providers/komoot-photon/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Traccar
      band: minimal
      in_catalog: true
      kin_score: 7.9
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
      agent_readiness: 2.9
      apps:
      - Traccar
      band: minimal
      in_catalog: true
      kin_score: 7.2
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
      kin_score: 5.6
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
      kin_score: 5.2
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
    - agent_band: null
      agent_readiness: null
      apps:
      - Traccar
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: AutoNavi (Amap)
      slug: autonavi
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Traccar
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Base Adresse Nationale (BAN)
      slug: base-adresse-nationale
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: null
      agent_readiness: null
      apps:
      - Traccar
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Tencent Location Service
      slug: tencent-maps
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geocoder
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.20
      key: AE-120.50.20
      name: Device Positioning
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - Traccar
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp: *id001
      name: Google Maps Platform
      slug: google-maps
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geolocation
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-maps/
    - agent_band: agent-aware
      agent_readiness: 22.2
      apps:
      - Traccar
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        status: none
      name: Unwired Labs
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
    - agent_band: null
      agent_readiness: null
      apps:
      - Traccar
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: OpenCelliD
      slug: opencellid
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/geolocation
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: human-only
      agent_readiness: 3.2
      apps:
      - Dawarich
      band: minimal
      in_catalog: true
      kin_score: 9.5
      mcp:
        status: unknown
      name: Overland
      slug: overland
      sources:
      - https://github.com/Freika/dawarich/blob/master/README.md
      status: profiled
      tags:
      - GPS
      - Location Tracking
      - Open Source
      - iOS
      tier: declared
      url: /providers/overland/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Dawarich
      band: minimal
      in_catalog: true
      kin_score: 4.4
      mcp:
        status: none
      name: OwnTracks
      slug: owntracks
      sources:
      - https://github.com/Freika/dawarich/blob/master/README.md
      status: profiled
      tags:
      - Company
      - Location Tracking
      - Open Source
      - Privacy
      tier: declared
      url: /providers/owntracks/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.80
      key: AE-120.80
      name: Map Data Contribution & Editing
      url: /capabilities/map-data-contribution-editing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - Organic Maps
      - OsmAnd
      band: developing
      in_catalog: true
      kin_score: 44.4
      mcp: &id003
        status: none
      name: OpenStreetMap
      slug: openstreetmap
      sources:
      - https://github.com/organicmaps/organicmaps/blob/master/private.h
      - https://github.com/osmandapp/OsmAnd/tree/master/OsmAnd/src/net/osmand/plus/plugins
      status: profiled
      tags: &id004
      - Geocoding
      - Geospatial
      - Mapping
      - Open Data
      tier: observed
      url: /providers/openstreetmap/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Dawarich
      band: developing
      in_catalog: true
      kin_score: 42.5
      mcp:
        source: https://docs.photoprism.app/developer-guide/api/mcp/
        status: verified
      name: PhotoPrism
      slug: photoprism
      sources:
      - https://github.com/Freika/dawarich/blob/master/README.md
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Photo Management
      - Self-Hosted
      tier: declared
      url: /providers/photoprism/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Dawarich
      band: emerging
      in_catalog: true
      kin_score: 22.3
      mcp:
        status: none
      name: Immich
      slug: immich
      sources:
      - https://github.com/Freika/dawarich/blob/master/README.md
      status: profiled
      tags:
      - Photo Management
      - Privacy
      - Self-Hosted
      - Video Management
      tier: declared
      url: /providers/immich/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.40
      key: AE-120.20.40
      name: Street-Level Imagery
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - OsmAnd
      band: minimal
      in_catalog: true
      kin_score: 9.7
      mcp:
        status: none
      name: Panoramax
      slug: panoramax
      sources:
      - https://github.com/osmandapp/OsmAnd/tree/master/OsmAnd/src/net/osmand/plus/plugins
      status: profiled
      tags:
      - Company
      - Mapping
      - Open Data
      - Photography
      tier: observed
      url: /providers/panoramax/
    - agent_band: null
      agent_readiness: null
      apps:
      - OsmAnd
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Mapillary
      slug: mapillary
      sources:
      - https://github.com/osmandapp/OsmAnd/tree/master/OsmAnd/src/net/osmand/plus/plugins
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-130.20
      key: AE-130.20
      name: Wearable & Health Data Sync
      url: /capabilities/wearable-health-data-sync/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.6
      apps:
      - komoot
      band: developing
      in_catalog: true
      kin_score: 46.5
      mcp:
        status: none
      name: Wahoo Fitness
      slug: wahoo
      sources:
      - https://www.komoot.com/connect
      status: profiled
      tags:
      - Bike Computers
      - Cycling
      - Endurance Training
      - Fitness
      tier: declared
      url: /providers/wahoo/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - komoot
      band: emerging
      in_catalog: true
      kin_score: 21.4
      mcp:
        status: none
      name: Garmin
      slug: garmin
      sources:
      - https://www.komoot.com/connect
      status: profiled
      tags:
      - Fitness
      - GPS
      - Outdoor
      - Wearables
      tier: declared
      url: /providers/garmin/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - Headway
      band: developing
      in_catalog: true
      kin_score: 44.4
      mcp: *id003
      name: OpenStreetMap
      slug: openstreetmap
      sources:
      - https://github.com/headwaymaps/headway/tree/main/services
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/openstreetmap/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.6
      apps:
      - Headway
      band: emerging
      in_catalog: true
      kin_score: 23.8
      mcp:
        status: none
      name: Pelias
      slug: pelias
      sources:
      - https://github.com/headwaymaps/headway/tree/main/services
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Open Source
      - Reverse Geocoding
      tier: observed
      url: /providers/pelias/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.20.10
      key: AE-210.20.10
      name: Hotel Booking
      url: /capabilities/lodging-stays/
      via_parent: Lodging & Stays
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Organic Maps
      band: emerging
      in_catalog: true
      kin_score: 20.5
      mcp:
        status: none
      name: Kayak
      slug: kayak
      sources:
      - https://github.com/organicmaps/organicmaps/blob/master/private.h
      status: profiled
      tags:
      - Company
      - Flights
      - Metasearch
      - Travel
      tier: observed
      url: /providers/kayak/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.30
      key: AE-120.50.30
      name: Location History & Timeline
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.5
      apps:
      - Dawarich
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp: &id009
        source: https://github.com/google/mcp
        status: verified
      name: Google Maps Timeline / Takeout
      slug: google
      sources:
      - https://github.com/Freika/dawarich/blob/master/README.md
      status: profiled
      tags: &id010
      - Advertising
      - Cloud
      - Developers
      - Google
      tier: declared
      url: /providers/google/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40.20
      key: AE-120.40.20
      name: Place Content & Descriptions
      url: /capabilities/places-points-of-interest/
      via_parent: Places & Points of Interest
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.8
      apps:
      - Organic Maps
      band: developing
      in_catalog: true
      kin_score: 43.0
      mcp:
        status: none
      name: Wikipedia
      slug: wikipedia
      sources:
      - https://github.com/organicmaps/organicmaps/blob/master/android/app/src/main/res/layout/place_page_wikipedia_fragment.xml
      status: profiled
      tags:
      - Encyclopedia
      - Open Data
      - Open Knowledge
      - Public APIs
      tier: observed
      url: /providers/wikipedia/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.20
      key: AE-120.30.20
      name: Road Attributes & Speed Limits
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - Traccar
      band: developing
      in_catalog: true
      kin_score: 44.4
      mcp: *id003
      name: OpenStreetMap (Overpass API)
      slug: openstreetmap
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/speedlimit
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/openstreetmap/
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.30
      key: AE-130.10.30
      name: Running & Cycling Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Dawarich
      band: developing
      in_catalog: true
      kin_score: 50.0
      mcp:
        status: none
      name: Strava
      slug: strava
      sources:
      - https://github.com/Freika/dawarich/blob/master/README.md
      status: profiled
      tags:
      - Cycling
      - Fitness
      - Fitness Tracking
      - Running
      tier: declared
      url: /providers/strava/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.30
      key: AE-120.30.30
      name: Transit Routing
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Headway
      band: minimal
      in_catalog: true
      kin_score: 4.9
      mcp:
        status: none
      name: OpenTripPlanner
      slug: opentripplanner
      sources:
      - https://github.com/headwaymaps/headway/tree/main/services
      status: profiled
      tags:
      - Multi-Modal
      - Open Source
      - Routing
      - Transportation
      tier: observed
      url: /providers/opentripplanner/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.10
      key: AE-120.30.10
      name: Turn-by-Turn Directions
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.9
      apps:
      - Headway
      band: emerging
      in_catalog: true
      kin_score: 25.7
      mcp:
        status: none
      name: Valhalla
      slug: valhalla
      sources:
      - https://github.com/headwaymaps/headway/tree/main/services
      status: profiled
      tags:
      - Mapping
      - Navigation
      - OpenStreetMap
      - Routing
      tier: observed
      url: /providers/valhalla/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Google Maps
      - Traccar
      - komoot
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id005
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase (Crashlytics / Analytics)
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.google.android.apps.maps/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/de.komoot.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/org.traccar.client/latest/
      status: profiled
      tags: &id006
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - komoot
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp: &id007
        status: none
      name: Facebook Analytics
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/de.komoot.android/latest/
      status: profiled
      tags: &id008
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Organic Maps
      - Waze
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id005
      name: Firebase Crashlytics
      slug: firebase
      sources:
      - https://github.com/organicmaps/organicmaps/blob/master/android/gradle/libs.versions.toml
      - https://reports.exodus-privacy.eu.org/en/reports/com.waze/latest/
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Dawarich
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/Freika/dawarich/blob/master/Gemfile
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
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - Dawarich
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/Freika/dawarich/blob/master/Gemfile
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - komoot
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp: *id007
      name: Facebook Login / Share
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/de.komoot.android/latest/
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Dawarich
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/Freika/dawarich/blob/master/Gemfile
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Traccar
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id005
      name: Firebase Cloud Messaging
      slug: firebase
      sources:
      - https://github.com/traccar/traccar/tree/master/src/main/java/org/traccar/notificators
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-aware
      agent_readiness: 22.0
      apps:
      - Traccar
      band: thin
      in_catalog: true
      kin_score: 29.2
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
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.0
      apps:
      - Traccar
      band: exemplar
      in_catalog: true
      kin_score: 68.0
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
      agent_readiness: 25.4
      apps:
      - Traccar
      band: strong
      in_catalog: true
      kin_score: 58.4
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
      id: AE-120.50.20
      key: AE-120.50.20
      name: Device Positioning
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.5
      apps:
      - Organic Maps
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp: *id009
      name: Google Play services location
      slug: google
      sources:
      - https://github.com/organicmaps/organicmaps/blob/master/android/gradle/libs.versions.toml
      status: profiled
      tags: *id010
      tier: observed
      url: /providers/google/
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - OsmAnd
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        status: none
      name: Google Play Billing
      slug: google-play
      sources:
      - https://github.com/osmandapp/OsmAnd/blob/master/OsmAnd/build-common.gradle
      status: profiled
      tags:
      - Android
      - Application
      - Google Play
      - In-App Purchases
      tier: observed
      url: /providers/google-play/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - Traccar
      band: strong
      in_catalog: true
      kin_score: 55.5
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
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Dawarich
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/Freika/dawarich/blob/master/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
  layer: common
summary:
  coverage_pct: 90.2
  declared_only: 7
  distinct_providers: 51
  in_catalog: 46
  mcp:
    documented: 0
    none: 31
    unchecked: 5
    verified: 12
  mcp_verified: 12
  mean_kin_score: 37.5
  observed: 44
  queued: 5
  reference_apps: 8
title: 'Maps, Navigation & GPS: application blueprint'
---
