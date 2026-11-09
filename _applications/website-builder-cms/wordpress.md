---
app: WordPress
app_slug: wordpress
app_url: https://github.com/WordPress/WordPress
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.20
  key: AE-170.20
  layer: domain
  name: Audio & Music
  providers:
  - Anghami
  - Mixcloud
  - ReverbNation
  - SoundCloud
  - Spotify
  url: /capabilities/audio-music/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.40
  key: AE-170.40
  layer: domain
  name: Creator Monetisation
  providers:
  - Kickstarter
  url: /capabilities/creator-monetisation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: domain
  name: Design & Creative Editing
  providers:
  - Canva
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.70.10
  key: AE-170.70.10
  layer: domain
  name: Link Unfurling & Rich Embeds
  providers:
  - Amazon Kindle Instant Preview
  - Issuu
  - Scribd
  - Speaker Deck
  - Wolfram Cloud
  url: /capabilities/content-management/
  via_parent: Content Management
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: domain
  name: Online Forms & Survey Collection
  providers:
  - Crowdsignal
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: domain
  name: Photo & Image Libraries
  providers:
  - Cloudup
  - Flickr
  - SmugMug
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.20.20
  key: AE-170.20.20
  layer: domain
  name: Podcast Hosting
  providers:
  - Pocket Casts
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Bluesky
  - Pinterest
  - Reddit
  - TikTok
  - Tumblr
  - X (Twitter)
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.10
  key: AE-170.10
  layer: domain
  name: Video Platforms
  providers:
  - Animoto
  - Dailymotion
  - TED
  - Vimeo
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30.30
  key: AE-170.30.30
  layer: common
  name: Avatars, GIFs & Stickers
  providers:
  - Gravatar
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: website-builder-cms
  name: Website Builder, CMS & Blogging
  url: /applications/website-builder-cms/
counts:
  declared: 0
  observed: 30
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/org.wordpress.android/latest/
- route: source code
  url: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
- route: source code
  url: https://github.com/WordPress/WordPress/blob/master/wp-includes/pluggable.php
