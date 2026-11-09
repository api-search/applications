---
access: understanding
agent_layer: []
apps:
- anchor: mastodon
  counts:
    declared: 0
    observed: 9
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/org.joinmastodon.android/latest/
  - route: dependency manifest
    url: https://github.com/mastodon/mastodon/blob/main/Gemfile
  - route: source code
    url: https://github.com/mastodon/mastodon/blob/main/.env.production.sample
  - route: source code
    url: https://github.com/mastodon/mastodon/tree/main/app/lib/translation_service
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
    source: https://github.com/mastodon/mastodon/blob/main/Gemfile
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
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://github.com/mastodon/mastodon/blob/main/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: DeepL
    provider: deepl
    says: ships the DeepL SDK or integration code
    source: https://github.com/mastodon/mastodon/tree/main/app/lib/translation_service
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: common
    name: Elasticsearch
    provider: elastic
    says: ships the Elasticsearch SDK or integration code
    source: https://github.com/mastodon/mastodon/blob/main/.env.production.sample
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: hCaptcha
    provider: hcaptcha
    says: ships the hCaptcha SDK or integration code
    source: https://github.com/mastodon/mastodon/blob/main/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: LibreTranslate
    provider: libre-translate
    says: ships the LibreTranslate SDK or integration code
    source: https://github.com/mastodon/mastodon/tree/main/app/lib/translation_service
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
    name: OpenStack Swift
    provider: openstack
    says: ships the OpenStack Swift SDK or integration code
    source: https://github.com/mastodon/mastodon/blob/main/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: PostgreSQL
    provider: postgresql
    says: ships the PostgreSQL SDK or integration code
    source: https://github.com/mastodon/mastodon/blob/main/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Redis
    provider: redis
    says: ships the Redis SDK or integration code
    source: https://github.com/mastodon/mastodon/blob/main/Gemfile
    tier: observed
  kind: open-source-saas
  name: Mastodon
  page: /applications/social-network/mastodon/
  slug: mastodon
  url: https://github.com/mastodon/mastodon
- anchor: bluesky
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/xyz.blueskyweb.app/latest/
  - route: dependency manifest
    url: https://github.com/bluesky-social/social-app/blob/main/package.json
  - route: source code
    url: https://github.com/bluesky-social/social-app/blob/main/.env.example
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
    name: bitdrift
    provider: bitdrift
    says: ships the bitdrift SDK or integration code
    source: https://github.com/bluesky-social/social-app/blob/main/package.json
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
    name: Expo
    provider: expo
    says: ships the Expo SDK or integration code
    source: https://github.com/bluesky-social/social-app/blob/main/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: null
    layer: common
    name: GrowthBook
    provider: growthbook
    says: ships the GrowthBook SDK or integration code
    source: https://github.com/bluesky-social/social-app/blob/main/package.json
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
    source: https://github.com/bluesky-social/social-app/blob/main/package.json
    tier: observed
  kind: open-source-saas
  name: Bluesky
  page: /applications/social-network/bluesky/
  slug: bluesky
  url: https://github.com/bluesky-social/social-app
