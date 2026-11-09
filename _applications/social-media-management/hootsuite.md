---
app: Hootsuite
app_slug: hootsuite
app_url: https://www.hootsuite.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3780
  key: content-compliance-standards-management
  layer: domain
  name: Content Compliance & Standards Management
  providers:
  - Proofpoint
  url: /capabilities/content-compliance-standards-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - WordPress
  url: /capabilities/content-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.70
  key: content-marketing-management
  layer: domain
  name: Content Marketing Management
  providers:
  - Acquia
  url: /capabilities/content-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: domain
  name: Design & Creative Editing
  providers:
  - Adobe Express
  - Canva
  - Figma
  - Miro
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.30.10
  key: AE-170.30.10
  layer: domain
  name: Image Processing & Optimisation
  providers:
  - Cloudinary
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: API Evangelist extension
  id: AE-913
  key: AE-913
  layer: domain
  name: Link Shortening & Link-in-Bio
  providers:
  - OneClick.bio
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: Turbo EA
  id: BC-420.40
  key: loyalty-retention-management
  layer: domain
  name: Loyalty & Retention Management
  providers:
  - TrueLoyal
  url: /capabilities/loyalty-retention-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710
  key: media-asset-management
  layer: domain
  name: Media Asset Management
  providers:
  - Bynder
  url: /capabilities/media-asset-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.50.10
  key: AE-170.50.10
  layer: domain
  name: Online Communities
  providers:
  - Dribbble
  url: /capabilities/social-networks-community/
  via_parent: Social Networks & Community
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: domain
  name: Reviews & Social Proof
  providers:
  - Google Business Profile
  - ReviewTrackers
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.70
  key: AE-140.70
  layer: domain
  name: Social & Creator Commerce
  providers:
  - Upfluence
  url: /capabilities/social-creator-commerce/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-914
  key: AE-914
  layer: domain
  name: Social Listening & Analytics
  providers:
  - Fedica
  - Panoramiq Insights
  - Talkwalker
  url: /capabilities/digital-marketing-management/
  via_parent: Digital Marketing Management
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: domain
  name: Social Networks & Community
  providers:
  - Facebook
  - Bluesky
  - Instagram
  - LinkedIn
  - Pinterest
  - Threads
  - TikTok
  - X (Twitter)
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: domain
  name: Team Chat Bridging
  providers:
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-110.20.20
  key: AE-110.20.20
  layer: domain
  name: Video Generation
  providers:
  - Lumen5
  url: /capabilities/generative-media/
  via_parent: Generative Media
- attribution: API Evangelist extension
  id: AE-170.10.10
  key: AE-170.10.10
  layer: domain
  name: Video Hosting & Encoding
  providers:
  - Brightcove
  - Vidyard
  - Vimeo
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
- attribution: API Evangelist extension
  id: AE-170.10
  key: AE-170.10
  layer: domain
  name: Video Platforms
  providers:
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - WhatsApp
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase
  - Mixpanel
  - Pendo
  - Wootric
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - monday.com
  - Wrike
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Airship (Urban Airship)
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.70
  key: AE-150.70
  layer: common
  name: Realtime Messaging
  providers:
  - Pusher
  url: /capabilities/realtime-messaging/
  via_parent: null
category:
  id: social-media-management
  name: Social Media Management & Scheduling
  url: /applications/social-media-management/
counts:
  declared: 35
  observed: 7
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
- route: integrations page
  url: https://apps.hootsuite.com/