- route: source code
  url: https://github.com/WordPress/WordPress/tree/master/wp-content/plugins
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 46.7
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
  layer: domain
  name: Amazon Kindle Instant Preview
  provider: amazon
  says: ships the Amazon Kindle Instant Preview SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20
    key: AE-170.20
    name: Audio & Music
    url: /capabilities/audio-music/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 6.8
    mcp: &id003
      status: none
    slug: anghami
    status: profiled
    tags: &id004
    - Middle East
    - Music
    - North-Africa
    - Streaming
    url: /providers/anghami/
  layer: domain
  name: Anghami
  provider: anghami
  says: ships the Anghami SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 5.0
    band: thin
    in_catalog: true
    kin_score: 34.5
    mcp: &id005
      status: none
    slug: animoto
    status: profiled
    tags: &id006
    - Company
    - Consumer
    - Video
    - Video Creation
    url: /providers/animoto/
  layer: domain
  name: Animoto
  provider: animoto
  says: ships the Animoto SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.2
    band: developing
    in_catalog: true
    kin_score: 45.1
    mcp: &id007
      status: none
    slug: bluesky
    status: profiled
    tags: &id008
    - At-Protocol
    - Decentralized
    - Federated
    - Open Source
    url: /providers/bluesky/
  layer: domain
  name: Bluesky
  provider: bluesky
  says: ships the Bluesky SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 71.4
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id009
      source: https://www.canva.dev/docs/mcp/
      status: verified
    slug: canva
    status: profiled
    tags: &id010
    - Application
    - Automation
    - Brand Management
    - Collaboration
    url: /providers/canva/
  layer: domain
  name: Canva
  provider: canva
  says: ships the Canva SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id011
      status: unchecked
    slug: cloudup
    status: queued for profiling
    tags: &id012 []
    url: null
  layer: domain
  name: Cloudup
  provider: cloudup
  says: ships the Cloudup SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id013
      status: unchecked
    slug: crowdsignal
    status: queued for profiling
    tags: &id014 []
    url: null
  layer: domain
  name: Crowdsignal
  provider: crowdsignal
  says: ships the Crowdsignal SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.9
    band: minimal
    in_catalog: true
    kin_score: 8.4
    mcp: &id015
      status: none
    slug: dailymotion
    status: profiled
    tags: &id016
    - Public APIs
    - Video
    url: /providers/dailymotion/
  layer: domain
  name: Dailymotion
  provider: dailymotion
  says: ships the Dailymotion SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.6
    band: developing
    in_catalog: true
    kin_score: 48.6
    mcp: &id017
      status: none
    slug: flickr
    status: profiled
    tags: &id018
    - Photography
    - Photos
    - Public APIs
    - Social Media
    url: /providers/flickr/
  layer: domain
  name: Flickr
  provider: flickr
  says: ships the Flickr SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.30
    key: AE-170.30.30
    name: Avatars, GIFs & Stickers
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 39.8
    mcp: &id019
      source: https://github.com/Automattic/mcp-server-gravatar
      status: verified
    slug: gravatar
    status: profiled
    tags: &id020
    - Avatars
    - Identity
    - Profiles
    - Social
    url: /providers/gravatar/
  layer: common
  name: Gravatar
  provider: gravatar
  says: ships the Gravatar SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/pluggable.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id021
      status: unchecked
    slug: issuu
    status: queued for profiling
    tags: &id022 []
    url: null
  layer: domain
  name: Issuu
  provider: issuu
  says: ships the Issuu SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.40
    key: AE-170.40
    name: Creator Monetisation
    url: /capabilities/creator-monetisation/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.4
    mcp: &id023
      status: none
    slug: kickstarter
    status: profiled
    tags: &id024
    - Company
    - Consumer
    - Crowdfunding
    - Fundraising
    url: /providers/kickstarter/
  layer: domain
  name: Kickstarter
  provider: kickstarter
  says: ships the Kickstarter SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20
    key: AE-170.20
    name: Audio & Music
    url: /capabilities/audio-music/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.9
    mcp: &id025
      status: none
    slug: mixcloud
    status: profiled
    tags: &id026
    - Music
    - Public APIs
    url: /providers/mixcloud/
  layer: domain
  name: Mixcloud
  provider: mixcloud
  says: ships the Mixcloud SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.4
    band: developing
    in_catalog: true
    kin_score: 49.4
    mcp: &id027
      source: https://developers.pinterest.com/about-pinterest-mcp/
      status: verified
    slug: pinterest
    status: profiled
    tags: &id028
    - Image
    - Social
    - Social Media
    - Video
    url: /providers/pinterest/
  layer: domain
  name: Pinterest
  provider: pinterest
  says: ships the Pinterest SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.20
    key: AE-170.20.20
    name: Podcast Hosting
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id029
      status: unchecked
    slug: pocket-casts
    status: queued for profiling
    tags: &id030 []
    url: null
  layer: domain
  name: Pocket Casts
  provider: pocket-casts
  says: ships the Pocket Casts SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.1
    band: strong
    in_catalog: true
    kin_score: 63.0
    mcp: &id031
      source: https://github.com/reddit/devvit-mcp
      status: verified
    slug: reddit
    status: profiled
    tags: &id032
    - Advertising
    - Community
    - Content
    - Reddit
    url: /providers/reddit/
  layer: domain
  name: Reddit
  provider: reddit
  says: ships the Reddit SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20
    key: AE-170.20
    name: Audio & Music
    url: /capabilities/audio-music/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 11.7
    mcp: &id033
      status: unknown
    slug: reverbnation
    status: profiled
    tags: &id034
    - Artists
    - Distribution
    - Music
    - Promotion
    url: /providers/reverbnation/
  layer: domain
  name: ReverbNation
  provider: reverbnation
  says: ships the ReverbNation SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.2
    mcp: &id035
      status: none
    slug: scribd
    status: profiled
    tags: &id036
    - Audiobooks
    - Company
    - Documents
    - Ebooks
    url: /providers/scribd/
  layer: domain
  name: Scribd
  provider: scribd
  says: ships the Scribd SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
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
    mcp: &id037
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id038
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/org.wordpress.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 25.0
    mcp: &id039
      status: none
    slug: smugmug
    status: profiled
    tags: &id040
    - Cloud Storage
    - E-Commerce
    - Photo Sharing
    - Photography
    url: /providers/smugmug/
  layer: domain
  name: SmugMug
  provider: smugmug
  says: ships the SmugMug SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20
    key: AE-170.20
    name: Audio & Music
    url: /capabilities/audio-music/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 31.0
    mcp: &id041
      status: none
    slug: soundcloud
    status: profiled
    tags: &id042
    - Audio
    - Music
    - OAuth
    - Streaming
    url: /providers/soundcloud/
  layer: domain
  name: SoundCloud
  provider: soundcloud
  says: ships the SoundCloud SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.7
    mcp: &id043
      status: unknown
    slug: speakerdeck
    status: profiled
    tags: &id044
    - Company
    - Presentation
    - Sharing
    - Slides
    url: /providers/speakerdeck/
  layer: domain
  name: Speaker Deck
  provider: speakerdeck
  says: ships the Speaker Deck SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.20
    key: AE-170.20
    name: Audio & Music
    url: /capabilities/audio-music/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: developing
    in_catalog: true
    kin_score: 49.8
    mcp: &id045
      status: none
    slug: spotify
    status: profiled
    tags: &id046
    - Audio
    - Music
    - Podcasts
    - Streaming
    url: /providers/spotify/
  layer: domain
  name: Spotify
  provider: spotify
  says: ships the Spotify SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.7
    band: emerging
    in_catalog: true
    kin_score: 11.7
    mcp: &id047
      status: unknown
    slug: ted-com
    status: profiled
    tags: &id048
    - Company
    - Education
    - Media
    - Non-Profit
    url: /providers/ted-com/
  layer: domain
  name: TED
  provider: ted-com
  says: ships the TED SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 41.0
    mcp: &id049
      status: none
    slug: tiktok
    status: profiled
    tags: &id050
    - Advertising
    - Commerce
    - Content
    - TikTok
    url: /providers/tiktok/
  layer: domain
  name: TikTok
  provider: tiktok
  says: ships the TikTok SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.9
    mcp: &id051
      status: none
    slug: tumblr
    status: profiled
    tags: &id052
    - Public APIs
    - Social
    url: /providers/tumblr/
  layer: domain
  name: Tumblr
  provider: tumblr
  says: ships the Tumblr SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.8
    band: thin
    in_catalog: true
    kin_score: 38.4
    mcp: &id053
      source: https://developer.vimeo.com/api/mcp-server
      status: documented
    slug: vimeo
    status: profiled
    tags: &id054
    - Live Streaming
    - Streaming
    - Video
    - Video Hosting
    url: /providers/vimeo/
  layer: domain
  name: Vimeo
  provider: vimeo
  says: ships the Vimeo SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.4
    band: thin
    in_catalog: true
    kin_score: 38.5
    mcp: &id055
      source: https://www.wolfram.com/artificial-intelligence/mcp/cloud/
      status: verified
    slug: wolframalpha
    status: profiled
    tags: &id056
    - Artificial Intelligence
    - Computational Knowledge
    - Machine Learning
    - Natural Language Processing
    url: /providers/wolframalpha/
  layer: domain
  name: Wolfram Cloud
  provider: wolframalpha
  says: ships the Wolfram Cloud SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id057
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id058
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: ships the X (Twitter) SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.4
    band: strong
    in_catalog: true
    kin_score: 62.6
    mcp: &id059
      status: none
    slug: youtube
    status: profiled
    tags: &id060
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: ships the YouTube SDK or integration code
  source: https://github.com/WordPress/WordPress/blob/master/wp-includes/class-wp-oembed.php
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/website-builder-cms/wordpress/
providers:
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id001
  name: Amazon Kindle Instant Preview
  slug: amazon
  status: profiled
  tags: *id002
  url: /providers/amazon/
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 6.8
  mcp: *id003
  name: Anghami
  slug: anghami
  status: profiled
  tags: *id004
  url: /providers/anghami/
