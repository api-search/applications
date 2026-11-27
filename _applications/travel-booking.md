---
access: understanding
agent_layer:
- app: TRIP
  finding: ships its own MCP server (mcp-server/ in the repo)
  source: https://github.com/itskovacs/trip/tree/main/mcp-server
  tier: observed
apps:
- anchor: adventurelog
  counts:
    declared: 3
    observed: 11
  evidence:
  - route: dependency manifest
    url: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/requirements.txt
  - route: documentation
    url: https://github.com/seanmorley15/AdventureLog/blob/main/documentation/docs/configuration/analytics.md
  - route: documentation
    url: https://github.com/seanmorley15/AdventureLog/blob/main/documentation/docs/configuration/google_maps_integration.md
  - route: documentation
    url: https://github.com/seanmorley15/AdventureLog/tree/main/documentation/docs/configuration/social_auth
  - route: source code
    url: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/geocoding/google.py
  - route: source code
    url: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/geocoding/osm.py
  - route: source code
    url: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/places/wikipedia.py
  - route: source code
    url: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/recommendations/osm.py
  - route: source code
    url: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/main/settings.py
  - route: source code
    url: https://github.com/seanmorley15/AdventureLog/tree/main/backend/server/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.30
      key: AE-130.10.30
      name: Running & Cycling Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: Endurain
    provider: endurain
    says: ships the Endurain SDK or integration code
    source: https://github.com/seanmorley15/AdventureLog/tree/main/backend/server/integrations
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
    source: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/main/settings.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10
      key: AE-120.10
      name: Geocoding
      url: /capabilities/geocoding/
      via_parent: null
    credit: null
    layer: common
    name: Google Maps Geocoding
    provider: google-maps
    says: ships the Google Maps Geocoding SDK or integration code
    source: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/geocoding/google.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40.10
      key: AE-120.40.10
      name: Place Search
      url: /capabilities/places-points-of-interest/
      via_parent: Places & Points of Interest
    credit: null
    layer: domain
    name: Google Places (New)
    provider: google-places
    says: ships the Google Places (New) SDK or integration code
    source: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/recommendations/google.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.20
      key: AE-170.30.20
      name: Photo Sharing
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: Immich
    provider: immich
    says: ships the Immich SDK or integration code
    source: https://github.com/seanmorley15/AdventureLog/tree/main/backend/server/integrations
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.20
      key: AE-120.10.20
      name: Reverse Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: common
    name: Nominatim (OSM)
    provider: nominatim
    says: ships the Nominatim (OSM) SDK or integration code
    source: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/geocoding/osm.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40.10
      key: AE-120.40.10
      name: Place Search
      url: /capabilities/places-points-of-interest/
      via_parent: Places & Points of Interest
    credit: null
    layer: domain
    name: Overpass API
    provider: overpass-api
    says: ships the Overpass API SDK or integration code
    source: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/recommendations/osm.py
    tier: observed
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
    says: ships the Strava SDK or integration code
    source: https://github.com/seanmorley15/AdventureLog/tree/main/backend/server/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/requirements.txt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.30
      key: AE-130.10.30
      name: Running & Cycling Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: wanderer
    provider: wanderer
    says: ships the wanderer SDK or integration code
    source: https://github.com/seanmorley15/AdventureLog/tree/main/backend/server/integrations
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
    source: https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/places/wikipedia.py
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
    name: Authentik
    provider: authentik
    says: lists Authentik as an integration
    source: https://github.com/seanmorley15/AdventureLog/tree/main/documentation/docs/configuration/social_auth
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Pocket ID
    provider: pocket-id
    says: lists Pocket ID as an integration
    source: https://github.com/seanmorley15/AdventureLog/tree/main/documentation/docs/configuration/social_auth
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Umami
    provider: umami
    says: lists Umami as an integration
    source: https://github.com/seanmorley15/AdventureLog/blob/main/documentation/docs/configuration/analytics.md
    tier: declared
  kind: self-hosted
  name: AdventureLog
  page: /applications/travel-booking/adventurelog/
  slug: adventurelog
  url: https://github.com/seanmorley15/AdventureLog
