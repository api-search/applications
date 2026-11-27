---
access: understanding
agent_layer:
- app: Readwise Reader
  finding: Readwise MCP server connects Claude, ChatGPT, Cursor or any MCP client to the Reader library
  source: https://readwise.io/read
  tier: declared
apps:
- anchor: miniflux
  counts:
    declared: 0
    observed: 28
  evidence:
  - route: source code
    url: https://github.com/miniflux/v2/tree/main/internal/integration
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Apprise
    provider: apprise
    says: ships the Apprise SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Betula
    provider: betula
    says: ships the Betula SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Cubox
    provider: cubox
    says: ships the Cubox SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Espial
    provider: espial
    says: ships the Espial SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    name: Gotify
    provider: gotify
    says: ships the Gotify SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Instapaper
    provider: instapaper
    says: ships the Instapaper SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.40
      key: AE-230.40.40
      name: Web Archiving & Page Snapshots
      url: /capabilities/web-data/
      via_parent: Web Data
    credit: null
    layer: domain
    name: Internet Archive (Wayback save)
    provider: internet-archive
    says: ships the Internet Archive (Wayback save) SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Karakeep
    provider: karakeep
    says: ships the Karakeep SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: LinkAce
    provider: linkace
    says: ships the LinkAce SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: linkding
    provider: linkding
    says: ships the linkding SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: LinkTaco
    provider: linktaco
    says: ships the LinkTaco SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Linkwarden
    provider: linkwarden
    says: ships the Linkwarden SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Matrix
    provider: matrix
    says: ships the Matrix SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.10
      key: knowledge-capture-management
      name: Knowledge Capture Management
      url: /capabilities/knowledge-capture-management/
      via_parent: null
    credit: null
    layer: domain
    name: Notion
    provider: notion
    says: ships the Notion SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    name: ntfy
    provider: ntfy
    says: ships the ntfy SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Omnivore
    provider: omnivore
    says: ships the Omnivore SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Pinboard
    provider: pinboard
    says: ships the Pinboard SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
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
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Raindrop.io
    provider: raindrop-io
    says: ships the Raindrop.io SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Readeck
    provider: readeck
    says: ships the Readeck SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Readwise
    provider: readwise
    says: ships the Readwise SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: RSS-Bridge
    provider: rss-bridge
    says: ships the RSS-Bridge SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Shaarli
    provider: shaarli
    says: ships the Shaarli SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Shiori
    provider: shiori
    says: ships the Shiori SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Wallabag
    provider: wallabag
    says: ships the Wallabag SDK or integration code
    source: https://github.com/miniflux/v2/tree/main/internal/integration
    tier: observed
  kind: self-hosted
  name: Miniflux
  page: /applications/news-feed-reader/miniflux/
  slug: miniflux
  url: https://github.com/miniflux/v2
- anchor: freshrss
  counts:
    declared: 0
    observed: 21
  evidence:
  - route: source code
    url: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
  integrations:
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
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    name: Buffer
    provider: buffer
    says: ships the Buffer SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    name: diaspora*
    provider: diaspora
    says: ships the diaspora* SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    name: Lemmy
    provider: lemmy
    says: ships the Lemmy SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: LinkAce
    provider: linkace
    says: ships the LinkAce SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: linkding
    provider: linkding
    says: ships the linkding SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    name: LinkedIn
    provider: linkedin
    says: ships the LinkedIn SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    name: Mastodon
    provider: mastodon
    says: ships the Mastodon SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Nextcloud Bookmarks
    provider: nextcloud
    says: ships the Nextcloud Bookmarks SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Omnivore
    provider: omnivore
    says: ships the Omnivore SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Pinboard
    provider: pinboard
    says: ships the Pinboard SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    name: Pinterest
    provider: pinterest
    says: ships the Pinterest SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Raindrop.io
    provider: raindrop-io
    says: ships the Raindrop.io SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    name: Reddit
    provider: reddit
    says: ships the Reddit SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Shaarli
    provider: shaarli
    says: ships the Shaarli SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Wallabag
    provider: wallabag
    says: ships the Wallabag SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
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
    name: XING
    provider: xing
    says: ships the XING SDK or integration code
    source: https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
    tier: observed
  kind: self-hosted
  name: FreshRSS
  page: /applications/news-feed-reader/freshrss/
  slug: freshrss
  url: https://github.com/FreshRSS/FreshRSS
- anchor: wallabag
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/fr.gaulupeau.apps.InThePoche/latest/
  - route: dependency manifest
    url: https://github.com/wallabag/wallabag/blob/master/composer.json
  - route: source code
    url: https://github.com/wallabag/wallabag/tree/master/src/Import
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Gmail
    provider: google-gmail
    says: ships the Gmail SDK or integration code
    source: https://github.com/wallabag/wallabag/blob/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Instapaper
    provider: instapaper
    says: ships the Instapaper SDK or integration code
    source: https://github.com/wallabag/wallabag/tree/master/src/Import
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
    name: Matomo (Piwik)
    provider: matomo
    says: ships the Matomo (Piwik) SDK or integration code
    source: https://github.com/wallabag/wallabag/blob/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Omnivore
    provider: omnivore
    says: ships the Omnivore SDK or integration code
    source: https://github.com/wallabag/wallabag/tree/master/src/Import
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Pinboard
    provider: pinboard
    says: ships the Pinboard SDK or integration code
    source: https://github.com/wallabag/wallabag/tree/master/src/Import
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Pocket
    provider: pocket
    says: ships the Pocket SDK or integration code
    source: https://github.com/wallabag/wallabag/tree/master/src/Import
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
    source: https://github.com/wallabag/wallabag/blob/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Shaarli
    provider: shaarli
    says: ships the Shaarli SDK or integration code
    source: https://github.com/wallabag/wallabag/tree/master/src/Import
    tier: observed
  kind: self-hosted
  name: Wallabag
  page: /applications/news-feed-reader/wallabag/
  slug: wallabag
  url: https://github.com/wallabag/wallabag
