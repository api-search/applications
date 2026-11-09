---
access: understanding
agent_layer: []
apps:
- anchor: privatebin
  counts:
    declared: 5
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/composer.json
  - route: source code
    url: https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Amazon S3
    provider: amazon-s3
    says: lists Amazon S3 as an integration
    source: https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Chhoto URL
    provider: chhoto-url
    says: lists Chhoto URL as an integration
    source: https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: lists Google Cloud Storage as an integration
    source: https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: Shlink
    provider: shlink
    says: lists Shlink as an integration
    source: https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    credit: null
    layer: domain
    name: YOURLS
    provider: yourls
    says: lists YOURLS as an integration
    source: https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
    tier: declared
  kind: self-hosted
  name: PrivateBin
  page: /applications/pastebin-file-drop/privatebin/
  slug: privatebin
  url: https://github.com/PrivateBin/PrivateBin
- anchor: psitransfer
  counts:
    declared: 0
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/psi-4ward/psitransfer/master/package.json
  - route: source code
    url: https://raw.githubusercontent.com/psi-4ward/psitransfer/master/config.js
  integrations: []
  kind: self-hosted
  name: PsiTransfer
  page: /applications/pastebin-file-drop/psitransfer/
  slug: psitransfer
  url: https://github.com/psi-4ward/psitransfer
- anchor: localsend
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/org.localsend.localsend_app/latest/
  - route: dependency manifest
    url: https://raw.githubusercontent.com/localsend/localsend/main/app/pubspec.yaml
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
    name: Apple App Store in-app purchase
    provider: apple
    says: ships the Apple App Store in-app purchase SDK or integration code
    source: https://raw.githubusercontent.com/localsend/localsend/main/app/pubspec.yaml
    tier: observed
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
    source: https://raw.githubusercontent.com/localsend/localsend/main/app/pubspec.yaml
    tier: observed
  kind: open-source-saas
  name: LocalSend
  page: /applications/pastebin-file-drop/localsend/
  slug: localsend
  url: https://github.com/localsend/localsend
- anchor: pingvin-share
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/stonith404/pingvin-share/main/backend/package.json
  - route: source code
    url: https://github.com/stonith404/pingvin-share/tree/main/backend/src/oauth/provider
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/stonith404/pingvin-share/main/backend/package.json
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
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/stonith404/pingvin-share/tree/main/backend/src/oauth/provider
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
    source: https://github.com/stonith404/pingvin-share/tree/main/backend/src/oauth/provider
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
    source: https://github.com/stonith404/pingvin-share/tree/main/backend/src/oauth/provider
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
    name: Microsoft sign-in (Entra ID)
    provider: microsoft-entra
    says: ships the Microsoft sign-in (Entra ID) SDK or integration code
    source: https://github.com/stonith404/pingvin-share/tree/main/backend/src/oauth/provider
    tier: observed
  kind: self-hosted
  name: Pingvin Share
  page: /applications/pastebin-file-drop/pingvin-share/
  slug: pingvin-share
  url: https://github.com/stonith404/pingvin-share
- anchor: send-(timvisee-fork-of-firefox-send)
  counts:
    declared: 1
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/timvisee/send/master/package.json
  - route: source code
    url: https://raw.githubusercontent.com/timvisee/send/master/server/config.js
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/timvisee/send/master/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://raw.githubusercontent.com/timvisee/send/master/package.json
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
    source: https://raw.githubusercontent.com/timvisee/send/master/package.json
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
    name: Mozilla accounts (Firefox Accounts)
    provider: mozilla-accounts
    says: lists Mozilla accounts (Firefox Accounts) as an integration
    source: https://raw.githubusercontent.com/timvisee/send/master/server/config.js
    tier: declared
  kind: self-hosted
  name: Send (timvisee fork of Firefox Send)
  page: /applications/pastebin-file-drop/send-timvisee-fork-of-firefox-send/
  slug: send-timvisee-fork-of-firefox-send
  url: https://github.com/timvisee/send
- anchor: zipline
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/diced/zipline/trunk/package.json
  - route: source code
    url: https://github.com/diced/zipline/tree/trunk/src/server/routes/api/auth/oauth
  - route: source code
    url: https://raw.githubusercontent.com/diced/zipline/trunk/src/lib/config/read/env.ts
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/diced/zipline/trunk/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://raw.githubusercontent.com/diced/zipline/trunk/src/lib/config/read/env.ts
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
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/diced/zipline/tree/trunk/src/server/routes/api/auth/oauth
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
    source: https://github.com/diced/zipline/tree/trunk/src/server/routes/api/auth/oauth
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
    source: https://github.com/diced/zipline/tree/trunk/src/server/routes/api/auth/oauth
    tier: observed
  kind: self-hosted
  name: Zipline
  page: /applications/pastebin-file-drop/zipline/
  slug: zipline
  url: https://github.com/diced/zipline
- anchor: wetransfer
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.wetransfer.app.live/latest/
  - route: documentation
    url: https://wetransfer.com/help-center
  - route: integrations page
    url: https://wetransfer.com/products/integrations
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
    name: Google CrashLytics
    provider: firebase
    says: ships the Google CrashLytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.wetransfer.app.live/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.wetransfer.app.live/latest/
    tier: observed
  kind: commercial
  name: WeTransfer
  page: /applications/pastebin-file-drop/wetransfer/
  slug: wetransfer
  url: https://wetransfer.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: pastebin-file-drop
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Utilities
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Tools
  store: google-play
  url: https://play.google.com/store/apps/category/TOOLS