- route: integrations page
  url: https://www.hootsuite.com/platform/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id005
      source: https://github.com/urbanairship/agent-tools
      status: verified
    slug: airship
    status: profiled
    tags: &id006
    - Email
    - Mobile
    - Notification
    - Push
    url: /providers/airship/
  layer: common
  name: Airship (Urban Airship)
  provider: airship
  says: ships the Airship (Urban Airship) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id019
      status: none
    slug: facebook
    status: profiled
    tags: &id020
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
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
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id025
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id026
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
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
    agent_readiness: 48.3
    band: strong
    in_catalog: true
    kin_score: 60.3
    mcp: &id037
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id038
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: common
  name: Mixpanel
  provider: mixpanel
  says: ships the Mixpanel SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
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
    agent_readiness: 35.4
    band: strong
    in_catalog: true
    kin_score: 56.4
    mcp: &id045
      source: https://support.pendo.io/hc/en-us/articles/41102236924955
      status: verified
    slug: pendoio
    status: profiled
    tags: &id046
    - Company
    - Digital Adoption
    - Product Analytics
    - Product Experience
    url: /providers/pendoio/
  layer: common
  name: Pendo
  provider: pendoio
  says: ships the Pendo SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id051
      status: none
    slug: pusher
    status: profiled
    tags: &id052
    - Pub/Sub
    - Push Notifications
    - Real-Time
    - WebSocket
    url: /providers/pusher/
  layer: common
  name: Pusher
  provider: pusher
  says: ships the Pusher SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
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
    agent_band: agent-aware
    agent_readiness: 20.7
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id075
      status: none
    slug: wootric
    status: profiled
    tags: &id076
    - CES
    - CSAT
    - Customer Experience
    - NPS
    url: /providers/wootric/
  layer: common
  name: Wootric
  provider: wootric
  says: ships the Wootric SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.hootsuite.droid.full/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-400.70
    key: content-marketing-management
    name: Content Marketing Management
    url: /capabilities/content-marketing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.7
    band: exemplar
    in_catalog: true
    kin_score: 75.5
    mcp: &id001
      status: none
    slug: acquia
    status: profiled
    tags: &id002
    - Content
    - DXP
    - Drupal
    - Experience
    url: /providers/acquia/
  layer: domain
  name: Acquia
  provider: acquia
  says: lists Acquia as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id003
      status: unchecked
    slug: adobe-express
    status: queued for profiling
    tags: &id004 []
    url: null
  layer: domain
  name: Adobe Express
  provider: adobe-express
  says: lists Adobe Express as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
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
  says: lists Bluesky as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: thin
    in_catalog: true
    kin_score: 35.0
    mcp: &id009
      status: none
    slug: brightcove
    status: profiled
    tags: &id010
    - Live Streaming
    - Media
    - Streaming
    - Video
    url: /providers/brightcove/
  layer: domain
  name: Brightcove
  provider: brightcove
  says: lists Brightcove as an integration
  source: https://apps.hootsuite.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3710
    key: media-asset-management
    name: Media Asset Management
    url: /capabilities/media-asset-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.6
    band: exemplar
    in_catalog: true
    kin_score: 67.6
    mcp: &id011
      status: none
    slug: bynder
    status: profiled
    tags: &id012
    - Brand Management
    - Content Management
    - Digital Asset Management
    - Marketing
    url: /providers/bynder/
  layer: domain
  name: Bynder
  provider: bynder
  says: lists Bynder as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
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
    mcp: &id013
      source: https://www.canva.dev/docs/mcp/
      status: verified
    slug: canva
    status: profiled
    tags: &id014
    - Application
    - Automation
    - Brand Management
    - Collaboration
    url: /providers/canva/
  layer: domain
  name: Canva
  provider: canva
  says: lists Canva as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.10
    key: AE-170.30.10
    name: Image Processing & Optimisation
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.0
    band: developing
    in_catalog: true
    kin_score: 52.4
    mcp: &id015
      source: https://cloudinary.com/documentation/cloudinary_llm_mcp
      status: verified
    slug: cloudinary
    status: profiled
    tags: &id016
    - Asset Management
    - Digital Asset Management
    - Image Processing
    - Image Transformation
    url: /providers/cloudinary/
  layer: domain
  name: Cloudinary
  provider: cloudinary
  says: lists Cloudinary as an integration
  source: https://apps.hootsuite.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.10
    key: AE-170.50.10
    name: Online Communities
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.6
    mcp: &id017
      status: none
    slug: dribbble
    status: profiled
    tags: &id018
    - Design
    - Public APIs
    url: /providers/dribbble/
  layer: domain
  name: Dribbble
  provider: dribbble
  says: lists Dribbble as an integration
  source: https://apps.hootsuite.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-914
    key: AE-914
    name: Social Listening & Analytics
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.4
    band: minimal
    in_catalog: true
    kin_score: 6.8
    mcp: &id021
      source: https://mcp.fedica.com/.well-known/oauth-protected-resource/mcp
      status: verified
    slug: fedica
    status: profiled
    tags: &id022
    - Analytics
    - Company
    - Marketing
    - Social Media
    url: /providers/fedica/
  layer: domain
  name: Fedica
  provider: fedica
  says: lists Fedica as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 57.8
    band: strong
    in_catalog: true
    kin_score: 65.6
    mcp: &id023
      source: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server
      status: verified
    slug: figma
    status: profiled
    tags: &id024
    - Collaboration
    - Design
    - Graphics
    - Interfaces
    url: /providers/figma/
  layer: domain
  name: Figma
  provider: figma
  says: lists Figma as an integration
  source: https://apps.hootsuite.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id027
      status: none
    slug: google-business-profile
    status: profiled
    tags: &id028
    - Business Profiles
    - Google
    - Local Business
    - Location
    url: /providers/google-business-profile/
  layer: domain
  name: Google Business Profile
  provider: google-business-profile
  says: lists Google Business Profile as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
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
    mcp: &id029
      status: none
    slug: instagram
    status: profiled
    tags: &id030
    - Instagram
    - Meta
    - Photos
    - Social Media
    url: /providers/instagram/
  layer: domain
  name: Instagram
  provider: instagram
  says: lists Instagram as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
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
    mcp: &id031
      status: none
    slug: linkedin
    status: profiled
    tags: &id032
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: lists LinkedIn as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.20.20
    key: AE-110.20.20
    name: Video Generation
    url: /capabilities/generative-media/
    via_parent: Generative Media
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.9
    band: thin
    in_catalog: true
    kin_score: 29.8
    mcp: &id033
      status: none
    slug: lumen5
    status: profiled
    tags: &id034
    - Company
    url: /providers/lumen5/
  layer: domain
  name: Lumen5
  provider: lumen5
  says: lists Lumen5 as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.1
    band: developing
    in_catalog: true
    kin_score: 46.4
    mcp: &id035
      source: https://developers.miro.com/docs/miro-mcp
      status: verified
    slug: miro
    status: profiled
    tags: &id036
    - Diagramming
    - Productivity
    - Visual Collaboration
    - Whiteboard
    url: /providers/miro/
  layer: domain
  name: Miro
  provider: miro
  says: lists Miro as an integration
  source: https://apps.hootsuite.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.3
    band: thin
    in_catalog: true
    kin_score: 33.6
    mcp: &id039
      source: https://github.com/mondaycom/mcp
      status: verified
    slug: monday-com
    status: profiled
    tags: &id040
    - Automation
    - CRM
    - GraphQL
    - Work Management
    url: /providers/monday-com/
  layer: common
  name: monday.com
  provider: monday-com
  says: lists monday.com as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-913
    key: AE-913
    name: Link Shortening & Link-in-Bio
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id041
      status: unchecked
    slug: oneclick-bio
    status: queued for profiling
    tags: &id042 []
    url: null
  layer: domain
  name: OneClick.bio
  provider: oneclick-bio
  says: lists OneClick.bio as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-914
    key: AE-914
    name: Social Listening & Analytics
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: minimal
    in_catalog: true
    kin_score: 2.2
    mcp: &id043
      status: unknown
    slug: panoramiq
    status: profiled
    tags: &id044
    - Company
    url: /providers/panoramiq/
  layer: domain
  name: Panoramiq Insights
  provider: panoramiq
  says: lists Panoramiq Insights as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
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
    mcp: &id047
      source: https://developers.pinterest.com/about-pinterest-mcp/
      status: verified
    slug: pinterest
    status: profiled
    tags: &id048
    - Image
    - Social
    - Social Media
    - Video
    url: /providers/pinterest/
  layer: domain
  name: Pinterest
  provider: pinterest
  says: lists Pinterest as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-3780
    key: content-compliance-standards-management
    name: Content Compliance & Standards Management
    url: /capabilities/content-compliance-standards-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 7.9
    band: developing
    in_catalog: true
    kin_score: 40.1
    mcp: &id049
      status: none
    slug: proofpoint
    status: profiled
    tags: &id050
    - Cybersecurity
    - Email Security
    - Security
    - Threat Intelligence
    url: /providers/proofpoint/
  layer: domain
  name: Proofpoint
  provider: proofpoint
  says: lists Proofpoint as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: strong
    in_catalog: true
    kin_score: 55.9
    mcp: &id053
      status: none
    slug: reviewtrackers
    status: profiled
    tags: &id054
    - Customer Feedback
    - Reputation Management
    - Review Monitoring
    - Sentiment Analytics
    url: /providers/reviewtrackers/
  layer: domain
  name: ReviewTrackers
  provider: reviewtrackers
  says: lists ReviewTrackers as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
    mcp: &id055
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id056
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id057
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id058
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-914
    key: AE-914
    name: Social Listening & Analytics
    url: /capabilities/digital-marketing-management/
    via_parent: Digital Marketing Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.3
    band: strong
    in_catalog: true
    kin_score: 54.8
    mcp: &id059
      status: none
    slug: talkwalker
    status: profiled
    tags: &id060
    - Brand Monitoring
    - Sentiment Analysis
    - Social Listening
    - Social Media Analytics
    url: /providers/talkwalker/
  layer: domain
  name: Talkwalker
  provider: talkwalker
  says: lists Talkwalker as an integration
  source: https://apps.hootsuite.com/
  tier: declared
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
    agent_readiness: 28.4
    band: developing
    in_catalog: true
    kin_score: 43.1
    mcp: &id061
      status: none
    slug: threads-api
    status: profiled
    tags: &id062
    - Meta
    - Publishing
    - Social
    - Social Network
    url: /providers/threads-api/
  layer: domain
  name: Threads
  provider: threads-api
  says: lists Threads as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
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
    mcp: &id063
      status: none
    slug: tiktok
    status: profiled
    tags: &id064
    - Advertising
    - Commerce
    - Content
    - TikTok
    url: /providers/tiktok/
  layer: domain
  name: TikTok
  provider: tiktok
  says: lists TikTok as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420.40
    key: loyalty-retention-management
    name: Loyalty & Retention Management
    url: /capabilities/loyalty-retention-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id065
      source: https://www.trueloyal.com/mcp
      status: documented
    slug: trueloyal
    status: profiled
    tags: &id066
    - Loyalty
    - Platform
    - Retail
    - Software-as-a-Service
    url: /providers/trueloyal/
  layer: domain
  name: TrueLoyal
  provider: trueloyal
  says: lists TrueLoyal as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.70
    key: AE-140.70
    name: Social & Creator Commerce
    url: /capabilities/social-creator-commerce/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.6
    band: emerging
    in_catalog: true
    kin_score: 20.2
    mcp: &id067
      status: none
    slug: upfluence
    status: profiled
    tags: &id068
    - Company
    - Influencer Marketing
    - MCP
    - Software-as-a-Service
    url: /providers/upfluence/
  layer: domain
  name: Upfluence
  provider: upfluence
  says: lists Upfluence as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: exemplar
    in_catalog: true
    kin_score: 71.1
    mcp: &id069
      status: none
    slug: vidyard
    status: profiled
    tags: &id070
    - Video
    - Video Analytics
    - Video Platform
    - Video Sharing
    url: /providers/vidyard/
  layer: domain
  name: Vidyard
  provider: vidyard
  says: lists Vidyard as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.8
    band: thin
    in_catalog: true
    kin_score: 38.4
    mcp: &id071
      source: https://developer.vimeo.com/api/mcp-server
      status: documented
    slug: vimeo
    status: profiled
    tags: &id072
    - Live Streaming
    - Streaming
    - Video
    - Video Hosting
    url: /providers/vimeo/
  layer: domain
  name: Vimeo
  provider: vimeo
  says: lists Vimeo as an integration
  source: https://apps.hootsuite.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.0
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id073
      status: none
    slug: whatsapp
    status: profiled
    tags: &id074
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: domain
  name: WhatsApp
  provider: whatsapp
  says: lists WhatsApp as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.4
    band: developing
    in_catalog: true
    kin_score: 46.0
    mcp: &id077
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id078
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: domain
  name: WordPress
  provider: wordpress
  says: lists WordPress as an integration
  source: https://apps.hootsuite.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 52.6
    mcp: &id079
      source: https://github.com/wrike/datahub-mcp
      status: verified
    slug: wrike
    status: profiled
    tags: &id080
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/wrike/
  layer: common
  name: Wrike
  provider: wrike
  says: lists Wrike as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
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
    mcp: &id081
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id082
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: X (Twitter)
  provider: x
  says: lists X (Twitter) as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
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
    mcp: &id083
      status: none
    slug: youtube
    status: profiled
    tags: &id084
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: lists YouTube as an integration
  source: https://www.hootsuite.com/platform/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/social-media-management/hootsuite/