- anchor: karakeep
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://github.com/karakeep-app/karakeep/blob/main/apps/mobile/package.json
  - route: dependency manifest
    url: https://github.com/karakeep-app/karakeep/blob/main/packages/shared/package.json
  - route: source code
    url: https://github.com/karakeep-app/karakeep/blob/main/packages/shared/config.ts
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: Ollama
    provider: ollama
    says: ships the Ollama SDK or integration code
    source: https://github.com/karakeep-app/karakeep/blob/main/packages/shared/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/karakeep-app/karakeep/blob/main/packages/shared/package.json
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
    name: RevenueCat
    provider: revenuecat
    says: ships the RevenueCat SDK or integration code
    source: https://github.com/karakeep-app/karakeep/blob/main/packages/shared/config.ts
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
    source: https://github.com/karakeep-app/karakeep/blob/main/apps/mobile/package.json
    tier: observed
  kind: self-hosted
  name: Karakeep
  page: /applications/news-feed-reader/karakeep/
  slug: karakeep
  url: https://github.com/karakeep-app/karakeep
- anchor: linkwarden
  counts:
    declared: 0
    observed: 55
  evidence:
  - route: source code
    url: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Amazon Cognito
    provider: amazon-cognito
    says: ships the Amazon Cognito SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Apple
    provider: apple
    says: ships the Apple SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Atlassian
    provider: atlassian
    says: ships the Atlassian SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Authelia
    provider: authelia
    says: ships the Authelia SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Authentik
    provider: authentik
    says: ships the Authentik SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Azure AD / B2C
    provider: microsoft-entra
    says: ships the Azure AD / B2C SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: Azure OpenAI
    provider: microsoft-azure-openai
    says: ships the Azure OpenAI SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Battle.net
    provider: battle-net
    says: ships the Battle.net SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Box
    provider: box
    says: ships the Box SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Bungie
    provider: bungie
    says: ships the Bungie SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Coinbase
    provider: coinbase
    says: ships the Coinbase SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Dropbox
    provider: dropbox
    says: ships the Dropbox SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Foursquare
    provider: foursquare
    says: ships the Foursquare SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: FreshBooks
    provider: freshbooks
    says: ships the FreshBooks SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: FusionAuth
    provider: fusionauth
    says: ships the FusionAuth SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Google
    provider: google-identity-platform
    says: ships the Google SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: HubSpot
    provider: hubspot
    says: ships the HubSpot SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Kakao
    provider: kakao
    says: ships the Kakao SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Keycloak
    provider: keycloak
    says: ships the Keycloak SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: LINE
    provider: line
    says: ships the LINE SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: LinkedIn
    provider: linkedin
    says: ships the LinkedIn SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Mailchimp
    provider: mailchimp
    says: ships the Mailchimp SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Naver
    provider: naver
    says: ships the Naver SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Netlify
    provider: netlify
    says: ships the Netlify SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Okta
    provider: okta
    says: ships the Okta SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: Ollama
    provider: ollama
    says: ships the Ollama SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: OneLogin
    provider: onelogin
    says: ships the OneLogin SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: OpenRouter
    provider: openrouter
    says: ships the OpenRouter SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Patreon
    provider: patreon
    says: ships the Patreon SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: Perplexity
    provider: perplexity
    says: ships the Perplexity SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Pinterest
    provider: pinterest
    says: ships the Pinterest SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Pipedrive
    provider: pipedrive
    says: ships the Pipedrive SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Reddit
    provider: reddit
    says: ships the Reddit SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Salesforce
    provider: salesforce
    says: ships the Salesforce SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Spotify
    provider: spotify
    says: ships the Spotify SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Strava
    provider: strava
    says: ships the Strava SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Synology
    provider: synology
    says: ships the Synology SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Todoist
    provider: todoist
    says: ships the Todoist SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Twitch
    provider: twitch
    says: ships the Twitch SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: VK
    provider: vk
    says: ships the VK SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Wikimedia
    provider: wikimedia
    says: ships the Wikimedia SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: WordPress.com
    provider: wordpress
    says: ships the WordPress.com SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Yandex ID
    provider: yandex
    says: ships the Yandex ID SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Zitadel
    provider: zitadel
    says: ships the Zitadel SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Zoho
    provider: zoho
    says: ships the Zoho SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
    name: Zoom
    provider: zoom
    says: ships the Zoom SDK or integration code
    source: https://github.com/linkwarden/linkwarden/blob/main/.env.sample
    tier: observed
  kind: open-source-saas
  name: Linkwarden
  page: /applications/news-feed-reader/linkwarden/
  slug: linkwarden
  url: https://github.com/linkwarden/linkwarden
- anchor: newsblur
  counts:
    declared: 0
    observed: 11
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.newsblur/latest/
  - route: dependency manifest
    url: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
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
    source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
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
    name: Apple (APNs)
    provider: apple
    says: ships the Apple (APNs) SDK or integration code
    source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: Google Gemini
    provider: google-gemini
    says: ships the Google Gemini SDK or integration code
    source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
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
    source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: common
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
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
    name: PayPal
    provider: paypal
    says: ships the PayPal SDK or integration code
    source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
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
    source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
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
    name: Sign in with Apple
    provider: apple
    says: ships the Sign in with Apple SDK or integration code
    source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
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
    source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
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
    source: https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
    tier: observed
  kind: open-source-saas
  name: NewsBlur
  page: /applications/news-feed-reader/newsblur/
  slug: newsblur
  url: https://github.com/samuelclay/NewsBlur
