---
app: Discord
app_slug: discord
app_url: https://discord.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.10.40
  key: AE-160.10.40
  layer: domain
  name: Account Linking
  providers:
  - Amazon Music
  - Bluesky
  - Bungie.net
  - Crunchyroll
  - eBay
  - Epic Games
  - Facebook
  - GitHub
  - Mastodon
  - PayPal
  - PlayStation Network
  - Reddit
  - Roblox
  - Spotify
  - Steam
  - TikTok
  - Twitch
  - X (Twitter)
  - Xbox
  - YouTube
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - AppsFlyer
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: messaging-chat
  name: Messaging & Team Chat
  url: /applications/messaging-chat/
counts:
  declared: 20
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.discord/latest/
- route: documentation
  url: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 46.4
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id003
      source: https://registry.modelcontextprotocol.io/v0/servers?search=appsflyer
      status: verified
    slug: appsflyer
    status: profiled
    tags: &id004
    - Company
    - Marketing Analytics
    - Mobile Attribution
    - Mobile Measurement
    url: /providers/appsflyer/
  layer: common
  name: AppsFlyer
  provider: appsflyer
  says: ships the AppsFlyer SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.discord/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id019
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id020
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.discord/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id031
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id032
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.discord/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 10.8
    band: emerging
    in_catalog: true
    kin_score: 16.1
    mcp: &id001
      status: none
    slug: amazon-music
    status: profiled
    tags: &id002
    - Audio
    - Company
    - Music
    - Streaming
    url: /providers/amazon-music/
  layer: domain
  name: Amazon Music
  provider: amazon-music
  says: lists Amazon Music as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.2
    band: developing
    in_catalog: true
    kin_score: 45.1
    mcp: &id005
      status: none
    slug: bluesky
    status: profiled
    tags: &id006
    - At-Protocol
    - Decentralized
    - Federated
    - Open Source
    url: /providers/bluesky/
  layer: domain
  name: Bluesky
  provider: bluesky
  says: lists Bluesky as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.0
    mcp: &id007
      status: none
    slug: bungie
    status: profiled
    tags: &id008
    - Community
    - Company
    - Gaming
    - Video Games
    url: /providers/bungie/
  layer: domain
  name: Bungie.net
  provider: bungie
  says: lists Bungie.net as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 15.1
    band: minimal
    in_catalog: true
    kin_score: 6.4
    mcp: &id009
      status: none
    slug: crunchyroll
    status: profiled
    tags: &id010
    - Company
    url: /providers/crunchyroll/
  layer: domain
  name: Crunchyroll
  provider: crunchyroll
  says: lists Crunchyroll as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.0
    band: developing
    in_catalog: true
    kin_score: 50.7
    mcp: &id011
      source: https://github.com/eBay/npm-public-api-mcp
      status: verified
    slug: ebay
    status: profiled
    tags: &id012
    - Auctions
    - Commerce
    - Marketplace
    - Product
    url: /providers/ebay/
  layer: domain
  name: eBay
  provider: ebay
  says: lists eBay as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.4
    band: developing
    in_catalog: true
    kin_score: 42.5
    mcp: &id013
      status: none
    slug: epic-games
    status: profiled
    tags: &id014
    - Achievements
    - Anti-Cheat
    - Cross-Platform
    - EOS
    url: /providers/epic-games/
  layer: domain
  name: Epic Games
  provider: epic-games
  says: lists Epic Games as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id015
      status: none
    slug: facebook
    status: profiled
    tags: &id016
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: lists Facebook as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id017
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id018
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.5
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id021
      status: none
    slug: mastodon
    status: profiled
    tags: &id022
    - Open Source
    - Real-Time
    - Social
    - Social Network
    url: /providers/mastodon/
  layer: domain
  name: Mastodon
  provider: mastodon
  says: lists Mastodon as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id023
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id024
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.1
    mcp: &id025
      status: none
    slug: playstation
    status: profiled
    tags: &id026
    - Company
    - Console
    - Entertainment
    - Gaming
    url: /providers/playstation/
  layer: domain
  name: PlayStation Network
  provider: playstation
  says: lists PlayStation Network as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.1
    band: strong
    in_catalog: true
    kin_score: 63.0
    mcp: &id027
      source: https://github.com/reddit/devvit-mcp
      status: verified
    slug: reddit
    status: profiled
    tags: &id028
    - Advertising
    - Community
    - Content
    - Reddit
    url: /providers/reddit/
  layer: domain
  name: Reddit
  provider: reddit
  says: lists Reddit as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.1
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id029
      source: https://github.com/Roblox/studio-rust-mcp-server
      status: verified
    slug: roblox
    status: profiled
    tags: &id030
    - Assets
    - Datastores
    - Game Development
    - Games
    url: /providers/roblox/
  layer: domain
  name: Roblox
  provider: roblox
  says: lists Roblox as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 49.8
    mcp: &id033
      status: none
    slug: spotify
    status: profiled
    tags: &id034
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
  layer: domain
  name: Spotify
  provider: spotify
  says: lists Spotify as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: thin
    in_catalog: true
    kin_score: 34.4
    mcp: &id035
      status: none
    slug: steam
    status: profiled
    tags: &id036
    - Distribution
    - Gaming
    - Steamworks
    - Valve
    url: /providers/steam/
  layer: domain
  name: Steam
  provider: steam
  says: lists Steam as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 41.0
    mcp: &id037
      status: none
    slug: tiktok
    status: profiled
    tags: &id038
    - Advertising
    - Commerce
    - Content
    - TikTok
    url: /providers/tiktok/
  layer: domain
  name: TikTok
  provider: tiktok
  says: lists TikTok as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.2
    band: developing
    in_catalog: true
    kin_score: 50.5
    mcp: &id039
      status: none
    slug: twitch
    status: profiled
    tags: &id040
    - Entertainment
    - Gaming
    - Live Streaming
    - Streaming
    url: /providers/twitch/
  layer: domain
  name: Twitch
  provider: twitch
  says: lists Twitch as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id041
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id042
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: lists X (Twitter) as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 21.8
    mcp: &id043
      status: none
    slug: microsoft-xbox
    status: profiled
    tags: &id044
    - Gaming
    - Microsoft
    - PlayFab
    - Xbox
    url: /providers/microsoft-xbox/
  layer: domain
  name: Xbox
  provider: microsoft-xbox
  says: lists Xbox as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.40
    key: AE-160.10.40
    name: Account Linking
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.4
    band: strong
    in_catalog: true
    kin_score: 62.6
    mcp: &id045
      status: none
    slug: youtube
    status: profiled
    tags: &id046
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: lists YouTube as an integration
  source: https://github.com/discord/discord-api-docs/blob/main/developers/resources/user.mdx
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/messaging-chat/discord/
providers:
- agent_band: agent-aware
  agent_readiness: 10.8
  band: emerging
  in_catalog: true
  kin_score: 16.1
  mcp: *id001
  name: Amazon Music
  slug: amazon-music
  status: profiled
  tags: *id002
  url: /providers/amazon-music/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id003
  name: AppsFlyer
  slug: appsflyer
  status: profiled
  tags: *id004
  url: /providers/appsflyer/