- anchor: pixelfed
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: dependency manifest
    url: https://github.com/pixelfed/pixelfed/blob/dev/composer.json
  - route: source code
    url: https://github.com/pixelfed/pixelfed/blob/dev/.env.example
  - route: source code
    url: https://github.com/pixelfed/pixelfed/blob/dev/config/captcha.php
  - route: source code
    url: https://github.com/pixelfed/pixelfed/blob/dev/config/filesystems.php
  - route: source code
    url: https://github.com/pixelfed/pixelfed/blob/dev/config/services.php
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
    source: https://github.com/pixelfed/pixelfed/blob/dev/composer.json
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
    name: Amazon SES
    provider: amazon-ses
    says: ships the Amazon SES SDK or integration code
    source: https://github.com/pixelfed/pixelfed/blob/dev/config/services.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: Cloudflare Turnstile
    provider: cloudflare-turnstile
    says: ships the Cloudflare Turnstile SDK or integration code
    source: https://github.com/pixelfed/pixelfed/blob/dev/config/captcha.php
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
    name: DigitalOcean Spaces
    provider: digital-ocean
    says: ships the DigitalOcean Spaces SDK or integration code
    source: https://github.com/pixelfed/pixelfed/blob/dev/config/filesystems.php
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
    name: Expo push
    provider: expo
    says: ships the Expo push SDK or integration code
    source: https://github.com/pixelfed/pixelfed/blob/dev/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: hCaptcha
    provider: hcaptcha
    says: ships the hCaptcha SDK or integration code
    source: https://github.com/pixelfed/pixelfed/blob/dev/config/captcha.php
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
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://github.com/pixelfed/pixelfed/blob/dev/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MySQL
    provider: mysql
    says: ships the MySQL SDK or integration code
    source: https://github.com/pixelfed/pixelfed/blob/dev/.env.example
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: null
    layer: common
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://github.com/pixelfed/pixelfed/blob/dev/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Redis
    provider: redis
    says: ships the Redis SDK or integration code
    source: https://github.com/pixelfed/pixelfed/blob/dev/.env.example
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
    name: Resend
    provider: resend
    says: ships the Resend SDK or integration code
    source: https://github.com/pixelfed/pixelfed/blob/dev/composer.json
    tier: observed
  kind: self-hosted
  name: Pixelfed
  page: /applications/social-network/pixelfed/
  slug: pixelfed
  url: https://github.com/pixelfed/pixelfed
- anchor: misskey
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: dependency manifest
    url: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/package.json
  - route: dependency manifest
    url: https://github.com/misskey-dev/misskey/blob/develop/packages/frontend/package.json
  - route: source code
    url: https://github.com/misskey-dev/misskey/blob/develop/.config/example.yml
  - route: source code
    url: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/core/CaptchaService.ts
  - route: source code
    url: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/server/api/endpoints/notes/translate.ts
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
    source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: Cloudflare Turnstile
    provider: cloudflare-turnstile
    says: ships the Cloudflare Turnstile SDK or integration code
    source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/core/CaptchaService.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: DeepL
    provider: deepl
    says: ships the DeepL SDK or integration code
    source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/server/api/endpoints/notes/translate.ts
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://github.com/misskey-dev/misskey/blob/develop/packages/frontend/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: Google reCAPTCHA
    provider: google-recaptcha
    says: ships the Google reCAPTCHA SDK or integration code
    source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/core/CaptchaService.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: hCaptcha
    provider: hcaptcha
    says: ships the hCaptcha SDK or integration code
    source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/core/CaptchaService.ts
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: mCaptcha
    provider: mcaptcha
    says: ships the mCaptcha SDK or integration code
    source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/core/CaptchaService.ts
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: common
    name: Meilisearch
    provider: meilisearch
    says: ships the Meilisearch SDK or integration code
    source: https://github.com/misskey-dev/misskey/blob/develop/.config/example.yml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: PostgreSQL
    provider: postgresql
    says: ships the PostgreSQL SDK or integration code
    source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Redis
    provider: redis
    says: ships the Redis SDK or integration code
    source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/package.json
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
    source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/package.json
    tier: observed
  kind: self-hosted
  name: Misskey
  page: /applications/social-network/misskey/
  slug: misskey
  url: https://github.com/misskey-dev/misskey