- anchor: trip
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: dependency manifest
    url: https://github.com/itskovacs/trip/blob/main/backend/trip/requirements.txt
  - route: source code
    url: https://github.com/itskovacs/trip/blob/main/backend/trip/config.py
  - route: source code
    url: https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/google.py
  - route: source code
    url: https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/osm.py
  - route: source code
    url: https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/photon.py
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.10
      key: AE-120.30.10
      name: Turn-by-Turn Directions
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    credit: null
    layer: common
    name: FOSSGIS OSRM routing
    provider: fossgis
    says: ships the FOSSGIS OSRM routing SDK or integration code
    source: https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/osm.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10
      key: AE-120.10
      name: Geocoding
      url: /capabilities/geocoding/
      via_parent: null
    credit: null
    layer: common
    name: Google Geocoding + Routes
    provider: google-maps
    says: ships the Google Geocoding + Routes SDK or integration code
    source: https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/google.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40.10
      key: AE-120.40.10
      name: Place Search
      url: /capabilities/places-points-of-interest/
      via_parent: Places & Points of Interest
    credit: null
    layer: domain
    name: Google Places API (New)
    provider: google-places
    says: ships the Google Places API (New) SDK or integration code
    source: https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/google.py
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
    name: Nominatim (OSM)
    provider: nominatim
    says: ships the Nominatim (OSM) SDK or integration code
    source: https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/osm.py
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
    name: OpenStreetMap tiles
    provider: openstreetmap
    says: ships the OpenStreetMap tiles SDK or integration code
    source: https://github.com/itskovacs/trip/blob/main/backend/trip/config.py
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
    name: Photon (komoot)
    provider: komoot
    says: ships the Photon (komoot) SDK or integration code
    source: https://github.com/itskovacs/trip/blob/main/backend/trip/config.py
    tier: observed
  kind: self-hosted
  name: TRIP
  page: /applications/travel-booking/trip/
  slug: trip
  url: https://github.com/itskovacs/trip
- anchor: bookingcom
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.booking/latest/
  integrations:
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.booking/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.booking/latest/
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
    name: Google CrashLytics
    provider: firebase
    says: ships the Google CrashLytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.booking/latest/
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
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.booking/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.booking/latest/
    tier: observed
  kind: commercial
  name: Booking.com
  page: /applications/travel-booking/booking-com/
  slug: booking-com
  url: https://www.booking.com/
- anchor: airbnb
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.airbnb.android/latest/
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
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.airbnb.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.airbnb.android/latest/
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.airbnb.android/latest/
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
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.airbnb.android/latest/
    tier: observed
  kind: commercial
  name: Airbnb
  page: /applications/travel-booking/airbnb/
  slug: airbnb
  url: https://www.airbnb.com/
- anchor: tripit
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.tripit/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Adobe Experience Cloud
    provider: adobe-experience-cloud
    says: ships the Adobe Experience Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tripit/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Apptentive (Alchemer Mobile)
    provider: apptentive
    says: ships the Apptentive (Alchemer Mobile) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tripit/latest/
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
    name: Dynatrace
    provider: dynatrace
    says: ships the Dynatrace SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tripit/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.30
      key: AE-120.20.30
      name: Indoor & Venue Maps
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: domain
    name: LocusLabs (Atrius) indoor airport maps
    provider: locuslabs
    says: ships the LocusLabs (Atrius) indoor airport maps SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.tripit/latest/
    tier: observed
  kind: commercial
  name: TripIt
  page: /applications/travel-booking/tripit/
  slug: tripit
  url: https://www.tripit.com/
- anchor: expedia
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.expedia.bookings/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Adobe Experience Cloud
    provider: adobe-experience-cloud
    says: ships the Adobe Experience Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.expedia.bookings/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.expedia.bookings/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.expedia.bookings/latest/
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
    name: Google CrashLytics
    provider: firebase
    says: ships the Google CrashLytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.expedia.bookings/latest/
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
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.expedia.bookings/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Qualtrics
    provider: qualtrics
    says: ships the Qualtrics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.expedia.bookings/latest/
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
    name: Salesforce Marketing Cloud
    provider: salesforce-marketing-cloud
    says: ships the Salesforce Marketing Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.expedia.bookings/latest/
    tier: observed
  kind: commercial
  name: Expedia
  page: /applications/travel-booking/expedia/
  slug: expedia
  url: https://www.expedia.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: travel-booking
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Travel
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Travel & Local
  store: google-play
  url: https://play.google.com/store/apps/category/TRAVEL_AND_LOCAL