providers:
- agent_band: agent-ready
  agent_readiness: 62.7
  band: exemplar
  in_catalog: true
  kin_score: 75.5
  mcp: *id001
  name: Acquia
  slug: acquia
  status: profiled
  tags: *id002
  url: /providers/acquia/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id003
  name: Adobe Express
  slug: adobe-express
  status: queued for profiling
  tags: *id004
  url: null
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id005
  name: Airship (Urban Airship)
  slug: airship
  status: profiled
  tags: *id006
  url: /providers/airship/
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
- agent_band: agent-ready
  agent_readiness: 30.1
  band: thin
  in_catalog: true
  kin_score: 35.0
  mcp: *id009
  name: Brightcove
  slug: brightcove
  status: profiled
  tags: *id010
  url: /providers/brightcove/
- agent_band: agent-ready
  agent_readiness: 38.6
  band: exemplar
  in_catalog: true
  kin_score: 67.6
  mcp: *id011
  name: Bynder
  slug: bynder
  status: profiled
  tags: *id012
  url: /providers/bynder/
- agent_band: agent-native
  agent_readiness: 71.4
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id013
  name: Canva
  slug: canva
  status: profiled
  tags: *id014
  url: /providers/canva/
- agent_band: agent-ready
  agent_readiness: 45.0
  band: developing
  in_catalog: true
  kin_score: 52.4
  mcp: *id015
  name: Cloudinary
  slug: cloudinary
  status: profiled
  tags: *id016
  url: /providers/cloudinary/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.6
  mcp: *id017
  name: Dribbble
  slug: dribbble
  status: profiled
  tags: *id018
  url: /providers/dribbble/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id019
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id020
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: minimal
  in_catalog: true
  kin_score: 6.8
  mcp: *id021
  name: Fedica
  slug: fedica
  status: profiled
  tags: *id022
  url: /providers/fedica/