- anchor: feedly
  counts:
    declared: 8
    observed: 0
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.devhd.feedly/latest/
  - route: integrations page
    url: https://docs.feedly.com/collection/420-integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Buffer
    provider: buffer
    says: lists Buffer as an integration
    source: https://docs.feedly.com/collection/420-integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.10
      key: knowledge-capture-management
      name: Knowledge Capture Management
      url: /capabilities/knowledge-capture-management/
      via_parent: null
    credit: null
    layer: domain
    name: Evernote
    provider: evernote
    says: lists Evernote as an integration
    source: https://docs.feedly.com/collection/420-integrations
    tier: declared
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
    says: lists IFTTT as an integration
    source: https://docs.feedly.com/collection/420-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://docs.feedly.com/collection/420-integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.10
      key: knowledge-capture-management
      name: Knowledge Capture Management
      url: /capabilities/knowledge-capture-management/
      via_parent: null
    credit: null
    layer: domain
    name: OneNote
    provider: microsoft-onenote
    says: lists OneNote as an integration
    source: https://docs.feedly.com/collection/420-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Pocket
    provider: pocket
    says: lists Pocket as an integration
    source: https://docs.feedly.com/collection/420-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://docs.feedly.com/collection/420-integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://docs.feedly.com/collection/420-integrations
    tier: declared
  kind: commercial
  name: Feedly
  page: /applications/news-feed-reader/feedly/
  slug: feedly
  url: https://feedly.com/
- anchor: readwise-reader
  counts:
    declared: 10
    observed: 0
  evidence:
  - route: integrations page
    url: https://readwise.io/read
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.20
      key: AE-170.60.20
      name: Books & E-Books
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Amazon Kindle
    provider: amazon
    says: lists Amazon Kindle as an integration
    source: https://readwise.io/read
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.10
      key: knowledge-capture-management
      name: Knowledge Capture Management
      url: /capabilities/knowledge-capture-management/
      via_parent: null
    credit: null
    layer: domain
    name: Evernote
    provider: evernote
    says: lists Evernote as an integration
    source: https://readwise.io/read
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Instapaper
    provider: instapaper
    says: lists Instapaper as an integration
    source: https://readwise.io/read
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.10
      key: knowledge-capture-management
      name: Knowledge Capture Management
      url: /capabilities/knowledge-capture-management/
      via_parent: null
    credit: null
    layer: domain
    name: Logseq
    provider: logseq
    says: lists Logseq as an integration
    source: https://readwise.io/read
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.10
      key: knowledge-capture-management
      name: Knowledge Capture Management
      url: /capabilities/knowledge-capture-management/
      via_parent: null
    credit: null
    layer: domain
    name: Notion
    provider: notion
    says: lists Notion as an integration
    source: https://readwise.io/read
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.10
      key: knowledge-capture-management
      name: Knowledge Capture Management
      url: /capabilities/knowledge-capture-management/
      via_parent: null
    credit: null
    layer: domain
    name: Obsidian
    provider: obsidian
    says: lists Obsidian as an integration
    source: https://readwise.io/read
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Pocket
    provider: pocket
    says: lists Pocket as an integration
    source: https://readwise.io/read
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.10
      key: knowledge-capture-management
      name: Knowledge Capture Management
      url: /capabilities/knowledge-capture-management/
      via_parent: null
    credit: null
    layer: domain
    name: Roam Research
    provider: roam-research
    says: lists Roam Research as an integration
    source: https://readwise.io/read
    tier: declared
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
    says: lists X (Twitter) as an integration
    source: https://readwise.io/read
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: YouTube
    provider: youtube
    says: lists YouTube as an integration
    source: https://readwise.io/read
    tier: declared
  kind: commercial
  name: Readwise Reader
  page: /applications/news-feed-reader/readwise-reader/
  slug: readwise-reader
  url: https://readwise.io/read
author: API Evangelist
candidates: []
credits: []
html: public
id: news-feed-reader
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: News
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Magazines & Newspapers
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: News & Magazines
  store: google-play
  url: https://play.google.com/store/apps/category/NEWS_AND_MAGAZINES