- anchor: friendica
  counts:
    declared: 0
    observed: 20
  evidence:
  - route: dependency manifest
    url: https://github.com/friendica/friendica/blob/develop/composer.json
  - route: source code
    url: https://github.com/friendica/friendica-addons
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
    source: https://github.com/friendica/friendica-addons/tree/develop/s3_storage
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Bluesky
    provider: bluesky
    says: ships the Bluesky SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/bluesky
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    credit: null
    layer: domain
    name: Discourse
    provider: discourse
    says: ships the Discourse SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/discourse
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Dreamwidth
    provider: dreamwidth
    says: ships the Dreamwidth SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/dwpost
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
    name: GeoNames
    provider: geonames
    says: ships the GeoNames SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/geonames
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
    name: Google Maps
    provider: google-maps
    says: ships the Google Maps SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/googlemaps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: common
    name: Gravatar
    provider: gravatar
    says: ships the Gravatar SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/gravatar
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: IFTTT
    provider: ifttt
    says: ships the IFTTT SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/ifttt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: InsaneJournal
    provider: insanejournal
    says: ships the InsaneJournal SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/ijpost
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: Invidious
    provider: invidious
    says: ships the Invidious SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/invidious
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: common
    name: Libravatar
    provider: libravatar
    says: ships the Libravatar SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/libravatar
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: LiveJournal
    provider: livejournal
    says: ships the LiveJournal SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/ljpost
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
    name: Matomo
    provider: matomo
    says: ships the Matomo SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/piwik
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Nitter
    provider: nitter
    says: ships the Nitter SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/nitter
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
    name: OpenStreetMap
    provider: openstreetmap
    says: ships the OpenStreetMap SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/openstreetmap
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: common
    name: OpenWeatherMap
    provider: openweathermap
    says: ships the OpenWeatherMap SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/curweather
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: pnut.io
    provider: pnut
    says: ships the pnut.io SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/pnut
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Tumblr
    provider: tumblr
    says: ships the Tumblr SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/tumblr
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: WordPress
    provider: wordpress
    says: ships the WordPress SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/wppost
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: X (Twitter)
    provider: x
    says: ships the X (Twitter) SDK or integration code
    source: https://github.com/friendica/friendica-addons/tree/develop/twitter
    tier: observed
  kind: self-hosted
  name: Friendica
  page: /applications/social-network/friendica/
  slug: friendica
  url: https://github.com/friendica/friendica
- anchor: instagram
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.instagram.android/latest/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook Login / Notifications
    provider: facebook
    says: ships the Facebook Login / Notifications SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.instagram.android/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.instagram.android/latest/
    tier: observed
  kind: commercial
  name: Instagram
  page: /applications/social-network/instagram/
  slug: instagram
  url: https://www.instagram.com/
- anchor: threads
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.instagram.barcelona/latest/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook Login / Notifications
    provider: facebook
    says: ships the Facebook Login / Notifications SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.instagram.barcelona/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.instagram.barcelona/latest/
    tier: observed
  kind: commercial
  name: Threads
  page: /applications/social-network/threads/
  slug: threads
  url: https://www.threads.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: social-network
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Social Networking
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Social
  store: google-play
  url: https://play.google.com/store/apps/category/SOCIAL
- category: Communication - Social Networks and Forums
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#communication---social-networks-and-forums
name: Social Networking & Microblogging
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: domain
  why: cross-posting and bridging to other networks is how federated apps reach users on closed ones
- capability:
    attribution: Turbo EA
    id: BC-3780.40
    key: user-generated-content-moderation
    name: User-Generated Content Moderation
    url: /capabilities/user-generated-content-moderation/
    via_parent: null
  fit: exact
  layer: domain
  why: every network moderates posts and media; the reference apps do it in-house (Misskey runs a local NSFW model), no vendor observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: domain
  why: translate-this-post is standard in Mastodon and Misskey
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: domain
  why: long-form cross-posting to blogs and journals (Friendica)
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: media attachments dominate storage; every self-hosted app ships an S3 driver
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: common
  why: open signups attract spam; captcha is the signup gate
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: confirmation and notification mail
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: mobile clients
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  fit: exact
  layer: common
  why: live timelines
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  fit: exact
  layer: common
  why: post and user search
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: Postgres/MySQL plus Redis for timelines and queues
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error and crash monitoring
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  fit: exact
  layer: common
  why: staged rollouts (Bluesky)
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: instance analytics
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: common
  why: profile avatars