- agent_band: agent-ready
  agent_readiness: 57.8
  band: strong
  in_catalog: true
  kin_score: 65.6
  mcp: *id023
  name: Figma
  slug: figma
  status: profiled
  tags: *id024
  url: /providers/figma/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id025
  name: Firebase
  slug: firebase
  status: profiled
  tags: *id026
  url: /providers/firebase/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id027
  name: Google Business Profile
  slug: google-business-profile
  status: profiled
  tags: *id028
  url: /providers/google-business-profile/
- agent_band: agent-ready
  agent_readiness: 38.9
  band: exemplar
  in_catalog: true
  kin_score: 69.0
  mcp: *id029
  name: Instagram
  slug: instagram
  status: profiled
  tags: *id030
  url: /providers/instagram/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: exemplar
  in_catalog: true
  kin_score: 76.4
  mcp: *id031
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id032
  url: /providers/linkedin/
- agent_band: agent-ready
  agent_readiness: 43.9
  band: thin
  in_catalog: true
  kin_score: 29.8
  mcp: *id033
  name: Lumen5
  slug: lumen5
  status: profiled
  tags: *id034
  url: /providers/lumen5/
- agent_band: agent-ready
  agent_readiness: 39.1
  band: developing
  in_catalog: true
  kin_score: 46.4
  mcp: *id035
  name: Miro
  slug: miro
  status: profiled
  tags: *id036
  url: /providers/miro/