- agent_band: human-only
  agent_readiness: 5.0
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id005
  name: Animoto
  slug: animoto
  status: profiled
  tags: *id006
  url: /providers/animoto/
- agent_band: agent-aware
  agent_readiness: 26.2
  band: developing
  in_catalog: true
  kin_score: 45.1
  mcp: *id007
  name: Bluesky
  slug: bluesky
  status: profiled
  tags: *id008
  url: /providers/bluesky/
- agent_band: agent-native
  agent_readiness: 71.4
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id009
  name: Canva
  slug: canva
  status: profiled
  tags: *id010
  url: /providers/canva/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id011
  name: Cloudup
  slug: cloudup
  status: queued for profiling
  tags: *id012
  url: null
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id013
  name: Crowdsignal
  slug: crowdsignal
  status: queued for profiling
  tags: *id014
  url: null
- agent_band: human-only
  agent_readiness: 3.9
  band: minimal
  in_catalog: true
  kin_score: 8.4
  mcp: *id015
  name: Dailymotion
  slug: dailymotion
  status: profiled
  tags: *id016
  url: /providers/dailymotion/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: developing
  in_catalog: true
  kin_score: 48.6
  mcp: *id017
  name: Flickr
  slug: flickr
  status: profiled
  tags: *id018
  url: /providers/flickr/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 39.8
  mcp: *id019
  name: Gravatar
  slug: gravatar
  status: profiled
  tags: *id020
  url: /providers/gravatar/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id021
  name: Issuu
  slug: issuu
  status: queued for profiling
  tags: *id022
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.4
  mcp: *id023
  name: Kickstarter
  slug: kickstarter
  status: profiled
  tags: *id024
  url: /providers/kickstarter/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id025
  name: Mixcloud
  slug: mixcloud
  status: profiled
  tags: *id026
  url: /providers/mixcloud/
