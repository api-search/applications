---
access: understanding
agent_layer: []
apps:
- anchor: opentripplanner
  counts:
    declared: 0
    observed: 9
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
    layer: domain
    name: Uber
    provider: uber
    says: ships the Uber SDK or integration code
    source: https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/application/src/ext/java/org/opentripplanner/ext/ridehailing/service
    tier: observed
  kind: self-hosted
  name: OpenTripPlanner
  page: /applications/public-transit/opentripplanner/
  slug: opentripplanner
  url: https://github.com/opentripplanner/OpenTripPlanner
- anchor: motis-(transitous)
  counts:
    declared: 6
    observed: 1
  evidence:
  - route: documentation
    url: https://github.com/motis-project/motis/blob/master/docs/setup.md
  - route: source code
    url: https://github.com/motis-project/motis/tree/master/src/elevators
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.40
      key: AE-210.30.40
      name: Public Transit Data
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Deutsche Bahn (FaSta)
    provider: deutsche-bahn
    says: ships the Deutsche Bahn (FaSta) SDK or integration code
    source: https://github.com/motis-project/motis/tree/master/src/elevators
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.50
      key: AE-210.30.50
      name: Micromobility & Bike Share
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: BIXI Montreal
    provider: bixi
    says: lists BIXI Montreal as an integration
    source: https://github.com/motis-project/motis/blob/master/docs/setup.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.50
      key: AE-210.30.50
      name: Micromobility & Bike Share
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: MobiData BW
    provider: mobidata-bw
    says: lists MobiData BW as an integration
    source: https://github.com/motis-project/motis/blob/master/docs/setup.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.50
      key: AE-210.30.50
      name: Micromobility & Bike Share
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: nextbike
    provider: nextbike
    says: lists nextbike as an integration
    source: https://github.com/motis-project/motis/blob/master/docs/setup.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-120
      key: location-mapping
      name: Location & Mapping
      url: /capabilities/location-mapping/
      via_parent: null
    credit: null
    layer: domain
    name: OpenStreetMap
    provider: openstreetmap
    says: lists OpenStreetMap as an integration
    source: https://github.com/motis-project/motis/blob/master/docs/setup.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.40
      key: AE-210.30.40
      name: Public Transit Data
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: opentransportdata.swiss
    provider: opentransportdata-swiss
    says: lists opentransportdata.swiss as an integration
    source: https://github.com/motis-project/motis/blob/master/docs/setup.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.40
      key: AE-210.30.40
      name: Public Transit Data
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: OVapi
    provider: ovapi
    says: lists OVapi as an integration
    source: https://github.com/motis-project/motis/blob/master/docs/setup.md
    tier: declared
  kind: self-hosted
  name: MOTIS (Transitous)
  page: /applications/public-transit/motis-transitous/
  slug: motis-transitous
  url: https://github.com/motis-project/motis
- anchor: onebusaway-android
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://github.com/OneBusAway/onebusaway-android/blob/master/gradle/libs.versions.toml
  - route: dependency manifest
    url: https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
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
    source: https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
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
    name: Firebase Crashlytics
    provider: firebase
    says: ships the Firebase Crashlytics SDK or integration code
    source: https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: Google Maps Platform
    provider: google-maps
    says: ships the Google Maps Platform SDK or integration code
    source: https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: MapLibre
    provider: maplibre
    says: ships the MapLibre SDK or integration code
    source: https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.40
      key: AE-210.30.40
      name: Public Transit Data
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: MobilityData
    provider: mobilitydata
    says: ships the MobilityData SDK or integration code
    source: https://github.com/OneBusAway/onebusaway-android/blob/master/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: Pelias
    provider: pelias
    says: ships the Pelias SDK or integration code
    source: https://github.com/OneBusAway/onebusaway-android/blob/master/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Plausible
    provider: plausible
    says: ships the Plausible SDK or integration code
    source: https://github.com/OneBusAway/onebusaway-android/blob/master/gradle/libs.versions.toml
    tier: observed
  kind: self-hosted
  name: OneBusAway Android
  page: /applications/public-transit/onebusaway-android/
  slug: onebusaway-android
  url: https://github.com/OneBusAway/onebusaway-android