- agent_band: agent-ready
  agent_readiness: 48.3
  band: strong
  in_catalog: true
  kin_score: 60.3
  mcp: *id037
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id038
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id039
  name: monday.com
  slug: monday-com
  status: profiled
  tags: *id040
  url: /providers/monday-com/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id041
  name: OneClick.bio
  slug: oneclick-bio
  status: queued for profiling
  tags: *id042
  url: null
- agent_band: human-only
  agent_readiness: 2.9
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id043
  name: Panoramiq Insights
  slug: panoramiq
  status: profiled
  tags: *id044
  url: /providers/panoramiq/
- agent_band: agent-ready
  agent_readiness: 35.4
  band: strong
  in_catalog: true
  kin_score: 56.4
  mcp: *id045
  name: Pendo
  slug: pendoio
  status: profiled
  tags: *id046
  url: /providers/pendoio/
- agent_band: agent-ready
  agent_readiness: 38.4
  band: developing
  in_catalog: true
  kin_score: 49.4
  mcp: *id047
  name: Pinterest
  slug: pinterest
  status: profiled
  tags: *id048
  url: /providers/pinterest/
- agent_band: agent-aware
  agent_readiness: 7.9
  band: developing
  in_catalog: true
  kin_score: 40.1
  mcp: *id049
  name: Proofpoint
  slug: proofpoint
  status: profiled
  tags: *id050
  url: /providers/proofpoint/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id051
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id052
  url: /providers/pusher/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: strong
  in_catalog: true
  kin_score: 55.9
  mcp: *id053
  name: ReviewTrackers
  slug: reviewtrackers
  status: profiled
  tags: *id054
  url: /providers/reviewtrackers/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id055
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id056
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id057
  name: Slack
  slug: slack
  status: profiled
  tags: *id058
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 28.3
  band: strong
  in_catalog: true
  kin_score: 54.8
  mcp: *id059
  name: Talkwalker
  slug: talkwalker
  status: profiled
  tags: *id060
  url: /providers/talkwalker/