- category: Pastebins
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#pastebins
- category: File Transfer - Single-click & Drag-n-drop Upload
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#file-transfer---single-click--drag-n-drop-upload
- category: File Transfer - Peer-to-peer Filesharing
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#file-transfer---peer-to-peer-filesharing
name: Pastebin, File Drop & Quick Share
needs:
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: file drops and pastes need a blob backend; S3 and GCS are the swappable datasources
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  fit: exact
  layer: domain
  why: short share links for pastes (PrivateBin shortener integrations)
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: hosted share servers gate uploads behind OAuth sign-in
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: upload notifications pushed to chat webhooks
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring of the upload server
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: common
  why: mobile clients take donations / upgrades through store billing
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product analytics SDKs ship in the mobile apps (Exodus)
stack:
- capabilities:
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
      - Pingvin Share
      - PrivateBin
      - Send (timvisee fork of Firefox Send)
      - Zipline
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
      - https://raw.githubusercontent.com/diced/zipline/trunk/package.json
      - https://raw.githubusercontent.com/stonith404/pingvin-share/main/backend/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.3
      apps:
      - PrivateBin
      - Send (timvisee fork of Firefox Send)
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
      - https://raw.githubusercontent.com/timvisee/send/master/package.json
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
  - capability:
      attribution: API Evangelist extension
      id: AE-913
      key: AE-913
      name: Link Shortening & Link-in-Bio
      url: /capabilities/digital-marketing-management/
      via_parent: Digital Marketing Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.2
      apps:
      - PrivateBin
      band: thin
      in_catalog: true
      kin_score: 29.0
      mcp:
        status: none
      name: Shlink
      slug: shlink
      sources:
      - https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
      status: profiled
      tags:
      - Company
      - PHP
      - Self-Hosted
      - URL Shorteners
      tier: declared
      url: /providers/shlink/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - PrivateBin
      band: emerging
      in_catalog: true
      kin_score: 14.8
      mcp:
        status: none
      name: YOURLS
      slug: yourls
      sources:
      - https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
      status: profiled
      tags:
      - Company
      - Open Source
      - PHP
      - URL Shorteners
      tier: declared
      url: /providers/yourls/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - PrivateBin
      band: minimal
      in_catalog: true
      kin_score: 5.6
      mcp:
        status: unknown
      name: Chhoto URL
      slug: chhoto-url
      sources:
      - https://raw.githubusercontent.com/PrivateBin/PrivateBin/master/cfg/conf.sample.php
      status: profiled
      tags:
      - Open Source
      - Rust
      - Self-Hosted
      - URL Shorteners
      tier: declared
      url: /providers/chhoto-url/
  layer: domain
- capabilities:
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
      - Pingvin Share
      - Zipline
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/diced/zipline/tree/trunk/src/server/routes/api/auth/oauth
      - https://github.com/stonith404/pingvin-share/tree/main/backend/src/oauth/provider
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Pingvin Share
      - Zipline
      band: developing
      in_catalog: true
      kin_score: 46.9
      mcp: &id001
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/diced/zipline/tree/trunk/src/server/routes/api/auth/oauth
      - https://github.com/stonith404/pingvin-share/tree/main/backend/src/oauth/provider
      status: profiled
      tags: &id002
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Pingvin Share
      - Zipline
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/diced/zipline/tree/trunk/src/server/routes/api/auth/oauth
      - https://github.com/stonith404/pingvin-share/tree/main/backend/src/oauth/provider
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - Pingvin Share
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        status: none
      name: Microsoft sign-in (Entra ID)
      slug: microsoft-entra
      sources:
      - https://github.com/stonith404/pingvin-share/tree/main/backend/src/oauth/provider
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-aware
      agent_readiness: 9.4
      apps:
      - Send (timvisee fork of Firefox Send)
      band: emerging
      in_catalog: true
      kin_score: 17.7
      mcp:
        status: none
      name: Mozilla accounts (Firefox Accounts)
      slug: mozilla-accounts
      sources:
      - https://raw.githubusercontent.com/timvisee/send/master/server/config.js
      status: profiled
      tags:
      - Authentication
      - Company
      - Identity
      - Mozilla
      tier: declared
      url: /providers/mozilla-accounts/
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - LocalSend
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Apple App Store in-app purchase
      slug: apple
      sources:
      - https://raw.githubusercontent.com/localsend/localsend/main/app/pubspec.yaml
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - LocalSend
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        status: none
      name: Google Play Billing
      slug: google-play
      sources:
      - https://raw.githubusercontent.com/localsend/localsend/main/app/pubspec.yaml
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
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Send (timvisee fork of Firefox Send)
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/timvisee/send/master/package.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - WeTransfer
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id003
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google CrashLytics
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.wetransfer.app.live/latest/
      status: profiled
      tags: &id004
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Zipline
      band: developing
      in_catalog: true
      kin_score: 46.9
      mcp: *id001
      name: Discord
      slug: discord
      sources:
      - https://raw.githubusercontent.com/diced/zipline/trunk/src/lib/config/read/env.ts
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/discord/
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
      - WeTransfer
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id003
      name: Google Firebase Analytics
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.wetransfer.app.live/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/firebase/
  layer: common
summary:
  coverage_pct: 100.0
  declared_only: 4
  distinct_providers: 14
  in_catalog: 14
  mcp:
    documented: 0
    none: 8
    unchecked: 0
    verified: 5
  mcp_verified: 5
  mean_kin_score: 47.9
  observed: 10
  queued: 0
  reference_apps: 7
title: 'Pastebin, File Drop & Quick Share: application blueprint'
---