- category: Travel Organization
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#travel-organization
name: Travel Booking & Trip Planning
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-120.10
    key: AE-120.10
    name: Geocoding
    url: /capabilities/geocoding/
    via_parent: null
  fit: exact
  layer: common
  why: geocoding place names on trips (Google, Nominatim, Photon)
- capability:
    attribution: API Evangelist extension
    id: AE-120.40.10
    key: AE-120.40.10
    name: Place Search
    url: /capabilities/places-points-of-interest/
    via_parent: Places & Points of Interest
  fit: exact
  layer: domain
  why: place/POI search and recommendations
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.20
    key: AE-120.10.20
    name: Reverse Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: common
  why: reverse geocoding visited locations (Nominatim)
- capability:
    attribution: API Evangelist extension
    id: AE-120.40.20
    key: AE-120.40.20
    name: Place Content & Descriptions
    url: /capabilities/places-points-of-interest/
    via_parent: Places & Points of Interest
  fit: exact
  layer: domain
  why: place enrichment from Wikipedia (nearest)
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: subscription payments (AdventureLog hosted)
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: social/OIDC sign-in
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.20
    key: AE-170.30.20
    name: Photo Sharing
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: domain
  why: trip photos from a photo library (Immich)
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.30
    key: AE-130.10.30
    name: Running & Cycling Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  fit: exact
  layer: domain
  why: GPS activity/trail imports into trip logs (Strava, wanderer, Endurain)
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: app/web analytics
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: common
  why: base map tiles for itineraries
- capability:
    attribution: API Evangelist extension
    id: AE-120.10.10
    key: AE-120.10.10
    name: Forward Geocoding
    url: /capabilities/geocoding/
    via_parent: Geocoding
  fit: exact
  layer: common
  why: forward geocoding search (Nominatim, Photon)
- capability:
    attribution: API Evangelist extension
    id: AE-120.30.10
    key: AE-120.30.10
    name: Turn-by-Turn Directions
    url: /capabilities/routing-navigation/
    via_parent: Routing & Navigation
  fit: exact
  layer: common
  why: routes between itinerary stops
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile install attribution in the booking apps
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: in-app ads
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash reporting and APM
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: tag management
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: marketing cloud / CRM messaging
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  fit: exact
  layer: common
  why: in-app surveys and feedback
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.30
    key: AE-120.20.30
    name: Indoor & Venue Maps
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: domain
  why: indoor airport maps (LocusLabs) — gap row, no indoor node
- capability:
    attribution: API Evangelist extension
    id: AE-210.10
    key: AE-210.10
    name: Flight Search & Booking
    url: /capabilities/flight-search-booking/
    via_parent: null
  fit: exact
  layer: domain
  why: flight search/booking supply; no reference app exposes its supplier integrations, so rows are inferred only
- capability:
    attribution: API Evangelist extension
    id: AE-210.20.10
    key: AE-210.20.10
    name: Hotel Booking
    url: /capabilities/lodging-stays/
    via_parent: Lodging & Stays
  fit: exact
  layer: domain
  why: hotel supply (Booking.com Demand API, Expedia Rapid); inferred only
