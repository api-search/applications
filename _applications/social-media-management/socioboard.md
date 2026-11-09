---
app: Socioboard
app_slug: socioboard
app_url: https://github.com/socioboard/Socioboard-5.0
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-913
  key: AE-913
  layer: domain
  name: Link Shortening & Link-in-Bio
  providers:
  - Bitly
  - TinyURL
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-170.60
  key: AE-170.60
  layer: domain
  name: News & Publishing
  providers:
  - Medium
  url: /capabilities/news-publishing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.60.10
  key: AE-170.60.10
  layer: domain
  name: News Data
  providers:
  - NewsAPI
  url: /capabilities/news-publishing/
  via_parent: News & Publishing
- attribution: API Evangelist extension
  id: AE-170.30
  key: AE-170.30
  layer: domain
  name: Photo & Image Libraries
  providers:
  - Flickr
  - GIPHY
  - Imgur
  - Pixabay
  url: /capabilities/photo-image-libraries/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Facebook
  - Instagram
  - LinkedIn
  - Pinterest
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
  - Dailymotion
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Twilio
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - GitHub
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-3750.20
  key: subscription-entitlement-management
  layer: common
  name: Subscription & Entitlement Management
  providers:
  - aMember
  url: /capabilities/subscription-entitlement-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - SendGrid
  url: /capabilities/email/
  via_parent: Email
category:
  id: social-media-management
  name: Social Media Management & Scheduling
  url: /applications/social-media-management/
counts:
  declared: 0
  observed: 22
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/socioboard-api/Common/package.json
- route: source code
  url: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
- route: source code
  url: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/docker/.env.example
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3750.20
    key: subscription-entitlement-management
    name: Subscription & Entitlement Management
    url: /capabilities/subscription-entitlement-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 17.5
    mcp: &id001
      status: unknown
    slug: amember
    status: profiled
    tags: &id002
    - Membership Software
    - Payment Integration
    - Self-Hosted
    - Subscription Management
    url: /providers/amember/
  layer: common
  name: aMember
  provider: amember
  says: ships the aMember SDK or integration code
  source: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/docker/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.4
    band: exemplar
    in_catalog: true
    kin_score: 73.7
    mcp: &id003
      source: https://dev.bitly.com/bitly-mcp/
      status: verified
    slug: bitly
    status: profiled
    tags: &id004
    - Analytics
    - Links
    - QR Codes
    - URL Shorteners
    url: /providers/bitly/
  layer: domain
  name: Bitly
  provider: bitly
  says: ships the Bitly SDK or integration code
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
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
    mcp: &id005
      status: none
    slug: dailymotion
    status: profiled
    tags: &id006
    - Public APIs
    - Video
    url: /providers/dailymotion/
  layer: domain
  name: Dailymotion
  provider: dailymotion
  says: ships the Dailymotion SDK or integration code
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster/trends.cluster.js
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
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id007
      status: none
    slug: facebook
    status: profiled
    tags: &id008
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
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
    mcp: &id009
      status: none
    slug: flickr
    status: profiled
    tags: &id010
    - Photography
    - Photos
    - Public APIs
    - Social Media
    url: /providers/flickr/
  layer: domain
  name: Flickr
  provider: flickr
  says: ships the Flickr SDK or integration code
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster/trends.cluster.js
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
    agent_readiness: 21.9
    band: strong
    in_catalog: true
    kin_score: 55.6
    mcp: &id011
      status: none
    slug: giphy
    status: profiled
    tags: &id012
    - GIFs
    - Media
    - Photography
    - Stickers
    url: /providers/giphy/
  layer: domain
  name: GIPHY
  provider: giphy
  says: ships the GIPHY SDK or integration code
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster/trends.cluster.js
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
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
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/docker/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
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
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/docker/.env.example
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
    agent_readiness: 21.2
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id017
      status: none
    slug: imgur
    status: profiled
    tags: &id018
    - Albums
    - Image
    - Image Hosting
    - Photography
    url: /providers/imgur/
  layer: domain
  name: Imgur
  provider: imgur
  says: ships the Imgur SDK or integration code
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster/trends.cluster.js
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
    agent_readiness: 38.9
    band: exemplar
    in_catalog: true
    kin_score: 69.0
    mcp: &id019
      status: none
    slug: instagram
    status: profiled
    tags: &id020
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: domain
  name: Instagram
  provider: instagram
  says: ships the Instagram SDK or integration code
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
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
    agent_readiness: 47.4
    band: exemplar
    in_catalog: true
    kin_score: 76.4
    mcp: &id021
      status: none
    slug: linkedin
    status: profiled
    tags: &id022
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: ships the LinkedIn SDK or integration code
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60
    key: AE-170.60
    name: News & Publishing
    url: /capabilities/news-publishing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.0
    band: thin
    in_catalog: true
    kin_score: 36.2
    mcp: &id023
      status: none
    slug: medium
    status: profiled
    tags: &id024
    - Blogging
    - Content
    - Media
    - Publishing
    url: /providers/medium/
  layer: domain
  name: Medium
  provider: medium
  says: ships the Medium SDK or integration code
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.60.10
    key: AE-170.60.10
    name: News Data
    url: /capabilities/news-publishing/
    via_parent: News & Publishing
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.2
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id025
      status: none
    slug: newsapi
    status: profiled
    tags: &id026
    - Articles
    - Headlines
    - News
    - Search
    url: /providers/newsapi/
  layer: domain
  name: NewsAPI
  provider: newsapi
  says: ships the NewsAPI SDK or integration code
  source: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/socioboard-api/Common/package.json
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
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
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
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 13.8
    mcp: &id029
      status: none
    slug: pixabay
    status: profiled
    tags: &id030
    - Illustrations
    - Image
    - Stock Media
    - Video
    url: /providers/pixabay/
  layer: domain
  name: Pixabay
  provider: pixabay
  says: ships the Pixabay SDK or integration code
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster/trends.cluster.js
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.1
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id031
      status: none
    slug: sendgrid
    status: profiled
    tags: &id032
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: common
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/socioboard-api/Common/package.json
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
    mcp: &id033
      status: none
    slug: tiktok
    status: profiled
    tags: &id034
    - Advertising
    - Commerce
    - Content
    - TikTok
    url: /providers/tiktok/
  layer: domain
  name: TikTok
  provider: tiktok
  says: ships the TikTok SDK or integration code
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id035
      status: none
    slug: tinyurl
    status: profiled
    tags: &id036
    - Public APIs
    - URL Shorteners
    url: /providers/tinyurl/
  layer: domain
  name: TinyURL
  provider: tinyurl
  says: ships the TinyURL SDK or integration code
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
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
    mcp: &id037
      status: none
    slug: tumblr
    status: profiled
    tags: &id038
    - Public APIs
    - Social
    url: /providers/tumblr/
  layer: domain
  name: Tumblr
  provider: tumblr
  says: ships the Tumblr SDK or integration code
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.4
    band: exemplar
    in_catalog: true
    kin_score: 90.3
    mcp: &id039
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id040
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: common
  name: Twilio
  provider: twilio
  says: ships the Twilio SDK or integration code
  source: https://raw.githubusercontent.com/socioboard/Socioboard-5.0/master/socioboard-api/Common/package.json
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
  says: ships the X (Twitter) SDK or integration code
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
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
    mcp: &id043
      status: none
    slug: youtube
    status: profiled
    tags: &id044
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: ships the YouTube SDK or integration code
  source: https://github.com/socioboard/Socioboard-5.0/tree/master/socioboard-api/Common/Cluster
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/social-media-management/socioboard/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 17.5
  mcp: *id001
  name: aMember
  slug: amember
  status: profiled
  tags: *id002
  url: /providers/amember/