- category: Feed Readers
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#feed-readers
- category: Bookmarks and Link Sharing
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#bookmarks-and-link-sharing
- category: Archiving and Digital Preservation (DP)
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#archiving-and-digital-preservation-dp
name: News, Feeds & Read-Later
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: common
  why: AI tagging, summarisation and chat over saved content (Karakeep, Linkwarden, NewsBlur).
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: common
  why: OpenRouter as an LLM backend in Linkwarden.
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: Account and 2FA email (Wallabag google-mailer).
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: FreshRSS share-to-WhatsApp.
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: New-entry and saved-item notifications (ntfy, Gotify, Pushover, Apprise, APNs).
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: common
  why: Entries pushed to Slack, Discord, Matrix, Telegram and Microsoft Teams.
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: Consumer sign-in (Linkwarden NextAuth providers, NewsBlur Apple/Google sign-in).
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  fit: exact
  layer: domain
  why: Readwise Reader ingests YouTube videos and transcripts as reading documents.
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: domain
  why: Share-to targets (Mastodon, Bluesky, Reddit, LinkedIn, X) and social content sources (X threads).
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.20
    key: AE-170.60.20
    name: Books & E-Books
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  fit: exact
  layer: domain
  why: Send-to-Kindle delivery of saved articles.
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.40
    key: AE-170.60.40
    name: Bookmarks, Read-Later & Feed Readers
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  fit: exact
  layer: domain
  why: 'The category itself: read-later services, bookmark managers and feed generators are what a reader saves to, imports from or syncs with.'
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: common
  why: Karakeep mobile subscriptions via RevenueCat.
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: Feedly integrations through Zapier and IFTTT.
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  fit: exact
  layer: common
  why: Full-text search backend (Meilisearch) for saved-link search; no node fits.
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: Object storage for archives, icons and screenshots (S3, DigitalOcean Spaces).
- capability:
    attribution: Turbo EA
    id: BC-830.10
    key: knowledge-capture-management
    name: Knowledge Capture Management
    url: /capabilities/knowledge-capture-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: Highlights and saved articles exported to note apps (Notion, Obsidian, Evernote, OneNote, Logseq, Roam).
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.40
    key: AE-230.40.40
    name: Web Archiving & Page Snapshots
    url: /capabilities/web-data/
    via_parent: Web Data
  fit: exact
  layer: domain
  why: Web page archiving and snapshots (Wayback Machine save); no node fits.
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: nearest
  layer: common
  why: Error monitoring (Sentry).
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: Premium subscriptions (NewsBlur Stripe, PayPal).
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: Matomo/Piwik tracking in Wallabag.
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: Workforce/self-hosted IdPs for SSO (Okta, Entra, Cognito, Authentik, Keycloak).
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    providers:
    - agent_band: agent-aware
      agent_readiness: 8.5
      apps:
      - Miniflux
      - Readwise Reader
      - Wallabag
      band: thin
      in_catalog: true
      kin_score: 30.7
      mcp:
        status: none
      name: Instapaper
      slug: instapaper
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      - https://github.com/wallabag/wallabag/tree/master/src/Import
      - https://readwise.io/read
      status: profiled
      tags:
      - Company
      - Productivity
      - Read-it-later
      - Web Service
      tier: observed
      url: /providers/instapaper/
    - agent_band: agent-aware
      agent_readiness: 5.3
      apps:
      - FreshRSS
      - Miniflux
      - Wallabag
      band: thin
      in_catalog: true
      kin_score: 30.5
      mcp:
        status: unknown
      name: Pinboard
      slug: pinboard
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      - https://github.com/miniflux/v2/tree/main/internal/integration
      - https://github.com/wallabag/wallabag/tree/master/src/Import
      status: profiled
      tags:
      - Bookmarking
      - Company
      - Productivity
      - Social
      tier: observed
      url: /providers/pinboard/
    - agent_band: agent-aware
      agent_readiness: 20.2
      apps:
      - FreshRSS
      - Miniflux
      - Wallabag
      band: thin
      in_catalog: true
      kin_score: 26.8
      mcp:
        status: none
      name: Shaarli
      slug: shaarli
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      - https://github.com/miniflux/v2/tree/main/internal/integration
      - https://github.com/wallabag/wallabag/tree/master/src/Import
      status: profiled
      tags:
      - Bookmarking
      - Open Source
      - PHP
      - Self-Hosted
      tier: observed
      url: /providers/shaarli/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Feedly
      - Readwise Reader
      - Wallabag
      band: minimal
      in_catalog: true
      kin_score: 3.3
      mcp:
        status: none
      name: Pocket
      slug: pocket
      sources:
      - https://docs.feedly.com/collection/420-integrations
      - https://github.com/wallabag/wallabag/tree/master/src/Import
      - https://readwise.io/read
      status: profiled
      tags:
      - Bookmarking
      - Productivity
      - Public APIs
      tier: observed
      url: /providers/pocket/
    - agent_band: null
      agent_readiness: null
      apps:
      - FreshRSS
      - Miniflux
      - Wallabag
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Omnivore
      slug: omnivore
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      - https://github.com/miniflux/v2/tree/main/internal/integration
      - https://github.com/wallabag/wallabag/tree/master/src/Import
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 32.1
      apps:
      - FreshRSS
      - Miniflux
      band: thin
      in_catalog: true
      kin_score: 32.8
      mcp:
        status: none
      name: LinkAce
      slug: linkace
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Bookmarking
      - Company
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/linkace/
    - agent_band: agent-aware
      agent_readiness: 21.1
      apps:
      - FreshRSS
      - Miniflux
      band: thin
      in_catalog: true
      kin_score: 29.1
      mcp:
        source: https://help.raindrop.io/integrations/mcp
        status: verified
      name: Raindrop.io
      slug: raindrop-io
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Bookmark
      - Cloud
      - Collaboration
      - Productivity
      tier: observed
      url: /providers/raindrop-io/
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - FreshRSS
      - Miniflux
      band: emerging
      in_catalog: true
      kin_score: 20.1
      mcp:
        status: none
      name: Wallabag
      slug: wallabag
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Open Source
      - Privacy
      - Read-it-later
      - Self-Hosted
      tier: observed
      url: /providers/wallabag/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - FreshRSS
      - Miniflux
      band: minimal
      in_catalog: true
      kin_score: 6.5
      mcp:
        status: none
      name: linkding
      slug: linkding
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Bookmark
      - Company
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/linkding/
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - Miniflux
      band: developing
      in_catalog: true
      kin_score: 48.9
      mcp:
        source: https://readwise.io/mcp
        status: verified
      name: Readwise
      slug: readwise
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Knowledge Management
      - Productivity
      - Reading
      - Software-as-a-Service
      tier: observed
      url: /providers/readwise/
    - agent_band: agent-ready
      agent_readiness: 30.2
      apps:
      - Miniflux
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp:
        status: none
      name: Linkwarden
      slug: linkwarden
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Bookmarking
      - Company
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/linkwarden/
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - Miniflux
      band: developing
      in_catalog: true
      kin_score: 40.9
      mcp:
        source: https://docs.karakeep.app/mcp
        status: verified
      name: Karakeep
      slug: karakeep
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Artificial Intelligence
      - Bookmarking
      - Collaboration
      - Company
      tier: observed
      url: /providers/karakeep/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - FreshRSS
      band: thin
      in_catalog: true
      kin_score: 32.7
      mcp:
        status: none
      name: Nextcloud Bookmarks
      slug: nextcloud
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      status: profiled
      tags:
      - Collaboration
      - File Sharing
      - File Sync
      - Self-Hosted
      tier: observed
      url: /providers/nextcloud/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Miniflux
      band: emerging
      in_catalog: true
      kin_score: 18.7
      mcp:
        status: unknown
      name: Betula
      slug: betula
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Bookmark manager
      - Federated
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/betula/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Miniflux
      band: emerging
      in_catalog: true
      kin_score: 18.5
      mcp:
        status: none
      name: Shiori
      slug: shiori
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Bookmarks
      - Go
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/shiori/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Miniflux
      band: emerging
      in_catalog: true
      kin_score: 16.4
      mcp:
        status: none
      name: RSS-Bridge
      slug: rss-bridge
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Aggregator
      - Open Source
      - PHP
      - RSS
      tier: observed
      url: /providers/rss-bridge/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Miniflux
      band: emerging
      in_catalog: true
      kin_score: 13.1
      mcp:
        status: unknown
      name: Cubox
      slug: cubox
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Knowledge Management
      - Reading
      tier: observed
      url: /providers/cubox/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Miniflux
      band: emerging
      in_catalog: true
      kin_score: 11.1
      mcp:
        status: none
      name: Readeck
      slug: readeck
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Bookmarking
      - Company
      - Content Curation
      - Reading
      tier: observed
      url: /providers/readeck/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Miniflux
      band: minimal
      in_catalog: true
      kin_score: 9.2
      mcp:
        status: unknown
      name: LinkTaco
      slug: linktaco
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Bookmarking
      - Company
      - LinkShortening
      - Open Source
      tier: observed
      url: /providers/linktaco/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Miniflux
      band: minimal
      in_catalog: true
      kin_score: 6.3
      mcp:
        status: unknown
      name: Espial
      slug: espial
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Bookmarking
      - Company
      - Haskell
      - Open Source
      tier: observed
      url: /providers/espial/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - FreshRSS
      - NewsBlur
      - Readwise Reader
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: X (Twitter)
      slug: x
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      - https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
      - https://readwise.io/read
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - Feedly
      - FreshRSS
      band: strong
      in_catalog: true
      kin_score: 65.9
      mcp:
        status: none
      name: Buffer
      slug: buffer
      sources:
      - https://docs.feedly.com/collection/420-integrations
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      status: profiled
      tags:
      - Analytics
      - Publishing
      - Scheduling
      - Social Media
      tier: observed
      url: /providers/buffer/
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - FreshRSS
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp: &id001
        status: none
      name: LinkedIn
      slug: linkedin
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      status: profiled
      tags: &id002
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: observed
      url: /providers/linkedin/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - FreshRSS
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp: &id003
        source: https://github.com/reddit/devvit-mcp
        status: verified
      name: Reddit
      slug: reddit
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      status: profiled
      tags: &id004
      - Advertising
      - Community
      - Content
      - Reddit
      tier: observed
      url: /providers/reddit/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - FreshRSS
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp: &id005
        source: https://developers.pinterest.com/about-pinterest-mcp/
        status: verified
      name: Pinterest
      slug: pinterest
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      status: profiled
      tags: &id006
      - Image
      - Social
      - Social Media
      - Video
      tier: observed
      url: /providers/pinterest/
    - agent_band: agent-aware
      agent_readiness: 25.7
      apps:
      - FreshRSS
      band: developing
      in_catalog: true
      kin_score: 46.3
      mcp:
        status: none
      name: Bluesky
      slug: bluesky
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      status: profiled
      tags:
      - At-Protocol
      - Decentralized
      - Federated
      - Open Source
      tier: observed
      url: /providers/bluesky/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - FreshRSS
      band: developing
      in_catalog: true
      kin_score: 44.2
      mcp:
        status: none
      name: diaspora*
      slug: diaspora
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      status: profiled
      tags:
      - Company
      - Decentralized
      - Social
      - Social Network
      tier: observed
      url: /providers/diaspora/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - FreshRSS
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id007
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      status: profiled
      tags: &id008
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - FreshRSS
      band: developing
      in_catalog: true
      kin_score: 40.3
      mcp:
        status: none
      name: XING
      slug: xing
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      status: profiled
      tags:
      - Company
      - Job
      - Networking
      - Recruiters
      tier: observed
      url: /providers/xing/
    - agent_band: agent-aware
      agent_readiness: 20.4
      apps:
      - FreshRSS
      band: thin
      in_catalog: true
      kin_score: 33.9
      mcp:
        status: none
      name: Lemmy
      slug: lemmy
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      status: profiled
      tags:
      - Community
      - Federated
      - Fediverse
      - Link Aggregator
      tier: observed
      url: /providers/lemmy/
    - agent_band: agent-aware
      agent_readiness: 22.0
      apps:
      - FreshRSS
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        status: none
      name: Mastodon
      slug: mastodon
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      status: profiled
      tags:
      - Open Source
      - Real-Time
      - Social
      - Social Network
      tier: observed
      url: /providers/mastodon/
  - capability:
      attribution: Turbo EA
      id: BC-830.10
      key: knowledge-capture-management
      name: Knowledge Capture Management
      url: /capabilities/knowledge-capture-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Miniflux
      - Readwise Reader
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: Notion
      slug: notion
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      - https://readwise.io/read
      status: profiled
      tags:
      - Collaboration
      - Database
      - Ideas
      - Notes
      tier: observed
      url: /providers/notion/
    - agent_band: agent-aware
      agent_readiness: 28.0
      apps:
      - Feedly
      - Readwise Reader
      band: developing
      in_catalog: true
      kin_score: 53.0
      mcp:
        source: https://dev.evernote.com/
        status: documented
      name: Evernote
      slug: evernote
      sources:
      - https://docs.feedly.com/collection/420-integrations
      - https://readwise.io/read
      status: profiled
      tags:
      - Company
      - Knowledge Management
      - Note Taking
      - Productivity
      tier: declared
      url: /providers/evernote/
    - agent_band: agent-ready
      agent_readiness: 30.7
      apps:
      - Feedly
      band: strong
      in_catalog: true
      kin_score: 57.0
      mcp:
        status: none
      name: OneNote
      slug: microsoft-onenote
      sources:
      - https://docs.feedly.com/collection/420-integrations
      status: profiled
      tags:
      - Microsoft
      - Microsoft 365
      - Notebooks
      - Notes
      tier: declared
      url: /providers/microsoft-onenote/
    - agent_band: agent-ready
      agent_readiness: 29.6
      apps:
      - Readwise Reader
      band: thin
      in_catalog: true
      kin_score: 34.9
      mcp:
        status: none
      name: Obsidian
      slug: obsidian
      sources:
      - https://readwise.io/read
      status: profiled
      tags:
      - Knowledge Management
      - Markdown
      - Notes
      - Productivity
      tier: declared
      url: /providers/obsidian/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Readwise Reader
      band: emerging
      in_catalog: true
      kin_score: 20.0
      mcp:
        status: none
      name: Logseq
      slug: logseq
      sources:
      - https://readwise.io/read
      status: profiled
      tags:
      - Company
      - Knowledge Management
      - Note Taking
      - Productivity
      tier: declared
      url: /providers/logseq/
    - agent_band: null
      agent_readiness: null
      apps:
      - Readwise Reader
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Roam Research
      slug: roam-research
      sources:
      - https://readwise.io/read
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.20
      key: AE-170.60.20
      name: Books & E-Books
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    providers:
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - Readwise Reader
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Amazon Kindle
      slug: amazon
      sources:
      - https://readwise.io/read
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: declared
      url: /providers/amazon/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - Readwise Reader
      band: strong
      in_catalog: true
      kin_score: 65.4
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://readwise.io/read
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: declared
      url: /providers/youtube/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.40
      key: AE-230.40.40
      name: Web Archiving & Page Snapshots
      url: /capabilities/web-data/
      via_parent: Web Data
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Miniflux
      band: minimal
      in_catalog: true
      kin_score: 4.0
      mcp:
        status: none
      name: Internet Archive (Wayback save)
      slug: internet-archive
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Archival
      - Digital Library
      - Non-Profit
      - Open Access
      tier: observed
      url: /providers/internet-archive/
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
      agent_readiness: 33.7
      apps:
      - Linkwarden
      - NewsBlur
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google
      slug: google-identity-platform
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      - https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Linkwarden
      - NewsBlur
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp: &id013
        status: none
      name: Apple
      slug: apple
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      - https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
      status: profiled
      tags: &id014
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Linkwarden
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: observed
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Linkwarden
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: observed
      url: /providers/salesforce/
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Linkwarden
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Linkwarden
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - Linkwarden
      band: exemplar
      in_catalog: true
      kin_score: 79.8
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Atlassian
      slug: atlassian
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Code
      - Collaboration
      - Platform
      - Productivity
      tier: observed
      url: /providers/atlassian/
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Linkwarden
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp: *id001
      name: LinkedIn
      slug: linkedin
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/linkedin/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Linkwarden
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: observed
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Linkwarden
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp: &id009
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags: &id010
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 58.9
      apps:
      - Linkwarden
      band: exemplar
      in_catalog: true
      kin_score: 72.2
      mcp:
        source: https://github.com/netlify/netlify-mcp
        status: verified
      name: Netlify
      slug: netlify
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - CDN
      - Cloud
      - Continuous Deployment
      - Developer Tools
      tier: observed
      url: /providers/netlify/
    - agent_band: agent-native
      agent_readiness: 47.0
      apps:
      - Linkwarden
      band: exemplar
      in_catalog: true
      kin_score: 71.3
      mcp:
        source: https://github.com/line/line-bot-mcp-server
        status: verified
      name: LINE
      slug: line
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Chatbots
      - Messaging
      - Mini Apps
      - Social Login
      tier: observed
      url: /providers/line/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Linkwarden
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp: *id003
      name: Reddit
      slug: reddit
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/reddit/
    - agent_band: agent-ready
      agent_readiness: 32.4
      apps:
      - Linkwarden
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://www.zoho.com/mcp/
        status: verified
      name: Zoho
      slug: zoho
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Analytics
      - CRM
      - Collaboration
      - Customer Service
      tier: observed
      url: /providers/zoho/
    - agent_band: agent-ready
      agent_readiness: 56.6
      apps:
      - Linkwarden
      band: strong
      in_catalog: true
      kin_score: 63.0
      mcp:
        source: https://developer.box.com/guides/box-mcp/
        status: verified
      name: Box
      slug: box
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Content Management
      - Documents
      tier: observed
      url: /providers/box/
    - agent_band: agent-native
      agent_readiness: 50.8
      apps:
      - Linkwarden
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        source: https://github.com/coinbase/payments-mcp
        status: verified
      name: Coinbase
      slug: coinbase
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Blockchain
      - Cryptocurrency
      - Custody
      - Exchange
      tier: observed
      url: /providers/coinbase/
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Linkwarden
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: observed
      url: /providers/zoom/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Linkwarden
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Pipedrive
      slug: pipedrive
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - CRM
      - Pipeline Management
      - Sales
      - Software-as-a-Service
      tier: observed
      url: /providers/pipedrive/
    - agent_band: agent-aware
      agent_readiness: 22.2
      apps:
      - Linkwarden
      band: developing
      in_catalog: true
      kin_score: 53.8
      mcp:
        source: https://developer.todoist.com/api/v1/#tag/MCP
        status: verified
      name: Todoist
      slug: todoist
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Productivity
      - Task
      - Task Management
      - To-Do
      tier: observed
      url: /providers/todoist/
    - agent_band: agent-ready
      agent_readiness: 51.3
      apps:
      - Linkwarden
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        status: none
      name: Strava
      slug: strava
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Cycling
      - Fitness
      - Fitness Tracking
      - Running
      tier: observed
      url: /providers/strava/
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Linkwarden
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        status: none
      name: Spotify
      slug: spotify
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Audio
      - Music
      - Podcasts
      - Streaming
      tier: observed
      url: /providers/spotify/
    - agent_band: agent-ready
      agent_readiness: 32.0
      apps:
      - Linkwarden
      band: developing
      in_catalog: true
      kin_score: 49.8
      mcp:
        status: none
      name: Wikimedia
      slug: wikimedia
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Encyclopedia
      - Open Knowledge
      - Wikimedia
      - Wikipedia
      tier: observed
      url: /providers/wikimedia/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Linkwarden
      band: developing
      in_catalog: true
      kin_score: 48.2
      mcp:
        status: none
      name: Twitch
      slug: twitch
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Entertainment
      - Gaming
      - Live Streaming
      - Streaming
      tier: observed
      url: /providers/twitch/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Linkwarden
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp: &id011
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags: &id012
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Linkwarden
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp: *id005
      name: Pinterest
      slug: pinterest
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/pinterest/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Linkwarden
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: WordPress.com
      slug: wordpress
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: observed
      url: /providers/wordpress/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Linkwarden
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
    - agent_band: agent-aware
      agent_readiness: 22.8
      apps:
      - Linkwarden
      band: developing
      in_catalog: true
      kin_score: 45.1
      mcp:
        source: https://github.com/foursquare/foursquare-places-mcp
        status: verified
      name: Foursquare
      slug: foursquare
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Geocoding
      - Location
      - Places
      - Restaurant
      tier: observed
      url: /providers/foursquare/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Linkwarden
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id007
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Linkwarden
      band: thin
      in_catalog: true
      kin_score: 33.1
      mcp:
        status: none
      name: Patreon
      slug: patreon
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Content
      - Creator Economy
      - Membership
      - Subscription
      tier: observed
      url: /providers/patreon/
    - agent_band: agent-ready
      agent_readiness: 38.2
      apps:
      - Linkwarden
      band: thin
      in_catalog: true
      kin_score: 31.5
      mcp:
        status: none
      name: Battle.net
      slug: battle-net
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Blizzard
      - Games
      - Gaming
      - World Of Warcraft
      tier: observed
      url: /providers/battle-net/
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - Linkwarden
      band: thin
      in_catalog: true
      kin_score: 31.0
      mcp:
        status: none
      name: FreshBooks
      slug: freshbooks
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Accounting
      - Expense Tracking
      - Invoicing
      - Time Tracking
      tier: observed
      url: /providers/freshbooks/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Linkwarden
      band: thin
      in_catalog: true
      kin_score: 26.2
      mcp:
        status: none
      name: Kakao
      slug: kakao
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Maps
      - Messaging
      - Navigation
      - Payments
      tier: observed
      url: /providers/kakao/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Linkwarden
      band: minimal
      in_catalog: true
      kin_score: 10.6
      mcp:
        status: none
      name: Naver
      slug: naver
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Cloud Platform
      - Maps
      - Search
      - Translation
      tier: observed
      url: /providers/naver/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Linkwarden
      band: minimal
      in_catalog: true
      kin_score: 6.5
      mcp:
        status: none
      name: Bungie
      slug: bungie
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Community
      - Company
      - Gaming
      - Video Games
      tier: observed
      url: /providers/bungie/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Linkwarden
      band: minimal
      in_catalog: true
      kin_score: 4.8
      mcp:
        status: none
      name: VK
      slug: vk
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Public APIs
      - Social
      tier: observed
      url: /providers/vk/
    - agent_band: null
      agent_readiness: null
      apps:
      - Linkwarden
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Yandex ID
      slug: yandex
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Karakeep
      - Linkwarden
      - NewsBlur
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/karakeep-app/karakeep/blob/main/packages/shared/package.json
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      - https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Linkwarden
      - NewsBlur
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      - https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Karakeep
      - Linkwarden
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp:
        status: none
      name: Ollama
      slug: ollama
      sources:
      - https://github.com/karakeep-app/karakeep/blob/main/packages/shared/package.json
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Artificial Intelligence
      - LLM
      - Models
      - Ollama
      tier: observed
      url: /providers/ollama/
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - Linkwarden
      band: exemplar
      in_catalog: true
      kin_score: 68.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure OpenAI
      slug: microsoft-azure-openai
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - GPT
      - Generative AI
      tier: observed
      url: /providers/microsoft-azure-openai/
    - agent_band: agent-native
      agent_readiness: 66.6
      apps:
      - Linkwarden
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        source: https://github.com/perplexityai/modelcontextprotocol
        status: verified
      name: Perplexity
      slug: perplexity
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - LLM
      - Search
      tier: observed
      url: /providers/perplexity/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - NewsBlur
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Linkwarden
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: observed
      url: /providers/okta/
    - agent_band: agent-ready
      agent_readiness: 37.3
      apps:
      - Linkwarden
      band: exemplar
      in_catalog: true
      kin_score: 74.5
      mcp:
        status: none
      name: Amazon Cognito
      slug: amazon-cognito
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Amazon Web Services
      - Authentication
      - Identity
      - OpenID Connect
      tier: observed
      url: /providers/amazon-cognito/
    - agent_band: agent-ready
      agent_readiness: 37.2
      apps:
      - Linkwarden
      band: exemplar
      in_catalog: true
      kin_score: 73.1
      mcp:
        status: none
      name: Authentik
      slug: authentik
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity Provider
      - LDAP
      tier: observed
      url: /providers/authentik/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Linkwarden
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Azure AD / B2C
      slug: microsoft-entra
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 31.5
      apps:
      - Linkwarden
      band: strong
      in_catalog: true
      kin_score: 56.2
      mcp:
        source: https://github.com/FusionAuth/fusionauth-mcp-api
        status: verified
      name: FusionAuth
      slug: fusionauth
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Authentication
      - Authorization
      - CIAM
      - Identity
      tier: observed
      url: /providers/fusionauth/
    - agent_band: agent-ready
      agent_readiness: 31.2
      apps:
      - Linkwarden
      band: strong
      in_catalog: true
      kin_score: 55.6
      mcp:
        status: none
      name: Authelia
      slug: authelia
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Authentication
      - Authorization
      - LDAP
      - MFA
      tier: observed
      url: /providers/authelia/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Linkwarden
      band: developing
      in_catalog: true
      kin_score: 54.1
      mcp:
        status: none
      name: Zitadel
      slug: zitadel
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity and Access Management
      - Open Source
      tier: observed
      url: /providers/zitadel/
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - Linkwarden
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        status: none
      name: Keycloak
      slug: keycloak
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity and Access Management
      - OAuth
      tier: observed
      url: /providers/keycloak/
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Linkwarden
      band: thin
      in_catalog: true
      kin_score: 29.5
      mcp:
        source: https://github.com/onelogin/onelogin-mcp
        status: verified
      name: OneLogin
      slug: onelogin
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Identity
      - Identity and Access Management
      - Multi-Factor Authentication
      - SSO
      tier: observed
      url: /providers/onelogin/
    - agent_band: agent-aware
      agent_readiness: 18.3
      apps:
      - Linkwarden
      band: emerging
      in_catalog: true
      kin_score: 12.0
      mcp:
        status: none
      name: Synology
      slug: synology
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Backup
      - Cloud
      - Company
      - Storage
      tier: observed
      url: /providers/synology/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Feedly
      - Miniflux
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp: *id009
      name: Slack
      slug: slack
      sources:
      - https://docs.feedly.com/collection/420-integrations
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags: *id010
      tier: observed
      url: /providers/slack/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - FreshRSS
      - Miniflux
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Miniflux
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp: *id011
      name: Discord
      slug: discord
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags: *id012
      tier: observed
      url: /providers/discord/
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - Miniflux
      band: thin
      in_catalog: true
      kin_score: 30.5
      mcp:
        status: none
      name: Matrix
      slug: matrix
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Decentralized
      - Federated
      - Messaging
      - Open Standard
      tier: observed
      url: /providers/matrix/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Feedly
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://docs.feedly.com/collection/420-integrations
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - NewsBlur
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp: *id013
      name: Apple (APNs)
      slug: apple
      sources:
      - https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
      status: profiled
      tags: *id014
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Miniflux
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        status: none
      name: Pushover
      slug: pushover
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Alerts
      - Messaging
      - Notification
      - Push Notifications
      tier: observed
      url: /providers/pushover/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Miniflux
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: none
      name: ntfy
      slug: ntfy
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Notification
      - Open Source
      - Pub/Sub
      - Self-Hosted
      tier: observed
      url: /providers/ntfy/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Miniflux
      band: minimal
      in_catalog: true
      kin_score: 10.9
      mcp:
        source: https://gotify.net/docs/mcp
        status: verified
      name: Gotify
      slug: gotify
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: profiled
      tags:
      - Messaging
      - Notification
      - Open Source
      - Self-Hosted
      tier: observed
      url: /providers/gotify/
    - agent_band: null
      agent_readiness: null
      apps:
      - Miniflux
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Apprise
      slug: apprise
      sources:
      - https://github.com/miniflux/v2/tree/main/internal/integration
      status: queued for profiling
      tags: []
      tier: observed
      url: null
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
      - Karakeep
      - NewsBlur
      - Wallabag
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/karakeep-app/karakeep/blob/main/apps/mobile/package.json
      - https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
      - https://github.com/wallabag/wallabag/blob/master/composer.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
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
      - NewsBlur
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - NewsBlur
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
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
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - NewsBlur
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/samuelclay/NewsBlur/blob/master/config/requirements.txt
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Linkwarden
      band: developing
      in_catalog: true
      kin_score: 47.4
      mcp:
        source: https://docs.digitalocean.com/reference/mcp/
        status: verified
      name: DigitalOcean Spaces
      slug: digital-ocean
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Cloud
      - Compute
      - Infrastructure
      - Servers
      tier: observed
      url: /providers/digital-ocean/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Feedly
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://docs.feedly.com/collection/420-integrations
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 42.4
      apps:
      - Feedly
      band: emerging
      in_catalog: true
      kin_score: 24.1
      mcp:
        source: https://github.com/IFTTT/ifttt-plugins
        status: verified
      name: IFTTT
      slug: ifttt
      sources:
      - https://docs.feedly.com/collection/420-integrations
      status: profiled
      tags:
      - Automation
      - No-Code
      - Webhook
      - iPaaS
      tier: declared
      url: /providers/ifttt/
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Karakeep
      band: thin
      in_catalog: true
      kin_score: 27.4
      mcp:
        source: https://www.revenuecat.com/docs/tools/mcp
        status: verified
      name: RevenueCat
      slug: revenuecat
      sources:
      - https://github.com/karakeep-app/karakeep/blob/main/packages/shared/config.ts
      status: profiled
      tags:
      - Billing
      - In-App Purchases
      - Mobile
      - Subscription
      tier: observed
      url: /providers/revenuecat/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Linkwarden
      band: strong
      in_catalog: true
      kin_score: 54.8
      mcp:
        source: https://openrouter.ai/docs/guides/overview/mcp-server
        status: verified
      name: OpenRouter
      slug: openrouter
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
      status: profiled
      tags:
      - Artificial Intelligence
      - Gateways
      - LLM
      - Router
      tier: observed
      url: /providers/openrouter/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.3
      apps:
      - Wallabag
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/matomo-org/plugin-McpServer
        status: verified
      name: Matomo (Piwik)
      slug: matomo
      sources:
      - https://github.com/wallabag/wallabag/blob/master/composer.json
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
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Linkwarden
      band: developing
      in_catalog: true
      kin_score: 52.5
      mcp:
        source: https://github.com/meilisearch/meilisearch-mcp
        status: verified
      name: Meilisearch
      slug: meilisearch
      sources:
      - https://github.com/linkwarden/linkwarden/blob/main/.env.sample
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
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - Wallabag
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://github.com/wallabag/wallabag/blob/master/composer.json
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: observed
      url: /providers/google-gmail/
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
      - FreshRSS
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp
      slug: whatsapp
      sources:
      - https://github.com/FreshRSS/FreshRSS/blob/edge/app/shares.php
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: observed
      url: /providers/whatsapp/
  layer: common
summary:
  coverage_pct: 96.3
  declared_only: 10
  distinct_providers: 109
  in_catalog: 105
  mcp:
    documented: 1
    none: 55
    unchecked: 4
    verified: 44
  mcp_verified: 44
  mean_kin_score: 47.8
  observed: 99
  queued: 4
  reference_apps: 8
title: 'News, Feeds & Read-Later: application blueprint'
---