- capability:
    attribution: API Evangelist extension
    id: AE-210.20.20
    key: AE-210.20.20
    name: Vacation & Short-Term Rentals
    url: /capabilities/lodging-stays/
    via_parent: Lodging & Stays
  fit: exact
  layer: domain
  why: short-term rentals; inferred only
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40.10
      key: AE-120.40.10
      name: Place Search
      url: /capabilities/places-points-of-interest/
      via_parent: Places & Points of Interest
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.3
      apps:
      - AdventureLog
      - TRIP
      band: strong
      in_catalog: true
      kin_score: 62.4
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Places (New)
      slug: google-places
      sources:
      - https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/google.py
      - https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/recommendations/google.py
      status: profiled
      tags:
      - Geolocation
      - Google
      - Location
      - Restaurant
      tier: observed
      url: /providers/google-places/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - AdventureLog
      band: emerging
      in_catalog: true
      kin_score: 15.1
      mcp:
        status: unknown
      name: Overpass API
      slug: overpass-api
      sources:
      - https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/recommendations/osm.py
      status: profiled
      tags:
      - GIS
      - Geographic
      - OpenStreetMap
      - Spatial
      tier: observed
      url: /providers/overpass-api/
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.30
      key: AE-130.10.30
      name: Running & Cycling Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.3
      apps:
      - AdventureLog
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        status: none
      name: Strava
      slug: strava
      sources:
      - https://github.com/seanmorley15/AdventureLog/tree/main/backend/server/integrations
      status: profiled
      tags:
      - Cycling
      - Fitness
      - Fitness Tracking
      - Running
      tier: observed
      url: /providers/strava/
    - agent_band: agent-aware
      agent_readiness: 17.2
      apps:
      - AdventureLog
      band: thin
      in_catalog: true
      kin_score: 28.2
      mcp:
        status: none
      name: Endurain
      slug: endurain
      sources:
      - https://github.com/seanmorley15/AdventureLog/tree/main/backend/server/integrations
      status: profiled
      tags:
      - Company
      - Fitness
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/endurain/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - AdventureLog
      band: minimal
      in_catalog: true
      kin_score: 9.2
      mcp:
        status: unknown
      name: wanderer
      slug: wanderer
      sources:
      - https://github.com/seanmorley15/AdventureLog/tree/main/backend/server/integrations
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/wanderer/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.30
      key: AE-120.20.30
      name: Indoor & Venue Maps
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - TripIt
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: LocusLabs (Atrius) indoor airport maps
      slug: locuslabs
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.tripit/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.20
      key: AE-170.30.20
      name: Photo Sharing
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - AdventureLog
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        status: none
      name: Immich
      slug: immich
      sources:
      - https://github.com/seanmorley15/AdventureLog/tree/main/backend/server/integrations
      status: profiled
      tags:
      - Photo Management
      - Privacy
      - Self-Hosted
      - Video Management
      tier: observed
      url: /providers/immich/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40.20
      key: AE-120.40.20
      name: Place Content & Descriptions
      url: /capabilities/places-points-of-interest/
      via_parent: Places & Points of Interest
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.3
      apps:
      - AdventureLog
      band: developing
      in_catalog: true
      kin_score: 41.8
      mcp:
        status: none
      name: Wikipedia
      slug: wikipedia
      sources:
      - https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/places/wikipedia.py
      status: profiled
      tags:
      - Encyclopedia
      - Open Data
      - Open Knowledge
      - Public APIs
      tier: observed
      url: /providers/wikipedia/
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
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Airbnb
      - Booking.com
      - Expedia
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.airbnb.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.booking/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.expedia.bookings/latest/
      status: profiled
      tags: &id002
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Airbnb
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.airbnb.android/latest/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - AdventureLog
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        status: none
      name: Umami
      slug: umami
      sources:
      - https://github.com/seanmorley15/AdventureLog/blob/main/documentation/docs/configuration/analytics.md
      status: profiled
      tags:
      - Cookieless Tracking
      - Open Source
      - Privacy
      - Web Analytics
      tier: declared
      url: /providers/umami/
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
      - Airbnb
      - Expedia
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook Login / Share
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.airbnb.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.expedia.bookings/latest/
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - AdventureLog
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/main/settings.py
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 37.2
      apps:
      - AdventureLog
      band: exemplar
      in_catalog: true
      kin_score: 73.1
      mcp:
        status: none
      name: Authentik
      slug: authentik
      sources:
      - https://github.com/seanmorley15/AdventureLog/tree/main/documentation/docs/configuration/social_auth
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity Provider
      - LDAP
      tier: declared
      url: /providers/authentik/
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - AdventureLog
      band: emerging
      in_catalog: true
      kin_score: 25.1
      mcp:
        status: none
      name: Pocket ID
      slug: pocket-id
      sources:
      - https://github.com/seanmorley15/AdventureLog/tree/main/documentation/docs/configuration/social_auth
      status: profiled
      tags:
      - Company
      - Identity
      - OAuth
      - OpenID Connect
      tier: declared
      url: /providers/pocket-id/
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
      - Booking.com
      - Expedia
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: Google CrashLytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.booking/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.expedia.bookings/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 43.8
      apps:
      - TripIt
      band: exemplar
      in_catalog: true
      kin_score: 85.6
      mcp:
        source: https://github.com/dynatrace-oss/dynatrace-mcp
        status: verified
      name: Dynatrace
      slug: dynatrace
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.tripit/latest/
      status: profiled
      tags:
      - AI Operations
      - APM
      - Analytics
      - Application Performance Monitoring
      tier: observed
      url: /providers/dynatrace/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Airbnb
      band: exemplar
      in_catalog: true
      kin_score: 76.3
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.airbnb.android/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.0
      apps:
      - Expedia
      - TripIt
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe Experience Cloud
      slug: adobe-experience-cloud
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.expedia.bookings/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.tripit/latest/
      status: profiled
      tags:
      - Analytics
      - Customer Experience
      - Digital Marketing
      - Personalization
      tier: observed
      url: /providers/adobe-experience-cloud/
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - Expedia
      band: exemplar
      in_catalog: true
      kin_score: 77.6
      mcp:
        status: none
      name: Salesforce Marketing Cloud
      slug: salesforce-marketing-cloud
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.expedia.bookings/latest/
      status: profiled
      tags:
      - Automation
      - Content Management
      - Customer Journey
      - Digital Marketing
      tier: observed
      url: /providers/salesforce-marketing-cloud/
  - capability:
      attribution: Turbo EA
      id: BC-430.50
      key: customer-feedback-management
      name: Customer Feedback Management
      url: /capabilities/customer-feedback-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Expedia
      band: developing
      in_catalog: true
      kin_score: 45.7
      mcp:
        status: none
      name: Qualtrics
      slug: qualtrics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.expedia.bookings/latest/
      status: profiled
      tags:
      - Customer Experience
      - Employee Experience
      - Experience Management
      - Surveys
      tier: observed
      url: /providers/qualtrics/
    - agent_band: agent-aware
      agent_readiness: 25.5
      apps:
      - TripIt
      band: developing
      in_catalog: true
      kin_score: 40.0
      mcp:
        status: none
      name: Apptentive (Alchemer Mobile)
      slug: apptentive
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.tripit/latest/
      status: profiled
      tags:
      - Company
      - Customer Feedback
      - Enterprise
      - Mobile
      tier: observed
      url: /providers/apptentive/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - TRIP
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id003
        status: none
      name: Nominatim (OSM)
      slug: nominatim
      sources:
      - https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/osm.py
      status: profiled
      tags: &id004
      - Geocoding
      - Location Services
      - Maps
      - OpenStreetMap
      tier: observed
      url: /providers/nominatim/
    - agent_band: null
      agent_readiness: null
      apps:
      - TRIP
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Photon (komoot)
      slug: komoot
      sources:
      - https://github.com/itskovacs/trip/blob/main/backend/trip/config.py
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10
      key: AE-120.10
      name: Geocoding
      url: /capabilities/geocoding/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.0
      apps:
      - AdventureLog
      - TRIP
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps Geocoding
      slug: google-maps
      sources:
      - https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/google.py
      - https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/geocoding/google.py
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
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
      - Booking.com
      - Expedia
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
        status: verified
      name: AppsFlyer
      slug: appsflyer
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.booking/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.expedia.bookings/latest/
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
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - TRIP
      band: developing
      in_catalog: true
      kin_score: 45.5
      mcp:
        status: none
      name: OpenStreetMap tiles
      slug: openstreetmap
      sources:
      - https://github.com/itskovacs/trip/blob/main/backend/trip/config.py
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Mapping
      - Open Data
      tier: observed
      url: /providers/openstreetmap/
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
      - Booking.com
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.booking/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - AdventureLog
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/requirements.txt
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.20
      key: AE-120.10.20
      name: Reverse Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - AdventureLog
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Nominatim (OSM)
      slug: nominatim
      sources:
      - https://github.com/seanmorley15/AdventureLog/blob/main/backend/server/adventures/providers/geocoding/osm.py
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/nominatim/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Booking.com
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.booking/latest/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.30.10
      key: AE-120.30.10
      name: Turn-by-Turn Directions
      url: /capabilities/routing-navigation/
      via_parent: Routing & Navigation
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - TRIP
      band: minimal
      in_catalog: true
      kin_score: 3.0
      mcp:
        status: none
      name: FOSSGIS OSRM routing
      slug: fossgis
      sources:
      - https://github.com/itskovacs/trip/blob/main/backend/trip/utils/providers/osm.py
      status: profiled
      tags:
      - GIS
      - Geospatial
      - Open Source
      - Routing
      tier: observed
      url: /providers/fossgis/
  layer: common
summary:
  coverage_pct: 93.3
  declared_only: 3
  distinct_providers: 30
  in_catalog: 28
  mcp:
    documented: 0
    none: 16
    unchecked: 2
    verified: 10
  mcp_verified: 10
  mean_kin_score: 54.2
  observed: 27
  queued: 2
  reference_apps: 6
title: 'Travel Booking & Trip Planning: application blueprint'
---