- agent_band: agent-aware
  agent_readiness: 28.4
  band: developing
  in_catalog: true
  kin_score: 43.1
  mcp: *id061
  name: Threads
  slug: threads-api
  status: profiled
  tags: *id062
  url: /providers/threads-api/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 41.0
  mcp: *id063
  name: TikTok
  slug: tiktok
  status: profiled
  tags: *id064
  url: /providers/tiktok/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id065
  name: TrueLoyal
  slug: trueloyal
  status: profiled
  tags: *id066
  url: /providers/trueloyal/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: emerging
  in_catalog: true
  kin_score: 20.2
  mcp: *id067
  name: Upfluence
  slug: upfluence
  status: profiled
  tags: *id068
  url: /providers/upfluence/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: exemplar
  in_catalog: true
  kin_score: 71.1
  mcp: *id069
  name: Vidyard
  slug: vidyard
  status: profiled
  tags: *id070
  url: /providers/vidyard/
- agent_band: agent-ready
  agent_readiness: 48.8
  band: thin
  in_catalog: true
  kin_score: 38.4
  mcp: *id071
  name: Vimeo
  slug: vimeo
  status: profiled
  tags: *id072
  url: /providers/vimeo/
- agent_band: agent-ready
  agent_readiness: 48.0
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id073
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id074
  url: /providers/whatsapp/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id075
  name: Wootric
  slug: wootric
  status: profiled
  tags: *id076
  url: /providers/wootric/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: developing
  in_catalog: true
  kin_score: 46.0
  mcp: *id077
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id078
  url: /providers/wordpress/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 52.6
  mcp: *id079
  name: Wrike
  slug: wrike
  status: profiled
  tags: *id080
  url: /providers/wrike/
- agent_band: agent-native
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id081
  name: X (Twitter)
  slug: x
  status: profiled
  tags: *id082
  url: /providers/x/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: strong
  in_catalog: true
  kin_score: 62.6
  mcp: *id083
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id084
  url: /providers/youtube/
siblings:
- name: Buffer
  rows: 39
  url: /applications/social-media-management/buffer/
- name: Mixpost
  rows: 5
  url: /applications/social-media-management/mixpost/
- name: Planoly
  rows: 8
  url: /applications/social-media-management/planoly/
- name: Postiz
  rows: 57
  url: /applications/social-media-management/postiz/
- name: Socioboard
  rows: 22
  url: /applications/social-media-management/socioboard/
- name: Sprout Social
  rows: 43
  url: /applications/social-media-management/sprout-social/
sitemap: true
title: 'Hootsuite: Social Media Management & Scheduling reference app'
---