- anchor: transit
  counts:
    declared: 6
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.thetransitapp.droid/latest/
  - route: integrations page
    url: https://resources.transitapp.com/article/403-ridehail-and-taxi
  - route: integrations page
    url: https://transitapp.com/partners
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
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.thetransitapp.droid/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.thetransitapp.droid/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.thetransitapp.droid/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Curb
    provider: curb-mobility
    says: lists Curb as an integration
    source: https://resources.transitapp.com/article/403-ridehail-and-taxi
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: iCabbi
    provider: icabbi
    says: lists iCabbi as an integration
    source: https://resources.transitapp.com/article/403-ridehail-and-taxi
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Lyft
    provider: lyft
    says: lists Lyft as an integration
    source: https://resources.transitapp.com/article/403-ridehail-and-taxi
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Ola
    provider: ola
    says: lists Ola as an integration
    source: https://resources.transitapp.com/article/403-ridehail-and-taxi
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Uber
    provider: uber
    says: lists Uber as an integration
    source: https://resources.transitapp.com/article/403-ridehail-and-taxi
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Via
    provider: via-transportation
    says: lists Via as an integration
    source: https://resources.transitapp.com/article/403-ridehail-and-taxi
    tier: declared
  kind: commercial
  name: Transit
  page: /applications/public-transit/transit/
  slug: transit
  url: https://transitapp.com/
- anchor: citymapper
  counts:
    declared: 9
    observed: 14
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
  - route: integrations page
    url: https://citymapper.com/partners
  - route: store listing
    url: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amazon
    provider: amazon
    says: ships the Amazon SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AppLovin
    provider: applovin
    says: ships the AppLovin SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2120.40
      key: customer-information-consent-management
      name: Customer Information & Consent Management
      url: /capabilities/customer-information-consent-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Didomi
    provider: didomi
    says: ships the Didomi SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google AdMob
    provider: google-admob
    says: ships the Google AdMob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: IAB Open Measurement
    provider: iab-tech-lab
    says: ships the IAB Open Measurement SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: InMobi
    provider: inmobi
    says: ships the InMobi SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
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
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: PubMatic
    provider: pubmatic
    says: ships the PubMatic SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50.10
      key: AE-210.50.10
      name: Mobile Tickets & Wallet Passes
      url: /capabilities/event-ticketing/
      via_parent: Event Ticketing
    credit: null
    layer: common
    name: Apple Wallet
    provider: apple
    says: lists Apple Wallet as an integration
    source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.50
      key: AE-210.30.50
      name: Micromobility & Bike Share
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: BCycle
    provider: bcycle
    says: lists BCycle as an integration
    source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.50
      key: AE-210.30.50
      name: Micromobility & Bike Share
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Bird
    provider: bird-rides
    says: lists Bird as an integration
    source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.50
      key: AE-210.30.50
      name: Micromobility & Bike Share
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Lime
    provider: lime
    says: lists Lime as an integration
    source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Lyft
    provider: lyft
    says: lists Lyft as an integration
    source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.50
      key: AE-210.30.50
      name: Micromobility & Bike Share
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Lyft bikeshare systems
    provider: lyft
    says: lists Lyft bikeshare systems as an integration
    source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.50
      key: AE-210.30.50
      name: Micromobility & Bike Share
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Skip
    provider: skip-scooters
    says: lists Skip as an integration
    source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.50
      key: AE-210.30.50
      name: Micromobility & Bike Share
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Spin
    provider: spin-scooters
    says: lists Spin as an integration
    source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Uber
    provider: uber
    says: lists Uber as an integration
    source: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
    tier: declared
  kind: commercial
  name: Citymapper
  page: /applications/public-transit/citymapper/
  slug: citymapper
  url: https://citymapper.com/