- agent_band: agent-aware
  agent_readiness: 26.2
  band: developing
  in_catalog: true
  kin_score: 45.1
  mcp: *id005
  name: Bluesky
  slug: bluesky
  status: profiled
  tags: *id006
  url: /providers/bluesky/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.0
  mcp: *id007
  name: Bungie.net
  slug: bungie
  status: profiled
  tags: *id008
  url: /providers/bungie/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: minimal
  in_catalog: true
  kin_score: 6.4
  mcp: *id009
  name: Crunchyroll
  slug: crunchyroll
  status: profiled
  tags: *id010
  url: /providers/crunchyroll/
- agent_band: agent-ready
  agent_readiness: 32.0
  band: developing
  in_catalog: true
  kin_score: 50.7
  mcp: *id011
  name: eBay
  slug: ebay
  status: profiled
  tags: *id012
  url: /providers/ebay/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id013
  name: Epic Games
  slug: epic-games
  status: profiled
  tags: *id014
  url: /providers/epic-games/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id015
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id016
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id017
  name: GitHub
  slug: github
  status: profiled
  tags: *id018
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id019
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id020
  url: /providers/google-analytics/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id021
  name: Mastodon
  slug: mastodon
  status: profiled
  tags: *id022
  url: /providers/mastodon/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id023
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id024
  url: /providers/paypal/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.1
  mcp: *id025
  name: PlayStation Network
  slug: playstation
  status: profiled
  tags: *id026
  url: /providers/playstation/
- agent_band: agent-ready
  agent_readiness: 39.1
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id027
  name: Reddit
  slug: reddit
  status: profiled
  tags: *id028
  url: /providers/reddit/
- agent_band: human-only
  agent_readiness: 3.1
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id029
  name: Roblox
  slug: roblox
  status: profiled
  tags: *id030
  url: /providers/roblox/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id031
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id032
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id033
  name: Spotify
  slug: spotify
  status: profiled
  tags: *id034
  url: /providers/spotify/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: thin
  in_catalog: true
  kin_score: 34.4
  mcp: *id035
  name: Steam
  slug: steam
  status: profiled
  tags: *id036
  url: /providers/steam/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 41.0
  mcp: *id037
  name: TikTok
  slug: tiktok
  status: profiled
  tags: *id038
  url: /providers/tiktok/
- agent_band: agent-ready
  agent_readiness: 32.2
  band: developing
  in_catalog: true
  kin_score: 50.5
  mcp: *id039
  name: Twitch
  slug: twitch
  status: profiled
  tags: *id040
  url: /providers/twitch/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id041
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id042
  url: /providers/x/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 21.8
  mcp: *id043
  name: Xbox
  slug: microsoft-xbox
  status: profiled
  tags: *id044
  url: /providers/microsoft-xbox/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id045
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id046
  url: /providers/youtube/
siblings:
- name: Element / Matrix (Synapse)
  rows: 4
  url: /applications/messaging-chat/element-matrix-synapse/
- name: Mattermost
  rows: 25
  url: /applications/messaging-chat/mattermost/
- name: Rocket.Chat
  rows: 11
  url: /applications/messaging-chat/rocket-chat/
- name: Signal
  rows: 7
  url: /applications/messaging-chat/signal/
- name: Slack
  rows: 24
  url: /applications/messaging-chat/slack/
- name: Zulip
  rows: 11
  url: /applications/messaging-chat/zulip/
sitemap: true
title: 'Discord: Messaging & Team Chat reference app'
---