- agent_band: agent-ready
  agent_readiness: 59.4
  band: exemplar
  in_catalog: true
  kin_score: 73.7
  mcp: *id003
  name: Bitly
  slug: bitly
  status: profiled
  tags: *id004
  url: /providers/bitly/
- agent_band: human-only
  agent_readiness: 3.9
  band: minimal
  in_catalog: true
  kin_score: 8.4
  mcp: *id005
  name: Dailymotion
  slug: dailymotion
  status: profiled
  tags: *id006
  url: /providers/dailymotion/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id007
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id008
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: developing
  in_catalog: true
  kin_score: 48.6
  mcp: *id009
  name: Flickr
  slug: flickr
  status: profiled
  tags: *id010
  url: /providers/flickr/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: strong
  in_catalog: true
  kin_score: 55.6
  mcp: *id011
  name: GIPHY
  slug: giphy
  status: profiled
  tags: *id012
  url: /providers/giphy/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id013
  name: GitHub
  slug: github
  status: profiled
  tags: *id014
  url: /providers/github/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id015
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id016
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 21.2
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id017
  name: Imgur
  slug: imgur
  status: profiled
  tags: *id018
  url: /providers/imgur/
- agent_band: agent-ready
  agent_readiness: 38.9
  band: exemplar
  in_catalog: true
  kin_score: 69.0
  mcp: *id019
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id020
  url: /providers/instagram/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: exemplar
  in_catalog: true
  kin_score: 76.4
  mcp: *id021
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id022
  url: /providers/linkedin/
- agent_band: agent-aware
  agent_readiness: 27.0
  band: thin
  in_catalog: true
  kin_score: 36.2
  mcp: *id023
  name: Medium
  slug: medium
  status: profiled
  tags: *id024
  url: /providers/medium/
- agent_band: agent-ready
  agent_readiness: 33.2
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id025
  name: NewsAPI
  slug: newsapi
  status: profiled
  tags: *id026
  url: /providers/newsapi/
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
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 13.8
  mcp: *id029
  name: Pixabay
  slug: pixabay
  status: profiled
  tags: *id030
  url: /providers/pixabay/
- agent_band: agent-ready
  agent_readiness: 40.1
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id031
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id032
  url: /providers/sendgrid/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 41.0
  mcp: *id033
  name: TikTok
  slug: tiktok
  status: profiled
  tags: *id034
  url: /providers/tiktok/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id035
  name: TinyURL
  slug: tinyurl
  status: profiled
  tags: *id036
  url: /providers/tinyurl/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.9
  mcp: *id037
  name: Tumblr
  slug: tumblr
  status: profiled
  tags: *id038
  url: /providers/tumblr/
- agent_band: agent-native
  agent_readiness: 56.4
  band: exemplar
  in_catalog: true
  kin_score: 90.3
  mcp: *id039
  name: Twilio
  slug: twilio
  status: profiled
  tags: *id040
  url: /providers/twilio/
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
- agent_band: agent-ready
  agent_readiness: 43.4
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id043
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id044
  url: /providers/youtube/
siblings:
- name: Buffer
  rows: 39
  url: /applications/social-media-management/buffer/
- name: Hootsuite
  rows: 42
  url: /applications/social-media-management/hootsuite/
- name: Mixpost
  rows: 5
  url: /applications/social-media-management/mixpost/
- name: Planoly
  rows: 8
  url: /applications/social-media-management/planoly/
- name: Postiz
  rows: 57
  url: /applications/social-media-management/postiz/
- name: Sprout Social
  rows: 43
  url: /applications/social-media-management/sprout-social/
sitemap: true
title: 'Socioboard: Social Media Management & Scheduling reference app'
---