- anchor: moovit
  counts:
    declared: 3
    observed: 14
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
  - route: integrations page
    url: https://moovit.com/partners/
  - route: store listing
    url: https://apps.apple.com/us/app/moovit-all-transit-options/id498477945
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Appodeal
    provider: appodeal
    says: ships the Appodeal SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: AppsFlyer
    provider: appsflyer
    says: ships the AppsFlyer SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: BidMachine
    provider: bidmachine-io
    says: ships the BidMachine SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2820.10
      key: referral-management
      name: Referral Management
      url: /capabilities/referral-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Button
    provider: usebutton
    says: ships the Button SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120
      key: location-mapping
      name: Location & Mapping
      url: /capabilities/location-mapping/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Carto
    provider: carto
    says: ships the Carto SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Digital Turbine (Fyber)
    provider: digital-turbine
    says: ships the Digital Turbine (Fyber) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google AdMob
    provider: google-admob
    says: ships the Google AdMob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: IAB Open Measurement
    provider: iab-tech-lab
    says: ships the IAB Open Measurement SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50.10
      key: AE-210.50.10
      name: Mobile Tickets & Wallet Passes
      url: /capabilities/event-ticketing/
      via_parent: Event Ticketing
    credit: null
    layer: common
    name: Apple Wallet
    provider: apple
    says: lists Apple Wallet as an integration
    source: https://apps.apple.com/us/app/moovit-all-transit-options/id498477945
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Lyft
    provider: lyft
    says: lists Lyft as an integration
    source: https://apps.apple.com/us/app/moovit-all-transit-options/id498477945
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: Uber
    provider: uber
    says: lists Uber as an integration
    source: https://apps.apple.com/us/app/moovit-all-transit-options/id498477945
    tier: declared
  kind: commercial
  name: Moovit
  page: /applications/public-transit/moovit/
  slug: moovit
  url: https://moovit.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: public-transit
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Navigation
  store: apple-app-store
  url: https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
- category: Travel
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Maps & Navigation
  store: google-play
  url: https://play.google.com/store/apps/category/MAPS_AND_NAVIGATION
- category: Maps and Global Positioning System (GPS)
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#maps-and-global-positioning-system-gps
name: Public Transit
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.40
    key: AE-210.30.40
    name: Public Transit Data
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  fit: exact
  layer: domain
  why: agency GTFS/GTFS-RT, SIRI and station-facility feeds; the broker rows (Pub/Sub, Service Bus, MQTT) are capability_fit gap pending proposed node AE-210.30.60
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.10
    key: AE-210.30.10
    name: Ride Hailing
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  fit: exact
  layer: domain
  why: first/last-mile ride-hail legs in itineraries
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.50
    key: AE-210.30.50
    name: Micromobility & Bike Share
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  fit: exact
  layer: domain
  why: GBFS bikeshare and scooter options
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.30
    key: AE-210.30.30
    name: Parking
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  fit: exact
  layer: domain
  why: park-and-ride and bike parking availability
- capability:
    attribution: API Evangelist extension
    id: AE-210.50.10
    key: AE-210.50.10
    name: Mobile Tickets & Wallet Passes
    url: /capabilities/event-ticketing/
    via_parent: Event Ticketing
  fit: exact
  layer: common
  why: passes in Apple Wallet (transit fare purchase itself has no node)
