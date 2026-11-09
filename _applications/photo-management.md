---
access: understanding
agent_layer:
- app: PhotoPrism
  finding: ships an MCP server (github.com/modelcontextprotocol/go-sdk in go.mod)
  source: https://github.com/photoprism/photoprism/blob/develop/go.mod
  tier: observed
apps:
- anchor: immich
  counts:
    declared: 1
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://github.com/immich-app/immich/blob/main/mobile/pubspec.yaml
  - route: dependency manifest
    url: https://github.com/immich-app/immich/blob/main/server/package.json
  - route: source code
    url: https://github.com/immich-app/immich/blob/main/docker/example.env
  - route: source code
    url: https://github.com/immich-app/immich/blob/main/docs/docs/features/reverse-geocoding.md
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40
      key: AE-120.40
      name: Places & Points of Interest
      url: /capabilities/places-points-of-interest/
      via_parent: null
    credit: null
    layer: domain
    name: geonames
    provider: geonames
    says: lists geonames as an integration
    source: https://github.com/immich-app/immich/blob/main/docs/docs/features/reverse-geocoding.md
    tier: declared
  kind: self-hosted
  name: Immich
  page: /applications/photo-management/immich/
  slug: immich
  url: https://github.com/immich-app/immich
- anchor: photoprism
  counts:
    declared: 1
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://github.com/photoprism/photoprism/blob/develop/frontend/package.json
  - route: dependency manifest
    url: https://github.com/photoprism/photoprism/blob/develop/go.mod
  - route: documentation
    url: https://docs.photoprism.app/getting-started/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20
      key: AE-120.20
      name: Maps & Tiles
      url: /capabilities/maps-tiles/
      via_parent: null
    credit: null
    layer: domain
    name: maptiler
    provider: maptiler
    says: lists maptiler as an integration
    source: https://docs.photoprism.app/getting-started/
    tier: declared
  kind: self-hosted
  name: PhotoPrism
  page: /applications/photo-management/photoprism/
  slug: photoprism
  url: https://github.com/photoprism/photoprism
- anchor: librephotos
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: dependency manifest
    url: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/requirements.txt
  - route: source code
    url: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.20
      key: AE-120.10.20
      name: Reverse Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    credit: null
    layer: domain
    name: mapbox
    provider: mapbox
    says: ships the mapbox SDK or integration code
    source: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
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
    name: maptiler
    provider: maptiler
    says: ships the maptiler SDK or integration code
    source: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: domain
    name: nextcloud
    provider: nextcloud
    says: ships the nextcloud SDK or integration code
    source: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/requirements.txt
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
    name: nominatim
    provider: nominatim
    says: ships the nominatim SDK or integration code
    source: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
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
    name: opencage
    provider: opencage
    says: ships the opencage SDK or integration code
    source: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
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
    name: tomtom
    provider: tomtom
    says: ships the tomtom SDK or integration code
    source: https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
    tier: observed
  kind: self-hosted
  name: LibrePhotos
  page: /applications/photo-management/librephotos/
  slug: librephotos
  url: https://github.com/LibrePhotos/librephotos
