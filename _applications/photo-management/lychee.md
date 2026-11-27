---
app: Lychee
app_slug: lychee
app_url: https://github.com/LycheeOrg/Lychee
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-120.10.10
  key: AE-120.10.10
  layer: domain
  name: Forward Geocoding
  providers:
  - nominatim
  url: /capabilities/geocoding/
  via_parent: Geocoding
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: common
  name: Customer Lifecycle Engagement
  providers:
  - mailgun
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - mollie
  - paypal
  - stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - amazon-s3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - amazon
  - apple
  - authelia
  - authentik
  - facebook
  - github
  - google-identity-platform
  - kanidm
  - keycloak
  - mastodon
  - microsoft-entra
  - nextcloud
  - pocket-id
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: photo-management
  name: Photo & Video Library Management
  url: /applications/photo-management/
counts:
  declared: 1
  observed: 18
credits: []
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
  facts:
    agent_band: agent-native
    agent_readiness: 53.6
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id001
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id002
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id005
      status: none
    slug: apple
    status: profiled
    tags: &id006
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.2
    band: strong
    in_catalog: true
    kin_score: 55.6
    mcp: &id007
      status: none
    slug: authelia
    status: profiled
    tags: &id008
    - Authentication
    - Authorization
    - LDAP
    - MFA
    url: /providers/authelia/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.2
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id009
      status: none
    slug: authentik
    status: profiled
    tags: &id010
    - Authentication
    - Authorization
    - Identity Provider
    - LDAP
    url: /providers/authentik/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id011
      status: none
    slug: facebook
    status: profiled
    tags: &id012
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id013
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id014
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id015
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id016
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.5
    mcp: &id017
      status: none
    slug: kanidm
    status: profiled
    tags: &id018
    - Authentication
    - Company
    - Identity
    - Open Source
    url: /providers/kanidm/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 17.3
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id019
      status: none
    slug: keycloak
    status: profiled
    tags: &id020
    - Authentication
    - Authorization
    - Identity and Access Management
    - OAuth
    url: /providers/keycloak/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.0
    band: emerging
    in_catalog: true
    kin_score: 25.5
    mcp: &id023
      status: none
    slug: mastodon
    status: profiled
    tags: &id024
    - Open Source
    - Real-Time
    - Social
    - Social Network
    url: /providers/mastodon/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id025
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id026
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
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
  facts:
    agent_band: agent-native
    agent_readiness: 71.7
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id027
      source: https://docs.mollie.com/docs/mcp-server
      status: verified
    slug: mollie
    status: profiled
    tags: &id028
    - Company
    - Financial Services
    - Fintech
    - Payments
    url: /providers/mollie/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 32.7
    mcp: &id029
      status: none
    slug: nextcloud
    status: profiled
    tags: &id030
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.7
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id031
      status: none
    slug: nominatim
    status: profiled
    tags: &id032
    - Geocoding
    - Location Services
    - Maps
    - OpenStreetMap
    url: /providers/nominatim/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id033
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id034
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: emerging
    in_catalog: true
    kin_score: 25.1
    mcp: &id035
      status: none
    slug: pocket-id
    status: profiled
    tags: &id036
    - Company
    - Identity
    - OAuth
    - OpenID Connect
    url: /providers/pocket-id/
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
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id037
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id038
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id021
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id022
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: mailgun
  provider: mailgun
  says: lists mailgun as an integration
  source: https://github.com/LycheeOrg/Lychee/blob/master/.env.example
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/photo-management/lychee/
providers:
- agent_band: agent-native
  agent_readiness: 53.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id001
  name: amazon
  slug: amazon
  status: profiled
  tags: *id002
  url: /providers/amazon/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id003
  name: amazon-s3
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id005
  name: apple
  slug: apple
  status: profiled
  tags: *id006
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 31.2
  band: strong
  in_catalog: true
  kin_score: 55.6
  mcp: *id007
  name: authelia
  slug: authelia
  status: profiled
  tags: *id008
  url: /providers/authelia/
- agent_band: agent-ready
  agent_readiness: 37.2
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id009
  name: authentik
  slug: authentik
  status: profiled
  tags: *id010
  url: /providers/authentik/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id011
  name: facebook
  slug: facebook
  status: profiled
  tags: *id012
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id013
  name: github
  slug: github
  status: profiled
  tags: *id014
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id015
  name: google-identity-platform
  slug: google-identity-platform
  status: profiled
  tags: *id016
  url: /providers/google-identity-platform/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.5
  mcp: *id017
  name: kanidm
  slug: kanidm
  status: profiled
  tags: *id018
  url: /providers/kanidm/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id019
  name: keycloak
  slug: keycloak
  status: profiled
  tags: *id020
  url: /providers/keycloak/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id021
  name: mailgun
  slug: mailgun
  status: profiled
  tags: *id022
  url: /providers/mailgun/
- agent_band: agent-aware
  agent_readiness: 22.0
  band: emerging
  in_catalog: true
  kin_score: 25.5
  mcp: *id023
  name: mastodon
  slug: mastodon
  status: profiled
  tags: *id024
  url: /providers/mastodon/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id025
  name: microsoft-entra
  slug: microsoft-entra
  status: profiled
  tags: *id026
  url: /providers/microsoft-entra/
- agent_band: agent-native
  agent_readiness: 71.7
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id027
  name: mollie
  slug: mollie
  status: profiled
  tags: *id028
  url: /providers/mollie/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id029
  name: nextcloud
  slug: nextcloud
  status: profiled
  tags: *id030
  url: /providers/nextcloud/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id031
  name: nominatim
  slug: nominatim
  status: profiled
  tags: *id032
  url: /providers/nominatim/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id033
  name: paypal
  slug: paypal
  status: profiled
  tags: *id034
  url: /providers/paypal/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: emerging
  in_catalog: true
  kin_score: 25.1
  mcp: *id035
  name: pocket-id
  slug: pocket-id
  status: profiled
  tags: *id036
  url: /providers/pocket-id/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id037
  name: stripe
  slug: stripe
  status: profiled
  tags: *id038
  url: /providers/stripe/
siblings:
- name: Amazon Photos
  rows: 2
  url: /applications/photo-management/amazon-photos/
- name: Apple Photos
  rows: 0
  url: /applications/photo-management/apple-photos/
- name: Ente Photos
  rows: 7
  url: /applications/photo-management/ente-photos/
- name: Flickr
  rows: 4
  url: /applications/photo-management/flickr/
- name: Google Photos
  rows: 1
  url: /applications/photo-management/google-photos/
- name: Immich
  rows: 1
  url: /applications/photo-management/immich/
- name: LibrePhotos
  rows: 6
  url: /applications/photo-management/librephotos/
- name: Nextcloud Memories
  rows: 1
  url: /applications/photo-management/nextcloud-memories/
- name: PhotoPrism
  rows: 1
  url: /applications/photo-management/photoprism/
- name: Piwigo
  rows: 0
  url: /applications/photo-management/piwigo/
sitemap: true
title: 'Lychee: Photo & Video Library Management reference app'
---