- capability:
    attribution: API Evangelist extension
    id: AE-120
    key: location-mapping
    name: Location & Mapping
    url: /capabilities/location-mapping/
    via_parent: null
  fit: nearest
  layer: domain
  why: OSM base data for street routing
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: common
  why: map display
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: common
  why: stop and place search
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: arrival and alert notifications
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app analytics
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash reporting
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: nearest
  layer: common
  why: graph/data object storage (no generic object-storage capability)
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: Turbo EA
    id: BC-2120.40
    key: customer-information-consent-management
    name: Customer Information & Consent Management
    url: /capabilities/customer-information-consent-management/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: Turbo EA
    id: BC-3760.30
    key: programmatic-sales-management
    name: Programmatic Sales Management
    url: /capabilities/programmatic-sales-management/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: Turbo EA
    id: BC-2820.10
    key: referral-management
    name: Referral Management
    url: /capabilities/referral-management/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: mobile-app SDK trackers reported by Exodus Privacy
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: Google Cloud Pub/Sub, Azure Service Bus, HiveMQ MQTT client (Integration and API Management)
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.10
      key: AE-210.30.10
      name: Ride Hailing
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Citymapper
      - Moovit
      - OpenTripPlanner
      - Transit
      band: developing
      in_catalog: true
      kin_score: 49.0
      mcp:
        status: none
      name: Uber
      slug: uber
      sources:
      - https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
      - https://apps.apple.com/us/app/moovit-all-transit-options/id498477945
      - https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/application/src/ext/java/org/opentripplanner/ext/ridehailing/service
      status: profiled
      tags:
      - Food Delivery
      - Ride Hailing
      - Taxis
      - Transportation
      tier: observed
      url: /providers/uber/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Citymapper
      - Moovit
      - Transit
      band: developing
      in_catalog: true
      kin_score: 52.3
      mcp: &id001
        status: none
      name: Lyft
      slug: lyft
      sources:
      - https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
      - https://apps.apple.com/us/app/moovit-all-transit-options/id498477945
      - https://resources.transitapp.com/article/403-ridehail-and-taxi
      status: profiled
      tags: &id002
      - Micromobility
      - Mobility
      - Ride Hailing
      - Transportation
      tier: declared
      url: /providers/lyft/
    - agent_band: agent-aware
      agent_readiness: 8.7
      apps:
      - Transit
      band: emerging
      in_catalog: true
      kin_score: 25.1
      mcp:
        status: unknown
      name: Ola
      slug: ola
      sources:
      - https://resources.transitapp.com/article/403-ridehail-and-taxi
      status: profiled
      tags:
      - Geocoding
      - Maps
      - Ride Hailing
      - Transportation
      tier: declared
      url: /providers/ola/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Transit
      band: emerging
      in_catalog: true
      kin_score: 18.9
      mcp:
        status: unknown
      name: Via
      slug: via-transportation
      sources:
      - https://resources.transitapp.com/article/403-ridehail-and-taxi
      status: profiled
      tags:
      - Mobility
      - On-Demand
      - Public Transit
      - Transportation
      tier: declared
      url: /providers/via-transportation/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Transit
      band: minimal
      in_catalog: true
      kin_score: 8.7
      mcp:
        status: unchecked
      name: Curb
      slug: curb-mobility
      sources:
      - https://resources.transitapp.com/article/403-ridehail-and-taxi
      status: profiled
      tags:
      - Company
      - Mobility
      - Ride Hailing
      - Taxi
      tier: declared
      url: /providers/curb-mobility/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Transit
      band: minimal
      in_catalog: true
      kin_score: 7.3
      mcp:
        status: unchecked
      name: iCabbi
      slug: icabbi
      sources:
      - https://resources.transitapp.com/article/403-ridehail-and-taxi
      status: profiled
      tags:
      - Fleet Management
      - NEMT
      - Taxi Dispatch
      - Voice AI
      tier: declared
      url: /providers/icabbi/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.50
      key: AE-210.30.50
      name: Micromobility & Bike Share
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Citymapper
      band: developing
      in_catalog: true
      kin_score: 52.3
      mcp: *id001
      name: Lyft bikeshare systems
      slug: lyft
      sources:
      - https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/lyft/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Citymapper
      band: thin
      in_catalog: true
      kin_score: 35.0
      mcp:
        status: unknown
      name: Bird
      slug: bird-rides
      sources:
      - https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
      status: profiled
      tags:
      - E-Scooter
      - Electric Scooters
      - Micromobility
      - Shared Mobility
      tier: declared
      url: /providers/bird-rides/
    - agent_band: agent-aware
      agent_readiness: 16.7
      apps:
      - Citymapper
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: none
      name: Lime
      slug: lime
      sources:
      - https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
      status: profiled
      tags:
      - Electric Bikes
      - Electric Scooters
      - Micromobility
      - Shared Mobility
      tier: declared
      url: /providers/lime/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - MOTIS (Transitous)
      band: emerging
      in_catalog: true
      kin_score: 16.4
      mcp:
        status: unchecked
      name: MobiData BW
      slug: mobidata-bw
      sources:
      - https://github.com/motis-project/motis/blob/master/docs/setup.md
      status: profiled
      tags:
      - Company
      - Mobility
      - Open Data
      - Transportation
      tier: declared
      url: /providers/mobidata-bw/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - MOTIS (Transitous)
      band: emerging
      in_catalog: true
      kin_score: 11.3
      mcp:
        status: unchecked
      name: BIXI Montreal
      slug: bixi
      sources:
      - https://github.com/motis-project/motis/blob/master/docs/setup.md
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/bixi/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - MOTIS (Transitous)
      band: minimal
      in_catalog: true
      kin_score: 10.6
      mcp:
        status: none
      name: nextbike
      slug: nextbike
      sources:
      - https://github.com/motis-project/motis/blob/master/docs/setup.md
      status: profiled
      tags:
      - Bike Sharing
      - Europe
      - Mobility
      - Transportation
      tier: declared
      url: /providers/nextbike/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - Citymapper
      band: minimal
      in_catalog: true
      kin_score: 8.1
      mcp:
        status: unchecked
      name: BCycle
      slug: bcycle
      sources:
      - https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
      status: profiled
      tags:
      - Bike Share
      - Docked Systems
      - Operator Tools
      tier: declared
      url: /providers/bcycle/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Citymapper
      band: minimal
      in_catalog: true
      kin_score: 8.1
      mcp:
        status: unchecked
      name: Spin
      slug: spin-scooters
      sources:
      - https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
      status: profiled
      tags:
      - Company
      - Micromobility
      - Software-as-a-Service
      - Transportation
      tier: declared
      url: /providers/spin-scooters/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Citymapper
      band: minimal
      in_catalog: true
      kin_score: 0.0
      mcp:
        status: unknown
      name: Skip
      slug: skip-scooters
      sources:
      - https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
      status: profiled
      tags:
      - Company
      - Micromobility
      - Scooters
      - Transportation
      tier: declared
      url: /providers/skip-scooters/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.30
      key: AE-210.30.30
      name: Parking
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.4
      apps:
      - OpenTripPlanner
      band: thin
      in_catalog: true
      kin_score: 35.6
      mcp:
        status: unchecked
      name: Bikeep
      slug: bikeep
      sources:
      - https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/application/src/ext/java/org/opentripplanner/ext/vehicleparking
      status: profiled
      tags:
      - Company
      - IoT
      - Mobility
      - Smart Parking
      tier: observed
      url: /providers/bikeep/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - OpenTripPlanner
      band: minimal
      in_catalog: true
      kin_score: 4.5
      mcp:
        status: unchecked
      name: ParkAPI
      slug: parkapi
      sources:
      - https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/application/src/ext/java/org/opentripplanner/ext/vehicleparking
      status: profiled
      tags:
      - Europe
      - Mobile
      - Parking
      - Real-Time
      tier: observed
      url: /providers/parkapi/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - OpenTripPlanner
      band: minimal
      in_catalog: true
      kin_score: 2.6
      mcp:
        status: unchecked
      name: Bikely
      slug: bikely
      sources:
      - https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/application/src/ext/java/org/opentripplanner/ext/vehicleparking
      status: profiled
      tags:
      - Bike Parking
      - Municipalities
      - Smart Infrastructure
      - Transit Hubs
      tier: observed
      url: /providers/bikely/
    - agent_band: null
      agent_readiness: null
      apps:
      - OpenTripPlanner
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Liipi
      slug: liipi
      sources:
      - https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/application/src/ext/java/org/opentripplanner/ext/vehicleparking
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.40
      key: AE-210.30.40
      name: Public Transit Data
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.2
      apps:
      - OneBusAway Android
      band: thin
      in_catalog: true
      kin_score: 32.0
      mcp:
        status: unchecked
      name: MobilityData
      slug: mobilitydata
      sources:
      - https://github.com/OneBusAway/onebusaway-android/blob/master/gradle/libs.versions.toml
      status: profiled
      tags:
      - Data Standards
      - Mobility
      - Non-Profit
      - Open Source
      tier: observed
      url: /providers/mobilitydata/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - MOTIS (Transitous)
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: unknown
      name: Deutsche Bahn (FaSta)
      slug: deutsche-bahn
      sources:
      - https://github.com/motis-project/motis/tree/master/src/elevators
      status: profiled
      tags:
      - Company
      - Railways
      - Transportation
      - Travel
      tier: observed
      url: /providers/deutsche-bahn/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - MOTIS (Transitous)
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: unchecked
      name: OVapi
      slug: ovapi
      sources:
      - https://github.com/motis-project/motis/blob/master/docs/setup.md
      status: profiled
      tags:
      - Company
      - GTFS
      - Public Data
      - Transportation
      tier: declared
      url: /providers/ovapi/
    - agent_band: null
      agent_readiness: null
      apps:
      - MOTIS (Transitous)
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: opentransportdata.swiss
      slug: opentransportdata-swiss
      sources:
      - https://github.com/motis-project/motis/blob/master/docs/setup.md
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-120
      key: location-mapping
      name: Location & Mapping
      url: /capabilities/location-mapping/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - MOTIS (Transitous)
      band: developing
      in_catalog: true
      kin_score: 45.5
      mcp:
        status: none
      name: OpenStreetMap
      slug: openstreetmap
      sources:
      - https://github.com/motis-project/motis/blob/master/docs/setup.md
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Mapping
      - Open Data
      tier: declared
      url: /providers/openstreetmap/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Citymapper
      - Moovit
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Citymapper
      - Moovit
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id003
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
      status: profiled
      tags: &id004
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 31.0
      apps:
      - Moovit
      band: strong
      in_catalog: true
      kin_score: 60.3
      mcp:
        status: none
      name: BidMachine
      slug: bidmachine-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
      status: profiled
      tags:
      - Ad Exchange
      - AdTech
      - Advertising
      - Mobile Advertising
      tier: observed
      url: /providers/bidmachine-io/
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - Citymapper
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon
      slug: amazon
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: observed
      url: /providers/amazon/
    - agent_band: agent-aware
      agent_readiness: 7.7
      apps:
      - Citymapper
      band: developing
      in_catalog: true
      kin_score: 46.1
      mcp:
        status: none
      name: InMobi
      slug: inmobi
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Enterprise
      tier: observed
      url: /providers/inmobi/
    - agent_band: agent-aware
      agent_readiness: 20.3
      apps:
      - Moovit
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Digital Turbine (Fyber)
      slug: digital-turbine
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
      status: profiled
      tags:
      - Advertising
      - Company
      - Mobile
      - Monetization
      tier: observed
      url: /providers/digital-turbine/
    - agent_band: agent-ready
      agent_readiness: 35.5
      apps:
      - Citymapper
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        status: none
      name: AppLovin
      slug: applovin
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - App Monetization
      - Mobile
      tier: observed
      url: /providers/applovin/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Moovit
      band: thin
      in_catalog: true
      kin_score: 34.0
      mcp:
        status: none
      name: Appodeal
      slug: appodeal
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
      status: profiled
      tags:
      - Advertising
      - Company
      - Mobile
      - Monetization
      tier: observed
      url: /providers/appodeal/
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - Citymapper
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        source: https://github.com/PubMatic/pubmatic-mcp-server
        status: verified
      name: PubMatic
      slug: pubmatic
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Programmatic Advertising
      - Supply Side Platform
      tier: observed
      url: /providers/pubmatic/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Citymapper
      - Moovit
      - OneBusAway Android
      - Transit
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id005
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: google-firebase
      sources:
      - https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
      - https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.thetransitapp.droid/latest/
      status: profiled
      tags: &id006
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Citymapper
      - Moovit
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 22.6
      apps:
      - OneBusAway Android
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        status: none
      name: Plausible
      slug: plausible
      sources:
      - https://github.com/OneBusAway/onebusaway-android/blob/master/gradle/libs.versions.toml
      status: profiled
      tags:
      - Analytics
      - Cookie-Free
      - Event Tracking
      - GDPR
      tier: observed
      url: /providers/plausible/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Transit
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.thetransitapp.droid/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - Citymapper
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Citymapper
      - Moovit
      - OneBusAway Android
      - Transit
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id005
      name: Firebase Crashlytics
      slug: google-firebase
      sources:
      - https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
      - https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.thetransitapp.droid/latest/
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - OpenTripPlanner
      band: exemplar
      in_catalog: true
      kin_score: 77.2
      mcp:
        source: https://raw.githubusercontent.com/microsoft/mcp/main/servers/Azure.Mcp.Server/README.md
        status: verified
      name: Azure Service Bus
      slug: azure-service-bus
      sources:
      - https://github.com/opentripplanner/OpenTripPlanner/blob/dev-2.x/application/pom.xml
      status: profiled
      tags:
      - Cloud
      - Enterprise
      - Message Broker
      - Microsoft Azure
      tier: observed
      url: /providers/azure-service-bus/
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - OpenTripPlanner
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp:
        source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
        status: verified
      name: Google Cloud Pub/Sub
      slug: google-cloud-pubsub
      sources:
      - https://github.com/opentripplanner/OpenTripPlanner/blob/dev-2.x/application/pom.xml
      status: profiled
      tags:
      - Event-Driven
      - Google Cloud
      - Messaging
      - Pub/Sub
      tier: observed
      url: /providers/google-cloud-pubsub/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - OpenTripPlanner
      band: strong
      in_catalog: true
      kin_score: 58.3
      mcp:
        status: none
      name: HiveMQ MQTT client
      slug: hivemq
      sources:
      - https://github.com/opentripplanner/OpenTripPlanner/blob/dev-2.x/application/pom.xml
      status: profiled
      tags:
      - IoT
      - MQTT
      - Message Broker
      - Messaging
      tier: observed
      url: /providers/hivemq/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - OneBusAway Android
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps Platform
      slug: google-maps
      sources:
      - https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
    - agent_band: human-only
      agent_readiness: 3.0
      apps:
      - OneBusAway Android
      band: emerging
      in_catalog: true
      kin_score: 17.3
      mcp:
        status: unchecked
      name: MapLibre
      slug: maplibre
      sources:
      - https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
      status: profiled
      tags:
      - Company
      - Geospatial
      - Mapping
      - Open Source
      tier: observed
      url: /providers/maplibre/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - Citymapper
      - Moovit
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
      status: profiled
      tags:
      - Company
      - Marketing Analytics
      - Mobile Attribution
      - Mobile Measurement
      tier: observed
      url: /providers/appsflyer/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50.10
      key: AE-210.50.10
      name: Mobile Tickets & Wallet Passes
      url: /capabilities/event-ticketing/
      via_parent: Event Ticketing
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Citymapper
      - Moovit
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Apple Wallet
      slug: apple
      sources:
      - https://apps.apple.com/us/app/citymapper-all-live-transit/id469463298
      - https://apps.apple.com/us/app/moovit-all-transit-options/id498477945
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
  - capability:
      attribution: Turbo EA
      id: BC-3760.30
      key: programmatic-sales-management
      name: Programmatic Sales Management
      url: /capabilities/programmatic-sales-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Citymapper
      - Moovit
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        source: https://github.com/IABTechLab/agentic-real-time-framework
        status: verified
      name: IAB Open Measurement
      slug: iab-tech-lab
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - Company
      - Standards
      tier: observed
      url: /providers/iab-tech-lab/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Citymapper
      - Moovit
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - OpenTripPlanner
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/opentripplanner/OpenTripPlanner/blob/dev-2.x/application/pom.xml
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
      id: BC-2120.40
      key: customer-information-consent-management
      name: Customer Information & Consent Management
      url: /capabilities/customer-information-consent-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.8
      apps:
      - Citymapper
      band: exemplar
      in_catalog: true
      kin_score: 78.8
      mcp:
        status: none
      name: Didomi
      slug: didomi
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.citymapper.app.release/latest/
      status: profiled
      tags:
      - AdTech
      - Advertising
      - CCPA
      - CMP
      tier: observed
      url: /providers/didomi/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Moovit
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.3
      apps:
      - OneBusAway Android
      band: emerging
      in_catalog: true
      kin_score: 22.9
      mcp:
        status: none
      name: Pelias
      slug: pelias
      sources:
      - https://github.com/OneBusAway/onebusaway-android/blob/master/gradle/libs.versions.toml
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
      id: AE-120
      key: location-mapping
      name: Location & Mapping
      url: /capabilities/location-mapping/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.3
      apps:
      - Moovit
      band: developing
      in_catalog: true
      kin_score: 45.8
      mcp:
        status: unchecked
      name: Carto
      slug: carto
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
      status: profiled
      tags:
      - GIS
      - Geospatial
      - Location Intelligence
      - Mapping
      tier: observed
      url: /providers/carto/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - OneBusAway Android
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id005
      name: Firebase Cloud Messaging
      slug: google-firebase
      sources:
      - https://github.com/OneBusAway/onebusaway-android/blob/master/onebusaway-android/build.gradle.kts
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: Turbo EA
      id: BC-2820.10
      key: referral-management
      name: Referral Management
      url: /capabilities/referral-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Moovit
      band: strong
      in_catalog: true
      kin_score: 56.0
      mcp:
        status: unknown
      name: Button
      slug: usebutton
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.tranzmate/latest/
      status: profiled
      tags:
      - Affiliates
      - Attribution
      - Commerce
      - Mobile Commerce
      tier: observed
      url: /providers/usebutton/
  layer: common
summary:
  coverage_pct: 95.9
  declared_only: 17
  distinct_providers: 49
  in_catalog: 47
  mcp:
    documented: 0
    none: 17
    unchecked: 15
    verified: 11
  mcp_verified: 11
  mean_kin_score: 38.9
  observed: 32
  queued: 2
  reference_apps: 6
title: 'Public Transit: application blueprint'
---