- anchor: ente-photos
  counts:
    declared: 3
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://github.com/ente-io/ente/blob/main/server/go.mod
  - route: dependency manifest
    url: https://github.com/ente-io/ente/blob/main/web/packages/base/package.json
  - route: source code
    url: https://github.com/ente-io/ente/blob/main/server/configurations/local.yaml
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3750.20
      key: subscription-entitlement-management
      name: Subscription & Entitlement Management
      url: /capabilities/subscription-entitlement-management/
      via_parent: null
    credit: null
    layer: common
    name: apple
    provider: apple
    says: ships the apple SDK or integration code
    source: https://github.com/ente-io/ente/blob/main/server/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-2510.40
      key: exception-and-alert-management
      name: Exception and Alert Management
      url: /capabilities/exception-and-alert-management/
      via_parent: null
    credit: null
    layer: common
    name: discord
    provider: discord
    says: ships the discord SDK or integration code
    source: https://github.com/ente-io/ente/blob/main/server/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3750.20
      key: subscription-entitlement-management
      name: Subscription & Entitlement Management
      url: /capabilities/subscription-entitlement-management/
      via_parent: null
    credit: null
    layer: common
    name: google-play
    provider: google-play
    says: ships the google-play SDK or integration code
    source: https://github.com/ente-io/ente/blob/main/server/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    credit: null
    layer: common
    name: stripe
    provider: stripe
    says: ships the stripe SDK or integration code
    source: https://github.com/ente-io/ente/blob/main/server/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: backblaze
    provider: backblaze
    says: lists backblaze as an integration
    source: https://github.com/ente-io/ente/blob/main/server/configurations/local.yaml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: firebase
    provider: firebase
    says: lists firebase as an integration
    source: https://github.com/ente-io/ente/blob/main/server/configurations/local.yaml
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: wasabi
    provider: wasabi
    says: lists wasabi as an integration
    source: https://github.com/ente-io/ente/blob/main/server/configurations/local.yaml
    tier: declared
  kind: open-source-saas
  name: Ente Photos
  page: /applications/photo-management/ente-photos/
  slug: ente-photos
  url: https://github.com/ente-io/ente
- anchor: lychee
  counts:
    declared: 1
    observed: 18
  evidence:
  - route: dependency manifest
    url: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
  - route: source code
    url: https://github.com/LycheeOrg/Lychee/blob/master/.env.example
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: amazon
    provider: amazon
    says: ships the amazon SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: amazon-s3
    provider: amazon-s3
    says: ships the amazon-s3 SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: apple
    provider: apple
    says: ships the apple SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: authelia
    provider: authelia
    says: ships the authelia SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: authentik
    provider: authentik
    says: ships the authentik SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: facebook
    provider: facebook
    says: ships the facebook SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: github
    provider: github
    says: ships the github SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: google-identity-platform
    provider: google-identity-platform
    says: ships the google-identity-platform SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: kanidm
    provider: kanidm
    says: ships the kanidm SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: keycloak
    provider: keycloak
    says: ships the keycloak SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: mastodon
    provider: mastodon
    says: ships the mastodon SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: microsoft-entra
    provider: microsoft-entra
    says: ships the microsoft-entra SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
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
    name: mollie
    provider: mollie
    says: ships the mollie SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: nextcloud
    provider: nextcloud
    says: ships the nextcloud SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
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
    name: nominatim
    provider: nominatim
    says: ships the nominatim SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
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
    name: paypal
    provider: paypal
    says: ships the paypal SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: pocket-id
    provider: pocket-id
    says: ships the pocket-id SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
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
    name: stripe
    provider: stripe
    says: ships the stripe SDK or integration code
    source: https://github.com/LycheeOrg/Lychee/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: common
    name: mailgun
    provider: mailgun
    says: lists mailgun as an integration
    source: https://github.com/LycheeOrg/Lychee/blob/master/.env.example
    tier: declared
  kind: self-hosted
  name: Lychee
  page: /applications/photo-management/lychee/
  slug: lychee
  url: https://github.com/LycheeOrg/Lychee
- anchor: nextcloud-memories
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://github.com/pulsejet/memories/blob/master/composer.json
  - route: dependency manifest
    url: https://github.com/pulsejet/memories/blob/master/package.json
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    credit: null
    layer: domain
    name: nextcloud
    provider: nextcloud
    says: ships the nextcloud SDK or integration code
    source: https://github.com/pulsejet/memories/blob/master/package.json
    tier: observed
  kind: self-hosted
  name: Nextcloud Memories
  page: /applications/photo-management/nextcloud-memories/
  slug: nextcloud-memories
  url: https://github.com/pulsejet/memories
- anchor: piwigo
  counts:
    declared: 0
    observed: 0
  evidence:
  - route: source code
    url: https://github.com/Piwigo/Piwigo/blob/master/README.md
  integrations: []
  kind: self-hosted
  name: Piwigo
  page: /applications/photo-management/piwigo/
  slug: piwigo
  url: https://github.com/Piwigo/Piwigo