- agent_band: agent-ready
  agent_readiness: 38.4
  band: developing
  in_catalog: true
  kin_score: 49.4
  mcp: *id027
  name: Pinterest
  slug: pinterest
  status: profiled
  tags: *id028
  url: /providers/pinterest/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id029
  name: Pocket Casts
  slug: pocket-casts
  status: queued for profiling
  tags: *id030
  url: null
- agent_band: agent-ready
  agent_readiness: 39.1
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id031
  name: Reddit
  slug: reddit
  status: profiled
  tags: *id032
  url: /providers/reddit/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 11.7
  mcp: *id033
  name: ReverbNation
  slug: reverbnation
  status: profiled
  tags: *id034
  url: /providers/reverbnation/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.2
  mcp: *id035
  name: Scribd
  slug: scribd
  status: profiled
  tags: *id036
  url: /providers/scribd/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id037
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id038
  url: /providers/sentry-system/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 25.0
  mcp: *id039
  name: SmugMug
  slug: smugmug
  status: profiled
  tags: *id040
  url: /providers/smugmug/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 31.0
  mcp: *id041
  name: SoundCloud
  slug: soundcloud
  status: profiled
  tags: *id042
  url: /providers/soundcloud/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.7
  mcp: *id043
  name: Speaker Deck
  slug: speakerdeck
  status: profiled
  tags: *id044
  url: /providers/speakerdeck/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id045
  name: Spotify
  slug: spotify
  status: profiled
  tags: *id046
  url: /providers/spotify/
- agent_band: agent-aware
  agent_readiness: 18.7
  band: emerging
  in_catalog: true
  kin_score: 11.7
  mcp: *id047
  name: TED
  slug: ted-com
  status: profiled
  tags: *id048
  url: /providers/ted-com/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 41.0
  mcp: *id049
  name: TikTok
  slug: tiktok
  status: profiled
  tags: *id050
  url: /providers/tiktok/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id051
  name: Tumblr
  slug: tumblr
  status: profiled
  tags: *id052
  url: /providers/tumblr/
- agent_band: agent-ready
  agent_readiness: 48.8
  band: thin
  in_catalog: true
  kin_score: 38.4
  mcp: *id053
  name: Vimeo
  slug: vimeo
  status: profiled
  tags: *id054
  url: /providers/vimeo/
- agent_band: agent-aware
  agent_readiness: 28.4
  band: thin
  in_catalog: true
  kin_score: 38.5
  mcp: *id055
  name: Wolfram Cloud
  slug: wolframalpha
  status: profiled
  tags: *id056
  url: /providers/wolframalpha/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id057
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id058
  url: /providers/x/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id059
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id060
  url: /providers/youtube/
siblings:
- name: Directus
  rows: 12
  url: /applications/website-builder-cms/directus/
- name: Ghost
  rows: 76
  url: /applications/website-builder-cms/ghost/
- name: Payload
  rows: 9
  url: /applications/website-builder-cms/payload/
- name: Strapi
  rows: 5
  url: /applications/website-builder-cms/strapi/
- name: Webflow
  rows: 17
  url: /applications/website-builder-cms/webflow/
sitemap: true
title: 'WordPress: Website Builder, CMS & Blogging reference app'
---