- capability:
    attribution: API Evangelist extension
    id: AE-120
    key: AE-120
    name: Location & Mapping
    url: /capabilities/location-mapping/
    via_parent: null
  fit: exact
  layer: common
  why: location-tagged posts
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: social sign-in SDK in the Android apps
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 61.2
      apps:
      - Friendica
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: X (Twitter)
      slug: x
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/twitter
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-aware
      agent_readiness: 26.2
      apps:
      - Friendica
      band: developing
      in_catalog: true
      kin_score: 45.1
      mcp:
        status: none
      name: Bluesky
      slug: bluesky
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/bluesky
      status: profiled
      tags:
      - At-Protocol
      - Decentralized
      - Federated
      - Open Source
      tier: observed
      url: /providers/bluesky/
    - agent_band: agent-aware
      agent_readiness: 12.9
      apps:
      - Friendica
      band: emerging
      in_catalog: true
      kin_score: 24.6
      mcp:
        status: unknown
      name: pnut.io
      slug: pnut
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/pnut
      status: profiled
      tags:
      - API-First
      - Community
      - Company
      - Social
      tier: observed
      url: /providers/pnut/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Friendica
      band: minimal
      in_catalog: true
      kin_score: 7.9
      mcp:
        status: none
      name: Tumblr
      slug: tumblr
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/tumblr
      status: profiled
      tags:
      - Public APIs
      - Social
      tier: observed
      url: /providers/tumblr/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Friendica
      band: minimal
      in_catalog: true
      kin_score: 5.4
      mcp:
        status: none
      name: Nitter
      slug: nitter
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/nitter
      status: profiled
      tags:
      - Company
      - Open Source
      - Privacy
      - TwitterAlternative
      tier: observed
      url: /providers/nitter/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - Friendica
      band: developing
      in_catalog: true
      kin_score: 46.0
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: WordPress
      slug: wordpress
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/wppost
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: observed
      url: /providers/wordpress/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Friendica
      band: emerging
      in_catalog: true
      kin_score: 13.2
      mcp:
        status: none
      name: Dreamwidth
      slug: dreamwidth
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/dwpost
      status: profiled
      tags:
      - Community
      - Company
      - Creative
      - Open Source
      tier: observed
      url: /providers/dreamwidth/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Friendica
      band: emerging
      in_catalog: true
      kin_score: 11.5
      mcp:
        status: unknown
      name: LiveJournal
      slug: livejournal
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/ljpost
      status: profiled
      tags:
      - Blogging
      - Community
      - Company
      - Social
      tier: observed
      url: /providers/livejournal/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Friendica
      band: minimal
      in_catalog: true
      kin_score: 3.1
      mcp:
        status: unknown
      name: InsaneJournal
      slug: insanejournal
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/ijpost
      status: profiled
      tags:
      - Blogging
      - Company
      - Journaling
      - Social Network
      tier: observed
      url: /providers/insanejournal/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.4
      apps:
      - Mastodon
      - Misskey
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://github.com/DeepL/deepl-mcp-server
        status: verified
      name: DeepL
      slug: deepl
      sources:
      - https://github.com/mastodon/mastodon/tree/main/app/lib/translation_service
      - https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/server/api/endpoints/notes/translate.ts
      status: profiled
      tags:
      - Artificial Intelligence
      - Deep Learning
      - Glossary
      - Localization
      tier: observed
      url: /providers/deepl/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Mastodon
      band: thin
      in_catalog: true
      kin_score: 26.2
      mcp:
        source: https://github.com/LibreTranslate/LibreTranslate-MCP
        status: verified
      name: LibreTranslate
      slug: libre-translate
      sources:
      - https://github.com/mastodon/mastodon/tree/main/app/lib/translation_service
      status: profiled
      tags:
      - Machine Translation
      - Natural Language Processing
      - Open Source
      - Translation
      tier: observed
      url: /providers/libre-translate/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50.10
      key: AE-170.50.10
      name: Online Communities
      url: /capabilities/social-networks-community/
      via_parent: Social Networks & Community
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Friendica
      band: thin
      in_catalog: true
      kin_score: 37.1
      mcp:
        source: https://github.com/discourse/discourse-mcp
        status: verified
      name: Discourse
      slug: discourse
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/discourse
      status: profiled
      tags:
      - Community
      - Forums
      - Open Source
      tier: observed
      url: /providers/discourse/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Friendica
      band: emerging
      in_catalog: true
      kin_score: 23.8
      mcp:
        status: none
      name: Invidious
      slug: invidious
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/invidious
      status: profiled
      tags:
      - Frontend
      - Open Source
      - Privacy
      - Video
      tier: observed
      url: /providers/invidious/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - Mastodon
      - Misskey
      - Pixelfed
      band: thin
      in_catalog: true
      kin_score: 31.5
      mcp:
        status: none
      name: hCaptcha
      slug: hcaptcha
      sources:
      - https://github.com/mastodon/mastodon/blob/main/Gemfile
      - https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/core/CaptchaService.ts
      - https://github.com/pixelfed/pixelfed/blob/dev/config/captcha.php
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Privacy
      - hCaptcha
      tier: observed
      url: /providers/hcaptcha/
    - agent_band: agent-aware
      agent_readiness: 23.1
      apps:
      - Misskey
      - Pixelfed
      band: thin
      in_catalog: true
      kin_score: 28.9
      mcp:
        source: https://github.com/cloudflare/mcp
        status: verified
      name: Cloudflare Turnstile
      slug: cloudflare-turnstile
      sources:
      - https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/core/CaptchaService.ts
      - https://github.com/pixelfed/pixelfed/blob/dev/config/captcha.php
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Cloudflare
      - Turnstile
      tier: observed
      url: /providers/cloudflare-turnstile/
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Misskey
      band: developing
      in_catalog: true
      kin_score: 48.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/core/CaptchaService.ts
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
    - agent_band: agent-aware
      agent_readiness: 15.8
      apps:
      - Misskey
      band: emerging
      in_catalog: true
      kin_score: 23.0
      mcp:
        status: none
      name: mCaptcha
      slug: mcaptcha
      sources:
      - https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/core/CaptchaService.ts
      status: profiled
      tags:
      - CAPTCHA
      - Company
      - Open Source
      - Privacy
      tier: observed
      url: /providers/mcaptcha/
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
      - Friendica
      - Mastodon
      - Misskey
      - Pixelfed
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/s3_storage
      - https://github.com/mastodon/mastodon/blob/main/Gemfile
      - https://github.com/misskey-dev/misskey/blob/develop/packages/backend/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - Mastodon
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/mastodon/mastodon/blob/main/Gemfile
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
    - agent_band: agent-ready
      agent_readiness: 44.6
      apps:
      - Pixelfed
      band: developing
      in_catalog: true
      kin_score: 45.0
      mcp:
        source: https://docs.digitalocean.com/reference/mcp/
        status: verified
      name: DigitalOcean Spaces
      slug: digital-ocean
      sources:
      - https://github.com/pixelfed/pixelfed/blob/dev/config/filesystems.php
      status: profiled
      tags:
      - Cloud
      - Compute
      - Infrastructure
      - Servers
      tier: observed
      url: /providers/digital-ocean/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Mastodon
      band: thin
      in_catalog: true
      kin_score: 36.1
      mcp:
        status: none
      name: OpenStack Swift
      slug: openstack
      sources:
      - https://github.com/mastodon/mastodon/blob/main/Gemfile
      status: profiled
      tags:
      - Cloud Platform
      - Infrastructure-as-a-Service
      - Open Source
      - OpenStack
      tier: observed
      url: /providers/openstack/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-native
      agent_readiness: 49.8
      apps:
      - Mastodon
      - Misskey
      - Pixelfed
      band: developing
      in_catalog: true
      kin_score: 47.4
      mcp:
        source: https://github.com/redis/mcp-redis
        status: verified
      name: Redis
      slug: redis
      sources:
      - https://github.com/mastodon/mastodon/blob/main/Gemfile
      - https://github.com/misskey-dev/misskey/blob/develop/packages/backend/package.json
      - https://github.com/pixelfed/pixelfed/blob/dev/.env.example
      status: profiled
      tags:
      - Cache
      - Database
      - In-Memory
      - Key-Value Store
      tier: observed
      url: /providers/redis/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Mastodon
      - Misskey
      band: emerging
      in_catalog: true
      kin_score: 12.2
      mcp:
        status: none
      name: PostgreSQL
      slug: postgresql
      sources:
      - https://github.com/mastodon/mastodon/blob/main/Gemfile
      - https://github.com/misskey-dev/misskey/blob/develop/packages/backend/package.json
      status: profiled
      tags:
      - Database
      - Open Source
      - Relational Database
      - SQL
      tier: observed
      url: /providers/postgresql/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Pixelfed
      band: thin
      in_catalog: true
      kin_score: 31.8
      mcp:
        status: none
      name: MySQL
      slug: mysql
      sources:
      - https://github.com/pixelfed/pixelfed/blob/dev/.env.example
      status: profiled
      tags:
      - Database
      - Open Source
      - RDBMS
      - Relational Database
      tier: observed
      url: /providers/mysql/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - Instagram
      - Misskey
      - Threads
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://github.com/misskey-dev/misskey/blob/develop/packages/frontend/package.json
      - https://reports.exodus-privacy.eu.org/en/reports/com.instagram.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.instagram.barcelona/latest/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 37.4
      apps:
      - Friendica
      band: exemplar
      in_catalog: true
      kin_score: 72.2
      mcp:
        source: https://github.com/matomo-org/plugin-McpServer
        status: verified
      name: Matomo
      slug: matomo
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/piwik
      status: profiled
      tags:
      - Analytics
      - Open Source
      - Privacy
      - Web Analytics
      tier: observed
      url: /providers/matomo/
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
      - Bluesky
      - Misskey
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/bluesky-social/social-app/blob/main/package.json
      - https://github.com/misskey-dev/misskey/blob/develop/packages/backend/package.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - Bluesky
      band: strong
      in_catalog: true
      kin_score: 58.6
      mcp:
        source: https://docs.bitdrift.io/ai/mcp.md
        status: verified
      name: bitdrift
      slug: bitdrift
      sources:
      - https://github.com/bluesky-social/social-app/blob/main/package.json
      status: profiled
      tags:
      - Company
      - Developer Tools
      - Mobile
      - Observability
      tier: observed
      url: /providers/bitdrift/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - Pixelfed
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://github.com/pixelfed/pixelfed/blob/dev/config/services.php
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
    - agent_band: agent-ready
      agent_readiness: 49.4
      apps:
      - Pixelfed
      band: strong
      in_catalog: true
      kin_score: 58.9
      mcp:
        source: https://resend.com/docs/mcp-server
        status: verified
      name: Resend
      slug: resend
      sources:
      - https://github.com/pixelfed/pixelfed/blob/dev/composer.json
      status: profiled
      tags:
      - Developer Tools
      - Email
      - Marketing Email
      - Transactional Email
      tier: observed
      url: /providers/resend/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Pixelfed
      band: thin
      in_catalog: true
      kin_score: 32.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://github.com/pixelfed/pixelfed/blob/dev/composer.json
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.30
      key: AE-170.30.30
      name: Avatars, GIFs & Stickers
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.3
      apps:
      - Friendica
      band: developing
      in_catalog: true
      kin_score: 39.8
      mcp:
        source: https://github.com/Automattic/mcp-server-gravatar
        status: verified
      name: Gravatar
      slug: gravatar
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/gravatar
      status: profiled
      tags:
      - Avatars
      - Identity
      - Profiles
      - Social
      tier: observed
      url: /providers/gravatar/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Friendica
      band: emerging
      in_catalog: true
      kin_score: 14.3
      mcp:
        status: none
      name: Libravatar
      slug: libravatar
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/libravatar
      status: profiled
      tags:
      - Avatars
      - Company
      - Federated
      - Open Source
      tier: observed
      url: /providers/libravatar/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - Friendica
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps
      slug: google-maps
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/googlemaps
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - Friendica
      band: developing
      in_catalog: true
      kin_score: 44.4
      mcp:
        status: none
      name: OpenStreetMap
      slug: openstreetmap
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/openstreetmap
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
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.3
      apps:
      - Bluesky
      - Pixelfed
      band: thin
      in_catalog: true
      kin_score: 31.4
      mcp:
        source: https://github.com/expo/expo-mcp
        status: verified
      name: Expo
      slug: expo
      sources:
      - https://github.com/bluesky-social/social-app/blob/main/package.json
      - https://github.com/pixelfed/pixelfed/blob/dev/composer.json
      status: profiled
      tags:
      - Build Automation
      - Mobile Development
      - Over-the-Air Updates
      - React Native
      tier: observed
      url: /providers/expo/
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - Mastodon
      band: exemplar
      in_catalog: true
      kin_score: 70.2
      mcp:
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elasticsearch
      slug: elastic
      sources:
      - https://github.com/mastodon/mastodon/blob/main/.env.production.sample
      status: profiled
      tags:
      - Analytics
      - Observability
      - Search
      - Security
      tier: observed
      url: /providers/elastic/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Misskey
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        source: https://github.com/meilisearch/meilisearch-mcp
        status: verified
      name: Meilisearch
      slug: meilisearch
      sources:
      - https://github.com/misskey-dev/misskey/blob/develop/.config/example.yml
      status: profiled
      tags:
      - AI Search
      - Full-Text Search
      - Hybrid Search
      - Open Source
      tier: observed
      url: /providers/meilisearch/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Instagram
      - Threads
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        status: none
      name: Facebook Login / Notifications
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.instagram.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.instagram.barcelona/latest/
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.3
      apps:
      - Bluesky
      band: thin
      in_catalog: true
      kin_score: 35.1
      mcp:
        source: https://github.com/growthbook/growthbook-mcp
        status: verified
      name: GrowthBook
      slug: growthbook
      sources:
      - https://github.com/bluesky-social/social-app/blob/main/package.json
      status: profiled
      tags:
      - A/B Testing
      - Experimentation
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/growthbook/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Pixelfed
      band: thin
      in_catalog: true
      kin_score: 38.6
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://github.com/pixelfed/pixelfed/blob/dev/composer.json
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.10.20
      key: AE-120.10.20
      name: Reverse Geocoding
      url: /capabilities/geocoding/
      via_parent: Geocoding
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Friendica
      band: minimal
      in_catalog: true
      kin_score: 5.2
      mcp:
        status: none
      name: GeoNames
      slug: geonames
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/geonames
      status: profiled
      tags:
      - Geocoding
      - Public APIs
      tier: observed
      url: /providers/geonames/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.5
      apps:
      - Friendica
      band: strong
      in_catalog: true
      kin_score: 60.4
      mcp:
        source: https://mcp.openweathermap.org/
        status: verified
      name: OpenWeatherMap
      slug: openweathermap
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/curweather
      status: profiled
      tags:
      - Air Pollution
      - Climate
      - Forecast
      - Weather
      tier: observed
      url: /providers/openweathermap/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.3
      apps:
      - Friendica
      band: emerging
      in_catalog: true
      kin_score: 25.0
      mcp:
        source: https://github.com/IFTTT/ifttt-plugins
        status: verified
      name: IFTTT
      slug: ifttt
      sources:
      - https://github.com/friendica/friendica-addons/tree/develop/ifttt
      status: profiled
      tags:
      - Automation
      - No-Code
      - Webhook
      - iPaaS
      tier: observed
      url: /providers/ifttt/
  layer: common
summary:
  coverage_pct: 100.0
  declared_only: 0
  distinct_providers: 44
  in_catalog: 44
  mcp:
    documented: 0
    none: 17
    unchecked: 0
    verified: 24
  mcp_verified: 24
  mean_kin_score: 41.2
  observed: 44
  queued: 0
  reference_apps: 7
title: 'Social Networking & Microblogging: application blueprint'
---