- anchor: google-photos
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.google.android.apps.photos/latest/
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
    name: firebase
    provider: firebase
    says: ships the firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.google.android.apps.photos/latest/
    tier: observed
  kind: commercial
  name: Google Photos
  page: /applications/photo-management/google-photos/
  slug: google-photos
  url: https://photos.google.com
- anchor: flickr
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.flickr/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: facebook
    provider: facebook
    says: ships the facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.flickr/latest/
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
    name: firebase
    provider: firebase
    says: ships the firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.flickr/latest/
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
    name: flurry
    provider: flurry
    says: ships the flurry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.flickr/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3770.50
      key: audience-insights-research-management
      name: Audience Insights & Research Management
      url: /capabilities/audience-insights-research-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: google-admob
    provider: google-admob
    says: ships the google-admob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.flickr/latest/
    tier: observed
  kind: commercial
  name: Flickr
  page: /applications/photo-management/flickr/
  slug: flickr
  url: https://www.flickr.com
- anchor: amazon-photos
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.amazon.clouddrive.photos/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.10
      key: product-telemetry-instrumentation
      name: Product Telemetry Instrumentation
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: branch-io
    provider: branch-io
    says: ships the branch-io SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.amazon.clouddrive.photos/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: moengage
    provider: moengage
    says: ships the moengage SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.amazon.clouddrive.photos/latest/
    tier: observed
  kind: commercial
  name: Amazon Photos
  page: /applications/photo-management/amazon-photos/
  slug: amazon-photos
  url: https://www.amazon.com/photos
- anchor: apple-photos
  counts:
    declared: 0
    observed: 0
  evidence: []
  integrations: []
  kind: commercial
  name: Apple Photos
  page: /applications/photo-management/apple-photos/
  slug: apple-photos
  url: https://www.apple.com/ios/photos/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: photo-management
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Photo & Video
  store: apple-app-store
  url: https://apps.apple.com/us/charts/iphone/photo-video-apps/6008
- category: Photography
  store: google-play
  url: https://play.google.com/store/apps/category/PHOTOGRAPHY
name: Photo & Video Library Management
needs:
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  fit: exact
  layer: domain
  why: 'the library itself: ingest, organise, share; and the platforms (Nextcloud) it plugs into'
- capability:
    attribution: Turbo EA
    id: BC-3710.20
    key: metadata-cataloguing
    name: Metadata Cataloguing
    url: /capabilities/metadata-cataloguing/
    via_parent: null
  fit: exact
  layer: domain
  why: EXIF/XMP extraction, albums, tags, faces -- done locally in every self-hosted app (no provider)
- capability:
    attribution: API Evangelist extension
    id: AE-120
    key: AE-120
    name: Location & Mapping
    url: /capabilities/location-mapping/
    via_parent: null
  fit: exact
  layer: domain
  why: closest BC slug for map tiles + reverse geocoding (no geocoding capability exists in the model)
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: object storage for originals and derivatives (S3/B2/Wasabi)
- capability:
    attribution: Turbo EA
    id: BC-4230.60
    key: tenant-backup-export-management
    name: Tenant Backup & Export Management
    url: /capabilities/tenant-backup-export-management/
    via_parent: null
  fit: exact
  layer: common
  why: backup/export of the library
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: OIDC / social login
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  fit: exact
  layer: common
  why: local users, LDAP, WebAuthn
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: one-off sales (Lychee webshop)
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  fit: exact
  layer: common
  why: storage plans (Ente)
- capability:
    attribution: Turbo EA
    id: BC-3750.20
    key: subscription-entitlement-management
    name: Subscription & Entitlement Management
    url: /capabilities/subscription-entitlement-management/
    via_parent: null
  fit: exact
  layer: common
  why: app-store IAP receipt validation
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  fit: exact
  layer: common
  why: email, push, engagement messaging
- capability:
    attribution: Turbo EA
    id: BC-2510.40
    key: exception-and-alert-management
    name: Exception and Alert Management
    url: /capabilities/exception-and-alert-management/
    via_parent: null
  fit: exact
  layer: common
  why: ops alerting
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: mobile analytics in commercial apps
- capability:
    attribution: Turbo EA
    id: BC-4280.10
    key: product-telemetry-instrumentation
    name: Product Telemetry Instrumentation
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: null
  fit: exact
  layer: common
  why: deep links / attribution
- capability:
    attribution: Turbo EA
    id: BC-3770.50
    key: audience-insights-research-management
    name: Audience Insights & Research Management
    url: /capabilities/audience-insights-research-management/
    via_parent: null
  fit: exact
  layer: common
  why: ad SDKs (AdMob) -- weak fit
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: metrics/traces
- capability:
    attribution: Turbo EA
    id: BC-3770.40
    key: content-recommendation-modelling
    name: Content Recommendation Modelling
    url: /capabilities/content-recommendation-modelling/
    via_parent: null
  fit: exact
  layer: domain
  why: memories / on-this-day, smart search (local ML in self-hosted apps)
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
      agent_readiness: 45.8
      apps:
      - LibrePhotos
      band: developing
      in_catalog: true
      kin_score: 49.3
      mcp:
        source: https://github.com/mapbox/mcp-server
        status: verified
      name: mapbox
      slug: mapbox
      sources:
      - https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
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
      - LibrePhotos
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp:
        source: https://github.com/tomtom-international/tomtom-mcp
        status: verified
      name: tomtom
      slug: tomtom
      sources:
      - https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
      status: profiled
      tags:
      - Maps
      - Navigation
      - Traffic
      - Transportation
      tier: observed
      url: /providers/tomtom/
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - LibrePhotos
      band: developing
      in_catalog: true
      kin_score: 42.4
      mcp: &id001
        status: none
      name: nominatim
      slug: nominatim
      sources:
      - https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
      status: profiled
      tags: &id002
      - Geocoding
      - Location Services
      - Maps
      - OpenStreetMap
      tier: observed
      url: /providers/nominatim/
    - agent_band: agent-aware
      agent_readiness: 26.5
      apps:
      - LibrePhotos
      band: developing
      in_catalog: true
      kin_score: 40.3
      mcp: &id003
        status: none
      name: maptiler
      slug: maptiler
      sources:
      - https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
      status: profiled
      tags: &id004
      - Geospatial
      - Maps
      - Tiles
      - Vector Tiles
      tier: observed
      url: /providers/maptiler/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - LibrePhotos
      band: minimal
      in_catalog: true
      kin_score: 7.9
      mcp:
        source: https://github.com/OpenCageData/opencage-geocoding-mcp
        status: verified
      name: opencage
      slug: opencage
      sources:
      - https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/api/geocode/config.py
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Public APIs
      tier: observed
      url: /providers/opencage/
  - capability:
      attribution: Turbo EA
      id: BC-3710
      key: media-asset-management
      name: Media Asset Management
      url: /capabilities/media-asset-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - LibrePhotos
      - Nextcloud Memories
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp: &id005
        status: none
      name: nextcloud
      slug: nextcloud
      sources:
      - https://github.com/LibrePhotos/librephotos/blob/HEAD/apps/backend/requirements.txt
      - https://github.com/pulsejet/memories/blob/master/package.json
      status: profiled
      tags: &id006
      - Collaboration
      - File Sharing
      - File Sync
      - Self-Hosted
      tier: observed
      url: /providers/nextcloud/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.10
      key: AE-120.10.10
      name: Forward Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.9
      apps:
      - Lychee
      band: developing
      in_catalog: true
      kin_score: 42.4
      mcp: *id001
      name: nominatim
      slug: nominatim
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/nominatim/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20
      key: AE-120.20
      name: Maps & Tiles
      url: /capabilities/maps-tiles/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.5
      apps:
      - PhotoPrism
      band: developing
      in_catalog: true
      kin_score: 40.3
      mcp: *id003
      name: maptiler
      slug: maptiler
      sources:
      - https://docs.photoprism.app/getting-started/
      status: profiled
      tags: *id004
      tier: declared
      url: /providers/maptiler/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.40
      key: AE-120.40
      name: Places & Points of Interest
      url: /capabilities/places-points-of-interest/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Immich
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: none
      name: geonames
      slug: geonames
      sources:
      - https://github.com/immich-app/immich/blob/main/docs/docs/features/reverse-geocoding.md
      status: profiled
      tags:
      - Geocoding
      - Public APIs
      tier: declared
      url: /providers/geonames/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Flickr
      - Lychee
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: facebook
      slug: facebook
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.flickr/latest/
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - Lychee
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: github
      slug: github
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 33.2
      apps:
      - Lychee
      band: exemplar
      in_catalog: true
      kin_score: 74.5
      mcp:
        status: none
      name: authentik
      slug: authentik
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity Provider
      - LDAP
      tier: observed
      url: /providers/authentik/
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - Lychee
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        status: none
      name: microsoft-entra
      slug: microsoft-entra
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Lychee
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp: &id009
        status: none
      name: apple
      slug: apple
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags: &id010
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 31.8
      apps:
      - Lychee
      band: strong
      in_catalog: true
      kin_score: 54.6
      mcp:
        status: none
      name: authelia
      slug: authelia
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags:
      - Authentication
      - Authorization
      - LDAP
      - MFA
      tier: observed
      url: /providers/authelia/
    - agent_band: agent-ready
      agent_readiness: 46.8
      apps:
      - Lychee
      band: developing
      in_catalog: true
      kin_score: 46.7
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: amazon
      slug: amazon
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: observed
      url: /providers/amazon/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Lychee
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: google-identity-platform
      slug: google-identity-platform
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - Lychee
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        status: none
      name: keycloak
      slug: keycloak
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity and Access Management
      - OAuth
      tier: observed
      url: /providers/keycloak/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Lychee
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp: *id005
      name: nextcloud
      slug: nextcloud
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/nextcloud/
    - agent_band: agent-aware
      agent_readiness: 22.5
      apps:
      - Lychee
      band: thin
      in_catalog: true
      kin_score: 26.5
      mcp:
        status: none
      name: mastodon
      slug: mastodon
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags:
      - Open Source
      - Real-Time
      - Social
      - Social Network
      tier: observed
      url: /providers/mastodon/
    - agent_band: agent-aware
      agent_readiness: 20.1
      apps:
      - Lychee
      band: emerging
      in_catalog: true
      kin_score: 19.1
      mcp:
        status: none
      name: pocket-id
      slug: pocket-id
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags:
      - Company
      - Identity
      - OAuth
      - OpenID Connect
      tier: observed
      url: /providers/pocket-id/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Lychee
      band: minimal
      in_catalog: true
      kin_score: 7.5
      mcp:
        status: none
      name: kanidm
      slug: kanidm
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags:
      - Authentication
      - Company
      - Identity
      - Open Source
      tier: observed
      url: /providers/kanidm/
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 66.2
      apps:
      - Amazon Photos
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        status: none
      name: moengage
      slug: moengage
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.amazon.clouddrive.photos/latest/
      status: profiled
      tags:
      - Customer Data Platform
      - Customer Engagement
      - Marketing Automation
      - Push Notifications
      tier: observed
      url: /providers/moengage/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Ente Photos
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id007
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: firebase
      slug: firebase
      sources:
      - https://github.com/ente-io/ente/blob/main/server/configurations/local.yaml
      status: profiled
      tags: &id008
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: declared
      url: /providers/firebase/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Lychee
      band: thin
      in_catalog: true
      kin_score: 32.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: mailgun
      slug: mailgun
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/.env.example
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: declared
      url: /providers/mailgun/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - Lychee
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp: &id011
        source: https://docs.stripe.com/mcp
        status: verified
      name: stripe
      slug: stripe
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags: &id012
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-native
      agent_readiness: 73.2
      apps:
      - Lychee
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://docs.mollie.com/docs/mcp-server
        status: verified
      name: mollie
      slug: mollie
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags:
      - Company
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/mollie/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - Lychee
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: paypal
      slug: paypal
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
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
      - Flickr
      - Google Photos
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id007
      name: firebase
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.google.android.apps.photos/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.flickr/latest/
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/firebase/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Flickr
      band: emerging
      in_catalog: true
      kin_score: 20.6
      mcp:
        status: none
      name: flurry
      slug: flurry
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.flickr/latest/
      status: profiled
      tags:
      - Analytics
      - Company
      - Mobile
      - SDK
      tier: observed
      url: /providers/flurry/
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
      - Lychee
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: amazon-s3
      slug: amazon-s3
      sources:
      - https://github.com/LycheeOrg/Lychee/blob/master/composer.json
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Ente Photos
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        source: https://github.com/backblaze-labs/b2-mcp
        status: verified
      name: backblaze
      slug: backblaze
      sources:
      - https://github.com/ente-io/ente/blob/main/server/configurations/local.yaml
      status: profiled
      tags:
      - Backup
      - Cloud Storage
      - Object Storage
      - Storage
      tier: declared
      url: /providers/backblaze/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Ente Photos
      band: emerging
      in_catalog: true
      kin_score: 24.0
      mcp:
        status: none
      name: wasabi
      slug: wasabi
      sources:
      - https://github.com/ente-io/ente/blob/main/server/configurations/local.yaml
      status: profiled
      tags:
      - Cloud Storage
      - Object Storage
      - REST API
      - S3 Compatible
      tier: declared
      url: /providers/wasabi/
  - capability:
      attribution: Turbo EA
      id: BC-3750.20
      key: subscription-entitlement-management
      name: Subscription & Entitlement Management
      url: /capabilities/subscription-entitlement-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Ente Photos
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp: *id009
      name: apple
      slug: apple
      sources:
      - https://github.com/ente-io/ente/blob/main/server/go.mod
      status: profiled
      tags: *id010
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Ente Photos
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        status: none
      name: google-play
      slug: google-play
      sources:
      - https://github.com/ente-io/ente/blob/main/server/go.mod
      status: profiled
      tags:
      - Android
      - Application
      - Google Play
      - In-App Purchases
      tier: observed
      url: /providers/google-play/
  - capability:
      attribution: Turbo EA
      id: BC-3770.50
      key: audience-insights-research-management
      name: Audience Insights & Research Management
      url: /capabilities/audience-insights-research-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.0
      apps:
      - Flickr
      band: strong
      in_catalog: true
      kin_score: 61.5
      mcp:
        status: none
      name: google-admob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.yahoo.mobile.client.android.flickr/latest/
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
      id: BC-2510.40
      key: exception-and-alert-management
      name: Exception and Alert Management
      url: /capabilities/exception-and-alert-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Ente Photos
      band: developing
      in_catalog: true
      kin_score: 46.9
      mcp:
        status: none
      name: discord
      slug: discord
      sources:
      - https://github.com/ente-io/ente/blob/main/server/go.mod
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
  - capability:
      attribution: Turbo EA
      id: BC-4280.10
      key: product-telemetry-instrumentation
      name: Product Telemetry Instrumentation
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Amazon Photos
      band: emerging
      in_catalog: true
      kin_score: 23.0
      mcp:
        status: none
      name: branch-io
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.amazon.clouddrive.photos/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - Ente Photos
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp: *id011
      name: stripe
      slug: stripe
      sources:
      - https://github.com/ente-io/ente/blob/main/server/go.mod
      status: profiled
      tags: *id012
      tier: observed
      url: /providers/stripe/
  layer: common
summary:
  coverage_pct: 100.0
  declared_only: 5
  distinct_providers: 33
  in_catalog: 33
  mcp:
    documented: 0
    none: 21
    unchecked: 0
    verified: 12
  mcp_verified: 12
  mean_kin_score: 44.6
  observed: 28
  queued: 0
  reference_apps: 11
title: 'Photo & Video Library Management: application blueprint'
---
